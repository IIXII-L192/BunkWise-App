# BunkWise v2.1.9-26 Release Notes

Welcome to **BunkWise v2.1.9-26** (Build 32)! 📱🚀✨

This release resolves initialization crashes in JavaScript to ensure data loads cleanly on launch.

---

## 🚀 What's New

### 1. Fixed JavaScript Runtime Crash at Startup 🛠️
* Removed a residual `fab.addEventListener` reference in `app.js` that was throwing a `ReferenceError` on launch.
* This successfully fixes the initialization crash, restoring all launcher dashboard tiles, calendars, timetable listings, and subject data cards to full functionality immediately on launch.

---

## 🛠️ Under-the-Hood Updates

### 1. Version Update 📦
* Updated `versionName` to `"2.1.9-26"`.
* Updated `versionCode` to `32`.
