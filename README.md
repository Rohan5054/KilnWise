# KilnWise website

A static site: one HTML page, a favicon and ten images. There is no build step.

## Launch

Upload the whole `kilnwise-site` folder to any static host, keeping `img/` and `favicon.svg` next to `index.html`. Netlify, Vercel, GitHub Pages and Cloudflare Pages all work, as does copying the files to the web root of an ordinary web server. To preview, open `index.html` in a browser.

## Before going live

- Once the domain is set, add a link-preview image to the `<head>`: `<meta property="og:image" content="https://YOUR-DOMAIN/img/smoke-sunrise.jpg">`.
- Keep the photo credits in the Sources list at the foot of the page. The Wikimedia Commons photos are CC BY 4.0 and CC BY-SA 3.0/4.0, which require attribution.
- The smoke animation is adapted from WebGL Fluid Simulation by Pavel Dobryakov (MIT licence). Its licence notice sits at the top of the first `<script>` and must stay.
- Fonts (Anton, Inter, Noto Sans Devanagari) load from Google Fonts.
- Browsers without WebGL show the kiln without smoke; people who turn on reduced motion see a still frame.
