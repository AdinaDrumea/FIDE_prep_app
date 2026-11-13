# FIDE Study Hub

A static, self-contained German study site with three chapters:

- `vocabulary.html` — vocabulary in context
- `grammar.html` — focused grammar reflex practice
- `fide-tasks.html` — B1 FIDE task practice
- `index.html` — main dashboard

No build step, package manager, server, or database is required.

## Publish with GitHub Pages

1. Create a new GitHub repository (for example `fide-study-hub`).
2. Upload **all files from this folder** to the repository root.
3. Commit the files to the `main` branch.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then save.
7. GitHub will show the public Pages address after deployment.

`index.html` is the site entry page.

## Progress and privacy

The apps store progress using `localStorage` in the browser. No study data is sent to a server by this site. Progress is therefore device/browser-specific and will not automatically sync between devices.

## Files

Keep `.nojekyll` in the repository root. It tells GitHub Pages to serve the site as-is without Jekyll processing.
