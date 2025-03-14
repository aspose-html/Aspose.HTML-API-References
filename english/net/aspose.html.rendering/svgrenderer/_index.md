---
title: SvgRenderer Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.SvgRenderer class. Represents SVG document renderer
type: docs
weight: 4740
url: /net/aspose.html.rendering/svgrenderer/
---
## SvgRenderer class

Represents SVG document renderer.

```csharp
public class SvgRenderer : Renderer<SVGDocument>
```

## Public Members
## Constructors

| Name | Description |
| --- | --- |
| [SvgRenderer](svgrenderer/)() | The default constructor. |

## Public Members
## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.html.rendering/renderer/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [Render](../../aspose.html.rendering/renderer-1/render/)(*[IDevice](../idevice/), [SVGDocument](../../aspose.html.dom.svg/svgdocument/)*) |  |
| [Render](../../aspose.html.rendering/renderer-1/render/)(*[IDevice](../idevice/), params SVGDocument[]*) |  |
| override [Render](../../aspose.html.rendering/svgrenderer/render/#render_5)(*[IDevice](../idevice/), CancellationToken, params SVGDocument[]*) | Defines a method for rendering multiple [`SVGDocument`](../../aspose.html.dom.svg/svgdocument/)s into a specific [`IDevice`](../idevice/), using a cancellation token to request cancellation of the operation. |
| [Render](../../aspose.html.rendering/renderer-1/render/)(*[IDevice](../idevice/), int, params SVGDocument[]*) |  |
| [Render](../../aspose.html.rendering/renderer-1/render/)(*[IDevice](../idevice/), [SVGDocument](../../aspose.html.dom.svg/svgdocument/), int*) |  |
| [Render](../../aspose.html.rendering/renderer-1/render/)(*[IDevice](../idevice/), [SVGDocument](../../aspose.html.dom.svg/svgdocument/), TimeSpan*) |  |
| override [Render](../../aspose.html.rendering/svgrenderer/render/#render_6)(*[IDevice](../idevice/), TimeSpan, params SVGDocument[]*) | Defines method for rendering multiple [`SVGDocument`](../../aspose.html.dom.svg/svgdocument/)s into specific [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |

### See Also

* class [SVGDocument](../../aspose.html.dom.svg/svgdocument/)
* class [Renderer&lt;TSource&gt;](../renderer-1/)
* namespace [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../)
