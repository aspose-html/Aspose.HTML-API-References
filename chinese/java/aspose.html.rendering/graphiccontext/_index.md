---
title: "GraphicContext 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.rendering.GraphicContext 类。保存当前图形控制参数。这些参数定义了图形操作符执行的全局框架。"
type: docs

url: /zh/java/com.aspose.html.rendering/graphiccontext/
---
## GraphicContext class

保存当前图形控制参数。这些参数定义了图形操作符执行的全局框架。

```java
public class GraphicContext : ICloneable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GraphicContext](graphiccontext/)() | 初始化 `GraphicContext` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | 设置或获取字符间距。 |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | 设置或获取用于填充路径内部的画笔对象。 |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | 设置或获取用于渲染文本的 TrueType 字体对象。 |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | 设置或获取文本字体大小。 |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | 设置或获取文本字体样式。 |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | 设置或获取指定已描边的任意开放路径端点形状的代码。 |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | 设置或获取当前线段虚线模式的相位偏移。 |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | 设置或获取在路径描边时使用的虚线模式描述。 |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | 设置或获取指定已描边路径相连段之间接点形状的代码。 |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | 设置或获取要描边的路径粗细。 |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | 设置或获取已描边路径斜接线接合的最大长度。此参数限制线段在锐角相接时产生的“尖刺”长度。 |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | 设置或获取用于已描边路径的画笔对象。 |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) 获取一个包含渲染文本信息的 [`TextInfo`](../textinfo/) 对象。 |
| [transformationMatrix](../../com.aspose.html.rendering/graphiccontext/transformationmatrix/) { get; set; } | 设置或获取变换矩阵。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [clone](../../com.aspose.html.rendering/graphiccontext/clone/)() | 创建一个 GraphicContext 类的新实例，其属性值与现有实例相同。 |
| [transform](../../com.aspose.html.rendering/graphiccontext/transform/)(IMatrix) | 通过乘以指定矩阵来修改当前变换矩阵。 |

### 另请参见

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
