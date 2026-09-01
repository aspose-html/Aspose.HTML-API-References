---
title: "ICanvasPathMethods Interface"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.canvas.ICanvasPathMethods interface. ICanvasPathMethods‑gränssnittet används för att manipulera objektsbanor."
type: docs

url: /sv/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

ICanvasPathMethods‑gränssnittet används för att manipulera objektens banor.

```java
public interface ICanvasPathMethods
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Lägger till en båge i banan som är centrerad vid (x, y) med radien r som startar vid startAngle och slutar vid endAngle i angiven riktning moturs (standard är medurs). |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Lägger till en båge i banan som är centrerad vid (x, y) med radien r som startar vid startAngle och slutar vid endAngle i angiven riktning moturs (standard är medurs). |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Lägger till en båge i banan med de angivna kontrollpunkterna och radien, ansluten till föregående punkt med en rak linje. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Lägger till en kubisk Bézier‑kurva i banan. Den kräver tre punkter. De två första punkterna är kontrollpunkter och den tredje är slutpunkten. Startpunkten är den sista punkten i den aktuella banan, som kan ändras med moveTo() innan Bézier‑kurvan skapas. |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Får pennans spets att flytta tillbaka till början av den aktuella delbanan. Den försöker rita en rak linje från den aktuella punkten till början. Om formen redan har stängts eller bara har en punkt gör funktionen ingenting. |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Lägger till en ellips i banan som är centrerad vid (x, y) med radierna radiusX och radiusY som startar vid startAngle och slutar vid endAngle i angiven riktning moturs (standard är medurs). |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Lägger till en ellips i banan som är centrerad vid (x, y) med radierna radiusX och radiusY som startar vid startAngle och slutar vid endAngle i angiven riktning moturs (standard är medurs). |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Ansluter den sista punkten i delbanan till x, y‑koordinaterna med en rak linje. |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Flyttar startpunkten för en ny delbana till (x, y)-koordinaterna. |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Lägger till en kvadratisk Bézier‑kurva i den aktuella banan. |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Skapar en bana för en rektangel vid position (x, y) med en storlek som bestäms av bredd och höjd. |

### Se även

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
