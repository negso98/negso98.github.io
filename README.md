# negin-site

Personal landing page — links to GitHub, LinkedIn, Spotify, and resume download.

## Deploy with GitHub Pages

1. Create a new repo on GitHub, e.g. `negso98.github.io` (this special name gives you the shortest URL: `https://negso98.github.io`) — or any other name if you'd rather it live at `https://negso98.github.io/repo-name`.
2. Push this folder to it (see commands below).
3. In the repo, go to **Settings → Pages**, set source to the `main` branch, root folder, and save.
4. Your site will be live at the URL GitHub shows within a minute or two.

## Before you push

- Add your resume as `resume.pdf` in this folder (the download button already points to it).
- Replace the LinkedIn and Spotify placeholder links in `index.html`.
- Replace the photo placeholder `<div>` in `index.html` with an `<img>` tag pointing to your photo (add the image file to this folder too).

## Push commands

```bash
cd negin-site
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/negso98/negso98.github.io.git
git push -u origin main
```
