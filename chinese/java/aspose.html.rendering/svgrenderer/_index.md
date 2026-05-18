---
title: "SvgRenderer 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.rendering.SvgRenderer 类。表示 SVG 文档渲染器。"
type: docs

url: /zh/java/com.aspose.html.rendering/svgrenderer/
---
## SvgRenderer class

表示 SVG 文档渲染器。

```java
public class SvgRenderer : Renderer<SVGDocument>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SvgRenderer](svgrenderer/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_5)(IDevice, CancellationToken, params SVGDocument[]) | 定义一个方法，用于将多个[`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/)渲染到特定的[`IDevice`](../idevice/)，使用取消令牌来请求取消操作。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_6)(IDevice, TimeSpan, params SVGDocument[]) | 定义方法，将多个[`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/)渲染到特定的[`IDevice`](../idevice/)。渲染将在没有任何加载资源的网络操作、活动计时器、动画任务或指定超时已到期时执行。 |

### 另请参阅

* class [SVGDocument](../../com.aspose.html.dom.svg/svgdocument/)
* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
