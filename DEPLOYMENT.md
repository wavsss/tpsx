# 🚀 GitHub Deployment Guide

## Step-by-Step Instructions

### 1️⃣ Create GitHub Repository

1. Go to [github.com](https://github.com)
2. Click the **"+"** icon → **"New repository"**
3. Repository name: `triples-fansites` (or any name you like)
4. Description: "tripleS Fan Sites Directory - 24 Members"
5. Select **Public**
6. ✅ Check "Add a README file" (we'll replace it)
7. Click **"Create repository"**

### 2️⃣ Upload Files to GitHub

**Option A: Using GitHub Web Interface (Easiest)**

1. In your repository, click **"Add file"** → **"Upload files"**
2. Drag and drop these 4 files:
   - `index.html`
   - `fansites.html`
   - `styles.css`
   - `script.js`
3. Scroll down and click **"Commit changes"**
4. Replace the README.md with the provided one

**Option B: Using Git Command Line**

```bash
# Navigate to your project folder
cd path/to/your/folder

# Initialize git
git init

# Add all files
git add index.html fansites.html styles.css script.js README.md .gitignore

# Commit
git commit -m "Initial commit: tripleS fan sites directory"

# Connect to GitHub (replace with your username and repo name)
git remote add origin https://github.com/yourusername/triples-fansites.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### 3️⃣ Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** (top right)
3. Click **"Pages"** (left sidebar)
4. Under **"Source"**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **"Save"**
6. Wait 1-2 minutes for deployment

Your site will be live at:
```
https://yourusername.github.io/triples-fansites
```

### 4️⃣ Connect Custom Domain (wav.haus)

1. In GitHub Pages settings, scroll to **"Custom domain"**
2. Enter: `tpsxfansites.wav.haus`
3. Click **"Save"**
4. GitHub will create a `CNAME` file automatically

5. In your **wav.haus panel**:
   - Select **"GitHub Pages"** option
   - Enter your GitHub Pages URL
   - Save configuration

6. Wait for DNS propagation (5-30 minutes)

### 5️⃣ Verify Deployment

1. Visit your GitHub Pages URL
2. Test the search function
3. Click on different members
4. Verify Twitter links open correctly
5. Test on mobile device

## 🔧 Troubleshooting

### Site not loading?
- Wait 2-5 minutes after enabling GitHub Pages
- Check that all files are in the root directory
- Verify file names are exactly: `index.html`, `fansites.html`, etc.

### 404 Error?
- Make sure `index.html` is in the root folder
- Check GitHub Pages is enabled in Settings

### Custom domain not working?
- DNS propagation takes time (up to 24 hours)
- Verify CNAME record is correct
- Check GitHub shows green checkmark for custom domain

### Styling broken?
- Check all files are uploaded
- View browser console (F12) for errors
- Clear browser cache (Ctrl + Shift + R)

## 📱 Test URLs

After deployment, test these pages:

```
https://yourusername.github.io/triples-fansites/
https://yourusername.github.io/triples-fansites/fansites.html?member=yooyeon
https://yourusername.github.io/triples-fansites/fansites.html?member=nakyoung
```

## ✨ Success!

Your tripleS fan sites directory is now live! 🎉

Share your link with other WAVs!

---

Need help? Open an issue on GitHub or check the README.md file.
