# TAOTI

Static website for **TAOTI — Transformation + Integration Advisory**.

TAOTI is a play on “the Tao of TI”. Here, **TI** means **Transformation + Integration**: connecting strategy, customer, product, technology, data, investment and delivery so complex organisations make coherent choices and achieve measurable outcomes.

## Site

The site uses plain HTML, CSS and JavaScript. GitHub Pages serves the `main` branch from the repository root.

- Current site: https://taoti06.github.io/TAOTI/
- Current repository: https://github.com/Taoti06/TAOTI
- Previous site address: https://taoti06.github.io/intent-and-practice/

GitHub redirects the old **repository** URL after a rename, but it does not redirect the old **Pages** address. The files in `legacy-pages-redirect/` are ready to publish from a new public repository named `intent-and-practice`. Copy `index.html` and `404.html` to that repository's root, then enable GitHub Pages from its `main` branch and root folder. The redirect preserves the page path, query string and fragment for browsers running JavaScript; the HTML fallback points to the TAOTI homepage. The old address does not redirect until that separate repository is created and Pages is enabled.
