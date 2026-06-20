---
title: "ICanvasPathMethods-Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.canvas.ICanvasPathMethods-Interface. Das ICanvasPathMethods-Interface wird verwendet, um Pfade von Objekten zu manipulieren."
type: docs

url: /de/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

Die ICanvasPathMethods‑Schnittstelle wird verwendet, um Pfade von Objekten zu manipulieren.

```java
public interface ICanvasPathMethods
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Fügt dem Pfad einen Bogen hinzu, der zentriert bei (x, y) mit dem Radius r ist, beginnend bei startAngle und endend bei endAngle, in der angegebenen Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Fügt dem Pfad einen Bogen hinzu, der zentriert bei (x, y) mit dem Radius r ist, beginnend bei startAngle und endend bei endAngle, in der angegebenen Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Fügt dem Pfad einen Bogen mit den angegebenen Kontrollpunkten und dem Radius hinzu, verbunden mit dem vorherigen Punkt durch eine gerade Linie. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Fügt dem Pfad eine kubische Bézierkurve hinzu. Sie benötigt drei Punkte. Die ersten beiden Punkte sind Kontrollpunkte und der dritte ist der Endpunkt. Der Startpunkt ist der letzte Punkt im aktuellen Pfad, der mit moveTo() geändert werden kann, bevor die Bézierkurve erstellt wird. |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Veranlasst den Stiftpunkt, zum Anfang des aktuellen Unterpfads zurückzukehren. Es versucht, eine gerade Linie vom aktuellen Punkt zum Anfang zu zeichnen. Wenn die Form bereits geschlossen ist oder nur einen Punkt hat, bewirkt diese Funktion nichts. |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Fügt dem Pfad eine Ellipse hinzu, die zentriert bei (x, y) mit den Radien radiusX und radiusY ist, beginnend bei startAngle und endend bei endAngle, in der angegebenen Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Fügt dem Pfad eine Ellipse hinzu, die zentriert bei (x, y) mit den Radien radiusX und radiusY ist, beginnend bei startAngle und endend bei endAngle, in der angegebenen Richtung gegen den Uhrzeigersinn (standardmäßig im Uhrzeigersinn). |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Verbindet den letzten Punkt im Unterpfad mit den x, y‑Koordinaten durch eine gerade Linie. |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Verschiebt den Startpunkt eines neuen Unterpfads zu den Koordinaten (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Fügt dem aktuellen Pfad eine quadratische Bézierkurve hinzu. |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Erstellt einen Pfad für ein Rechteck an der Position (x, y) mit einer Größe, die durch Breite und Höhe bestimmt wird. |

### Siehe auch

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
