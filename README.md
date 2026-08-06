# Web Dev Templates

Base template and variants for freelance web dev — landing pages for small businesses in the Philippines.

## Structure

- `base/template.html` — the source of truth. Never edit this directly per client.
- `variants/` — skins of the base template for specific industries (portfolio pieces).
- `assets/` — shared placeholder images/logos.

## How to build a new version for a client

1. Copy `base/template.html` into a new folder (not inside `variants/` — create `clients/[client-name]/` instead).
2. Fill in the `[...]` placeholder text.
3. Adjust the `:root { }` CSS variables at the top for the client's brand colors.
4. Remove any sections that aren't needed (e.g. testimonials).
5. Replace placeholder images with real photos.

## Stack

Plain HTML/CSS/JS — no framework, no build step. Can be hosted on GitHub Pages, Netlify, or any shared hosting.
