# Gedanken-Check PWA

## Mit GitHub Pages veröffentlichen
1. Auf GitHub ein neues Repository anlegen, z. B. `gedanken-check`.
2. Den kompletten Inhalt dieses Ordners hochladen.
3. Repository → Settings → Pages.
4. Source: `Deploy from a branch`.
5. Branch: `main`, Ordner: `/ (root)` → Save.
6. Die danach angezeigte GitHub-Pages-URL in Safari öffnen.
7. iPhone: Teilen → `Zum Home-Bildschirm` → `Als Web-App öffnen` → Hinzufügen.

## Speicherung
Die Einträge liegen ausschließlich im lokalen Browser-Speicher (`localStorage`) auf dem jeweiligen Gerät.
Sie werden nicht an GitHub übertragen. Unter `Meine Einträge` gibt es Export und Import für Backups.

## Offline
Nach dem ersten erfolgreichen Laden wird die App per Service Worker zwischengespeichert und kann anschließend offline geöffnet werden.
