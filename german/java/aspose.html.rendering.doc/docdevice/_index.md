---
title: "DocDevice Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.doc.DocDevice Klasse. Stellt das Rendern in ein DOCX-Dokument dar"
type: docs

url: /de/java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Stellt das Rendern in ein DOCX-Dokument dar.

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Initialisiert eine neue Instanz der `DocDevice` Klasse. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Initialisiert eine neue Instanz der `DocDevice` Klasse über einen Ausgabestream. |
| [DocDevice](docdevice/#constructor_5)(String) | Initialisiert eine neue Instanz der `DocDevice` Klasse über einen Ausgabedateinamen. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Initialisiert eine neue Instanz der `DocDevice` Klasse mit Rendering-Optionen und Stream‑Provider. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Initialisiert eine neue Instanz der `DocDevice` Klasse mit Rendering-Optionen und Ausgabestream. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | Initialisiert eine neue Instanz der `DocDevice` Klasse mit Rendering-Optionen und Ausgabedateinamen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Fügt ein Rechteck zum aktuellen Pfad als vollständigen Unterpfad hinzu. |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Beginnt das Rendern des Dokuments. |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Beginnt das Rendern des HTML‑Knotens. |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Beginnt das Rendern der neuen Seite. |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillRule) | Modifiziert den aktuellen Clipping‑Pfad, indem er mit dem aktuellen Pfad geschnitten wird, wobei die FillMode‑Regel zur Bestimmung des zu füllenden Bereichs verwendet wird. Diese Methode beendet den aktuellen Pfad. |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | Schließt den aktuellen Unterpfad, indem ein gerader Linienabschnitt vom aktuellen Punkt zum Startpunkt des Unterpfads hinzugefügt wird. Wenn der aktuelle Unterpfad bereits geschlossen ist, bewirkt "ClosePath" nichts. Dieser Operator beendet den aktuellen Unterpfad. Das Hinzufügen eines weiteren Abschnitts zum aktuellen Pfad beginnt einen neuen Unterpfad, selbst wenn der neue Abschnitt am Endpunkt beginnt, der durch die Methode "ClosePath" erreicht wurde. |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Fügt dem aktuellen Pfad eine kubische Bézier‑Kurve hinzu. Die Kurve erstreckt sich vom aktuellen Punkt zum Punkt pt2 und verwendet pt1 und pt2 als Bézier‑Steuerpunkte. Der neue aktuelle Punkt ist pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Zeichnet das angegebene Bild. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | Beendet das Rendern des HTML‑Knotens. |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | Beendet das Rendern der aktuellen Seite. |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillRule) | Füllt den gesamten von dem aktuellen Pfad umschlossenen Bereich. Besteht der Pfad aus mehreren getrennten Teilpfaden, füllt er die Innenbereiche aller Teilpfade zusammen. Diese Methode beendet den aktuellen Pfad. |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | Füllt die angegebene Textzeichenkette am angegebenen Ort. |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | Spült alle Daten in den Ausgabestream. |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Fügt ein gerades Liniensegment vom aktuellen Punkt zum Punkt (pt) hinzu. Der neue aktuelle Punkt ist pt. |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Beginnt einen neuen Teilpfad, indem der aktuelle Punkt zu den Koordinaten des Parameters pt verschoben wird, wobei ein verbindendes Liniensegment weggelassen wird. War die vorherige Pfadkonstruktionsmethode im aktuellen Pfad ebenfalls "MoveTo", überschreibt das neue "MoveTo" sie; es verbleibt kein Rest der vorherigen "MoveTo"-Operation im Pfad. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | Zeichnet eine Linie entlang des aktuellen Pfads. Die gezeichnete Linie folgt jedem geraden oder gekrümmten Segment im Pfad, zentriert auf dem Segment mit parallel verlaufenden Seiten. Jeder Teilpfad des Pfads wird separat behandelt. Diese Methode beendet den aktuellen Pfad. |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillRule) | Zeichnet und füllt den aktuellen Pfad. Diese Methode beendet den aktuellen Pfad. |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | Zeichnet die angegebene Textzeichenkette am angegebenen Ort. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | Hält die aktuellen Grafiksteuerungsparameter für das DocDevice. Diese Parameter definieren das globale Rahmenwerk, in dem die Grafikoperatoren ausgeführt werden. |

### Siehe auch

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
