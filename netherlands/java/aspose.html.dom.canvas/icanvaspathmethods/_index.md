---
title: "ICanvasPathMethods Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.canvas.ICanvasPathMethods interface. De ICanvasPathMethods interface wordt gebruikt om paden van objecten te manipuleren."
type: docs

url: /nl/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

De **ICanvasPathMethods**-interface wordt gebruikt om paden van objecten te manipuleren.

```java
public interface ICanvasPathMethods
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Voegt een boog toe aan het pad die gecentreerd is op positie (x, y) met straal r, beginnend bij startAngle en eindigend bij endAngle, bewegend in de opgegeven richting tegen de klok in (standaard met de klok mee). |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Voegt een boog toe aan het pad die gecentreerd is op positie (x, y) met straal r, beginnend bij startAngle en eindigend bij endAngle, bewegend in de opgegeven richting tegen de klok in (standaard met de klok mee). |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Voegt een boog toe aan het pad met de gegeven controlepunten en straal, verbonden met het vorige punt door een rechte lijn. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Voegt een kubieke Bézier-curve toe aan het pad. Het vereist drie punten. De eerste twee punten zijn controlepunten en het derde punt is het eindpunt. Het startpunt is het laatste punt in het huidige pad, dat kan worden gewijzigd met moveTo() voordat de Bézier-curve wordt gemaakt. |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Laat het punt van de pen terugkeren naar het begin van het huidige subpad. Het probeert een rechte lijn te tekenen van het huidige punt naar het begin. Als de vorm al gesloten is of slechts één punt heeft, doet deze functie niets. |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Voegt een ellips toe aan het pad die gecentreerd is op positie (x, y) met de stralen radiusX en radiusY, beginnend bij startAngle en eindigend bij endAngle, bewegend in de opgegeven richting tegen de klok in (standaard met de klok mee). |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Voegt een ellips toe aan het pad die gecentreerd is op positie (x, y) met de stralen radiusX en radiusY, beginnend bij startAngle en eindigend bij endAngle, bewegend in de opgegeven richting tegen de klok in (standaard met de klok mee). |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Verbindt het laatste punt in het subpad met de x, y-coördinaten via een rechte lijn. |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Verplaatst het startpunt van een nieuw subpad naar de (x, y)-coördinaten. |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Voegt een kwadratische Bézier-curve toe aan het huidige pad. |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Creëert een pad voor een rechthoek op positie (x, y) met een grootte die wordt bepaald door breedte en hoogte. |

### Zie ook

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
