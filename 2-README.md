# Frame / Photo Puzzle Studio

Turn your favorite photos into a sliding-swap puzzle — right in your browser. No accounts, no servers: your photos never leave your device.

**Play it live:** https://akash991833.github.io/photo-puzzle-studio/

## Features

- **Upload any photo** (JPG, PNG, WebP up to 20 MB) or pick a built-in sample
- **Auto photo enhancement** — every upload is gently sharpened, color-balanced and upscaled client-side before slicing (contrast stretch + saturation + unsharp mask)
- **Easy / Medium / Hard** presets (3×3, 4×4, 6×6) plus a **custom grid** — choose any columns × rows from 2×2 up to 64 pieces
- Timer, move counter, live "in place" progress
- Peek at the original photo anytime with Preview
- Pause anytime (auto-pauses when the tab hides)
- Optional tile numbers for an easier run
- Tap-to-swap or drag-and-drop, keyboard friendly
- Mobile-perfect responsive layout

## Tech

A single `index.html` — no build step, no dependencies, no backend. All image processing (enhancement, cropping, slicing) happens in `<canvas>` on your device.

## Run locally

Open `index.html` in any modern browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Publishing

Hosted with GitHub Pages from the `main` branch.

---

Made by [Akash Vishwakarma](https://github.com/AKASH991833)
