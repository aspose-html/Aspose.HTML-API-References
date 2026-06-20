---
title: "RendererTSource 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.rendering.Renderer1TSource 类。表示所有渲染器的抽象类。"
type: docs

url: /zh/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

表示所有渲染器的抽象类。

```java
public abstract class Renderer<TSource> : Renderer
```

| 参数 | 描述 |
| --- | --- |
| TDocument | 文档的类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | 定义用于将 !:TDocument 渲染到指定的 [`IDevice`](../idevice/) 的方法。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | 定义用于将 !:TDocument 渲染到指定的 [`IDevice`](../idevice/) 的方法。渲染将在没有任何网络操作用于加载资源、活动计时器、动画任务或指定超时已到达时执行。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | 定义用于将 !:TDocument 渲染到指定的 [`IDevice`](../idevice/) 的方法。渲染将在没有任何网络操作用于加载资源、活动计时器、动画任务或指定超时已到达时执行。 |

### 另请参见

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
