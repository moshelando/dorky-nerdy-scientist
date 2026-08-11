# HISA2C Website

Static, GitHub Pages-ready website for HISA2C.

## Publish on GitHub Pages

1. Create a GitHub repository.
2. Upload **the contents of this folder** to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your branch (usually `main`) and the root `/` folder.
6. Save. GitHub will publish the site.

No build step, package manager, framework, or external dependency is required.

## Files

- `index.html` — Home
- `strategy.html` — Our Strategy
- `leadership.html` — Our Leadership
- `assets/styles.css` — all site styling
- `assets/site.js` — responsive navigation and subtle reveal behavior
- `assets/hisa2c-logo.png` — web-optimized transparent version of the supplied HISA2C logo

## Adding leadership photos

In `leadership.html`, each `<div class="photo-placeholder">...</div>` can be replaced with an image, for example:

```html
<img class="leader-photo" src="assets/elaine-iseley.jpg" alt="Elaine Iseley">
```

If you add photos, place the image files in `assets/`.
