# Ember Support Site

A beautiful, professional support website for Ember that can be hosted on GitHub Pages.

## Files Included

- `index.html` - Main support page with FAQ, contact info, and features
- `privacy.html` - Privacy Policy
- `app-icon.png` - App icon asset

## Deploying to GitHub Pages

### Option 1: Create a New Repository (Recommended)

1. **Create a new GitHub repository:**
   - Go to [github.com/new](https://github.com/new)
   - Name it `ember-support`
   - Make it **Public**
   - Click "Create repository"

2. **Upload the files:**
   - Click "uploading an existing file"
   - Drag and drop all files
   - Click "Commit changes"

3. **Enable GitHub Pages:**
   - Go to repository Settings > Pages
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

4. **Your site will be live at:**
   ```
   https://edgarpielb.github.io/ember-support/
   ```

### Option 2: Add to Existing Repository

If you have an existing repo, you can:

1. Create a `docs` folder in your repository
2. Copy the files into `docs/`
3. Go to Settings > Pages
4. Select "Deploy from branch" > main > `/docs`

## Using in App Store Connect

1. Once deployed, use this URL as your **Support URL**:
   ```
   https://edgarpielb.github.io/ember-support/
   ```

2. Use this URL for **Privacy Policy URL**:
   ```
   https://edgarpielb.github.io/ember-support/privacy.html
   ```

## Customization

- **Support Email:** Currently set to `habitglassapp@gmail.com` - update in both HTML files if needed
- **Colors:** Edit the CSS variables in `:root` to match your brand
- **FAQ:** Add or modify questions in the FAQ section of `index.html`

## Testing Locally

Simply open `index.html` in any web browser to preview the site.
