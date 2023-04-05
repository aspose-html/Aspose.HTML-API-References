---
title: MhtmlRenderer.Render
second_title: Aspose.HTML for .NET API Reference
description: MhtmlRenderer method. Renders multiple MHTML documents into specified IDevice. The rendering will be performed once there are no any network operations for loading resources active timers animation tasks or specified timeout is elapsed
type: docs
weight: 20
url: /net/aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Renders multiple MHTML documents into specified [`IDevice`](../../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Stream[] documents)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The device. |
| timeout | TimeSpan | A TimeSpan that represents the number of milliseconds to wait, or a TimeSpan that represents -1 millisecond to wait indefinitely. |
| documents | Stream[] | The documents to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* namespace [Aspose.Html.Rendering](../../mhtmlrenderer/)
* assembly [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Defines a method for rendering multiple MHTML documents into a specific [`IDevice`](../../idevice/), using a cancellation token to request cancellation of the operation.

```csharp
public override void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] documents)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| cancellationToken | CancellationToken | A CancellationToken to observe while waiting for the task to complete. |
| documents | Stream[] | The documents to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* namespace [Aspose.Html.Rendering](../../mhtmlrenderer/)
* assembly [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Renders MHTML document into specified [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, Stream document, Configuration configuration)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The device. |
| document | Stream | The document. |
| configuration | Configuration | The configuration. |

### See Also

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [MhtmlRenderer](../)
* namespace [Aspose.Html.Rendering](../../mhtmlrenderer/)
* assembly [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Renders MHTML document into specified [`IDevice`](../../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed.

```csharp
public void Render(IDevice device, Stream document, Configuration configuration, TimeSpan timeout)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The device. |
| document | Stream | The document. |
| configuration | Configuration | The configuration. |
| timeout | TimeSpan | A TimeSpan that represents the number of milliseconds to wait, or a TimeSpan that represents -1 millisecond to wait indefinitely. |

### See Also

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [MhtmlRenderer](../)
* namespace [Aspose.Html.Rendering](../../mhtmlrenderer/)
* assembly [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Renders multiple MHTML documents into specified [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The device. |
| documents | IList`1 | The IList of documents to render. |
| configuration | Configuration | The configuration. |

### See Also

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [MhtmlRenderer](../)
* namespace [Aspose.Html.Rendering](../../mhtmlrenderer/)
* assembly [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Renders multiple MHTML documents into specified [`IDevice`](../../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed.

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration, 
    TimeSpan timeout)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The device. |
| documents | IList`1 | The IList of documents to render. |
| configuration | Configuration | The configuration. |
| timeout | TimeSpan | A TimeSpan that represents the number of milliseconds to wait, or a TimeSpan that represents -1 millisecond to wait indefinitely. |

### See Also

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [MhtmlRenderer](../)
* namespace [Aspose.Html.Rendering](../../mhtmlrenderer/)
* assembly [Aspose.HTML](../../../)
