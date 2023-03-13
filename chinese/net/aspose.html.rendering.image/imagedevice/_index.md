---
title: Class ImageDevice
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Rendering.Image.ImageDevice 班级. 表示渲染为光栅格式jpegpngbmpgiftiff
type: docs
weight: 4300
url: /zh/net/aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

表示渲染为光栅格式：jpeg、png、bmp、gif、tiff。

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | 初始化一个新的实例`ImageDevice`类. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | 初始化一个新的实例`ImageDevice`类. |
| [ImageDevice](imagedevice/#constructor_5)(string) | 初始化一个新的实例`ImageDevice`类. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | 初始化一个新的实例`ImageDevice`按渲染选项和流提供程序分类。 |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | 初始化一个新的实例`ImageDevice`按渲染选项和输出流分类。 |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, string) | 初始化一个新的实例`ImageDevice`按渲染选项和输出文件名分类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| virtual [Graphics](../../aspose.html.rendering.image/imagedevice/graphics/) { get; } | 获取 Graphics 的实例。 |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.image/imagedevice/addrect/)(RectangleF) | 将一个矩形附加到当前路径作为一个完整的子路径。 |
| override [BeginDocument](../../aspose.html.rendering.image/imagedevice/begindocument/)(Document) | 开始呈现文档。 |
| override [BeginElement](../../aspose.html.rendering.image/imagedevice/beginelement/)(Element, RectangleF) | 开始渲染元素。 |
| override [BeginPage](../../aspose.html.rendering.image/imagedevice/beginpage/)(SizeF) | 开始呈现新页面。 |
| override [Clip](../../aspose.html.rendering.image/imagedevice/clip/)(FillMode) | 通过将当前路径与当前路径相交来修改当前剪切路径，使用 FillMode 规则来确定要填充的区域。 此方法终止当前路径。 |
| override [ClosePath](../../aspose.html.rendering.image/imagedevice/closepath/)() | 通过从当前点到子路径起点附加一条直线段来关闭当前子路径。 如果当前子路径已经关闭，则“ClosePath”不执行任何操作。 此运算符终止当前子路径。将另一个段附加到当前路径开始一个新的子路径， ，即使新段开始于“ClosePath”方法到达的端点。 |
| override [CubicBezierTo](../../aspose.html.rendering.image/imagedevice/cubicbezierto/)(PointF, PointF, PointF) | 将三次贝塞尔曲线附加到当前路径。曲线从当前点延伸到点 pt2, ，使用 pt1 和 pt2 作为贝塞尔控制点。新的当前点是 pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.image/imagedevice/drawimage/)(byte[], ImageType, RectangleF) | 绘制指定图像。 |
| override [EndDocument](../../aspose.html.rendering.image/imagedevice/enddocument/)() | 结束文档呈现。 |
| override [EndElement](../../aspose.html.rendering.image/imagedevice/endelement/)(Element) | 结束元素的渲染。 |
| override [EndPage](../../aspose.html.rendering.image/imagedevice/endpage/)() | 结束当前页面的渲染。 |
| override [Fill](../../aspose.html.rendering.image/imagedevice/fill/)(FillMode) | 填充当前路径包围的整个区域。 如果路径由多个断开连接的子路径组成，则填充所有子路径的内部， 一起考虑。 此方法终止当前路径。 |
| override [FillText](../../aspose.html.rendering.image/imagedevice/filltext/)(string, PointF) | 在指定位置填充指定的文本字符串。 |
| override [Flush](../../aspose.html.rendering.image/imagedevice/flush/)() | 将所有数据刷新到输出流。 |
| override [LineTo](../../aspose.html.rendering.image/imagedevice/lineto/)(PointF) | 从当前点到该点 (pt) 追加一条直线段。新的当前点是 pt. |
| override [MoveTo](../../aspose.html.rendering.image/imagedevice/moveto/)(PointF) | 通过将当前点移动到参数 pt 的坐标开始新的子路径，省略任何连接线段。 如果当前路径中之前的路径构造方法也是“MoveTo”，则新的“MoveTo”覆盖它； 路径中没有先前“MoveTo”操作的痕迹。 |
| override [RestoreGraphicContext](../../aspose.html.rendering.image/imagedevice/restoregraphiccontext/)() | 通过从堆栈中弹出它来将整个图形上下文恢复到它以前的值。 |
| override [SaveGraphicContext](../../aspose.html.rendering.image/imagedevice/savegraphiccontext/)() | 将整个图形上下文的副本推送到堆栈上。 |
| override [Stroke](../../aspose.html.rendering.image/imagedevice/stroke/)() | 沿当前路径画一条线。描边线跟随路径中的每个直线或曲线段， 以线段为中心，边与其平行。路径的每个子路径都被单独处理。 此方法终止当前路径。 |
| override [StrokeAndFill](../../aspose.html.rendering.image/imagedevice/strokeandfill/)(FillMode) | 描边并填充当前路径。 此方法终止当前路径。 |
| override [StrokeText](../../aspose.html.rendering.image/imagedevice/stroketext/)(string, PointF) | 在指定位置描边指定的文本字符串。 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| class [ImageGraphicContext](imagedevice.imagegraphiccontext/) | 保存当前图形控制参数`ImageDevice`. 这些参数定义图形运算符执行的全局框架。 |

### 也可以看看

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* 命名空间 [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* 部件 [Aspose.HTML](../../)


