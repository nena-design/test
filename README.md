# hello world cat

A tiny static site: ASCII art of a cat holding a sign that says **hello world**.

## Run locally

It's just static files, so any static server works:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

Or simply open `index.html` in your browser.

## Files

- `index.html` — the page and the ASCII art
- `style.css` — terminal-style theme, glow, and a subtle entrance animation

## Deploy

Push to `main` and enable **GitHub Pages** (Settings → Pages → deploy from `main` / root) to publish it.
