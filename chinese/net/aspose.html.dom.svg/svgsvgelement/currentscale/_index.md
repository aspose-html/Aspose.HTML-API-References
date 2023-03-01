---
title: SVGSVGElement.CurrentScale
second_title: Aspose.HTML for .NET API 参考
description: SVGSVGElement 财产. 在最外层的 svg 元素上此属性指示当前相对于初始视图的比例因子以考虑用户放大和平移操作如放大和平移中所述 DOM 属性 currentScale 和 currentTranslate 相当于 2x3 矩阵 abcdef  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y如果启用放大即 zoomAndPanmagnify那么效果就像在 SVG 文档片段的最外层即最外层 svg 元素之外放置了一个额外的转换 访问时不是最外层 svg 元素的svg元素未定义此属性的行为
type: docs
weight: 10
url: /zh/net/aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

在最外层的 svg 元素上，此属性指示当前相对于初始视图的比例因子，以考虑用户放大和平移操作，如放大和平移中所述。 DOM 属性 currentScale 和 currentTranslate 相当于 2x3 矩阵 [abcdef] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]。如果启用“放大”（即 zoomAndPan="magnify"），那么效果就像在 SVG 文档片段的最外层（即最外层 svg 元素之外）放置了一个额外的转换。 访问时不是最外层 svg 元素的“svg”元素，未定义此属性的行为。

```csharp
public float CurrentScale { get; set; }
```

### 适当的价值

当前比例。

### 也可以看看

* class [SVGSVGElement](../)
* 命名空间 [Aspose.Html.Dom.Svg](../../svgsvgelement/)
* 部件 [Aspose.HTML](../../../)


