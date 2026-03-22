# 🚀 AMAN HUB - App Installation Guide

## 📦 **Files You Have:**

```
📂 Folder
├── 📄 index.html          (Main app)
├── 📄 manifest.json       (App config)
├── 📄 sw.js               (Service Worker)
└── 🖼️ aman.png            (App Logo)
```

---

## 🎨 **AMAN Logo (aman.png)**

✨ **Professional Camera Icon**
- Orange & Cyan color scheme
- Camera design with "AMAN" text
- Perfect for app installation
- Works on all devices
- Scales from 192x192 to 512x512 pixels

**Used for:**
- Home screen icon (Android & iPhone)
- App launcher icon
- Browser tab icon
- Splash screen
- App store display

---

## 📱 **How to Install:**

### **Android (Chrome):**
1. Open `index.html` in Chrome
2. Tap **Download button** (📥) in header
3. Tap **Install** → **Install app**
4. ✅ App with **AMAN logo** on home screen!

### **iPhone (Safari):**
1. Open `index.html` in Safari
2. Tap **Share** button (⬆️)
3. Select **"Add to Home Screen"**
4. Name: "AMAN HUB"
5. ✅ App with **AMAN logo** appears!

### **Desktop (Chrome/Edge):**
1. Open `index.html` in browser
2. Click **Download button** (📥)
3. Click **Install**
4. ✅ Desktop app shortcut created!

---

## 🎯 **App Icon Details:**

- **Logo File:** aman.png
- **Colors:** Blue (#0a0e27), Orange (#ff6b35), Cyan (#00d9ff)
- **Format:** SVG-based PNG
- **Sizes:** 192px, 512px
- **Transparency:** Full support
- **Rounded Corners:** Auto-applied on iOS

---

## ⚙️ **Setup Files:**

### **manifest.json** (App Configuration)
```json
{
  "name": "AMAN HUB - Photography Portfolio Platform",
  "short_name": "AMAN HUB",
  "start_url": "./",
  "display": "standalone",
  "theme_color": "#0a0e27",
  "background_color": "#0a0e27",
  "icons": [
    {
      "src": "aman.png",
      "sizes": "192x192",
      "type": "image/png"
    },
    {
      "src": "aman.png",
      "sizes": "512x512",
      "type": "image/png"
    }
  ]
}
```

### **sw.js** (Service Worker)
- Offline support
- Caching strategy
- Auto-sync on reconnect

### **index.html** (App Code)
- Complete photography portfolio
- Photo upload system
- Gallery with filters
- Dark/Light mode
- Full PWA features

---

## 📸 **App Features:**

✅ **Photography Gallery**
- Upload unlimited photos
- Filter by category
- Search functionality
- Lightbox preview

✅ **Offline Support**
- Works without internet
- Service Worker caching
- Full functionality offline

✅ **Responsive Design**
- Mobile optimized
- Tablet friendly
- Desktop compatible

✅ **Dark/Light Mode**
- Toggle anytime
- Auto-saves preference
- Beautiful transitions

✅ **App Installation**
- One-click install
- Home screen icon (aman.png logo)
- Full screen experience
- No browser chrome

---

## 🚀 **Quick Start:**

1. **Download all 4 files**
   - index.html
   - manifest.json
   - sw.js
   - aman.png

2. **Keep in same folder**
   ```
   📂 my-app/
   ├── index.html
   ├── manifest.json
   ├── sw.js
   └── aman.png
   ```

3. **Open index.html**
   - Right-click → Open with Browser
   - Or double-click in file explorer

4. **Install as App**
   - Look for Download button (📥) in header
   - Click to install
   - Confirm installation
   - App appears on home screen with AMAN logo!

---

## 💻 **Browser Support:**

| Browser | Android | iPhone | Desktop |
|---------|---------|--------|---------|
| Chrome | ✅ | ❌* | ✅ |
| Safari | ❌ | ✅ | ❌ |
| Edge | ✅ | ❌* | ✅ |

*Use "Add to Home Screen" on iOS Safari

---

## 🎨 **Customizing the Logo:**

Don't like the design? You can:
1. Edit `aman.png` in image editor
2. Replace with your own logo (192x192 & 512x512)
3. Keep filename as `aman.png`
4. Update manifest.json if needed

---

## 🔒 **Privacy & Security:**

✅ All data stored locally
✅ No server needed
✅ No tracking
✅ Completely offline capable
✅ Your photos stay private

---

## ⚠️ **Troubleshooting:**

**Install button not showing?**
- Use Chrome, Edge, or Firefox
- Must be served over HTTPS or localhost
- Clear browser cache

**App not working offline?**
- First visit the online site
- Service Worker needs time to cache
- Check browser console for errors

**Logo not appearing?**
- Make sure `aman.png` is in same folder
- Check manifest.json has correct icon paths
- Hard-refresh the app (Ctrl+F5)

---

## 📚 **What to Know:**

- **First Visit:** Takes time to cache everything
- **Offline:** Works perfectly after first visit
- **Updates:** Reinstall app for major updates
- **Storage:** Browser has cache limits (50-100MB)
- **Data:** All stored locally, very secure

---

## 🎉 **You're All Set!**

Your AMAN HUB app is ready to install!

**Download all 4 files and enjoy:**
- 📸 Professional photography platform
- 🚀 App installation with beautiful logo
- 📱 Works on all devices
- 🔓 Completely offline
- ❤️ Made for photographers

---

## 📞 **Need Help?**

1. Check browser console (F12 > Console)
2. Look for error messages
3. Clear browser cache and retry
4. Check that all 4 files are in same folder

**Enjoy your AMAN HUB app!** 🎉📸
