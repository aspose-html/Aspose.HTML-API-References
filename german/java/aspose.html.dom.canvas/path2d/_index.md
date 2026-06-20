---
title: "Path2D-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.canvas.Path2D Klasse. Das Path2D-Interface der Canvas 2D API wird verwendet, um Pfade zu deklarieren, die später auf CanvasRenderingContext2D-Objekten verwendet werden. Die Pfadmethoden des CanvasRenderingContext2D-Interfaces sind ebenfalls auf diesem Interface vorhanden und ermöglichen es Ihnen, Pfade zu erstellen, die Sie bei Bedarf auf einer Leinwand behalten und wiedergeben können."
type: docs

url: /de/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

Die Path2D‑Schnittstelle der Canvas‑2D‑API wird verwendet, um Pfade zu deklarieren, die später auf CanvasRenderingContext2D‑Objekten verwendet werden. Die Pfadmethoden der CanvasRenderingContext2D‑Schnittstelle sind ebenfalls in dieser Schnittstelle vorhanden und ermöglichen es Ihnen, Pfade zu erstellen, die Sie bei Bedarf auf einer Leinwand behalten und wiedergeben können.

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Path2D](path2d/#constructor)() | gibt ein neu instanziiertes Path2D-Objekt zurück. |
| [Path2D](path2d/#constructor_1)(Path2D) | gibt ein neu instanziiertes Path2D-Objekt mit einem anderen Pfad als Argument zurück (erstellt eine Kopie). |
| [Path2D](path2d/#constructor_2)(String) | gibt ein neu instanziiertes Path2D-Objekt mit einem String zurück, der SVG-Pfad-Daten enthält. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Fügt dem Pfad den durch das Argument angegebenen Pfad hinzu. |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Fügt dem Pfad den durch das Argument angegebenen Pfad hinzu. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Fügt dem Pfad einen Bogen hinzu, der zentriert bei (x, y) mit dem Radius r ist, beginnend bei startAngle und endend bei endAngle, in der angegebenen Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Fügt dem Pfad einen Bogen hinzu, der zentriert bei (x, y) mit dem Radius r ist, beginnend bei startAngle und endend bei endAngle, in der angegebenen Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Fügt dem Pfad einen Bogen mit den angegebenen Kontrollpunkten und dem Radius hinzu, verbunden mit dem vorherigen Punkt durch eine gerade Linie. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Fügt dem Pfad eine kubische Bézierkurve hinzu. Sie benötigt drei Punkte. Die ersten beiden Punkte sind Kontrollpunkte und der dritte ist der Endpunkt. Der Startpunkt ist der letzte Punkt im aktuellen Pfad, der mit moveTo() geändert werden kann, bevor die Bézierkurve erstellt wird. |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | Veranlasst den Stiftpunkt, zum Anfang des aktuellen Unterpfads zurückzukehren. Es versucht, eine gerade Linie vom aktuellen Punkt zum Anfang zu zeichnen. Wenn die Form bereits geschlossen ist oder nur einen Punkt hat, bewirkt diese Funktion nichts. |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | Gibt das Objekt frei. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Fügt dem Pfad eine Ellipse hinzu, die zentriert bei (x, y) mit den Radien radiusX und radiusY ist, beginnend bei startAngle und endend bei endAngle, in der angegebenen Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Fügt dem Pfad eine Ellipse hinzu, die zentriert bei (x, y) mit den Radien radiusX und radiusY ist, beginnend bei startAngle und endend bei endAngle, in der angegebenen Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | Verbindet den letzten Punkt im Unterpfad mit den x, y‑Koordinaten durch eine gerade Linie. |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | Verschiebt den Startpunkt eines neuen Unterpfads zu den Koordinaten (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Fügt dem aktuellen Pfad eine quadratische Bézierkurve hinzu. |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Erstellt einen Pfad für ein Rechteck an der Position (x, y) mit einer Größe, die durch Breite und Höhe bestimmt wird. |

### Siehe auch

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
