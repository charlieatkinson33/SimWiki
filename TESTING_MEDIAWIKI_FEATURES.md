# Testing MediaWiki Features - SimWiki

This document explains how to test all the MediaWiki-style features that have been implemented.

## ✅ What Has Been Implemented

### Core Wiki Features

1. **Custom Layout with MediaWiki-Style Interface** (`_layouts/default.html`)
   - Wikipedia-style tabs (Article, Discussion, History)
   - "Edit this page" button (prominent blue button)
   - "View history" button
   - "Discuss" button
   - Contribution notice on every page
   - Page metadata footer
   - Enhanced sidebar navigation

2. **User Accounts System** (`user-accounts.md`)
   - Complete guide to GitHub accounts
   - How to create an account
   - Security features (2FA)
   - Profile management
   - Contribution tracking
   - Privacy controls
   - Comparison with traditional wiki accounts

3. **How to Edit Guide** (`how-to-edit.md`)
   - Step-by-step for first-time contributors
   - Markdown tutorial
   - Common editing tasks
   - Screenshot placeholders for future video guide
   - Troubleshooting section
   - From beginner to expert progression

4. **Recent Changes Page** (`recent-changes.md`)
   - Links to commit history
   - Pending pull requests view
   - Discussion activity
   - Filtering options
   - RSS feeds
   - Statistics and graphs

5. **MediaWiki Features Documentation** (`MEDIAWIKI_FEATURES.md`)
   - Complete feature comparison
   - How each MediaWiki feature is implemented
   - Advantages over traditional MediaWiki
   - Migration path if needed

6. **Setup Guide** (`SETUP_MEDIAWIKI_FEATURES.md`)
   - Step-by-step for repository owner
   - Enable GitHub Discussions
   - Configure branch protection
   - Set up collaborators
   - Complete checklist

7. **Issue Templates** (`.github/ISSUE_TEMPLATE/`)
   - Bug report template
   - Content suggestion template
   - Configuration with helpful links

8. **Discussion Templates** (`.github/DISCUSSION_TEMPLATE/`)
   - General discussion template
   - Guidance for users

9. **Pull Request Template** (`.github/PULL_REQUEST_TEMPLATE.md`)
   - Structured contribution format
   - Checklist for contributors
   - Type of change categories

10. **Updated Configuration** (`_config.yml`)
    - Wiki features enabled
    - Community links configured
    - Navigation updated with new pages

11. **Updated README** (`README.md`)
    - Prominent wiki features section
    - Clear call-to-action for contributors
    - Links to all documentation

## 🧪 Testing Checklist

### Pre-Deployment Testing

- [x] YAML syntax validation for all config files
- [x] Front matter present in all new .md files
- [x] Relative URL paths use correct format
- [x] Issue templates are valid YAML
- [x] Discussion templates are valid YAML
- [x] _config.yml is valid
- [x] All new pages have proper layout specified
- [ ] GitHub Pages builds successfully (requires push)
- [ ] Edit links point to correct GitHub URLs
- [ ] History links work correctly
- [ ] Discussion links work (after Discussions enabled)

### Post-Deployment Testing

Once deployed to GitHub Pages, test:

#### Visual Testing

1. **Homepage**
   - [ ] New layout renders correctly
   - [ ] Wiki tabs appear at top (Article, Discussion, History)
   - [ ] Edit buttons are visible and styled correctly
   - [ ] Contribution notice displays
   - [ ] Sidebar navigation includes new pages
   - [ ] All links work

2. **New Pages**
   - [ ] `/how-to-edit` loads and renders properly
   - [ ] `/user-accounts` loads and renders properly
   - [ ] `/recent-changes` loads and renders properly
   - [ ] `/MEDIAWIKI_FEATURES` loads (or is linked from About)
   - [ ] All internal links work
   - [ ] All external GitHub links work

3. **Category Pages**
   - [ ] Edit buttons appear on category pages
   - [ ] Layout is consistent across all pages
   - [ ] Navigation works

4. **Mobile Responsiveness**
   - [ ] Pages render well on mobile
   - [ ] Edit buttons are accessible
   - [ ] Navigation is usable

#### Functionality Testing

1. **Edit Workflow**
   - [ ] Click "Edit this page" button
   - [ ] Redirects to GitHub editor
   - [ ] Correct file opens for editing
   - [ ] Can make changes
   - [ ] Can submit pull request

