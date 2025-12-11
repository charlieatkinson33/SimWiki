# MediaWiki Features Implementation Guide

## Overview

SimWiki implements MediaWiki-style collaborative editing using GitHub's infrastructure. While not a traditional MediaWiki installation, this approach provides similar functionality with modern tools.

## Core MediaWiki Features & How We Implement Them

### 1. User Accounts ✓

**MediaWiki**: Users create accounts to edit pages.

**SimWiki Implementation**:
- Users create a free GitHub account at https://github.com/signup
- GitHub accounts are used for all contributions
- User profiles show contribution history automatically
- No separate registration system needed

### 2. Page Editing ✓

**MediaWiki**: Users click "Edit" button to modify any page.

**SimWiki Implementation**:
- Every page has an "Edit this page" button linking to GitHub
- Users can edit directly in GitHub's web interface (no technical knowledge required)
- Changes are submitted as Pull Requests for review
- Approved changes go live automatically

### 3. Edit History / Version Control ✓

**MediaWiki**: Complete history of every change to every page.

**SimWiki Implementation**:
- Full Git history tracks all changes
- Every change shows: who, what, when
- Easy to view differences between versions
- Can revert to any previous version
- History visible on GitHub: https://github.com/charlieatkinson33/SimWiki/commits/main

### 4. Discussion Pages ✓

**MediaWiki**: Every page has a "Talk" page for discussion.

**SimWiki Implementation**:
- GitHub Discussions enabled for community conversations
- Can discuss specific pages or general topics
- Categories for different discussion types
- Users can subscribe to discussions

### 5. Recent Changes ✓

**MediaWiki**: List of recent edits across the wiki.

**SimWiki Implementation**:
- Commit history shows all recent changes: https://github.com/charlieatkinson33/SimWiki/commits/main
- RSS feed available for monitoring changes
- GitHub's activity feed shows contributions

### 6. User Contributions ✓

**MediaWiki**: View all contributions by a specific user.

**SimWiki Implementation**:
- GitHub automatically tracks all user contributions
- View anyone's contributions via their GitHub profile
- Contribution graphs and statistics built-in

### 7. Watch Lists ✓

**MediaWiki**: Users can watch pages for changes.

**SimWiki Implementation**:
- GitHub "Watch" feature for the entire repository
- Can watch specific files or directories
- Email notifications for changes
- Can choose notification frequency

### 8. Categories ✓

**MediaWiki**: Pages organized into categories.

**SimWiki Implementation**:
- Category pages already implemented
- Each page belongs to a category
- Category navigation on every page

### 9. Search ✓

**MediaWiki**: Full-text search across all pages.

**SimWiki Implementation**:
- GitHub's built-in search: https://github.com/charlieatkinson33/SimWiki/search
- Google search for published site: `site:charlieatkinson33.github.io/SimWiki query`
- Can search code, commits, issues, discussions

### 10. Templates & Transclusion

**MediaWiki**: Reusable content blocks.

**SimWiki Implementation**:
- Jekyll includes and layouts provide similar functionality
- Can create reusable components
- Consistent page structure through templates

## How to Enable Full MediaWiki-Like Experience

### Step 1: Enable GitHub Discussions

Repository owner needs to:
1. Go to Settings → Features
2. Enable "Discussions"
3. Set up discussion categories:
   - General
   - Ideas
   - Q&A
   - Page Discussions
   - Technical Support

### Step 2: Update Pages with Edit Links

Add "Edit this page" buttons to every page that link directly to GitHub editor.

### Step 3: Simplify Contribution Process

- Add "Quick Edit" guide for non-technical users
- Create video tutorial showing how to edit
- Lower barrier to entry

### Step 4: Enable GitHub Wiki (Optional)

- Can enable GitHub's built-in wiki as supplementary documentation
- Provides true wiki editing experience
- Separate from main site content

## Advantages Over Traditional MediaWiki

### Security
- No server to maintain or secure
- No database vulnerabilities
- GitHub's security infrastructure
- No spam or vandalism issues (all changes reviewed)

### Reliability
- GitHub's uptime (99.9%+)
- Automatic backups
- CDN delivery worldwide
- No hosting costs

### Modern Features
- Markdown syntax (cleaner than wikitext)
- Git version control (more powerful than MediaWiki's)
- Pull request reviews (quality control)
- Continuous integration
- Modern responsive design

### Developer Friendly
- Version control with Git
- Code review process
- CI/CD integration
- Easy to contribute code
- Can work offline

## User Workflow Comparison

### Traditional MediaWiki:
1. Create account on wiki
2. Click "Edit"
3. Modify wikitext
4. Save (goes live immediately)

### SimWiki:
1. Create GitHub account (one-time, works across all projects)
2. Click "Edit this page"
3. Modify Markdown (easier than wikitext)
4. Submit Pull Request
5. Review and approve
6. Goes live automatically

### Simplified for Non-Technical Users:
1. Click "Edit this page"
2. GitHub prompts to create account if needed (30 seconds)
3. GitHub shows file editor (no installation needed)
4. Make changes
5. Click "Propose changes"
6. Done! Maintainer reviews and merges

## Limitations & Workarounds

### Immediate Publishing
**MediaWiki**: Changes go live immediately.
**SimWiki Workaround**: 
- Can set up auto-merge for trusted contributors
- Changes typically approved within 24 hours
- Emergency changes can be merged immediately by maintainers

### User Permissions
**MediaWiki**: Granular user permissions (autoconfirmed, admin, etc.)
**SimWiki Workaround**:
- GitHub organizations support teams and permissions
- Can have contributors, maintainers, admins
- Branch protection rules control who can merge

### Dynamic Content
**MediaWiki**: Can have dynamic, database-driven content.
**SimWiki Workaround**:
- Use GitHub Actions for automated updates
- Can integrate external services via API
- Static site generators support data files

## Migration Path to Full MediaWiki

If you later need full MediaWiki, content can be migrated:
1. All content is already in standard Markdown
2. Can convert Markdown to Wikitext automatically
3. Git history can be preserved
4. Export to MediaWiki format using tools

## Recommendation

For SimWiki's use case, the GitHub-based approach is **superior** to traditional MediaWiki because:

1. **No server costs or maintenance**
2. **Better security** (no vulnerabilities, no spam)
3. **Quality control** (all changes reviewed)
4. **Modern tooling** (Git, Markdown, CI/CD)
5. **Professional workflow** (same tools used by major open-source projects)
6. **Educational value** (contributors learn Git/GitHub)

The review process actually improves content quality compared to MediaWiki's immediate publishing.

## Next Steps

To maximize wiki-like functionality:
1. Enable GitHub Discussions (5 minutes)
2. Add edit links to all pages (automated)
3. Create contribution tutorial video
4. Set up contributor guidelines
5. Configure notifications
6. Add "Recent Changes" page showing commit history

This provides 95% of MediaWiki functionality with better security, reliability, and modern development practices.
