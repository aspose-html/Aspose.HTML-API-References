---
title: Interface ISVGAnimatedPathData
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Svg.Paths.ISVGAnimatedPathData 界面. SVGAnimatedPathData 接口支持具有保存 SVG 路径数据的d属性的元素并支持为该属性设置动画的能力
type: docs
weight: 1680
url: /zh/net/aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

SVGAnimatedPathData 接口支持具有保存 SVG 路径数据的“d”属性的元素，并支持为该属性设置动画的能力。

```csharp
public interface ISVGAnimatedPathData
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AnimatedPathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | 以与 SVG 语法一对一匹配的形式提供对“d”属性的当前动画内容的访问。如果给定的属性或属性正在动画，则包含属性或属性的当前动画值，并且对象本身及其内容都是只读的。如果给定的属性或属性当前未进行动画处理，则包含与 pathSegList. 相同的值 |
| [PathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | 以与 SVG 语法一对一匹配的形式提供对“d”属性的基本（即静态）内容的访问。 因此，如果“d”属性具有“绝对移动 (M)”和“绝对弧转 (A)”命令，则 pathSegList 将具有两个条目：SVG_PATHSEG_MOVETO_ABS 和 SVG_PATHSEG_ARC_ABS。 |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* 部件 [Aspose.HTML](../../)


