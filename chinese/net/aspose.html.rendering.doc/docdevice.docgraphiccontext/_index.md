---
title: Class DocDevice.DocGraphicContext
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Rendering.Doc.DocDeviceDocGraphicContext 班级. 保存 DocDevice 的当前图形控制参数 这些参数定义图形运算符执行的全局框架
type: docs
weight: 4180
url: /zh/net/aspose.html.rendering.doc/docdevice.docgraphiccontext/
---
## DocDevice.DocGraphicContext class

保存 DocDevice 的当前图形控制参数。 这些参数定义图形运算符执行的全局框架。

```csharp
public class DocGraphicContext : GraphicContext
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [DocGraphicContext](docgraphiccontext/)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | 设置或获取字符间距。 |
| virtual [FillBrush](../../aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | 设置或获取用于填充路径内部的画笔对象。 |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | 设置或获取用于呈现文本的真实字体对象。 |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | 设置或获取文本字体大小。 |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | 设置或获取文本字体样式。 |
| virtual [LineCap](../../aspose.html.rendering/graphiccontext/linecap/) { get; set; } | 设置或获取指定任何被描边的开放路径的端点形状的代码。 |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | 设置或获取当前虚线模式的相位偏移。 |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | 设置或获取描边路径时要使用的破折号模式的描述。 |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | Sets of 获取描边路径的虚线样式。 |
| virtual [LineJoin](../../aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | 设置或获取指定描边路径的连接段之间关节形状的代码。 |
| virtual [LineWidth](../../aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | 设置或获取要描边的路径的厚度。 |
| virtual [MiterLimit](../../aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | 设置或获取描边路径的斜接线连接的最大长度。 此参数限制线段以锐角连接时产生的“尖峰”长度。 |
| virtual [StrokeBrush](../../aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | 设置或获取用于描边路径的画笔对象。 |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | 得到一个[`TextInfo`](../../aspose.html.rendering/textinfo/)包含有关渲染文本信息的对象。 |
| override [TransformationMatrix](../../aspose.html.rendering.doc/docgraphiccontext/transformationmatrix/) { get; set; } | 设置或获取转换矩阵。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Clone](../../aspose.html.rendering.doc/docgraphiccontext/clone/)() | 创建一个新的实例[`GraphicContext`](../../aspose.html.rendering/graphiccontext/)与现有实例具有相同属性值的类。 |
| override [Transform](../../aspose.html.rendering.doc/docgraphiccontext/transform/)(Matrix) | 乘以指定矩阵修改当前变换矩阵 |

### 也可以看看

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [DocDevice](../docdevice/)
* 命名空间 [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* 部件 [Aspose.HTML](../../)


