<div align="center">

# Magnetic Search Flutter

**Local Magnet/ED2K Link Collection Manager**

[![Flutter](https://img.shields.io/badge/Flutter-3.10.7+-02569B?style=flat-square&logo=flutter)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.0+-0175C2?style=flat-square&logo=dart)](https://dart.dev)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux%20%7C%20Android%20%7C%20iOS%20%7C%20Web-lightgrey?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.0-blue?style=flat-square)](https://github.com)

English | [简体中文](README.md)

<!-- Placeholder: App Logo/Screenshot -->
<!--
<img src="docs/images/logo.png" alt="Logo" width="200"/>
<img src="docs/images/screenshot_main.png" alt="Main Screenshot" width="600"/>
-->

</div>

---

## 📖 Overview

**Magnetic Search Flutter** is a cross-platform magnet link and ED2K link collection management tool. All data is stored locally, ensuring your privacy is protected.

### ✨ Key Features

- 🔍 **Multi-source Search** - Custom search sources for quick resource discovery
- 💾 **Local Storage** - All data stored locally, privacy guaranteed
- 📂 **Category Management** - Flexible category system with create, rename, delete, and hide options
- 🖼️ **Cover Management** - Support local upload and online search for cover images
- 🌐 **Built-in Browser** - WebView with automatic magnet/ED2K link detection
- 🎨 **Theme Customization** - Multiple preset themes with custom color support
- 🌍 **Multi-language** - Support for Chinese/English switching
- 📱 **Cross-platform** - Support for Windows, macOS, Linux, Android, iOS, Web
- 🔄 **Data Backup** - JSON format import/export with LAN transfer support
- 🔗 **Multi-link Support** - Single favorite can contain multiple magnet/ED2K links

---

## 📸 Screenshots

<!-- Placeholder: Feature Screenshots -->
<!--
### Main Interface
<img src="docs/images/screenshot_home.png" alt="Main Interface" width="800"/>

### Search Feature
<img src="docs/images/screenshot_search.png" alt="Search Interface" width="800"/>

### Favorites Management
<img src="docs/images/screenshot_favorites.png" alt="Favorites Management" width="800"/>

### WebView Browsing
<img src="docs/images/screenshot_webview.png" alt="WebView Browsing" width="800"/>

### Settings Page
<img src="docs/images/screenshot_settings.png" alt="Settings Page" width="800"/>

### Theme Customization
<img src="docs/images/screenshot_themes.png" alt="Theme Customization" width="800"/>
-->

> 📌 **Note**: Place screenshots in `docs/images/` directory and uncomment above

---

## 🚀 Getting Started

### Requirements

- Flutter SDK >= 3.10.7
- Dart SDK >= 3.0

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/magnetic_search_flutter.git

# Navigate to project directory
cd magnetic_search_flutter

# Install dependencies
flutter pub get

# Run the app
flutter run
```

### Platform-specific Configuration

<details>
<summary>🪟 Windows</summary>

```bash
flutter run -d windows
```

</details>

<details>
<summary>🍎 macOS</summary>

```bash
flutter run -d macos
```

</details>

<details>
<summary>🐧 Linux</summary>

```bash
flutter run -d linux
```

</details>

<details>
<summary>🤖 Android</summary>

```bash
flutter run -d android
```

</details>

<details>
<summary>📱 iOS</summary>

```bash
flutter run -d ios
```

</details>

---

## 📁 Project Structure

```
magnetic_search_flutter/
├── lib/
│   ├── main.dart                 # App entry point
│   ├── pages/                    # Pages
│   │   ├── search_page.dart      # Search page
│   │   ├── favorites_page.dart   # Favorites page
│   │   ├── settings_page.dart    # Settings page
│   │   └── webview_page.dart     # WebView page
│   ├── services/                 # Service layer
│   │   ├── database_service.dart # Database service
│   │   ├── storage_service.dart  # Storage service
│   │   ├── backup_manager_service.dart  # Backup manager
│   │   └── lan_transfer_service.dart    # LAN transfer
│   ├── models/                   # Data models
│   │   ├── magnet_favorite.dart  # Favorite model
│   │   ├── search_source.dart    # Search source
│   │   └── cover_source.dart     # Cover source
│   ├── widgets/                  # UI components
│   ├── theme/                    # Theme configuration
│   ├── styles/                   # Style system
│   └── l10n/                     # Internationalization
│       ├── app_zh.arb            # Chinese translations
│       └── app_en.arb            # English translations
├── assets/                       # Assets
│   ├── images/                   # Images
│   └── fonts/                    # Fonts
├── docs/                         # Documentation
├── android/                      # Android platform
├── ios/                          # iOS platform
├── windows/                      # Windows platform
├── macos/                        # macOS platform
├── linux/                        # Linux platform
└── web/                          # Web platform
```

---

## 🔧 Features

### 1. Search

<!-- Placeholder: Search feature screenshot -->
<!--
<img src="docs/images/feature_search.png" alt="Search Feature" width="600"/>
-->

- Multiple custom search sources
- Recent search history
- Quick access to frequently used websites
- One-click add to favorites

### 2. Favorites Management

<!-- Placeholder: Favorites management screenshot -->
<!--
<img src="docs/images/feature_favorites.png" alt="Favorites Management" width="600"/>
-->

- **Category Management**: Create, rename, delete, hide categories
- **Batch Operations**: Multi-select, batch delete, batch move, batch share
- **Sorting**: Manual sorting, by time, by name
- **Cover Management**: Local upload or online search
- **Status Marking**: Mark as downloaded

### 3. WebView Browsing

<!-- Placeholder: WebView screenshot -->
<!--
<img src="docs/images/feature_webview.png" alt="WebView Browsing" width="600"/>
-->

- Built-in browser, no need to switch apps
- Automatic detection of magnet and ED2K links
- Smart image detection for quick cover selection
- Ad blocking
- Tab management

### 4. Data Backup

<!-- Placeholder: Backup feature screenshot -->
<!--
<img src="docs/images/feature_backup.png" alt="Data Backup" width="600"/>
-->

- **JSON Format**: Standard JSON import/export
- **LAN Transfer**: Fast transfer between devices
- **Backup Management**: Rename, delete, mark as important
- **Diff Comparison**: Compare backup file differences

### 5. Theme Customization

<!-- Placeholder: Theme screenshot -->
<!--
<img src="docs/images/feature_themes.png" alt="Theme Customization" width="600"/>
-->

- Dark/Light mode switching
- Multiple preset themes
- Custom theme colors
- Follow system theme

### 6. Settings

<!-- Placeholder: Settings screenshot -->
<!--
<img src="docs/images/feature_settings.png" alt="Settings" width="600"/>
-->

- Search source configuration
- Cover source configuration
- Language switching (Chinese/English)
- Cache management
- Auto-update check

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Framework | Flutter 3.10.7+ |
| Language | Dart 3.0+ |
| Database | SQLite (sqflite) |
| Network | HTTP, WebView |
| Storage | SharedPreferences, Local Files |
| Animation | flutter_animate |
| i18n | intl, ARB |
| LAN Transfer | shelf, WebSocket |
| QR Code | qr_flutter, mobile_scanner |

---

## 📦 Main Dependencies

```yaml
dependencies:
  flutter_inappwebview: 6.2.0-beta-3  # WebView
  sqflite: ^2.3.0                      # Database
  shared_preferences: ^2.2.2           # Local storage
  flutter_animate: ^4.5.0              # Animation
  shelf: ^1.4.0                        # HTTP server
  qr_flutter: ^4.1.0                   # QR code generation
  mobile_scanner: ^3.5.0               # QR code scanning
  file_picker: ^8.0.3                  # File picker
  share_plus: ^7.2.1                   # Share functionality
  intl: ^0.20.2                        # Internationalization
```

---

## 🌍 Internationalization

| Language | Status |
|----------|--------|
| 简体中文 | ✅ Full Support |
| English | ✅ Full Support |

### Adding a New Language

1. Create `app_xx.arb` file in `lib/l10n/` directory
2. Copy content from `app_en.arb` and translate
3. Add language configuration in `l10n.yaml`
4. Run `flutter gen-l10n` to generate code

---

## 📝 Development Guide

### Code Standards

This project follows Flutter official code standards. See [docs/coding_standards.md](docs/coding_standards.md) for details.

### Commit Convention

```
feat: New feature
fix: Bug fix
docs: Documentation update
style: Code formatting
refactor: Refactoring
test: Testing
chore: Build/tools
```

### Branch Management

- `main` - Main branch, stable version
- `develop` - Development branch
- `feature/*` - Feature branches
- `hotfix/*` - Hotfix branches

---

## 🤝 Contributing

Issues and Pull Requests are welcome!

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'feat: Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Bilibili: 咕噜咕噜大法师**

<!-- Placeholder: Author avatar/links -->
<!--
<img src="docs/images/author_avatar.png" alt="Author Avatar" width="100"/>
-->

---

## 🙏 Acknowledgments

Thanks to these open source projects:

- [Flutter](https://flutter.dev)
- [flutter_inappwebview](https://github.com/pichillilorenzo/flutter_inappwebview)
- [sqflite](https://github.com/tekartik/sqflite)
- [flutter_animate](https://github.com/gskinnerTeam/flutter_animate)

---

## 📊 Project Status

<!-- Placeholder: Project badges -->
<!--
![GitHub stars](https://img.shields.io/github/stars/your-username/magnetic_search_flutter?style=social)
![GitHub forks](https://img.shields.io/github/forks/your-username/magnetic_search_flutter?style=social)
![GitHub issues](https://img.shields.io/github/issues/your-username/magnetic_search_flutter)
![GitHub license](https://img.shields.io/github/license/your-username/magnetic_search_flutter)
-->

---

<div align="center">

**If this project helps you, please give it a ⭐ Star!**

Made with ❤️ by 咕噜咕噜大法师

</div>
