# 🚀 AMAN HUB - Install as App Guide

## ✨ **What's New?**

AMAN HUB is now a Progressive Web App (PWA)! You can install it on your device and use it like a native app.

---

## 📱 **How to Install?**

### **On Android:**
1. Open AMAN HUB in Chrome browser
2. Look for the **Download (📥)** button in the header
3. Tap the **Install** button
4. Confirm installation
5. ✅ App will appear on your home screen

**Alternative:**
- Tap the **3 dots menu** in Chrome
- Select **"Install app"** or **"Add to Home screen"**

### **On iPhone/iPad:**
1. Open AMAN HUB in Safari browser
2. Tap the **Share** button (bottom center)
3. Scroll down and select **"Add to Home Screen"**
4. Name it "AMAN HUB"
5. ✅ App will appear on your home screen

### **On Desktop (Windows/Mac):**
1. Open AMAN HUB in Chrome browser
2. Look for the **Download (📥)** button in the header
3. Click **Install**
4. ✅ App will be installed and a shortcut will be created

---

## 🎯 **Features of Installed App:**

✅ **Standalone Experience**
- Uses full screen (no browser address bar)
- Looks and feels like a native app
- Separate window from browser

✅ **Offline Support**
- Access cached content even without internet
- Service Worker caches images and pages
- Perfect for viewing your gallery offline

✅ **App Icon**
- Custom icon on home screen
- Appears in app switcher
- Custom splash screen on launch

✅ **Quick Shortcuts**
- Tap and hold app icon to see shortcuts
- Quick access to Upload Photo
- Direct link to Gallery view

✅ **Performance**
- Faster loading from cache
- Reduced data usage
- Better battery life

---

## 📁 **Files Included:**

You need 3 files in the same folder:

```
📂 Folder
├── 📄 aman_hub_final.html    (Main app file)
├── 📄 manifest.json           (App configuration)
└── 📄 sw.js                   (Service Worker - offline)
```

**❌ Don't forget any file!**

---

## ⚙️ **App Configuration (manifest.json):**

```json
{
  "name": "AMAN HUB - Photography Portfolio Platform",
  "short_name": "AMAN HUB",
  "start_url": "./",
  "display": "standalone",
  "theme_color": "#0a0e27",
  "background_color": "#0a0e27"
}
```

---

## 🔄 **Service Worker (sw.js):**

The service worker automatically:
- **Caches** images and pages on first visit
- **Serves** cached content offline
- **Updates** cache when online
- **Syncs** data when connection returns

No manual action needed! 🤖

---

## 🌐 **Browser Support:**

| Browser | Android | iPhone | Desktop |
|---------|---------|--------|---------|
| Chrome | ✅ | ❌* | ✅ |
| Safari | ❌ | ✅ | ❌ |
| Edge | ✅ | ❌* | ✅ |
| Firefox | ✅ | ❌* | ✅ |

*iPhone uses Safari's "Add to Home Screen"

---

## 🛠️ **Troubleshooting:**

### **Install button not showing?**
- Use a supported browser (Chrome, Edge, Firefox)
- Check if site is served over HTTPS or localhost
- Clear browser cache and reload

### **App not working offline?**
- First visit the online site to cache content
- Service Worker needs time to download resources
- Check if you're truly offline (toggle airplane mode)

### **Update not applying?**
- Clear app cache: Settings → App → AMAN HUB → Storage → Clear Cache
- Uninstall and reinstall the app
- Check browser console for errors

### **Can't uninstall?**
- **Android**: Long press app → Uninstall
- **iPhone**: Long press icon → Remove App
- **Desktop**: Right click shortcut → Delete

---

## 🚀 **What You Can Do:**

✅ Upload photos (stored in browser)
✅ View gallery offline
✅ Like photos
✅ Search and filter
✅ Dark/Light mode
✅ All features work offline

---

## 📊 **App Storage:**

- **Browser cache**: ~10-50MB (customizable)
- **IndexedDB**: ~100MB for uploaded photos
- **LocalStorage**: Settings and preferences

---

## 🔐 **Privacy & Security:**

✅ All data stored locally on your device
✅ No server required
✅ No tracking or analytics
✅ Your photos are completely private
✅ Works offline and online

---

## 💡 **Tips:**

1. **First visit**: Open the online version to cache everything
2. **Home screen**: Install app for easy access
3. **Quick links**: Use app shortcuts for faster action
4. **Dark mode**: Reduce battery usage on OLED screens
5. **Storage**: Old browsers have smaller cache limits

---

## 📞 **Need Help?**

Check browser console (F12 > Console tab) for any errors.

Service Worker logs start with ✅ or ❌ for debugging.

---

## ✨ **Enjoy Your App!**

Your photography portfolio is now available as a fully functional offline app! 📸

Download it, install it, and share your amazing photos! 🎉
