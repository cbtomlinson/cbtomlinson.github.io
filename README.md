# littletomato.dev

Personal portfolio site for Chelsea Tomlinson. Plain HTML/CSS — no build step, no dependencies. Hosted on GitHub Pages at [littletomato.dev](https://littletomato.dev).

## Files

| File | What it is |
|------|------------|
| `index.html` | The whole site (single page: hero, work, about, contact) |
| `styles.css` | All styling. Colors live in the `:root` variables at the top |
| `assets/tomato.svg` | Logo + favicon |
| `assets/og-image.png` | Social share card (shown when the link is texted/shared) — 1200×630 |
| `404.html` | Not-found page |
| `CNAME` | Tells GitHub Pages to serve the site at `littletomato.dev` |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (no Jekyll processing) |

## How to edit

- **Add a project:** copy one of the `<article class="card">` blocks in `index.html` and change the text. Set the real link in the card's `href`.
- **Change colors:** edit the variables at the top of `styles.css` (`--accent` is the tomato red).
- **Update the share card:** replace `assets/og-image.png` (keep it 1200×630).

## Publishing changes

Commit and push to the `main` branch — GitHub Pages redeploys automatically within a minute or two.

```sh
git add -A
git commit -m "Update site"
git push
```
