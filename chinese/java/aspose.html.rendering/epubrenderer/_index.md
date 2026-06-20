---
title: "EpubRenderer 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.rendering.EpubRenderer 类。表示 EPub 文档渲染器"
type: docs

url: /zh/java/com.aspose.html.rendering/epubrenderer/
---
## EpubRenderer class

表示 EPub 文档渲染器。

```java
public class EpubRenderer : Renderer<Stream>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EpubRenderer](epubrenderer/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | 定义一个方法，将多个 EPub 文档渲染到特定的[`IDevice`](../idevice/)，并使用取消令牌请求取消操作。 |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | 将多个 EPub 文档渲染到指定的[`IDevice`](../idevice/)。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_4)(IDevice, Stream, Configuration) | 将 EPub 文档渲染到指定的[`IDevice`](../idevice/)。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | 定义方法，将多个 EPub 流渲染到特定的[`IDevice`](../idevice/)。渲染将在没有任何网络操作用于加载资源、活动计时器、动画任务或指定超时已到达时执行。 |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | 将多个 EPub 文档渲染到指定的[`IDevice`](../idevice/)。渲染将在没有任何网络操作用于加载资源、活动计时器、动画任务或指定超时已到达时执行。 |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | 将 EPub 文档渲染到指定的[`IDevice`](../idevice/)。渲染将在没有任何网络操作用于加载资源、活动计时器、动画任务或指定超时已到达时执行。 |

### 另请参见

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
