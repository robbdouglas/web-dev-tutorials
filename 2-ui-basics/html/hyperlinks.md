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

Ergänze zum obrigen beispiel noch das **target** Attribut und setze es auf **"\_blank"**! Deine Zielwebsite öffnet sich im Browser nun in einem neuen Tab und nicht mehr im aktuellen Tab!

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

## 3. Zu einem bestimmten Punkt auf der Website (per Link) springen:

Definiere eine ID an der Stelle, zu der du springen möchtest.
Möchtest du z.B. nach ganz oben bzw. auf den Start der Website springen, schreibe:

```html
<body id="home"></body>
```

Wenn du nun beispielsweise am Ende deiner Website einen Link einbauen möchtest, der dich zum Beginn der Website bringt, schreibe:

```html
<p>Klicke <a href="#home">hier </a>um zur Startseite zu gelangen!</p>
```
