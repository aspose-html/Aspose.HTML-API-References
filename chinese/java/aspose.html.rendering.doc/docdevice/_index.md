---
title: "DocDevice 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.rendering.doc.DocDevice 类。表示渲染为 DOCX 文档"
type: docs

url: /zh/java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

表示渲染到 DOCX 文档。

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | 初始化 `DocDevice` 类的新实例。 |
| [DocDevice](docdevice/#constructor_4)(Stream) | 通过输出流初始化 `DocDevice` 类的新实例。 |
| [DocDevice](docdevice/#constructor_5)(String) | 通过输出文件名初始化 `DocDevice` 类的新实例。 |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | 通过渲染选项和流提供程序初始化 `DocDevice` 类的新实例。 |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | 通过渲染选项和输出流初始化 `DocDevice` 类的新实例。 |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | 通过渲染选项和输出文件名初始化 `DocDevice` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## 方法

| 名称 | 描述 |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | 将矩形追加到当前路径，作为完整的子路径。 |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | 开始渲染文档。 |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | 开始渲染 html 节点。 |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | 开始渲染新页面。 |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillRule) | 通过将当前裁剪路径与当前路径相交并使用 FillMode 规则确定填充区域来修改当前裁剪路径。此方法会终止当前路径。 |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | 通过从当前点到子路径起始点追加直线段来关闭当前子路径。如果当前子路径已经关闭，\"ClosePath\" 不执行任何操作。此操作符会终止当前子路径。向当前路径追加另一段会开始一个新子路径，即使新段的起点是由 \"ClosePath\" 方法达到的端点。 |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | 向当前路径追加三次 Bézier 曲线。该曲线从当前点延伸到点 pt2，使用 pt1 和 pt2 作为 Bézier 控制点。新的当前点为 pt3。 |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], WebImageFormat, RectangleF) | 绘制指定的图像。 |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | 结束渲染 html 节点。 |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | 结束当前页面的渲染。 |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillRule) | 填充当前路径所围成的整个区域。如果路径由多个不相连的子路径组成，则会一起填充所有子路径的内部。此方法结束当前路径。 |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | 在指定位置填充指定的文本字符串。 |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | 将所有数据刷新到输出流。 |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | 在当前点到点 (pt) 之间追加一段直线段。新的当前点为 pt。 |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | 通过将当前点移动到参数 pt 的坐标来开始一个新的子路径，省略任何连接的线段。如果当前路径中的前一个路径构造方法也是 "MoveTo"，则新的 "MoveTo" 会覆盖它；路径中不再保留之前的 "MoveTo" 操作的痕迹。 |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | 沿当前路径描边。描边线沿路径的每条直线或曲线段绘制，位于段的中心，两侧与段平行。路径的每个子路径分别处理。此方法结束当前路径。 |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillRule) | 描边并填充当前路径。此方法结束当前路径。 |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | 在指定位置描绘指定的文本字符串。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | 保存 DocDevice 的当前图形控制参数。这些参数定义了图形操作执行的全局框架。 |

### 另请参见

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
