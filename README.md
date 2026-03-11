# Prompter — Teleprompter PWA

A clean, minimal teleprompter that works on Android, Windows, and any modern browser. Installable as a PWA — no browser UI, runs like a native app.

## Features

- **Auto-scroll** with adjustable speed
- **Manual scroll**: tap right side to advance, left to go back
- **Pause on tap** (auto mode)
- **Font size control**
- **Top fade**: text fades into darkness at the top, drawing eyes to the reading line
- **Progress bar** at the bottom
- **HUD controls** that auto-hide after 3 seconds
- **Offline support** via service worker
- Saves your script and settings between sessions

## Keyboard Shortcuts (when in prompter mode)

| Key | Action |
|-----|--------|
| `Space` | Play / Pause |
| `↑ / ↓` | Increase / Decrease speed |
| `← / →` | Back / Forward (manual mode) |
| `R` | Restart from beginning |
| `+ / -` | Increase / Decrease font size |
| `Esc` | Return to editor |

## Install as PWA

### Android (Chrome)
1. Open the site URL in Chrome
2. Tap the three-dot menu → **Add to Home Screen**
3. Opens fullscreen with no browser UI

### Windows (Chrome or Edge)
1. Open the site URL
2. Click the install icon in the address bar (or three-dot menu → **Install Prompter**)
3. Opens in its own window: resize and drag near your webcam

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your app will be live at `https://yourusername.github.io/prompter`

## Local Development

Just open `index.html` in a browser. No build step needed — it's a single HTML file.