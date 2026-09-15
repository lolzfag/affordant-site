# Affordant — landing page

Single static page (`index.html`, no build step). Hosted on GitHub Pages.

- Contact address: search `hello@affordant.io` in `index.html` (two places).
- Booking link: set the `href` on `id="book"` and remove `hidden`.
- Custom domain: add a `CNAME` file containing the domain, then point DNS at GitHub Pages
  (apex: A records 185.199.108.153 / .109 / .110 / .111; `www`: CNAME to `lolzfag.github.io`).
