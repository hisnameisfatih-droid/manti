# MANTI BERLIN – One Page (Vercel-ready)

Schlichte, appetitanregende One‑Page für ein Manti‑Restaurant in Berlin.

## Quick Deploy (Vercel)

1. Dieses Repo/Zip in ein eigenes Git‑Repo legen oder direkt in Vercel importieren.
2. **Projekt erstellen** → Framework: *Other* (reines HTML).
3. Build‑Command: *(leer lassen)* • Output: `/` (Root).
4. Deploy.

> Optional: Domain verbinden und `robots.txt`/`og:image` sowie Kontaktdaten anpassen.

## Anpassen

- **E‑Mail/Telefon/Adresse:** In `index.html` nach `hello@mantiberlin.de`, `+49 30 000000`, „Kreuzberg“ suchen und ersetzen.
- **Öffnungszeiten & Preise:** In der Speisekarte/Footersektion updaten.
- **Bilder:** Aktuell sind Unsplash‑URLs hinterlegt. Eigene Fotos können durch lokale Dateien ersetzt werden und in `index.html` referenziert werden.
- **SEO:** `<title>`, `<meta name="description">`, Open Graph (`og:*`) und JSON‑LD (`Restaurant`) in `index.html` pflegen.

## Struktur

```
.
├─ index.html        # komplette One-Pager Seite
├─ vercel.json       # Header/Caching (optional)
├─ robots.txt
└─ README.md
```

## Lizenz
Nur als Vorlage gedacht. Bitte Markenrechte/Assets beachten.
