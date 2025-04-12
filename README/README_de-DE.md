[中文](../README.md) | [English](README_en-US.md) | [繁體中文](README_zh-TW.md) | [Русский](README_ru-RU.md) | [日本語](README_ja-JP.md) | [한국어](README_ko-KR.md) | [Deutsch](README_de-DE.md) | [Français](README_fr-FR.md)

# Anytype Schwebendes Inhaltsverzeichnis

## Projekt Hintergrund
Seit 2022 fordern Anytype-Community-Nutzer die Hinzufügung einer schwebenden Inhaltsverzeichnis-Funktion. Leider ist diese Funktion bis April 2025 noch nicht in den offiziellen Entwicklungsplan aufgenommen worden. Interessanterweise zeigt auch Notion, einer der Hauptwettbewerber von Anytype, wenig Enthusiasmus bei der Implementierung dieser Funktion.

## Lösung
Dieses Projekt implementiert ein schlankes und elegantes schwebendes Inhaltsverzeichnis für Anytype mittels benutzerdefiniertem CSS. Diese Lösung stimmt mit dem Ansatz des Community-Nutzers [@sandroid](https://community.anytype.io/t/custom-table-of-contents-custom-css/27360/8) überein.

Im Designprozess haben wir uns von der schwebenden Inhaltsverzeichnis-Struktur von sspai.com inspirieren lassen. Trotz der Einschränkung, dass Anytype nur benutzerdefiniertes CSS ohne JS unterstützt, ist das Endergebnis dennoch beeindruckend.

## Demo
![Schwebendes Inhaltsverzeichnis Demo](../image/IMG_20250411_234639.gif)

## Funktionen
- Schlankes und elegantes Layout des schwebenden Inhaltsverzeichnisses
- Inhaltsverzeichnis folgt dem Seiten-Scroll für einfache Navigation
- Hover-Effekte für Inhaltsverzeichnis-Einträge

## Verwendung
1. Öffnen Sie Anytype und navigieren Sie zu `Datei -> Öffnen -> Benutzerdefiniertes CSS`
2. Kopieren Sie den Inhalt von `custom.css` oder `custom.min.css` in die `Benutzerdefiniertes CSS`-Datei
3. Starten Sie Anytype neu, um die Änderungen zu übernehmen

## Hinweise
- Für benutzerdefinierte Styling-Anpassungen können Sie die Parameter in `custom.css` ändern

## Stilbeschreibung
- Ebene 1 Überschrift: Keine Einrückung
- Ebene 2 Überschrift: Einrückung um eine Zeichenbreite
- Ebene 3 Überschrift: Einrückung um zwei Zeichenbreiten
- Alle Überschriften behalten linksbündige Aufzählungspunkte bei 