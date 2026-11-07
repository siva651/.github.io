# Siva Manikanta Reddy — Portfolio

This repository deploys the static portfolio to GitHub Pages.

- The deployable source archive is stored as binary chunks under `deploy/`.
- Deployment workflow: `.github/workflows/pages.yml`
- Target branch: `main`
- Pages URL: https://siva651.github.io/.github.io/

A push to `main` concatenates the archive chunks, extracts the static site and publishes it using GitHub Pages. No build step or application backend is required.

The site source includes semantic HTML, CSS, native JavaScript modules, GSAP, a procedural Three.js scene, Canvas fallback and the supplied résumé PDF.
