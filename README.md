# Treesys website

Public site for **[Treesys](https://www.treesys.org/)**: technology for humanity, starting with education.

This repository is the source for [www.treesys.org](https://www.treesys.org/) (GitHub Pages).

## Contents

| Path | Role |
|------|------|
| `index.html` | Full site (ES/EN), self-contained |
| `CNAME` | Custom domain `www.treesys.org` |
| `.nojekyll` | Serve files as-is on GitHub Pages |

## Preview locally

```bash
cd treesys-website
python3 -m http.server 8080
```

Open [http://127.0.0.1:8080](http://127.0.0.1:8080).

## Deploy

Push `main` to GitHub. With **Settings → Pages → Source: GitHub Actions**, the workflow publishes the site root.

After the first deploy, point DNS for `www.treesys.org` (and apex redirect if you use it) at GitHub Pages as usual.

## Related

- [Arborito](https://arborito.org) — learning app
- [arborito](https://github.com/treesys-org/arborito) · [arborito-games](https://github.com/treesys-org/arborito-games) · [arborito-sdk](https://github.com/treesys-org/arborito-sdk)

## License

- **Site code** (HTML/CSS/JS): [GPL-3.0-or-later](LICENSE)
- **Treesys / Arborito names, logos, and mascot**: **all rights reserved** — see [NOTICE](NOTICE)

Brand assets are not licensed with the code. Do not reuse them as the face of another product without permission.
