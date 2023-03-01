---
title: Interface ICanvasPathMethods
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods gränssnitt. ICanvasPathMethodsgränssnittet används för att manipulera sökvägar för objekt.
type: docs
weight: 240
url: /sv/net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

ICanvasPathMethods-gränssnittet används för att manipulera sökvägar för objekt.

```csharp
public interface ICanvasPathMethods
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Lägger till en båge till banan som är centrerad vid (x, y) position med radie r som börjar vid startAngle och slutar vid endAngle går i den angivna riktningen moturs (standard till medurs). |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Lägger till en båge till banan som är centrerad vid (x, y) position med radie r som börjar vid startAngle och slutar vid endAngle går i den angivna riktningen moturs (standard till medurs). |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Lägger till en båge till banan med de givna kontrollpunkterna och radien, kopplad till föregående punkt med en rät linje. |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Lägger till en kubisk Bézier-kurva till sökvägen. Det krävs tre poäng. De två första punkterna är kontrollpunkter och den tredje är slutpunkten. Startpunkten är den sista punkten i den aktuella sökvägen, som kan ändras med moveTo() innan Bézier-kurvan skapas. |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Får pennans punkt att flytta tillbaka till början av den aktuella undersökvägen. Den försöker rita en rät linje från den aktuella punkten till början. Om formen redan har stängts eller bara har en punkt, gör den här funktionen ingenting. |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Lägger till en ellips till banan som är centrerad vid (x, y) position med radierna radiusX och radiusY som börjar vid startAngle och slutar vid endAngle går i den angivna riktningen med moturs (standard till medurs). |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Lägger till en ellips till banan som är centrerad vid (x, y) position med radierna radiusX och radiusY som börjar vid startAngle och slutar vid endAngle går i den angivna riktningen med moturs (standard till medurs). |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Kopplar den sista punkten i undersökvägen till x, y-koordinaterna med en rät linje. |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Flyttar startpunkten för en ny delväg till (x, y) koordinaterna. |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Lägger till en kvadratisk Bézier-kurva till den aktuella vägen. |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Skapar en bana för en rektangel vid position (x, y) med en storlek som bestäms av bredd och höjd. |

### Se även

* namnutrymme [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* hopsättning [Aspose.HTML](../../)


