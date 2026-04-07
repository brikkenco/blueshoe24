# blueshoe24 — Landing Page

A desktop landing page concept for blueshoe24, built as a single-file HTML/CSS/JS prototype.

## Features

- Lottie splash screen animation on load
- Hero section with staggered fade-up entrance
- Scroll-reveal animations on all major sections
- Interactive pillar chart (gauge + animated line chart)
- Reputation chart with animated progress bar
- Responsive nav and footer matching the THE website style
- Single file — no build tool or framework required

## Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
   cd YOUR_REPO
   ```

2. Open `index.html` directly in a browser, or serve locally:
   ```bash
   npx serve .
   # or
   python3 -m http.server 8080
   ```

> **Note on the hero video:** `images/THE-Promo-SHORT.mp4` is excluded from this repo because it exceeds GitHub's 100 MB file limit. To restore the video, add the MP4 back to `images/` — the page degrades gracefully without it.

## Deploy to GitHub Pages

1. Push to GitHub.
2. Go to **Settings → Pages** in your repo.
3. Under **Source**, select the `main` branch and `/ (root)`.
4. Save — your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO/`.

## Assets

| File | Description |
|------|-------------|
| `index.html` | Entire page — HTML, CSS, and JS |
| `THE-Logo3.json` | Lottie animation for the splash screen |
| `images/` | Screenshots, feature images, university logos |

## Dependencies (CDN — no install needed)

- [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts
- [Lottie Web](https://github.com/airbnb/lottie-web) via cdnjs
