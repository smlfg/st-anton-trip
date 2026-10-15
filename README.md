# St. Anton Trip Page

Statische Seite zur Planung eines Ski-Wochenendes in St. Anton am Arlberg über Ostern 2026:
Zugverbindungen, Ablauf, Unterkunft, Skipass, Budget und Packliste auf einer Seite.

## Status

[![Deploy GitHub Pages](https://github.com/smlfg/st-anton-trip/actions/workflows/deploy.yml/badge.svg)](https://github.com/smlfg/st-anton-trip/actions/workflows/deploy.yml)

Live unter [smlfg.github.io/st-anton-trip](https://smlfg.github.io/st-anton-trip/). Die Reise
(3. bis 6. April 2026) ist vorbei; der letzte inhaltliche Stand der Seite ist vom 1. April 2026.

## Lokal ansehen

Die ganze Seite steckt in `index.html` (HTML, CSS und JavaScript in einer Datei).

```bash
git clone https://github.com/smlfg/st-anton-trip.git
cd st-anton-trip
python3 -m http.server 8000
```

Dann `http://localhost:8000` im Browser öffnen.

## Deployment

Jeder Push auf `main` startet `.github/workflows/deploy.yml`, das den Repo-Inhalt auf GitHub Pages
veröffentlicht. Der Workflow lässt sich auch von Hand starten (`workflow_dispatch`).

## Lizenz

MIT, siehe [LICENSE](LICENSE).
