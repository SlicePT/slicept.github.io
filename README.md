# slicept.github.io

This repository contains the static website for SlicePT. It's a small HTML/CSS site (single `index.html` + assets in `src/`) intended to be hosted on GitHub Pages.

Summary
- Site entry: `index.html`
- Static assets: `src/` (images, etc.)
- Contact / booking form: https://forms.gle/uxuCqVuLhTqqZLPZ6

Quick local development

1. Open the project folder in your terminal or a code editor:

```bash
cd /path/to/slicept.github.io
```

2. Recommended: run a simple local server (so relative paths and image loading behave like on the web):

Using Python 3 (no extra installs):

```bash
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

To stop the server, press Ctrl+C in the terminal where it is running, or kill the process:

```bash
# find and kill by PID (example)
pkill -f "python3 -m http.server"
```

Editing the site
- Edit `index.html` for content changes (text, styles).
- Replace or add images under `src/`. Keep filenames and relative paths in `index.html` in sync.

Git / publishing notes
- The site is typically published via GitHub Pages. The repository's default branch is `main` (see repository settings for which branch is used for Pages).
- If you are working on a feature branch (for example `basicWebPage`), push your branch and open a pull request to `main`.

```bash
# push current branch
git add .
git commit -m "Describe changes"
git push origin $(git branch --show-current)
```

Accessibility and caching
- If you don't see updated content in your browser after edits, perform a hard reload (Cmd+Shift+R) or open the page in a private/incognito window to bypass cache.

Other notes
- A `.gitignore` is included to ignore macOS artifacts such as `.DS_Store` and common editor folders.
- Server logs (when started with `nohup`) are sometimes written to `/tmp/slicept_http.log` in local workflows — check there if you need to see request logs.

Contact
- Booking/contact form: https://forms.gle/uxuCqVuLhTqqZLPZ6

License
- This project is provided as-is. Add a LICENSE file to declare a formal license (e.g., MIT) if desired.
