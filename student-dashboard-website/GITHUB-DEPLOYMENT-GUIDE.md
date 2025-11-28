# 🚀 DEPLOY TO GITHUB PAGES - STEP BY STEP GUIDE

## 📋 Prerequisites
- GitHub account (create one at https://github.com/signup if needed)
- Your website files downloaded to your computer

---

## STEP 1: Download Your Website Files

1. **Download the folder** `/app/student-dashboard-website/` from this platform
   - OR download the package: `/app/student-dashboard-website-FINAL.tar.gz`
   
2. **Extract the files** on your computer (if using .tar.gz)

3. **Verify you have these files:**
   ```
   ✓ index.html
   ✓ problem.html
   ✓ research.html
   ✓ solution.html
   ✓ architecture.html
   ✓ data.html
   ✓ dashboard.html
   ✓ ethics.html
   ✓ lessons.html
   ✓ appendix.html
   ✓ images/ folder (with architecture-diagram.png and er-diagram.png)
   ✓ README.md
   ```

---

## STEP 2: Create GitHub Repository

1. **Go to GitHub:** https://github.com

2. **Sign in** to your account

3. **Click the "+" icon** in the top right corner

4. **Select "New repository"**

5. **Fill in repository details:**
   ```
   Repository name: student-dashboard-presentation
                    (or any name you prefer)
   
   Description: Centralized Student Dashboard Presentation Website
                (optional but recommended)
   
   Visibility: ✓ Public (required for free GitHub Pages)
   
   Initialize: ☐ Do NOT check any boxes
               (no README, no .gitignore, no license)
   ```

6. **Click "Create repository"**

---

## STEP 3: Upload Your Files

### METHOD A: Using GitHub Web Interface (Easiest)

1. **On the new repository page**, you'll see quick setup options

2. **Click:** "uploading an existing file"

3. **Drag and drop** ALL your files and folders into the upload area
   - Include the `images/` folder
   - Include all HTML files
   - Include all documentation files

4. **Important:** Make sure you upload the **contents** of the folder, not the folder itself
   - ✅ Correct: index.html, problem.html, images/, etc. at root level
   - ❌ Wrong: student-dashboard-website/ folder containing everything

5. **Add commit message:** "Initial commit - Complete website"

6. **Click "Commit changes"**

### METHOD B: Using Git Command Line (Advanced)

```bash
# Navigate to your website folder
cd path/to/student-dashboard-website

# Initialize git
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit - Complete website"

# Add remote repository (replace YOUR-USERNAME and REPO-NAME)
git remote add origin https://github.com/YOUR-USERNAME/REPO-NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

---

## STEP 4: Enable GitHub Pages

1. **Go to your repository** on GitHub

2. **Click "Settings"** tab (top right area)

3. **Scroll down** and click **"Pages"** in the left sidebar

4. **Under "Source":**
   - Branch: Select **"main"** (or "master")
   - Folder: Select **"/ (root)"**

5. **Click "Save"**

6. **Wait 1-2 minutes** for GitHub to build your site

7. **Refresh the page** - you'll see a message:
   ```
   ✅ Your site is live at https://YOUR-USERNAME.github.io/REPO-NAME/
   ```

---

## STEP 5: Access Your Live Website

1. **Copy the URL** from the green success message

2. **Open in browser:** https://YOUR-USERNAME.github.io/REPO-NAME/

3. **Test everything:**
   - ✓ All 10 pages load
   - ✓ Navigation works
   - ✓ Dark mode toggle works
   - ✓ Your diagrams appear
   - ✓ Mobile responsive works

---

## 🎉 SUCCESS! Your Website is Live!

You can now share this URL with:
- Your presentation audience
- Your professors
- On your resume/portfolio
- With your team members

---

## 🔧 Common Issues & Solutions

### Issue 1: Images not showing
**Problem:** Images show as broken
**Solution:** 
- Verify `images/` folder was uploaded
- Check image filenames match exactly (case-sensitive)
- Paths should be `./images/filename.png`

### Issue 2: Page not found (404)
**Problem:** Website shows 404 error
**Solution:**
- Wait 2-3 minutes after enabling Pages
- Check branch is set to "main" not "master"
- Verify index.html is in root directory (not in a subfolder)

### Issue 3: Dark mode not working
**Problem:** Dark mode toggle doesn't work
**Solution:**
- This is normal - GitHub Pages may restrict localStorage
- It will work when testing locally
- Consider it a bonus feature, not essential

### Issue 4: Styles look broken
**Problem:** Website looks unstyled
**Solution:**
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Verify all HTML files were uploaded
- Check browser console for errors

### Issue 5: Wrong URL structure
**Problem:** URL is https://username.github.io/username.github.io/repo/
**Solution:**
- Repository name should NOT be "username.github.io"
- Use a different name like "student-dashboard-presentation"

---

## 🔄 Updating Your Website

If you need to make changes:

1. **Edit files** on your computer

2. **Go to repository** on GitHub

3. **Click on the file** you want to update

4. **Click the pencil icon** (Edit)

5. **Make changes**

6. **Commit changes**

7. **Wait 1-2 minutes** - changes will appear automatically!

---

## 📱 Custom Domain (Optional)

Want a custom URL like www.yourname.com?

1. Buy a domain from Namecheap, GoDaddy, etc.

2. Go to repository Settings → Pages

3. Add your custom domain

4. Follow GitHub's instructions for DNS setup

---

## 📊 GitHub Pages Features

✅ Free hosting forever
✅ Automatic HTTPS (secure)
✅ Fast CDN delivery
✅ Easy to update
✅ Professional URL
✅ No server management needed

---

## 🎯 Quick Checklist

Before deploying:
- [ ] All files downloaded
- [ ] GitHub account created
- [ ] Repository created (Public)
- [ ] All files uploaded (including images/)
- [ ] GitHub Pages enabled
- [ ] Waited 2-3 minutes
- [ ] Website URL accessed
- [ ] All pages tested
- [ ] Shared URL with team

---

## 💡 Pro Tips

1. **Test locally first:** Open index.html on your computer before deploying

2. **Bookmark the URL:** You'll use it for your presentation

3. **Share with team:** Send the URL to all 5 speakers

4. **Mobile test:** Check on your phone before presenting

5. **Backup:** Keep a copy of all files on your computer

6. **Screenshot:** Take screenshots of the live site as backup

---

## 🎤 For Your Presentation

During presentation:
1. Have the live URL bookmarked
2. Open it in a separate browser tab
3. Test beforehand at the venue
4. Have offline version as backup (downloaded files)

---

## 📞 Need Help?

If you get stuck:
1. Check the "Common Issues" section above
2. Google the error message
3. Check GitHub Pages documentation
4. Ask your team members
5. Contact GitHub support

---

## ✨ Congratulations!

Once deployed, your website is:
- ✅ Publicly accessible 24/7
- ✅ Professional portfolio piece
- ✅ Ready for presentation
- ✅ Shareable with anyone
- ✅ Free forever

---

*Deployment guide created for Group 20 - QuadraMind*
*Centralized Student Dashboard Project*
