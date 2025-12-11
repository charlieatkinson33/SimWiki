# Setup Guide: MediaWiki-Style Features

This guide explains how to enable all MediaWiki-like features for SimWiki. Complete these steps to provide full wiki functionality with user accounts and contributions.

## ✅ What's Already Configured

The following features are already implemented and ready to use:

- ✅ **Edit links** on every page
- ✅ **Version history** via Git commits
- ✅ **User accounts** via GitHub
- ✅ **Recent changes** page
- ✅ **Contribution tracking** automatic via GitHub
- ✅ **Category system** fully implemented
- ✅ **Search functionality** via GitHub and Google
- ✅ **Watch/notification system** via GitHub
- ✅ **User contribution pages** automatic via GitHub profiles
- ✅ **Custom MediaWiki-inspired layout** with tabs and edit buttons
- ✅ **Comprehensive how-to-edit guide** for non-technical users

## 🔧 Required Setup Steps (Repository Owner)

### Step 1: Enable GitHub Discussions (5 minutes)

**Why:** Provides MediaWiki-style "Talk" pages for community discussion.

**How to enable:**

1. Go to your repository settings:
   - Visit: https://github.com/charlieatkinson33/SimWiki/settings

2. Scroll to "Features" section

3. Check the box for **"Discussions"**

4. Click "Set up discussions"

5. Optionally customize discussion categories:
   - **General** - General discussions about the wiki
   - **Ideas** - Suggestions for new content
   - **Q&A** - Questions and answers
   - **Page Discussions** - Discussions about specific pages
   - **Show and tell** - Share your implementations
   - **Technical** - Technical questions about contributing

**Result:** Users can now discuss content, ask questions, and collaborate.

**Links created:**
- Main discussions: https://github.com/charlieatkinson33/SimWiki/discussions
- New discussion: https://github.com/charlieatkinson33/SimWiki/discussions/new

### Step 2: Enable GitHub Pages (Already done)

**Status:** ✅ Already configured via GitHub Actions workflow

**Verify it's working:**
- Go to: https://github.com/charlieatkinson33/SimWiki/settings/pages
- Confirm "Source" is set to "GitHub Actions"
- Check that deployments are succeeding: https://github.com/charlieatkinson33/SimWiki/actions

### Step 3: Configure Branch Protection (5 minutes)

**Why:** Ensures all changes are reviewed before going live (quality control).

**How to enable:**

1. Go to repository settings:
   - Visit: https://github.com/charlieatkinson33/SimWiki/settings/branches

2. Click "Add branch protection rule"

3. For "Branch name pattern" enter: `main`

4. Enable these settings:
   - ✅ **Require a pull request before merging**
   - ✅ **Require approvals** (set to 1)
   - ✅ **Dismiss stale pull request approvals when new commits are pushed**
   - ✅ **Require status checks to pass before merging** (if you have CI/CD)
   - ✅ **Require conversation resolution before merging**
   - ✅ **Include administrators** (optional but recommended)

5. Click "Create" or "Save changes"

**Result:** All edits must be reviewed before going live, preventing spam and vandalism.

### Step 4: Set Up Contributor Permissions (5 minutes)

**Why:** Allows trusted users to review and merge changes.

**How to configure:**

1. Go to repository settings:
   - Visit: https://github.com/charlieatkinson33/SimWiki/settings/access

2. Click "Add people" or "Manage access"

3. Add collaborators by GitHub username:
   - **Triage** - Can manage issues and PRs (no write access)
   - **Write** - Can push changes directly (not recommended for most)
   - **Maintain** - Can manage issues, PRs, and settings (good for moderators)
   - **Admin** - Full access (only for trusted maintainers)

4. Recommended structure:
   - **You (owner):** Admin
   - **Trusted maintainers:** Maintain
   - **Active contributors:** Triage
   - **Everyone else:** Contributor (default, via forks)

**Result:** Distributed maintenance and faster review process.

### Step 5: Configure Notifications (2 minutes)

**Why:** Stay informed of contributions without being overwhelmed.

**Your notification settings:**

1. Go to repository page: https://github.com/charlieatkinson33/SimWiki

2. Click "Watch" button (top right)

3. Choose notification level:
   - **All Activity** - Every issue, PR, discussion (can be overwhelming)
   - **Participating and @mentions** - Only when directly involved (recommended)
   - **Issues and Pull Requests** - Review requests and discussions
   - **Custom** - Choose specific events

