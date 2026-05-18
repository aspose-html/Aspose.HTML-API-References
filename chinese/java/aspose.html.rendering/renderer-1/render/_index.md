---
title: "Renderer-1.Render"
second_title: "Aspose.HTML for Java API 参考"
description: "渲染器方法。定义将 TDocument 渲染到指定 IDevice 的方法"
type: docs

url: /zh/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

定义将 !:TDocument 渲染到指定的[`IDevice`](../../idevice/)的方法。

```java
public void Render(IDevice device, TSource source)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| 文档 | TSource | 文档。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

定义将 !:TDocument 渲染到指定的[`IDevice`](../../idevice/)的方法。渲染将在没有任何加载资源的网络操作、活动计时器、动画任务或指定超时已到期时执行。

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| 文档 | TSource | 文档。 |
| 超时 | TimeSpan | 一个 TimeSpan，表示要等待的毫秒数，或表示 -1 毫秒以无限期等待的 TimeSpan。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

定义将 !:TDocument 渲染到指定的[`IDevice`](../../idevice/)的方法。渲染将在没有任何加载资源的网络操作、活动计时器、动画任务或指定超时已到期时执行。

```java
public void Render(IDevice device, TSource source, int timeout)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| 文档 | TSource | 文档。 |
| 超时 | Int32 | 一个毫秒数，表示要等待的毫秒数，或 -1 毫秒以无限期等待。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params TSource[]) {#render_1}

```java
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
