---
title: HtmlRenderer Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Rendering.HtmlRenderer class. Represents an HTML document renderer
type: docs
weight: 4300
url: /java/com.aspose.html.rendering/htmlrenderer/
---
## HtmlRenderer class

Represents an HTML document renderer.

```java
public class HtmlRenderer : Renderer<Document>
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlRenderer](htmlrenderer/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Document) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Document[]) |  |
| [render](../../com.aspose.html.rendering/htmlrenderer/render/#render_5)(IDevice, CancellationToken, params Document[]) | Defines a method for rendering multiple [`Document`](../../com.aspose.html.dom/document/)s into a specific [`IDevice`](../idevice/), using a cancellation token to request cancellation of the operation. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Document, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Document, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Document[]) |  |
| [render](../../com.aspose.html.rendering/htmlrenderer/render/#render_6)(IDevice, TimeSpan, params Document[]) | Defines method for rendering multiple [`Document`](../../com.aspose.html.dom/document/)s into specific [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |

### See Also

* class [Document](../../com.aspose.html.dom/document/)
* class [Renderer&lt;TDocument&gt;](../renderer-1/)
* package [com.aspose.html.Rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
