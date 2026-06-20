---
title: "MhtmlRenderer.Render"
second_title: "Aspose.HTML for Java API 参考"
description: "MhtmlRenderer 方法。将多个 MHTML 文档渲染到指定的 IDevice。渲染将在没有任何加载资源的网络操作、活动计时器、动画任务或指定超时已到期时执行。"
type: docs

url: /zh/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

将多个 MHTML 文档渲染到指定的[`IDevice`](../../idevice/)。渲染将在没有任何加载资源的网络操作、活动计时器、动画任务或指定超时已到期时执行。

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 设备。 |
| timeout | TimeSpan | 一个 TimeSpan，表示要等待的毫秒数，或表示 -1 毫秒以无限期等待的 TimeSpan。 |
| 文档 | Stream[] | 要渲染的文档。 |

### 另请参见

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

定义一个方法，用于将多个 MHTML 文档渲染到特定的 [`IDevice`](../../idevice/)，并使用取消令牌请求取消操作。

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| cancellationToken | CancellationToken | 在等待任务完成期间观察的 CancellationToken。 |
| 源 | Stream[] | 要渲染的 MHTML 文档。 |

### 另请参见

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

将 MHTML 文档渲染到指定的 [`IDevice`](../../idevice/)。

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 设备。 |
| 文档 | 流 | 文档。 |
| 配置 | 配置 | 配置。 |

### 另请参见

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

将 MHTML 文档渲染到指定的 [`IDevice`](../../idevice/)。渲染将在没有任何用于加载资源的网络操作、活动计时器、动画任务，或在指定超时已到达时执行。

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 设备。 |
| 文档 | 流 | 文档。 |
| 配置 | 配置 | 配置。 |
| timeout | TimeSpan | 一个 TimeSpan，表示要等待的毫秒数，或表示 -1 毫秒以无限期等待的 TimeSpan。 |

### 另请参见

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

将多个 MHTML 文档渲染到指定的 [`IDevice`](../../idevice/)。

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 设备。 |
| 文档 | IList`1 | 要渲染的文档 IList。 |
| 配置 | 配置 | 配置。 |

### 另请参见

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

将多个 MHTML 文档渲染到指定的[`IDevice`](../../idevice/)。渲染将在没有任何加载资源的网络操作、活动计时器、动画任务或指定超时已到期时执行。

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 设备。 |
| 文档 | IList`1 | 要渲染的文档 IList。 |
| 配置 | 配置 | 配置。 |
| timeout | TimeSpan | 一个 TimeSpan，表示要等待的毫秒数，或表示 -1 毫秒以无限期等待的 TimeSpan。 |

### 另请参见

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
