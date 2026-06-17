# 🌟 Children's Clock

A cheerful, animated analog clock built with pure HTML, SVG, and JavaScript — designed to celebrate **International Children's Day (June 1st)**.

![Children's Clock Preview](preview.png)

## Features

- **Real-time analog clock** — hour, minute, and second hands update continuously with millisecond precision (no tick stuttering on the second hand)
- **Responsive layout** — the clock face scales to fill any window size, from phone screens to large desktop monitors
- **Playful design** — bear ears, rainbow dot ring, colorful hour numbers (Alata font), four corner stars, and a floating animation
- **Digital time display** — shown below the clock face in a monospace font (DM Mono)
- **Date display** — full weekday, month, day, and year
- **iPhone / iOS Safari compatible** — uses `100dvh`, `viewport-fit=cover`, `env(safe-area-inset-*)`, `-webkit-backdrop-filter`, and pinch/double-tap zoom disabled
- **Confetti burst** — a small celebration fires every time the minute changes
- **No dependencies** — single self-contained HTML file, no frameworks or build tools required

## Demo

Open `index.html` directly in any modern browser. No server required.

## File Structure

```
Children-s-Clock/
└── index.html      # The entire clock — HTML, SVG, CSS, and JS in one file
```

## Fonts Used

All fonts are loaded from [Google Fonts](https://fonts.google.com/):

| Font | Usage |
|------|-------|
| [Baloo 2](https://fonts.google.com/specimen/Baloo+2) | Digital time display label |
| [Nunito](https://fonts.google.com/specimen/Nunito) | Date label and body text |
| [DM Mono](https://fonts.google.com/specimen/DM+Mono) | Digital HH:MM:SS readout |
| [Alata](https://fonts.google.com/specimen/Alata) | Clock face hour numbers |

## Browser Compatibility

| Browser | Status |
|---------|--------|
| Chrome / Edge (desktop) | ✅ Full support |
| Firefox (desktop) | ✅ Full support |
| Safari (desktop) | ✅ Full support |
| iOS Safari (iPhone) | ✅ Full support |
| Android Chrome | ✅ Full support |

## Usage

Simply download `index.html` and open it in a browser, or host it on any static file host (GitHub Pages, Netlify, Vercel, etc.).

To deploy via GitHub Pages:
1. Go to your repository **Settings → Pages**
2. Set source to **Deploy from a branch → main → / (root)**
3. Your clock will be live at `https://<your-username>.github.io/Children-s-Clock/`

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
