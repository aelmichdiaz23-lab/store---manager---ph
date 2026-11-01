# Store Manager Organizer

Simple PWA starter para sa sari-sari store. May paninda/stock, benta, gastos, utang/notes, at backup/restore. Ang records ay nasa local browser storage ng device.

## Files
- `index.html` — app
- `manifest.json` — PWA metadata
- `sw.js` — basic offline cache

## Android / GitHub Pages setup
1. I-extract ang ZIP.
2. Sa GitHub repository, i-upload ang **tatlong file** (`index.html`, `manifest.json`, `sw.js`) sa root folder.
3. Commit changes.
4. Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.
5. Hintayin ang Pages URL. Buksan sa Chrome sa Android. Menu ⋮ → Add to Home screen / Install app.
6. Buksan minsan habang may internet para ma-cache ang app. Pagkatapos, subukan offline.

Important: Ang offline records ay hindi naka-sync sa ibang device. Mag-download ng backup sa Backup tab. Ito ay starter organizer, hindi pa accounting/tax system.
