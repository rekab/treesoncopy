# Deployment Checklist

Follow these steps to deploy your TREESON website:

## Pre-Deployment

- [ ] Add all required images to the `images/` directory
- [ ] Update Google Form embed URL in `index.html`
- [ ] Verify all social media links in footer sections
- [ ] Test the site locally by opening `index.html` in a browser
- [ ] Check all cast member page links work correctly
- [ ] Verify YouTube video embed displays properly

## GitHub Setup

- [ ] Create a new GitHub account if you don't have one
- [ ] Create a new repository (e.g., "treeson-musical")
- [ ] Initialize git in your local directory
- [ ] Add all files to git
- [ ] Commit the files
- [ ] Push to GitHub

## GitHub Pages Configuration

- [ ] Go to repository Settings
- [ ] Navigate to Pages section
- [ ] Select "main" branch as source
- [ ] Save the settings
- [ ] Wait 2-5 minutes for deployment
- [ ] Visit your site at: `https://USERNAME.github.io/REPO-NAME/`

## Custom Domain (Optional)

- [ ] Create `CNAME` file in repository root with your domain
- [ ] Add DNS records at your domain registrar:
  - Type: CNAME
  - Name: www
  - Value: USERNAME.github.io
- [ ] Wait 24-48 hours for DNS propagation
- [ ] Verify HTTPS certificate is provisioned by GitHub

## Post-Deployment

- [ ] Test the site on mobile devices
- [ ] Test all navigation links
- [ ] Verify all images load correctly
- [ ] Check contact form works
- [ ] Test social media links
- [ ] Run through all cast member pages

## Maintenance

- [ ] Keep GitHub repository private or public as preferred
- [ ] Update content by editing files and pushing to GitHub
- [ ] Monitor GitHub Pages build status in Actions tab
- [ ] Periodically check for broken links

## Costs

- **GitHub Pages**: Free
- **Custom Domain**: Keep your existing domain registration
- **Total Monthly Cost**: $0 (vs. Squarespace ~$12-16/month)

## Support

If you encounter issues:
1. Check GitHub Pages documentation: https://docs.github.com/en/pages
2. Verify all file names and paths are correct (case-sensitive!)
3. Check browser console for JavaScript errors
4. Review the README.md troubleshooting section
