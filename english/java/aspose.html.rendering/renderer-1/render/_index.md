---
title: Renderer-1.Render
second_title: Aspose.HTML for Java API Reference
description: Renderer method. Defines method for rendering TDocument into specified IDevice
type: docs
weight: 10
url: /net/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TDocument) {#render_3}

Defines method for rendering !:TDocument into specified [`IDevice`](../../idevice/).

```java
public void Render(IDevice device, TDocument document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| document | TDocument | The document. |

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TDocument&gt;](../)
* package [com.aspose.html.Rendering](../../renderer-1/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TDocument, TimeSpan) {#render_5}

Defines method for rendering !:TDocument into specified [`IDevice`](../../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed.

```java
public void Render(IDevice device, TDocument document, TimeSpan timeout)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| document | TDocument | The document. |
| timeout | TimeSpan | A TimeSpan that represents the number of milliseconds to wait, or a TimeSpan that represents -1 millisecond to wait indefinitely. |

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TDocument&gt;](../)
* package [com.aspose.html.Rendering](../../renderer-1/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TDocument, int) {#render_4}

Defines method for rendering !:TDocument into specified [`IDevice`](../../idevice/). The rendering will be performed once there are no any network operations for loading resources, active timers, animation tasks or specified timeout is elapsed.

```java
public void Render(IDevice device, TDocument document, int timeout)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| document | TDocument | The document. |
| timeout | Int32 | A number of milliseconds that represents the number of milliseconds to wait, or -1 millisecond to wait indefinitely. |

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TDocument&gt;](../)
* package [com.aspose.html.Rendering](../../renderer-1/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TDocument[]) {#render_6}

```java
public void Render(IDevice device, params TDocument[] documents)
```

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TDocument&gt;](../)
* package [com.aspose.html.Rendering](../../renderer-1/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TDocument[]) {#render}

```java
public void Render(IDevice device, int timeout, params TDocument[] documents)
```

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TDocument&gt;](../)
* package [com.aspose.html.Rendering](../../renderer-1/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TDocument[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TDocument[] documents)
```

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TDocument&gt;](../)
* package [com.aspose.html.Rendering](../../renderer-1/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params TDocument[]) {#render_1}

```java
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TDocument[] documents)
```

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TDocument&gt;](../)
* package [com.aspose.html.Rendering](../../renderer-1/)
* package [Aspose.HTML](../../../)
