---
title: RendererTSource Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.rendering.Renderer1TSource class. Represents an abstract class for the all renderers
type: docs

url: /java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

Represents an abstract class for the all renderers.

```java
public abstract class Renderer<TSource> : Renderer
```

| Parameter | Description |
| --- | --- |
| TDocument | The type of the document. |

## Methods

| Name | Description |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | Defines method for rendering !:TDocument into specified [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | Defines method for rendering !:TDocument into specified [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | Defines method for rendering !:TDocument into specified [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |

### See Also

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
