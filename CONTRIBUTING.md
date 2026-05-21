# Contributing to SYNTERLAB

Thanks for your interest in contributing to the SYNTERLAB landing page.

## What lives here

This repo contains the public-facing landing page at [synterlab.space](https://synterlab.space). The site is a single self-contained HTML file with no build step required.

```
index.html    — full landing page (CSS + JS inline)
README.md     — project documentation
```

## How to run locally

```bash
# Any static file server works. Examples:
npx serve .
python3 -m http.server 8080
```

Open `http://localhost:8080` in your browser.

## What you can contribute

- Bug reports (broken layout, accessibility issues, broken links)
- Copy/content fixes (typos, clarity)
- Performance improvements
- Accessibility improvements (ARIA, keyboard navigation, contrast)

## What we do NOT accept

- Changes to pricing or product descriptions (these are owned by the product team)
- New sections or major layout changes without prior discussion
- Third-party scripts or tracking

## Submitting a change

1. Fork the repo
2. Make your change in `index.html`
3. Test in Chrome and Firefox, both desktop and mobile
4. Open a pull request with a clear description of what changed and why

## Code style

- All CSS and JS must remain inline in `index.html`
- No runtime dependencies except Google Fonts
- No em dashes anywhere in copy or code
- Strictly monochrome (only `#4ADE80` green and `#EF4444` red as functional tuner indicators)
- All copy in English
