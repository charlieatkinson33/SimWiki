---
layout: default
title: How to Edit Pages - SimWiki
---

# How to Edit SimWiki Pages

SimWiki works just like Wikipedia - anyone can edit! We use GitHub for collaboration, which provides better quality control and security than traditional wikis.

## 🚀 Quick Start (30 seconds)

1. **Click "Edit this page"** on any page
2. **Make your changes** in the editor
3. **Click "Propose changes"** at the bottom
4. **Done!** A maintainer will review and publish your edit

No software installation needed. Everything happens in your web browser.

---

## 📝 Step-by-Step Guide for First-Time Contributors

### Step 1: Create a GitHub Account (if you don't have one)

GitHub is a platform used by millions of developers and is free to use.

1. Go to [github.com/signup](https://github.com/signup)
2. Enter your email address
3. Create a password
4. Choose a username
5. Verify your account (check your email)
6. **That's it!** This account works across all GitHub projects

**Why GitHub?**
- Free and secure
- Professional version control
- Used by Wikipedia, Microsoft, Google, and millions of others
- All changes are tracked and attributed to you
- Your contributions build your profile

### Step 2: Navigate to the Page You Want to Edit

Browse SimWiki and find the page you want to improve:
- [Categories](/SimWiki/categories) - Browse all content
- [Search](https://github.com/charlieatkinson33/SimWiki/search) - Find specific content
- [Home](/SimWiki/) - Start from the homepage

### Step 3: Click "Edit this page"

Every page has an "Edit this page" button at the top. This opens the GitHub editor.

**What happens next:**
- If you're not logged in, you'll be prompted to log in
- GitHub will create your own copy of the page (called a "fork")
- You'll see the page content in Markdown format

### Step 4: Make Your Changes

You'll see the page content in **Markdown** format. Don't worry - it's easier than it looks!

#### Markdown Basics

```markdown
# This is a heading
## This is a subheading
### This is a smaller subheading

**Bold text**
*Italic text*

- Bullet point
- Another bullet point

1. Numbered list
2. Second item

[Link text](https://example.com)

![Image description](image-url.jpg)
```

#### Common Edits

**Adding a new alternative:**
```markdown
### DIY Blood Pressure Cuff

**Cost:** £15  
**Time:** 1 hour  
**Difficulty:** Easy

**Materials:**
- Item 1 - £5
- Item 2 - £10

**Instructions:**
1. First step
2. Second step
```

**Fixing a typo:**
Just change the text directly!

**Adding a supplier:**
```markdown
**Supplier:** [Supplier Name](https://supplier-url.com)
**Price:** £50
```

**Updating costs:**
Simply change the price numbers.

### Step 5: Preview Your Changes (Optional)

Click the "Preview" tab to see how your changes will look.

### Step 6: Describe Your Changes

At the bottom of the page, you'll see:

**"Propose changes"**

1. **Summary**: Briefly describe what you changed (e.g., "Updated IV arm cost" or "Added new suture pad alternative")
2. **Extended description** (optional): Add more details if needed

### Step 7: Submit Your Edit

Click the green **"Propose changes"** button.

This creates what's called a "Pull Request" - a request to include your changes in the wiki.

### Step 8: Wait for Review

A maintainer will review your changes (usually within 24 hours) and:
- **Approve** - Your changes go live automatically!
- **Request changes** - They'll comment with suggestions
- **Discuss** - They might ask questions

You'll receive an email notification about the status.

---

## 🎯 What Should You Edit?

### Good Edits We Love

✅ **Fixing errors**
- Typos and grammar
- Broken links
- Incorrect information
- Outdated prices

✅ **Adding information**
- New suppliers
- Better instructions
- Safety warnings
- Cost updates
- Alternative methods

✅ **Improving clarity**
- Better explanations
- More detail
- Clearer instructions
- Additional photos/diagrams

✅ **New content**
- DIY alternatives you've built
- Cost comparisons
- Step-by-step guides
- Supplier recommendations

### Edits That Need Discussion First

⚠️ **Major changes**
- Restructuring entire pages
- Removing large sections
- Changing the purpose of a page

For these, please [open a discussion](https://github.com/charlieatkinson33/SimWiki/discussions) first!

---

## 🔧 Advanced Editing

### Editing Multiple Files

To add images or edit multiple pages:

1. **Fork the repository** (GitHub will prompt you)
2. **Make changes** to multiple files
3. **Submit one Pull Request** with all changes

### Adding Images

1. Upload images to `/assets/images/category-name/`
2. Reference in Markdown: `![Description](/SimWiki/assets/images/category/filename.jpg)`

### Creating New Pages

1. Click "Add file" → "Create new file" in the repository
2. Name your file: `filename.md`
3. Add front matter:
```yaml
---
layout: default
title: Your Page Title
---
```
4. Write your content
5. Submit as Pull Request

---

## 🤝 Collaboration Features

### Discussions

Can't decide if an edit is right? Start a discussion!

- [General Discussion](https://github.com/charlieatkinson33/SimWiki/discussions)
- Ask questions
- Propose ideas
- Get community feedback

### Issue Tracking

Found a problem but can't fix it yourself?

- [Report an Issue](https://github.com/charlieatkinson33/SimWiki/issues)
- Describe the problem
- Others can pick it up

### Watch for Changes

Want to be notified of changes?

1. Go to the [repository](https://github.com/charlieatkinson33/SimWiki)
2. Click "Watch" at the top
3. Choose notification preferences

---

## 📚 Learning Resources

### Never Used Markdown?

- [Markdown Guide](https://www.markdownguide.org/basic-syntax/) - 5-minute tutorial
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- Practice in the GitHub editor - it has live preview!

### New to GitHub?

- [GitHub Hello World](https://guides.github.com/activities/hello-world/) - 10-minute intro
- [GitHub Docs](https://docs.github.com/en/get-started) - Comprehensive guides
- The SimWiki community is here to help!

### Video Tutorials

Coming soon! We're creating video guides for:
- Your first edit
- Adding images
- Creating new pages
- Using discussions

---

## 🆘 Getting Help

### Common Issues

**"I clicked Edit but nothing happened"**
- Make sure you're logged into GitHub
- Try clicking again
- Check if pop-up blockers are interfering

**"My changes aren't showing up"**
- Changes need to be reviewed first (usually < 24 hours)
- Check your Pull Request status
- You'll get an email when it's approved

**"I made a mistake in my edit"**
- No problem! You can edit your Pull Request before it's approved
- Or just submit a new edit after it's merged
- All changes can be reverted if needed

**"The Markdown is confusing"**
- Use the Preview tab to see results
- Copy formatting from existing pages
- Ask in [Discussions](https://github.com/charlieatkinson33/SimWiki/discussions)

**"I want to help but don't know what to edit"**
- Check [open issues](https://github.com/charlieatkinson33/SimWiki/issues)
- Look for "good first issue" labels
- Browse pages and fix typos you find
- Add information about equipment you use

### Get Support

**For editing help:**
- [GitHub Discussions](https://github.com/charlieatkinson33/SimWiki/discussions) - Ask the community
- [Report an Issue](https://github.com/charlieatkinson33/SimWiki/issues) - Technical problems

**For content questions:**
- Comment on the relevant page's Pull Request
- Start a discussion about the topic

---

## 🌟 Benefits of Contributing

### For You

- **Build your portfolio** - All contributions are on your GitHub profile
- **Learn new skills** - Git, Markdown, web development
- **Share your expertise** - Help the simulation community
- **Professional recognition** - Your name on contributions
- **Networking** - Connect with other educators

### For the Community

- **Better content** - More accurate and comprehensive
- **Cost savings** - Help others save thousands
- **Innovation** - Share creative solutions
- **Collaboration** - Build collective knowledge
- **Accessibility** - Make simulation education affordable

---

## 🎓 From Beginner to Expert

### Your First Edit (Start Here!)

1. Find a typo
2. Click "Edit this page"
3. Fix the typo
4. Submit!

**You're now a contributor!** 🎉

### Your Fifth Edit

Try something more substantial:
- Add a supplier you know
- Update a cost
- Improve instructions
- Add safety information

### Your Tenth Edit

You're becoming an expert! Consider:
- Creating new pages
- Adding images
- Restructuring content
- Helping other contributors

### Regular Contributor

- Join discussions
- Review others' contributions
- Suggest new features
- Help maintain content quality

---

## 📜 Rules and Guidelines

### Do's

✅ Be respectful and constructive  
✅ Provide accurate information  
✅ Cite sources where appropriate  
✅ Follow existing formatting  
✅ Include safety warnings  
✅ Give credit to others  

### Don'ts

❌ Plagiarize or copy copyrighted content  
❌ Promote specific brands commercially  
❌ Include false or misleading information  
❌ Post spam or irrelevant content  
❌ Share patient or confidential information  

### Content License

By contributing, you agree to license your content under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). This means:
- Your content can be used and modified by others
- You'll be credited for your contribution
- Derivatives must use the same license
- You retain your copyright

---

## 🚀 Ready to Start?

1. **Browse** the wiki and find something to improve
2. **Click** "Edit this page"
3. **Make** your changes
4. **Submit** and wait for review
5. **Celebrate** when your edit goes live!

Every expert was once a beginner. Your first edit might feel uncertain, but you're helping thousands of simulation educators by contributing. Thank you for being part of SimWiki!

---

## 📞 Questions?

- [Start a Discussion](https://github.com/charlieatkinson33/SimWiki/discussions/new)
- [Check Existing Discussions](https://github.com/charlieatkinson33/SimWiki/discussions)
- [View Contribution Guide]({{ '/contribute' | relative_url }})

**Happy editing!** 📝

---

[Back to Home](/) | [View All Categories](/categories) | [About SimWiki](/about)
