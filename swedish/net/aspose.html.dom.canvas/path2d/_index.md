---
title: Class Path2D
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Canvas.Path2D klass. Path2Dgränssnittet för Canvas 2D API används för att deklarera sökvägar som sedan används på CanvasRenderingContext2Dobjekt. Banmetoderna för CanvasRenderingContext2Dgränssnittet finns också i det här gränssnittet och gör att du kan skapa banor som du kan behålla och spela upp efter behov på en duk.
type: docs
weight: 290
url: /sv/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

Path2D-gränssnittet för Canvas 2D API används för att deklarera sökvägar som sedan används på CanvasRenderingContext2D-objekt. Banmetoderna för CanvasRenderingContext2D-gränssnittet finns också i det här gränssnittet och gör att du kan skapa -banor som du kan behålla och spela upp efter behov på en duk.

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Path2D](path2d/#constructor)() | returnerar ett nyligen instansierat Path2D object |
| [Path2D](path2d/#constructor_1)(Path2D) | returnerar ett nyligen instansierat Path2D-objekt med en annan sökväg som argument (skapar en kopia) |
| [Path2D](path2d/#constructor_2)(string) | returnerar ett nyligen instansierat Path2D-objekt med en sträng som består av SVG-sökvägsdata. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Lägger till sökvägen som argumentet ger till sökvägen. |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Lägger till sökvägen som argumentet ger till sökvägen. |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Lägger till en båge till banan som är centrerad vid (x, y) position med radie r som börjar vid startAngle och slutar vid endAngle går i den angivna riktningen moturs (standard till medurs). |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Lägger till en båge till banan som är centrerad vid (x, y) position med radie r som börjar vid startAngle och slutar vid endAngle går i den angivna riktningen moturs (standard till medurs). |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Lägger till en båge till banan med de givna kontrollpunkterna och radien, kopplad till föregående punkt med en rät linje. |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Lägger till en kubisk Bézier-kurva till sökvägen. Det krävs tre poäng. De två första punkterna är kontrollpunkter och den tredje är slutpunkten. Startpunkten är den sista punkten i den aktuella sökvägen, som kan ändras med moveTo() innan Bézier-kurvan skapas. |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath/)() | Får pennans punkt att flytta tillbaka till början av den aktuella undersökvägen. Den försöker rita en rät linje från den aktuella punkten till början. Om formen redan har stängts eller bara har en punkt, gör den här funktionen ingenting. |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose/)() | Kastar objekt. |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Lägger till en ellips till banan som är centrerad vid (x, y) position med radierna radiusX och radiusY som börjar vid startAngle och slutar vid endAngle går i den angivna riktningen med moturs (standard till medurs). |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Lägger till en ellips till banan som är centrerad vid (x, y) position med radierna radiusX och radiusY som börjar vid startAngle och slutar vid endAngle går i den angivna riktningen med moturs (standard till medurs). |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto/)(double, double) | Kopplar den sista punkten i undersökvägen till x, y-koordinaterna med en rät linje. |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto/)(double, double) | Flyttar startpunkten för en ny delväg till (x, y) koordinaterna. |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Lägger till en kvadratisk Bézier-kurva till den aktuella vägen. |
| [Rect](../../aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Skapar en bana för en rektangel vid position (x, y) med en storlek som bestäms av bredd och höjd. |

### Se även

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* namnutrymme [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* hopsättning [Aspose.HTML](../../)


