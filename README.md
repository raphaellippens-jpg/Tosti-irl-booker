# Tosti Bookcatcher RPG

A colorful, responsive, pixel-art book-catching browser game prototype.

## Run it
- Open `index.html` in a modern browser for manual search, demo catalogue, journal, room and local saving.
- For camera scanning, serve the files over HTTPS (or localhost) and use a browser that supports `BarcodeDetector`. Camera permissions are required.
- ISBN lookup uses the Google Books API and needs an internet connection. Manual book entry works without it.

## Features
- Demo catalogue and manual custom-book creation
- Camera barcode scan where supported, ISBN input fallback
- Online ISBN metadata lookup
- Book journal with search and rarity filter
- XP and levels
- Pixel-art room with interactive shelf slots
- Automatic localStorage saving
- Exportable JSON backup

## Notes
This is an independent fan-made concept inspired by the bookstore name supplied by the user; it is not an official Tosti website. It does not use Tosti branding assets. Progress is saved in the current browser on the current device. Cross-device syncing is not included.

## GitHub Pages
Upload `index.html`, `style.css`, `app.js`, and `README.md` to the root of a GitHub repository, then enable GitHub Pages in repository settings. Camera access generally requires HTTPS, which GitHub Pages provides.