4. Recommended for owner:
   - Watch: **Issues and Pull Requests**
   - Receive notifications for: Pull requests, Issues
   - Check GitHub daily or enable email notifications

**Result:** You'll know when contributions need review.

### Step 6: Enable GitHub Wiki (Optional)

**Why:** Provides additional wiki-style documentation area.

**How to enable:**

1. Go to repository settings:
   - Visit: https://github.com/charlieatkinson33/SimWiki/settings

2. Scroll to "Features" section

3. Check the box for **"Wikis"**

4. A wiki will be created at: https://github.com/charlieatkinson33/SimWiki/wiki

**When to use:**
- Main site (GitHub Pages): Primary content, structured pages
- GitHub Wiki: Meta-documentation, community guidelines, quick notes

**Result:** Additional collaborative space for documentation.

### Step 7: Add Issue Templates (Optional, 5 minutes)

**Why:** Helps users report issues and suggest content systematically.

**Status:** You can add templates in `.github/ISSUE_TEMPLATE/` directory.

Example templates to create:
- `bug_report.yml` - Report errors in content
- `content_suggestion.yml` - Suggest new DIY alternatives
- `supplier_update.yml` - Update supplier information
- `question.yml` - Ask questions

**Result:** More organized issue tracking and suggestions.

## 📚 Features Now Available

After completing the setup, users can:

### 1. Create Accounts
- Visit https://github.com/signup
- Free GitHub account
- Works across all open-source projects

### 2. Edit Any Page
- Click "Edit this page" button
- Make changes in web browser
- Submit as pull request
- Automatic review process

### 3. View History
- Every page has "History" link
- See all changes with timestamps
- View who made each edit
- Compare versions

### 4. Discuss Content
- GitHub Discussions enabled
- Community conversations
- Q&A functionality
- Subscribe to topics

### 5. Track Contributions
- Automatic contribution tracking
- Profile shows all edits
- Contribution graphs
- Recognition system

### 6. Watch Changes
- Watch entire repository
- Custom notification preferences
- RSS feeds available
- Email or web notifications

### 7. Search Content
- GitHub code search
- Google site search
- Search discussions and issues
- Filter by type, date, author

### 8. Collaborate
- Comment on pull requests
- Review others' changes
- Mention other users (@username)
- React to contributions

## 🎯 How It Compares to MediaWiki

| MediaWiki Feature | SimWiki Implementation | Status |
|-------------------|------------------------|--------|
| User registration | GitHub accounts | ✅ Ready |
| Page editing | Pull request workflow | ✅ Ready |
| Edit history | Git commit history | ✅ Ready |
| Talk pages | GitHub Discussions | ⚙️ Enable in settings |
| Recent changes | Commit log + Recent changes page | ✅ Ready |
| User contributions | GitHub profile + commits | ✅ Ready |
| Watchlist | GitHub Watch + notifications | ✅ Ready |
| Categories | Category pages | ✅ Ready |
| Search | GitHub + Google | ✅ Ready |
| User permissions | Repository collaborators | ⚙️ Configure as needed |
| Templates | Jekyll includes | ✅ Ready |
| Page protection | Branch protection | ⚙️ Configure in settings |

## 📖 User Documentation

Point users to these pages:

- **[How to Edit](/how-to-edit)** - Complete guide for contributors
- **[User Accounts](/user-accounts)** - GitHub account setup and features
- **[Recent Changes](/recent-changes)** - Track wiki activity
- **[Contribute](/contribute)** - Contribution guidelines
- **[MediaWiki Features](/MEDIAWIKI_FEATURES)** - Feature comparison

## 🎓 Training Contributors

### For Non-Technical Users

Share these resources:
1. **How to Edit guide** - Step-by-step with screenshots
2. **Video tutorial** (recommended to create)
3. **First contribution walkthrough**
4. **Markdown basics** - Simple examples

### For Technical Users

They can use:
- Git command line
- GitHub Desktop
- Text editors with Git integration
- Fork and clone workflow

### For Moderators/Maintainers

Train on:
- Reviewing pull requests
- Managing discussions
- Handling issues
- Using GitHub tools

## 🚀 Promotion and Onboarding

### Announce the Wiki Functionality

