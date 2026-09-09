# compounding-site

Static site for Compounding, published with GitHub Pages.

- Everything under `site/` is published as-is. `site/index.html` is the home page.
- Pushing to `main` deploys automatically via `.github/workflows/pages.yml`.
- Live at https://everyinc.github.io/compounding-site/

## Serving it at every.to/compounding

A GitHub Pages custom domain attaches to a host, never a path, so DNS alone cannot do it.
The every.to Next app proxies the path instead (see EveryInc/every PR #886). If a site
generator is added here, set its base path to `/compounding` so assets resolve behind the
proxy.
