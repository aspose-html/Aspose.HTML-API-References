---
title: MhtmlRenderer Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Rendering.MhtmlRenderer class. Represents a MHTML document renderer
type: docs
weight: 4400
url: /net/com.aspose.html.rendering/mhtmlrenderer/
---
## MhtmlRenderer class

Represents a MHTML document renderer.

```java
public class MhtmlRenderer : Renderer<Stream>
```

## Constructors

| Name | Description |
| --- | --- |
| [MhtmlRenderer](mhtmlrenderer/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | Defines a method for rendering multiple MHTML documents into a specific [`IDevice`](../idevice/), using a cancellation token to request cancellation of the operation. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | Renders multiple MHTML documents into specified [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_4)(IDevice, Stream, Configuration) | Renders MHTML document into specified [`IDevice`](../idevice/). |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | Renders multiple MHTML documents into specified [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | Renders multiple MHTML documents into specified [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | Renders MHTML document into specified [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |

### See Also

* class [Renderer&lt;TDocument&gt;](../renderer-1/)
* package [com.aspose.html.Rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
