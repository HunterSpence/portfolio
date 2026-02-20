# 🚀 Deployment Instructions

Your portfolio site has been successfully created and pushed to GitHub!

## 📍 Repository Location

**GitHub Repository**: https://github.com/HunterSpence/portfolio

## 🔧 Enable GitHub Pages (One-Time Setup)

To make your site live, follow these steps:

1. **Go to Repository Settings**
   - Navigate to: https://github.com/HunterSpence/portfolio/settings/pages

2. **Configure GitHub Pages**
   - Under "Build and deployment"
   - **Source**: Select **GitHub Actions** (not "Deploy from a branch")
   - Click **Save**

3. **Wait for Deployment**
   - The GitHub Actions workflow will automatically run
   - Check progress: https://github.com/HunterSpence/portfolio/actions
   - First deployment takes ~1-2 minutes

4. **Access Your Live Site**
   - URL: **https://hunterspence.github.io/portfolio**
   - It may take a few minutes for DNS to propagate

## 📁 Project Structure

```
portfolio-site/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions deployment workflow
├── index.html                  # Main HTML file
├── styles.css                  # CSS with glassmorphism design
├── script.js                   # JavaScript for animations
├── README.md                   # Project documentation
└── DEPLOYMENT.md              # This file
```

## 🎨 Design Highlights

- **Colors**: Deep navy (#0a1628), charcoal (#1a1f2e), electric blue (#3b82f6), cyan (#06b6d4)
- **Font**: Inter (loaded from Google Fonts)
- **Effects**: Glassmorphism cards, smooth scroll, reveal animations
- **Responsive**: Mobile-first design

## ✅ What's Already Done

✓ Git repository initialized  
✓ All files created (HTML, CSS, JS)  
✓ GitHub Actions workflow configured  
✓ Repository created and pushed to GitHub  
✓ Git configured with your credentials  

## 🔄 Making Updates

To update your portfolio:

```bash
cd C:\Users\hspen\portfolio-site

# Make your changes to index.html, styles.css, or script.js

git add -A
git commit -m "update: description of your changes"
git push
```

The site will automatically redeploy within 1-2 minutes!

## 🎯 Next Steps

1. **Enable GitHub Pages** (see instructions above)
2. **Add your actual LinkedIn/Discord links** in index.html
3. **Add a profile photo** to replace the gradient circle avatar
4. **Customize content** as needed
5. **Consider adding a custom domain** (optional)

## 📝 Customization Tips

- **Hero gradient**: Edit `.hero-background` in styles.css
- **Color scheme**: Modify CSS variables in `:root`
- **Projects**: Add/remove project cards in index.html
- **Skills**: Update skill badges in the Skills section
- **Contact**: Replace placeholder links with real ones

## 🐛 Troubleshooting

**Site not loading?**
- Ensure GitHub Pages is set to "GitHub Actions" (not "Deploy from a branch")
- Check the Actions tab for deployment errors
- Wait 5-10 minutes for first deployment

**Changes not showing?**
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- Clear browser cache
- Check if commit was pushed: `git log`

## 📞 Support

If you encounter issues:
1. Check GitHub Actions logs: https://github.com/HunterSpence/portfolio/actions
2. Verify GitHub Pages settings
3. Review browser console for JavaScript errors

---

**Ready to go live!** 🎉

Just enable GitHub Pages in settings and your stunning portfolio will be live at:
**https://hunterspence.github.io/portfolio**
