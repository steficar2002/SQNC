# Presentation — Sequence × Volcano Bet

A single-page slide presentation you can run locally and publish as a website. Optimized for **mobile** and **desktop**.

## Run locally

```bash
npm install
npm start
```

Then open **http://localhost:3000** in your browser.

Or open `index.html` directly in a browser (no server needed).

## Controls

- **Desktop:** Arrow keys or Space (next), click prev/next, or click the progress dots.
- **Mobile:** Swipe left/right or use the bottom navigation.

## Publish as a website

The project is static (one `index.html`). You can publish it on:

1. **Netlify** — Drag the project folder to [app.netlify.com/drop](https://app.netlify.com/drop), or connect your Git repo.
2. **Vercel** — Import the folder or repo at [vercel.com](https://vercel.com).
3. **GitHub Pages** — Push to a repo and enable Pages; set source to the branch and root (or `/docs` if you use a `docs` folder).
4. **Any static host** — Upload the contents of this folder (at least `index.html`) to your web server.

No build step required; the HTML is ready to deploy.

## Edit the presentation

- Edit **index.html** to change text, slides, or styles.
- Slides are `<div class="slide">` with ids `s1`, `s2`, …; add/remove/reorder them and update the `slideIds` array in the `<script>` at the bottom so the navigation and counter stay in sync.
