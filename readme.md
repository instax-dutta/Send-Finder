# 🌌 Send Server Finder — Private File Sharing Made Simple

[![Vercel Deployment](https://img.shields.io/badge/Deploy-Vercel-black?logo=vercel&logoColor=white)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Finstax-dutta%2FSend-Finder)
[![Netlify Deployment](https://img.shields.io/badge/Deploy-Netlify-00C4B4?logo=netlify&logoColor=white)](https://app.netlify.com/start/deploy?repository=https://github.com/instax-dutta/Send-Finder)
[![License: MIT](https://img.shields.io/badge/License-MIT-cyan.svg)](https://opensource.org/licenses/MIT)
[![Privacy: Built-in](https://img.shields.io/badge/Privacy-Zero--Knowledge-brightgreen.svg)](#-zero-knowledge-privacy-promise)

Find the fastest private server near you to share encrypted files. We automatically check 23+ secure, community-hosted **Send** servers for speed and rank them instantly.

**Live Site → [sf.sdad.pro](https://sf.sdad.pro)**

![Send Server Finder Dashboard](assets/preview.jpg)

---

## ⚡️ Find the Best Server in 2 Seconds

Sharing files on the decentralized web shouldn't mean guessing which server is online or closest. **Send Server Finder** benchmarks all active servers directly from your browser, taking the guesswork out of secure file sharing.

*   **Zero-Knowledge Privacy** — Files are encrypted in your browser *before* uploading. Nobody—not even the server owner—can read them.
*   **Automatic Benchmarking** — Checks all public servers in parallel as soon as you open the page.
*   **Interactive 3D Speed Map** — A beautiful, real-time WebGL globe maps server locations and highlights the fastest paths.
*   **Smart Network Handling** — Servers are tested in batches to prevent network congestion from skewing results.
*   **Fastest Option Highlighted** — The top 3 fastest, healthiest servers are visually marked. Copy the recommended address in a single click.
*   **Persistent & Light** — Smart 5-minute local cache avoids redundant tests if you refresh the page.

---

## 🔒 Zero-Knowledge Privacy Promise

Your security is our absolute priority. This utility operates under strict privacy-first guardrails:

1.  **Fully Client-Side**: 100% of the testing and routing happens in your browser. There is no tracking, no backend database, and no cookies.
2.  **Zero File Access**: This finder is a directory tool. It helps you select the best server; your actual files never pass through this utility.
3.  **Local Encryption**: The target **Send** servers use native client-side encryption. The host only stores encrypted blocks of data and has zero access to your decryption keys.

---

## 🚀 Deploy Your Own in 60 Seconds (IKEA Effect)

Want your own branded file sharing server finder? You can deploy this entire dashboard to Vercel or Netlify with a single click. No databases to set up, zero maintenance.

### One-Click Deployments

| Platform | Quick Link |
| :--- | :--- |
| **Vercel** | [![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Finstax-dutta%2FSend-Finder) |
| **Netlify** | [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/instax-dutta/Send-Finder) |

### Manual Setup

This application is built with zero-dependency vanilla technologies. To host it anywhere manually:

1.  Clone this repository: `git clone https://github.com/instax-dutta/Send-Finder.git`
2.  Upload `index.html`, `assets/`, `vercel.json` (for Vercel), and `_headers` (for Netlify) to your static hosting provider.
3.  Point your domain to your provider. Done!

---

## 🛠️ The Tech Stack

| Layer | Technology | Why We Chose It |
| :--- | :--- | :--- |
| **Frontend** | HTML5, CSS3, Vanilla ES6 JavaScript | Zero build step, instant load time, maximum client-side performance. |
| **3D Globe** | WebGL / Three.js | High-performance, low-polygon graphics that run smoothly on mobile devices. |
| **Fonts** | Space Grotesk (headings) & JetBrains Mono (data) | Futuristic aesthetic meets highly readable tabular information. |
| **Security** | Strict CSP, X-Frame-Options, HSTS | Standard-setting browser security headers to block cross-site scripting (XSS). |

---

## 🌎 Data Source & Community Credits

The list of active servers is fetched live and synced with the canonical database at [timvisee/send-instances](https://github.com/timvisee/send-instances).

### What is "Send"?
[Send](https://github.com/timvisee/send) is a modernized, community-maintained fork of Mozilla's discontinued **Firefox Send** project. It provides end-to-end encrypted file sharing with self-destructing links, download counters, and custom passwords.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE). Feel free to fork, modify, and distribute as you wish!
