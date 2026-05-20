---
title: "Path2D Class"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.canvas.Path2D-klass. Path2D-gränssnittet i Canvas 2D API används för att deklarera banor som senare används på CanvasRenderingContext2D-objekt. Banmetoderna i CanvasRenderingContext2D-gränssnittet finns också på detta gränssnitt och gör det möjligt att skapa banor som du kan behålla och återspela vid behov på en canvas."
type: docs

url: /sv/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

Path2D‑gränssnittet i Canvas 2D‑API:t används för att deklarera banor som senare används på CanvasRenderingContext2D‑objekt. Banmetoderna i CanvasRenderingContext2D‑gränssnittet finns även på detta gränssnitt och gör det möjligt att skapa banor som du kan behålla och återspela vid behov på en canvas.

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Path2D](path2d/#constructor)() | returnerar ett nyinstansierat Path2D-objekt |
| [Path2D](path2d/#constructor_1)(Path2D) | returnerar ett nyinstansierat Path2D-objekt med en annan bana som argument (skapar en kopia) |
| [Path2D](path2d/#constructor_2)(String) | returnerar ett nyinstansierat Path2D-objekt med en sträng som består av SVG-banadata. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Lägger till banan den bana som ges av argumentet. |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Lägger till banan den bana som ges av argumentet. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Lägger till en båge i banan som är centrerad vid positionen (x, y) med radien r, startar vid startAngle och slutar vid endAngle och går i den angivna riktningen moturs (standard är medurs). |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Lägger till en båge i banan som är centrerad vid positionen (x, y) med radien r, startar vid startAngle och slutar vid endAngle och går i den angivna riktningen moturs (standard är medurs). |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Lägger till en båge i banan med de angivna kontrollpunkterna och radien, ansluten till föregående punkt med en rak linje. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Lägger till en kubisk Bézier-kurva i banan. Den kräver tre punkter. De två första punkterna är kontrollpunkter och den tredje är slutpunkten. Startpunkten är den sista punkten i den aktuella banan, som kan ändras med moveTo() innan Bézier‑kurvan skapas. |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | Får pennans punkt att flytta tillbaka till början av den aktuella delbanan. Den försöker rita en rak linje från den aktuella punkten till starten. Om formen redan har stängts eller bara har en punkt gör funktionen ingenting. |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | Avslutar objektet. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Lägger till en ellips i banan som är centrerad vid positionen (x, y) med radierna radiusX och radiusY, startar vid startAngle och slutar vid endAngle och går i den angivna riktningen moturs (standard är medurs). |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Lägger till en ellips i banan som är centrerad vid positionen (x, y) med radierna radiusX och radiusY, startar vid startAngle och slutar vid endAngle och går i den angivna riktningen moturs (standard är medurs). |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | Ansluter den sista punkten i delbanan till koordinaterna x, y med en rak linje. |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | Flyttar startpunkten för en ny delbana till koordinaterna (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Lägger till en kvadratisk Bézier-kurva i den aktuella banan. |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Skapar en bana för en rektangel vid positionen (x, y) med en storlek som bestäms av bredd och höjd. |

### Se även

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
