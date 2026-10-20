# Pocket Vault

Offline, zero-knowledge password manager for iPhone, built as a single HTML page with a tiny service worker. Hosted on GitHub Pages and added to the home screen.

- AES-256-GCM, key from PBKDF2-SHA256 (600,000 iterations), WebCrypto only
- Vault stored encrypted in IndexedDB on the device; nothing is ever sent anywhere
- No data or secrets live in this repo, only app code

**Install:** open the Pages URL in Safari → Share → Add to Home Screen, then create the vault from the home-screen app (Safari and home-screen apps keep separate storage). Export an encrypted backup to iCloud Drive regularly.
