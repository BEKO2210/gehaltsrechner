# 💰 Gehaltsrechner

**Live-Verdienst-Tracker für Deutschland**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-667eea?style=for-the-badge&logo=github)](https://BEKO2210.github.io/gehaltsrechner)
[![PWA](https://img.shields.io/badge/PWA-Installable-48bb78?style=for-the-badge)](https://BEKO2210.github.io/gehaltsrechner)
[![Mobile First](https://img.shields.io/badge/Mobile-First-ed8936?style=for-the-badge)](https://BEKO2210.github.io/gehaltsrechner)

Eine moderne, mobile-first Progressive Web App (PWA) zur Berechnung deines Brutto- und Netto-Gehalts in Echtzeit. Sieh auf einen Blick, wie viel du verdienst – und wie viel davon an den Staat geht.

---

## ✨ Features

### 🎯 Kernfunktionen
- **Live-Verdienst-Ticker** – Echtzeit-Anzeige deines Verdienstes seit Arbeitsbeginn
- **Brutto/Netto-Rechner** – Automatische Berechnung aller Abgaben
- **Stundensatz-Anzeige** – Was du wirklich pro Stunde verdienst
- **Steuerklassen I-VI** – Berücksichtigung deiner Steuerklasse
- **Zeitraum-Umschaltung** – Monats- oder Jahresgehalt

### 📊 Übersichten
- Pro Stunde
- Pro Tag (8h)
- Pro Woche
- Pro Monat
- Pro Jahr

### 🎨 Design
- **Mobile-First** – Optimiert für Smartphones
- **Dark Mode** – Modernes, augenschonendes Design
- **Gradient UI** – Ansprechende Farbverläufe
- **Smooth Animations** – Flüssige Übergänge

### 📱 PWA Features
- **Installierbar** – Als App auf deinem Homescreen
- **Offline-fähig** – Funktioniert ohne Internet
- **Service Worker** – Schnelle Ladezeiten

---

## 🚀 Schnellstart

### Online nutzen
```
https://BEKO2210.github.io/gehaltsrechner
```

### Als App installieren

**iOS (Safari):**
1. Öffne die Seite in Safari
2. Tippe auf "Teilen" (Share-Button)
3. Wähle "Zum Home-Bildschirm"
4. Fertig!

**Android (Chrome):**
1. Öffne die Seite in Chrome
2. Tippe auf das Menü (⋮)
3. Wähle "Zum Startbildschirm hinzufügen"
4. Fertig!

---

## 🛠️ Technologie-Stack

| Technologie | Verwendung |
|-------------|------------|
| HTML5 | Struktur & Semantik |
| CSS3 | Styling & Animationen |
| Vanilla JavaScript | Logik & Berechnungen |
| Service Worker | Offline-Funktionalität |
| Web App Manifest | PWA-Konfiguration |

---

## 📐 Berechnungsgrundlagen

### Abgaben-Sätze (vereinfacht)
- **Lohnsteuer:** ca. 20% (abhängig von Steuerklasse)
- **Sozialabgaben:** ca. 20%
  - Rentenversicherung: 9.3%
  - Krankenversicherung: 7.3%
  - Pflegeversicherung: 1.7%
  - Arbeitslosenversicherung: 1.2%

### Steuerklassen-Faktoren
| Klasse | Faktor | Beschreibung |
|--------|--------|--------------|
| I | 1.0 | Alleinstehend |
| II | 0.9 | Alleinerziehend |
| III | 0.8 | Verheiratet (höherer Verdienst) |
| IV | 1.0 | Verheiratet (gleicher Verdienst) |
| V | 1.2 | Verheiratet (niedrigerer Verdienst) |
| VI | 1.4 | Zweitjob |

**Hinweis:** Die Berechnungen sind vereinfacht und dienen als Orientierung. Für exakte Werte konsultiere einen Steuerberater oder das [Brutto-Netto-Rechner des Bundesfinanzministeriums](https://www.brutto-netto-rechner.info/).

---

## 🏗️ Projektstruktur

```
gehaltsrechner/
├── index.html          # Hauptanwendung
├── manifest.json       # PWA-Manifest
├── sw.js              # Service Worker
├── icons/             # App-Icons (verschiedene Größen)
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-192x192.png
│   ├── icon-384x384.png
│   └── icon-512x512.png
└── README.md          # Diese Datei
```

---

## 🎨 Design-System

### Farbpalette
```css
--primary: #667eea;      /* Hauptfarbe (Lila-Blau) */
--primary-dark: #5a67d8; /* Dunkles Lila */
--secondary: #f093fb;    /* Akzent (Pink) */
--success: #48bb78;      /* Erfolg (Grün) */
--danger: #f56565;       /* Gefahr/Abgaben (Rot) */
--warning: #ed8936;      /* Warnung (Orange) */
--bg: #0f172a;          /* Hintergrund (Dunkelblau) */
--card: #1e293b;        /* Karten-Hintergrund */
--text: #f8fafc;        /* Text (Hell) */
--text-muted: #94a3b8;  /* Gedämpfter Text */
--border: #334155;      /* Rahmen */
```

### Typografie
- **Font:** Inter (Google Fonts)
- **Überschriften:** 600-700 weight
- **Body:** 400 weight
- **Zahlen:** Tabular nums (monospace)

---

## 🔧 Lokale Entwicklung

### Repository klonen
```bash
git clone https://github.com/BEKO2210/gehaltsrechner.git
cd gehaltsrechner
```

### Lokaler Server
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve

# PHP
php -S localhost:8000
```

### Öffnen
```
http://localhost:8000
```

---

## 📱 Browser-Kompatibilität

| Browser | Unterstützung |
|---------|---------------|
| Chrome | ✅ Vollständig |
| Firefox | ✅ Vollständig |
| Safari | ✅ Vollständig |
| Edge | ✅ Vollständig |
| Opera | ✅ Vollständig |

---

## 🗺️ Roadmap

- [ ] Überstunden-Rechner
- [ ] Urlaubstage-Tracker
- [ ] Mehrere Länder (Österreich, Schweiz)
- [ ] Dark/Light Mode Toggle
- [ ] Gehaltsvergleich (Branchen)
- [ ] PDF-Export der Berechnungen
- [ ] Lokale Speicherung der Einstellungen

---

## 🤝 Mitwirken

Beiträge sind willkommen! So kannst du helfen:

1. Fork das Repository
2. Erstelle einen Feature-Branch (`git checkout -b feature/AmazingFeature`)
3. Committe deine Änderungen (`git commit -m 'Add some AmazingFeature'`)
4. Push zum Branch (`git push origin feature/AmazingFeature`)
5. Öffne einen Pull Request

---

## 📝 Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert – siehe [LICENSE](LICENSE) für Details.

---

## 👤 Autor

**Belkis Aslani**
- GitHub: [@BEKO2210](https://github.com/BEKO2210)
- LinkedIn: [Belkis Aslani](https://linkedin.com/in/belkis-aslani)
- Website: [HomeOfficeDeutschland.de](https://homeofficedeutschland.de)

---

## 🙏 Danksagung

- Design inspiriert von modernen Fintech-Apps
- Icons und UI-Elemente basierend auf best practices
- Farbschema inspiriert von Tailwind CSS

---

**Made with ❤️ in Freiberg am Neckar, Germany**

[![Stars](https://img.shields.io/github/stars/BEKO2210/gehaltsrechner?style=social)](https://github.com/BEKO2210/gehaltsrechner)
