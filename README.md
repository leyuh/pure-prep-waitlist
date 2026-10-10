# Pure Prep waitlist

Static waitlist landing page for [Pure Prep](https://pureprep.app), served by GitHub Pages from `main` (root) with the custom domain in `CNAME`.

The waitlist is served at https://pureprep.app/waitlist/ (everything lives in `waitlist/`). The root only redirects.

- `waitlist/index.html`: landing page and sign-up form (posts to the Pure Prep Waitlist Google Form in the background)
- `waitlist/privacy.html`: waitlist privacy policy
- `index.html`: redirects `/` to `/waitlist/`, keeping the query string (UTM params) and hash
- `privacy.html`: redirects the old `/privacy.html` to `/waitlist/privacy.html`
- `404.html`: redirects unknown paths to `/waitlist/`
- `waitlist/styles.css`: shared styles (app palette; the macro pie colors #4f7a48 / #b86b4b / #9a7a2e as accents; hand-coded SVG leaves in the background)
- `waitlist/assets/`: the Pure Prep app logo (`logo.png`, the Leaf P from leyuh/pure-prep `assets/logo.png`) and favicons / apple-touch / 192 / 512 icons generated from it; `waitlist/favicon.ico` (a copy stays at the root for browsers that request `/favicon.ico`)
- Hero card "An example day": 3 meals, about 2,110 kcal, portions and nutrition from the Pure Prep app's food database (`onboarding.js` FOOD)

No build step. Serve the repo root with any static server and open `/waitlist/`.
