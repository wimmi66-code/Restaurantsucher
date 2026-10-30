# Restaurantsucher Hamm – Handy-App (PWA)

Die App zeigt, welche Restaurants in Hamm und Umgebung gerade geöffnet haben, sortiert nach Küche, mit beliebtestem Gericht, Preisklasse und Reservierungsmöglichkeit.

- **Reiter 1 – Suche mit Claude:** Zeitpunkt, Küche, Ort, Preis und Extras wählen. Die App setzt Datum und Uhrzeit automatisch in den Auftrag ein. Auftrag kopieren, „Claude öffnen“ antippen, Websuche einschalten, einfügen.
- **Reiter 2 – Schnell in Google Maps:** Ein Tipp öffnet die passende Suche. Dort den Filter „Jetzt geöffnet“ wählen.

## Veröffentlichen auf GitHub Pages

1. github.com → **+** → **New repository** → Name `Restaurantsucher` → **Public** → **Create repository**
2. **uploading an existing file** → Inhalt dieses Ordners einschließlich `icons` hineinziehen → **Commit changes**
3. **More** → **Settings** → **Pages** → Branch **main**, **/ (root)** → **Save**
4. Nach 1–3 Minuten: `https://wimmi66-code.github.io/Restaurantsucher/`

## Installieren

iPhone: Link in Safari → **Teilen** → **Zum Home-Bildschirm**. Android: Chrome → **App installieren**.

## Aktualisieren

Dateien erneut hochladen und in `sw.js` die Version hochzählen (`restaurantsucher-v2` …).
