---
title: "DeviceTGraphicContextTRenderingOptions Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.Device2TGraphicContextTRenderingOptions Klasse. Stellt die Basisklasse für die Implementierung bestimmter Rendering‑Geräte dar."
type: docs

url: /de/java/com.aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Stellt die Basisklasse für die Implementierung bestimmter Rendering-Geräte dar.

```java
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | Beschreibung |
| --- | --- |
| TGraphicContext | Grafik‑Kontext, der die aktuellen Grafiksteuerungsparameter enthält |
| TRenderingOptions | Rendering‑Optionen |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) Gibt den Grafik‑Kontext zurück |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) Gibt Rendering‑Optionen zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) | Fügt ein Rechteck zum aktuellen Pfad als vollständigen Unterpfad hinzu. |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) | Beginnt das Rendern des Dokuments. |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Beginnt das Rendern des Knotens. |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) | Beginnt das Rendern der neuen Seite. |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) | Modifiziert den aktuellen Clipping-Pfad, indem er mit dem aktuellen Pfad geschnitten wird, wobei die FillRule verwendet wird, um den zu füllenden Bereich zu bestimmen. Diese Methode beendet den aktuellen Pfad. |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() | Schließt den aktuellen Unterpfad, indem ein gerader Linienabschnitt vom aktuellen Punkt zum Startpunkt des Unterpfads hinzugefügt wird. Wenn der aktuelle Unterpfad bereits geschlossen ist, bewirkt "ClosePath" nichts. Dieser Operator beendet den aktuellen Unterpfad. Das Hinzufügen eines weiteren Abschnitts zum aktuellen Pfad beginnt einen neuen Unterpfad, selbst wenn der neue Abschnitt am Endpunkt beginnt, der durch die Methode "ClosePath" erreicht wurde. |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Fügt dem aktuellen Pfad eine kubische Bézier‑Kurve hinzu. Die Kurve erstreckt sich vom aktuellen Punkt zum Punkt pt2 und verwendet pt1 und pt2 als Bézier‑Steuerpunkte. Der neue aktuelle Punkt ist pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) | Zeichnet das angegebene Bild. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() | Beendet das Rendern des Dokuments. |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) | Beendet das Rendern des Knotens. |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() | Beendet das Rendern der aktuellen Seite. |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) | Füllt den gesamten von dem aktuellen Pfad umschlossenen Bereich. Besteht der Pfad aus mehreren getrennten Teilpfaden, füllt er die Innenbereiche aller Teilpfade zusammen. Diese Methode beendet den aktuellen Pfad. |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) | Füllt die angegebene Textzeichenkette am angegebenen Ort. |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() | Spült alle Daten in den Ausgabestream. |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) | Fügt ein gerades Liniensegment vom aktuellen Punkt zum Punkt (pt) hinzu. Der neue aktuelle Punkt ist pt. |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) | Beginnt einen neuen Teilpfad, indem der aktuelle Punkt zu den Koordinaten des Parameters pt verschoben wird, wobei ein verbindendes Liniensegment weggelassen wird. War die vorherige Pfadkonstruktionsmethode im aktuellen Pfad ebenfalls "MoveTo", überschreibt das neue "MoveTo" sie; es verbleibt kein Rest der vorherigen "MoveTo"-Operation im Pfad. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() | Stellt den gesamten Grafik-Kontext auf seinen vorherigen Wert wieder her, indem er ihn vom Stapel entfernt. |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() | Schiebt eine Kopie des gesamten Grafik-Kontexts auf den Stapel. |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() | Zeichnet eine Linie entlang des aktuellen Pfads. Die gezeichnete Linie folgt jedem geraden oder gekrümmten Segment im Pfad, zentriert auf dem Segment mit parallel verlaufenden Seiten. Jeder Teilpfad des Pfads wird separat behandelt. Diese Methode beendet den aktuellen Pfad. |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) | Zeichnet und füllt den aktuellen Pfad. Diese Methode beendet den aktuellen Pfad. |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) | Zeichnet die angegebene Textzeichenkette am angegebenen Ort. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.pagewritingstrategy-2) | Gibt Typen von Strategien zum Schreiben von Seiten in Ausgabestream\streams an. |

### Siehe auch

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
