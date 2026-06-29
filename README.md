# SunesMad 🏠

> Danish pantry & food inventory tracker (PWA)

PWA til lagerstyring af madvarer og spisekammer, bygget som én HTML-fil med Google Sheets som backend.

## Funktioner

- Overblik over varer fordelt på lokationer (reol, skab, soveværelse m.fl.)
- Tilføj, juster og fjern antal
- Aldersfarver baseret på alder (grøn → gul → orange → rød)
- Fungerer offline som PWA (installerbar på mobil)
- PIN-beskyttet redigering

## Teknisk

- Én enkelt `index.html` — ingen build-trin, ingen framework
- Google Apps Script som API-lag mod Google Sheets
- `localStorage` som midlertidig cache

## Links

- **App:** https://sunezapa.github.io/sunes-mad/
- **Backend:** Google Sheets (SunesMadApp)

## Brug

Appen er personlig og kræver egen Google Sheet + Apps Script deployment.

## Sprog

Appen er på dansk og beregnet til dansk/nordisk brug.
