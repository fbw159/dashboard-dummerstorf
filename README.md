# Abwärmeverteilung Rechenzentrum Dummerstorf – Dashboard

Interaktives Browser-Dashboard zur Ausbreitung der Abwärme des geplanten Rechenzentrums Dummerstorf in Luft und Boden (Karte, Zeitleiste, alle Modellparameter). Begleitet das Manuskript „Abwärme RZ Dummerstorf“ (Universität Rostock, LTT, mit Rostock Dynamics).

**Stand:** Fassung 15, 2. Oktober 2026 (Physikkern unverändert seit 25.09.2026).

## Dateien

| Datei | Inhalt |
|---|---|
| `index.html` | Dashboard inkl. Physikkern und eingebetteter Wetterdaten |
| `maplibre-gl.js` / `maplibre-gl.css` | Kartenbibliothek MapLibre GL JS 4.7.1, unverändert aus dem npm-Paket (BSD-3-Clause) |

Alle drei Dateien müssen im selben Ordner liegen.

## Starten

`index.html` direkt im Browser öffnen oder lokal ausliefern, z. B.:

```bash
python -m http.server 8000
# dann http://localhost:8000 öffnen
```

Kartenkacheln (OpenFreeMap) und Schriften werden online nachgeladen.

## Lizenz

Noch offen.
