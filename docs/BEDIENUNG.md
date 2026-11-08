# Luma – Android-Bildstudio

Installierbare, eigenständige Android-App mit deutscher Oberfläche und einem Ablauf wie bei mobilen Kreativ-Editoren: Erstellen → Foto öffnen → unten ein Werkzeug wählen → bearbeiten → oben exportieren.

## Funktionsumfang

- 153 auswählbare Looks einschließlich Original: 40 Luma, 17 Film-LUTs aus ImageToolbox, 39 übertragene PixelPerfect-Kurven, 24 QuickEdit-ACV-Looks, 23 PhotoEditor-MediaEffect-Presets, 10 kreative Effekte.
- Stufenlose Filterstärke; Helligkeit, Kontrast, Sättigung, Wärme, Vignette und Filmkorn.
- Filter kombinieren: im Filterbereich nach unten scrollen und „Look fixieren & weiteren kombinieren“ wählen. Text und Pinsel bleiben editierbar.
- Zuschnitt mit freier Auswahl und Formatvorlagen, Drehen um 90°, horizontales Spiegeln.
- Textebenen: verschieben, Größe, Drehung, Farbe, vier Schriftfamilien, fett/kursiv, mehrere Zeilen.
- 32 Emoji-Sticker, Pinsel mit Farbe und Größe, drei Rahmen.
- Text-/Sticker-Ebenenverwaltung, Rückgängig/Wiederholen (bis 16 Schritte, speicherabhängig).
- Automatischer lokaler Entwurf; benannte Projektkopien über Startseite → Projekte.
- PNG/JPG speichern und über Android teilen; wählbare Ausgabegröße und JPG-Qualität.
- System-Dateiauswahl ohne allgemeinen Zugriff auf die Fotobibliothek. EXIF-Ausrichtung wird beim Öffnen berücksichtigt.
- Offline: keine Netzwerkberechtigung, kein Login, kein Wasserzeichen.

## Installation

`Luma-1.0.1.apk` auf ein Android-Handy ab Android 9 kopieren und öffnen. Falls Android fragt, die Installation für die verwendete Dateien-App erlauben. Die APK benötigt keinen Zugriff auf das gesamte Fotoarchiv. Ein Foto wird gezielt über die Android-Dateiauswahl geöffnet.

## Verwendung

1. „Foto öffnen“ wählen oder das Beispielbild ausprobieren.
2. Filterkategorie wählen. Die horizontale Leiste zeigt Vorschaubilder; über „Alle 153 durchsuchen“ lässt sich der gesamte Katalog durchsuchen.
3. Mit „Stärke“ den Look dosieren; weitere Regler liegen unter „Anpassen“. Der Bereich ist vertikal scrollbar.
4. „Original“ gedrückt halten, um mit der aktuellen Bildbasis zu vergleichen. Nach dem Fixieren eines Looks ist dieser Teil der neuen Basis.
5. Bei „Schnitt“ die Ecken ziehen oder ein Format als Ausgangspunkt wählen. „Ausschnitt anwenden“ übernimmt die Auswahl. Beim Ziehen kann das Verhältnis wieder frei angepasst werden.
6. Unter „Text“ oder „Sticker“ eine Ebene hinzufügen. Im Bild antippen, um sie zu wählen; dann verschieben. Formatoptionen stehen darunter.
7. Unter „Pinsel“ direkt ins Bild zeichnen. ↶ und ↷ ändern den letzten Bearbeitungsschritt.
8. „Export“ öffnet Format, Auflösung und Qualität. „Speichern“ fragt nach dem Ziel, „Teilen“ öffnet das Android-Teilen-Menü.
9. Auf der Startseite unter „Projekte“ den letzten Entwurf öffnen oder das aktuelle Projekt als eigene Kopie speichern.

## Grenzen dieser Version

- Arbeitsbilder werden beim Import auf höchstens 2560 Pixel lange Kante skaliert; Export vergrößert sie nicht. Das begrenzt den Speicherverbrauch auf Handys.
- Integriert sind ausgewählte Bestandteile der verlinkten Projekte. Die vollständigen Anwendungen und ihre gesamten Funktionsumfänge werden nicht mitgeliefert.
- Die beiden PicsArt-Aktivierungs-Repositories liefern keinen Android-Editor-Quellcode und wurden nicht als Codebasis verwendet. Es handelt sich um keine modifizierte PicsArt-App.
- Keine KI-Generierung, automatisches Freistellen, PSD-/PSB-Bearbeitung, RAW-Entwicklung, Videobearbeitung oder Cloud-Synchronisation.
- Die Filterstapel werden durch Übernehmen des Looks in die Bildbasis gebildet. Einzeln editierbare Knoten pro Filter sind nicht vorhanden. Rückgängig ist innerhalb der Sitzung möglich.
- Projekte speichern Bildbasis, Filterzustand und Ebenen. Die Rückgängig-Historie wird beim erneuten Öffnen nicht wiederhergestellt.
- Texte, Sticker und Pinsel bleiben bei Zuschneiden/Drehen editierbar. Die ursprüngliche Bildbasis vor einem Zuschnitt ist über Rückgängig erreichbar, solange die Sitzung läuft.
- MediaEffect-Filter werden von Android/OpenGL gerendert. Geräte- und Grafiktreiber können sich in der Ausgabe leicht unterscheiden.
- UI-Sprache Deutsch; einige importierte Look-Namen bleiben Englisch.

## Lizenzhinweise

Die Lizenzhinweise stehen in [LIZENZEN.txt](LIZENZEN.txt) und in der App unter ⓘ.
