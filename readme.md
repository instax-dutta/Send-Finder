# Send Instance Finder

> Measure latency to every public [Send](https://github.com/timvisee/send) instance and find the fastest encrypted file-sharing server near you.

**Live → [sf.sdad.pro](https://sf.sdad.pro)**

---

## What It Does

Send Instance Finder benchmarks **23 public Send instances** directly from your browser and ranks them by response time so you always pick the fastest one.

- **Auto-tests on page load** — results appear instantly
- **Cached results** — 5-minute localStorage cache avoids redundant re-tests
- **Batched testing** — instances are tested in groups of 6 to reduce network congestion
- **Top 3 highlighted** — fastest instances are visually marked
- **One-click copy** — grab the recommended instance URL instantly
- **Fully client-side** — no backend, no tracking, no data leaves your browser

## Design

Built with the **Minimal Futurism** design system:

- Dark mode (`hsl(0 0% 7%)` background)
- Cyan/teal accent (`hsl(185 85% 42%)`)
- JetBrains Mono (body) + Space Grotesk (headings)
- Sharp 2px border radius
- Subtle glow effects, background grid, scan-line animation
- `prefers-reduced-motion` respected

## Tech Stack

| Layer | Tech |
|-------|------|
| Frontend | Vanilla HTML / CSS / JS (single file) |
| Fonts | Google Fonts (JetBrains Mono, Space Grotesk) |
| Hosting | Netlify |
| Security | CSP, X-Frame-Options, HSTS-ready headers |
| SEO | JSON-LD, OpenGraph, Twitter Cards |

## Deploy

### Netlify (recommended)

1. Push to GitHub
2. Connect repo in [Netlify](https://app.netlify.com)
3. Deploy settings:
   - **Build command:** _(leave empty)_
   - **Publish directory:** `.`
4. Set custom domain to `sf.sdad.pro`

### Manual

Just serve `index.html` from any static host. No build step required.

## Instance Data

The list of 23 instances is sourced from [timvisee/send-instances](https://github.com/timvisee/send-instances). Each entry includes:

- URL, max file size, time limit, download limit, country + flag

## About Send

[Send](https://github.com/timvisee/send) is a fork of Mozilla's discontinued Firefox Send. It provides end-to-end encrypted file sharing with self-destructing links, download limits, and password protection.

## License

MIT
