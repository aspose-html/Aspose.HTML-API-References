---
title: RendererTSource Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.Renderer1TSource class. The base abstract class for all renderers
type: docs
weight: 4710
url: /net/aspose.html.rendering/renderer-1/
---
## Renderer<TSource> class

The base abstract class for all renderers.

```csharp
public abstract class Renderer<TSource> : Renderer
```

| Parameter | Description |
| --- | --- |
| TSource | The type of the source. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.html.rendering/renderer/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_3)(*[IDevice](../idevice/), TSource*) | Defines method for rendering *TSource* into specified [`IDevice`](../idevice/). |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_6)(*[IDevice](../idevice/), params TSource[]*) | Defines method for rendering multiple *TSource*s into specific [`IDevice`](../idevice/). |
| abstract [Render](../../aspose.html.rendering/renderer-1/render/#render_1)(*[IDevice](../idevice/), CancellationToken, params TSource[]*) | Defines a method for rendering multiple *TSource*s into a specific [`IDevice`](../idevice/), using a cancellation token to request cancellation of the operation. |
| [Render](../../aspose.html.rendering/renderer-1/render/#render)(*[IDevice](../idevice/), int, params TSource[]*) | Defines method for rendering multiple *TSource*s into specific [`IDevice`](../idevice/). |
| abstract [Render](../../aspose.html.rendering/renderer-1/render/#render_2)(*[IDevice](../idevice/), TimeSpan, params TSource[]*) | Defines method for rendering multiple *TSource*s into specific [`IDevice`](../idevice/). |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_4)(*[IDevice](../idevice/), TSource, int*) | Defines method for rendering *TSource* into specified [`IDevice`](../idevice/). |
| [Render](../../aspose.html.rendering/renderer-1/render/#render_5)(*[IDevice](../idevice/), TSource, TimeSpan*) | Defines method for rendering *TSource* into specified [`IDevice`](../idevice/). |

### See Also

* class [Renderer](../renderer/)
* namespace [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../)
