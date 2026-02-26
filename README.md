# 🍷 Deutscher Wein E-Commerce Monitor 2026

**Öffentliche Marktanalyse — 12 deutsche Online-Weinhändler im Vergleich**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Update: Wöchentlich](https://img.shields.io/badge/Update-W%C3%B6chentlich-green.svg)]()
[![Accessibility: WCAG AA](https://img.shields.io/badge/Accessibility-WCAG%20AA-blue.svg)]()

---

## 📊 Was ist das?

Ein interaktives Dashboard, das die wichtigsten deutschen Online-Weinhändler vergleicht — Sortiment, Preise, Versandkosten, Bewertungen und Features. Die Daten werden wöchentlich automatisch aktualisiert.

### Erfasste Händler

| Händler | Segment | Weine |
|---------|---------|-------|
| Hawesko | Premium Mass Market | 8.500 |
| VINELLO | Marktplatz | 18.800 |
| WirWinzer | Winzer-Marktplatz | 53.588 |
| Vicampo | Marktplatz | 15.159 |
| Lobenberg | Premium / Sammler | 10.072 |
| weine.de | Wert / Deutsch-Fokus | 3.500 |
| Weinquelle | Traditionell / Spezialist | 812 |
| Weinfreunde | Massenmarkt / REWE | 1.000 |
| Silkes Weinkeller | Premium Kuratiert | 1.600 |
| Ludwig von Kapff | Premium Heritage | 1.896 |
| Jacques' Wein-Depot | Omnichannel | 550 |
| Belvini / Cheers2you | Marken-Shop | 80 |

## 🔍 Dashboard-Sektionen

1. **Marktübersicht** — KPIs auf einen Blick
2. **Sortimentsvergleich** — Anzahl Weine pro Händler (linear/logarithmisch)
3. **Versandkosten** — Versand und Freiversandgrenzen
4. **Preisspanne** — Minimum- bis Maximum-Preise
5. **Feature-Matrix** — Bio, Abo, Sommelier, App, Miles & More
6. **Bewertungen** — Ratings aller Händler
7. **Marktpositionierung** — Scatter-Plot (Sortiment × Versand × Bewertung)
8. **Shop-Profile** — Detailkarten aller Händler
9. **Methodik** — Datenerhebung und Quellen

## ♿ Barrierefreiheit

Dieses Dashboard wurde unter Berücksichtigung der WCAG AA Richtlinien entwickelt:

- Kontrastwerte ≥ 4.5:1 (Normaltext) / ≥ 3:1 (großer Text)
- Alle Diagramme haben eine alternative Tabellenansicht
- Vollständige Tastaturnavigation
- ARIA-Labels auf allen interaktiven Elementen
- Schriftgrößen-Umschalter (A- / A / A+)
- Hoher-Kontrast-Modus
- `prefers-reduced-motion` wird respektiert
- Farbe wird nie als einziges Unterscheidungsmerkmal verwendet

## 🛠 Technologie

- **Frontend**: Vanilla HTML/CSS/JS
- **Charts**: [Chart.js](https://www.chartjs.org/) v4
- **Fonts**: [Fraunces](https://fonts.google.com/specimen/Fraunces) + [Source Sans 3](https://fonts.google.com/specimen/Source+Sans+3)
- **Hosting**: GitHub Pages / statisches Hosting
- **Datenerhebung**: Automatisiert (wöchentlich)

## 📁 Projektstruktur

```
├── index.html          # Dashboard (Single-Page-App)
├── data/
│   └── history/        # Wöchentliche Snapshots (YYYY-MM-DD.json)
├── README.md
└── LICENSE
```

## 🔄 Daten aktualisieren

Die Daten befinden sich direkt im `<script id="market-data">` Block in `index.html`. Um zu aktualisieren:

1. Neue Daten im gleichen JSON-Format erheben
2. Den `lastUpdated` Wert anpassen
3. Commit & Push — das Dashboard aktualisiert sich automatisch

## 📄 Lizenz

MIT License — siehe [LICENSE](LICENSE)

## 🤝 Beitragen

Pull Requests sind willkommen! Insbesondere:
- Neue Händler hinzufügen
- Datenaktualisierungen
- Barrierefreiheits-Verbesserungen
- Übersetzungen

---

*Erstellt mit ❤️ für den deutschen Weinmarkt*
