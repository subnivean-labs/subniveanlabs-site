# Subnivean Labs

Static landing page for https://subniveanlabs.com, ready for GitHub Pages.

## Publish

1. Create a public repository named `subniveanlabs-site` under `mushroom-moon`.
2. Upload `index.html`, `favicon.svg`, `CNAME`, and `.nojekyll` to the `main` branch root.
3. In Settings → Pages, select Deploy from a branch, `main`, and `/ (root)`.
4. Set the custom domain to `subniveanlabs.com`.
5. In Porkbun DNS, remove the parking records for the root and `www`. Preserve all email records.
6. Add four root (`@`) A records: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.
7. Add a `www` CNAME pointing to `mushroom-moon.github.io`.
8. When GitHub finishes its DNS check and provisions the certificate, enable Enforce HTTPS.

No installation, build step, or JavaScript is needed.
