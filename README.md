# Internetions Bowls — Static Site

This repository contains a static website (HTML/CSS and images). The project is set up to deploy to GitHub Pages using a GitHub Actions workflow.

How to publish:

1. Create a GitHub repository and copy the `git` remote URL.
2. Run locally:

```bash
git remote add origin <your-repo-url>
git push -u origin main
```

3. After pushing, the GitHub Actions workflow will deploy the site to the `gh-pages` branch automatically.

Notes:
- Make sure your default branch is named `main` (or update the workflow trigger).
- The workflow publishes the repository root as the site. If you have build steps, modify the workflow accordingly.
