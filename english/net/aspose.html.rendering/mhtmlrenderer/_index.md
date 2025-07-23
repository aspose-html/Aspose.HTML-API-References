---
title: MhtmlRenderer Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.MhtmlRenderer class. Represents a MHTML document renderer
type: docs
weight: 4580
url: /net/aspose.html.rendering/mhtmlrenderer/
---
## MhtmlRenderer class

Represents a MHTML document renderer.

```csharp
public class MhtmlRenderer : Renderer<Stream>
```

## Constructors

| Name | Description |
| --- | --- |
| [MhtmlRenderer](mhtmlrenderer/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.html.rendering/renderer/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [Render](../../aspose.html.rendering/renderer-1/render/)(*[IDevice](../idevice/), Stream*) |  |
| [Render](../../aspose.html.rendering/renderer-1/render/)(*[IDevice](../idevice/), params Stream[]*) |  |
| override [Render](../../aspose.html.rendering/mhtmlrenderer/render/#render_9)(*[IDevice](../idevice/), CancellationToken, params Stream[]*) | Defines a method for rendering multiple MHTML documents into a specific [`IDevice`](../idevice/), using a cancellation token to request cancellation of the operation. |
| [Render](../../aspose.html.rendering/mhtmlrenderer/render/#render_1)(*[IDevice](../idevice/), IList&lt;Stream&gt;, [Configuration](../../aspose.html/configuration/)*) | Renders multiple MHTML documents into specified [`IDevice`](../idevice/). |
| [Render](../../aspose.html.rendering/renderer-1/render/)(*[IDevice](../idevice/), int, params Stream[]*) |  |
| [Render](../../aspose.html.rendering/mhtmlrenderer/render/#render_4)(*[IDevice](../idevice/), Stream, [Configuration](../../aspose.html/configuration/)*) | Renders MHTML document into specified [`IDevice`](../idevice/). |
| [Render](../../aspose.html.rendering/renderer-1/render/)(*[IDevice](../idevice/), Stream, int*) |  |
| [Render](../../aspose.html.rendering/renderer-1/render/)(*[IDevice](../idevice/), Stream, TimeSpan*) |  |
| override [Render](../../aspose.html.rendering/mhtmlrenderer/render/#render_10)(*[IDevice](../idevice/), TimeSpan, params Stream[]*) | Renders multiple MHTML documents into specified [`IDevice`](../idevice/). |
| [Render](../../aspose.html.rendering/mhtmlrenderer/render/#render_2)(*[IDevice](../idevice/), IList&lt;Stream&gt;, [Configuration](../../aspose.html/configuration/), TimeSpan*) | Renders multiple MHTML documents into specified [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |
| [Render](../../aspose.html.rendering/mhtmlrenderer/render/#render_5)(*[IDevice](../idevice/), Stream, [Configuration](../../aspose.html/configuration/), TimeSpan*) | Renders MHTML document into specified [`IDevice`](../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed. |

### See Also

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* namespace [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../)
