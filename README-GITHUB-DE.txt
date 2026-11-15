# Chess.com – GitHub Pages Paket

## Veröffentlichung auf GitHub Pages

1. Entpacke diese ZIP-Datei.
2. Lade **alle Dateien und Ordner aus dem ZIP-Inhalt** in das Stammverzeichnis deines GitHub-Repositories hoch.
3. Achte darauf, dass `index.html` direkt im Stammverzeichnis liegt (nicht in einem zusätzlichen Unterordner).
4. Öffne im Repository **Settings → Pages**.
5. Wähle **Deploy from a branch**, danach `main` und `/ (root)`, und speichere.
6. Öffne nach dem Deployment die angezeigte GitHub-Pages-Adresse.

## Als App auf dem Smartphone installieren

- **iPhone/iPad:** Seite in Safari öffnen → Teilen → „Zum Home-Bildschirm“ → Hinzufügen.
- **Android:** Seite in Chrome öffnen → Menü ⋮ → „App installieren“ oder „Zum Startbildschirm hinzufügen“.
- Das grüne Bauern-Logo aus deiner Vorlage ist als Browser-Favicon, Apple-Touch-Icon und PWA-App-Icon eingebunden.
- Für Installation und Offline-Cache muss die Seite über HTTPS aufgerufen werden, was GitHub Pages bereitstellt.

## Enthalten

- `index.html` – komplette interaktive Website
- `site.webmanifest` – App-Name, Startmodus und Icon-Varianten
- `sw.js` – Service Worker mit Offline-Cache
- `favicon.ico` und `assets/icons/` – Browser- und App-Icons
- `assets/brand/pawn-mark.png` – transparentes Logo für Website-Kopfzeile

Die Partie gegen Bots, Profilwerte und Einstellungen funktionieren lokal im Browser. Für echte Online-Spieler, geteilte Freundespartien und Live-Turniere ist ein separater Multiplayer-Server notwendig.
