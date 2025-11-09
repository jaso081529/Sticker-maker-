# HP67 Prompt2Sticker – Offline PWA

## Dateien
- `index.html` – komplette App (Prompt→Sticker, Export, A3-Bogen).
- `sw.js` – Service Worker (Offline-Cache).
- `manifest.json` – PWA Manifest.
- `icons/` – App-Icons (PNG 192/512).

## Deployment (GitHub Pages)
1. Neues Repository anlegen.
2. Diese vier Dateien + `icons/` in den Repo-Root laden.
3. In den Repo-Einstellungen: **Pages** → Source: `main` branch → root `/`.
4. Öffnen: `https://<USER>.github.io/<REPO>/`.
5. Browser fragt ggf. „Zum Home-Bildschirm hinzufügen“. Alternativ Button **Installieren** nutzen.

## Nutzung
- Prompt eingeben → **Generieren**.
- **PNG** exportiert mit 300 DPI pHYs Tag. **PDF (Druck)** öffnet Motiv-only Seite.
- **A3-Bogen**: Vorschau, PNG, oder Druckdialog.

## Hinweis
- Keine externen Dienste. 100 % offline.
- QR-Code ist nicht enthalten.
