# The Explainers

A small library of interactive, no-jargon explainers for confusing technical topics.
Each one teaches through a single sustained metaphor and is built to be poked,
dragged, and clicked — not just read.

Each edition is a **single self-contained HTML file** (fonts and a little animation
loaded from a CDN; no build step, no install).

## Editions

| # | Topic | Metaphor | File |
|---|-------|----------|------|
| 01 | Apache Kafka | A global newspaper distribution system | [`kafka-explained.html`](kafka-explained.html) |
| 02 | Certificates (TLS) | Passports & border control | [`certificates-explained.html`](certificates-explained.html) |
| 03 | The Security Stack — TLS, mTLS, OAuth 2.0, OIDC, JWT | Newspaper edition | [`security-explained.html`](security-explained.html) |

`index.html` is an editorial landing page linking all three.

## Viewing

Open any file directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Publishing with GitHub Pages

1. Push this repo to GitHub.
2. **Settings → Pages → Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Your site appears at `https://<username>.github.io/<repo>/`.

The landing page and all relative links work as-is.

## The shared recipe

- One sustained metaphor, start to finish
- Interactive demos over walls of text
- A jargon decoder for the scary words
- An honest "where this breaks" section
- A one-sentence recap you'll actually remember
