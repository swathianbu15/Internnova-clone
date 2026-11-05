# InternNova Homepage Redesign

A responsive, static homepage redesign created as a student internship project.

## Project structure

```text
InternNova_Redesign/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── img/
│   └── README.md
└── README.md
```

## Run locally
1. Extract the ZIP.
2. Open the folder in VS Code.
3. Open `index.html` in a browser, or use the VS Code Live Server extension.

No build step or backend is required.

## Features
- Responsive desktop, tablet and mobile layout
- Separate HTML, CSS and JavaScript files
- Mobile navigation with accessible expanded state
- Scroll progress indicator
- Scroll reveal animations with reduced-motion support
- Functional FAQ accordion using native HTML details/summary
- Official InternNova links for internships, premium tracks, events, login, privacy and terms
- SEO description, semantic sections and accessible navigation labels

## Deployment
### GitHub Pages
1. Create a GitHub repository, for example `internnova-homepage-redesign`.
2. Upload the contents of this folder (make sure `index.html` is at the repository root).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then save.
6. Wait for the deployment and open the generated Pages URL.

## Important submission notes
- This is an independent redesign concept, not an official InternNova website.
- Content and public figures were aligned with information visible on the official website at the time of preparation. Recheck details before final submission.
- Statistics are attributed to the official website and are not independently audited.
- Testimonials were intentionally not fabricated.
- Certificate verification and student services link to the official site because a static frontend cannot securely verify certificates or access private student data without an authorised backend/API.
- External fonts and Lucide icons load from their CDNs; internet access is needed for those assets. The page itself remains usable if those assets fail.
- The `img/` folder is reserved for project-owned images. The visual hero illustration is built with HTML/CSS so the project does not depend on unlicensed stock photos.
