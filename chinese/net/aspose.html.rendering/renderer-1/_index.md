---
title: RendererTDocument
second_title: Aspose.HTML for .NET API 参考
description: 表示所有渲染器的抽象类
type: docs
weight: 4560
url: /zh/net/aspose.html.rendering/renderer-1/
---
## Renderer&lt;TDocument&gt; class

表示所有渲染器的抽象类。

```csharp
public abstract class Renderer<TDocument> : Renderer
```

| 范围 | 描述 |
| --- | --- |
| TDocument | 文档的类型。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Dispose](../../aspose.html.rendering/renderer/dispose)() | 释放非托管和 - 可选 - 托管资源。 |
| [Render](../../aspose.html.rendering/renderer`1/render#render_2)(IDevice, TDocument) | 定义将!:TDocument渲染到指定[`IDevice`](../idevice)的方法。 |
| [Render](../../aspose.html.rendering/renderer`1/render#render_5)(IDevice, params TDocument[]) | 定义将多个!:TDocument渲染到特定:::R5:T:Aspose.Html.Rendering.IDevice::的方法:. |
| [Render](../../aspose.html.rendering/renderer`1/render#render)(IDevice, int, params TDocument[]) | 定义将多个!:TDocument渲染到特定:::R5:T:Aspose.Html.Rendering.IDevice::的方法:. 一旦没有任何用于加载资源、活动计时器、动画任务或指定超时的网络操作，将执行渲染。 |
| [Render](../../aspose.html.rendering/renderer`1/render#render_3)(IDevice, TDocument, int) | 定义将!:TDocument渲染到指定[`IDevice`](../idevice)的方法。 一旦没有任何用于加载资源、活动计时器、动画任务或指定超时的网络操作，将执行渲染。 |
| [Render](../../aspose.html.rendering/renderer`1/render#render_4)(IDevice, TDocument, TimeSpan) | 定义将!:TDocument渲染到指定[`IDevice`](../idevice)的方法。 一旦没有任何用于加载资源、活动计时器、动画任务或指定超时的网络操作，将执行渲染。 |
| abstract [Render](../../aspose.html.rendering/renderer`1/render#render_1)(IDevice, TimeSpan, params TDocument[]) | 定义将多个!:TDocument渲染到特定:::R5:T:Aspose.Html.Rendering.IDevice::的方法:. 一旦没有任何用于加载资源、活动计时器、动画任务或指定超时的网络操作，将执行渲染。 |

### 也可以看看

* class [Renderer](../renderer)
* 命名空间 [Aspose.Html.Rendering](../../aspose.html.rendering)
* 部件 [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->