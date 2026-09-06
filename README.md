# Zomes77 (English) — Geodesic Dome Generator

Static web app that builds 3D zome domes + 2D cutting layouts.
Modified from [timhutton/zomes](https://github.com/timhutton/zomes).

## Run locally

Open `index.html` directly in a browser, or serve it statically:

```bash
npx serve .
```

## Deploy to GitHub Pages

1. Create a new GitHub repo, e.g. `Zomes77-en`.
2. Upload this folder's contents (`index.html`, `Zomes_files/`, `README.md`).
3. Open **Settings → Pages → Deploy from a branch → `main` / root**.
4. Visit `https://USERNAME.github.io/Zomes77-en/`.

## Structure

```text
Zomes77_en/
├── index.html                  # main app (single file, English UI)
├── Zomes_files/
│   └── jspdf.min.js            # 2D PDF export library
└── README.md
```

## Features

- 3D view: Wireframe / Surface / Flat, Shadow, background switcher
- 2D Layout (on/off toggle)
- Parameters: Height, N, Top strut angle, Cut proportion, Kite ratio
- 3D/2D colors (dropup menus)
- Download: SVG, PDF, OBJ, DXF (2D) + 3D OBJ
