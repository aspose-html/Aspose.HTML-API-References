---
title: Class DocDevice
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Rendering.Doc.DocDevice klas. Stellt das Rendern in ein DOCXDokument dar.
type: docs
weight: 4170
url: /de/net/aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Stellt das Rendern in ein DOCX-Dokument dar.

```csharp
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Initialisiert eine neue Instanz von`DocDevice` Klasse. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Initialisiert eine neue Instanz von`DocDevice` Klasse nach Ausgabestream. |
| [DocDevice](docdevice/#constructor_5)(string) | Initialisiert eine neue Instanz von`DocDevice` Klasse nach Name der Ausgabedatei. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Initialisiert eine neue Instanz von`DocDevice` Klasse nach Rendering-Optionen und Stream-Provider. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Initialisiert eine neue Instanz von`DocDevice` Klasse nach Rendering-Optionen und Ausgabestream. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, string) | Initialisiert eine neue Instanz von`DocDevice` Klasse nach Rendering-Optionen und Name der Ausgabedatei. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Hängt ein Rechteck als vollständigen Teilpfad an den aktuellen Pfad an. |
| override [BeginDocument](../../aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Beginnt mit der Wiedergabe des Dokuments. |
| override [BeginElement](../../aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Beginnt mit dem Rendern des HTML-Knotens. |
| override [BeginPage](../../aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Beginnt mit dem Rendern der neuen Seite. |
| override [Clip](../../aspose.html.rendering.doc/docdevice/clip/)(FillMode) | Ändert den aktuellen Beschneidungspfad, indem er ihn mit dem aktuellen Pfad schneidet, wobei die FillMode-Regel verwendet wird, um den zu füllenden Bereich zu bestimmen. Diese Methode beendet den aktuellen Pfad. |
| override [ClosePath](../../aspose.html.rendering.doc/docdevice/closepath/)() | Schließt den aktuellen Unterpfad durch Anhängen eines geraden Liniensegments vom aktuellen Punkt an den Startpunkt des Unterpfads. Wenn der aktuelle Unterpfad bereits geschlossen ist, tut "ClosePath" nichts. Dieser Operator beendet den aktuellen Unterpfad. Das Anhängen eines weiteren Segments an den aktuellen Pfad beginnt einen neuen Unterpfad, , selbst wenn das neue Segment an dem Endpunkt beginnt, der von der „ClosePath“-Methode erreicht wird. |
| override [CubicBezierTo](../../aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Hängt eine kubische Bézier-Kurve an den aktuellen Pfad an. Die Kurve erstreckt sich vom aktuellen Punkt bis zum Punkt pt2, , wobei pt1 und pt2 als Bézier-Kontrollpunkte verwendet werden. Der neue aktuelle Punkt ist pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.doc/docdevice/drawimage/)(byte[], ImageType, RectangleF) | Zeichnet das angegebene Bild. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.doc/docdevice/endelement/)(Element) | Beendet das Rendern des HTML-Knotens. |
| override [EndPage](../../aspose.html.rendering.doc/docdevice/endpage/)() | Beendet das Rendern der aktuellen Seite. |
| override [Fill](../../aspose.html.rendering.doc/docdevice/fill/)(FillMode) | Füllt den gesamten vom aktuellen Pfad eingeschlossenen Bereich. Wenn der Pfad aus mehreren getrennten Teilpfaden besteht, füllt er das Innere aller Teilpfade aus, zusammen betrachtet. Diese Methode beendet den aktuellen Pfad. |
| override [FillText](../../aspose.html.rendering.doc/docdevice/filltext/)(string, PointF) | Füllt die angegebene Textzeichenfolge an der angegebenen Stelle aus. |
| override [Flush](../../aspose.html.rendering.doc/docdevice/flush/)() | Flusht alle Daten in den Ausgabestream. |
| override [LineTo](../../aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Hängt ein gerades Liniensegment vom aktuellen Punkt an den Punkt (pt) an. Der neue aktuelle Punkt ist pt. |
| override [MoveTo](../../aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Beginnt einen neuen Teilpfad, indem der aktuelle Punkt auf die Koordinaten des Parameters pt verschoben wird, wobei alle Verbindungsliniensegmente weggelassen werden. Wenn die vorherige Pfadkonstruktionsmethode im aktuellen Pfad auch "MoveTo" war, überschreibt das neue "MoveTo" sie; keine Spur der vorherigen "MoveTo"-Operation bleibt im Pfad. |
| override [RestoreGraphicContext](../../aspose.html.rendering.doc/docdevice/restoregraphiccontext/)() | Stellt den gesamten Grafikkontext auf seinen früheren Wert wieder her, indem er vom Stapel entfernt wird. |
| override [SaveGraphicContext](../../aspose.html.rendering.doc/docdevice/savegraphiccontext/)() | Schiebt eine Kopie des gesamten Grafikkontexts auf den Stack. |
| override [Stroke](../../aspose.html.rendering.doc/docdevice/stroke/)() | Zeichnet eine Linie entlang des aktuellen Pfads. Die strichlierte Linie folgt jedem geraden oder gekrümmten Segment im Pfad, zentriert auf dem Segment mit parallelen Seiten dazu. Jeder der Teilpfade des Pfades wird separat behandelt. Diese Methode beendet den aktuellen Pfad. |
| override [StrokeAndFill](../../aspose.html.rendering.doc/docdevice/strokeandfill/)(FillMode) | Striche und aktuellen Pfad füllen. Diese Methode beendet aktuellen Pfad. |
| override [StrokeText](../../aspose.html.rendering.doc/docdevice/stroketext/)(string, PointF) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [DocGraphicContext](docdevice.docgraphiccontext/) | Enthält aktuelle Grafiksteuerungsparameter für das DocDevice. Diese Parameter definieren den globalen Rahmen, in dem die Grafikoperatoren ausgeführt werden. |

### Siehe auch

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* namensraum [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* Montage [Aspose.HTML](../../)


