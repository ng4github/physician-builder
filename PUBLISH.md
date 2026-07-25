# Publish to GitHub Pages

`index.html` is fully self-contained (fonts, runtime, and all logic inlined). It works offline and needs no build step.

## Prompt for Claude Code

Paste this into a new Claude Code session, in a folder containing `index.html`:

---

I have a single self-contained `index.html` in this folder. Publish it to GitHub Pages under my account `ng4github`:

1. Create a new public repo named `physician-builder`.
2. Commit `index.html` at the repo root on the `main` branch.
3. Enable GitHub Pages for the repo, serving from the `main` branch, root folder.
4. Wait for the first Pages build to finish, then print the live URL.

Do not modify the contents of `index.html`.

---

The live URL will be:

    https://ng4github.github.io/physician-builder/

## Manual alternative (no Claude Code)

1. Create a new public repo `physician-builder` on GitHub.
2. Upload `index.html` to the repo root.
3. Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)` → Save.
4. Wait about a minute, then open the URL above.
