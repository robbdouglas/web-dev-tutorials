# Wichtige HTML Elemente

## Überschriften und Text

Die wichtigste Überschrift (unbedingt nur einmal pro Website verwenden):
```html
<h1> und </h1>
```

Weitere Überschriften (h1 ist die größte, h6 die kleinste Überschrift):

```html
<h2> und </h2>
<h3> und </h3>
<h4> und </h4>
<h5> und </h5>
<h6> und </h6>
```

Paragraph (für gewöhnlichen Text):

```html
<p> und </p>
```

---

## Listen

Beginne eine Liste mit dem **ul** oder **ol** Tag und schließe sie mit dem analogen Closing-Tag: 

### Ungeordnete Liste (unordered list):

```html
<ul> und </ul>
```

### Geordnete Liste (ordered list):

```html
<ol> und </ol>
```

### Listenelemente (list element):

Jede geordnete und ungeordnete Liste enthält Listenelemente, also den Inhalt:

```html
<li> und </li>
```

Der HTML-Code für beispielsweise eine ungeordnete Liste sieht folgendermaßen aus:

```html
<ul>
    <li>Brot</li>
    <li>Butter</li>
    <li>Eier</li>
</ul>
```

Analog dazu eine geordnete Liste:

```html
<ol>
    <li>Einkaufen</li>
    <li>Putzen</li>
    <li>Trainieren</li>
</ol>
```

---

## Tabellen

Für Tabellen wird der **table** Tag verwendet. Hiermit beginnt/endet eine Tabelle:

```html
<table> und </table>
```

### Tabellenzeilen

Eine Tabelle wird Zeile für Zeile und darin Zelle für Zelle geschrieben. Jede Zeile beginnt und endet mit dem **tr** Tag:

```html
<tr> und </tr>
```

### Tabellenkopf (table head):

Zellen im Tabellenkopf werden mit dem **th** Tag geschrieben:

```html
<th> und </th>
```

### Tabellenzellen:

Alle anderen Zellen in einer Tabelle werden mit dem **td** Tag geschrieben:

```html
<td> und </td>
```

So würde z.B. der HTML-Code einer Tabelle aussehen:

```html
<table>
    <tr>
        <th>Name</th>
        <th>Alter</th>
        <th>Wohnort</th>
    </tr>
    <tr>
        <td>Julia</th>
        <td>29</td>
        <td>Gera</td>
    </tr>
    <tr>
        <td>Robert</th>
        <td>29</td>
        <td>Berlin</td>
    </tr>
    <tr>
        <td>Gerd</th>
        <td>82</td>
        <td>Gera</td>
    </tr>
</table>
```