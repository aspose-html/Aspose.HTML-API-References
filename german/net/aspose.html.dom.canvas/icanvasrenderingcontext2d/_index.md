---
title: Interface ICanvasRenderingContext2D
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Canvas.ICanvasRenderingContext2D koppel. Die ICanvasRenderingContext2DSchnittstelle wird zum Zeichnen von Rechtecken Text Bildern und anderen Objekten auf dem CanvasElement verwendet. Es stellt den 2DRenderingKontext für die Zeichenoberfläche eines CanvasElements bereit.
type: docs
weight: 260
url: /de/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

Die ICanvasRenderingContext2D-Schnittstelle wird zum Zeichnen von Rechtecken, Text, Bildern und anderen Objekten auf dem Canvas-Element verwendet. Es stellt den 2D-Rendering-Kontext für die Zeichenoberfläche eines Canvas-Elements bereit.

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) { get; } | Ein schreibgeschützter Rückverweis auf das HTMLCanvasElement. Kann null sein, wenn es keinem Canvas-Element zugeordnet ist. |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle/) { get; set; } | Farbe oder Stil zur Verwendung in Formen. Standard: (schwarz). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha/) { get; set; } | Alphawert, der auf Formen und Bilder angewendet wird, bevor sie auf der Leinwand zusammengesetzt werden. Standard 1,0 (undurchsichtig). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation/) { get; set; } | Wenn globalAlpha angewendet wird, legt dies fest, wie Formen und Bilder auf die vorhandene Bitmap gezeichnet werden. Standard: (source-over) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled/) { get; set; } | Bildglättungsmodus; Wenn deaktiviert, werden Bilder beim Skalieren nicht geglättet. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur/) { get; set; } | Gibt den Unschärfeeffekt an. Standard 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor/) { get; set; } | Farbe des Schattens. Standardmäßig vollständig transparentes Schwarz. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx/) { get; set; } | Horizontaler Abstand, um den der Schatten versetzt wird. Standard 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety/) { get; set; } | Vertikaler Abstand um den der Schatten versetzt wird. Standard 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle/) { get; set; } | Farbe oder Stil für die Linien um Formen. Standard: (schwarz). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;string, string&gt;) | Fügt der Leinwand einen Trefferbereich hinzu. Dadurch können Sie die Treffererkennung vereinfachen, Ereignisse an DOM-Elemente weiterleiten und es Benutzern ermöglichen, die Zeichenfläche zu erkunden, ohne sie zu sehen. |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Beginnt einen neuen Pfad, indem die Liste der Unterpfade geleert wird. Rufen Sie diese Methode auf, wenn Sie einen neuen Pfad erstellen möchten. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Entfernt alle Trefferregionen von der Leinwand. |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Setzt alle Pixel im Rechteck, das durch Startpunkt (x, y) und Größe (Breite, Höhe) definiert ist, auf transparentes Schwarz und löscht alle zuvor gezeichneten Inhalte. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Erstellt einen neuen Clipping-Bereich durch Berechnung des Schnittpunkts des aktuellen Clipping-Bereichs und des durch den Pfad beschriebenen Bereichs unter Verwendung der Windungszahlregel ungleich Null. Offene Unterpfade müssen beim Berechnen des Clipping-Bereichs implizit geschlossen werden, ohne die tatsächlichen Unterpfade zu beeinflussen . Der neue Clipping-Bereich ersetzt den aktuellen Clipping-Bereich. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Erstellt einen neuen Clipping-Bereich durch Berechnung des Schnittpunkts des aktuellen Clipping-Bereichs und des durch den Pfad beschriebenen Bereichs unter Verwendung der Windungszahlregel ungleich Null. Offene Teilpfade müssen bei der Berechnung des Clipping-Bereichs implizit geschlossen werden, ohne dass dies Auswirkungen auf die eigentlichen Teilpfade hat. Der neue Clipping-Bereich ersetzt den aktuellen Clipping-Bereich. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Erstellt einen neuen Clipping-Bereich durch Berechnung des Schnittpunkts des aktuellen Clipping-Bereichs und des durch den Pfad beschriebenen Bereichs unter Verwendung der Windungszahlregel ungleich Null. Offene Teilpfade müssen bei der Berechnung des Clipping-Bereichs implizit geschlossen werden, ohne dass dies Auswirkungen auf die eigentlichen Teilpfade hat. Der neue Clipping-Bereich ersetzt den aktuellen Clipping-Bereich. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Erstellt ein neues, leeres ImageData-Objekt mit den angegebenen Abmessungen. Alle Pixel im neuen Objekt sind transparent schwarz. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Erstellt ein neues, leeres ImageData-Objekt mit den angegebenen Abmessungen. Alle Pixel im neuen Objekt sind transparent schwarz. |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Erstellt einen linearen Farbverlauf entlang der Linie, die durch die durch die Parameter repräsentierten Koordinaten gegeben ist. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, string) | Erstellt ein Muster unter Verwendung des angegebenen Bildes (eine CanvasImageSource). Es wiederholt die Quelle in den Richtungen, die durch das Wiederholungsargument angegeben sind. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, string) | Erstellt ein Muster unter Verwendung des angegebenen Bildes (eine CanvasImageSource). Es wiederholt die Quelle in den Richtungen, die durch das Wiederholungsargument angegeben sind. |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Erstellt einen radialen Farbverlauf, der durch die Koordinaten der beiden durch die Parameter repräsentierten Kreise gegeben ist. |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Wenn ein bestimmtes Element fokussiert ist, zeichnet diese Methode einen Fokusring um den aktuellen Pfad. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Zeichnet das angegebene Bild. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Zeichnet das angegebene Bild. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Zeichnet das angegebene Bild. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Zeichnet das angegebene Bild. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Zeichnet das angegebene Bild. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Zeichnet das angegebene Bild. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Füllt die Teilpfade mit dem aktuellen Füllstil und Standardalgorithmus CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Füllt die Unterpfade mit dem aktuellen Füllstil. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Füllt die Teilpfade mit dem aktuellen Füllstil und Standardalgorithmus CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Füllt die Unterpfade mit dem aktuellen Füllstil. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Zeichnet ein gefülltes Rechteck an der Position (x, y), dessen Größe durch Breite und Höhe bestimmt wird. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(string, double, double) | Zeichnet (füllt) einen gegebenen Text an der gegebenen (x,y) Position. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(string, double, double, double) | Zeichnet (füllt) einen gegebenen Text an der gegebenen (x,y) Position. |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Gibt ein ImageData-Objekt zurück, das die zugrunde liegenden Pixeldaten für den Bereich der Leinwand darstellt, der durch das Rechteck gekennzeichnet ist, das bei (sx, sy) beginnt und eine sw-Breite und eine sh-Höhe hat. Diese Methode wird nicht von der Leinwandtransformationsmatrix beeinflusst. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Gibt an, ob der angegebene Punkt im aktuellen Pfad enthalten ist oder nicht. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Gibt an, ob der angegebene Punkt im aktuellen Pfad enthalten ist oder nicht. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Gibt an, ob der angegebene Punkt im aktuellen Pfad enthalten ist oder nicht. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Gibt an, ob der angegebene Punkt im aktuellen Pfad enthalten ist oder nicht. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Gibt an, ob sich der angegebene Punkt innerhalb des Bereichs befindet, der durch das Streichen eines Pfads eingeschlossen ist. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Gibt an, ob sich der angegebene Punkt innerhalb des Bereichs befindet, der durch das Streichen eines Pfads eingeschlossen ist. |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(string) | Gibt ein TextMetrics-Objekt zurück. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Zeichnet Daten aus dem gegebenen ImageData-Objekt auf die Bitmap. Wenn ein schmutziges Rechteck bereitgestellt wird, werden nur die Pixel dieses Rechtecks gezeichnet. Diese Methode wird nicht von der Canvas-Transformationsmatrix beeinflusst. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Zeichnet Daten aus dem gegebenen ImageData-Objekt auf die Bitmap. Wenn ein schmutziges Rechteck bereitgestellt wird, werden nur die Pixel dieses Rechtecks gezeichnet. Diese Methode wird nicht von der Canvas-Transformationsmatrix beeinflusst. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(string) | Entfernt die Trefferregion mit der angegebenen ID aus der Leinwand. |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Setzt die aktuelle Transformation durch die Identitätsmatrix zurück. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Stellt den Zeichnungsstilstatus bis zum letzten Element auf dem 'Statusstapel' wieder her, der durch save() gespeichert wurde. |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Fügt der Transformationsmatrix eine Rotation hinzu. Das Winkelargument stellt einen Rotationswinkel im Uhrzeigersinn dar und wird in Bogenmaß ausgedrückt. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Speichert den aktuellen Status des Zeichnungsstils mithilfe eines Stapels, sodass Sie alle daran vorgenommenen Änderungen mithilfe von restore() rückgängig machen können. |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Fügt eine Skalierungstransformation zu den Canvas-Einheiten horizontal um x und vertikal um y hinzu. |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Setzt die aktuelle Transformation auf die Identitätsmatrix zurück und ruft dann die transform()-Methode mit denselben Argumenten auf. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Zeichnet die Unterpfade mit dem aktuellen Strichstil. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Zeichnet die Unterpfade mit dem aktuellen Strichstil. |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Zeichnet ein Rechteck mit einem Startpunkt bei (x, y) und einer Breite von w und einer Höhe von h unter Verwendung des aktuellen Strichstils auf die Leinwand. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(string, double, double) | Zeichnet (Striche) einen gegebenen Text an der gegebenen (x, y) Position. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(string, double, double, double?) | Zeichnet (Striche) einen gegebenen Text an der gegebenen (x, y) Position. |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Multipliziert die aktuelle Transformationsmatrix mit der durch ihre Argumente beschriebenen Matrix. |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Fügt eine Übersetzungstransformation hinzu, indem die Leinwand und ihr Ursprung x horizontal und y vertikal auf dem Raster verschoben werden. |

### Siehe auch

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* namensraum [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* Montage [Aspose.HTML](../../)