2. **History Links**
   - [ ] Click "View history" button
   - [ ] Redirects to GitHub commits page
   - [ ] Shows correct file history
   - [ ] Can view diffs

3. **Discussion Links**
   - [ ] Click "Discuss" button
   - [ ] Redirects to GitHub Discussions (once enabled)
   - [ ] Can create new discussion
   - [ ] Can participate in discussions

4. **Recent Changes**
   - [ ] All GitHub links work
   - [ ] Commit history is accessible
   - [ ] Pull requests list loads
   - [ ] Discussions list loads (once enabled)
   - [ ] RSS feeds work

5. **User Account Flow**
   - [ ] Can navigate to user accounts page
   - [ ] All GitHub signup/login links work
   - [ ] Documentation is clear and accurate

6. **Contribution Flow**
   - [ ] New user can find "How to Edit" guide
   - [ ] Can follow guide to make first edit
   - [ ] Pull request template appears correctly
   - [ ] Submission process is clear

#### GitHub Integration Testing

1. **Issues**
   - [ ] Issue templates appear when creating new issue
   - [ ] Bug report template works
   - [ ] Content suggestion template works
   - [ ] Config links work

2. **Pull Requests**
   - [ ] PR template appears for new pull requests
   - [ ] Template is helpful and clear
   - [ ] Checklist renders properly

3. **Discussions** (requires enabling)
   - [ ] Discussion template appears
   - [ ] Can create discussions
   - [ ] Categories are set up appropriately

## 🎨 Visual Features to Verify

### Layout Elements

Check that these appear on all pages:

1. **Header Section**
   - Site title and description
   - "View on GitHub" button

