---
title: "EpubRenderer klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.rendering.EpubRenderer class. Representerar en EPub-dokumentrenderare"
type: docs

url: /sv/java/com.aspose.html.rendering/epubrenderer/
---
## EpubRenderer class

Representerar en EPub‑dokumentrenderare.

```java
public class EpubRenderer : Renderer<Stream>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EpubRenderer](epubrenderer/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | Definierar en metod för att rendera flera EPub-dokument till en specifik [`IDevice`](../idevice/), med en avbokningstoken för att begära avbrytning av operationen. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | Renderar flera EPub-dokument till angivet [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_4)(IDevice, Stream, Configuration) | Renderar EPub-dokument till angivet [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | Definierar metod för att rendera flera EPub-strömmar till en specifik [`IDevice`](../idevice/). Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationsuppgifter eller när angiven tidsgräns har löpt ut. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | Renderar flera EPub-dokument till angivet [`IDevice`](../idevice/). Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationsuppgifter eller när angiven tidsgräns har löpt ut. |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | Renderar EPub-dokument till angivet [`IDevice`](../idevice/). Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationsuppgifter eller när angiven tidsgräns har löpt ut. |

### Se även

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
