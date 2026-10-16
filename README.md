# ERUNZ RAPSODI Official Website

Static GitHub Pages website. Upload all files and folders to the root of the `erunzrapsodi.github.io` repository. Set Pages to deploy from the `main` branch and `/ (root)`.

## Updating links
- Spotify: edit `trust/index.html` and `index.html`.
- Audiomack: add an `<a class="btn" href="YOUR_LINK" target="_blank" rel="noopener noreferrer">Audiomack</a>` in the `.platforms` section of `trust/index.html`.
- Apple Music and Boomplay: replace the shared TuneCore button with direct buttons when verified links are known.

## Custom domain
`CNAME` is preconfigured for erunzrapsodi.com. In Wix DNS management, point A records for `@` to GitHub Pages addresses 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153 and CNAME `www` to `erunzrapsodi.github.io`. Remove conflicting A/AAAA records, not unrelated MX/TXT records. In GitHub repository Settings > Pages set custom domain `erunzrapsodi.com` and enable Enforce HTTPS after DNS validates. DNS propagation can take time.

Do not share private keys or credentials in this public repository.
