# 💕 Proposal Website for Sneha

A beautiful, interactive proposal website created by Jenish for Sneha!

## 🚀 How to Deploy (Step by Step)

### Step 1: Create a Free Database (JSONBin.io)

1. Go to [https://jsonbin.io](https://jsonbin.io)
2. Click **"Create Account"** (it's free!)
3. After logging in, click **"Create a Bin"**
4. Enter `[]` as the content and click **"Create"**
5. Copy your **Bin ID** (looks like: `6745abc123def456`)
6. Go to **API Keys** section and copy your **X-Access-Key**

### Step 2: Update the Code

Open these files and replace the placeholders:

**In `index.html` (around line 290):**
```javascript
const JSONBIN_BIN_ID = 'YOUR_BIN_ID_HERE';     // Paste your Bin ID
const JSONBIN_API_KEY = 'YOUR_API_KEY_HERE';  // Paste your API Key
```

**In `admin.html` (around line 165):**
```javascript
const JSONBIN_BIN_ID = 'YOUR_BIN_ID_HERE';     // Same Bin ID
const JSONBIN_API_KEY = 'YOUR_API_KEY_HERE';  // Same API Key
const githubUsername = 'YOUR_GITHUB_USERNAME'; // Your GitHub username
```

### Step 3: Create GitHub Repository

1. Go to [https://github.com](https://github.com) and log in
2. Click the **"+"** button → **"New repository"**
3. Name it: `proposal-for-sneha`
4. Make it **Public**
5. Click **"Create repository"**

### Step 4: Upload Files to GitHub

Run these commands in your terminal:

```bash
cd e:\project
git init
git add .
git commit -m "💕 Proposal for Sneha"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/proposal-for-sneha.git
git push -u origin main
```

### Step 5: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** → **"Pages"** (in the left sidebar)
3. Under "Source", select **"main"** branch
4. Click **"Save"**
5. Wait 2-3 minutes for deployment

### Step 6: Get Your Links! 🎉

- **Send to Sneha:** `https://YOUR_USERNAME.github.io/proposal-for-sneha/`
- **Check responses:** `https://YOUR_USERNAME.github.io/proposal-for-sneha/admin.html`

---

## 💖 Good Luck, Jenish!

May Sneha say YES! 🤞💕🎉

---

## 📁 Files

- `index.html` - The beautiful proposal page
- `admin.html` - Dashboard to view responses
- `README.md` - This file with instructions
