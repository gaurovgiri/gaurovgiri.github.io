# TODO: Prepare Portfolio Site for First Blog Post

This checklist will help you remove all example/placeholder content and prepare your portfolio site for publishing your first blog post.

## 🎯 Priority Tasks (Do These First)

### 1. ✅ Complete About Page
**Status:** ⚠️ Contains placeholder content  
**File:** `_tabs/about.md`

**Current Issue:**
```
> Add Markdown syntax content to file `_tabs/about.md`{: .filepath } and it will show up on this page.
```

**Action Required:**
- [X] Replace the placeholder prompt with your actual bio
- [X] Write about your background as an AI Engineer
- [X] Mention your interests (AI, music, community building)
- [X] Add your education and work experience
- [X] Include your skills and technologies you work with
- [X] Add projects you've worked on
- [X] Consider adding photos or media

**Example structure:**
```markdown
---
icon: fas fa-info-circle
order: 4
---

# About Me

## Who I Am
[Your introduction]

## What I Do
[Your work and expertise]

## My Journey
[Your background story]

## Skills & Technologies
[List your tech stack]

## Connect With Me
[Social links or contact info]
```

---

### 2. 📝 Write Your First Blog Post
**Status:** ⚠️ No posts yet  
**Location:** `_posts/` folder

**Action Required:**
- [ ] Create your first blog post file following this naming convention:
  - Format: `YYYY-MM-DD-title-of-post.md`
  - Example: `2025-10-24-my-first-blog-post.md`
  
**Template for your first post:**
```markdown
---
title: "Your Engaging Title Here"
date: 2025-10-24 10:00:00 +0545  # Nepal timezone
categories: [Technology, AI]  # Choose relevant categories
tags: [ai, machine-learning, portfolio]  # Add relevant tags
image:
  path: /assets/img/posts/your-image.jpg  # Optional featured image
  alt: Image description
---

## Introduction

Your engaging opening paragraph...

## Main Content

Your blog post content here...

## Conclusion

Wrap up your thoughts...
```

**Blog Post Ideas:**
- [ ] Introduction post: "Hello World - My Journey into AI Engineering"
- [ ] Technical tutorial related to your work
- [ ] Reflection on a project you've completed
- [ ] Insights about AI/ML trends
- [ ] Your experience building this portfolio site

---

## 🔧 Configuration & Settings

### 3. ⚙️ Review and Update _config.yml
**Status:** ✅ Mostly configured, needs verification  
**File:** `_config.yml`

**Items to verify/complete:**
- [x] `title`: "Gaurav Giri" ✅
- [x] `tagline`: Set ✅
- [x] `url`: "https://gauravgiri.com.np" ✅
- [x] `github.username`: "gaurovgiri" ✅
- [x] `twitter.username`: "gaurovgiri" ✅
- [x] `social.name`: "Gaurav Giri" ✅
- [x] `social.email`: Set ✅
- [x] `avatar`: Set to 'assets/img/Gaurav Giri.png' ✅
- [ ] `timezone`: **NEEDS SETTING!** (Suggested: `Asia/Kathmandu`)

**Optional but Recommended:**
- [ ] Set up Google Analytics (`analytics.google.id`)
- [ ] Configure GoatCounter for page views (`analytics.goatcounter.id`)
- [ ] Enable comments system (choose: disqus, utterances, or giscus)
  - Configure `comments.provider` and the corresponding settings
- [ ] Add site verification codes for search engines:
  - `webmaster_verifications.google`
  - `webmaster_verifications.bing`

---

### 4. 🌐 Domain & Deployment

**CNAME Status:** ✅ Configured  
**Current:** `www.gauravgiri.com.np`

**Action Required:**
- [ ] Verify DNS settings for your domain point to GitHub Pages
  - Should point to your GitHub Pages: `gaurovgiri.github.io`
- [ ] Ensure HTTPS is enabled in GitHub repository settings
- [ ] Test that `https://www.gauravgiri.com.np` resolves correctly
- [ ] Test that `https://gauravgiri.com.np` (without www) also works

---

## 🎨 Branding & Assets

