# Privacy Policy - Grammar & Typo Fix

This repository contains the privacy policy for the Grammar & Typo Fix Chrome extension.

## Files

- `privacy.html` - The privacy policy page that can be deployed as a GitHub Page

## Deploying as GitHub Pages

To deploy the privacy policy as a GitHub Page, follow these steps:

### Option 1: Deploy from the root directory (Recommended)

1. Go to your repository settings on GitHub
2. Navigate to **Settings** → **Pages**
3. Under **Source**, select:
   - **Branch**: `main` (or your default branch)
   - **Folder**: `/ (root)`
4. Click **Save**
5. GitHub will automatically deploy your site. The privacy policy will be available at:
   - `https://[your-username].github.io/[repository-name]/privacy.html`

### Option 2: Rename to index.html

If you want the privacy policy to be the main page of your GitHub Pages site:

1. Rename `privacy.html` to `index.html`
2. Follow the steps in Option 1
3. Your site will be available at:
   - `https://[your-username].github.io/[repository-name]/`

### Option 3: Use a docs folder

1. Create a `docs` folder in your repository
2. Move `privacy.html` into the `docs` folder
3. In GitHub repository settings → **Pages**, select:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or your default branch)
   - **Folder**: `/docs`
4. Click **Save**
5. Your privacy policy will be available at:
   - `https://[your-username].github.io/[repository-name]/privacy.html`

## Accessing the Privacy Policy

Once deployed, you can access the privacy policy at:
- `https://[your-username].github.io/[repository-name]/privacy.html`

Replace `[your-username]` with your GitHub username and `[repository-name]` with your repository name.

## Notes

- GitHub Pages typically takes a few minutes to deploy after you push changes
- Make sure your repository is public (or you have GitHub Pro/Team/Enterprise) to use GitHub Pages
- The privacy policy is a standalone HTML file with embedded CSS, so it doesn't require any additional dependencies
