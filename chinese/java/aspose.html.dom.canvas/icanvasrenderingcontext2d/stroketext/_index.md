---
title: "ICanvasRenderingContext2D.StrokeText"
second_title: "Aspose.HTML for Java API 参考"
description: "ICanvasRenderingContext2D 方法。在给定的 x y 位置绘制给定文本的描边。"
type: docs

url: /zh/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/
---
## StrokeText(String, double, double) {#stroketext}

在给定的 (x, y) 位置绘制（描边）指定文本。

```java
public void StrokeText(String text, double x, double y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 使用当前字体、textAlign、textBaseline 和 direction 值绘制的文本。 |
| x | Double | 文本起始点的 x 轴坐标。 |
| y | Double | 文本起始点的 y 轴坐标。 |

### 另请参见

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## StrokeText(String, double, double, double?) {#stroketext_1}

在给定的 (x, y) 位置绘制（描边）指定文本。

```java
public void StrokeText(String text, double x, double y, double? maxWidth)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 使用当前字体、textAlign、textBaseline 和 direction 值绘制的文本。 |
| x | Double | 文本起始点的 x 轴坐标。 |
| y | Double | 文本起始点的 y 轴坐标。 |
| maxWidth | Nullable`1 | 绘制的最大宽度。如果指定且字符串计算后宽于此宽度，则会调整字体，使用更水平压缩的字体（如果有可用的，或通过水平缩放当前字体合成出可读的字体）或更小的字体。 |

### 另请参见

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
