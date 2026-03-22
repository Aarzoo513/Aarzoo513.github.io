# 🚀 Deploy Your Portfolio to GitHub Pages

## Follow these simple steps to publish your portfolio online for FREE!

---

## Step 1: Create a GitHub Account (if you don't have one)

1. Go to [github.com](https://github.com)
2. Click **"Sign up"** in the top right
3. Enter your email and create a password
4. Verify your email address
5. Complete your profile setup

---

## Step 2: Create a New Repository

1. Log in to your GitHub account
2. Click the **"+"** icon in the top right corner
3. Select **"New repository"**
4. **Name your repository:** `your-username.github.io`
   - Replace `your-username` with your actual GitHub username
   - **IMPORTANT:** The name must be exactly in this format!
   - Example: If your username is `aarzoo-lakhani`, name it `aarzoo-lakhani.github.io`

5. Add a description (optional): "My Professional Portfolio"
6. Choose **"Public"** (so it's visible to everyone)
7. Click **"Create repository"**

---

## Step 3: Upload Your Portfolio Files

### Option A: Using GitHub Web Interface (Easiest)

1. In your new repository, click **"Add file"** > **"Upload files"**
2. Drag and drop your files:
   - `index.html`
   - Any images or additional files needed
3. Leave the commit message as default or add: "Initial portfolio upload"
4. Click **"Commit changes"**

### Option B: Using Git Command Line (Advanced)

```bash
# Navigate to your portfolio folder
cd path/to/your/portfolio

# Initialize git
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial portfolio commit"

# Add remote repository (replace USERNAME with your GitHub username)
git remote add origin https://github.com/USERNAME/USERNAME.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

---

## Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** (top right tab)
3. Scroll down to **"Pages"** section on the left sidebar
4. Under "Source", select **"Deploy from a branch"**
5. Select **"main"** branch and **"/root"** folder
6. Click **"Save"**

---

## Step 5: Access Your Live Portfolio! 🎉

After a few seconds (up to 2 minutes), your portfolio will be live at:

```
https://your-username.github.io
```

**Example:** `https://aarzoo-lakhani.github.io`

You can now:
- ✅ Share the link on LinkedIn, email, and social media
- ✅ Show employers your professional portfolio
- ✅ Update content anytime by uploading new files

---

## How to Update Your Portfolio

1. Edit `index.html` on your computer
2. Either:
   - Upload the updated file through GitHub web interface (Option A)
   - Or push changes through Git command line (Option B)
3. Changes usually appear within a few minutes

---

## Troubleshooting

### Portfolio not showing up?
- ✅ Ensure your repository is named `your-username.github.io`
- ✅ Check that it's set to **Public**
- ✅ Wait 2-5 minutes for GitHub Pages to build
- ✅ Clear your browser cache and refresh (Ctrl+Shift+R or Cmd+Shift+R)

### Want a custom domain?
1. Buy a domain from GoDaddy, Namecheap, or similar
2. Go to repository Settings → Pages → Custom domain
3. Enter your domain name and save
4. Update DNS records at your domain provider (instructions will be provided)

---

## Pro Tips 💡

- **Back up your files:** Keep a copy on your computer
- **Use Markdown:** You can create a `README.md` file with more information
- **Add a file structure:**
  ```
  your-repo/
  ├── index.html          (your main portfolio)
  ├── styles/
  │   └── style.css       (separate CSS if needed)
  ├── assets/
  │   └── images/         (your images folder)
  └── README.md           (repository description)
  ```

- **Make it SEO friendly:** Add metadata to your `index.html` for better search engine visibility
- **Share your GitHub profile:** Let recruiters see your projects and contributions

---

## Getting Help

- 📚 **GitHub Docs:** https://docs.github.com/en/pages
- 💬 **GitHub Community:** https://github.community
- 🎓 **YouTube Tutorials:** Search "GitHub Pages tutorial"

---

## Summary Checklist

- [ ] Created GitHub account
- [ ] Created repository named `username.github.io`
- [ ] Uploaded `index.html` to the repository
- [ ] Enabled GitHub Pages in Settings
- [ ] Portfolio is live at `https://username.github.io`
- [ ] Shared portfolio link on LinkedIn and other platforms

**Your portfolio is now live! Congratulations! 🎊**
