# SiteForge Studio

A responsive, dark-themed landing page for a web design studio. Built with plain HTML, CSS and JavaScript so it can be hosted directly on GitHub Pages without a build step.

## Live website

After the GitHub Pages workflow completes, the site should be available at:

https://sadikfinance.github.io/Portfolio-/

## Deployments

Every push to `main` runs the workflow in `.github/workflows/deploy-pages.yml` and publishes the root of the repository to GitHub Pages.

If the first deployment does not start, open the repository's **Settings → Pages** and select **GitHub Actions** as the build and deployment source.

## Before accepting customer enquiries

The current contact button uses a placeholder email address (`hello@siteforgestudio.example`). Replace it in `index.html` with a real address before publishing it for customers. No real phone number or WhatsApp number has been configured yet.

## Files

- `index.html` — responsive landing page and styling
- `.github/workflows/deploy-pages.yml` — automatic GitHub Pages deployment
