# Website

This repository contains a minimal static website starter.

Files added:

- [index.html](index.html) — main homepage
- [styles.css](styles.css) — site styles

How to view locally:

1. Open `index.html` directly in your browser by double-clicking it.
2. Or run a quick static server from the project folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

Next steps:

- Edit `index.html` to add your content.
- Replace colors, fonts, and assets in `styles.css` as needed.

Wallpaper selector:

- Use the paint button (🎨) in the header to open the wallpaper selector.
- Pick one of the gradient presets, upload your own image, or click "Reset" to return to the default background.
- Your selection is saved in your browser via `localStorage`.

Sell with us:

- The "Sell With Us" form is on the homepage under the "Sell With Us" section.
- Fill in item title, category, price, description, contact email and optionally upload images.
- Submissions are stored in your browser's `localStorage` (demo mode). You can view submitted listings in the "Your Listings" area below the form.

Note: This starter site doesn't include a backend — if you want to accept real listings, I can add a simple server endpoint or show how to connect to a backend service.
