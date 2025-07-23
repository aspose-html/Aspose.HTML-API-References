---
title: SvgRenderer.Render
second_title: Aspose.HTML for .NET API Reference
description: SvgRenderer Render method. Defines method for rendering multiple SVGDocuments into specific IDevice
type: docs
weight: 20
url: /net/aspose.html.rendering/svgrenderer/render/
---
## Render(*[IDevice](../../idevice/), TimeSpan, params SVGDocument[]*) {#render_6}

Defines method for rendering multiple [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument/)s into specific [`IDevice`](../../idevice/).

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| timeout | TimeSpan | A TimeSpan that represents the number of milliseconds to wait, or a TimeSpan that represents -1 millisecond to wait indefinitely. |
| sources | SVGDocument[] | The SVG documents to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Html.Rendering](../../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params SVGDocument[]*) {#render_5}

Defines a method for rendering multiple [`SVGDocument`](../../../aspose.html.dom.svg/svgdocument/)s into a specific [`IDevice`](../../idevice/), using a cancellation token to request cancellation of the operation.

```csharp
public override void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |
| sources | SVGDocument[] | The SVG documents to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Html.Rendering](../../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../../)
