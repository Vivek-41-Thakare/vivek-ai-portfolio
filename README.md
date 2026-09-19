# Vivek Thakare — Portfolio

A responsive static portfolio website built for GitHub Pages.

## Files

- `index.html` — portfolio content
- `style.css` — responsive design
- `script.js` — scroll reveal + active navigation
- `assets/vivek-profile.jpeg` — profile image
- `assets/Vivek-Thakare-Resume.pdf` — resume

## Run locally

Just open `index.html` in a browser.

For a local server (recommended):

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish on GitHub Pages

### Option 1 — Project URL

Create a public GitHub repository, for example:

`vivek-portfolio`

Upload all files from this folder to the repository.

Then:

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**.
5. Save.
6. GitHub will publish the site.

Your URL will look like:

`https://YOUR-USERNAME.github.io/vivek-portfolio/`

### Option 2 — Clean personal URL

Create the repository:

`YOUR-USERNAME.github.io`

Upload the same files to the root of that repository.

Your portfolio will then be:

`https://YOUR-USERNAME.github.io/`

## Important

The project information and experience text in this version are based on the supplied resume. Project-specific live-demo/repository URLs were not invented where they were not provided.
