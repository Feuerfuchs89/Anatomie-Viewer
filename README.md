# Anatomie-Viewer

Interaktiver 3D-Atlas der menschlichen Anatomie im Browser: Schichten, Suche (deutsch, lateinisch, englisch), Befundmarker, Bewegungen und PDF-Export. Läuft als einzelne HTML-Datei, ohne Server und ohne Anmeldung.

## Veröffentlichen mit GitHub Pages
1. Repository anlegen und alle Dateien hochladen (`index.html` im Hauptverzeichnis).
2. Settings → Pages → Branch `main`, Ordner `/ (root)` → Save.
3. Settings → General → Social preview: `social-preview-1280x640.png` hochladen.

## Offline und ohne Drittanbieter (optional)
Diese Dateien einfach neben `index.html` hochladen:
- `jspdf.umd.min.js` (jsPDF 2.5.1): sonst lädt die App die PDF-Bibliothek beim PDF-Export von cdnjs.
- `Manrope-latin.woff2` und `SourceSans3-latin.woff2`: sonst nutzt die App Systemschriften.

## Bedienung per Tastatur
Fokus auf das Modell, dann Pfeiltasten drehen, `+` und `-` zoomen, Umschalt plus Pfeiltasten verschiebt.

## Lizenz und Quellen
- Programm: © 2026 Michael Assmann.
- 3D-Modell: [Z-Anatomy](https://github.com/Z-Anatomy/Models-of-human-anatomy), CC BY-SA 4.0, basierend auf BodyParts3D (CC BY-SA 2.1 JP). Bearbeitet von Michael Assmann (vereinfacht, komprimiert). Das bearbeitete Modell steht unter [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.de).
- Einzelne Z-Anatomy-Teile (Innenohr, Niere) stehen unter Nicht-kommerziell-Lizenzen.
- three.js (MIT), jsPDF (MIT), Manrope und Source Sans 3 (SIL OFL).

## Hinweis
Nur zur Veranschaulichung. Kein Medizinprodukt, keine Diagnose, kein Ersatz für ärztliche oder therapeutische Beratung.

## Kontakt
Michael Assmann, Hans-Driesch-Straße 45, 04179 Leipzig, Knotenpunktmassagen@googlemail.com
