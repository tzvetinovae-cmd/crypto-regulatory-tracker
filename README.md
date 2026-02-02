# Crypto Regulatory Tracker PWA

A Progressive Web App that monitors UK FCA & US SEC/CFTC cryptocurrency regulatory updates with real-time notifications.

## 📱 Installation on iPhone

### Method 1: Safari (Recommended)
1. Open Safari on your iPhone
2. Navigate to your hosted URL (e.g., `https://yourdomain.com`)
3. Tap the **Share** button (square with arrow pointing up)
4. Scroll down and tap **"Add to Home Screen"**
5. Tap **"Add"** in the top right
6. The app icon will appear on your home screen!

### Method 2: Chrome
1. Open Chrome on your iPhone
2. Navigate to your hosted URL
3. Tap the **Share** button
4. Tap **"Add to Home Screen"**
5. Follow the prompts

## 🚀 Features

- ✅ **Real-time monitoring** - Search for latest regulatory updates
- ✅ **Push notifications** - Get alerted when new updates are found
- ✅ **Offline support** - Works without internet (cached data)
- ✅ **Persistent storage** - Your settings and notifications are saved
- ✅ **Mobile optimized** - Responsive design for iPhone
- ✅ **Background sync** - Checks for updates even when closed
- ✅ **Installable** - Feels like a native app

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free)
```bash
# 1. Create a new GitHub repo
# 2. Upload these files:
#    - index.html
#    - manifest.json
#    - service-worker.js
#    - icon-192.png
#    - icon-512.png
# 3. Enable GitHub Pages in repo settings
# 4. Your app will be at: https://username.github.io/repo-name
```

### Option 2: Netlify (Free)
```bash
# 1. Create account at netlify.com
# 2. Drag and drop all files to Netlify
# 3. Get instant HTTPS URL
# 4. Done!
```

### Option 3: Vercel (Free)
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
cd /path/to/your/app
vercel

# Follow prompts
```

### Option 4: Cloudflare Pages (Free)
```bash
# 1. Sign up at pages.cloudflare.com
# 2. Connect GitHub repo or upload files
# 3. Deploy automatically
```

## 📁 Required Files

Make sure all these files are in the same directory:
- `index.html` - Main app file
- `manifest.json` - PWA configuration
- `service-worker.js` - Offline & caching
- `icon-192.png` - App icon (small)
- `icon-512.png` - App icon (large)

## 🔧 Configuration

Edit `manifest.json` to customize:
- App name and description
- Theme colors
- Icon paths
- Start URL

## 🔔 Notifications Setup

The app will request notification permission on first use. To enable:
1. Open the app
2. Tap "Start Monitoring"
3. Tap "Allow" when prompted for notifications
4. You'll now receive alerts for new regulatory updates!

## 🌍 Browser Support

| Browser | Support |
|---------|---------|
| Safari (iOS 14+) | ✅ Full |
| Chrome (iOS) | ✅ Full |
| Firefox (iOS) | ⚠️ Limited |
| Edge (iOS) | ✅ Full |

## 🐛 Troubleshooting

**App won't install:**
- Make sure you're using Safari or Chrome
- Check that you're on HTTPS (not HTTP)
- Clear browser cache and try again

**Notifications not working:**
- Go to iPhone Settings → Safari → Notifications
- Make sure notifications are enabled
- Check app permissions

**App not updating:**
- Force close and reopen
- Clear browser cache
- Reinstall the app

## 💡 Tips

- **Home screen placement:** Drag the app icon to your dock for quick access
- **Widget support:** iOS doesn't support PWA widgets yet, but notifications work great
- **Battery usage:** Minimal - checks only run when you open the app
- **Data usage:** Very low - only fetches when checking for updates

## 🔒 Privacy & Security

- All data stored locally on your device
- No data sent to external servers except:
  - Claude API for searches
  - Regulatory authority websites
- No tracking or analytics
- Open source code you can audit

## 📊 Storage Usage

- App size: ~500KB
- Cached data: ~2MB
- Icons: ~100KB
- Total: ~2.6MB

## 🤝 Support

If you have issues:
1. Check this README
2. Clear cache and reinstall
3. Make sure you're on latest iOS version
4. Try different browser

## 📄 License

Free to use and modify for personal or commercial use.

---

**Enjoy your crypto regulatory tracking! 🚀📊**
