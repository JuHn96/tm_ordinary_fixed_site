# TM Ordinary Fixed Site

This folder was generated automatically to make the code run locally exactly as in the original live demo **without editing code**.

- All files from your source zip were copied as-is.
- Additionally, for every `src`, `href`, or `url(...)` reference found in your HTML/CSS/JS, this tool **created the same folder path** under this directory and placed the best-matching file there (by filename), so paths in code resolve without modification.

## How to run (VS Code)
1. Install the extension **"Live Server"** (ritwickdey.LiveServer).
2. Right-click `index.html` (or the main page) → **Open with Live Server**.
3. Or run a simple HTTP server:
   - **Python 3**: `python -m http.server 5500`
   - **Node**: `npx http-server -p 5500`

> Tip: If your main entry file isn't `index.html` at the root, navigate to the correct HTML file inside the folder.

## Notes
- External CDN links remain untouched.
- If some assets still don't show, check `fix_report.json` for unresolved references (usually truly missing in the original zip or non-file links).
