---
title: Class DocDevice
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Rendering.Doc.DocDevice 班级. 表示渲染到DOCX文档
type: docs
weight: 4170
url: /zh/net/aspose.html.rendering.doc/docdevice/
---
## DocDevice class

表示渲染到DOCX文档。

```csharp
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | 初始化一个新的实例`DocDevice`类. |
| [DocDevice](docdevice/#constructor_4)(Stream) | 初始化一个新的实例`DocDevice`按输出流分类. |
| [DocDevice](docdevice/#constructor_5)(string) | 初始化一个新的实例`DocDevice`按输出文件名分类. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | 初始化一个新的实例`DocDevice`按渲染选项和流提供程序分类。 |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | 初始化一个新的实例`DocDevice`通过渲染选项和输出流进行分类。 |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, string) | 初始化一个新的实例`DocDevice`按渲染选项和输出文件名分类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | 将一个矩形附加到当前路径作为一个完整的子路径。 |
| override [BeginDocument](../../aspose.html.rendering.doc/docdevice/begindocument/)(Document) | 开始呈现文档。 |
| override [BeginElement](../../aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | 开始呈现 html 节点。 |
| override [BeginPage](../../aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | 开始呈现新页面。 |
| override [Clip](../../aspose.html.rendering.doc/docdevice/clip/)(FillMode) | 通过将当前路径与当前路径相交来修改当前剪切路径，使用 FillMode 规则来确定要填充的区域。 此方法终止当前路径。 |
| override [ClosePath](../../aspose.html.rendering.doc/docdevice/closepath/)() | 通过从当前点到子路径起点附加一条直线段来关闭当前子路径。 如果当前子路径已经关闭，则“ClosePath”不执行任何操作。 此运算符终止当前子路径。将另一个段附加到当前路径开始一个新的子路径， ，即使新段开始于“ClosePath”方法到达的端点。 |
| override [CubicBezierTo](../../aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | 将三次贝塞尔曲线附加到当前路径。曲线从当前点延伸到点 pt2, ，使用 pt1 和 pt2 作为贝塞尔控制点。新的当前点是 pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.doc/docdevice/drawimage/)(byte[], ImageType, RectangleF) | 绘制指定图像。 |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.doc/docdevice/endelement/)(Element) | 结束 html 节点的渲染。 |
| override [EndPage](../../aspose.html.rendering.doc/docdevice/endpage/)() | 结束当前页面的渲染。 |
| override [Fill](../../aspose.html.rendering.doc/docdevice/fill/)(FillMode) | 填充当前路径包围的整个区域。 如果路径由多个断开连接的子路径组成，则填充所有子路径的内部， 一起考虑。 此方法终止当前路径。 |
| override [FillText](../../aspose.html.rendering.doc/docdevice/filltext/)(string, PointF) | 在指定位置填充指定的文本字符串。 |
| override [Flush](../../aspose.html.rendering.doc/docdevice/flush/)() | 将所有数据刷新到输出流。 |
| override [LineTo](../../aspose.html.rendering.doc/docdevice/lineto/)(PointF) | 从当前点到该点 (pt) 追加一条直线段。新的当前点是 pt. |
| override [MoveTo](../../aspose.html.rendering.doc/docdevice/moveto/)(PointF) | 通过将当前点移动到参数 pt 的坐标开始新的子路径，省略任何连接线段。 如果当前路径中之前的路径构造方法也是“MoveTo”，则新的“MoveTo”覆盖它； 路径中没有先前“MoveTo”操作的痕迹。 |
| override [RestoreGraphicContext](../../aspose.html.rendering.doc/docdevice/restoregraphiccontext/)() | 通过从堆栈中弹出它来将整个图形上下文恢复到它以前的值。 |
| override [SaveGraphicContext](../../aspose.html.rendering.doc/docdevice/savegraphiccontext/)() | 将整个图形上下文的副本推送到堆栈上。 |
| override [Stroke](../../aspose.html.rendering.doc/docdevice/stroke/)() | 沿当前路径画一条线。描边线跟随路径中的每个直线或曲线段， 以线段为中心，边与其平行。路径的每个子路径都被单独处理。 此方法终止当前路径。 |
| override [StrokeAndFill](../../aspose.html.rendering.doc/docdevice/strokeandfill/)(FillMode) | 描边并填充当前路径。 此方法终止当前路径。 |
| override [StrokeText](../../aspose.html.rendering.doc/docdevice/stroketext/)(string, PointF) | 在指定位置描边指定的文本字符串。 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| class [DocGraphicContext](docdevice.docgraphiccontext/) | 保存 DocDevice 的当前图形控制参数。 这些参数定义图形运算符执行的全局框架。 |

### 也可以看看

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* 命名空间 [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* 部件 [Aspose.HTML](../../)


