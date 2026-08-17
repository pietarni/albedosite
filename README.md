# albedodelight.com

Minimal company site for Albedo Delight Oy, hosted on GitHub Pages.

## Deploy

1. Push this repo to GitHub.
2. In the repo: **Settings → Pages → Build and deployment → Source**: deploy from the `main` branch, root `/`.
3. Under **Custom domain**, set `albedodelight.com` (the `CNAME` file handles this on push).
4. At your DNS provider, add:
   - `A` records for `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` for `www` → `<username>.github.io` (optional, if you want www)
