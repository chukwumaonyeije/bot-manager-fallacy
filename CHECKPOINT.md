# 📋 Project Checkpoint - Doctors Who Code Blog

**Last Updated:** November 18, 2025  
**Status:** ✅ Six blog posts published and deployed

---

## 🎯 Current Status

### Published Articles (6 total)

1. **🧠 The Bot Manager Fallacy: Why Doctors Won't Be Supervising AI**
   - File: `blog/bot-manager-fallacy.md`
   - Topics: bot manager fallacy, future of physicians, AI in medicine, clinical AI workflows
   - Status: ✅ Published

2. **📝 The Disappearing Note: How Automation Is Rewriting Clinical Documentation**
   - File: `blog/the-disappearing-note.md`
   - Topics: clinical documentation, ambient scribe, AI documentation, EHR automation, CodeCraftMD
   - Status: ✅ Published

3. **❤️ Empathy as the Last Mile: Why AI Doesn't Win When It Ignores the Gut Feeling**
   - File: `blog/empathy-as-the-last-mile.md`
   - Topics: empathy in medicine, AI and patient care, human side of medicine, patient-centered care
   - Status: ✅ Published

4. **💻 Coding the Coder: Why Physicians Must Understand Their Own Algorithms**
   - File: `blog/coding-the-coder.md`
   - Topics: algorithmic literacy, doctors who code, clinical algorithms, physician autonomy, CodeCraftMD
   - Status: ✅ Published

5. **🩺 Procedure as Protection: How Hands-On Skill Becomes a Physician's Moat**
   - File: `blog/procedure-as-protection.md`
   - Topics: procedural skills, hands-on medicine, AI-proof skills, physician training
   - Status: ✅ Published

6. **🎓 Teaching Tomorrow's Doctors: A Curriculum for an AI-Augmented Clinical School**
   - File: `blog/teaching-tomorrows-doctors.md`
   - Topics: medical education, AI in medical school, clinical curriculum, physician training
   - Status: ✅ Published

---

## 🌐 Site Information

### Repository
- **GitHub:** https://github.com/chukwumaonyeije/bot-manager-fallacy
- **Branch:** main
- **Last Commit:** 271a2aa - "Add five new blog posts to complete AI in medicine series"

### Live Site
- **URL:** https://chukwumaonyeije.github.io/bot-manager-fallacy/
- **Platform:** GitHub Pages
- **Theme:** Minima (Jekyll)

### Configuration
- **Base URL:** `/bot-manager-fallacy`
- **Site Title:** Doctors Who Code
- **Author:** Dr. Chukwuma Onyeije
- **Email:** info@codecraftmd.com

---

## 📁 Project Structure

```
bot-manager-fallacy/
├── _config.yml              # Jekyll configuration
├── index.md                 # Homepage
├── Gemfile                  # Ruby dependencies
├── README.md                # Repository documentation
├── CHECKPOINT.md            # This file (project checkpoint)
├── blog/
│   ├── index.md             # Blog index page
│   ├── bot-manager-fallacy.md
│   ├── the-disappearing-note.md
│   ├── empathy-as-the-last-mile.md
│   ├── coding-the-coder.md
│   ├── procedure-as-protection.md
│   └── teaching-tomorrows-doctors.md
└── assets/
    └── images/              # Banner images (placeholders referenced)
```

---

## 🚀 Coming Soon (Planned Articles)

Listed in `blog/index.md`:

1. **The Future of Clinical Documentation: Ambient Scribe → EvidenceMD → CodeCraftMD**
   - Deep dive into the documentation automation pipeline
   - How tools integrate to eliminate manual charting

2. **Beyond the Hype: What AI Actually Gets Wrong in Clinical Practice**
   - Real-world AI failures in clinical settings
   - Common pitfalls and how to avoid them

3. **The Physician as Product Designer: Building Tools That Actually Help**
   - How clinicians can shape the tools they use
   - CodeCraftMD case study

---

## 🎨 Missing Assets

All blog posts reference banner images that need to be created:

- `assets/images/bot-manager-fallacy-banner.png` ✅ (likely exists)
- `assets/images/disappearing-note-banner.png` ⚠️
- `assets/images/empathy-last-mile-banner.png` ⚠️
- `assets/images/coding-the-coder-banner.png` ⚠️
- `assets/images/procedure-as-protection-banner.png` ⚠️
- `assets/images/teaching-tomorrows-doctors-banner.png` ⚠️

