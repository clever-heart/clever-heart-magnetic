<div align="center">

<img src="./assets/image/app_logo.jpg" alt="Clever Heart Magnetic Collection" width="120" height="120">

#  Clever Heart Magnetic Collection Ciallo～(∠・ω< )⌒★

**Local Magnet/ED2K Resource Collection Management Tool**

🔒 A magnet/ED2K link management software focused on privacy protection

</div>

<div align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Android-brightgreen.svg" alt="Platform">
  <img src="https://img.shields.io/badge/Language-Flutter-blue.svg" alt="Language">
  <img src="https://img.shields.io/badge/Version-1.0.4-orange.svg" alt="Version">
</div>

<div align="right">
  <a href="./README.md">中文</a> | <a href="./README_EN.md">English</a>
</div>

---

## 📖 Introduction

**Clever Heart Magnetic Collection** is a lightweight magnet link and ED2K link collection management tool. All data is stored completely locally, no user information is uploaded, protecting your privacy. If the software becomes popular, I will consider open-sourcing it.

---

## ✨ Main Features

### 🔍 Search & Collection
- Support custom search sources for quick resource discovery
- One-click collection of magnet/ED2K links
- Save recent search history

### 📂 Category Management
- Flexible category system: create, rename, delete, hide
- Batch operations: multi-select, batch delete, batch move, batch share
- Support manual sorting, sort by time, sort by name

### 🎬 Online Playback
- Support VOD and P2P playback modes
- Auto-parse magnet link file list, multi-file selection playback
- Player features: subtitle search & settings, screenshot save, resume playback, audio/subtitle track switching, video adjustment (brightness/contrast/saturation/super resolution), lock screen mode
- VOD/P2P mode auto-remembers last selection

### 📥 Download Management
- Magnet link multi-file selection download (video and audio files only)
- Download task card display (collection header + sub-file structure)
- Support pause/resume/delete download tasks
- Independent progress and speed display for sub-files
- Video first-frame thumbnail extraction

### 📜 Playback History
- Auto-record playback progress, resume on reopen
- Auto-cover fetch (prioritize collection cover)
- Support multi-select delete playback records

### ️ Cover Management
- Support local upload cover images
- Online search for cover images
- Smart image detection
- saveBase64 switch: save network covers as Base64, visible offline
- Network image disk cache

### 🌐 Built-in Browser
- Built-in browser, no need to switch apps
- Auto-detect magnet links and ED2K links in pages
- Ad blocking feature
- Tab management
- Settings page supports setting as default browser for quick capture of magnet/ED2K links in pages

### 🔗 One-Click Open
- Support one-click invoke third-party apps installed on system
- Support opening: Xunlei, 115 Netdisk and other apps supporting magnet links and ED2K
- Support opening various online magnet playback software
- Support mark as downloaded feature, quick copy name for downloaded or empty collections, quick search in other apps

### 💾 Data Backup
- JSON format import/export
- LAN transfer backup files
- Backup management: rename, delete, mark as important
- Diff comparison feature

### 🎨 Personalization Settings
- Dark/Light mode switching
- Multiple preset theme styles
- Custom theme colors
- Support Chinese/English switching

---

## 📥 Download & Install

### 💻 Windows/Android Version

