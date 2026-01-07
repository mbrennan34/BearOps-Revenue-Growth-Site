# SETUP GUIDE - BearOps Sales Enablement Platform

## 🎯 DOWNLOAD THE ZIP FILE

**Download this single file:** BearOps-Sales-Enablement.zip

This ZIP contains all 13 HTML files + documentation.

---

## 📦 INSTALLATION (3 STEPS)

### STEP 1: Extract the ZIP
- **Windows:** Right-click → "Extract All" → Choose a location
- **Mac:** Double-click the .zip file
- **Recommended location:** Desktop or Documents folder

### STEP 2: Open the Folder
Navigate to the extracted folder. You should see:
```
BearOps-Sales-Enablement/
├── index.html                    ← OPEN THIS ONE!
├── sales-enablement-dashboard.html
├── sales-playbooks.html
├── meddicc.html
├── miller-heiman.html
├── icp-builder.html
├── onboarding-timeline.html
├── (+ 6 more HTML files)
└── (documentation files)
```

### STEP 3: Open index.html
Choose ONE of these methods:

**Method A: Double-Click**
- Find `index.html`
- Double-click it
- If it doesn't open, try Method B

**Method B: Right-Click → Open With**
- Right-click `index.html`
- Choose "Open with"
- Select "Google Chrome" (or Firefox/Edge)
- Check "Always use this app"
- Click OK

**Method C: Drag & Drop**
- Open Chrome/Firefox browser
- Drag `index.html` into the browser window
- Drop it

**Method D: Browser File Menu**
- Open Chrome/Firefox
- Press Ctrl+O (Windows) or Cmd+O (Mac)
- Browse to your folder
- Select `index.html`
- Click Open

---

## ✅ VERIFICATION

Once index.html opens, you should see:
- ✓ BearOps Sales Enablement Platform title
- ✓ Automatic redirect to dashboard
- ✓ Dashboard with 8 colorful module cards
- ✓ Click "Sales Playbooks" → see 3 methodology cards
- ✓ Click "MEDDICC" → opens MEDDICC tool
- ✓ Navigation buttons work

---

## 🚨 TROUBLESHOOTING

### Problem: Files won't open after moving them

**Solution 1: Check File Extensions**
Windows might be hiding extensions. 

1. Open File Explorer
2. Click "View" tab
3. Check "File name extensions"
4. Look at files - are they named:
   - `index.html` ✓ CORRECT
   - `index.html.txt` ✗ WRONG

If they have `.txt` at the end:
- Rename each file to remove `.txt`
- Example: Rename `index.html.txt` → `index.html`

**Solution 2: Security Restriction (Windows)**
Windows blocks files downloaded from the internet.

1. Right-click `index.html`
2. Choose "Properties"
3. At the bottom, look for "Security: This file came from another computer..."
4. Check the "Unblock" checkbox
5. Click "Apply" then "OK"
6. Repeat for each HTML file (or just the ones you're trying to open)

**Solution 3: File Association**
Your computer doesn't know HTML files should open in a browser.

1. Right-click any `.html` file
2. Choose "Open with" → "Choose another app"
3. Select Google Chrome or Firefox
4. Check "Always use this app to open .html files"
5. Click OK

**Solution 4: Browser Security**
Try opening in a different browser:
- Chrome (recommended)
- Firefox
- Edge
- Brave

**Solution 5: Use a Local Web Server**
If nothing else works, run a local server:

**Option A: Python (if installed)**
```
cd /path/to/BearOps-Sales-Enablement
python -m http.server 8000
```
Then open: http://localhost:8000

**Option B: Node.js (if installed)**
```
npx http-server
```

---

## 📍 IMPORTANT NOTES

1. **Keep all files together** - Don't separate them into subfolders
2. **Don't rename files** - The links reference specific filenames
3. **Internet required** - For Google Fonts to load (visual only)
4. **Modern browser needed** - Chrome, Firefox, Edge (latest versions)
5. **No installation required** - These are just HTML files

---

## 💻 UPLOADING TO A WEBSITE (Optional)

If you want to host this on the web:

1. **Upload the entire folder** to your web host
2. All files must be in the same directory
3. Access via: `https://yoursite.com/folder/index.html`
4. Share that URL with your team

**Benefits:**
- Access from anywhere
- No download needed
- Team collaboration
- Professional deployment

---

## 🆘 STILL STUCK?

If files still won't open:

1. **Check browser console for errors:**
   - Open the file
   - Press F12
   - Click "Console" tab
   - Screenshot any red errors

2. **Try the single-file version:**
   - Ask for a standalone version
   - Single HTML with everything embedded
   - No dependencies, no linking issues

3. **Verify file integrity:**
   - Check file sizes (shouldn't be 0 KB)
   - Open in Notepad - should see HTML code
   - If files are empty or corrupted, re-download

---

## 📧 QUICK START

1. Download BearOps-Sales-Enablement.zip
2. Extract to Desktop
3. Open index.html in Chrome
4. Bookmark the page
5. Start using the platform!

---

**The platform works perfectly - it's just a matter of getting the files to open in your browser!**
