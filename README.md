# 2048

A standalone clone of the original [2048](https://github.com/gabrielecirulli/2048) by Gabriele Cirulli, rebuilt from scratch with plain HTML/CSS/JavaScript — no framework, no build step.

Demo: `https://<username>.github.io/<repo>/` (replace with your GitHub Pages link after deploying).

## Features

- Play with the keyboard (arrow keys / WASD) or swipe on mobile/tablet.
- Fully responsive — scales to the screen or to the iframe it's embedded in.
- Best score saved with `localStorage`.
- Win (2048) / game over overlays, with an option to keep playing after winning.

## Run locally

Just open `index.html` in a browser, or serve it with any static server, e.g.:

```bash
npx serve .
```

## Deploy to GitHub Pages

1. Create a new GitHub repo and push the contents of this folder to the `main` branch.
2. Go to **Settings → Pages**, set the source to branch `main`, folder `/ (root)`.
3. After a minute or two, GitHub will give you a link like `https://<username>.github.io/<repo>/`.

## Embedding via iframe

```html
<iframe
  src="https://<username>.github.io/<repo>/"
  style="width:100%; height:100%; border:0;"
  loading="lazy"
></iframe>
```

## Credit

Inspired by [2048 by Gabriele Cirulli](https://github.com/gabrielecirulli/2048). This is an independent rebuild — no source code or assets from the original are reused.
