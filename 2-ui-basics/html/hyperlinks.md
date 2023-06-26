# HYPERLINKS & ANCHOR TAG

## 1. Link zu einer anderen Website

So kannst du einen Link zu einer anderen Website herstellen:

### 1.1 Beispiel in einem Paragraphen:

```html
<p>Go to <a href="https://www.google.com">Hier geht's zu Google</a></p>
```

Nutze den **<a></a>** Tag, definiere im Attribut **href** das Ziel des Links, also die Website in diesem Fall und schreibe einen Text zwischen die beiden Tags, der per Klick zum Ziel führt!

### 1.2 Link zu einer anderen Website (in einem Paragraphen) in neuem Tab:

```html
<p>
  Go to
  <a href="https://www.google.com" target="_blank">Hier geht's zu Google</a>
</p>
```

Ergänze zum obrigen beispiel noch das **target** Attribut und setze es auf **"\_blank"**!

### 1.3 Tipp und Ergänzung: Das **rel** Attribut

```html
<p>
  Go to
  <a href="https://www.google.com" target="_blank" rel="noopener noreferrer"
    >Hier geht's zu Google</a
  >
</p>
```

Ergänze stets das **rel** Attribut mit den Werten **"noopener noreferrer"** um eine sichere und datenschutzfreundliche Umgebung für den Benutzer zu schaffen!

## 2. E-Mail per Link versenden

```html
<p>
  Send me an
  <a href="mailto:beispiel@icloud.com ?subject=Betreff">E-Mail</a>
</p>
```

Um per Klick auf einen Link eine E-Mail zu verfassen, nutze den **<a></a>** Tag. Definiere im **href** Attribut die E-Mail-Adresse des Empfängers und ggf. mit **?subject=Betreff** den Betreff.
