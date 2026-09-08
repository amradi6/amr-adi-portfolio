# Amr Adi Portfolio

A fast, dependency-free portfolio site for Amr Adi — Flutter Developer and Java / Spring Boot Backend Developer.

## Run locally

No package installation is required. From the repository root, start any local static server:

```bash
# Python
python -m http.server 4173

# Or use VS Code / WebStorm Live Server
```

Then open `http://localhost:4173`.

## Build

There is no compile step: `index.html`, `styles.css`, and `script.js` are production-ready static assets. Before publishing, check the page at desktop and mobile widths and replace the social placeholder URLs in `index.html`.

## Deploy to Vercel

1. Push this repository to GitHub.
2. In Vercel, choose **Add New Project** and import the repository.
3. Select **Other** as the framework preset. Leave Build Command blank and set the Output Directory to `.`.
4. Deploy. Vercel will serve `index.html` directly.

To use `amradi.me`, add the domain under the Vercel project’s **Domains** settings. Configure the DNS records Vercel provides at your domain registrar, then wait for verification and TLS provisioning.

## Content to personalize

- Replace the GitHub and LinkedIn placeholder links in the footer with the real profile URLs.
- A CV PDF was not available as a staged attachment, so no misleading download link was added. To add one, place the file at `assets/amr-adi-cv.pdf` and add a download CTA in `index.html`.
- Update the copyright year if the site is launched after 2025.
