# GitHub Pages Setup Instructions

This guide will help you configure GitHub Pages for the IAM Audit Utility documentation.

## Quick Setup Steps

1. **Go to Repository Settings**
   - Navigate to your repository on GitHub
   - Click on "Settings" tab
   - Scroll down to "Pages" in the left sidebar

2. **Configure GitHub Pages Source**
   - Under "Build and deployment"
   - Source: Select "Deploy from a branch"
   - Branch: Select "main" (or your default branch)
   - Folder: Select "/ (root)"
   - Click "Save"

3. **Wait for Deployment**
   - GitHub Pages will take 1-2 minutes to build and deploy
   - You'll see a message: "Your site is live at https://username.github.io/repository-name/"

4. **Access Your Documentation**
   - The root URL will redirect to `docs/` automatically
   - Main documentation hub: `https://username.github.io/repository-name/docs/`

## What We've Configured

The following files have been added/updated to support GitHub Pages:

- **`_config.yml`**: Jekyll configuration for markdown processing and relative links
- **`index.html`**: Root page that redirects to the docs folder

## How It Works

1. GitHub Pages uses Jekyll to process markdown files
2. The `_config.yml` enables GitHub Flavored Markdown (GFM)
3. Relative links are automatically converted
4. Emojis and special formatting are preserved
5. The root `index.html` redirects visitors to the documentation

## Troubleshooting

If you still see raw markdown:
1. Verify GitHub Pages is enabled in repository settings
2. Check that the build completed successfully (green checkmark in Actions tab)
3. Clear your browser cache and refresh
4. Try accessing the site in an incognito/private window