Create announcements in:
- GitHub Discussions
- Your simulation community channels
- Social media
- Email to stakeholders

### Key Messages

📢 **"SimWiki now works like Wikipedia!"**
- Anyone can contribute
- Create a free GitHub account
- Edit pages directly in your browser
- All changes reviewed for quality
- Your contributions are credited to you

### First-Time Contributor Experience

Make it easy:
1. Clear "Edit this page" buttons
2. Contribution notice on every page
3. Simple editing guide
4. Welcoming community
5. Fast review process (< 24 hours)

## 🔒 Quality Control

### Review Process

With branch protection enabled:
1. User submits pull request
2. Automated checks run (if configured)
3. Maintainer reviews changes
4. Discussion if needed
5. Approve and merge
6. Auto-deploys to live site

### Preventing Spam and Vandalism

GitHub's system prevents issues:
- All changes reviewed before going live
- Users tracked by account
- Can revert any change
- Can block problem users
- Complete audit trail

### Maintaining Quality

Best practices:
- Review contributions within 24 hours
- Provide constructive feedback
- Welcome new contributors
- Create style guide
- Use templates for consistency

## 📊 Monitoring and Analytics

### Track Wiki Health

Monitor these metrics:
- **Contributors:** https://github.com/charlieatkinson33/SimWiki/graphs/contributors
- **Activity:** https://github.com/charlieatkinson33/SimWiki/pulse
- **Traffic:** https://github.com/charlieatkinson33/SimWiki/graphs/traffic (if enabled)
- **Engagement:** Discussion activity, issue count

### Growth Indicators

Healthy wiki shows:
- Increasing contributors
- Regular contributions
- Active discussions
- Growing page count
- Diverse contributions

## ⚙️ Advanced Configuration

### Custom Domain (Optional)

Point your own domain to GitHub Pages:
1. Add CNAME file with your domain
2. Configure DNS at your registrar
3. Enable HTTPS in settings
4. Update `_config.yml` with new URL

### Automation (Optional)

Set up GitHub Actions for:
- Automated content checks
- Link validation
- Spell checking
- Image optimization
- Scheduled updates

### Integrations (Optional)

Connect external services:
- Analytics (Google Analytics, Plausible)
- Search (Algolia)
- Comments (Giscus - uses GitHub Discussions)
- Monitoring (StatusPage)

## 🆘 Troubleshooting

### Common Issues

**"People can't edit pages"**
- Ensure GitHub Pages is deployed
- Check that edit links are working
- Verify page paths are correct

**"Pull requests not being reviewed"**
- Set up notifications
- Add more maintainers
- Create review reminders

**"Discussions not visible"**
- Enable Discussions in repository settings
- Check that links point to correct URL
- Refresh page

**"Changes not deploying"**
- Check GitHub Actions status
- Review workflow logs
- Verify branch protection settings

### Getting Help

- **GitHub Support:** https://support.github.com/
- **GitHub Community:** https://github.community/
- **Jekyll Documentation:** https://jekyllrb.com/docs/
- **SimWiki Discussions:** After enabled, use for community support

## 📋 Launch Checklist

Before announcing to community:

- [ ] GitHub Discussions enabled
- [ ] Branch protection configured
- [ ] Notifications set up
- [ ] Edit links tested
- [ ] How-to-edit guide reviewed
- [ ] At least one other maintainer added
- [ ] Tested full contribution workflow
- [ ] Announcement prepared
- [ ] Welcome message in Discussions

**Estimated total setup time:** 30-45 minutes

## 🎉 You're Ready!

Once you've completed the setup:

1. **Test the workflow yourself**
   - Make a test edit
   - Submit a pull request
   - Review and approve it
   - Verify it deploys

2. **Announce to community**
   - Share the How to Edit guide
   - Invite contributions
   - Be responsive to first contributors

3. **Maintain momentum**
   - Review contributions promptly
   - Engage in discussions
   - Recognize contributors
   - Continuously improve

**Your wiki is now fully functional with MediaWiki-style features!**

---

## 📞 Questions?

- Review the [MediaWiki Features Guide](/MEDIAWIKI_FEATURES.md)
- Check [GitHub Pages documentation](https://docs.github.com/en/pages)
- Ask in [GitHub Community](https://github.community/)

---

**Last updated:** 2024
**Version:** 1.0
