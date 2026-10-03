# Fieldcraft Archery Range

This project is a static Three.js game that can be hosted as a plain website.

## Run locally

Open the file directly:

- `games/archery_game.html`

Or use a local web server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000/
```

## Publish online

The easiest option is GitHub Pages:

1. Push this folder to a GitHub repository.
2. Open the repository on GitHub.
3. Go to Settings > Pages.
4. Select the branch to publish, usually `main`.
5. Keep the root folder as `/`.
6. Save.

Your game will be live at a URL like:

```text
https://<your-username>.github.io/<repo-name>/
```

This app uses the Three.js CDN and Google Fonts, so the page needs an internet connection when loaded.