### 5. 🖼️ Verify Images and Favicons
**Status:** ⚠️ Needs verification  
**Location:** `assets/img/`

**Current images found:**
- `Gaurav Giri.png` (used as avatar)
- `logo.png`
- `logo2.png`
- `logo-minimal.png`
- `favicons/favicon.png`

**Action Required:**
- [ ] Verify `Gaurav Giri.png` is your actual photo/avatar
- [ ] Check if `logo.png`, `logo2.png`, `logo-minimal.png` are your branding or placeholders
- [ ] Generate proper favicons (multiple sizes needed):
  - [ ] Use a favicon generator (e.g., [RealFaviconGenerator](https://realfavicongenerator.net/))
  - [ ] Generate: 16x16, 32x32, 180x180, 192x192, 512x512 sizes
  - [ ] Add `apple-touch-icon.png`, `manifest.json`, `browserconfig.xml`
  - [ ] Place all favicon files in `assets/img/favicons/`
- [ ] Prepare a social preview image (1200x630px recommended)
  - [ ] Update `social_preview_image` in `_config.yml` if needed

---

### 6. 📱 Social Media Integration
**Status:** ⚠️ Partially configured  
**Files:** `_data/contact.yml`, `_config.yml`

**Currently enabled in contact.yml:**
- [x] GitHub
- [x] Twitter (X)
- [x] Email
- [x] RSS

**Optional additions to uncomment/add:**
- [ ] LinkedIn (you have it in _config.yml social links, consider adding to contact.yml)
- [ ] Instagram (you have it in _config.yml, consider adding to contact.yml)
- [ ] Mastodon
- [ ] Stack Overflow
- [ ] Bluesky
- [ ] Reddit
- [ ] Threads

**Action Required:**
- [ ] Review `_data/contact.yml` and uncomment/configure desired platforms
- [ ] Ensure consistency between `_config.yml` social links and `_data/contact.yml`

---

## 📚 Content Preparation

### 7. 📄 Review Static Pages
**Location:** `_tabs/` folder

**Pages to review:**
- [ ] `about.md` - **CRITICAL: Has placeholder content**
- [ ] `archives.md` - Auto-generated, should work once posts are added
- [ ] `categories.md` - Auto-generated, should work once posts are added  
- [ ] `tags.md` - Auto-generated, should work once posts are added

---

### 8. 🗑️ Clean Up Example/Development Files

**Action Required:**
- [ ] Review and possibly remove or update `README.md`
  - Current README is well-written and helpful for others
  - Consider keeping it as-is if you want to help others use the theme
  - Or simplify it to be more portfolio-focused
- [ ] Keep `.placeholder` file in `_posts/` until you add your first post
- [ ] Remove after adding first real post

---

## 🚀 Pre-Launch Checklist

### 9. 🧪 Testing

**Before publishing your first post:**
- [ ] Test the site locally using Docker:
  ```bash
  docker compose up
  ```
  Then visit `http://localhost:4000`
  
- [ ] Verify all pages load correctly:
  - [ ] Home page
  - [ ] About page
  - [ ] Archives page
  - [ ] Categories page
  - [ ] Tags page
  
- [ ] Test your first blog post:
  - [ ] Post appears on home page
  - [ ] Post has correct date, title, categories, tags
  - [ ] Images load correctly
  - [ ] Code syntax highlighting works (if applicable)
  - [ ] Table of contents generates properly
  
- [ ] Test responsive design:
  - [ ] Desktop view
  - [ ] Tablet view
  - [ ] Mobile view
  
- [ ] Test navigation:
  - [ ] All internal links work
  - [ ] Social media links work
  - [ ] RSS feed works (`/feed.xml`)
  
- [ ] Test SEO:
  - [ ] Page titles are correct
  - [ ] Meta descriptions are present
  - [ ] Social preview images work

---

### 10. 🔍 SEO & Performance

**Action Required:**
- [ ] Submit sitemap to Google Search Console
  - Sitemap URL: `https://www.gauravgiri.com.np/sitemap.xml`
- [ ] Submit sitemap to Bing Webmaster Tools
- [ ] Add Google Analytics tracking code (optional)
- [ ] Set up search console verification codes in `_config.yml`
- [ ] Test site speed with PageSpeed Insights
- [ ] Verify RSS feed is working: `/feed.xml`

---

## 📋 Optional Enhancements

### 11. 💬 Comments System (Optional)
**Current Status:** Not configured

**Options:**
1. **Disqus** - Popular but ads on free tier
2. **Utterances** - Uses GitHub issues, clean and free
3. **Giscus** - Uses GitHub Discussions, modern and free

**If you want comments:**
- [ ] Choose a provider
- [ ] Set up account/configuration
- [ ] Update `comments.provider` in `_config.yml`
- [ ] Fill in the provider-specific settings

---

### 12. 📊 Analytics (Optional)
**Current Status:** Not configured

**Options to consider:**
- [ ] Google Analytics 4 (most popular)
- [ ] GoatCounter (privacy-friendly, simple)
- [ ] Umami (self-hosted, privacy-focused)
- [ ] Matomo (self-hosted)
- [ ] Cloudflare Web Analytics (privacy-focused)
- [ ] Fathom (paid, privacy-focused)

---

### 13. 🎨 Theme Customization (Optional)

**If you want to customize the look:**
- [ ] Modify color scheme in `_sass/themes/`
- [ ] Customize fonts in `_sass/base/_typography.scss`
- [ ] Add custom CSS in `_sass/`
- [ ] Set `theme_mode` in `_config.yml` (light/dark/auto)

---

## ✅ Final Pre-Publish Checklist

**Before you announce your blog to the world:**

- [ ] ✅ Timezone is set in `_config.yml`
- [ ] ✅ About page has real content (not placeholder)
- [ ] ✅ First blog post is written and published
- [ ] ✅ All images load correctly
- [ ] ✅ Favicons are generated and working
- [ ] ✅ Domain is working correctly
- [ ] ✅ SSL/HTTPS is enabled
- [ ] ✅ Social media links all work
- [ ] ✅ Site tested on mobile and desktop
- [ ] ✅ No console errors in browser
- [ ] ✅ RSS feed is working
- [ ] ✅ SEO meta tags are correct
- [ ] ✅ README updated (if desired)
- [ ] ✅ Personal information is accurate everywhere

---

## 🎉 Launch Day!

**When you're ready to share:**
- [ ] Push final changes to GitHub
- [ ] Wait for GitHub Pages to build (check Actions tab)
- [ ] Do final check of live site
- [ ] Share on social media:
  - [ ] Twitter/X
  - [ ] LinkedIn
  - [ ] Instagram
  - [ ] Other platforms
- [ ] Update your social media bios to link to your new blog

---

## 📝 Notes

**Important Files to Never Commit:**
- Local environment files
- Personal API keys/tokens
- Draft posts you're not ready to publish (keep in a separate folder outside the repo)

**Git Workflow:**
- Main branch: `blog` (as per your repo)
- Consider creating drafts in a separate branch
- Use meaningful commit messages

**Backup Strategy:**
- Your blog is already backed up on GitHub ✅
- Consider backing up your images separately
- Keep drafts in a separate folder/notes app

---

## 🆘 Need Help?

**Resources:**
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [Chirpy Theme Documentation](https://github.com/cotes2020/jekyll-theme-chirpy)
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

**Issues to Watch For:**
- Build failures in GitHub Actions
- Broken images or links
- Timezone issues with post dates
- Mobile responsiveness issues

---

## 🎯 Quick Start Guide (TL;DR)

**Minimum steps to publish your first blog:**

1. Set timezone in `_config.yml`: `timezone: Asia/Kathmandu`
2. Write About page in `_tabs/about.md`
3. Create first blog post in `_posts/2025-10-24-my-first-post.md`
4. Test locally with `docker compose up`
5. Commit and push to GitHub
6. Share with the world! 🎉

---

**Last Updated:** October 24, 2025  
**Next Review:** After publishing first blog post

---

Good luck with your blog, Gaurav! 🚀✨
