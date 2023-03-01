---
title: Interface ICanvasPathMethods
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods koppel. Die Schnittstelle ICanvasPathMethods wird verwendet um Pfade von Objekten zu manipulieren.
type: docs
weight: 240
url: /de/net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

Die Schnittstelle ICanvasPathMethods wird verwendet, um Pfade von Objekten zu manipulieren.

```csharp
public interface ICanvasPathMethods
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Fügt dem Pfad einen Bogen hinzu, der an der Position (x, y) zentriert ist, mit Radius r, beginnend bei startAngle und endend bei endAngle, in die angegebene Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Fügt dem Pfad einen Bogen hinzu, der an der Position (x, y) zentriert ist, mit Radius r, beginnend bei startAngle und endend bei endAngle, in die angegebene Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Fügt dem Pfad mit den angegebenen Kontrollpunkten und Radius einen Bogen hinzu, der durch eine gerade Linie mit dem vorherigen Punkt verbunden ist. |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Fügt dem Pfad eine kubische Bézier-Kurve hinzu. Es erfordert drei Punkte. Die ersten beiden Punkte sind Kontrollpunkte und der dritte ist der Endpunkt. Der Startpunkt ist der letzte Punkt im aktuellen Pfad, , der mit moveTo() geändert werden kann, bevor die Bézier-Kurve erstellt wird. |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Bewirkt, dass sich die Stiftspitze zum Anfang des aktuellen Unterpfads zurückbewegt. Es wird versucht, eine gerade Linie vom aktuellen Punkt zum Startpunkt zu ziehen. Wenn die Form bereits geschlossen ist oder nur einen Punkt hat, macht diese Funktion nichts. |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Fügt dem Pfad eine Ellipse hinzu, die an der Position (x, y) zentriert ist, mit den Radien radiusX und radiusY, beginnend bei startAngle und endend bei endAngle, in die angegebene Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Fügt dem Pfad eine Ellipse hinzu, die an der Position (x, y) zentriert ist, mit den Radien radiusX und radiusY, beginnend bei startAngle und endend bei endAngle, in die angegebene Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Verbindet den letzten Punkt im Teilpfad mit einer geraden Linie mit den x-, y-Koordinaten. |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Verschiebt den Startpunkt eines neuen Unterpfads zu den (x, y)-Koordinaten. |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Fügt dem aktuellen Pfad eine quadratische Bézier-Kurve hinzu. |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Erstellt einen Pfad für ein Rechteck an Position (x, y) mit einer Größe, die durch Breite und Höhe bestimmt wird. |

### Siehe auch

* namensraum [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* Montage [Aspose.HTML](../../)


