# Search Notes

A small static site on GitHub Pages: short notes on page titles, meta descriptions and Google
Search Console numbers. It is also the public test site, verified in Search Console, for checking
a search-analytics tool's Search Console connection end to end (real sign-in, API calls, empty
data and quota handling).

Live at https://yashjamkar.github.io/seo-engine-pages/ once Pages is enabled
(Settings → Pages → Deploy from a branch → `main`, `/ (root)`).

Plain HTML and CSS: no build step, no scripts, no tracking. `.nojekyll` makes Pages serve the
files as they are.

The sitemap is submitted in Search Console directly: a project site cannot serve the
`robots.txt` crawlers read, which lives at the domain root.
