# Portfolio Setup Guide

## 📋 What's Been Configured

✅ **GitHub Repository**: Created at `https://github.com/latituded3420/portfolio`
✅ **.gitignore**: Configured to protect sensitive files
✅ **GitHub Pages Workflow**: Automatic deployment setup
✅ **README.md**: Comprehensive documentation

## 🚀 Next Steps to Complete Your Portfolio

### Step 1: Add Your Portfolio Files

You need to upload the following files from your portfolio project:

```
portfolio/
├── index.html          # Main HTML (update with your content)
├── style.css           # CSS styles (make sure it's optimized)
├── script.js           # JavaScript functionality
├── languages.js        # Multi-language translations
├── package.json        # Dependencies
└── assets/             # Folder with images
    └── images/         # Your portfolio images
        └── Portfolio.jpg
```

**Security Note**: Do NOT include `email.js` with hardcoded credentials!

### Step 2: Clone Repository Locally

```bash
git clone https://github.com/latituded3420/portfolio.git
cd portfolio
```

### Step 3: Clean Up Sensitive Files

Before uploading, ensure your files are cleaned:

**Remove from index.html:**
- Remove commented EmailJS script
- Remove hardcoded email addresses (use placeholder)

**Remove from script.js:**
- Remove email configuration functions
- Remove backend API calls

**Delete:**
- `email.js` (contains credentials)
- Any `.env` files

### Step 4: Add Files to Git

```bash
# Add all portfolio files
git add index.html style.css script.js languages.js package.json assets/
git commit -m "Add portfolio website files with security fixes"
git push origin main
```

### Step 5: Enable GitHub Pages

1. Go to your repository Settings
2. Navigate to "Pages" in the left sidebar
3. Under "Build and deployment":
   - Source: Select `Deploy from a branch`
   - Branch: Select `gh-pages` and `/root` folder
   - Click Save

**Auto-Deploy**: Once you push files to `main`, GitHub Actions will automatically:
1. Checkout your code
2. Deploy to the `gh-pages` branch
3. Make your site live at: `https://latituded3420.github.io/portfolio/`

### Step 6: Verify Deployment

```bash
# Check if Actions workflow ran
# Visit: https://github.com/latituded3420/portfolio/actions

# Visit your live portfolio
# https://latituded3420.github.io/portfolio/
```

## 🔧 Features to Add/Remove

### ✅ Keep These Features
- Multi-language support (EN, ES, FR)
- Dark/Light theme toggle
- Responsive design
- Smooth animations
- Project filtering
- Social media links
- Contact form (client-side validation)

### ❌ Remove These Features
- Backend email service (removed for security)
- Phone field in contact form (incomplete)
- commented EmailJS code
- Hardcoded credentials

### ➕ Recommended Features to Add

**1. SEO Meta Tags** (in index.html `<head>`):
```html
<meta name="description" content="Frontend Developer Portfolio">
<meta property="og:title" content="Salim Shaikh - Frontend Developer">
<meta property="og:description" content="Portfolio showcasing projects and skills">
<meta property="og:image" content="assets/images/og-image.jpg">
```

**2. Favicon** (replace with your own):
```html
<link rel="icon" type="image/png" href="assets/favicon.png">
```

**3. Performance Optimization**:
- Minify CSS/JS for production
- Lazy load images
- Defer non-critical scripts

**4. Form Handling** (if you want emails later):
- Use FormSubmit.co (free, no backend needed)
- Or Formspree.io
- Add to contact form without exposing credentials

## 📝 Customization Checklist

- [ ] Update hero section with your name/title
- [ ] Update about section with your bio
- [ ] Update skills and proficiency levels
- [ ] Add/update project descriptions and links
- [ ] Update social media links (GitHub, LinkedIn, Email)
- [ ] Update contact email (without hardcoding in JS)
- [ ] Add your portfolio images to assets/
- [ ] Test all features (animations, language switching, dark mode)
- [ ] Test on mobile devices
- [ ] Test form submission workflow

## 🔐 Security Checklist

- [ ] No hardcoded email credentials
- [ ] No API keys in source code
- [ ] No `.env` files committed
- [ ] No sensitive data in HTML comments
- [ ] Contact form uses client-side validation only
- [ ] `.gitignore` prevents accidental commits

## 🌐 Deployment Verification

After deployment, check:

```bash
# Check live site
https://latituded3420.github.io/portfolio/

# Verify all features work:
- Language switching (EN/ES/FR)
- Dark/Light mode toggle
- Project filtering
- Form submission
- Mobile responsiveness
- All links work correctly
```

## 🆘 Troubleshooting

**GitHub Pages Not Working?**
- Check Actions tab for workflow errors
- Ensure workflow file is in `.github/workflows/deploy.yml`
- Try triggering manually: Push a new commit to `main`

**Styles Not Loading?**
- Add GitHub repository name to CSS links if deploying as subdirectory
- Example: `<link rel="stylesheet" href="/portfolio/style.css">`

**JavaScript Not Working?**
- Check browser console for errors
- Verify all JS files are in same directory as HTML
- Check for mixed HTTP/HTTPS issues

## 📞 Contact Form Solution

For email functionality WITHOUT storing credentials:

**Option 1: FormSubmit.co** (Recommended)
```html
<form action="https://formsubmit.co/salimshaikh50113@gmail.com" method="POST">
  <input type="email" name="email" required>
  <textarea name="message" required></textarea>
  <button type="submit">Send</button>
</form>
```

**Option 2: Formspree.io**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <!-- form fields -->
</form>
```

These services handle email delivery securely without you needing to store credentials!

## ✨ Final Steps

1. Customize all content
2. Upload files to repository
3. Enable GitHub Pages
4. Share your portfolio: `https://latituded3420.github.io/portfolio/`

---

**Happy Coding!** 🚀

For more help, check the README.md or GitHub Issues.

Last updated: January 2026