2. **Wiki Tabs Bar**
   - Light background (#f8f9fa)
   - Three tabs: Article, Discussion, History
   - Active tab (Article) highlighted
   - Tabs have hover effects

3. **Page Tools Bar**
   - Floats to the right
   - Three buttons: Edit, History, Discuss
   - Edit button is blue and prominent
   - Buttons have icons (emojis)
   - Hover effects work

4. **Contribution Notice**
   - Blue left border
   - Light background
   - Welcoming message
   - Clear call-to-action

5. **Content Area**
   - Main content renders correctly
   - Markdown formatting works
   - Links are styled correctly

6. **Footer Section**
   - Page modification information
   - Links to history and contributors
   - License information
   - Wikipedia-style styling

7. **Sidebar**
   - Navigation section with new pages
   - Community section with GitHub links
   - Resources section with helpful links

### Style Verification

1. **Colors**
   - Link blue: #0645ad
   - Visited link purple: #0b0080
   - Background gray: #f8f9fa
   - Border gray: #a2a9b1

2. **Typography**
   - Sans-serif for body text
   - Serif for headings (Linux Libertine/Georgia fallback)
   - Proper line height and spacing

3. **Interactive Elements**
   - Buttons have hover states
   - Links are underlined on hover
   - Cards have subtle hover effects

## 🔗 Link Verification

### Internal Links (Relative URLs)

Verify these work:
- `/` - Homepage
- `/categories` - Categories overview
- `/about` - About page
- `/contribute` - Contribute guide
- `/how-to-edit` - How to edit guide
- `/recent-changes` - Recent changes
- `/user-accounts` - User accounts guide
- `/MEDIAWIKI_FEATURES` - Feature documentation

### GitHub Links (External URLs)

Verify these work:
- `https://github.com/charlieatkinson33/SimWiki` - Repository home
- `https://github.com/charlieatkinson33/SimWiki/discussions` - Discussions (after enabled)
- `https://github.com/charlieatkinson33/SimWiki/issues` - Issues
- `https://github.com/charlieatkinson33/SimWiki/pulls` - Pull requests
- `https://github.com/charlieatkinson33/SimWiki/commits/main` - Commit history
- `https://github.com/charlieatkinson33/SimWiki/graphs/contributors` - Contributors
- `https://github.com/signup` - GitHub signup

### Dynamic Edit Links

Each page should have an edit link formatted as:
`https://github.com/charlieatkinson33/SimWiki/edit/main/[PAGE_PATH]`

For example:
- Edit index.md: `/edit/main/index.md`
- Edit about.md: `/edit/main/about.md`
- Edit category page: `/edit/main/categories/task-trainers.md`

### Dynamic History Links

Each page should have a history link formatted as:
`https://github.com/charlieatkinson33/SimWiki/commits/main/[PAGE_PATH]`

## 🚀 Deployment Testing

### GitHub Actions Workflow

1. **Check Workflow Status**
   - Go to: https://github.com/charlieatkinson33/SimWiki/actions
   - Verify latest workflow run succeeded
   - Check build logs if there are errors

2. **Deployment Status**
   - Go to: https://github.com/charlieatkinson33/SimWiki/deployments
   - Verify successful deployment to GitHub Pages
   - Check deployment time

3. **Pages Settings**
   - Go to: https://github.com/charlieatkinson33/SimWiki/settings/pages
   - Verify "Source" is set to "GitHub Actions"
   - Check that site is published

### Live Site Testing

1. **Access the Site**
   - Go to: https://charlieatkinson33.github.io/SimWiki/
   - Verify site loads
   - Check for any 404 errors

2. **Browser Testing**
   - Test in Chrome/Edge
   - Test in Firefox
   - Test in Safari (if available)
   - Test on mobile device

3. **Performance**
   - Page loads quickly
   - No broken images
   - All CSS loads properly
   - No JavaScript errors

## 🐛 Known Issues and Limitations

### Limitations

1. **Immediate Publishing**
   - Unlike MediaWiki, changes require review (feature, not bug)
   - Addresses spam and vandalism concerns

2. **GitHub Account Required**
   - Users need GitHub account (free)
   - No anonymous editing (security feature)

3. **Discussions Require Enabling**
   - Repository owner must enable GitHub Discussions
   - One-time 5-minute setup

### Potential Issues

1. **CSS Path**
   - If CSS doesn't load, check `baseurl` in `_config.yml`
   - Verify Jekyll theme is installed

2. **404 on New Pages**
   - If new pages show 404, wait for site rebuild
   - Check GitHub Actions for build status

3. **Edit Links Don't Work**
   - Verify repository name in `_config.yml`
   - Check that `page.path` variable is available

## 📊 Success Metrics

After deployment, measure:

1. **Contributor Engagement**
   - Number of new contributors
   - Pull requests submitted
   - Issues opened
   - Discussions started (after enabled)

2. **Content Growth**
   - New pages created
   - Existing pages improved
   - Total contributions

3. **Community Health**
   - Response time to contributions
   - Contributor retention
   - Discussion participation

## 🆘 Troubleshooting

### Issue: Site doesn't build

**Possible causes:**
- YAML syntax error
- Missing dependencies
- Theme not loading

**Solutions:**
- Check GitHub Actions logs
- Validate YAML files
- Review Gemfile dependencies

### Issue: Edit buttons don't appear

**Possible causes:**
- Layout not applied to pages
- CSS not loading
- JavaScript issue

**Solutions:**
- Verify front matter has `layout: default`
- Check CSS loads in browser dev tools
- Review layout HTML

### Issue: Links are broken

**Possible causes:**
- Incorrect baseurl
- Wrong path format
- File doesn't exist

**Solutions:**
- Check `_config.yml` baseurl setting
- Use relative URLs consistently
- Verify file paths

## ✅ Final Checklist

Before announcing to users:

- [ ] All pages load correctly
- [ ] Edit buttons work on all pages
- [ ] History links work
- [ ] GitHub Discussions enabled
- [ ] Issue templates tested
- [ ] PR template tested
- [ ] Mobile responsive
- [ ] All links work
- [ ] Documentation is accurate
- [ ] Setup guide followed
- [ ] At least one test contribution made
- [ ] Branch protection configured

## 📸 Screenshots Needed

For documentation, capture:
- [ ] Homepage with new layout
- [ ] Edit button and wiki tabs
- [ ] Contribution notice
- [ ] Sidebar navigation
- [ ] How to Edit page
- [ ] User Accounts page
- [ ] Recent Changes page
- [ ] Edit workflow (GitHub editor)
- [ ] Pull request submission
- [ ] Mobile view

## 📝 Documentation Updates

After testing, update:
- [ ] Add screenshots to How to Edit guide
- [ ] Create video tutorial (optional)
- [ ] Update IMPLEMENTATION_SUMMARY.md
- [ ] Add success stories as they come
- [ ] Document any issues found

---

## 🎉 Testing Complete?

Once all tests pass:
1. Enable GitHub Discussions
2. Announce to community
3. Monitor first contributions
4. Iterate based on feedback
5. Celebrate the wiki launch! 🎊

---

**Last Updated:** 2024
**Tester:** Repository maintainer
**Status:** Ready for deployment
