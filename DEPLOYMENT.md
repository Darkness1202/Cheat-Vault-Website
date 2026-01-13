# 🚀 Deploying CheatVault to GitHub Pages

Follow this step-by-step guide to host your CheatVault website for FREE on GitHub Pages!

## 📋 Prerequisites

- A GitHub account (create one at https://github.com)
- Basic familiarity with GitHub (we'll walk you through it!)

---

## Method 1: GitHub Web Interface (Easiest - No Software Needed!)

### Step 1: Create a GitHub Account
1. Go to https://github.com
2. Click "Sign up"
3. Follow the registration process

### Step 2: Create a New Repository
1. Click the **+** icon in the top-right corner
2. Select **"New repository"**
3. Fill in the details:
   - **Repository name**: `cheat-vault` (or any name you prefer)
   - **Description**: "Ultimate game cheat code database"
   - **Public** (must be public for free GitHub Pages)
   - ✅ Check "Add a README file"
4. Click **"Create repository"**

### Step 3: Upload Files
1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop ALL these files:
   - `index.html`
   - `README.md`
   - `LICENSE`
   - `CONTRIBUTING.md`
   - `.gitignore`
3. Add commit message: "Initial commit - CheatVault website"
4. Click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. Go to **Settings** (gear icon at top of repo)
2. Scroll down and click **"Pages"** in the left sidebar
3. Under **"Source"**:
   - Branch: Select **main**
   - Folder: Select **/ (root)**
4. Click **"Save"**
5. 🎉 You'll see: "Your site is published at https://YOUR-USERNAME.github.io/cheat-vault/"

### Step 5: Visit Your Website
- Wait 1-2 minutes for deployment
- Click the URL or visit: `https://YOUR-USERNAME.github.io/cheat-vault/`
- Your CheatVault is now LIVE! 🎮

---

## Method 2: GitHub Desktop (Recommended for Easy Updates)

### Step 1: Install GitHub Desktop
1. Download from https://desktop.github.com
2. Install and sign in with your GitHub account

### Step 2: Create Repository
1. Open GitHub Desktop
2. **File** → **New repository**
3. Fill in:
   - Name: `cheat-vault`
   - Local path: Choose where to save
   - ✅ Check "Initialize with README"
4. Click **"Create Repository"**

### Step 3: Add Your Files
1. Open the repository folder (button in GitHub Desktop)
2. Copy all CheatVault files into this folder:
   - `index.html`
   - `README.md`
   - `LICENSE`
   - `CONTRIBUTING.md`
   - `.gitignore`

### Step 4: Commit and Push
1. GitHub Desktop will show all new files
2. In the bottom-left:
   - Summary: "Initial commit"
   - Description: "Add CheatVault website files"
3. Click **"Commit to main"**
4. Click **"Publish repository"**
5. ⚠️ **IMPORTANT**: Uncheck "Keep this code private"
6. Click **"Publish Repository"**

### Step 5: Enable GitHub Pages
1. Go to your repository on GitHub.com
2. **Settings** → **Pages**
3. Source: **main** branch, **/ (root)** folder
4. Click **"Save"**

### Step 6: Access Your Site
- URL: `https://YOUR-USERNAME.github.io/cheat-vault/`
- Updates: Just save files and click "Commit" in GitHub Desktop!

---

## Method 3: Command Line (For Developers)

### Step 1: Create Repository on GitHub.com
1. Go to GitHub.com
2. Create new repository named `cheat-vault` (Public)

### Step 2: Set Up Locally
```bash
# Navigate to your CheatVault folder
cd /path/to/cheat-vault-github

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: CheatVault website"

# Add remote (replace YOUR-USERNAME)
git remote add origin https://github.com/YOUR-USERNAME/cheat-vault.git

# Set branch name
git branch -M main

# Push to GitHub
git push -u origin main
```

### Step 3: Enable Pages
1. Go to repository Settings → Pages
2. Source: main branch, / (root)
3. Save

---

## 🎨 Customization Options

### Change Repository Name
- Settings → General → Repository name
- Your URL will change to match

### Custom Domain (Optional)
1. Buy a domain (Namecheap, Google Domains, etc.)
2. In GitHub: Settings → Pages → Custom domain
3. Add your domain (e.g., `cheatvault.com`)
4. Configure DNS with your domain provider:
   ```
   Type: A
   Host: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153
   ```
5. Add CNAME record:
   ```
   Type: CNAME
   Host: www
   Value: YOUR-USERNAME.github.io
   ```

---

## 🔄 Updating Your Website

### Via GitHub Web
1. Click on `index.html`
2. Click the pencil icon (Edit)
3. Make changes
4. Scroll down → "Commit changes"
5. Wait 1-2 minutes for update

### Via GitHub Desktop
1. Edit `index.html` in your favorite editor
2. Save the file
3. Open GitHub Desktop
4. Add commit message
5. Click "Commit to main"
6. Click "Push origin"

---

## 🐛 Troubleshooting

### Site Not Loading?
- ✅ Check repo is **Public** (Settings → General)
- ✅ Confirm Pages is enabled (Settings → Pages)
- ✅ Wait 2-5 minutes after enabling Pages
- ✅ Try incognito/private browsing mode
- ✅ Hard refresh: `Ctrl+Shift+R` (Windows) or `Cmd+Shift+R` (Mac)

### 404 Error?
- ✅ File must be named exactly `index.html` (lowercase)
- ✅ File must be in root folder (not in a subfolder)

### Changes Not Showing?
- ✅ Wait 1-2 minutes for GitHub to rebuild
- ✅ Clear browser cache
- ✅ Check "Actions" tab for deployment status

---

## 📊 GitHub Pages Benefits

✅ **100% Free** - No hosting costs
✅ **Fast** - Global CDN (Content Delivery Network)
✅ **Secure** - Free HTTPS/SSL certificate
✅ **Reliable** - 99.9% uptime
✅ **Easy** - No server management needed
✅ **Version Control** - Track all changes

---

## 📈 Analytics (Optional)

### Add Google Analytics
1. Create Google Analytics account
2. Get tracking ID
3. Add to `index.html` before `</head>`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

---

## 🎯 Next Steps

1. ✅ Deploy your site
2. ✅ Share with friends
3. ✅ Add more games
4. ✅ Accept contributions from community
5. ✅ Promote on social media

---

## 💡 Pro Tips

- Use GitHub Issues to track game requests
- Enable Discussions for community engagement
- Star other cheat code repositories for inspiration
- Join gaming communities and share your site

---

**Need Help?** Open an issue in the repository!

**Happy Gaming! 🎮**
