# Farben in CSS

In diesem Beispiel wollen wir auf verschiedenen Wegen die Schriftfarbe einer h1 definieren.

## 1. Mit Name der Farbe

Definiere den Wert von "color" über den (englischen) Namen der Farbe.
Beispiel:

```css
h1 {
  color: red;
}
```

## 2. Mit Hexadezimalcode der Farbe

Farben können ebenfalls mit einem 6-stelligen Farbcode definiert werden.
Weiß hat beispielsweise den Farbcode FFFFFF
Schreibe vor den Hexadezimalcode einen Hashtag #!
Beispiel:

```css
h1 {
  color: #ffffff;
}
```

## 3. Mit RGB

Du kannst deine Farbe auch manuell mit Hilfe von RGB definieren.
Schreibst du beispielsweise den Namen einer Farbe, so wird links daneben ein kleines Quadrat in deiner Farbe angezeigt.
Klicke darauf und suche dir per Hand deine Farbe aus.
Die Syntax der RGB-Farben wird durch einen Code dargestellt, welcher aus drei Zahlen besteht.
Beispiel:

```css
h1 {
  color: rgb(122, 65, 65);
}
```

## 4. Mit HSL

HSL-Farben lassen sich vorhersagen: H-Werte (Hue, Farbton) zwischen 0 und 30 liefern Rot, ab 30 wird's Orange, bis 60 Gelb. Grün reicht von 60 bis etwa 150, dann folgt Blau bis 270 und das Schlusslicht bei hohen Werte für H bilden die violetten und purpurnen Töne.

Größere Werte für Lightness hellen den Farbton auf, intensive reinere Farben entstehen bei einer hohen Sättigung.

Der HSL-Farbwähler macht die Kombination von Farben – z.B. für eine Farbpalette – einfach. Grundfarbe aussuchen, mit dem Lightness-Slider die Helligkeit regeln und drei oder mehr Farben gleicher Sättigung und Helligkeit bilden eine harmonische Palette.

[(Quelle und weitere Infos)](https://www.mediaevent.de/css/farbrechner.html#:~:text=HSL%2DFarben%20lassen%20sich%20vorhersagen,die%20violetten%20und%20purpurnen%20T%C3%B6ne.)

[Hier findest du eine gute HSL Dokumentation](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/hsl)

## 5. Tipp: Woher weiß ich, welchen Hex- oder RGB-Code meine Farbe hat?

Hier findest du zwei Links, welche euch bei eurer Farbauswahl helfen:

[Farb-Tabelle: Eine Übersicht](https://www.farb-tabelle.de/de/farbtabelle.htm)

[Dokumentation von w3schools](https://www.w3schools.com/colors/colors_palettes.asp)

[Coolors: Erstellt dir zufällige zusammenpassende Farbschemen mit den entsprechenden Codes](https://coolors.co/)
