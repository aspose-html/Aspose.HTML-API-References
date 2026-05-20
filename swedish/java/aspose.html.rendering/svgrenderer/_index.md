---
title: "SvgRenderer‑klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.rendering.SvgRenderer-klass. Representerar en SVG-dokumentrenderare"
type: docs

url: /sv/java/com.aspose.html.rendering/svgrenderer/
---
## SvgRenderer class

Representerar en SVG‑dokumentrenderare.

```java
public class SvgRenderer : Renderer<SVGDocument>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SvgRenderer](svgrenderer/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_5)(IDevice, CancellationToken, params SVGDocument[]) | Definierar en metod för att rendera flera [`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/)s till en specifik [`IDevice`](../idevice/), med en avbrytningstoken för att begära avbrytning av operationen. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_6)(IDevice, TimeSpan, params SVGDocument[]) | Definierar en metod för att rendera flera [`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/)s till en specifik [`IDevice`](../idevice/). Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationsuppgifter eller när den angivna tidsgränsen har löpt ut. |

### Se även

* class [SVGDocument](../../com.aspose.html.dom.svg/svgdocument/)
* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
