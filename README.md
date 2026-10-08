# theia-hq.github.io

The source of the Theia org's landing page: `index.html`, `404.html` and one stylesheet, with no build step, published
by GitHub Pages from the root of the default branch. The fonts (Roboto Slab, Inter, JetBrains Mono) are served from
`assets/fonts/` with their licenses, so the page makes no request to any other site. A few lines of script add a copy
button to the install line; the page reads the same without them. To preview it, run
`python3 -m http.server` here and open `http://localhost:8000` (the 404 page uses root paths, so it needs a server).
