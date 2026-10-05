# MangaVerse v1.0.1 — Release Notes

## 🔧 Source Selection Fix

### 📚 All Sources Always Visible
Fixed the source picker so every content source is listed and selectable — no more hidden sources or settings gates:
* **All five sources shown**: The picker now always displays every registered source instead of locking non-default ones behind a toggle.
* **MangaRead by default**: Fresh installs start on MangaRead, the primary source.
* **First-use mature consent kept**: Non-MangaRead sources still ask for mature-content consent on first selection, then remember your choice.
* **Adult Mode toggle removed**: The confusing gate in Settings is gone — picking a source just works.

### 🛡️ Manifest Hardening
* Set `android:allowBackup="false"` to lock down app-data backup behavior.

### ⚙️ Release Automation
* New GitHub Actions workflow builds and publishes the release APK automatically on every version tag.

---

## 📦 Build Info

| Key | Value |
|-----|-------|
| Version | `1.0.1` |
| Build | `9` |
| APK size | ~68.5 MB |
| Min supported build | `1` |
| Released | `2026-10-05` |

---

## ⬇️ Download

Grab `MangaVerse.apk` below and sideload it on your device.
