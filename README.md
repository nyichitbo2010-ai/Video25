# NEON RECAP Telegram Mini App — UI prototype v2

This is a static front-end UI prototype. It includes:
- Neon cyberpunk dashboard
- Word-by-word / character-by-character animated live code panel
- Movie Recap and Audio Book workflow cards
- Voice Reference Kit UI for `ref.wav`, `ref.txt`, and `link.txt`
- Telegram WebApp SDK integration

## Important
The reference controls are UI-only: selecting `ref.wav` only displays its local filename; it does not upload the file. `ref.txt` and `link.txt` remain in the browser and are not sent to the Python script. No AI API or Python backend is connected.

## Preview
Open `index.html` in a browser, or run `python -m http.server 8000` from this folder.

## GitHub Pages
Upload `index.html` to the root of a public repository, then enable Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
