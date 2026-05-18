---
title: "IDevice Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.IDevice Schnittstelle. Definiert Methoden und Eigenschaften, die benutzerdefiniertes Rendern von grafischen Elementen wie Pfaden, Text und Bildern unterstützen."
type: docs

url: /de/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

Definiert Methoden und Eigenschaften, die benutzerdefiniertes Rendering von grafischen Elementen wie Pfaden, Text und Bildern unterstützen.

```java
public interface IDevice : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) Gibt den Grafik‑Kontext zurück. |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) Gibt die Rendering-Optionen zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | Fügt dem aktuellen Pfad ein Rechteck als vollständigen Unterpfad hinzu. |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | Beginnt das Rendern des Dokuments. |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Beginnt das Rendern des Elements. |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | Beginnt das Rendern der neuen Seite. |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | Modifiziert den aktuellen Clipping-Pfad, indem er ihn mit dem aktuellen Pfad schneidet und dabei die FillRule verwendet, um den zu füllenden Bereich zu bestimmen. Diese Methode beendet den aktuellen Pfad. |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | Schließt den aktuellen Unterpfad, indem ein gerader Linienabschnitt vom aktuellen Punkt zum Startpunkt des Unterpfads angehängt wird. Wenn der aktuelle Unterpfad bereits geschlossen ist, bewirkt \"ClosePath\" nichts. Dieser Operator beendet den aktuellen Unterpfad. Das Anhängen eines weiteren Segments an den aktuellen Pfad startet einen neuen Unterpfad, selbst wenn das neue Segment am Endpunkt beginnt, der durch die Methode \"ClosePath\" erreicht wurde. |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Fügt dem aktuellen Pfad eine kubische Bézier‑Kurve hinzu. Die Kurve erstreckt sich vom aktuellen Punkt zum Punkt pt3 und verwendet pt1 und pt2 als Bézier‑Steuerpunkte. Der neue aktuelle Punkt ist pt3. |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Zeichnet das angegebene Bild. |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | Beendet das Rendern des Dokuments. |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | Beendet das Rendern des Elements. |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | Beendet das Rendern der aktuellen Seite. |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | Füllt den gesamten von dem aktuellen Pfad umschlossenen Bereich. Wenn der Pfad aus mehreren getrennten Teilpfaden besteht, füllt er die Innenbereiche aller Teilpfade zusammen. Diese Methode beendet den aktuellen Pfad. |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | Füllt die angegebene Textzeichenfolge am angegebenen Ort. |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | Spült alle Daten in den Ausgabestream. |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | Fügt ein gerades Liniensegment vom aktuellen Punkt zum Punkt (pt) hinzu. Der neue aktuelle Punkt ist pt. |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | Beginnt einen neuen Teilpfad, indem der aktuelle Punkt zu den Koordinaten des Parameters pt verschoben wird, wobei ein verbindendes Liniensegment weggelassen wird. Wenn die vorherige Pfadkonstruktionsmethode im aktuellen Pfad ebenfalls "MoveTo" war, überschreibt das neue "MoveTo" sie; es verbleibt kein Rest der vorherigen "MoveTo"-Operation im Pfad. |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | Stellt den gesamten Grafik-Kontext auf seinen vorherigen Wert wieder her, indem er ihn vom Stapel entfernt. |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | Schiebt eine Kopie des gesamten Grafik-Kontexts auf den Stapel. |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | Zeichnet eine Linie entlang des aktuellen Pfads. Die gezeichnete Linie folgt jedem geraden oder gekrümmten Segment im Pfad, zentriert auf dem Segment mit parallel verlaufenden Seiten. Jeder Teilpfad des Pfads wird separat behandelt. Diese Methode beendet den aktuellen Pfad. |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | Zeichnet und füllt den aktuellen Pfad. Diese Methode beendet den aktuellen Pfad. |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | Zeichnet die angegebene Textzeichenfolge am angegebenen Ort. |

### Siehe auch

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
