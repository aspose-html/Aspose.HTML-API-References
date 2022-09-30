---
title: ImageDevice
second_title: Aspose.HTML für .NET-API-Referenz
description: Stellt das Rendern in Rasterformate dar jpeg png bmp gif tiff.
type: docs
weight: 4290
url: /de/net/aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Stellt das Rendern in Rasterformate dar: jpeg, png, bmp, gif, tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ImageDevice](imagedevice#constructor)(ICreateStreamProvider) | Initialisiert eine neue Instanz von[`ImageDevice`](../imagedevice) Klasse. |
| [ImageDevice](imagedevice#constructor_4)(Stream) | Initialisiert eine neue Instanz von[`ImageDevice`](../imagedevice) Klasse. |
| [ImageDevice](imagedevice#constructor_5)(string) | Initialisiert eine neue Instanz von[`ImageDevice`](../imagedevice) Klasse. |
| [ImageDevice](imagedevice#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Initialisiert eine neue Instanz von[`ImageDevice`](../imagedevice) Klasse nach Rendering-Optionen und Stream-Provider. |
| [ImageDevice](imagedevice#constructor_2)(ImageRenderingOptions, Stream) | Initialisiert eine neue Instanz von[`ImageDevice`](../imagedevice)Klasse nach Rendering-Optionen und Ausgabestream. |
| [ImageDevice](imagedevice#constructor_3)(ImageRenderingOptions, string) | Initialisiert eine neue Instanz von[`ImageDevice`](../imagedevice) Klasse nach Rendering-Optionen und Name der Ausgabedatei. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device`2/graphiccontext) { get; } |  |
| virtual [Graphics](../../aspose.html.rendering.image/imagedevice/graphics) { get; } | Ruft die Instanz von Graphics ab. |
| [Options](../../aspose.html.rendering/device`2/options) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.image/imagedevice/addrect)(RectangleF) | Hängt ein Rechteck als vollständigen Teilpfad an den aktuellen Pfad an. |
| override [BeginDocument](../../aspose.html.rendering.image/imagedevice/begindocument)(Document) | Beginnt mit der Wiedergabe des Dokuments. |
| override [BeginElement](../../aspose.html.rendering.image/imagedevice/beginelement)(Element, RectangleF) | Beginnt mit dem Rendern des Elements. |
| override [BeginPage](../../aspose.html.rendering.image/imagedevice/beginpage)(SizeF) | Beginnt mit dem Rendern der neuen Seite. |
| override [Clip](../../aspose.html.rendering.image/imagedevice/clip)(FillMode) | Ändert den aktuellen Beschneidungspfad, indem er ihn mit dem aktuellen Pfad schneidet, wobei die FillMode-Regel verwendet wird, um den zu füllenden Bereich zu bestimmen. Diese Methode beendet den aktuellen Pfad. |
| override [ClosePath](../../aspose.html.rendering.image/imagedevice/closepath)() | Schließt den aktuellen Unterpfad durch Anhängen eines geraden Liniensegments vom aktuellen Punkt an den Startpunkt des Unterpfads. Wenn der aktuelle Unterpfad bereits geschlossen ist, tut "ClosePath" nichts. Dieser Operator beendet den aktuellen Unterpfad. Das Anhängen eines weiteren Segments an den aktuellen Pfad beginnt einen neuen Unterpfad, , selbst wenn das neue Segment an dem Endpunkt beginnt, der von der „ClosePath“-Methode erreicht wird. |
| override [CubicBezierTo](../../aspose.html.rendering.image/imagedevice/cubicbezierto)(PointF, PointF, PointF) | Hängt eine kubische Bézier-Kurve an den aktuellen Pfad an. Die Kurve erstreckt sich vom aktuellen Punkt bis zum Punkt pt2, , wobei pt1 und pt2 als Bézier-Kontrollpunkte verwendet werden. Der neue aktuelle Punkt ist pt3. |
| [Dispose](../../aspose.html.rendering/device`2/dispose)() |  |
| override [DrawImage](../../aspose.html.rendering.image/imagedevice/drawimage)(byte[], ImageType, RectangleF) | Zeichnet das angegebene Bild. |
| override [EndDocument](../../aspose.html.rendering.image/imagedevice/enddocument)() | Beendet das Rendern des Dokuments. |
| override [EndElement](../../aspose.html.rendering.image/imagedevice/endelement)(Element) | Beendet das Rendern des Elements. |
| override [EndPage](../../aspose.html.rendering.image/imagedevice/endpage)() | Beendet das Rendern der aktuellen Seite. |
| override [Fill](../../aspose.html.rendering.image/imagedevice/fill)(FillMode) | Füllt den gesamten vom aktuellen Pfad eingeschlossenen Bereich. Wenn der Pfad aus mehreren getrennten Teilpfaden besteht, füllt er das Innere aller Teilpfade aus, zusammen betrachtet. Diese Methode beendet den aktuellen Pfad. |
| override [FillText](../../aspose.html.rendering.image/imagedevice/filltext)(string, PointF) | Füllt die angegebene Textzeichenfolge an der angegebenen Stelle aus. |
| override [Flush](../../aspose.html.rendering.image/imagedevice/flush)() | Flusht alle Daten in den Ausgabestream. |
| override [LineTo](../../aspose.html.rendering.image/imagedevice/lineto)(PointF) | Hängt ein gerades Liniensegment vom aktuellen Punkt an den Punkt (pt) an. Der neue aktuelle Punkt ist pt. |
| override [MoveTo](../../aspose.html.rendering.image/imagedevice/moveto)(PointF) | Beginnt einen neuen Teilpfad, indem der aktuelle Punkt auf die Koordinaten des Parameters pt verschoben wird, wobei alle Verbindungsliniensegmente weggelassen werden. Wenn die vorherige Pfadkonstruktionsmethode im aktuellen Pfad auch "MoveTo" war, überschreibt das neue "MoveTo" sie; keine Spur der vorherigen "MoveTo"-Operation bleibt im Pfad. |
| override [RestoreGraphicContext](../../aspose.html.rendering.image/imagedevice/restoregraphiccontext)() | Stellt den gesamten Grafikkontext auf seinen früheren Wert wieder her, indem er vom Stapel entfernt wird. |
| override [SaveGraphicContext](../../aspose.html.rendering.image/imagedevice/savegraphiccontext)() | Schiebt eine Kopie des gesamten Grafikkontexts auf den Stack. |
| override [Stroke](../../aspose.html.rendering.image/imagedevice/stroke)() | Zeichnet eine Linie entlang des aktuellen Pfads. Die strichlierte Linie folgt jedem geraden oder gekrümmten Segment im Pfad, zentriert auf dem Segment mit parallelen Seiten dazu. Jeder der Teilpfade des Pfades wird separat behandelt. Diese Methode beendet den aktuellen Pfad. |
| override [StrokeAndFill](../../aspose.html.rendering.image/imagedevice/strokeandfill)(FillMode) | Striche und aktuellen Pfad füllen. Diese Methode beendet aktuellen Pfad. |
| override [StrokeText](../../aspose.html.rendering.image/imagedevice/stroketext)(string, PointF) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [ImageGraphicContext](imagedevice.imagegraphiccontext) | Enthält aktuelle Grafiksteuerungsparameter für die[`ImageDevice`](../imagedevice) . Diese Parameter definieren den globalen Rahmen, innerhalb dessen die Grafikoperatoren ausgeführt werden. |

### Siehe auch

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2)
* class [ImageRenderingOptions](../imagerenderingoptions)
* namensraum [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image)
* Montage [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
