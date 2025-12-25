# 🚀 GitHub Pages Deployment Guide

Complete step-by-step guide to deploy your RDR2 Portfolio Site to GitHub Pages.

---

## 📋 Pre-Deployment Checklist

Before deploying, ensure you have:
- [ ] Git installed on your computer
- [ ] GitHub account created
- [ ] All files in the project folder
- [ ] README.md reviewed and personalized

---

## 🔧 Step 1: Rename Files (Optional but Recommended)

For cleaner URLs, rename your HTML files:

**Current → New**
```
rdr2_mask_reveal.html    → index.html
1_index.html             → home.html
2_characters.html        → characters.html
3_weaponscroll.html      → weapons.html
4_story.html             → story.html
5_gallery.html           → gallery.html
6_about.html             → about.html
7_horizontal_scroll.html → locations.html
```

> **Important:** If you rename files, you MUST update all navigation links in every HTML file!

**Example:** Change `<a href="1_index.html">` to `<a href="home.html">`

---

## 🌐 Step 2: Create GitHub Repository

1. **Go to GitHub**
   - Visit [github.com](https://github.com)
   - Click the **+** icon (top right)
   - Select **New repository**

2. **Repository Settings**
   - **Repository name:** `rdr2-portfolio-site`
   - **Description:** "Interactive Red Dead Redemption 2 themed portfolio website with GSAP animations"
   - **Visibility:** Public ✅
   - **DO NOT** initialize with README (we already have one)
   - Click **Create repository**

---

## 💻 Step 3: Initialize Git Locally

Open **PowerShell** or **Command Prompt** in your project folder:

```powershell
# Navigate to your project folder
cd "C:\Users\bmich\OneDrive\Desktop\RDR2 Front End website"

# Initialize Git repository
git init

# Add all files
git add .

# Create first commit
git commit -m "Initial commit: RDR2 Portfolio Site"
```

---

## 🔗 Step 4: Connect to GitHub

Replace `YOUR-USERNAME` with your actual GitHub username:

```powershell
# Add remote repository
git remote add origin https://github.com/YOUR-USERNAME/rdr2-portfolio-site.git

# Rename branch to main
git branch -M main

# Push to GitHub
git push -u origin main
```

**If prompted for credentials:**
- Username: Your GitHub username
- Password: Use a **Personal Access Token** (not your password)
  - Get token: GitHub → Settings → Developer settings → Personal access tokens → Generate new token

---

## 🌍 Step 5: Enable GitHub Pages

1. **Go to your repository on GitHub**
   - `https://github.com/YOUR-USERNAME/rdr2-portfolio-site`

2. **Navigate to Settings**
   - Click **Settings** tab (top right)

3. **Find Pages Section**
   - Scroll down to **Pages** (left sidebar)

4. **Configure Deployment**
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
   - Click **Save**

5. **Wait for Deployment**
   - GitHub will build your site (takes 1-2 minutes)
   - Refresh the page to see the live URL

---

## ✅ Step 6: Verify Deployment

Your site will be live at:
```
https://YOUR-USERNAME.github.io/rdr2-portfolio-site/
```

**Test the following:**
- [ ] Landing page (mask reveal) loads
- [ ] Click animation transitions to home page
- [ ] All navigation links work
- [ ] Videos play correctly
- [ ] Images load properly
- [ ] Mobile responsive design works
- [ ] All 7 pages are accessible

---

## 🐛 Troubleshooting

### Issue: 404 Page Not Found
**Solution:** 
- Ensure `index.html` exists in root (or rename `rdr2_mask_reveal.html`)
- Check GitHub Pages is enabled in Settings

### Issue: Videos Don't Play
**Solution:**
- Ensure video files are committed to repository
- Check file paths are relative (not absolute)
- Verify video file sizes aren't too large (GitHub has 100MB file limit)

### Issue: Images Not Loading
**Solution:**
- Check image file names match exactly (case-sensitive)
- Ensure images are in the same directory as HTML files
- Use relative paths: `Hero-image.png` not `/Hero-image.png`

### Issue: Navigation Links Broken
**Solution:**
- If you renamed files, update ALL navigation links
- Use Find & Replace in your editor:
  - Find: `1_index.html` → Replace: `home.html`
  - Find: `2_characters.html` → Replace: `characters.html`
  - etc.

---

## 🔄 Updating Your Site

After making changes:

```powershell
# Navigate to project folder
cd "C:\Users\bmich\OneDrive\Desktop\RDR2 Front End website"

# Stage changes
git add .

# Commit with message
git commit -m "Update: describe your changes here"

# Push to GitHub
git push
```

GitHub Pages will automatically rebuild your site within 1-2 minutes.

---

## 📊 Optional: Add Custom Domain

If you have a custom domain (e.g., `yourname.com`):

1. **In GitHub Repository Settings → Pages:**
   - Enter your custom domain
   - Click Save

2. **In Your Domain Registrar (GoDaddy, Namecheap, etc.):**
   - Add CNAME record pointing to: `YOUR-USERNAME.github.io`

---

## 🎯 Next Steps

After deployment:

1. **Update README.md**
   - Replace `YOUR-USERNAME` with your actual username
   - Add screenshots to `/screenshots` folder
   - Update live demo link

2. **Share Your Site**
   - Add to your resume
   - Share on LinkedIn
   - Include in job applications

3. **Monitor Performance**
   - Use Google Lighthouse for performance audit
   - Test on multiple devices
   - Get feedback from peers

---

## 📝 Quick Reference Commands

```powershell
# Check status
git status

# View commit history
git log --oneline

# Create new branch
git checkout -b feature-name

# Switch branches
git checkout main

# Pull latest changes
git pull

# View remote URL
git remote -v
```

---

## 🆘 Need Help?

- **Git Documentation:** [git-scm.com/doc](https://git-scm.com/doc)
- **GitHub Pages Docs:** [docs.github.com/pages](https://docs.github.com/pages)
- **GSAP Forums:** [greensock.com/forums](https://greensock.com/forums)

---

**Good luck with your deployment! 🚀**

If you encounter any issues, double-check file paths and ensure all assets are committed to the repository.
