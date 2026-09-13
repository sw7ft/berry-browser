# Berry Browser

**Berry Browser** is a sideloadable **Chromium `.bar`** for BlackBerry 10 — a real GPU-rendered browser app (HTTPS, modern sites, YouTube, WhatsApp Web), not the stock WebKit browser.

This repo is the **public launch page** and release hub. Engine source and patches live in **[chromium-for-bb10](https://github.com/sw7ft/chromium-for-bb10)**.

**Live site:** [sw7ft.github.io/berry-browser](https://sw7ft.github.io/berry-browser/)

**Demo (Passport walkthrough):** [YouTube — starts at the demo (~8:55)](https://www.youtube.com/watch?v=5H_1-b8XfA0&t=535s)

## Screenshots

Built-in start page — search, URL bar, and shortcuts (DuckDuckGo default):

![Berry Browser start page on BB10](assets/screenshots/start-page.png)

Settings — auto-detect panel size and touch mapping at launch, or pick your BB10 model (Passport, Classic, Q10, Z series, etc.):

![Berry Browser device settings](assets/screenshots/device-settings.png)

## Stable download

**Latest:** [BerryBrowserV3-3.0.2-build84.bar](https://github.com/sw7ft/chromium-for-bb10/raw/main/releases/BerryBrowserV3-3.0.2-build84.bar) (~60 MB)  
Canonical copy: [chromium-for-bb10/releases](https://github.com/sw7ft/chromium-for-bb10/tree/main/releases)

Install: enable Development Mode → sideload the `.bar` (Sachesi, DDPB, or on-device BAR installer) → launch **Berry Browser** from the home screen.

## What lives in this repo

| Path | Purpose |
|------|---------|
| `index.html` | Landing page (demo embed, screenshots, download links) |
| `assets/screenshots/` | Product screenshots (also embedded above) |
| `experimental/` | Experimental `.bar` builds via GitHub Releases |
| GitHub **Releases** | Attach tester BAR files |

## GitHub Pages

Published from **`main`** at repo root → **https://sw7ft.github.io/berry-browser/**

## Related

- [chromium-for-bb10](https://github.com/sw7ft/chromium-for-bb10) — port, branches (`berry-v3`), documentation
- [BerryCore](https://github.com/sw7ft/BerryCore) — BB10/QNX userland & `qpkg`
- [berrycore.sw7ft.com](https://berrycore.sw7ft.com/)

Not affiliated with BlackBerry Limited.
