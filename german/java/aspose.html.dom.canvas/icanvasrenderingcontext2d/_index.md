---
title: "ICanvasRenderingContext2D‑Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.canvas.ICanvasRenderingContext2D‑Schnittstelle. Die ICanvasRenderingContext2D‑Schnittstelle wird zum Zeichnen von Rechtecken, Text, Bildern und anderen Objekten auf das Canvas‑Element verwendet. Sie stellt den 2D‑Rendering‑Kontext für die Zeichenfläche eines Canvas‑Elements bereit."
type: docs

url: /de/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

Die ICanvasRenderingContext2D‑Schnittstelle wird zum Zeichnen von Rechtecken, Text, Bildern und anderen Objekten auf dem Canvas-Element verwendet. Sie stellt den 2D‑Renderkontext für die Zeichenfläche eines Canvas-Elements bereit.

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) Eine schreibgeschützte Rückreferenz auf das HTMLCanvasElement. Kann null sein, wenn es nicht mit einem Canvas‑Element verknüpft ist. |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Startet einen neuen Pfad, indem die Liste der Unterpfade geleert wird. Rufen Sie diese Methode auf, wenn Sie einen neuen Pfad erstellen möchten. |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Entfernt alle Trefferregionen vom Canvas. |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Setzt alle Pixel im Rechteck, das durch den Startpunkt (x, y) und die Größe (Breite, Höhe) definiert ist, auf transparentes Schwarz und löscht damit jeglichen zuvor gezeichneten Inhalt. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Erstellt eine neue Clipping‑Region, indem die Schnittmenge der aktuellen Clipping‑Region und des durch den Pfad beschriebenen Bereichs berechnet wird, unter Verwendung der Non‑Zero‑Winding‑Number‑Regel. Offene Unterpfade müssen beim Berechnen der Clipping‑Region implizit geschlossen werden, ohne die tatsächlichen Unterpfade zu beeinflussen. Die neue Clipping‑Region ersetzt die aktuelle Clipping‑Region. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Erstellt eine neue Clipping‑Region, indem die Schnittmenge der aktuellen Clipping‑Region und des durch den Pfad beschriebenen Bereichs berechnet wird, unter Verwendung der Non‑Zero‑Winding‑Number‑Regel. Offene Unterpfade müssen beim Berechnen der Clipping‑Region implizit geschlossen werden, ohne die tatsächlichen Unterpfade zu beeinflussen. Die neue Clipping‑Region ersetzt die aktuelle Clipping‑Region. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Erstellt eine neue Clipping‑Region, indem die Schnittmenge der aktuellen Clipping‑Region und des durch den Pfad beschriebenen Bereichs berechnet wird, unter Verwendung der Non‑Zero‑Winding‑Number‑Regel. Offene Unterpfade müssen beim Berechnen der Clipping‑Region implizit geschlossen werden, ohne die tatsächlichen Unterpfade zu beeinflussen. Die neue Clipping‑Region ersetzt die aktuelle Clipping‑Region. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Erstellt ein neues, leeres ImageData‑Objekt mit den angegebenen Abmessungen. Alle Pixel im neuen Objekt sind transparent schwarz. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Erstellt ein neues, leeres ImageData‑Objekt mit den angegebenen Abmessungen. Alle Pixel im neuen Objekt sind transparent schwarz. |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Erstellt einen linearen Farbverlauf entlang der Linie, die durch die durch die Parameter angegebenen Koordinaten definiert ist. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | Erstellt ein Muster mithilfe des angegebenen Bildes (eine CanvasImageSource). Es wiederholt die Quelle in den durch das Wiederholungsargument angegebenen Richtungen. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | Erstellt ein Muster mithilfe des angegebenen Bildes (eine CanvasImageSource). Es wiederholt die Quelle in den durch das Wiederholungsargument angegebenen Richtungen. |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Erstellt einen radialen Farbverlauf, der durch die Koordinaten der beiden durch die Parameter dargestellten Kreise definiert ist. |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Wenn ein gegebenes Element fokussiert ist, zeichnet diese Methode einen Fokusring um den aktuellen Pfad. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Zeichnet das angegebene Bild. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Zeichnet das angegebene Bild. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Zeichnet das angegebene Bild. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Zeichnet das angegebene Bild. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Zeichnet das angegebene Bild. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Zeichnet das angegebene Bild. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Füllt die Unterpfade mit dem aktuellen Füllstil und dem Standardalgorithmus CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Füllt die Unterpfade mit dem aktuellen Füllstil. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Füllt die Unterpfade mit dem aktuellen Füllstil und dem Standardalgorithmus CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Füllt die Unterpfade mit dem aktuellen Füllstil. |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Zeichnet ein gefülltes Rechteck an der Position (x, y), dessen Größe durch Breite und Höhe bestimmt wird. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | Zeichnet (füllt) einen angegebenen Text an der angegebenen Position (x,y). |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | Zeichnet (füllt) einen angegebenen Text an der angegebenen Position (x,y). |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Gibt ein ImageData-Objekt zurück, das die zugrunde liegenden Pixeldaten für den Bereich der Leinwand darstellt, der durch das Rechteck definiert ist, das bei (sx, sy) beginnt und eine Breite von sw sowie eine Höhe von sh hat. Diese Methode wird nicht von der Transformationsmatrix der Leinwand beeinflusst. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Gibt an, ob der angegebene Punkt im aktuellen Pfad enthalten ist oder nicht. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Gibt an, ob der angegebene Punkt im aktuellen Pfad enthalten ist oder nicht. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Gibt an, ob der angegebene Punkt im aktuellen Pfad enthalten ist oder nicht. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Gibt an, ob der angegebene Punkt im aktuellen Pfad enthalten ist oder nicht. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Gibt an, ob der angegebene Punkt innerhalb des Bereichs liegt, der durch das Strichzeichnen eines Pfades entsteht, oder nicht. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Gibt an, ob der angegebene Punkt innerhalb des Bereichs liegt, der durch das Strichzeichnen eines Pfades entsteht, oder nicht. |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | Gibt ein TextMetrics-Objekt zurück. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Malt Daten aus dem angegebenen ImageData-Objekt auf die Bitmap. Wenn ein schmutziges Rechteck angegeben wird, werden nur die Pixel aus diesem Rechteck gemalt. Diese Methode wird nicht von der Transformationsmatrix der Leinwand beeinflusst. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Malt Daten aus dem angegebenen ImageData-Objekt auf die Bitmap. Wenn ein schmutziges Rechteck angegeben wird, werden nur die Pixel aus diesem Rechteck gemalt. Diese Methode wird nicht von der Transformationsmatrix der Leinwand beeinflusst. |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | Entfernt die Trefferregion mit der angegebenen ID von der Leinwand. |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Setzt die aktuelle Transformation durch die Einheitsmatrix zurück. |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Stellt den Zeichenstilzustand auf das letzte Element im 'Zustandsstapel' wieder her, das durch save() gespeichert wurde. |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Fügt der Transformationsmatrix eine Drehung hinzu. Das Winkelargument stellt einen im Uhrzeigersinn gerichteten Rotationswinkel dar und wird in Radianten angegeben. |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Speichert den aktuellen Zeichenstilzustand mithilfe eines Stapels, sodass Sie jede Änderung mit restore() rückgängig machen können. |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Fügt den Leinwand-Einheiten eine Skalierungstransformation hinzu, horizontal um x und vertikal um y. |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Setzt die aktuelle Transformation auf die Einheitsmatrix zurück und ruft anschließend die Methode transform() mit denselben Argumenten auf. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Striche die Unterpfade mit dem aktuellen Strichstil. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Striche die Unterpfade mit dem aktuellen Strichstil. |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Malt ein Rechteck, das einen Startpunkt bei (x, y) hat und eine Breite w sowie eine Höhe h besitzt, auf die Leinwand, wobei der aktuelle Strichstil verwendet wird. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | Zeichnet (striche) einen angegebenen Text an der angegebenen Position (x, y). |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | Zeichnet (striche) einen angegebenen Text an der angegebenen Position (x, y). |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Multipliziert die aktuelle Transformationsmatrix mit der durch ihre Argumente beschriebenen Matrix. |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Fügt eine Translations­transformation hinzu, indem die Leinwand und ihr Ursprung horizontal um x und vertikal um y im Raster verschoben werden. |

### Siehe auch

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
