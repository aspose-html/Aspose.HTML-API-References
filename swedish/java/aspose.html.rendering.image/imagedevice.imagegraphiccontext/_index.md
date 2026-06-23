---
title: "ImageDevice.ImageGraphicContext klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.rendering.image.ImageDeviceImageGraphicContext klass. Innehåller aktuella grafikstyrningsparametrar för ImageDevice. Dessa parametrar definierar den globala ramen inom vilken grafikoperatorerna körs."
type: docs

url: /sv/java/com.aspose.html.rendering.image/imagedevice.imagegraphiccontext/
---
## ImageDevice.ImageGraphicContext class

Innehåller aktuella grafikstyrningsparametrar för [`ImageDevice`](../imagedevice/). Dessa parametrar definierar den globala ramen inom vilken grafikoperatorerna körs.

```java
public class ImageGraphicContext : GraphicContext
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [imageGraphicContext](../../com.aspose.html.rendering.image/imagedevice.imagegraphiccontext/.ctor)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Ställer in eller hämtar teckenavstånd. |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Ställer in eller hämtar penselobjektet som används för att fylla banornas innanmål. |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | Ställer in eller hämtar TrueType-typsnittobjektet som används för att rendera text. |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Ställer in eller hämtar texttypsnittsstorlek. |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Ställer in eller hämtar texttypsnittsstil. |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Ställer in eller hämtar koden som specificerar formen på ändpunkterna för alla öppna banor som strokas. |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Ställer in eller hämtar fasförskjutningen för det aktuella streckmönstret. |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Ställer in eller hämtar beskrivningen av streckmönstret som ska användas när banor strokas. |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Ställer in eller hämtar koden som specificerar formen på fogarna mellan anslutna segment av en strokad bana. |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Ställer in eller hämtar tjockleken på banor som ska strokas. |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Ställer in eller hämtar den maximala längden på snedställda linjefogar för strokade banor. Denna parameter begränsar längden på \"spikar\" som bildas när linjesegment möts i skarpa vinklar. |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Ställer in eller hämtar penselobjektet som används för strokade banor. |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) Hämtar ett [`TextInfo`](../../com.aspose.html.rendering/textinfo/)‑objekt som innehåller information om renderad text. |
| [transformationMatrix](../../com.aspose.html.rendering/graphiccontext/transformationmatrix/) { get; set; } | Ställer in eller hämtar transformationsmatris. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [clone](../../com.aspose.html.rendering/graphiccontext/clone/)() | Skapar en ny instans av en GraphicContext-klass med samma egenskapsvärden som en befintlig instans. |
| [transform](../../com.aspose.html.rendering/graphiccontext/transform/)(IMatrix) | Modifiera den aktuella transformationsmatrisen genom att multiplicera med den angivna matrisen. |

### Se även

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [ImageDevice](../imagedevice/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
