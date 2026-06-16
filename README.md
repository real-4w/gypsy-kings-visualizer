# Gypsy Kings Visualizer

Public, self-contained HTML dashboard for **West Coast Rangers Gypsy Kings** match and player stats (2022–2026).

## Live site

Once GitHub Pages is enabled (Settings → Pages → branch `main`, folder `/`):

**https://real-4w.github.io/gypsy-kings-visualizer/**

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main visualizer (GitHub Pages entry point) |
| `gypsy_kings_visualizer_V3.html` | Same file, versioned name |

## Updating (from the dev repo)

This repository is synced **manually** from the private development repo [`real-4w/GK`](https://github.com/real-4w/GK):

```powershell
python "w_create_html_version V3.py"   # regenerate HTML from Excel
python w_sync_html_publish.py          # copy and push to this repo
```

Sync does not run automatically.
