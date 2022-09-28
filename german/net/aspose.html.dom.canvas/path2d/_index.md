---
title: Path2D
second_title: Aspose.HTML für .NET-API-Referenz
description: Die Path2DSchnittstelle der Canvas 2DAPI wird verwendet um Pfade zu deklarieren die dann später auf CanvasRenderingContext2DObjekten verwendet werden. Die Pfadmethoden der CanvasRenderingContext2DSchnittstelle sind auch auf dieser Schnittstelle vorhanden und ermöglichen es Ihnen Pfade zu erstellen die Sie beibehalten und nach Bedarf auf einer Leinwand wiedergeben können.
type: docs
weight: 300
url: /de/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

Die Path2D-Schnittstelle der Canvas 2D-API wird verwendet, um Pfade zu deklarieren, die dann später auf CanvasRenderingContext2D-Objekten verwendet werden. Die Pfadmethoden der CanvasRenderingContext2D-Schnittstelle sind auch auf dieser Schnittstelle vorhanden und ermöglichen es Ihnen, -Pfade zu erstellen, die Sie beibehalten und nach Bedarf auf einer Leinwand wiedergeben können.

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Path2D](path2d#constructor)() | gibt ein neu instanziiertes Path2D-Objekt zurück |
| [Path2D](path2d#constructor_1)(Path2D) | gibt ein neu instanziiertes Path2D-Objekt mit einem anderen Pfad als Argument zurück (erstellt eine Kopie) |
| [Path2D](path2d#constructor_2)(string) | gibt ein neu instanziiertes Path2D-Objekt mit einer Zeichenfolge zurück, die aus SVG-Pfaddaten besteht. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath#addpath)(Path2D) | Fügt dem Pfad den durch das Argument angegebenen Pfad hinzu. |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath#addpath_1)(Path2D, SVGMatrix) | Fügt dem Pfad den durch das Argument angegebenen Pfad hinzu. |
| [Arc](../../aspose.html.dom.canvas/path2d/arc#arc)(double, double, double, double, double) | Fügt dem Pfad einen Bogen hinzu, der an der Position (x, y) zentriert ist, mit Radius r, beginnend bei startAngle und endend bei endAngle, in die angegebene Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [Arc](../../aspose.html.dom.canvas/path2d/arc#arc_1)(double, double, double, double, double, bool) | Fügt dem Pfad einen Bogen hinzu, der an der Position (x, y) zentriert ist, mit Radius r, beginnend bei startAngle und endend bei endAngle, in die angegebene Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto)(double, double, double, double, double) | Fügt dem Pfad mit den angegebenen Kontrollpunkten und Radius einen Bogen hinzu, der durch eine gerade Linie mit dem vorherigen Punkt verbunden ist. |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto)(double, double, double, double, double, double) | Fügt dem Pfad eine kubische Bézier-Kurve hinzu. Es erfordert drei Punkte. Die ersten beiden Punkte sind Kontrollpunkte und der dritte ist der Endpunkt. Der Startpunkt ist der letzte Punkt im aktuellen Pfad, , der mit moveTo() geändert werden kann, bevor die Bézier-Kurve erstellt wird. |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath)() | Bewirkt, dass sich die Stiftspitze zum Anfang des aktuellen Unterpfads zurückbewegt. Es wird versucht, eine gerade Linie vom aktuellen Punkt zum Startpunkt zu ziehen. Wenn die Form bereits geschlossen ist oder nur einen Punkt hat, macht diese Funktion nichts. |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose)() | Entledigt Objekt. |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse#ellipse)(double, double, double, double, double, double, double) | Fügt dem Pfad eine Ellipse hinzu, die an der Position (x, y) zentriert ist, mit den Radien radiusX und radiusY, beginnend bei startAngle und endend bei endAngle, in die angegebene Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse#ellipse_1)(double, double, double, double, double, double, double, bool) | Fügt dem Pfad eine Ellipse hinzu, die an der Position (x, y) zentriert ist, mit den Radien radiusX und radiusY, beginnend bei startAngle und endend bei endAngle, in die angegebene Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto)(double, double) | Verbindet den letzten Punkt im Teilpfad mit einer geraden Linie mit den x-, y-Koordinaten. |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto)(double, double) | Verschiebt den Startpunkt eines neuen Unterpfads zu den (x, y)-Koordinaten. |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto)(double, double, double, double) | Fügt dem aktuellen Pfad eine quadratische Bézier-Kurve hinzu. |
| [Rect](../../aspose.html.dom.canvas/path2d/rect)(double, double, double, double) | Erstellt einen Pfad für ein Rechteck an Position (x, y) mit einer Größe, die durch Breite und Höhe bestimmt wird. |

### Siehe auch

* class [DOMObject](../../aspose.html.dom/domobject)
* interface [ICanvasPathMethods](../icanvaspathmethods)
* namensraum [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas)
* Montage [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
