# GitHub Pages Setup Instructions

This repository is configured to deploy automatically to GitHub Pages.

## Automatic Deployment

The site will automatically build and deploy when changes are pushed to the `main` or `master` branch.

## Manual Setup Required (One-Time)

To enable GitHub Pages for this repository, the repository owner needs to:

1. Go to the repository settings: https://github.com/charlieatkinson33/SimWiki/settings/pages

2. Under "Build and deployment":
   - **Source**: Select "GitHub Actions"

3. The workflow file `.github/workflows/jekyll-gh-pages.yml` is already configured and will run automatically.

## Viewing the Site

Once deployed, the site will be available at:
**https://charlieatkinson33.github.io/SimWiki/**

## Local Development (Optional)

To test the site locally:

```bash
# Install Ruby 3.x (if not already installed)

# Install dependencies
bundle install

# Serve the site locally
bundle exec jekyll serve

# Visit http://localhost:4000/SimWiki/
```

## Repository Structure

```
SimWiki/
├── _config.yml          # Jekyll configuration
├── index.md             # Home page
├── categories.md        # Categories overview
├── categories/          # Individual category pages
│   ├── task-trainers.md
│   ├── manikins.md
│   ├── recording-equipment.md
│   ├── assessment-tools.md
│   ├── consumables.md
│   ├── monitoring-equipment.md
│   ├── props-environment.md
│   └── technology.md
├── about.md             # About page
├── contribute.md        # Contribution guide
├── assets/
│   └── css/
│       └── style.scss   # Custom styling
└── .github/
    └── workflows/
        └── jekyll-gh-pages.yml  # GitHub Actions deployment
```

## Theme

The site uses the Jekyll Slate theme with custom CSS overrides for styling.

## Editing Content

All content is written in Markdown (.md files). Simply edit the files and commit to update the website.

## Troubleshooting

### Site not building
- Check the Actions tab for build errors
- Ensure GitHub Pages is enabled in repository settings
- Verify the workflow has permissions to deploy

### Links not working
- Ensure all internal links use relative paths
- Check that the `baseurl` in `_config.yml` matches the repository name

### Custom CSS not applying
- Verify `assets/css/style.scss` has front matter (the `---` at the top)
- Check that the theme is properly imported

## Support

For issues or questions:
- Open an issue in the repository
- Check Jekyll documentation: https://jekyllrb.com/docs/
- GitHub Pages documentation: https://docs.github.com/en/pages
