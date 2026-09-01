---
title: "RendererTSource klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.rendering.Renderer1TSource klass. Representerar en abstrakt klass för alla renderare"
type: docs

url: /sv/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

Representerar en abstrakt klass för alla renderare.

```java
public abstract class Renderer<TSource> : Renderer
```

| Parameter | Beskrivning |
| --- | --- |
| TDocument | Typen av dokumentet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | Definierar metod för att rendera !:TDocument till angiven [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | Definierar metod för att rendera !:TDocument till angiven [`IDevice`](../idevice/). Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationer eller när angiven tidsgräns har löpt ut. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | Definierar metod för att rendera !:TDocument till angiven [`IDevice`](../idevice/). Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animationer eller när angiven tidsgräns har löpt ut. |

### Se även

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
