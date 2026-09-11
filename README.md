# Personal Portfolio

A single-page personal portfolio site — plain HTML, CSS, and JS, no build step. Deployed with GitHub Pages.

## Structure

- `index.html` — page content (hero, about, skills, projects, experience, contact)
- `style.css` — styling, including light/dark theme via CSS variables
- `script.js` — mobile nav, theme toggle, scroll reveal

## Customize

Everything in `index.html` marked "Your Name", "Project One", etc. is placeholder — replace with your own bio, skills, projects, experience, and links (GitHub, LinkedIn, email).

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
```

## Deploy

Pushing to the `main` branch auto-deploys via the GitHub Actions workflow in `.github/workflows/deploy.yml`.