**Note:** Posts will display without banners if images don't exist. Consider creating these later.

---

## 🛠️ Technical Setup

### Local Development

To run the site locally:

```bash
# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve

# View at
http://localhost:4000/bot-manager-fallacy/
```

### Deployment

Changes automatically deploy to GitHub Pages when pushed to `main` branch:

```bash
git add .
git commit -m "Your commit message"
git push origin main
```

Wait 1-2 minutes for GitHub Pages to rebuild.

---

## 📝 Writing New Articles

### Template for New Blog Posts

```markdown
---
layout: default
title: "🔹 Your Article Title"
description: "Brief description for SEO (150-160 characters)"
author: "Dr. Chukwuma Onyeije"
date: YYYY-MM-DD
keywords:
  - keyword 1
  - keyword 2
  - keyword 3
---

![Banner]({{ site.baseurl }}/assets/images/your-banner.png)

[← Back to Blog]({{ site.baseurl }}/blog/)  
[🏠 DoctorsWhoCode Home]({{ site.baseurl }}/)

---

# **Your Article Title**

*By Dr. Chukwuma Onyeije | Maternal–Fetal Medicine  
Founder, CodeCraftMD and Doctors Who Code*

---

[Your content here]

---

[← Back to Blog]({{ site.baseurl }}/blog/)  
[🏠 DoctorsWhoCode Home]({{ site.baseurl }}/)
```

### Steps to Add New Article

1. **Create the markdown file** in `blog/` directory
2. **Add front matter** with title, description, keywords
3. **Update `blog/index.md`** to add the article to the index
4. **Commit and push** to GitHub
5. **Verify** on live site after deployment

---

## 🎯 Series Theme

**Core Message:** AI won't replace physicians, but it will transform what physicians do. The future belongs to doctors who:
- Understand algorithms
- Master procedures
- Lead with empathy
- Design workflows
- Code when necessary

**Voice:** Authoritative, clinically grounded, reflective, practical, and forward-looking

**Audience:** Physicians, medical students, residents, healthcare technologists, medical educators

---

## 📊 SEO Strategy

### Primary Keywords
- doctors who code
- AI in medicine
- clinical AI workflows
- CodeCraftMD
- physician autonomy
- medical automation
- future of physicians

### Content Strategy
- Long-form, in-depth articles (2000-3000 words)
- Strong narrative structure
- Clinical credibility + tech literacy
- Actionable insights
- Series continuity

---

## 🔗 Social Links

- **Twitter/X:** @CodeCraftMD
- **GitHub:** chukwumaonyeije
- **LinkedIn:** chukwumaonyeije
- **Email:** info@codecraftmd.com

---

## 📅 Next Steps

1. ✅ Verify all six articles are live on GitHub Pages
2. ⚠️ Create banner images for new articles
3. 📝 Draft next article from "Coming Soon" list
4. 🎨 Consider custom CSS for better styling
5. 📊 Add analytics (optional - Google Analytics ID in _config.yml)
6. 🔗 Share articles on LinkedIn, Twitter, medical communities
7. 📱 Create social media snippets/graphics

---

## 💡 Future Enhancements

- Add search functionality
- Create RSS feed (already configured via jekyll-feed)
- Add comments section (Disqus or similar)
- Create downloadable PDF versions
- Build email newsletter signup
- Add related articles section
- Create series page grouping related articles
- Mobile optimization review

---

## 🆘 Troubleshooting

### Site not updating after push?
- Check GitHub Actions tab for build status
- GitHub Pages can take 1-2 minutes to rebuild
- Clear browser cache
- Verify `_config.yml` baseurl is correct

### Images not showing?
- Verify path uses `{{ site.baseurl }}/assets/images/filename.png`
- Check file exists in correct directory
- Ensure proper capitalization (case-sensitive on Linux servers)

### Local Jekyll not working?
```bash
bundle update
bundle install
bundle exec jekyll serve
```

---

**🎉 Congratulations! Your blog series is live and ready for the world.**

Visit your blog at: **https://chukwumaonyeije.github.io/bot-manager-fallacy/**
