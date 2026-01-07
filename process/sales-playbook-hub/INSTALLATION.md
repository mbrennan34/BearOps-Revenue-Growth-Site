# BearOps Sales Enablement Platform - Installation Instructions

## ⚠️ IMPORTANT: How to Make the Links Work

The links between pages will NOT work when viewing individual files through Claude's interface. You need to download all files and open them locally or on a web server.

## 📥 Installation Steps

### Option 1: Download to Your Computer (Recommended for Testing)

1. **Download ALL 13 HTML files** from this conversation:
   - index.html
   - sales-enablement-dashboard.html
   - sales-playbooks.html
   - onboarding-timeline.html
   - meddicc.html
   - miller-heiman.html
   - icp-builder.html
   - content-library.html
   - discovery-framework.html
   - demo-structure.html
   - positioning-messaging.html
   - tech-stack-metrics.html
   - team-alignment.html

2. **Put them all in the same folder** on your computer
   - Example: `C:\BearOps-Enablement\` or `~/BearOps-Enablement/`
   - DO NOT put them in subfolders - they must all be at the same level

3. **Open index.html in your browser**
   - Double-click `index.html` 
   - OR right-click and choose "Open with" → Chrome/Firefox/Edge
   - You'll be redirected to the dashboard
   - All links will now work!

### Option 2: Upload to a Website (Recommended for Team Use)

1. **Upload all 13 HTML files** to your web server
   - Use FTP, cPanel, or your hosting provider's file manager
   - Put them all in the same directory (e.g., `/enablement/`)

2. **Access via URL**
   - Navigate to: `https://yourwebsite.com/enablement/`
   - OR: `https://yourwebsite.com/enablement/index.html`
   - Share this URL with your team

3. **Benefits of hosting**:
   - Accessible from anywhere
   - Team can use it simultaneously
   - Can track usage with analytics
   - Professional appearance

### Option 3: Host on GitHub Pages (Free)

1. Create a GitHub repository
2. Upload all 13 HTML files
3. Enable GitHub Pages in repository settings
4. Access at: `https://yourusername.github.io/repo-name/`

## ✅ Testing the Installation

Once files are in the same folder:

1. Open `index.html` in your browser
2. You should see the dashboard with 8 module cards
3. Click "Sales Playbooks" → should show 3 methodology tools
4. Click "MEDDICC" → should open MEDDICC tool
5. Click "← Back to Playbooks" → returns to playbooks hub
6. Click "🏠 Dashboard" → returns to main dashboard

## 🔧 Troubleshooting

**Problem: Links still don't work**
- ✅ Make sure ALL 13 files are in the same folder
- ✅ Don't open files from different locations
- ✅ Try a different browser (Chrome recommended)
- ✅ Check for typos in filenames (they're case-sensitive on some systems)

**Problem: Page looks broken**
- ✅ Make sure you have internet connection (loads Google Fonts)
- ✅ Clear your browser cache
- ✅ Try opening in incognito/private mode

**Problem: Can't find certain tools**
- ✅ MEDDICC, Miller Heiman, ICP Builder: Go through Sales Playbooks hub
- ✅ They're not directly on the dashboard - it's a two-level navigation

## 📂 File Structure

```
your-folder/
├── index.html                          ← Start here
├── sales-enablement-dashboard.html     ← Main dashboard
├── sales-playbooks.html                ← Methodologies hub
├── onboarding-timeline.html           ← 90-day onboarding
├── meddicc.html                       ← MEDDICC tool
├── miller-heiman.html                 ← Miller Heiman tool
├── icp-builder.html                   ← ICP Builder tool
├── content-library.html               ← Placeholder
├── discovery-framework.html           ← Placeholder
├── demo-structure.html                ← Placeholder
├── positioning-messaging.html         ← Placeholder
├── tech-stack-metrics.html           ← Placeholder
└── team-alignment.html               ← Placeholder
```

## 🎯 Navigation Flow

```
index.html
    ↓
Dashboard (main hub)
    ├── Training & Onboarding → onboarding-timeline.html
    ├── Sales Playbooks → sales-playbooks.html
    │       ├── MEDDICC → meddicc.html
    │       ├── Miller Heiman → miller-heiman.html
    │       └── ICP Builder → icp-builder.html
    ├── Content Library → content-library.html
    ├── Discovery Framework → discovery-framework.html
    ├── Demo Structure → demo-structure.html
    ├── Positioning & Messaging → positioning-messaging.html
    ├── Tech Stack & Metrics → tech-stack-metrics.html
    └── Team Alignment → team-alignment.html
```

## 💡 Pro Tips

1. **Bookmark the dashboard** once you have it working locally
2. **Keep all files together** - don't reorganize or rename them
3. **Back up regularly** - especially if you're adding custom content
4. **Use a local web server** for best results (MAMP, XAMPP, or `python -m http.server`)

## 🆘 Still Need Help?

If you're still having issues:
1. Make sure you downloaded ALL 13 files
2. Check they're all in the SAME folder
3. Open `index.html` first (not individual pages)
4. Try in Chrome browser
5. Check browser console for errors (F12 → Console tab)

---

**Remember: The links work perfectly - you just need all files in the same folder!**
