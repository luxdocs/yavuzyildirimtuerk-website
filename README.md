# Yavuz Yıldırımtürk – Yazılar Arşivi

Statische Website, kein Build-Schritt nötig. Alle Dateien werden lokal ausgeliefert – keine Verbindungen zu fremden Servern.

## Inhalt
- `index.html` – die Seite
- `support.js` – Laufzeit für die Seite
- `archiv.json` – alle Texte
- `assets/` – Bilder
- `fonts/` – Schriften
- `vendor/` – React (Laufzeitbibliothek, lokal, MIT-Lizenz)

## Schriften
Alle Schriften liegen bereits lokal im Ordner `fonts/` (keine Verbindung zu Google Fonts, DSGVO-freundlich): Literata, Instrument Sans, Covered By Your Grace und Loved by the King. Alle stehen unter der SIL Open Font License (Lizenztexte liegen bei) und dürfen frei verwendet werden.

## Veröffentlichen mit GitHub Pages
1. Alle Dateien dieses Ordners ins Repository hochladen (Struktur beibehalten).
2. Repository → Settings → Pages → Source: „Deploy from a branch“, Branch `main`, Ordner `/ (root)`.
3. Nach ca. 1 Minute ist die Seite unter `https://<benutzername>.github.io/<repo>/` erreichbar.

Hinweis: Lokal per Doppelklick geöffnet lädt `archiv.json` nicht (Browser-Sicherheit). Online oder über einen lokalen Server (`python3 -m http.server`) funktioniert alles.
