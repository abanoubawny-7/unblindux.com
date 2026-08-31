# unblindux.com

The Unblind UX landing page. Static single-page site hosted on GitHub Pages at **https://unblindux.com**.

## What's in here

```
index.html      The whole page (HTML + inline CSS + a small vanilla-JS video loader)
404.html        Branded not-found fallback
CNAME           Custom domain for GitHub Pages (unblindux.com)
.nojekyll       Tells Pages to serve files as-is (skip Jekyll processing)
assets/         Logos (SVG), favicon, and all photos (hero, portrait, proof, events)
```

No build step, no dependencies, no framework. Edit `index.html` directly and re-upload.

## How it deploys

Hosted on **GitHub Pages** from the `main` branch, root folder. The `CNAME` file points the site at the apex domain `unblindux.com`; `www` redirects to it. See `DEPLOY.md` (kept alongside this repo in the vault) for the full first-time setup runbook: repo creation, Pages settings, and DNS records.

To publish a change: edit the file, commit to `main`, and GitHub Pages redeploys automatically within a minute or two.

## Editing notes

- All copy follows the Unblind UX content rules: no em-dash or en-dash, no hype words. Keep it that way.
- The two videos (talk + mentee testimonial) load only on click, so the page stays fast. They point at YouTube embeds.
- The Events rail pins the next Upcoming event first and keeps it in view; that card is tinted coral. When the upcoming event passes, remove the `pinned` class and the `Upcoming` pill from that card.
- Links (booking, socials, talk) are the canonical Unblind UX URLs. Update them in one place if they ever change.
