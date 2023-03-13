---
title: EpubRenderer.Render
second_title: Aspose.HTML for .NET API 参考
description: EpubRenderer 方法. 定义渲染多个 EPub 的方法Streams具体化IDevice . 一旦没有任何用于加载资源活动计时器动画任务的网络操作或指定的超时已过将执行渲染
type: docs
weight: 20
url: /zh/net/aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_9}

定义渲染多个 EPub 的方法Streams具体化[`IDevice`](../../idevice/) . 一旦没有任何用于加载资源、活动计时器、动画任务的网络操作或指定的超时已过，将执行渲染。

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Stream[] documents)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| device | IDevice | 输出设备。 |
| timeout | TimeSpan | ATimeSpan表示要等待的毫秒数，或者TimeSpan表示 -1 毫秒无限期等待。 |
| documents | Stream[] | 要呈现的文档。 |

### 也可以看看

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* 命名空间 [Aspose.Html.Rendering](../../epubrenderer/)
* 部件 [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

将 EPub 文档渲染到指定的位置[`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, Stream document, Configuration configuration)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| device | IDevice | 装置。 |
| document | Stream | 文档。 |
| configuration | Configuration | 配置。 |

### 也可以看看

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* 命名空间 [Aspose.Html.Rendering](../../epubrenderer/)
* 部件 [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

将 EPub 文档渲染到指定的位置[`IDevice`](../../idevice/) . 一旦没有任何用于加载资源、活动计时器、动画任务的网络操作或指定的超时已过，将执行渲染。

```csharp
public void Render(IDevice device, Stream document, Configuration configuration, TimeSpan timeout)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| device | IDevice | 装置。 |
| document | Stream | 文档。 |
| configuration | Configuration | 配置。 |
| timeout | TimeSpan | ATimeSpan表示要等待的毫秒数，或者TimeSpan表示 -1 毫秒无限期等待。 |

### 也可以看看

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* 命名空间 [Aspose.Html.Rendering](../../epubrenderer/)
* 部件 [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

将多个 EPub 文档渲染到指定的位置[`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| device | IDevice | 装置。 |
| documents | IList`1 | 这IList要呈现的文档。 |
| configuration | Configuration | 配置。 |

### 也可以看看

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* 命名空间 [Aspose.Html.Rendering](../../epubrenderer/)
* 部件 [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

将多个 EPub 文档渲染到指定的位置[`IDevice`](../../idevice/) . 一旦没有任何用于加载资源、活动计时器、动画任务的网络操作或指定的超时已过，将执行渲染。

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration, 
    TimeSpan timeout)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| device | IDevice | 装置。 |
| documents | IList`1 | 这IList要呈现的文档。 |
| configuration | Configuration | 配置。 |
| timeout | TimeSpan | ATimeSpan表示要等待的毫秒数，或者TimeSpan表示 -1 毫秒无限期等待。 |

### 也可以看看

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* 命名空间 [Aspose.Html.Rendering](../../epubrenderer/)
* 部件 [Aspose.HTML](../../../)


