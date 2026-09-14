# Benjamin Gangol — Portfolio

Persönliche Portfolio-Website für Bewerbungen in der Softwareentwicklung.

## Aufbau

- `dist/index.html`: Inhalte und Seitenstruktur
- `dist/style.css`: Gestaltung und responsive Layouts

Die Website verwendet HTML und CSS ohne Build-Schritt. Schriftarten werden über Google Fonts geladen; lokale Ersatzschriften sind definiert.

## Lokal ansehen

Im Projektverzeichnis starten:

```sh
python3 -m http.server 5173 --directory dist
```

Anschließend `http://localhost:5173` im Browser öffnen.

## Cloudflare Pages mit GitHub

Ein neues Pages-Projekt anlegen, GitHub verbinden und dieses Repository auswählen.

| Einstellung | Wert |
| --- | --- |
| Produktionsbranch | `main` |
| Framework | None |
| Build-Befehl | `exit 0` |
| Build-Ausgabeverzeichnis | `dist` |

Änderungen an `main` können damit automatisch veröffentlicht werden.

## Inhaltlicher Stand

Profil, Fähigkeiten, Werdegang und E-Mail-Kontakt sind vorhanden. Die drei Projektkarten enthalten noch Platzhalter und müssen vor Verwendung in Bewerbungen ergänzt werden.
