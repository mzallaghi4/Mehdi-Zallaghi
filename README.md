# Mehdi Zallaghi — Academic Website

A lightweight academic portfolio built with plain HTML, CSS, and JavaScript for free hosting on GitHub Pages.

## Personalize before publishing
1. Open `index.html` and review the About text.
2. Replace the Publications placeholder with verified paper titles, authors, venues, years, and links. The Google Scholar link is already configured.
3. Add your actual courses and teaching roles in the Teaching section.
4. Update the Research descriptions if you want to emphasize particular methods or applications.
5. Optionally add a headshot as `assets/images/profile.jpg` and then add an `<img>` element to the hero section.

## Run locally
Open `index.html` in a browser. For a local server, run `python -m http.server 8000` from this directory and visit `http://localhost:8000`.

## Publish with GitHub Pages
1. Create a public repository named exactly `mzallaghi4.github.io` under the GitHub account `mzallaghi4`.
2. Upload all files and folders in this project to the repository root (not an enclosing project folder).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then save.
6. After deployment, visit `https://mzallaghi4.github.io/`. Initial publication may take a few minutes.

You can also push from a terminal:

```bash
git init
git add .
git commit -m "Create academic website"
git branch -M main
git remote add origin https://github.com/mzallaghi4/mzallaghi4.github.io.git
git push -u origin main
```

For subsequent updates:

```bash
git add .
git commit -m "Update website"
git push
```

## Editing content
- Main content and links: `index.html`
- Design and responsive layout: `assets/css/style.css`
- Mobile navigation and footer year: `assets/js/main.js`
- Blog articles: create another standalone HTML page in `blog/posts/` and link to it from the Blog section.

The publication and teaching areas intentionally contain prompts rather than invented academic credentials or course history.
