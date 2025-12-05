# SimWiki Deployment Guide

## Quick Start

The SimWiki website is ready to be deployed on GitHub Pages. Follow these steps:

### 1. Enable GitHub Pages

1. Go to your repository on GitHub: https://github.com/charlieatkinson33/SimWiki
2. Click on **Settings** (in the top menu)
3. Scroll down and click on **Pages** (in the left sidebar under "Code and automation")
4. Under "Build and deployment":
   - Source: Select **"Deploy from a branch"**
   - Branch: Select **copilot/create-simulation-alternatives-website**
   - Folder: Select **/ (root)**
5. Click **Save**

### 2. Wait for Deployment

- GitHub Actions will automatically build and deploy your site
- This typically takes 1-2 minutes
- You can monitor progress in the "Actions" tab

### 3. Access Your Website

Once deployed, your website will be available at:
**https://charlieatkinson33.github.io/SimWiki/**

## Website Structure

```
SimWiki/
├── index.html              # Homepage
├── categories.html         # All categories overview
├── about.html             # About page
├── styles.css             # Stylesheet
├── _config.yml            # GitHub Pages config
├── README.md              # Repository documentation
└── categories/            # Category pages
    ├── task-trainers.html
    ├── network-cameras.html
    ├── manikins.html
    ├── iv-training.html
    ├── wound-simulation.html
    ├── av-systems.html
    ├── monitoring.html
    ├── environments.html
    ├── airway-management.html
    ├── phlebotomy.html
    ├── control-systems.html
    └── pediatric.html
```

## Features

### Completed Pages (with full content)
- **Task Trainers**: DIY suturing pads, intubation trainers, catheterization models
- **Network Cameras**: IP camera systems, recording solutions (up to 99% savings)
- **Manikins**: CPR trainers, high-fidelity simulators, pediatric options
- **IV Training Aids**: Homemade venipuncture arms and cannulation practice equipment
- **Wound Simulation**: DIY moulage recipes using household items
- **Audio/Video Systems**: Budget recording and debriefing setups

### Placeholder Pages (ready for content)
- Monitoring Equipment
- Simulation Environments
- Airway Management
- Phlebotomy Training
- Control Systems
- Pediatric Simulation

## Cost Savings Examples

The website demonstrates significant potential savings:
- Task trainers: Up to 98% cost reduction
- Network cameras: Up to 99% savings vs. commercial systems
- Manikins: Up to 99% with hybrid approaches
- Complete 4-room simulation center: £50,000-£200,000+ savings

## Customization

### Adding New Categories
1. Create a new HTML file in the `categories/` folder
2. Copy the structure from an existing category page
3. Update the content with your new category information
4. Add a link to the new category on `categories.html` and `index.html`

### Updating Styling
- Edit `styles.css` to change colors, fonts, or layout
- The current theme uses a purple gradient (#667eea to #764ba2)

### Content Updates
- All pages use simple HTML structure
- No build process required - just edit and push
- Changes will be live within minutes after pushing to GitHub

## Support

For issues or questions about the website:
- Check the GitHub repository for documentation
- Refer to [GitHub Pages documentation](https://docs.github.com/en/pages)

## License

This project is open source and available for educational use.
