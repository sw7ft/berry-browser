# Berry Browser

Launch page and release hub for **Berry Browser** — the Chromium-based browser for BlackBerry 10.

This repository is intentionally **not** the engine source tree. For patches, branches, and the full port narrative, see **[sw7ft/chromium-for-bb10](https://github.com/sw7ft/chromium-for-bb10)**.

## What lives here

| Path | Purpose |
|------|---------|
| `index.html` | Project landing page (story, stable download, links) |
| `experimental/` | Pointer page for experimental `.bar` builds |
| GitHub **Releases** | Attach experimental BAR files (stable BAR also linked from the site) |

## Stable download

Latest recommended build (as of site publish): **[BerryBrowserV3-3.0.2-build84.bar](https://github.com/sw7ft/chromium-for-bb10/raw/main/releases/BerryBrowserV3-3.0.2-build84.bar)** — canonical copy in [chromium-for-bb10/releases](https://github.com/sw7ft/chromium-for-bb10/tree/main/releases).

## GitHub Pages

1. Repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / root (`/`)

Site URL will be `https://sw7ft.github.io/berry-browser/` (or a custom domain if you add one).

## Related projects

- [chromium-for-bb10](https://github.com/sw7ft/chromium-for-bb10) — Chromium port & documentation
- [BerryCore](https://github.com/sw7ft/BerryCore) — BB10/QNX userland & packaging
- [berrycore.sw7ft.com](https://berrycore.sw7ft.com/)

Not affiliated with BlackBerry Limited.
