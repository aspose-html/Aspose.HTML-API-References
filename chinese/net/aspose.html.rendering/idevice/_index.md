---
title: Interface IDevice
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Rendering.IDevice 界面. 定义支持自定义呈现图形元素如路径文本和图像的方法和属性
type: docs
weight: 4280
url: /zh/net/aspose.html.rendering/idevice/
---
## IDevice interface

定义支持自定义呈现图形元素（如路径、文本和图像）的方法和属性。

```csharp
public interface IDevice : IDisposable
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/idevice/graphiccontext/) { get; } | 获取图形上下文。 |
| [Options](../../aspose.html.rendering/idevice/options/) { get; } | 获取渲染选项。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddRect](../../aspose.html.rendering/idevice/addrect/)(RectangleF) | 将一个矩形附加到当前路径作为一个完整的子路径。 |
| [BeginDocument](../../aspose.html.rendering/idevice/begindocument/)(Document) | 开始呈现文档。 |
| [BeginElement](../../aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | 开始渲染元素。 |
| [BeginPage](../../aspose.html.rendering/idevice/beginpage/)(SizeF) | 开始呈现新页面。 |
| [Clip](../../aspose.html.rendering/idevice/clip/)(FillMode) | 通过将当前路径与当前路径相交来修改当前剪切路径，使用 FillMode 规则来确定要填充的区域。 此方法终止当前路径。 |
| [ClosePath](../../aspose.html.rendering/idevice/closepath/)() | 通过从当前点到子路径起点附加一条直线段来关闭当前子路径。 如果当前子路径已经关闭，则“ClosePath”不执行任何操作。 此运算符终止当前子路径。将另一个段附加到当前路径开始一个新的子路径， ，即使新段开始于“ClosePath”方法到达的端点。 |
| [CubicBezierTo](../../aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | 将三次贝塞尔曲线附加到当前路径。曲线从当前点延伸到点 pt3, ，使用 pt1 和 pt2 作为贝塞尔控制点。新的当前点是 pt3. |
| [DrawImage](../../aspose.html.rendering/idevice/drawimage/)(byte[], ImageType, RectangleF) | 绘制指定图像。 |
| [EndDocument](../../aspose.html.rendering/idevice/enddocument/)() | 结束文档呈现。 |
| [EndElement](../../aspose.html.rendering/idevice/endelement/)(Element) | 结束元素的渲染。 |
| [EndPage](../../aspose.html.rendering/idevice/endpage/)() | 结束当前页面的渲染。 |
| [Fill](../../aspose.html.rendering/idevice/fill/)(FillMode) | 填充当前路径包围的整个区域。 如果路径由多个断开连接的子路径组成，则填充所有子路径的内部， 一起考虑。 此方法终止当前路径。 |
| [FillText](../../aspose.html.rendering/idevice/filltext/)(string, PointF) | 在指定位置填充指定的文本字符串。 |
| [Flush](../../aspose.html.rendering/idevice/flush/)() | 将所有数据刷新到输出流。 |
| [LineTo](../../aspose.html.rendering/idevice/lineto/)(PointF) | 从当前点到该点 (pt) 追加一条直线段。新的当前点是 pt. |
| [MoveTo](../../aspose.html.rendering/idevice/moveto/)(PointF) | 通过将当前点移动到参数 pt 的坐标开始新的子路径，省略任何连接线段。 如果当前路径中之前的路径构造方法也是“MoveTo”，则新的“MoveTo”覆盖它； 路径中没有先前“MoveTo”操作的痕迹。 |
| [RestoreGraphicContext](../../aspose.html.rendering/idevice/restoregraphiccontext/)() | 通过从堆栈中弹出它来将整个图形上下文恢复到它以前的值。 |
| [SaveGraphicContext](../../aspose.html.rendering/idevice/savegraphiccontext/)() | 将整个图形上下文的副本推送到堆栈上。 |
| [Stroke](../../aspose.html.rendering/idevice/stroke/)() | 沿当前路径画一条线。描边线跟随路径中的每个直线或曲线段， 以线段为中心，边与其平行。路径的每个子路径都被单独处理。 此方法终止当前路径。 |
| [StrokeAndFill](../../aspose.html.rendering/idevice/strokeandfill/)(FillMode) | 描边并填充当前路径。 此方法终止当前路径。 |
| [StrokeText](../../aspose.html.rendering/idevice/stroketext/)(string, PointF) | 在指定位置描边指定的文本字符串。 |

### 也可以看看

* 命名空间 [Aspose.Html.Rendering](../../aspose.html.rendering/)
* 部件 [Aspose.HTML](../../)


