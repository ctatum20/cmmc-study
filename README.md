# CMMC Level 2 Study Guide - Mobile App Setup 📱

This is a Progressive Web App (PWA) that works like a native app on your phone!

## 🆓 FREE Hosting Options

### Option 1: GitHub Pages (Recommended - 100% Free)

**Step 1: Create GitHub Account**
1. Go to https://github.com
2. Sign up (free)

**Step 2: Create a Repository**
1. Click the "+" icon → "New repository"
2. Name it: `cmmc-study` (or anything you want)
3. Make sure "Public" is selected
4. Check "Add a README file"
5. Click "Create repository"

**Step 3: Upload the Files**
1. In your new repo, click "Add file" → "Upload files"
2. Drag ALL these files into the upload area:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Click "Commit changes"

**Step 4: Enable GitHub Pages**
1. Go to your repo's "Settings" tab
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 1-2 minutes, then your site will be live at:
   `https://YOUR-USERNAME.github.io/cmmc-study/`

---

### Option 2: Netlify (Also Free, Drag & Drop)

1. Go to https://netlify.com
2. Sign up free
3. Drag the entire `cmmc-pwa` folder onto their dashboard
4. Done! They give you a free URL instantly

---

### Option 3: Vercel (Free)

1. Go to https://vercel.com
2. Sign up with GitHub
3. Import your GitHub repo
4. Auto-deploys!

---

## 📲 Add to Phone Home Screen

### iPhone (Safari)
1. Open your app URL in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add"
5. 🎉 It's now on your home screen like a real app!

### Android (Chrome)
1. Open your app URL in Chrome
2. Tap the 3-dot menu
3. Tap "Add to Home screen" or "Install app"
4. Tap "Add"
5. 🎉 It's now on your home screen!

---

## ✨ Features

- ✅ Works OFFLINE after first load
- ✅ Saves your progress automatically
- ✅ 4 quiz modes
- ✅ Check off controls as you study
- ✅ Filter by type or study status
- ✅ Mobile-friendly design

---

## 🔧 Troubleshooting

**App not installing?**
- Make sure you're using Safari (iPhone) or Chrome (Android)
- The site must be served over HTTPS (GitHub Pages does this automatically)

**Progress not saving?**
- Don't use Private/Incognito mode
- Allow cookies/local storage

**Offline not working?**
- Visit the site once while online first
- The service worker needs to cache files

---

## 💡 Tips

- Study a domain, then quiz yourself on it
- Use "Unstudied Only" quiz mode to focus on weak areas
- The flashcard mode is great for quick review
- Your progress syncs across sessions on the same device

Good luck on your CCA exam! 🎯
