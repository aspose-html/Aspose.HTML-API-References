---
title: HtmlRenderer.Render
second_title: Aspose.HTML for .NET API Reference
description: HtmlRenderer Render method. Defines method for rendering multiple HTMLDocuments into specific IDevice
type: docs
weight: 20
url: /net/aspose.html.rendering/htmlrenderer/render/
---
## Render(*[IDevice](../../idevice/), TimeSpan, params HTMLDocument[]*) {#render_6}

Defines method for rendering multiple [`HTMLDocument`](../../../aspose.html/htmldocument/)s into specific [`IDevice`](../../idevice/).

```csharp
public override void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| timeout | TimeSpan | A TimeSpan that represents the number of milliseconds to wait, or a TimeSpan that represents -1 millisecond to wait indefinitely. |
| sources | HTMLDocument[] | The HTML documents to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* namespace [Aspose.Html.Rendering](../../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params HTMLDocument[]*) {#render_5}

Defines a method for rendering multiple [`HTMLDocument`](../../../aspose.html/htmldocument/)s into a specific [`IDevice`](../../idevice/), using a cancellation token to request cancellation of the operation.

```csharp
public override void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| cancellationToken | CancellationToken | A CancellationToken to observe while waiting for the task to complete. |
| sources | HTMLDocument[] | The HTML documents to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* namespace [Aspose.Html.Rendering](../../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../../)
