# Victory Circle website

Static website for the Victory Circle iPhone app. It contains the product home page, support page, and privacy policy. All website files live here; the iOS app and its App Store assets remain in `01 Apps/Victory Circle - iOS`.

## Preview locally

From this folder, run `python3 -m http.server 8000` and open `http://localhost:8000/`. The site uses plain HTML and CSS, with no build step or package dependencies.

## Publish with GitHub Pages

Create a public repository such as `vsskkv/victory-circle-support`. Put `index.html`, `support.html`, `privacy-policy.html`, `styles.css`, `.nojekyll`, and the complete `assets/` folder in its root. Under **Settings → Pages**, publish from the default branch and `/(root)`.

After it is live, check the actual HTTPS URLs and add the support and privacy policy URLs to App Store Connect. The expected project URLs, if the repository is named `victory-circle-support`, are:

- `https://vsskkv.github.io/victory-circle-support/`
- `https://vsskkv.github.io/victory-circle-support/support.html`
- `https://vsskkv.github.io/victory-circle-support/privacy-policy.html`

These are examples until publication is verified. The website deliberately says the App Store release is in preparation, so update the home page with a real download link only after the app is live.
