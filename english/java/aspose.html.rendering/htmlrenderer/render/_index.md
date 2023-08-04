---
title: HtmlRenderer.Render
second_title: Aspose.HTML for Java API Reference
description: HtmlRenderer method. Defines method for rendering multiple Documents into specific IDevice. The rendering will be performed once there are no any network operations for loading resources active timers animation tasks or specified timeout is elapsed
type: docs
weight: 20
url: /java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Document[]) {#render_6}

Defines method for rendering multiple [`Document`](../../../com.aspose.html.dom/document/)s into specific [`IDevice`](../../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed.

```java
public void Render(IDevice device, TimeSpan timeout, params Document[] documents)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| timeout | TimeSpan | A TimeSpan that represents the number of milliseconds to wait, or a TimeSpan that represents -1 millisecond to wait indefinitely. |
| documents | Document[] | The documents to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [Document](../../../com.aspose.html.dom/document/)
* class [HtmlRenderer](../)
* package [com.aspose.html.Rendering](../../htmlrenderer/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Document[]) {#render_5}

Defines a method for rendering multiple [`Document`](../../../com.aspose.html.dom/document/)s into a specific [`IDevice`](../../idevice/), using a cancellation token to request cancellation of the operation.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Document[] documents)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| cancellationToken | CancellationToken | A CancellationToken to observe while waiting for the task to complete. |
| documents | Document[] | The documents to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [Document](../../../com.aspose.html.dom/document/)
* class [HtmlRenderer](../)
* package [com.aspose.html.Rendering](../../htmlrenderer/)
* package [Aspose.HTML](../../../)
