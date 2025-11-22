# Image Extraction Guide

Since you have screenshots of the current Squarespace site, you'll need to extract images for the new site.

## Quick Image Extraction Methods

### Method 1: From Squarespace (Easiest)
1. Log into your Squarespace site
2. Go to Design → Custom CSS or your pages
3. Download images directly from the media library
4. Or use browser DevTools to find image URLs and download them

### Method 2: From Screenshots
For the cast photos visible in your screenshots:
1. Open each screenshot in an image editor (Photoshop, GIMP, etc.)
2. Use the rectangular selection tool to crop each headshot
3. Save as JPG with the correct filename
4. Aim for consistent sizing (600x800px works well)

### Method 3: From Live Site
Using browser Developer Tools:
1. Visit https://www.treesonmusical.com/
2. Right-click on an image → "Inspect"
3. Find the `<img>` tag and copy the `src` URL
4. Download the image from that URL
5. Rename to match the required filename

## Required Images Checklist

### Hero Section
- [ ] `images/forest-hero.jpg` - The forest background from the hero section

### Music Section  
- [ ] `images/album-cover.jpg` - TREESON album cover (visible in your screenshots)

### Creative Team (for homepage)
- [ ] `images/victoria-campbell.jpg`
- [ ] `images/andrew-coopman.jpg`
- [ ] `images/joseph-purdue.jpg`

### Cast Photos (all 16)
- [ ] `images/cast/daniele-alancarter.jpg`
- [ ] `images/cast/g-victoria-campbell.jpg`
- [ ] `images/cast/simon-bachtiger.jpg`
- [ ] `images/cast/peter-campbell.jpg`
- [ ] `images/cast/emett-matthews.jpg`
- [ ] `images/cast/jenny-mollet.jpg`
- [ ] `images/cast/stephen-ingram.jpg`
- [ ] `images/cast/diana-chu.jpg`
- [ ] `images/cast/sinead-davies.jpg`
- [ ] `images/cast/sarsi-grace.jpg`
- [ ] `images/cast/auguste-jankauskaite.jpg`
- [ ] `images/cast/sarah-waddington.jpg`
- [ ] `images/cast/aly-carrigan.jpg`
- [ ] `images/cast/luisa-cortes.jpg`
- [ ] `images/cast/jacob-didas.jpg`
- [ ] `images/cast/colin-wardale.jpg`

## Image Optimization Tips

Before uploading to GitHub:
1. Resize images to appropriate dimensions
2. Use JPG format (smaller file size)
3. Compress images using tools like:
   - TinyPNG (https://tinypng.com/)
   - ImageOptim (Mac)
   - Squoosh (https://squoosh.app/)
4. Aim for <200KB per image

## Quick Terminal Commands

To create the image directories:
```bash
mkdir -p images/cast
```

To verify all images are in place:
```bash
ls images/
ls images/cast/
```

Expected output should show all required files.
