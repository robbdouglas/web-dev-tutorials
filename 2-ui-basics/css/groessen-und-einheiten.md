# Größen und Einheiten in CSS

## Absolute Größen

Absolute Größen sind **unabhängig** von anderen Größen und daher einfach zu verwenden. Beachte allerdings, dass die Verwendung von absoluten Größen

### px

Ein **Pixel** ist ein **Bildpunkt** und bestimmt die Größe von Elementen. Je mehr Pixel, desto größer das Element.

### pt

Ein **Punkt** oder **Point** ist eine Maßeinheit, die hauptsächlich in der Druckindustrie verwendet wird, um die Größe von Schriftarten und anderen Druckelementen zu bestimmen. Je mehr Punkte, desto größer das Element.

### cm, in...

Klassische Maßeinheiten wie **Centimeter** oder **Inches** können ebenfalls beim Coden verwendet werden. 

---

## Relative Größen

Relative Größen werden i.d.R. verwendet, um deine Website **responsive** zu gestalten. 
Das bedeutet, dass sie auf unterschiedlich großen Screens so dargestellt werden kann, wie du es geplant hast, ohne Komplikationen wie beispielsweise **Verrutschen** der Elemente. Der Name **relative** Größen bedeutet, dass diese Einheiten von einer anderen Größe **abhängig** sind und nicht einzeln ohne Bezug verwendet werden dürfen.

### %

Die klassische relative Größe **Prozent** kann beim Coden verwendet werden, um eine prozentuale relative Größe im Vergleich zu der Größe eines anderen Elements zu definieren. Bei beispielsweise einer vorher definierten **font-size von 20px** würde **50%** eine neue **font-size von 10px** bedeuten.

### rem

Die relative Größe **rem** bedeutet **Root-Element** und ist von selbigem abhängig. 
Ist beispielsweise das Root-Element 10px groß, so würde **2rem=20px** bedeuten.

### em

Die relative Größe **em** funktioniert analog zu **rem**, bezieht sich jedoch auf das **Elternelement**.

### vh

Die relative Größe **vh** bedeutet **viewport height**. Viewport beschreibt dabei den sichtbaren Bereich des Browserfensters. **100 vh** würde also bedeuten, dass die vollständige Höhe des Browserfensters angesprochen wird.

### vw

Die relative Größe **vw** bedeutet **viewport width** und funktioniert analog zu **vh**, bezieht sich allerdings auf die Breite. Viewport beschreibt dabei ebenfalls den sichtbaren Bereich des Browserfensters.