# Pure Prep waitlist

Static waitlist landing page for [Pure Prep](https://pureprep.app), served by GitHub Pages from `main` (root) with the custom domain in `CNAME`.

- `index.html`: landing page and sign-up form (posts to the Pure Prep Waitlist Google Form in the background)
- `privacy.html`: waitlist privacy policy
- `404.html`: redirects to the home page
- `styles.css`: shared styles (app palette; the macro pie colors #4f7a48 / #b86b4b / #9a7a2e as accents; hand-coded SVG leaves in the background)
- `assets/`: the Pure Prep app logo (`logo.png`, the Leaf P from leyuh/pure-prep `assets/logo.png`) and favicons / apple-touch / 192 / 512 icons generated from it; `favicon.ico` at the root
- Hero card "An example day": 3 meals, about 2,110 kcal, portions and nutrition from the Pure Prep app's food database (`onboarding.js` FOOD)

No build step. Open `index.html` locally or serve the folder with any static server.
