# TREESON Musical Website

A clean, static website for TREESON: An Eco-Musical, rebuilt from the original Squarespace site.

## 📁 Project Structure

```
treeson-site/
├── index.html              # Homepage
├── styles.css              # Main stylesheet
├── images/                 # Image assets
│   ├── forest-hero.jpg    # Hero background image
│   ├── album-cover.jpg    # Album cover for music section
│   └── cast/              # Cast headshots
│       ├── daniele-alancarter.jpg
│       ├── g-victoria-campbell.jpg
│       └── ...            # (16 total cast photos)
└── pages/
    └── cast/              # Individual cast bio pages
        ├── daniele-alancarter.html
        ├── g-victoria-campbell.html
        └── ...            # (16 total pages)
```

## 🖼️ Required Images

You'll need to provide the following images:

### Main Images:
- `images/forest-hero.jpg` - Forest background for hero section (recommended: 1920x1080px)
- `images/album-cover.jpg` - TREESON album cover (square, ~600x600px)
- `images/victoria-campbell.jpg` - Creative team photo
- `images/andrew-coopman.jpg` - Creative team photo  
- `images/joseph-purdue.jpg` - Creative team photo

### Cast Photos (images/cast/):
All cast headshots should be:
- Aspect ratio: 3:4 (portrait)
- Recommended size: 600x800px minimum
- File names (already linked in HTML):
  - `daniele-alancarter.jpg`
  - `g-victoria-campbell.jpg`
  - `simon-bachtiger.jpg`
  - `peter-campbell.jpg`
  - `emett-matthews.jpg`
  - `jenny-mollet.jpg`
  - `stephen-ingram.jpg`
  - `diana-chu.jpg`
  - `sinead-davies.jpg`
  - `sarsi-grace.jpg`
  - `auguste-jankauskaite.jpg`
  - `sarah-waddington.jpg`
  - `aly-carrigan.jpg`
  - `luisa-cortes.jpg`
  - `jacob-didas.jpg`
  - `colin-wardale.jpg`

## 📝 Customization

### Update the Contact Form
In `index.html`, replace the Google Form embed URL:
```html
<iframe src="https://docs.google.com/forms/d/e/YOUR_GOOGLE_FORM_ID/viewform?embedded=true"
```

### Update Social Media Links
In the footer section of all HTML files, update these links:
- Instagram: `https://www.instagram.com/treesonmusical/`
- Facebook: `https://www.facebook.com/treesonmusical/`
- Twitter: `https://twitter.com/treesonmusical`
- YouTube: Update to the correct channel URL

## 🚀 Deployment to GitHub Pages

### Step 1: Create GitHub Repository
```bash
# In your local directory with the files
git init
git add .
git commit -m "Initial commit - TREESON website"
```

### Step 2: Push to GitHub
```bash
# Create a repo on GitHub first (e.g., treeson-musical)
git remote add origin https://github.com/YOUR_USERNAME/treeson-musical.git
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repo on GitHub
2. Click "Settings"
3. Click "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Your site will be live at: `https://YOUR_USERNAME.github.io/treeson-musical/`

### Step 4: Custom Domain (Optional)
To use `www.treesonmusical.com`:

1. In your GitHub repo, create a file named `CNAME` with this content:
   ```
   www.treesonmusical.com
   ```

2. At your domain registrar (e.g., Squarespace Domains, GoDaddy, etc.), add these DNS records:
   ```
   Type: CNAME
   Name: www
   Value: YOUR_USERNAME.github.io
   ```

3. Wait 24-48 hours for DNS propagation

4. GitHub will automatically provision an SSL certificate (HTTPS)

## 🎨 Design Notes

- **Colors**: Dark background (#0a0a0a), sage green accent (#7cb342)
- **Typography**: Clean sans-serif (Helvetica Neue/Arial)
- **Responsive**: Mobile-first design with breakpoints at 768px and 480px
- **Performance**: No external dependencies, pure HTML/CSS
- **File Size**: ~60KB total (before images)

## 📱 Browser Support

- Chrome/Edge (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Local Testing

Simply open `index.html` in a web browser to test locally. No build process or server required!

For a local server (optional):
```bash
# Python 3
python -m http.server 8000

# Then visit: http://localhost:8000
```

## 📄 License

© 2020 TREESON, the Musical. Copyright of G. Victoria Campbell.

## 🐛 Troubleshooting

**Images not showing?**
- Check file paths are correct (case-sensitive on Linux servers)
- Ensure images are in the correct directories
- Verify image file names match exactly

**YouTube video not loading?**
- Verify the video ID is correct: `f0pHObhs-Ds`
- Check that the video is set to "Public" or "Unlisted" on YouTube

**Google Form not displaying?**
- Make sure you've generated the embed code from Google Forms
- The form must be set to accept responses
