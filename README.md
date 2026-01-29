# extension-privacy-policies

Privacy policy pages for my demo/test Chrome extensions. Hosted via GitHub Pages (docs/), each extension has its own policy page and a shared umbrella policy. Used for Chrome Web Store listings (unlisted demos) and client reviews.

## GitHub Pages Setup

This repository uses GitHub Pages to host privacy policy documentation.

### Enabling GitHub Pages

To enable GitHub Pages for this repository:

1. Go to your repository on GitHub
2. Navigate to **Settings** > **Pages**
3. Under "Build and deployment":
   - **Source**: Select "Deploy from a branch"
   - **Branch**: Select `main` and `/docs` folder
   - Click **Save**
4. Wait a few minutes for GitHub to build and deploy the site
5. Your privacy policies will be available at: `https://[username].github.io/extension-privacy-policies/`

### Structure

- **`docs/index.md`**: Umbrella privacy policy covering all extensions
- **`docs/demo-reader.md`**: Specific privacy policy for the Demo Reader extension
- **`docs/_config.yml`**: Jekyll configuration with minimal theme

### Customization

Before publishing, update the placeholders in the privacy policy documents:

- `[DATE]`: Replace with the current date (e.g., "January 29, 2026")
- `[DEVELOPER NAME]`: Replace with your name or organization name
- `[CONTACT_EMAIL]`: Replace with your contact email address
- `[BRIEF_DESCRIPTION]`: In extension-specific policies, add a brief description of what the extension does

### Adding New Extensions

To add a privacy policy for a new extension:

1. Create a new file in the `docs/` directory (e.g., `docs/new-extension.md`)
2. Use `docs/demo-reader.md` as a template
3. Update the umbrella policy (`docs/index.md`) to link to the new extension policy
