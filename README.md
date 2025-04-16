# 🔥 Ad Remover - Ultimate Adblock Extension & Youtube Killer

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/none?label=Chrome%20Version)](https://developer.chrome.com/docs/webstore/)
![GitHub repo size](https://img.shields.io/github/repo-size/EVL44/Ad-Remover)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

**The most aggressive ad-blocker for Chrome that mercilessly destroys:**  
🎥 YouTube ads | 📢 Pop-ups | 🕵️ Tracking scripts | 💰 Adware | 🍪 Third-party cookies  

![Extension Demo](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2RqN3BwY3d6Z3h1c2l1bDZ5N2ZqYzJ6eHlwN3RqZ3F5dGx5aGt5dyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3ohzdIuqJniNz7bWn6/giphy.gif)

## 🚀 Features

- **Nuclear-grade ad blocking**
  - ✅ Pre/mid/post-roll YouTube video ads
  - ✅ YouTube banner/overlay ads
  - ✅ Pop-ups & redirects
  - ✅ Tracking scripts (Google Analytics, Facebook Pixel)
  - ✅ Malware/adware domains

- **Next-gen tech**
  - ⚡ Manifest V3 support
  - 🛡️ DeclarativeNetRequest API
  - 🧠 Pattern-based filter updates
  - 📈 Real-time traffic monitoring
  - 🔄 Auto-skip sponsored content

- **Bonus perks**
  - 🕶️ Dark mode detection
  - ⏩ Video speed controls
  - 🧹 Cookie management
  - 📊 Resource usage monitor

## ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/EVL44/Ad-Remover.git

# Load in Chrome:
1. Enable Developer Mode at chrome://extensions
2. Click "Load unpacked"
3. Select the /dist folder
```
## Prerequisites:

  - Chrome 88+
  
  - Node.js 16+ (for development)
  
  - Git (optional)

## 🕹️ Usage
```bash
// Block additional domains by adding to rules.json
{
  "id": 69420,
  "action": { "type": "block" },
  "condition": {
    "urlFilter": "||annoyingadserver.com^",
    "resourceTypes": ["script"]
  }
}
```
## 🛠️ Configuration
Setting	Default	Description
aggressiveMode	true	Aggressive ad removal
youtubeAdSkipDelay	50ms	YouTube ad skip speed
cookieMaxAge	1h	Tracking cookie lifespan
resourceBlockList	[array]	Custom domains to block
## 🤝 Contributing
**Fork it 🍴**

Create your feature branch:

bash
Copy
git checkout -b feature/AmazingFeature
Commit changes:

```bash
git commit -m 'Add some AmazingFeature'
```

Push to branch:

```bash
git push origin feature/AmazingFeature
Open a Pull Request
```
First time contributing? Check out our contribution guidelines!

## 📜 License
Distributed under MIT License. See LICENSE for more information.

## 📧 Contact
Ad Remover Team - @EVL44
Project Link: https://github.com/EVL44/Ad-Remover

## 🙏 Acknowledgments
Inspired by uBlock Origin

Shoutout to Adblock Plus

Chrome Extension Docs team

Open source contributors
