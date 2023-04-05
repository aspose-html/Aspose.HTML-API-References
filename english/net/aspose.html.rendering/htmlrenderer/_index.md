---
title: HtmlRenderer Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.HtmlRenderer class. Represents an HTML document renderer
type: docs
weight: 4280
url: /net/aspose.html.rendering/htmlrenderer/
---
## HtmlRenderer class

Represents an HTML document renderer.

```csharp
public class HtmlRenderer : Renderer<Document>
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlRenderer](htmlrenderer/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.html.rendering/renderer/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [Render](../../aspose.html.rendering/renderer-1/render/)(IDevice, Document) |  |
| [Render](../../aspose.html.rendering/renderer-1/render/)(IDevice, params Document[]) |  |
| override [Render](../../aspose.html.rendering/htmlrenderer/render/#render_5)(IDevice, CancellationToken, params Document[]) | Defines a method for rendering multiple [`Document`](../../aspose.html.dom/document/)s into a specific [`IDevice`](../idevice/), using a cancellation token to request cancellation of the operation. |
| [Render](../../aspose.html.rendering/renderer-1/render/)(IDevice, Document, int) |  |
| [Render](../../aspose.html.rendering/renderer-1/render/)(IDevice, Document, TimeSpan) |  |
| [Render](../../aspose.html.rendering/renderer-1/render/)(IDevice, int, params Document[]) |  |
| override [Render](../../aspose.html.rendering/htmlrenderer/render/#render_6)(IDevice, TimeSpan, params Document[]) | Defines method for rendering multiple [`Document`](../../aspose.html.dom/document/)s into specific [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |

### See Also

* class [Document](../../aspose.html.dom/document/)
* class [Renderer&lt;TDocument&gt;](../renderer-1/)
* namespace [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../)
