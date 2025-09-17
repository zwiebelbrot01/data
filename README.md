# Ronaldo vs Messi - Datenvisualisierung

Eine interaktive Datenvisualisierung, die die Tore von Cristiano Ronaldo und Lionel Messi vergleicht.

## 🎯 Features

- **Interaktive Visualisierung** der Tordaten beider Spieler
- **Verschiedene Ansichten:**
  - Body-Part: Tore nach Körperteil (Kopf, linker/rechter Fuß)
  - Results: Tore nach Spielergebnis (Sieg, Unentschieden, Niederlage)
  - Matchday: Tore nach Spieltag-Wichtigkeit
- **Halbzeit-Filter:** Erste Halbzeit, Zweite Halbzeit oder komplettes Spiel
- **Hover-Effekte** und detaillierte Informationen bei Klick
- **Responsive Design** mit modernem UI

## 🚀 Live Demo

[Zur Live-Anwendung auf Vercel](https://your-app-name.vercel.app)

## 🛠️ Technologien

- **HTML5** - Struktur der Anwendung
- **CSS3** - Styling und Animationen
- **JavaScript** - Interaktivität und Datenverarbeitung
- **jQuery** - DOM-Manipulation
- **gmynd.js** - Datengruppierung und -verarbeitung

## 📁 Projektstruktur

```
├── index.html          # Hauptseite
├── style.css           # Styling
├── main.js             # Hauptlogik
├── data.js             # Tordaten
├── jquery.min.js       # jQuery Bibliothek
├── gmynd.js            # Datenverarbeitungs-Bibliothek
├── vercel.json         # Vercel Konfiguration
├── *.woff2, *.otf      # Font-Dateien
└── README.md           # Diese Datei
```

## 🎮 Bedienung

1. **Hauptansichten wechseln:** Klicke auf "Body-Part", "Results" oder "Matchday"
2. **Halbzeit filtern:** Wähle "Whole game", "1st half" oder "2nd half"
3. **Tor-Details anzeigen:** Klicke auf einen beliebigen Kreis
4. **Hover-Effekte:** Fahre mit der Maus über die Kreise für eine Vergrößerung

## 🎨 Farbcodierung

- **Grün (#00CC6D):** Sieg
- **Rot (#BF211E):** Niederlage
- **Lila (#8846D2):** Unentschieden

## 📊 Datenquelle

Die Visualisierung basiert auf historischen Tordaten von Cristiano Ronaldo und Lionel Messi aus verschiedenen Saisons und Wettbewerben.

## 🚀 Deployment

### Lokale Entwicklung

1. Dateien in einen lokalen Webserver laden
2. `index.html` öffnen

### Vercel Deployment

1. Repository mit Vercel verbinden
2. Automatisches Deployment bei Git-Push

## 📝 Lizenz

Dieses Projekt dient zu Bildungszwecken und zur Datenvisualisierung.

---

Erstellt für die Analyse und Visualisierung von Fußballdaten 🏆
