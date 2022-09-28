---
title: XpsDevice
second_title: Aspose.HTML für .NET-API-Referenz
description: Stellt das Rendern in ein XPSDokument dar.
type: docs
weight: 4510
url: /de/net/aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

Stellt das Rendern in ein XPS-Dokument dar.

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [XpsDevice](xpsdevice#constructor)(ICreateStreamProvider) | Initialisiert eine neue Instanz von[`XpsDevice`](../xpsdevice) Klasse. |
| [XpsDevice](xpsdevice#constructor_4)(Stream) | Initialisiert eine neue Instanz von[`XpsDevice`](../xpsdevice) Klasse. |
| [XpsDevice](xpsdevice#constructor_5)(string) | Initialisiert eine neue Instanz von[`XpsDevice`](../xpsdevice) Klasse. |
| [XpsDevice](xpsdevice#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Initialisiert eine neue Instanz von[`XpsDevice`](../xpsdevice) Klasse nach Rendering-Optionen und Stream-Provider. |
| [XpsDevice](xpsdevice#constructor_2)(XpsRenderingOptions, Stream) | Initialisiert eine neue Instanz von[`XpsDevice`](../xpsdevice)Klasse nach Rendering-Optionen und Ausgabestream. |
| [XpsDevice](xpsdevice#constructor_3)(XpsRenderingOptions, string) | Initialisiert eine neue Instanz von[`XpsDevice`](../xpsdevice) Klasse nach Rendering-Optionen und Name der Ausgabedatei. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device`2/graphiccontext) { get; } |  |
| [Options](../../aspose.html.rendering/device`2/options) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.xps/xpsdevice/addrect)(RectangleF) | Hängt ein Rechteck als vollständigen Teilpfad an den aktuellen Pfad an. |
| override [BeginDocument](../../aspose.html.rendering.xps/xpsdevice/begindocument)(Document) | Beginnt mit der Wiedergabe des Dokuments. |
| override [BeginElement](../../aspose.html.rendering.xps/xpsdevice/beginelement)(Element, RectangleF) | Beginnt mit dem Rendern des Elements. |
| override [BeginPage](../../aspose.html.rendering.xps/xpsdevice/beginpage)(SizeF) | Beginnt mit dem Rendern der neuen Seite. |
| override [Clip](../../aspose.html.rendering.xps/xpsdevice/clip)(FillMode) | Ändert den aktuellen Beschneidungspfad, indem er ihn mit dem aktuellen Pfad schneidet, wobei die FillMode-Regel verwendet wird, um den zu füllenden Bereich zu bestimmen. Diese Methode beendet den aktuellen Pfad. |
| override [ClosePath](../../aspose.html.rendering.xps/xpsdevice/closepath)() | Schließt den aktuellen Unterpfad durch Anhängen eines geraden Liniensegments vom aktuellen Punkt an den Startpunkt des Unterpfads. Wenn der aktuelle Unterpfad bereits geschlossen ist, tut "ClosePath" nichts. Dieser Operator beendet den aktuellen Unterpfad. Das Anhängen eines weiteren Segments an den aktuellen Pfad beginnt einen neuen Unterpfad, , selbst wenn das neue Segment an dem Endpunkt beginnt, der von der „ClosePath“-Methode erreicht wird. |
| override [CubicBezierTo](../../aspose.html.rendering.xps/xpsdevice/cubicbezierto)(PointF, PointF, PointF) | Hängt eine kubische Bézier-Kurve an den aktuellen Pfad an. Die Kurve erstreckt sich vom aktuellen Punkt bis zum Punkt pt2, , wobei pt1 und pt2 als Bézier-Kontrollpunkte verwendet werden. Der neue aktuelle Punkt ist pt3. |
| [Dispose](../../aspose.html.rendering/device`2/dispose)() |  |
| override [DrawImage](../../aspose.html.rendering.xps/xpsdevice/drawimage)(byte[], ImageType, RectangleF) | Zeichnet das angegebene Bild. |
| virtual [EndDocument](../../aspose.html.rendering/device`2/enddocument)() |  |
| override [EndElement](../../aspose.html.rendering.xps/xpsdevice/endelement)(Element) | Beendet das Rendern des Elements. |
| override [EndPage](../../aspose.html.rendering.xps/xpsdevice/endpage)() | Beendet das Rendern der aktuellen Seite. |
| override [Fill](../../aspose.html.rendering.xps/xpsdevice/fill)(FillMode) | Füllt den gesamten vom aktuellen Pfad eingeschlossenen Bereich. Wenn der Pfad aus mehreren getrennten Teilpfaden besteht, füllt er das Innere aller Teilpfade aus, zusammen betrachtet. Diese Methode beendet den aktuellen Pfad. |
| override [FillText](../../aspose.html.rendering.xps/xpsdevice/filltext)(string, PointF) | Füllt die angegebene Textzeichenfolge an der angegebenen Stelle aus. |
| override [Flush](../../aspose.html.rendering.xps/xpsdevice/flush)() | Flusht alle Daten in den Ausgabestream. |
| override [LineTo](../../aspose.html.rendering.xps/xpsdevice/lineto)(PointF) | Hängt ein gerades Liniensegment vom aktuellen Punkt an den Punkt (pt) an. Der neue aktuelle Punkt ist pt. |
| override [MoveTo](../../aspose.html.rendering.xps/xpsdevice/moveto)(PointF) | Beginnt einen neuen Teilpfad, indem der aktuelle Punkt auf die Koordinaten des Parameters pt verschoben wird, wobei alle Verbindungsliniensegmente weggelassen werden. Wenn die vorherige Pfadkonstruktionsmethode im aktuellen Pfad auch "MoveTo" war, überschreibt das neue "MoveTo" sie; keine Spur der vorherigen "MoveTo"-Operation bleibt im Pfad. |
| override [RestoreGraphicContext](../../aspose.html.rendering.xps/xpsdevice/restoregraphiccontext)() | Stellt den gesamten Grafikkontext auf seinen früheren Wert wieder her, indem er vom Stapel entfernt wird. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device`2/savegraphiccontext)() |  |
| override [Stroke](../../aspose.html.rendering.xps/xpsdevice/stroke)() | Zeichnet eine Linie entlang des aktuellen Pfads. Die strichlierte Linie folgt jedem geraden oder gekrümmten Segment im Pfad, zentriert auf dem Segment mit parallelen Seiten dazu. Jeder der Teilpfade des Pfades wird separat behandelt. Diese Methode beendet den aktuellen Pfad. |
| override [StrokeAndFill](../../aspose.html.rendering.xps/xpsdevice/strokeandfill)(FillMode) | Striche und aktuellen Pfad füllen. Diese Methode beendet aktuellen Pfad. |
| override [StrokeText](../../aspose.html.rendering.xps/xpsdevice/stroketext)(string, PointF) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [XpsGraphicContext](xpsdevice.xpsgraphiccontext) | Enthält aktuelle Grafiksteuerungsparameter für das XpsDevice. Diese Parameter definieren den globalen Rahmen, in dem die Grafikoperatoren ausgeführt werden. |

### Siehe auch

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext)
* class [XpsRenderingOptions](../xpsrenderingoptions)
* namensraum [Aspose.Html.Rendering.Xps](../../aspose.html.rendering.xps)
* Montage [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
