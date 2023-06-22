# HTML Grundstruktur (Boilerplate)

Die klassische HTML Grundstruktur, auch **Boilerplate** genannt, sieht folgendermaßen aus:

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```

Diese kann in VSCode mit dem Shortcut 

```
! (mit Enter bestätigen) 
```

erzeugt werden. 

Die Grundstruktur besteht aus folgenden Kernelementen:

1. Das Dokument wird in der Sprache HTML gelesen bzw. interpretiert:
```html
<!DOCTYPE html>
```

2. Die Wurzel (root) eines HTML Dokuments - Hiermit beginnt und endet dieses:
```html
<html> und </html>
```

3. Im head sind Metadaten enthalten. Hier werden beispielsweise auch andere Dateien (z.B. CSS Dateien) verlinkt und mit dem Dokument verbunden. Elemente im head sind auf der Website nicht sichtbar (außer Titel im entsprechenden Tab des Browsers):
```html
<head> und </head>
```

4. Hier sind alle sichtbaren Elemente der Website enthalten:
```html
<body> und </body>
```