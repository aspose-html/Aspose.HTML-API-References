---
title: RendererTSource Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.Renderer1TSource class. Represents an abstract class for the all renderers
type: docs
weight: 4700
url: /net/aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

Represents an abstract class for the all renderers.

```csharp
public abstract class Renderer<TSource> : Renderer
```

| Parameter | Description |
| --- | --- |
| TDocument | The type of the document. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.html.rendering/renderer/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_3)(*[IDevice](../idevice/), TSource*) | Defines method for rendering !:TDocument into specified [`IDevice`](../idevice/). |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_6)(*[IDevice](../idevice/), params TSource[]*) |  |
| abstract [Render](../../aspose.html.rendering/renderer-1/render/#render_1)(*[IDevice](../idevice/), CancellationToken, params TSource[]*) |  |
| [Render](../../aspose.html.rendering/renderer-1/render/#render)(*[IDevice](../idevice/), int, params TSource[]*) |  |
| abstract [Render](../../aspose.html.rendering/renderer-1/render/#render_2)(*[IDevice](../idevice/), TimeSpan, params TSource[]*) |  |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_4)(*[IDevice](../idevice/), TSource, int*) | Defines method for rendering !:TDocument into specified [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_5)(*[IDevice](../idevice/), TSource, TimeSpan*) | Defines method for rendering !:TDocument into specified [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |

### See Also

* class [Renderer](../renderer/)
* namespace [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../)
