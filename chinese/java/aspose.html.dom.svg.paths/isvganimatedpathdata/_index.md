---
title: "ISVGAnimatedPathData 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData 接口。SVGAnimatedPathData 接口支持具有 d 属性（保存 SVG 路径数据）的元素，并支持对该属性进行动画化的能力"
type: docs

url: /zh/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

SVGAnimatedPathData 接口支持具有 ‘d’ 属性的元素，该属性保存 SVG 路径数据，并支持对该属性进行动画化。

```java
public interface ISVGAnimatedPathData
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) 提供对 ‘d’ 属性当前动画内容的访问，形式与 SVG 语法一一对应。如果给定的属性或属性正在动画化，则包含该属性或属性的当前动画值，且对象本身及其内容均为只读。如果给定的属性或属性当前未动画化，则包含与 pathSegList 相同的值。 |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) 提供对 ‘d’ 属性基础（即静态）内容的访问，形式与 SVG 语法一一对应。因此，如果 ‘d’ 属性包含一个“绝对移动 (M)”和一个“绝对弧线 (A)”命令，则 pathSegList 将有两个条目：SVG_PATHSEG_MOVETO_ABS 和 SVG_PATHSEG_ARC_ABS。 |

### 另请参阅

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
