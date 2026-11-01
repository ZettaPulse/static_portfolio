# ZettaPulse Portfolio

A responsive, dark-themed static portfolio highlighting Priyam Anand's backend,
cloud, and AI engineering experience and the ZettaPulse contributors.

## Features

- Personal introduction and career highlights
- Backend, cloud, DevOps, and AI services
- Three experience-based case studies and an illustrative architecture flow
- Technical skills and resume-listed certifications
- Contributor profiles, GitHub and LinkedIn links, and email contact
- Responsive layout, animated details, and reduced-motion support

## Run locally

No build step or package installation is required. From this directory, run:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000>.

You can also open `index.html` directly, though a local web server more closely
matches static hosting behavior.

## Deploy to Vercel

Import the GitHub repository into Vercel. This repository's root contains the
site files, so use the default root directory and configure:

- **Framework Preset:** Other
- **Build Command:** leave empty
- **Output Directory:** `.`
- **Install Command:** leave empty

Vercel can then deploy the static HTML, CSS, JavaScript, and image assets
directly.

## Project files

- `index.html` — portfolio content and page structure
- `styles.css` — styling, responsive layouts, and animations
- `script.js` — mobile navigation, scroll progress, and reveal effects
- `assets/` — contributor portraits used by the page

The source-only `Reference/` directory is intentionally excluded from Git; it
contains the original resume and reference materials, which are not needed to
build or deploy the site.
