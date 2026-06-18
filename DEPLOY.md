# CYBER 2026 — CMMC Command Suite
## GitHub Pages — 4-File Deploy

### Files
```
index.html     ← The complete platform (2.8 MB, self-contained)
.nojekyll      ← Stops Jekyll from mangling the HTML (REQUIRED)
_config.yml    ← Minimal GitHub Pages config
DEPLOY.md      ← This file
```

### Steps

**1. Create repo**
- github.com/new → Name: `cmmc-command-suite` → Public → no README → Create

**2. Upload all 4 files**
- Add file → Upload files → drag all 4 → Commit

> ⚠️ macOS hides dotfiles by default. Press **Cmd+Shift+.** in Finder to see `.nojekyll` before dragging.
> Windows: enable "Show hidden files" in File Explorer options.

**3. Enable Pages**
- Settings → Pages → Branch: **main** / Folder: **/ (root)** → Save

**4. Wait ~60 seconds → your URL:**
```
https://YOUR_USERNAME.github.io/cmmc-command-suite/
```

### Updating
Re-upload just `index.html` whenever you have a new version.

### Offline / Air-Gapped
Open `index.html` directly in any modern browser — no internet required.
All libraries (mammoth.js, PDF.js) are embedded.
