# 🚀 Quick Start Guide

## You're 3 Steps Away From Going Live!

### Step 1: Get Your Images (1-2 hours)
The website code is complete, but you need to add images:

**Download the treeson-site folder** (it's ready in your outputs)

**Add images to these locations:**
```
treeson-site/
  images/
    forest-hero.jpg         ← Hero background
    album-cover.jpg         ← Album cover
    victoria-campbell.jpg   ← Creative team
    andrew-coopman.jpg      ← Creative team
    joseph-purdue.jpg       ← Creative team
    cast/
      daniele-alancarter.jpg  ← All 16 cast headshots
      g-victoria-campbell.jpg
      ... (14 more)
```

**Where to get the images:**
- Log into Squarespace → Download from media library
- OR use browser DevTools on the live site to find image URLs
- OR extract from your screenshots (lower quality)

See `IMAGE_GUIDE.md` for detailed instructions.

### Step 2: Deploy to GitHub (30 minutes)

**A. Create GitHub Account** (if needed)
- Go to https://github.com/
- Sign up (free)

**B. Create Repository**
- Click the "+" icon → "New repository"
- Name it "treeson-musical" (or whatever you prefer)
- Make it public or private
- Don't add README/gitignore (we have them)
- Click "Create repository"

**C. Upload Your Files**
Option 1 - Using Git (recommended):
```bash
cd treeson-site
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/treeson-musical.git
git branch -M main
git push -u origin main
```

Option 2 - Using GitHub Web Interface:
- Click "uploading an existing file"
- Drag and drop all files from treeson-site folder
- Click "Commit changes"

**D. Enable GitHub Pages**
1. Go to repository → Settings → Pages
2. Source: Select "main" branch
3. Click Save
4. Wait 2-5 minutes
5. Visit: `https://YOUR_USERNAME.github.io/treeson-musical/`

### Step 3: Point Your Domain (5 minutes + 24-48 hours propagation)

**A. Create CNAME file in your GitHub repo:**
- Create new file named `CNAME` (no extension)
- Add this single line: `www.treesonmusical.com`
- Commit the file

**B. Update DNS at your domain registrar:**
Go to wherever you manage www.treesonmusical.com and add:
```
Type: CNAME
Name: www
Value: YOUR_USERNAME.github.io
TTL: 3600 (or Auto)
```

**C. Wait for DNS propagation** (24-48 hours)
- GitHub will auto-provision SSL certificate
- Your site will be live at www.treesonmusical.com

## ✅ Pre-Launch Checklist

Before going live, update these in `index.html`:

- [ ] Replace Google Form URL: Search for "YOUR_GOOGLE_FORM_ID"
- [ ] Verify YouTube video ID is correct (currently: f0pHObhs-Ds)
- [ ] Check all social media links in footer
- [ ] Test locally by opening index.html in browser
- [ ] Verify all cast member links work

## 💰 Cost Breakdown

| Item | Current (Squarespace) | New (GitHub Pages) |
|------|----------------------|-------------------|
| Hosting | $12-27/month | $0/month |
| Domain | ~$20/year | ~$20/year |
| SSL | Included | Free (auto) |
| **Total** | **$144-324/year** | **$20/year** |
| **Savings** | | **$124-304/year** |

## 🎯 What You're Getting

✅ **Complete Website** - All pages built and styled
✅ **16 Cast Bios** - Individual pages for each cast member  
✅ **Responsive Design** - Works on mobile, tablet, desktop
✅ **YouTube Integration** - Embedded video player
✅ **Contact Form** - Google Forms embed (you add your form)
✅ **Professional Design** - Matches original Squarespace aesthetic
✅ **Fast Performance** - Loads in <1 second (before images)
✅ **Free Hosting** - GitHub Pages at no cost
✅ **Custom Domain** - Use www.treesonmusical.com
✅ **HTTPS/SSL** - Automatic and free

## 📚 Documentation Included

- **README.md** - Full documentation
- **PROJECT_SUMMARY.md** - What was built and why
- **IMAGE_GUIDE.md** - How to get and optimize images  
- **DEPLOYMENT.md** - Step-by-step deployment checklist
- **This file** - Quick start guide

## 🆘 Need Help?

**Common Questions:**

**Q: I'm not technical. Can I do this?**
A: Yes! The GitHub web interface is user-friendly. Just upload files and enable Pages. No coding required.

**Q: What if I want to make changes later?**
A: Edit the HTML files, commit to GitHub, and the site auto-updates. Or hire someone for $50-100 for updates.

**Q: Can I still use Squarespace during testing?**
A: Yes! Test at `username.github.io/repo-name` first. Only switch DNS when ready.

**Q: What if something breaks?**
A: GitHub keeps version history. You can revert to any previous version with one click.

**Q: Do I need to keep paying Squarespace?**
A: Only until you've verified the new site works perfectly. Then cancel.

## 🎉 You're Ready!

1. Download the `treeson-site` folder
2. Add your images (follow IMAGE_GUIDE.md)
3. Upload to GitHub (follow DEPLOYMENT.md)
4. Go live!

**Estimated time investment:** 2-3 hours total
**Estimated annual savings:** $124-304

Questions? Check the documentation files or GitHub Pages documentation at https://docs.github.com/en/pages

---

**Pro tip:** Test everything locally first (just open index.html in your browser) before deploying to GitHub. This catches any issues early!
