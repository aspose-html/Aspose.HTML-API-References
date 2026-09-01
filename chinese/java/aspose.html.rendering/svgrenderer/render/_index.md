---
title: "SvgRenderer.Render"
second_title: "Aspose.HTML for Java API 参考"
description: "SvgRenderer 方法。 定义用于将多个 SVGDocuments 渲染到特定 IDevice 的方法。 渲染将在没有任何网络操作用于加载资源、活动计时器、动画任务或指定超时已到达时执行。"
type: docs

url: /zh/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

定义用于将多个 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s 渲染到特定 [`IDevice`](../../idevice/) 的方法。 渲染将在没有任何网络操作用于加载资源、活动计时器、动画任务或指定超时已到达时执行。

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| timeout | TimeSpan | 一个 TimeSpan，表示要等待的毫秒数，或表示 -1 毫秒以无限期等待的 TimeSpan。 |
| 文档 | SVGDocument[] | 要渲染的文档。 |

### 另请参见

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

定义一种方法，用于将多个 [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s 渲染到特定 [`IDevice`](../../idevice/)，并使用取消令牌来请求取消该操作。

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| cancellationToken | CancellationToken | 在等待任务完成期间要观察的取消令牌。 |
| 源 | SVGDocument[] | 要渲染的 SVG 文档。 |

### 另请参见

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
