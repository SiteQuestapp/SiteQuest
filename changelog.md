## [1.0.9] - 2026-07-11

### Key Updates
- **Guest Mode** — Explore the app instantly without signing in. When you create an account later, everything you saved transfers over automatically.
- **Seamless Sign-Up** — Create an account with Google or Auth0 and your guest data (settings, saved items, and progress) comes along with you.

### Bug Fixes
- **Cleaner Guest Label** — Guest users now see a simple "Guest" name instead of a messy code.
- **Welcome Tour Fixed** — New guests now get the proper intro walkthrough on first launch.
- **Fewer False Errors** — Reduced unnecessary error messages that weren't actual problems.
---

## [1.0.8] - 2026-07-11

### 🐛 Fixes
- Fixed SiteQuest Pets heading wrapping to two lines on narrow viewports.
- Fixed milestone badge text overflowing its card container.
- Reduced line spacing in milestone card badge text for tighter layout.

---

## [1.0.7] - 2026-07-11

### 🚀 Updates
- Responsive text scaling for SiteQuest Pets header and milestone section on smaller screens.

---

## [1.0.6] - 2026-07-11

### 🐛 Fixes
- Fixed "unexpected shutdown" error appearing after auto-update or tray icon exit.
- Added data flush before forced app exit in renderer crash handler.
- Added data flush before auto-update restart to prevent pending data loss.
- Added data flush on Windows session end to prevent data loss during system shutdown.

---

## [1.0.5] - 2026-07-11

### 🚀 Features
- **Uninstall Feedback (Windows)**: Automatically opens a feedback form when users uninstall the app via Windows Settings.
- **Uninstall Feedback (Mac)**: LaunchAgent checks on login if the app was removed and opens a feedback form.
- Feedback URL includes user email, app version, and OS for context.
- Feedback URL only opens on real uninstalls, not during auto-updates.
---
## [1.0.4] - 2026-06-25
### 🐛 Fixes
- Fixed changelog fetch URL to point to the correct repository.
- Updated GitHub fallback link in changelog error view.

### ⚙️ Maintenance
- Prepared auto-updater with GitHub Releases for seamless updates.
- Updated build configuration and metadata.

---

## [1.0.3] - 2026-05-06
### 🚀 Updates
- Updated repository and homepage links.
- Initialized official release branch.
  
---

## [1.0.2] - 2026-05-06
### 🚀 Updates
- Ui and performance fixes
---
## [1.0.0] - 2026-04-20
### 🎉 Core Features
- **Multi-Site Productivity**: A seamless sidebar interface allowing you to pin and switch between your favorite web apps.

### 🛡️ Advanced Security
- **Secure Sandbox**: Native support for Chrome extensions and isolated web sessions for maximum privacy.
- **Security Auditing**: Real-time connection auditing and security popovers for every site you visit.
- **Privacy Controls**: Granular control over history, cache, and third-party tracking.

### 📈 Smart Performance
- **Resource Balancer**: Intelligent memory management that unloads inactive sites to maintain peak system performance.
- **Global Sync Engine**: Encrypted cloud synchronization for your sites, settings, and custom prompts.
- **Gamified Productivity**: Built-in Streak Service to track your daily progress and keep you engaged.

### 🌍 Global Accessibility
- **Deep i18n Integration**: Professionally translated into 18+ languages with a robust logic-hub architecture.
- **Interactive Onboarding**: A comprehensive guided tutorial to get you up to speed in seconds.
- **PDF & Local Files**: Drag-and-drop support for local PDFs and documents directly into the sidebar.
