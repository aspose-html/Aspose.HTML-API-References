---
title: "XpsDevice.XpsGraphicContext‑Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.xps.XpsDeviceXpsGraphicContext Klasse. Enthält aktuelle Grafiksteuerungsparameter für das XpsDevice. Diese Parameter definieren den globalen Rahmen, innerhalb dessen die Grafikoperatoren ausgeführt werden."
type: docs

url: /de/java/com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext/
---
## XpsDevice.XpsGraphicContext class

Enthält aktuelle Grafiksteuerungsparameter für das XpsDevice. Diese Parameter definieren das globale Framework, innerhalb dessen die Grafikoperatoren ausgeführt werden.

```java
public class XpsGraphicContext : GraphicContext
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [xpsGraphicContext](../../com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext/.ctor)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Legt den Zeichenabstand fest oder liest ihn aus. |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Legt das Pinselobjekt fest oder liest es aus, das zum Füllen der Innenbereiche von Pfaden verwendet wird. |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | Legt das TrueType-Schriftobjekt fest oder liest es aus, das zum Rendern von Text verwendet wird. |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Legt die Schriftgröße des Textes fest oder liest sie aus. |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Legt den Schriftstil des Textes fest oder liest ihn aus. |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Legt den Code fest oder liest ihn aus, der die Form der Endpunkte für jeden offenen Pfad, der gestrichen wird, angibt. |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Legt den Phasenversatz des aktuellen Strichmuster für Linien fest oder liest ihn aus. |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Legt die Beschreibung des Strichmusters fest oder liest sie aus, das beim Streichen von Pfaden verwendet wird. |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Legt den Code fest oder liest ihn aus, der die Form der Verbindungen zwischen verbundenen Segmenten eines gestrichenen Pfades angibt. |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Legt die Dicke der zu streichenden Pfade fest oder liest sie aus. |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Legt die maximale Länge von Gehrungs-Verbindungen für gestrichene Pfade fest oder liest sie aus. Dieser Parameter begrenzt die Länge der \"Spitzen\", die entstehen, wenn Liniensegmente an scharfen Winkeln zusammenlaufen. |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Legt das Pinselobjekt fest oder liest es aus, das für gestrichene Pfade verwendet wird. |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) Gibt ein [`TextInfo`](../../com.aspose.html.rendering/textinfo/) Objekt zurück, das Informationen über gerenderten Text enthält. |
| [transformationMatrix](../../com.aspose.html.rendering/graphiccontext/transformationmatrix/) { get; set; } | Legt die Transformationsmatrix fest oder liest sie aus. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [clone](../../com.aspose.html.rendering/graphiccontext/clone/)() | Erstellt eine neue Instanz einer GraphicContext Klasse mit denselben Eigenschaftswerten wie eine vorhandene Instanz. |
| [transform](../../com.aspose.html.rendering/graphiccontext/transform/)(IMatrix) | Modifiziert die aktuelle Transformationsmatrix, indem die angegebene Matrix multipliziert wird. |

### Siehe auch

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [XpsDevice](../xpsdevice/)
* package [com.aspose.html.rendering.xps](../../com.aspose.html.rendering.xps/)
* package [Aspose.HTML](../../)
