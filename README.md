# Gypsy Kings Visualizer

Public, self-contained HTML dashboard for **West Coast Rangers Gypsy Kings** match and player stats (2022–2026).

## Live site

**https://real-4w.github.io/gypsy-kings-visualizer/**

(GitHub Pages: branch `main`, folder `/`)

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main visualizer (GitHub Pages entry point) |
| `gypsy_kings_visualizer_V4.html` | Same file, versioned name |

## Updating (from the dev repo)

This repository is synced **manually** from the development repo [`real-4w/GK`](https://github.com/real-4w/GK):

```powershell
python "w_create_html_version V4.py"   # regenerate HTML from Excel
python "w_sync_html_publish V4.py"     # regenerate, copy, and publish
```

`w_sync_html_publish V4.py` regenerates the HTML automatically unless you pass `--skip-generate`.
