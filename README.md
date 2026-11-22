# Samia Shahrin | Portfolio

Personal portfolio website. Plain HTML, CSS and JavaScript, no build step.

## Structure
```
index.html      the whole site (styles and scripts included)
images/         profile photo, dashboards, artwork and photography
.nojekyll       tells GitHub Pages to serve files as they are
```

## Publish on GitHub Pages
1. Create a new public repository on GitHub, for example `samia-portfolio`
   (or `<your-username>.github.io` to get the shorter address).
2. Upload everything in this folder (index.html, images folder, .nojekyll) to the
   root of the repository: Add file > Upload files, then Commit.
3. Go to Settings > Pages. Under "Build and deployment", set Source to
   "Deploy from a branch", Branch to `main` and folder to `/ (root)`. Save.
4. After a minute or two the site is live at
   `https://<your-username>.github.io/samia-portfolio/`
   (or `https://<your-username>.github.io/` for the special repository name).

## Updating content
All text and image lists live in the `CONTENT` block near the bottom of
`index.html`. To add an image, put the file in `images/` and add a line to the
matching list (`projects`, `art`, `photos`) with its path, width, height,
title and description.
