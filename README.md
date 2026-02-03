# 🍎 NutriSnap - AI Calorie Tracker PWA

A Progressive Web App for tracking nutrition with AI-powered food recognition, personalized goals, and comprehensive food database.

## 📱 Features

- ✅ **AI Food Recognition** - Take photos of meals for automatic calorie calculation
- ✅ **600+ Food Database** - Comprehensive Asian and Western foods
- ✅ **Smart Search** - Grouped search with serving size adjustment
- ✅ **Manual Entry** - Per-100g input with automatic calculation
- ✅ **Personalized Goals** - BMR/TDEE calculation for cutting, bulking, or maintaining
- ✅ **Weight Tracking** - Monitor weight trends alongside nutrition
- ✅ **7-Day Charts** - Visual progress tracking
- ✅ **Excel Export** - Complete data export with multiple sheets
- ✅ **Offline Support** - Works without internet after initial load
- ✅ **No Account Required** - All data stored locally on your device

## 🚀 Quick Start (For Friends/Testers)

### Method 1: Direct Install (Recommended)

1. **On iPhone:**
   - Open Safari and visit: `[YOUR_HOSTED_URL]`
   - Tap the Share button (square with arrow)
   - Scroll down and tap "Add to Home Screen"
   - Name it "NutriSnap" and tap "Add"
   - The app icon will appear on your home screen!

2. **On Android:**
   - Open Chrome and visit: `[YOUR_HOSTED_URL]`
   - Tap the menu (three dots)
   - Tap "Add to Home Screen" or "Install App"
   - Confirm installation
   - The app will appear in your app drawer!

### Method 2: From Files

If you receive the files via email/messaging:

1. Download all files to the same folder
2. Open `calorie-tracker.html` in your browser
3. Follow the "Add to Home Screen" steps above

## 📂 Files Included

```
nutrisnap-pwa/
├── calorie-tracker.html    # Main app file
├── manifest.json           # PWA configuration
├── service-worker.js       # Offline functionality
├── icon-generator.html     # Generate app icons
└── README.md              # This file
```

## 🎨 Generating Icons

1. Open `icon-generator.html` in your browser
2. Right-click each icon and save with the suggested filename:
   - icon-72.png
   - icon-96.png
   - icon-128.png
   - icon-144.png
   - icon-152.png
   - icon-192.png
   - icon-384.png
   - icon-512.png
3. Place all icons in the same folder as the HTML file

## 🌐 Hosting Options (For Sharing)

### Option 1: GitHub Pages (Free, Easy)

1. Create a GitHub account (if you don't have one)
2. Create a new repository named "nutrisnap"
3. Upload all files to the repository
4. Go to Settings → Pages
5. Select "main" branch and click Save
6. Your app will be live at: `https://[username].github.io/nutrisnap/calorie-tracker.html`
7. Share this URL with friends!

### Option 2: Netlify Drop (Easiest)

1. Go to https://app.netlify.com/drop
2. Drag and drop your folder
3. Get an instant URL like: `https://random-name.netlify.app`
4. Share this URL with friends!

### Option 3: Google Drive (Quick & Dirty)

1. Upload `calorie-tracker.html` to Google Drive
2. Right-click → Get Link → Set to "Anyone with the link"
3. Copy the file ID from the link
4. Share this URL: `https://drive.google.com/uc?export=download&id=[FILE_ID]`
5. Friends can download and open in Safari/Chrome

### Option 4: Vercel (Professional)

1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel` in the project folder
3. Follow prompts
4. Get a URL like: `https://nutrisnap.vercel.app`

## 📱 Installation Instructions (Send to Friends)

**Hey! I made a calorie tracking app. Here's how to install it:**

**iPhone Users:**
1. Open this link in Safari: `[YOUR_URL]`
2. Tap Share button (bottom middle)
3. Scroll down → "Add to Home Screen"
4. Tap "Add"
5. Done! Open from your home screen like any app

**Android Users:**
1. Open this link in Chrome: `[YOUR_URL]`
2. Tap the menu (⋮)
3. Tap "Add to Home Screen" or "Install App"
4. Done! Find it in your app drawer

**Features:**
- 📸 Take photos of food for AI calorie detection
- 🔍 Search 600+ foods with serving size adjustment
- ✏️ Manual entry with per-100g calculation
- 📊 Track weight and see 7-day charts
- 💪 Personalized goals (cut/maintain/bulk)
- 📥 Export to Excel
- 🔒 All data stays on your device (private & offline)

## 🔧 Technical Details

### PWA Features
- **Service Worker**: Caches resources for offline use
- **Manifest**: Makes app installable on mobile devices
- **localStorage**: Stores all data locally (no server needed)
- **Responsive Design**: Works on all screen sizes

### Browser Support
- ✅ Safari (iOS 11.3+)
- ✅ Chrome (Android 5+)
- ✅ Edge (Desktop)
- ✅ Firefox (Desktop)

### Storage
- All data stored in browser localStorage
- No account or login required
- Data persists across sessions
- Manual export for backup

### Privacy
- ✅ No tracking or analytics
- ✅ No data sent to servers (except AI photo analysis)
- ✅ No cookies or user profiling
- ✅ Open source - view the code yourself

## 🐛 Troubleshooting

**"Blank page appears"**
- Clear browser cache
- Make sure all files are in the same folder
- Try a different browser

**"Can't add to home screen"**
- Make sure you're using Safari (iOS) or Chrome (Android)
- Check that icons are generated and in the same folder
- Try opening the manifest.json to verify it loads

**"Offline doesn't work"**
- Load the app once while online
- Service worker needs initial registration
- Check browser console for errors

**"Icons don't appear"**
- Generate icons using icon-generator.html
- Place them in the same folder as calorie-tracker.html
- Clear cache and reinstall

## 📊 Data Export/Import

**Backup Your Data:**
1. Open app → History tab
2. Click "Export JSON" or "Export Excel"
3. Save the file somewhere safe

**Restore Data:**
1. Open app → History tab
2. Click "Import"
3. Select your backup file
4. Confirm restoration

## 🎯 Usage Tips

- **Track consistently**: Log meals right after eating
- **Use photos**: AI recognition is pretty accurate for common foods
- **Adjust servings**: Always verify serving sizes in search
- **Set realistic goals**: Use the Profile tab to calculate your targets
- **Export weekly**: Keep backups of your data
- **Share progress**: Export to Excel and share with trainers/nutritionists

## 💡 Pro Tips

1. **Meal Prep**: Calculate once, log multiple times
2. **Restaurant Meals**: Use manual entry with per-100g from nutrition info
3. **Recipes**: Calculate ingredients, divide by servings
4. **Snacks**: Search + adjust serving size = perfect tracking
5. **Progress**: Check History chart weekly to spot trends

## 📞 Feedback & Issues

This is a test version! If you find bugs or have suggestions:
- Take a screenshot
- Note what you were doing
- Share feedback with me

## 🔐 Privacy & Security

- ✅ No server-side data storage
- ✅ No user accounts or passwords
- ✅ No data sharing or selling
- ✅ AI photo analysis uses Claude API (only for food recognition)
- ✅ All nutrition data stored locally in your browser

## 📜 License

Free to use for personal purposes. Share with friends!

---

**Enjoy tracking your nutrition with NutriSnap! 🍎💪**
