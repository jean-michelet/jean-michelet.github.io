# Jean Michelet site

Static Astro portfolio built for GitHub Pages.

## Local development

```bash
npm install
npm run dev
```

## Deployment

1. Push the repository to GitHub.
2. In the repository settings, enable GitHub Pages and select **GitHub Actions** as the source.
3. Update `public/CNAME` if the final custom domain changes.
4. Update the `site` URL in `astro.config.mjs` if the production URL changes.

The workflow in `.github/workflows/deploy.yml` builds and publishes the Astro output. Do not use
GitHub Pages' branch-based Jekyll deployment for this project.
