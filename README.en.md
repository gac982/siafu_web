# Siafu website

Promotional landing page for **Siafu**, the terminal-based load-testing tool configured with YAML and written in Go.

- Published page: `index.html`
- Siafu version: v0.4.2
- Project repository: <https://github.com/gac982/siafu>
- Español: [README.md](README.md)

## View the page

It is a single self-contained file: open it directly in a browser.

```bash
# option 1: open the file
xdg-open index.html

# option 2: serve it locally
python3 -m http.server 8000
# http://localhost:8000
```

No build, server, or network connection is required: all HTML, CSS, and JavaScript is inline. The only local dependency is `assets/logo.png`, used as the favicon and `og:image`.

## Structure

```text
index.html        full page (inline HTML + CSS + JS)
assets/logo.png   Siafu logo (favicon / og:image)
README.md         Spanish README
README.en.md      this file (English)
```

## Design

- Siafu's four-color TUI palette: Ink `#0E1116`, Bone `#E6E1D6`, Ember `#FC4C02`, Ash `#7A8394`.
- Editorial typography (Times-like serif) for headings; system sans for body; mono for code and terminal.
- Mobile-first, no shadows or gradients, 1px borders.
- TUI simulator, YAML explorer with custom highlighting, and clipboard copy, all in vanilla JavaScript.

## License

This page describes Siafu, which is distributed under AGPL-3.0-or-later.
