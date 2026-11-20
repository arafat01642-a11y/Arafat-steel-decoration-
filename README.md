# ARAFAT STEEL DECORATION — Starter App

This is an original bilingual (Bangla/English) offline-first app prototype.

## Included
- Accessories catalogue (admin-managed)
- Bangladeshi Pipe catalogue (admin-managed)
- Metal weight calculator (estimated formulas)
- Quotation / invoice builder with print-to-PDF
- CNC design catalogue (admin-managed image URLs)
- Admin panel for business details and catalogue management
- JSON backup and restore
- Bangla / English toggle
- Local device storage and service-worker offline cache

## Important notes
- This is a web-app/PWA starter, not a signed Android APK.
- Install it through a secure HTTPS host or a local Android WebView wrapper. Service-worker offline caching requires HTTPS or localhost.
- Data is stored in browser localStorage. Export backups regularly. Clearing browser/app data can erase it.
- Weight formulas are approximate and should be checked against your material supplier's specifications.
- The initial catalog is intentionally empty. Add only product images/data you own or are authorized to use.
- Before commercial use, add an app lock/admin authentication and test on target Android devices.

## Quick test
Open `index.html` in a browser. For full PWA installation/offline support, serve this folder from HTTPS.
