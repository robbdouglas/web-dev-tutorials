# Pseudo Klassen und Elemente

## 1. Der Hover-Effekt:

Um Websites optisch ansprechender und dynamischer gestalten wollt, könnt ihr den "Hover-Effekt" verwenden.
Beispiel:

```css
h1 {
  background-color: black;
}

h1:hover {
  background-color: red;
}
```

Solltest du die Mouse über deiner h1-Überschrift halten, so ändert sich währenddessen die Hintergrundfarbe von schwarz zu rot.

Tipp: Den Hover-Effekt kannst du besonders gut bei Buttons oder deiner Navigationsleiste verwenden!

## 2. Die Farbe eines bereits besuchten Links ändern:

Um anzuzeigen, dass ein ein vorhandener Links bereits geklickt wurde, kann **"visited"** werden:

HTML:

```html
<a href=https://www.google.com>KLICK MICH</a>
```

CSS:

```css
a:visited {
  color: red;
}
```

In diesem Fall wird der Link "KLICK MICH" in roter Schriftfarbe angezeigt, nachdem er geklickt wurde.

## Farbe des Links während des Klickens ändern

Um während des Klickens einen Link hervorzuheben, lässt sich mit **"active"** die Farbe des Links verändern:

```css
a:active {
  color: yellow;
}
```
