# 📋 Changelog — Yadavar (یادآور)

All notable changes to Yadavar are documented in this file.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) conventions.

---

## [2.3.0] — July 2026 *(Current Release)*

### 🎉 Highlights
This is the biggest release yet — bringing cloud backup, cross-platform support, and a polished user experience to both iOS and Android.

### ✨ Added
- **Google Drive Backup & Restore** — Securely back up your entire calendar to your private Google Drive app folder with a single tap
  - Uses the restricted `drive.appdata` scope — Yadavar can only access its own hidden folder
  - User-initiated backup; no automatic sync
- **Encrypted Backups** — Optional AES-256-GCM encryption for all backup files
  - Encryption key derived from your chosen passphrase
  - Passphrase is never stored or transmitted — only you can decrypt your data
- **iOS App Store Release** — Yadavar is now available on the Apple App Store for iPhone and iPad
- **macOS Support** — Yadavar now runs natively on macOS (Apple Silicon and Intel)
- **Persian Holiday Auto-Import** — Automatically fetches and displays Iranian national and religious holidays
  - Anonymous API requests with no personal data
  - Cached locally for offline access
- **Local Notification Reminders** — Set reminders for any event; delivered on-device without any server
- **Multi-Platform Architecture** — Unified codebase supporting iOS, Android, and macOS

### 🔧 Improved
- Complete UI redesign with Persian-optimized typography and layout
- Significantly improved Jalali date conversion accuracy
- Faster app launch and calendar rendering performance
- Enhanced dark mode with better contrast ratios
- Accessibility improvements (Dynamic Type, VoiceOver/TalkBack support)

### 🐛 Fixed
- Corrected edge-case Jalali calendar conversion errors near year boundaries
- Fixed reminder notifications not firing after device restart on Android
- Resolved Google OAuth token refresh issues on long-duration sessions

---

## [2.1.3] — *(Previous Android Release)*

### ✨ Added
- Initial Google Drive backup integration (basic, unencrypted)
- Persian holiday display from remote API
- Event search functionality
- Recurring event support (daily, weekly, monthly, yearly)

### 🔧 Improved
- Improved notification reliability on Android 12+
- Better RTL (right-to-left) layout support throughout the App
- Reduced battery consumption from background processes

### 🐛 Fixed
- Fixed crash on Android when creating events with very long notes
- Corrected display of some Persian month names in edge locales
- Fixed notification badge counts on app icon

---

## [1.0.0] — *(Initial Release)*

### 🎉 First Release

- 📅 **Core Persian (Jalali/Shamsi) Calendar** — full month/year navigation
- ✏️ **Event Management** — create, edit, and delete events with titles and notes
- 🔔 **Basic Reminders** — set a notification time for any event
- 🌙 **Dark Mode** — light and dark theme support
- 📴 **Fully Offline** — no internet required for core functionality
- 🇮🇷 **Persian Locale** — complete Persian language interface

---

## Version Support

| Version | Platform | Status |
|---------|----------|--------|
| 2.3.0 | iOS, Android, macOS | ✅ Current |
| 2.1.3 | Android | ⚠️ Legacy — upgrade recommended |
| 1.0.0 | Android | ❌ End of Life |

---

*For support or questions, see [SUPPORT.md](./SUPPORT.md) or email [shahabahreini@hotmail.com](mailto:shahabahreini@hotmail.com).*
