# BloomVibe landing page

Static landing page for the BloomVibe Android app. The site is designed to be published directly with GitHub Pages from the repository root.

## Files

- `index.html` - landing page markup
- `styles.css` - responsive styling and visual design
- `script.js` - section reveal animation and footer year
- `favicon.svg` - site icon
- `.nojekyll` - prevents GitHub Pages from running Jekyll processing

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. Open repository `Settings` -> `Pages`.
3. Set `Source` to `Deploy from a branch`.
4. Choose branch `main` and folder `/ (root)`.
5. Save the settings and wait for GitHub Pages to publish.

## Local preview

You can preview the site with any simple static server, for example:

```bash
python3 -m http.server 8000
```
