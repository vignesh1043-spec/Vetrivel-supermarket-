# Vetrivel Supermarket – Android Inventory App

Offline owner-only inventory starter project. Green/white theme, local SQLite database, product CRUD, stock IN/OUT, low-stock count, basic daily recorded sales total, ML Kit barcode scanning, CSV export.

## Build APK using an Android phone (GitHub Actions)
1. Sign in to GitHub in your phone browser and create a **public or private repository** named `VetrivelSupermarket`.
2. Upload the contents of this ZIP (not the ZIP itself) to the repository.
3. Open the repository's **Actions** tab and enable Actions if asked.
4. The workflow named **Build Android APK** runs automatically after upload.
5. Open the completed workflow run, scroll to **Artifacts**, and download `VetrivelSupermarket-debug-apk`.
6. Extract the downloaded artifact ZIP and install `app-debug.apk`. Android may ask you to allow installation from your browser/files app.

## Important
- This is a starter prototype, not a Play Store release. Debug APK is unsigned for store publishing.
- Data is stored only on this phone. Uninstalling the app or clearing its data can erase inventory. Export CSV backups regularly.
- CSV export is a product list backup; it does not currently restore data or export the full stock movement history.
- Barcode scanning requires camera permission. Standard retail EAN/UPC/QR formats are supported by ML Kit.
- Use the same APK on the same phone. Do not assume data synchronizes between devices.
- Test with sample products and confirm quantities/prices before using for real shop accounts.
