# 🚀 Quick Setup Guide - GitHub Pages Deployment

## Step 1: Create a GitHub Account (if you don't have one)
- Go to https://github.com
- Sign up (it's free!)

## Step 2: Create a New Repository

1. Click the **+** icon in the top right → **New repository**
2. Name it: `task-app`
3. Add description: "A beautiful task management PWA"
4. Select **Public** (so GitHub Pages works)
5. Check **Add a README file**
6. Click **Create repository**

## Step 3: Upload the Files

### Option A: Using GitHub Web Interface (Easiest)
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop these files:
   - `index.html`
   - `README.md`
   - `.gitignore`
3. Click **Commit changes**

### Option B: Using Git Command Line
1. Install Git: https://git-scm.com/download
2. Open terminal/command prompt and run:
```bash
git clone https://github.com/YOUR-USERNAME/task-app.git
cd task-app
```

3. Replace the files with your task-app files, then:
```bash
git add .
git commit -m "Add task app"
git push origin main
```

## Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. In the left menu, click **Pages**
4. Under "Source", select **Main branch** from the dropdown
5. Click **Save**
6. Wait 1-2 minutes...
7. You'll see a message: "Your site is published at: https://YOUR-USERNAME.github.io/task-app"

## Step 5: Add to Your iPhone Home Screen

1. On your iPhone, open **Safari**
2. Go to: `https://YOUR-USERNAME.github.io/task-app`
3. Tap the **Share** button (↗️)
4. Tap **Add to Home Screen**
5. Name it "Task App"
6. Tap **Add**

Done! 🎉 Your task app is now on your home screen!

## Need Help?

- **Can't see "Add to Home Screen"?** Make sure you're using Safari, not Chrome
- **Page says "404"?** Wait a few minutes - GitHub Pages takes time to deploy
- **Want to update the app?** Just edit index.html in your repository and commit

---

**Your app URL:** `https://YOUR-USERNAME.github.io/task-app`

Replace `YOUR-USERNAME` with your actual GitHub username!
