---
title: "HtmlRenderer.Render"
second_title: "Aspose.HTML for Java API 参考"
description: "HtmlRenderer 方法。定义将多个 HTMLDocument 渲染到特定 IDevice 的方法"
type: docs

url: /zh/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

定义将多个[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 渲染到特定[`IDevice`](../../idevice/) 的方法。

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| 超时 | TimeSpan | 一个 TimeSpan，表示要等待的毫秒数，或表示 -1 毫秒以无限期等待的 TimeSpan。 |
| 源 | HTMLDocument[] | 要渲染的 HTML 文档。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

定义一种方法，将多个[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 渲染到特定[`IDevice`](../../idevice/)，并使用取消令牌请求取消操作。

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| cancellationToken | CancellationToken | 用于在等待任务完成时观察的 CancellationToken。 |
| 源 | HTMLDocument[] | 要渲染的 HTML 文档。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
