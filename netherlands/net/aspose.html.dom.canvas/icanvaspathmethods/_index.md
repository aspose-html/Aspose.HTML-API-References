---
title: Interface ICanvasPathMethods
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods koppel. De ICanvasPathMethodsinterface wordt gebruikt om paden van objecten te manipuleren.
type: docs
weight: 240
url: /nl/net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

De ICanvasPathMethods-interface wordt gebruikt om paden van objecten te manipuleren.

```csharp
public interface ICanvasPathMethods
```

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Voegt een boog toe aan het pad dat gecentreerd is op (x, y) positie met straal r beginnend bij startAngle en eindigend bij endAngle, in de gegeven richting tegen de klok in (standaard met de klok mee). |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Voegt een boog toe aan het pad dat gecentreerd is op (x, y) positie met straal r beginnend bij startAngle en eindigend bij endAngle, in de gegeven richting tegen de klok in (standaard met de klok mee). |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Voegt een boog toe aan het pad met de gegeven controlepunten en straal, verbonden met het vorige punt door een rechte lijn. |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Voegt een kubieke Bézier-curve toe aan het pad. Hiervoor zijn drie punten nodig. De eerste twee punten zijn controlepunten en het derde is het eindpunt. Het startpunt is het laatste punt in het huidige pad, , dat kan worden gewijzigd met moveTo() voordat de Bézier-curve wordt gemaakt. |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Zorgt ervoor dat de punt van de pen teruggaat naar het begin van het huidige subpad. Het probeert een rechte lijn te trekken van het huidige punt naar het beginpunt. Als de vorm al gesloten is of slechts één punt heeft, doet deze functie niets. |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Voegt een ellips toe aan het pad dat is gecentreerd op (x, y) positie met de stralen radiusX en radiusY beginnend bij startAngle en eindigend bij endAngle in de gegeven richting tegen de klok in (standaard met de klok mee). |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Voegt een ellips toe aan het pad dat is gecentreerd op (x, y) positie met de stralen radiusX en radiusY beginnend bij startAngle en eindigend bij endAngle in de gegeven richting tegen de klok in (standaard met de klok mee). |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Verbindt het laatste punt in het subpad met de x-, y-coördinaten met een rechte lijn. |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Verplaatst het startpunt van een nieuw subpad naar de (x, y) coördinaten. |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Voegt een kwadratische Bézier-kromme toe aan het huidige pad. |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Creëert een pad voor een rechthoek op positie (x, y) met een grootte die wordt bepaald door breedte en hoogte. |

### Zie ook

* naamruimte [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* montage [Aspose.HTML](../../)


