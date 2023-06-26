# CSS Selektoren

## 1. Tag/Type/Element Selector

Hierbei wird das Element direkt angesprochen. WICHTIG: Es sind ALLE Elemente dieser Art betroffen!

Beispiel:

```css
h2 {
  color: blue;
}

p {
  color: aqua;
}
```

## 2. ID Selector

Eine ID betrifft GENAU EIN einziges Element und ist daher einzigartig und einmalig zu verwenden.

In der HTML Datei wird das entsprechende Element wie in folgendem Beispiel angesprochen:

```html
<p id="meine-id">Ich bin ein Paragraph</p>
```

Die in der HTML Datei definierte ID wird mit einem **#** in der CSS Datei angesprochen:

```css
#meine-id {
  color: red;
}
```

## 3. Class Selector

Sollte man weder ALLE Elemente, noch EIN EINZIGES Element stylen wollen, so arbeitet man mit dem Class Selector. Klassen können beliebig häufig verwendet werden.

Diese werden so in der HTML Datei definiert:

```html
<h2 class="meine-class">Ich bin ein Paragraph</h2>
```

Die in der HTML Datei definierte Klasse wird mit einem **.** in der CSS Datei angesprochen:

```css
.meine-class {
  color: blue;
}
```

## 4. Universal Selector

Um ALLE Elemente anzusprechen, verwendet man den universal selector mit Hilfe von:

```css
* {
  font-size: 30px;
}
```

## 5. List Selector / Grouping Selector

Um mehrere Elemente gleichzeitig anzusprechen, führe alle entsprechenden Elemente mit einem **,** auf:

```css
h1,
h2,
p {
  font-size: 30px;
}
```

## 6. Descendant Selector

Beispiel:

```css
div p {
  color: green;
}
```

Bedeutet: ALLE Paragraphen, die Kinder IRGENDEINER div sind, werden angesprochen (und erhalten die Schriftfarbe grün).

## 7. Child Selector

Beispiel:

```css
div > p {
  color: green;
}
```

Hier werden NUR DIREKTE Kinder angesprochen (und erhalten die Schriftfarbe grün).
Dies wird durch das **>** Zeichen dargestellt.

## 8. Adjacent Sibling Selector

Beispiel:

```css
h5 + p {
  color: yellowgreen;
}
```

Nur DER DIREKTE Paragraph nach h5 wird angesprochen (und erhält die Schriftfarbe gelbgrün).
Dies wird durch das **+** Zeichen dargestellt.
