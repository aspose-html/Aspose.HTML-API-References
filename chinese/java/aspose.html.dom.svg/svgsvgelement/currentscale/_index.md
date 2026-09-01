---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGSVGElement 属性。对于最外层的 svg 元素，此属性指示相对于初始视图的当前缩放因子，以考虑用户放大和平移操作，如在 “Magnification and panning” 中所述。DOM 属性 currentScale 和 currentTranslate 等价于 2x3 矩阵 a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y。如果启用了放大（即 zoomAndPan=magnify），则效果相当于在 SVG 文档片段的最外层（即最外层 svg 元素之外）放置了一个额外的变换。当在不是最外层的 svg 元素上访问时，此属性的行为未定义。"
type: docs

url: /zh/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

在最外层的 svg 元素上，此属性指示相对于初始视图的当前缩放因子，以考虑用户放大和平移操作，如在 “Magnification and panning” 中所述。DOM 属性 currentScale 和 currentTranslate 等价于 2x3 矩阵 [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]。如果启用了 \"magnification\"（即 zoomAndPan=\"magnify\"），则效果相当于在 SVG 文档片段的最外层（即最外层 svg 元素之外）放置了一个额外的变换。当在不是最外层的 ‘svg’ 元素上访问时，此属性的行为未定义。

```java
public float CurrentScale { get; set; }
```

### Property Value

当前缩放。

### 另请参见

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
