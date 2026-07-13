# BunkWise v2.1.8-26 Release Notes

Welcome to **BunkWise v2.1.8-26** (Build 31)! 📱🛠️🎉

This release resolves WebView load restrictions on high API/target SDK devices.

---

## 🚀 What's New

### 1. Reverted Restrictive WebView Access Policies 🔒
* Removed deprecated and restrictive local file URL access settings (`allowFileAccessFromFileURLs` and `allowUniversalAccessFromFileURLs`) from `MainActivity.kt`.
* This completely restores support for local resource loading on strict Android 16/15 target SDK platforms, resolving the black screen issue and ensuring all application screens, buttons, and graphics render normally.

---

## 🛠️ Under-the-Hood Updates

### 1. Version Update 📦
* Updated `versionName` to `"2.1.8-26"`.
* Updated `versionCode` to `31`.
