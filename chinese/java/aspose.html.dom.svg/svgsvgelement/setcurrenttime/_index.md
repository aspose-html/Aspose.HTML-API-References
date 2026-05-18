---
title: "SVGSVGElement.SetCurrentTime"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGSVGElement 方法。调整此 SVG 文档片段的时钟，以建立新的当前时间。如果在文档时间线开始之前调用 setCurrentTime，例如在 script 元素中的脚本在文档的 SVGLoad 事件分发之前运行，则该方法最后一次调用时的 seconds 参数值即为文档时间线开始后将要跳转到的时间。"
type: docs

url: /zh/java/com.aspose.html.dom.svg/svgsvgelement/setcurrenttime/
---
## SVGSVGElement.SetCurrentTime method

调整此 SVG 文档片段的时钟，建立新的当前时间。如果在文档时间线开始之前调用 setCurrentTime（例如，在文档的 SVGLoad 事件分发之前，由 ‘script’ 元素中的脚本运行），则该方法最后一次调用中的秒数值表示文档时间线开始后文档将要跳转的时间。

```java
public void SetCurrentTime(float seconds)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 秒 | 单精度浮点数 | 相对于当前 SVG 文档片段的开始时间的新当前时间（单位为秒）。 |

### 另请参阅

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
