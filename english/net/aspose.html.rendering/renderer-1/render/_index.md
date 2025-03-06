---
title: Renderer-1.Render
second_title: Aspose.HTML for .NET API Reference
description: Renderer Render method. Defines method for rendering TDocument into specified IDevice
type: docs
weight: 10
url: /net/aspose.html.rendering/renderer-1/render/
---
## Render(*[IDevice](../../idevice/), TSource*) {#render_3}

Defines method for rendering !:TDocument into specified [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| document | TSource | The document. |

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Html.Rendering](../../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, TimeSpan*) {#render_5}

Defines method for rendering !:TDocument into specified [`IDevice`](../../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed.

```csharp
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| document | TSource | The document. |
| timeout | TimeSpan | A TimeSpan that represents the number of milliseconds to wait, or a TimeSpan that represents -1 millisecond to wait indefinitely. |

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Html.Rendering](../../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, int*) {#render_4}

Defines method for rendering !:TDocument into specified [`IDevice`](../../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed.

```csharp
public void Render(IDevice device, TSource source, int timeout)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| document | TSource | The document. |
| timeout | Int32 | A number of milliseconds that represents the number of milliseconds to wait, or -1 millisecond to wait indefinitely. |

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Html.Rendering](../../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../../)

---

## Render(*[IDevice](../../idevice/), params TSource[]*) {#render_6}

```csharp
public void Render(IDevice device, params TSource[] sources)
```

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Html.Rendering](../../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../../)

---

## Render(*[IDevice](../../idevice/), int, params TSource[]*) {#render}

```csharp
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Html.Rendering](../../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../../)

---

## Render(*[IDevice](../../idevice/), TimeSpan, params TSource[]*) {#render_2}

```csharp
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Html.Rendering](../../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params TSource[]*) {#render_1}

```csharp
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Html.Rendering](../../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../../)
