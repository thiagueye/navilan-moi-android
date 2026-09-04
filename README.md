# நவிலன் மொய் மென்பொருள் – Android WebView App

This project wraps the Blogger application at https://navilanmoisoftware.blogspot.com/ in an Android WebView.

Features:
- Uses the live Blogger application and its existing login/cloud data.
- JavaScript + DOM storage enabled.
- Overrides window.print() inside the WebView and routes receipts to AndroidThermal.printText().
- Bluetooth paired thermal-printer selection.
- ESC/POS raster printing for 58mm and 80mm printers.
- Android 12+ Bluetooth permissions.
- GitHub Actions workflow builds app-debug.apk without Android Studio.

The uploaded Blogger XML already contains the AndroidThermal print bridge call and 58/80mm thermal-width handling.