Go to [Releases](https://github.com/clever-heart/clever-heart-magnetic/releases/) page to download the latest version installer.

### 📋 System Requirements

- 🪟 Windows 10 or higher
- 🤖 Android 5.0 or higher

> 📌 **Note**: Currently only Windows and Android platforms are supported

---

## 🖼️ App Screenshots

### 💻 Windows Platform

|                                              Windows-Explore Home                                               | Windows-Collection Management |
|:-------------------------------------------------------------------------------------------------------:|:---:|
| <img src="./assets/image/windows-page-1.png" alt="Windows-Explore Home" style="width: 100%; max-width: 400px;"> | <img src="./assets/image/windows-page-2.png" alt="Windows-Collection Management" style="width: 100%; max-width: 400px;"> |

|                                              Windows-Record Management                                               |                                              Windows-Settings Page                                               |
|:-------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------:|
| <img src="./assets/image/windows-page-3.png" alt="Windows-Record Management" style="width: 100%; max-width: 400px;"> | <img src="./assets/image/windows-page-4.png" alt="Windows-Settings Page" style="width: 100%; max-width: 400px;"> |

|                                              Windows-Online Playback                                               |                                              Windows-Download Management                                               |
|:-------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------:|
| <img src="./assets/image/windows-page-5.png" alt="Windows-Online Playback" style="width: 100%; max-width: 400px;"> | <img src="./assets/image/windows-page-6.png" alt="Windows-Download Management" style="width: 100%; max-width: 400px;"> |

### 📱 Android Platform

|                                             Android-Explore Home                                              | Android-Collection Management |
|:-----------------------------------------------------------------------------------------------------:|:---:|
| <img src="./assets/image/phone-page-1.png" alt="Android-Explore Home" style="width: 100%; max-width: 180px;"> | <img src="./assets/image/phone-page-2.png" alt="Android-Collection Management" style="width: 100%; max-width: 180px;"> |

|                                              Android-Settings                                               |                                             Android-Web Browsing                                              |
|:-----------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------:|
| <img src="./assets/image/phone-page-3.png" alt="Android-Record Management" style="width: 100%; max-width: 180px;"> | <img src="./assets/image/phone-page-4.png" alt="Android-Settings Page" style="width: 100%; max-width: 180px;"> |

|                                             Android-Online Playback                                              | Android-Download Management |
|:-----------------------------------------------------------------------------------------------------:|:---:|
| <img src="./assets/image/phone-page-5.png" alt="Android-Online Playback" style="width: 100%; max-width: 180px;"> | <img src="./assets/image/phone-page-6.png" alt="Android-Download Management" style="width: 100%; max-width: 180px;"> |

---

## 📚 User Guide

### 🚀 First Time Use

1. Download and install the software
2. Open the software and start adding your first collection
3. Configure search sources and cover sources in settings

### ➕ Add Collection

**Method 1: Manual Add**
1. Click the "+" button in the bottom right
2. Enter magnet link or ED2K link
3. Fill in title, select category
4. Optional: Add cover image

**Method 2: Add from Browser**
1. Open built-in browser
2. Visit resource website
3. Software will auto-detect magnet/ED2K links in the page
4. Click link to quick collect

### 🎬 Online Playback

1. Click magnet link in search results or collection list, resource parse page pops up
2. Select file to play, click play button
3. Android can choose VOD or P2P mode, desktop only supports P2P mode
4. During playback, tap screen to show control bar: screenshot, subtitle settings, video adjustment, audio/subtitle switching, lock screen
5. After exit, reopen same resource to resume

### ⬇️ Download Management

1. In resource parse page, select files to download (only video and audio files can be downloaded), click download button
2. Download task cards display in download management page, click to expand and view sub-file details
3. Support pause/resume/delete operations
4. Android notification bar can view download progress

### 🔄 Data Backup & Restore

**Backup Data**
1. Go to Settings -> Data Backup
2. Click "Export Backup"
3. Select save location

**Restore Data**
1. Go to Settings -> Data Backup
2. Click "Import Backup"
3. Select backup file

**LAN Transfer**
1. On sending device: Settings -> Data Backup -> LAN Transfer -> Send
2. On receiving device: Settings -> Data Backup -> LAN Transfer -> Receive
3. Scan QR code or enter address to complete transfer

---

## ❓ FAQ

### Q: Where is data stored?
A: All data is stored completely on your local device, not uploaded to any server.

### Q: How to switch devices?
A: Use data backup feature to export backup file, then import on new device.

### Q: What link formats are supported?
A: Support magnet links (magnet:?xt=...) and ED2K links (ed2k://...).

### Q: How to add custom search sources?
A: Go to Settings -> Search Source Management, click add button, enter search source name and URL template.

### Q: What's the difference between VOD and P2P modes?
A: VOD mode is only available on Android with fast download speed; P2P mode is available on all platforms without third-party SDK. Last selected mode is auto-remembered.

---

## 🔐 Privacy Statement

- ✅ All data stored completely locally, no user information uploaded
- ✅ No user behavior data collected
- ✅ Network requests only for search and fetching cover images

---

## 👤 Contact Author

**Bilibili: 咕噜咕噜大法师**

If you have questions or suggestions, feel free to contact me via Bilibili or this site.

---

## 📝 Changelog

### v1.0.4
- ✨ New: Magnet online playback — VOD (Android only) and P2P (all platforms) modes, support multi-file selection playback
- ✨ New: Player — subtitle search/settings, screenshot, resume playback, audio/subtitle switching, video adjustment (brightness/contrast/saturation/super resolution), lock screen
- ✨ New: Download management — multi-file selection download, task cards (collection+sub-files), pause/resume/delete, independent progress
- ✨ New: Playback history — auto-record progress and resume, auto-cover fetch, multi-select delete
- ✨ New: Enhanced cover management — saveBase64 switch, network image disk cache
- ✨ New: Android notification bar — playback progress/download details, VOD/P2P mode tags
- ✨ New: Desktop system tray — minimize to tray, close confirmation, ESC back
- ✨ New: Changelog Markdown rendering and image display
- 🎨 Improved: Tracker CDN mirrors, magnet parse fullscreen page, LAN discovery
- 🐛 Fixed: Subtitle settings/track sync, P2P false completion, empty input crash, Android Release crash

### v1.0.3
- ✨ New: Avatar upload and cropping feature
- ✨ New: All-platform image cropping feature
- ✨ New: Config management system (local + subscription source mode)
- ✨ New: URL import config
- ✨ New: Global scaling support (80%-120%)
- ✨ New: Explore page UI optimization
- ✨ New: Collection page sorting (random sort + transparency)
- ✨ New: Resource list (type tags + size + auto-open)
- ✨ New: Magnet/ED2K link detection and filtering
- ✨ New: Fullscreen background (glass overlay + blur effect)
- ✨ New: Image compression settings
- ✨ New: Collection category save
- ✨ New: Cache separation (app/browser)
- ✨ New: Windows custom cache directory
- ✨ New: Tab auto-scroll
- ✨ New: External app selector (universal)
- 🎨 Improved: Design token system, code splitting (13 components)
- 🎨 Improved: RegExp cache, icon unification
- 🎨 Improved: List interaction, image loading performance
- 🐛 Fixed: Background image file leak
- 🐛 Fixed: 32-bit Base32 magnet links
- 🐛 Fixed: ED2K links cannot open
- 🐛 Fixed: Magnet link detection and double-click open
- 🐛 Fixed: Pagination/transparency/zoom slider issues
- 🐛 Fixed: Collection category filter and backup path issues
- 🐛 Fixed: SQL syntax error
- 🐛 Fixed: Installer 64-bit architecture

### v1.0.2
- ✨ New: Add Baidu Netdisk, Quark Netdisk magnet download integration [Requested by 小黑盒-疯狂大马猴zd]
- ✨ New: Add user-defined display scaling feature [Requested by QQ-氨基酸奶]
- 🎨 Improved: Mobile browser URL input interaction experience
- 🎨 Improved: Backup management dialog uses dynamic theme color instead of hardcoded blue
- 🎨 Improved: Settings page refresh logic, fix scroll position reset issue
- ⚡ Improved: Optimize backup loading performance, quickly skip non-matching backup files
- 🐛 Fixed: Fix Windows title bar buttons invisible issue
- 📊 New: Add Umeng analytics feature (optional, requires user consent)
- 🔒 New: Add privacy policy confirmation dialog
- 🔧 Adjusted: Disable default Google Analytics

### v1.0.1
- 🎨 Improved: Collection page filter UI beautification and add download status filter
- 🎨 Improved: Optimize PC collection page layout and add window size save feature
- 🎨 Improved: Optimize update check mechanism, add manual check frequency limit
- 🎨 Improved: Remove display quantity limit for backup details and diff comparison dialogs
- 🐛 Fixed: Fix ED2K link share format issue
- 🐛 Fixed: Fix merge import logic and optimize code structure

### v1.0.0
- 🎉 First release
- ✨ Support magnet/ED2K link collection management
- 📂 Support category management
- 💾 Support data backup and restore
- 📡 Support LAN transfer
- 🌍 Support multi-language (Chinese/English)

---

<div align="center">

**If this software helps you, please give a ⭐ Star to support!**

Made with ❤️ by 咕噜咕噜大法师

</div>
