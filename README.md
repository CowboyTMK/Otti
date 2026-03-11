Otti - Technisches Portfolio 🚀
Willkommen in meinem Portfolio-Repository. Hier dokumentiere ich meine Projekte, technischen Erfahrungen und Schwerpunkte aus den Bereichen IT-Infrastruktur und Handwerk.


## 🌐 Deployment & Erreichbarkeit

* **Live-Webseite (Aktuell):** [https://cowboytmk.github.io/Otti/](https://cowboytmk.github.io/Otti/)
* **Hinweis zur Struktur:** Die ursprüngliche Konfiguration über den Ordner `profil` wurde zugunsten einer sauberen Root-Struktur aufgelöst. Der Zugriff erfolgt nun direkt über das Hauptverzeichnis.

---

## 🌐 Seite lokal starten / öffnen

**Variante 1 – Direkt im Browser öffnen**

1. Repository herunterladen oder klonen:
```bash
git clone [https://github.com/CowboyTMK/Otti.git](https://github.com/CowboyTMK/Otti.git)



# 🌐 Seite starten / öffnen

## Variante 1 – Direkt im Browser öffnen

1. Repository herunterladen oder klonen

```bash
git clone https://github.com/CowboyTMK/Otti.git
```

2. In den Projektordner wechseln

```bash
cd Otti
```

3. Datei `index.html` im Browser öffnen

```text
index.html
```

Die Seite funktioniert lokal ohne Server, da sie nur aus statischen HTML-Dateien besteht.

---

## Variante 2 – Lokalen Webserver verwenden

Ein lokaler Server verhindert Probleme mit relativen Pfaden.

### Python

```bash
cd Otti
python -m http.server 8000
```

Danach im Browser öffnen:

```text
http://localhost:8000
```

---


---

🛠️ Themen & Schwerpunkte
Das Portfolio ist in verschiedene Fachbereiche unterteilt, die Einblicke in meine praktische Arbeit geben:

• Systemintegration: IT-Infrastrukturen und Vernetzung.

• Heimnetzwerk & Home-Assistant: Smart Home Automatisierung und sichere Netzwerkkonfiguration.

• 3D-Druck: Projekte, Prototyping und additive Fertigung.

• Technische Praxis & Motorrad: Dokumentationen zu mechanischen Arbeiten und Instandhaltung.

• Produktionsumfeld: IT-Lösungen und Prozesse im industriellen Kontext.

---

🏗️ Repository-Struktur
Nach der Optimierung der Verzeichnisstruktur sieht das Projekt nun wie folgt aus:

• `index.html` – Die zentrale Einstiegsseite (Landingpage).

• `portfolio/` – Verzeichnis mit den detaillierten Projektseiten (z. B. `3d-druck.html`, `systemintegration.html`).

• `README.md` – Diese Dokumentation.


---

📝 Technischer Änderungsverlauf

* **11.03.2026 - 19:42 Uhr | Dokumentations-Update:** Vollständige Aktualisierung der `README.md` auf die neue Verzeichnisstruktur inklusive detaillierter Projekthistorie.
* **11.03.2026 - 19:38 Uhr | Git-Infrastruktur Fixes:** Korrektur des Branch-Zustands (Detached HEAD), Auflösung von Merge-Konflikten bei unzusammenhängenden Historien und finale Synchronisation via Force-Push.
* **11.03.2026 - 19:35 Uhr | GitHub Pages Konfiguration:** Umstellung der Deployment-Quelle auf das Root-Verzeichnis, um die Erreichbarkeit unter der Haupt-URL sicherzustellen.
* **11.03.2026 - 19:25 Uhr | Struktur-Migration:** Verschiebung aller Dateien aus dem Verzeichnis `/profil` in das Root-Verzeichnis und Bereinigung der Alt-Ordner sowie Korrektur von Case-Sensitivity Fehlern.
* **11.03.2026 - 18:45 Uhr | Initialer Commit:** Erstellung der Grundstruktur der Portfolio-Webseite innerhalb des Unterverzeichnisses `/profil`.

---

📝 Ausführlicher Entwicklungsverlauf

Phase 1: Initialer Aufbau (Version 1.0)

• Konzept: Erstellung einer statischen Portfolio-Webseite auf Basis von HTML5.

• Struktur: Trennung der Inhalte in eine Startseite und themenspezifische Detailseiten im Unterordner `/profil/portfolio`.

• Inhalt: Dokumentation der Schwerpunkte 3D-Druck, Systemintegration und Smart Home.

Phase 2: Deployment-Optimierung (März 2026)

Im Zuge der Veröffentlichung auf GitHub Pages traten strukturelle Hindernisse auf, die eine grundlegende Umgestaltung der Verzeichnisstruktur erforderlich machten:

1. Struktur-Begradigung (Root-Level Migration):

  • Ursprünglich lagen alle relevanten Dateien im Unterordner `/profil`. Dies führte dazu, dass die Webseite nur über `.../profil/index.html` erreichbar war.

  • Lösung: Migration aller Dateien aus `/profil` direkt in das Hauptverzeichnis (Root). Der Ordner `profil` wurde vollständig entfernt.

2. Fehlerbehebung im Git-Workflow:

  • Während der Migration kam es zu einem "Detached HEAD" Zustand und Divergenzen zwischen dem lokalen Stand und GitHub.

  • Lösung: Zusammenführung der Historien mittels `git merge --allow-unrelated-histories` und Bereinigung durch `git push --force`.

3. Automatisierung:

  • Einrichtung der automatischen Bereitstellung via GitHub Pages.

Phase 3: Aktueller Status (Version 2.0)

• Die Webseite ist nun unter der primären Repository-URL direkt erreichbar.

• Die interne Verlinkung wurde auf das Root-Verzeichnis angepasst.

• Die Dokumentation wurde vollständig aktualisiert.

---

📜 Lizenz & Nutzung
Dieses Projekt dient als persönliches Portfolio zur Dokumentation meiner Fähigkeiten. Der Code ist frei einsehbar und kann als Inspiration für eigene Projekte genutzt werden.




