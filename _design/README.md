# Design-Quellen Hochzeit Daniela & Emanuel

Stand: 29.10.2026. Grafiker-Paket zur Save-the-Date-Karte, aufbereitet für Website und weitere Drucksachen.

## Ordner
| Pfad | Inhalt |
|---|---|
| `assets/css/tokens.css` | Farben, @font-face, Typo-Muster als CSS-Variablen |
| `assets/fonts/` | woff2-Subsets (Latin inkl. Umlaute, ß, €, „“): Pinyon Script 400, Jost 300/400/400 italic/500 |
| `assets/img/` | Illustrationen als SVG (farbkorrigiert, auf Inhalt beschnitten) |
| `_design/` | Originale: Druck-PDF, Elemente-PDF, alle TTFs, Vorschau-PNGs der Karte |

## Farben (Grafiker, verbindlich)
| Rolle | HEX | CMYK | Kontrast auf Creme |
|---|---|---|---|
| Creme | #F6E9D7 | 4/9/18/0 | – |
| Beere | #8F3B67 | 42/84/29/18 | 5.9:1 |
| Rosé | #B5586A | 23/73/40/12 | 3.8:1 |
| Rosé 50 % | #B5586A @ 50 % | – | 1.9:1 (Deko) |
| Rauchblau | #4F6A80 | 71/48/33/18 | 4.7:1 |
| Text dunkel | #2A1E24 | 69/73/55/76 | 13.4:1 |

Grün (Eukalyptus) kommt nur in den Illustrationen vor.

## SVGs
| Datei | Inhalt |
|---|---|
| `blumenecke-oben-links.svg` | Florale Ecke, Stiele oben links (Karte: Ecke oben links) |
| `blumenecke-unten-rechts.svg` | Florale Ecke, Stiele unten rechts |
| `namenszug-daniela-emanuel.svg` | Daniela / Ringe / Emanuel |
| `wir-heiraten.svg` | Script-Schriftzug |
| `ringe-rose.svg`, `ringe-rose-50.svg` | Ringe mit Diamant, 100 % und 50 % |
| `qr-code-website.svg` | QR → https://danielaundemanuel.zeilinger.pro (geprüft) |

Umwandlung: Elemente-PDF ist CMYK. Farben über FOGRA39 → sRGB konvertiert, Palettenfarben exakt auf die HEX-Werte des Grafikers gesetzt, dann mit svgo optimiert. Die Blumenecken haben je ca. 350 KB.

## Schriften
Pinyon Script (Sorkin Type) und Jost (indestructible type*) stehen beide unter der SIL Open Font License 1.1. Selbst-Hosting auf der Website ist erlaubt.

## Karte (Druck-PDF)
113 × 156 mm = A6 + 4 mm Beschnitt, 2 Seiten, QR ca. 33 mm.
Vorderseite: SAVE THE DATE · Daniela & Emanuel · 11. September 2027 · Kienbauerhof, Aichkirchen bei Wels
Rückseite: Wir heiraten! · Bitte haltet euch diesen Tag für uns frei. · QR · Alle weiteren Infos findet ihr auf unserer Website.
