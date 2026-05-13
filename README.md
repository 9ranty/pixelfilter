# PixelFilter

A browser-based LCD/CRT pixel-effect tool. Apply RGB subpixel, shadow mask, slot mask, and aperture grille filters to images, or generate pure pattern art in SVG and PNG.

![Mac OS X Leopard-styled UI](https://img.shields.io/badge/UI-Aqua-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## Features

- **Filter mode** — upload an image and apply pixel-grid effects
- **Pattern mode** — generate standalone pixel patterns as SVG or PNG
- **Layouts** — RGB Stripe, RGB Square, CRT TV
- **Phosphor masks** — Shadow Mask, Slot Mask, Aperture Grille
- **Color schemes** — Custom, Random, Harmonious, Harmonious-from-image, Tonal-from-image
- **Multiple aspect ratios** — 16:9, 4:3, 1:1, 3:4, 9:16, 21:9
- **Looping video export** — record an animated loop (2–8s) for sharing
- **Save** — PNG image, SVG vector, or recorded loop

## Run it

It's a single-file static site. Any HTTP server works:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

Or just open `index.html` directly in a browser.

## License

[MIT](LICENSE)
