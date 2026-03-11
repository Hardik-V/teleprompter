# Prompter: Teleprompter PWA

A clean, minimal teleprompter that works on Android, Windows, and any modern browser. Installable as a PWA — no browser UI, runs like a native app.

## Features

- **Auto-scroll** with adjustable speed
- **Manual scroll**: tap right side to advance, left to go back
- **Pause on tap** (auto mode)
- **Confidence mode**: text dims based on distance from the current line, drawing your eye naturally to where you are
- **Line spacing option**: change line spacing between 3 modes
- **Font size control** (editor + live in HUD)
- **Max width control**: Narrow / Mid / Wide — useful for near-camera laptop use vs. tablet
- **Alignment toggle**: Left or Centre aligned text
- **Estimated time remaining**: live countdown shown bottom-right while scrolling
- **Progress bar** at the bottom
- **HUD controls** that auto-hide after 3 seconds
- **Offline support** via service worker
- Saves your script and all settings between sessions

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
3. Opens in its own window — resize and drag near your webcam

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your app will be live at `https://yourusername.github.io/teleprompter`

## Local Development

Just open `index.html` in a browser. No build step needed it's a single HTML file.
