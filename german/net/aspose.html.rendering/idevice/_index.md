---
title: Interface IDevice
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Rendering.IDevice koppel. Definiert Methoden und Eigenschaften die das benutzerdefinierte Rendering der Grafikelemente wie Pfade Text und Bilder unterstützen.
type: docs
weight: 4280
url: /de/net/aspose.html.rendering/idevice/
---
## IDevice interface

Definiert Methoden und Eigenschaften, die das benutzerdefinierte Rendering der Grafikelemente wie Pfade, Text und Bilder unterstützen.

```csharp
public interface IDevice : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/idevice/graphiccontext/) { get; } | Ruft den grafischen Kontext ab. |
| [Options](../../aspose.html.rendering/idevice/options/) { get; } | Ruft Renderoptionen ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddRect](../../aspose.html.rendering/idevice/addrect/)(RectangleF) | Hängt ein Rechteck als vollständigen Teilpfad an den aktuellen Pfad an. |
| [BeginDocument](../../aspose.html.rendering/idevice/begindocument/)(Document) | Beginnt mit der Wiedergabe des Dokuments. |
| [BeginElement](../../aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Beginnt mit dem Rendern des Elements. |
| [BeginPage](../../aspose.html.rendering/idevice/beginpage/)(SizeF) | Beginnt mit dem Rendern der neuen Seite. |
| [Clip](../../aspose.html.rendering/idevice/clip/)(FillMode) | Ändert den aktuellen Beschneidungspfad, indem er ihn mit dem aktuellen Pfad schneidet, wobei die FillMode-Regel verwendet wird, um den zu füllenden Bereich zu bestimmen. Diese Methode beendet den aktuellen Pfad. |
| [ClosePath](../../aspose.html.rendering/idevice/closepath/)() | Schließt den aktuellen Unterpfad durch Anhängen eines geraden Liniensegments vom aktuellen Punkt an den Startpunkt des Unterpfads. Wenn der aktuelle Unterpfad bereits geschlossen ist, tut "ClosePath" nichts. Dieser Operator beendet den aktuellen Unterpfad. Das Anhängen eines weiteren Segments an den aktuellen Pfad beginnt einen neuen Unterpfad, , selbst wenn das neue Segment an dem Endpunkt beginnt, der von der „ClosePath“-Methode erreicht wird. |
| [CubicBezierTo](../../aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Hängt eine kubische Bézier-Kurve an den aktuellen Pfad an. Die Kurve erstreckt sich vom aktuellen Punkt bis zum Punkt pt3, , wobei pt1 und pt2 als Bézier-Kontrollpunkte verwendet werden. Der neue aktuelle Punkt ist pt3. |
| [DrawImage](../../aspose.html.rendering/idevice/drawimage/)(byte[], ImageType, RectangleF) | Zeichnet das angegebene Bild. |
| [EndDocument](../../aspose.html.rendering/idevice/enddocument/)() | Beendet das Rendern des Dokuments. |
| [EndElement](../../aspose.html.rendering/idevice/endelement/)(Element) | Beendet das Rendern des Elements. |
| [EndPage](../../aspose.html.rendering/idevice/endpage/)() | Beendet das Rendern der aktuellen Seite. |
| [Fill](../../aspose.html.rendering/idevice/fill/)(FillMode) | Füllt den gesamten vom aktuellen Pfad eingeschlossenen Bereich. Wenn der Pfad aus mehreren getrennten Teilpfaden besteht, füllt er das Innere aller Teilpfade aus, zusammen betrachtet. Diese Methode beendet den aktuellen Pfad. |
| [FillText](../../aspose.html.rendering/idevice/filltext/)(string, PointF) | Füllt die angegebene Textzeichenfolge an der angegebenen Stelle aus. |
| [Flush](../../aspose.html.rendering/idevice/flush/)() | Flusht alle Daten in den Ausgabestream. |
| [LineTo](../../aspose.html.rendering/idevice/lineto/)(PointF) | Hängt ein gerades Liniensegment vom aktuellen Punkt an den Punkt (pt) an. Der neue aktuelle Punkt ist pt. |
| [MoveTo](../../aspose.html.rendering/idevice/moveto/)(PointF) | Beginnt einen neuen Teilpfad, indem der aktuelle Punkt auf die Koordinaten des Parameters pt verschoben wird, wobei alle Verbindungsliniensegmente weggelassen werden. Wenn die vorherige Pfadkonstruktionsmethode im aktuellen Pfad auch "MoveTo" war, überschreibt das neue "MoveTo" sie; keine Spur der vorherigen "MoveTo"-Operation bleibt im Pfad. |
| [RestoreGraphicContext](../../aspose.html.rendering/idevice/restoregraphiccontext/)() | Stellt den gesamten Grafikkontext auf seinen früheren Wert wieder her, indem er vom Stapel entfernt wird. |
| [SaveGraphicContext](../../aspose.html.rendering/idevice/savegraphiccontext/)() | Schiebt eine Kopie des gesamten Grafikkontexts auf den Stack. |
| [Stroke](../../aspose.html.rendering/idevice/stroke/)() | Zeichnet eine Linie entlang des aktuellen Pfads. Die strichlierte Linie folgt jedem geraden oder gekrümmten Segment im Pfad, zentriert auf dem Segment mit parallelen Seiten dazu. Jeder der Teilpfade des Pfades wird separat behandelt. Diese Methode beendet den aktuellen Pfad. |
| [StrokeAndFill](../../aspose.html.rendering/idevice/strokeandfill/)(FillMode) | Striche und aktuellen Pfad füllen. Diese Methode beendet aktuellen Pfad. |
| [StrokeText](../../aspose.html.rendering/idevice/stroketext/)(string, PointF) | Zeichnet die angegebene Textzeichenfolge an der angegebenen Position. |

### Siehe auch

* namensraum [Aspose.Html.Rendering](../../aspose.html.rendering/)
* Montage [Aspose.HTML](../../)


