---
title: "Path2D Class"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.canvas.Path2D class. De Path2D-interface van de Canvas 2D API wordt gebruikt om paden te declareren die later worden gebruikt op CanvasRenderingContext2D-objecten. De padmethoden van de CanvasRenderingContext2D-interface zijn ook aanwezig op deze interface en stellen je in staat om paden te maken die je kunt behouden en indien nodig op een canvas kunt afspelen."
type: docs

url: /nl/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

De **Path2D**-interface van de **Canvas 2D API** wordt gebruikt om paden te declareren die later worden gebruikt op **CanvasRenderingContext2D**-objecten. De padmethoden van de **CanvasRenderingContext2D**-interface zijn ook op deze interface aanwezig en stellen je in staat om paden te maken die je kunt behouden en opnieuw kunt afspelen wanneer dat nodig is op een canvas.

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Path2D](path2d/#constructor)() | geeft een nieuw aangemaakt Path2D-object terug |
| [Path2D](path2d/#constructor_1)(Path2D) | geeft een nieuw aangemaakt Path2D-object terug met een ander pad als argument (maakt een kopie) |
| [Path2D](path2d/#constructor_2)(String) | geeft een nieuw aangemaakt Path2D-object terug met een string die SVG-padgegevens bevat. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Voegt aan het pad het pad toe dat door het argument wordt gegeven. |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Voegt aan het pad het pad toe dat door het argument wordt gegeven. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Voegt een boog toe aan het pad die gecentreerd is op positie (x, y) met straal r, beginnend bij startAngle en eindigend bij endAngle, bewegend in de opgegeven richting tegen de klok in (standaard met de klok mee). |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Voegt een boog toe aan het pad die gecentreerd is op positie (x, y) met straal r, beginnend bij startAngle en eindigend bij endAngle, bewegend in de opgegeven richting tegen de klok in (standaard met de klok mee). |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Voegt een boog toe aan het pad met de gegeven controlepunten en straal, verbonden met het vorige punt door een rechte lijn. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Voegt een kubieke Bézier-curve toe aan het pad. Het vereist drie punten. De eerste twee punten zijn controlepunten en het derde punt is het eindpunt. Het startpunt is het laatste punt in het huidige pad, dat kan worden gewijzigd met moveTo() voordat de Bézier-curve wordt gemaakt. |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | Laat het punt van de pen terugkeren naar het begin van het huidige subpad. Het probeert een rechte lijn te tekenen van het huidige punt naar het begin. Als de vorm al gesloten is of slechts één punt heeft, doet deze functie niets. |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | Verwijdert het object. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Voegt een ellips toe aan het pad die gecentreerd is op positie (x, y) met de stralen radiusX en radiusY, beginnend bij startAngle en eindigend bij endAngle, bewegend in de opgegeven richting tegen de klok in (standaard met de klok mee). |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Voegt een ellips toe aan het pad die gecentreerd is op positie (x, y) met de stralen radiusX en radiusY, beginnend bij startAngle en eindigend bij endAngle, bewegend in de opgegeven richting tegen de klok in (standaard met de klok mee). |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | Verbindt het laatste punt in het subpad met de x, y-coördinaten via een rechte lijn. |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | Verplaatst het startpunt van een nieuw subpad naar de (x, y)-coördinaten. |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Voegt een kwadratische Bézier-curve toe aan het huidige pad. |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Creëert een pad voor een rechthoek op positie (x, y) met een grootte die wordt bepaald door breedte en hoogte. |

### Zie ook

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
