---
title: SvgRenderer.Render
second_title: Aspose.HTML for Java API Reference
description: SvgRenderer method. Defines method for rendering multiple SVGDocuments into specific IDevice. The rendering will be performed once there are no any network operations for loading resources active timers animation tasks or specified timeout is elapsed
type: docs
weight: 20
url: /java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

Defines method for rendering multiple [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s into specific [`IDevice`](../../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed.

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] documents)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| timeout | TimeSpan | A TimeSpan that represents the number of milliseconds to wait, or a TimeSpan that represents -1 millisecond to wait indefinitely. |
| documents | SVGDocument[] | The documents to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../svgrenderer/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

Defines a method for rendering multiple [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s into a specific [`IDevice`](../../idevice/), using a cancellation token to request cancellation of the operation.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] documents)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |
| documents | SVGDocument[] | The documents to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../svgrenderer/)
* package [Aspose.HTML](../../../)
