---
title: Class Path2D
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Canvas.Path2D klas. De Path2Dinterface van de Canvas 2D API wordt gebruikt om paden te declareren die later worden gebruikt op CanvasRenderingContext2Dobjecten. De padmethoden van de CanvasRenderingContext2Dinterface zijn ook aanwezig op deze interface en stellen u in staat om paden te maken die u kunt behouden en naar behoefte opnieuw kunt afspelen op een canvas.
type: docs
weight: 290
url: /nl/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

De Path2D-interface van de Canvas 2D API wordt gebruikt om paden te declareren die later worden gebruikt op CanvasRenderingContext2D-objecten. De padmethoden van de CanvasRenderingContext2D-interface zijn ook aanwezig op deze interface en stellen u in staat om -paden te maken die u kunt behouden en naar behoefte opnieuw kunt afspelen op een canvas.

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Path2D](path2d/#constructor)() | retourneert een nieuw geïnstantieerd Path2D-object |
| [Path2D](path2d/#constructor_1)(Path2D) | retourneert een nieuw geïnstantieerd Path2D-object met een ander pad als argument (maakt een kopie) |
| [Path2D](path2d/#constructor_2)(string) | retourneert een nieuw geïnstantieerd Path2D-object met een tekenreeks bestaande uit SVG-padgegevens. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Voegt aan het pad het pad toe dat wordt gegeven door het argument. |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Voegt aan het pad het pad toe dat wordt gegeven door het argument. |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Voegt een boog toe aan het pad dat gecentreerd is op (x, y) positie met straal r beginnend bij startAngle en eindigend bij endAngle, in de gegeven richting tegen de klok in (standaard met de klok mee). |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Voegt een boog toe aan het pad dat gecentreerd is op (x, y) positie met straal r beginnend bij startAngle en eindigend bij endAngle, in de gegeven richting tegen de klok in (standaard met de klok mee). |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Voegt een boog toe aan het pad met de gegeven controlepunten en straal, verbonden met het vorige punt door een rechte lijn. |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Voegt een kubieke Bézier-curve toe aan het pad. Hiervoor zijn drie punten nodig. De eerste twee punten zijn controlepunten en het derde is het eindpunt. Het startpunt is het laatste punt in het huidige pad, , dat kan worden gewijzigd met moveTo() voordat de Bézier-curve wordt gemaakt. |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath/)() | Zorgt ervoor dat de punt van de pen teruggaat naar het begin van het huidige subpad. Het probeert een rechte lijn te trekken van het huidige punt naar het beginpunt. Als de vorm al gesloten is of slechts één punt heeft, doet deze functie niets. |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose/)() | Verwijdert object. |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Voegt een ellips toe aan het pad dat is gecentreerd op (x, y) positie met de stralen radiusX en radiusY beginnend bij startAngle en eindigend bij endAngle in de gegeven richting tegen de klok in (standaard met de klok mee). |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Voegt een ellips toe aan het pad dat is gecentreerd op (x, y) positie met de stralen radiusX en radiusY beginnend bij startAngle en eindigend bij endAngle in de gegeven richting tegen de klok in (standaard met de klok mee). |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto/)(double, double) | Verbindt het laatste punt in het subpad met de x-, y-coördinaten met een rechte lijn. |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto/)(double, double) | Verplaatst het startpunt van een nieuw subpad naar de (x, y) coördinaten. |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Voegt een kwadratische Bézier-kromme toe aan het huidige pad. |
| [Rect](../../aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Creëert een pad voor een rechthoek op positie (x, y) met een grootte die wordt bepaald door breedte en hoogte. |

### Zie ook

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* naamruimte [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* montage [Aspose.HTML](../../)


