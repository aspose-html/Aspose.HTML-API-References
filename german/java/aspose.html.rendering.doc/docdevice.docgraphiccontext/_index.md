---
title: "DocDevice.DocGraphicContext Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.doc.DocDeviceDocGraphicContext Klasse. Hält die aktuellen Grafiksteuerungsparameter für das DocDevice. Diese Parameter definieren das globale Rahmenwerk, in dem die Grafikoperatoren ausgeführt werden"
type: docs

url: /de/java/com.aspose.html.rendering.doc/docdevice.docgraphiccontext/
---
## DocDevice.DocGraphicContext class

Hält die aktuellen Grafiksteuerungsparameter für das DocDevice. Diese Parameter definieren das globale Rahmenwerk, in dem die Grafikoperatoren ausgeführt werden.

```java
public class DocGraphicContext : GraphicContext
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [docGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/.ctor)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Setzt oder liest den Zeichenabstand. |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Setzt oder liest das Pinselobjekt, das zum Füllen der Innenbereiche von Pfaden verwendet wird. |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | Setzt oder liest das TrueType-Schriftobjekt, das zum Rendern von Text verwendet wird. |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Setzt oder liest die Schriftgröße des Textes. |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Setzt oder liest den Schriftstil des Textes. |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Setzt oder liest den Code, der die Form der Endpunkte für jeden offenen Pfad, der gezeichnet wird, festlegt. |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Setzt oder liest den Phasenversatz des aktuellen Strichmusters. |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Setzt oder liest die Beschreibung des Strichmusters, das beim Zeichnen von Pfaden verwendet wird. |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Setzt oder liest den Code, der die Form der Verbindungen zwischen verbundenen Segmenten eines gezeichneten Pfades festlegt. |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Setzt oder liest die Dicke der zu zeichnenden Pfade. |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Setzt oder liest die maximale Länge von Gehrungs‑Verbindungen für gezeichnete Pfade. Dieser Parameter begrenzt die Länge der "Spitzen", die entstehen, wenn Liniensegmente an scharfen Winkeln zusammenlaufen. |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Setzt oder liest das Pinselobjekt, das für gezeichnete Pfade verwendet wird. |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) Ruft ein [`TextInfo`](../../com.aspose.html.rendering/textinfo/) Objekt ab, das Informationen über gerenderten Text enthält. |
| [transformationMatrix](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transformationmatrix) { get; set; } | Setzt oder liest die Transformationsmatrix. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [clone](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/clone)() | Erstellt eine neue Instanz einer [`GraphicContext`](../../com.aspose.html.rendering/graphiccontext/) Klasse mit denselben Eigenschaftswerten wie eine vorhandene Instanz. |
| [transform](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transform)(IMatrix) | Modifiziert die aktuelle Transformationsmatrix, indem die angegebene Matrix multipliziert wird. |

### Siehe auch

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [DocDevice](../docdevice/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
