# Twitch Combos Overlay Blocker

🚫 **Blocks Twitch New intrusive combo overlays that interrupt your viewing experience.**

A lightweight userscript that automatically removes combos overlays on Twitch, allowing you to enjoy streams without pop-up interruptions.

## What are Twitch Combos?

Twitch Combos are interactive overlay features that appear during streams to encourage viewer engagement. While some viewers enjoy them, others find them disruptive to the viewing experience. [Learn more about Twitch Combos](https://help.twitch.tv/s/article/combos?language=en_US)

## ✨ Features

- **🔄 Real-time blocking** - Instantly removes combos overlays as they appear
- **🎨 CSS-based hiding** - Multiple layers of protection using CSS rules  
- **👁️ DOM monitoring** - Watches for dynamically added overlay elements
- **⚡ Zero configuration** - Works out of the box with smart detection
- **🐛 Debug logging** - Optional console logging for troubleshooting
- **🪶 Lightweight** - Minimal performance impact on your browsing

## 🚀 Quick Installation

### Step 1: Install a Userscript Manager
Choose one of these browser extensions:

| Browser | Recommended Extension |
|---------|----------------------|
| **Chrome** | [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) |
| **Firefox** | [Tampermonkey](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/) or [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) |
| **Safari** | [Tampermonkey](https://apps.apple.com/us/app/tampermonkey/id1482490089) |
| **Edge** | [Tampermonkey](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd) |

### Step 2: Install the Script
**[📥 Click here to install](https://raw.githubusercontent.com/nebhay/twitch-combos-blocker/main/twitch-combos-blocker.user.js)**

Your userscript manager will automatically detect and prompt you to install the script.

### Step 3: Enjoy!
The script activates automatically on all Twitch pages. No additional setup required!

## 🛠️ How It Works

The blocker uses multiple detection and blocking methods:

1. **CSS Injection** - Applies comprehensive CSS rules to hide combos overlays
2. **DOM Mutation Observer** - Monitors page changes and removes new overlay elements  


## 🐛 Troubleshooting

### Script Not Working?
1. **Check if your userscript manager is enabled**
2. **Refresh the Twitch page** after installation
3. **Check browser console** (F12) for any error messages
4. **Verify the script is active** in your userscript manager dashboard

### Still Seeing Combos?
1. **Enable debug logging** by setting `CONFIG.DEBUG = true`
2. **Check console logs** to see what elements are being detected
3. **Report the issue** with console logs and screenshots

### Performance Issues?
The script is designed to be lightweight, but if you experience issues:
1. **Disable debug logging** by setting `CONFIG.DEBUG = false`
2. **Check for conflicts** with other userscripts or extensions

## 📋 Compatibility

- ✅ **Browsers**: Chrome, Firefox, Safari, Edge
- ✅ **Userscript Managers**: Tampermonkey, Greasemonkey, Violentmonkey




## 🔗 Links

- **[Official Twitch Combos Documentation](https://help.twitch.tv/s/article/combos?language=en_US)**
- **[Install Script](https://raw.githubusercontent.com/nebhay/twitch-combos-blocker/main/twitch-combos-blocker.user.js)**
- **[Report Issues](https://github.com/nebhay/twitch-combos-blocker/issues)**
- **[Tampermonkey](https://tampermonkey.net/)**

---

⭐ **If this script helped you, consider giving it a star!** ⭐

*Made with ❤️ by nebhay*
