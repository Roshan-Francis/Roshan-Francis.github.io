# Roshan Francis: portfolio

A single-page portfolio built with plain HTML, CSS and a little JavaScript. No build step, no dependencies.

## Put it on GitHub Pages

1. On GitHub, create a new public repository named `Roshan-Francis.github.io`.
   This special name gives you the address `https://roshan-francis.github.io`.
   (Any other repository name also works. The site will then live at `https://roshan-francis.github.io/<repo-name>/`.)
2. Upload `index.html`, `photo.png`, `Roshan_Francis_Resume.pdf` and this `README.md` to the repository root.
   Or from a terminal:
   ```bash
   git init
   git add index.html photo.png Roshan_Francis_Resume.pdf README.md
   git commit -m "Add portfolio"
   git branch -M main
   git remote add origin https://github.com/Roshan-Francis/Roshan-Francis.github.io.git
   git push -u origin main
   ```
3. In the repository, open **Settings > Pages**, set **Source** to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. Wait a minute or two, then open your site address.

## Editing

- All the text is in `index.html`. Search for a project name to change its description or links.

- Colors are the variables at the top of the `<style>` block.

## Updating your resume

Replace `Roshan_Francis_Resume.pdf` with the new file, keeping the same name, and commit. The download button will serve the new version.
