# TRON Clock (Fullscreen)

A TRON-inspired fullscreen digital clock with **fixed-width character cells** so the display never “wiggles” when digits change, plus motivational quotes refreshed every minute.

## Features

- **TRON-style neon grid** background and cyan glow
- **Orbitron** font (Google Fonts)
- Time rendered as **8 fixed-width cells**: `HH:MM:SS` (no layout shifting)
- Subtle **per-digit pulse** animation on change
- Date displayed below the clock
- Motivational quote at the bottom, **refreshes every minute** (minute-aligned)
- Fully responsive; scales to any monitor resolution

## Run locally

Just open `index.html` in your browser.

### Optional: run from a local web server

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Kiosk mode (Chrome/Chromium)

```bash
chrome --kiosk index.html
```

## Customize

### Change the color palette
Edit the CSS variables at the top of `index.html`:

- `--bg`
- `--cyan`, `--cyan2`
- `--glow`

### Change quotes
Edit the `quotes` array in the `<script>` section.

## License

MIT (see `LICENSE`).
