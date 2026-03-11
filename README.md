# Otti
Linux für noobs

# Otti

Statische Profil- und Portfolio-Website.

Das Repository enthält eine einfache Website zur Darstellung eines technischen Profils sowie verschiedener Themenbereiche und Projekte.
Die Seite ist vollständig statisch aufgebaut und benötigt keine Build-Tools oder externe Abhängigkeiten.

---

# Seite starten / öffnen

## Variante 1 – Direkt im Browser öffnen

1. Repository herunterladen oder klonen

```bash
git clone https://github.com/CowboyTMK/Otti.git
```

2. In den Projektordner wechseln

```bash
cd Otti/profil
```

3. Datei `index.html` im Browser öffnen

```text
profil/index.html
```

Die Seite funktioniert lokal ohne Server, da sie nur aus statischen HTML-Dateien besteht.

---

## Variante 2 – Lokalen Webserver verwenden (empfohlen)

Ein lokaler Server verhindert Probleme mit relativen Pfaden.

### Python

```bash
cd Otti/profil
python -m http.server 8000
```

Danach im Browser öffnen:

```text
http://localhost:8000
```

---

# Projektübersicht

**Otti** ist eine statische Portfolio-Seite.
Sie dient zur strukturierten Darstellung von:

* Profilinformationen
* technischen Fähigkeiten
* Projekten
* Interessensgebieten
* praktischen Erfahrungen

Die Startseite fungiert als zentrale Übersicht.
Weitere Seiten beschreiben einzelne Themenbereiche detaillierter.

---

# Technisches Format

Die Website basiert vollständig auf statischen Webtechnologien.

## Verwendete Technologien

* **HTML** – Struktur der Website
* **CSS** – Layout und Gestaltung
* **Browser Rendering** – Ausführung ohne zusätzliche Software

Es werden **keine Frameworks**, **keine Build-Tools** und **keine Datenbanken** verwendet.

---

## HTML-Struktur

Die Seiten sind klassische HTML-Dokumente.

Typischer Aufbau:

```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Seitentitel</title>
</head>

<body>

    Inhalt der Seite

</body>
</html>
```

Die Navigation zwischen den Seiten erfolgt über interne Links.

Beispiel:

```
<a href="portfolio/3d-druck.html">3D Druck</a>
```

---

# Projektstruktur

```
Otti
│
├── README.md
│
└── profil
    │
    ├── index.html
    │
    └── portfolio
        ├── 3d-druck.html
        ├── heimnetzwerk.html
        ├── home-assistant.html
        ├── motorrad.html
        ├── produktionsumfeld.html
        ├── systemintegration.html
        └── technische-praxis.html
```

---

# Seitenstruktur

## Startseite

`profil/index.html`

Funktion:

* zentrale Übersicht
* Einstiegspunkt der Website
* Navigation zu Portfolio-Bereichen

---

## Portfolio-Seiten

Ordner:

```
profil/portfolio/
```

Diese Seiten beschreiben einzelne Themenbereiche.

Beispiele:

| Seite             | Inhalt                              |
| ----------------- | ----------------------------------- |
| 3D Druck          | Projekte und technische Anwendungen |
| Heimnetzwerk      | Netzwerkstruktur und Infrastruktur  |
| Home Assistant    | Smart-Home Systeme                  |
| Systemintegration | technische Integration              |
| Technische Praxis | praktische technische Erfahrung     |
| Produktionsumfeld | Arbeitsumgebungen                   |
| Motorrad          | persönlicher technischer Bereich    |

---

# Navigation der Website

Typischer Ablauf beim Besuch der Seite:

```
Startseite
   ↓
Themenübersicht
   ↓
Portfolio-Seiten
   ↓
Detailinformationen zu einzelnen Bereichen
```

Der Besucher beginnt auf der **Startseite** und gelangt von dort zu den verschiedenen Themenbereichen.

---

# Erweiterungsmöglichkeiten

Das Projekt ist bewusst minimal gehalten und kann erweitert werden.

Mögliche Erweiterungen:

* zentrales CSS-Stylesheet
* responsive Layout für mobile Geräte
* Bilder und Projektdokumentationen
* JavaScript-Interaktionen
* Kontaktformular
* GitHub Pages Deployment
* Navigationselemente zwischen allen Seiten

---

# Veröffentlichung

Die Website kann direkt über **GitHub Pages** veröffentlicht werden.

Vorgehen:

1. Repository öffnen
2. Einstellungen → Pages
3. Branch `main` auswählen
4. Ordner `profil` als Root definieren

Danach wird die Seite automatisch veröffentlicht.

---

# Verlauf

## Version 1.0

Erste Struktur der Website.

Enthält:

* Startseite
* mehrere Portfolio-Seiten
* statische HTML-Struktur
* einfache interne Navigation

Ziel:
Grundlage für eine persönliche Portfolio-Website.

---

# Lizenz

Dieses Projekt dient als persönliches Portfolio.
Nutzung oder Anpassung für eigene Projekte möglich.
