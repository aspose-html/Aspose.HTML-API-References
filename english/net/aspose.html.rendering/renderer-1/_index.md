---
title: RendererTDocument Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.Renderer1TDocument class. Represents an abstract class for the all renderers
type: docs
weight: 4650
url: /net/aspose.html.rendering/renderer-1/
---
## Renderer&lt;TDocument&gt; class

Represents an abstract class for the all renderers.

```csharp
public abstract class Renderer<TDocument> : Renderer
```

| Parameter | Description |
| --- | --- |
| TDocument | The type of the document. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.html.rendering/renderer/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TDocument) | Defines method for rendering !:TDocument into specified [`IDevice`](../idevice/). |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TDocument[]) |  |
| abstract [Render](../../aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TDocument[]) |  |
| [Render](../../aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TDocument[]) |  |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TDocument, int) | Defines method for rendering !:TDocument into specified [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TDocument, TimeSpan) | Defines method for rendering !:TDocument into specified [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |
| abstract [Render](../../aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TDocument[]) |  |

### See Also

* class [Renderer](../renderer/)
* namespace [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../)
