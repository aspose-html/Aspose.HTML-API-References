---
title: Class DeviceTGraphicContextTRenderingOptions
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Rendering.Device2TGraphicContextTRenderingOptions klas. Stellt die Basisklasse für die Implementierung bestimmter RenderingGeräte dar.
type: docs
weight: 4140
url: /de/net/aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Stellt die Basisklasse für die Implementierung bestimmter Rendering-Geräte dar.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | Beschreibung |
| --- | --- |
| TGraphicContext | Grafikkontext, der aktuelle Grafiksteuerungsparameter enthält |
| TRenderingOptions | Rendering-Optionen |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } | Ruft den grafischen Kontext ab |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } | Ruft Renderoptionen ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [AddRect](../../aspose.html.rendering/device-2/addrect/)(RectangleF) | Hängt ein Rechteck als vollständigen Teilpfad an den aktuellen Pfad an. |
| virtual [BeginDocument](../../aspose.html.rendering/device-2/begindocument/)(Document) | Beginnt mit der Wiedergabe des Dokuments. |
| abstract [BeginElement](../../aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Beginnt mit dem Rendern des Knotens. |
| virtual [BeginPage](../../aspose.html.rendering/device-2/beginpage/)(SizeF) | Beginnt mit dem Rendern der neuen Seite. |
| abstract [Clip](../../aspose.html.rendering/device-2/clip/)(FillMode) | Ändert den aktuellen Beschneidungspfad, indem er ihn mit dem aktuellen Pfad schneidet, wobei die FillMode-Regel verwendet wird, um den zu füllenden Bereich zu bestimmen. Diese Methode beendet den aktuellen Pfad. |
| abstract [ClosePath](../../aspose.html.rendering/device-2/closepath/)() | Schließt den aktuellen Unterpfad durch Anhängen eines geraden Liniensegments vom aktuellen Punkt an den Startpunkt des Unterpfads. Wenn der aktuelle Unterpfad bereits geschlossen ist, tut "ClosePath" nichts. Dieser Operator beendet den aktuellen Unterpfad. Das Anhängen eines weiteren Segments an den aktuellen Pfad beginnt einen neuen Unterpfad, , selbst wenn das neue Segment an dem Endpunkt beginnt, der von der „ClosePath“-Methode erreicht wird. |
| abstract [CubicBezierTo](../../aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Hängt eine kubische Bézier-Kurve an den aktuellen Pfad an. Die Kurve erstreckt sich vom aktuellen Punkt bis zum Punkt pt2, , wobei pt1 und pt2 als Bézier-Kontrollpunkte verwendet werden. Der neue aktuelle Punkt ist pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| abstract [DrawImage](../../aspose.html.rendering/device-2/drawimage/)(byte[], ImageType, RectangleF) | Zeichnet das angegebene Bild. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() | Beendet das Rendern des Dokuments. |
| abstract [EndElement](../../aspose.html.rendering/device-2/endelement/)(Element) | Beendet das Rendern des Knotens. |
| virtual [EndPage](../../aspose.html.rendering/device-2/endpage/)() | Beendet das Rendern der aktuellen Seite. |
| abstract [Fill](../../aspose.html.rendering/device-2/fill/)(FillMode) | Füllt den gesamten vom aktuellen Pfad eingeschlossenen Bereich. Wenn der Pfad aus mehreren getrennten Teilpfaden besteht, füllt er das Innere aller Teilpfade aus, zusammen betrachtet. Diese Methode beendet den aktuellen Pfad. |
| abstract [FillText](../../aspose.html.rendering/device-2/filltext/)(string, PointF) | Füllt die angegebene Textzeichenfolge an der angegebenen Stelle aus. |
| virtual [Flush](../../aspose.html.rendering/device-2/flush/)() | Flusht alle Daten in den Ausgabestream. |
| abstract [LineTo](../../aspose.html.rendering/device-2/lineto/)(PointF) | Hängt ein gerades Liniensegment vom aktuellen Punkt an den Punkt (pt) an. Der neue aktuelle Punkt ist pt. |
| abstract [MoveTo](../../aspose.html.rendering/device-2/moveto/)(PointF) | Beginnt einen neuen Teilpfad, indem der aktuelle Punkt auf die Koordinaten des Parameters pt verschoben wird, wobei alle Verbindungsliniensegmente weggelassen werden. Wenn die vorherige Pfadkonstruktionsmethode im aktuellen Pfad auch "MoveTo" war, überschreibt das neue "MoveTo" sie; keine Spur der vorherigen "MoveTo"-Operation bleibt im Pfad. |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device-2/restoregraphiccontext/)() | Stellt den gesamten Grafikkontext auf seinen früheren Wert wieder her, indem er vom Stapel entfernt wird. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() | Schiebt eine Kopie des gesamten Grafikkontexts auf den Stack. |
| abstract [Stroke](../../aspose.html.rendering/device-2/stroke/)() | Zeichnet eine Linie entlang des aktuellen Pfads. Die strichlierte Linie folgt jedem geraden oder gekrümmten Segment im Pfad, zentriert auf dem Segment mit parallelen Seiten dazu. Jeder der Teilpfade des Pfades wird separat behandelt. Diese Methode beendet den aktuellen Pfad. |
| abstract [StrokeAndFill](../../aspose.html.rendering/device-2/strokeandfill/)(FillMode) | Striche und aktuellen Pfad füllen. Diese Methode beendet aktuellen Pfad. |
| abstract [StrokeText](../../aspose.html.rendering/device-2/stroketext/)(string, PointF) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](device-2.deviceconfiguration-2/) | Stellt das Konfigurationsobjekt für Geräte dar. |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](device-2.pagewritingstrategy-2/) | Gibt Arten von Strategien zum Schreiben von Seiten in Ausgabestrom/-ströme an. |

### Siehe auch

* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* namensraum [Aspose.Html.Rendering](../../aspose.html.rendering/)
* Montage [Aspose.HTML](../../)


