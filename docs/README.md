# ForestPPL website

Static site for ForestPPL, published with GitHub Pages. No build step, no Jekyll, no external services except Google Fonts.

## Files

| File | Purpose |
|---|---|
| `index.html` | Main page: quick start, language tour, trees, libraries, command cheat sheet, community |
| `reference.html` | Full language reference (copy of `ForestPPL_Reference.index.html` from the repo root) |
| `favicon.svg` | Browser tab icon |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publish

1. Put this `docs` folder in the root of the `ForestPPL` repository and push it.
2. On GitHub open **Settings → Pages**.
3. Under **Build and deployment** choose **Source: Deploy from a branch**, branch **main**, folder **/docs**, then **Save**.
4. After a minute or two the site is live at `https://okogosov.github.io/ForestPPL/`.

Add that address to the repository's **About** box (gear icon → Website) so visitors find it from the repo page.

## Update

- Edit `index.html` and push; Pages republishes automatically.
- When the reference changes, copy the new `ForestPPL_Reference.index.html` over `docs/reference.html`.
- Enable **Settings → General → Features → Discussions** so the Community section links work.

## Links used by the page

- Download: `https://github.com/okogosov/ForestPPL/raw/main/ForestPPL_SFX.exe`
- Tutorial: `Tutorial ForestPPL.pdf` in the repo root
- Discussions and Issues of `okogosov/ForestPPL`
