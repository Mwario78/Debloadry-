# Android Debloater App

A lightweight Android application designed to **uninstall or disable system and user apps** on your device.

## Features
- Lists all installed apps (including system apps)
- Uninstalls apps using system permissions
- Integrates device admin for additional control
- Requires `QUERY_ALL_PACKAGES`, `REQUEST_DELETE_PACKAGES`, and device admin permissions

## Requirements
- Android 6.0+
- Internet access (for checking app details online)
- Grant necessary permissions manually if prompted

## Disclaimer
Use responsibly. Removing system apps may affect your device functionality.

---

**Package name:** `com.debloater`  
**Main Activity:** `MainActivity.java`  
**Device Admin:** Enabled via `DeviceAdminReceiver`
