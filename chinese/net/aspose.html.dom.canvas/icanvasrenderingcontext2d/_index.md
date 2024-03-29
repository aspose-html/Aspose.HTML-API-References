---
title: Interface ICanvasRenderingContext2D
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Canvas.ICanvasRenderingContext2D 界面. ICanvasRenderingContext2D 接口用于将矩形文本图像和其他对象绘制到画布元素上它为画布元素的绘图表面提供 2D 渲染上下文
type: docs
weight: 260
url: /zh/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

ICanvasRenderingContext2D 接口用于将矩形、文本、图像和其他对象绘制到画布元素上。它为画布元素的绘图表面提供 2D 渲染上下文。

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) { get; } | 对 HTMLCanvasElement 的只读反向引用。如果它不与画布元素关联，则可能为空。 |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle/) { get; set; } | 内部形状使用的颜色或样式。默认值：（黑色）. |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha/) { get; set; } | 在将形状和图像合成到画布上之前应用于它们的 Alpha 值。默认 1.0（不透明）. |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation/) { get; set; } | 应用 globalAlpha 后，设置如何将形状和图像绘制到现有位图上。默认值：(source-over) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled/) { get; set; } | 图像平滑模式；如果禁用，图像将不会在缩放时平滑。 |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur/) { get; set; } | 指定模糊效果。默认 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor/) { get; set; } | 阴影的颜色。默认全透明黑色. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx/) { get; set; } | 阴影将偏移的水平距离。默认 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety/) { get; set; } | 阴影将偏移的垂直距离。默认 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle/) { get; set; } | 形状周围的线条使用的颜色或样式。默认值：（黑色）. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;string, string&gt;) | 将点击区域添加到画布。 这使您可以更轻松地进行命中检测，让您将事件路由到 DOM 元素， 并使用户可以在不看到画布的情况下探索画布。 |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | 通过清空子路径列表开始一条新路径。当你想创建一个新的路径时调用这个方法。 |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | 从画布中删除所有命中区域。 |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | 将由起点 (x, y) 和大小 (width, height) 定义的矩形中的所有像素设置为透明黑色，擦除任何先前绘制的内容。 |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | 通过计算当前裁剪区域和路径所描述的区域的交集，使用非零绕数规则来创建一个新的裁剪区域。 Open subpaths must be implicitly closed when computing the clipping region, without affect the actual subpaths . 新的剪辑区域替换当前剪辑区域。 |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | 通过使用非零缠绕数规则计算当前裁剪区域与路径描述的区域的交集来创建新的裁剪区域。 Open subpaths must be implicitly closed when computing the clipping region, without affect the actual subpaths. new clipping region replaces the current clipping region. 计算裁剪区域时必须隐式关闭，而不影响实际子路径。 |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | 通过使用非零缠绕数规则计算当前裁剪区域与路径描述的区域的交集来创建新的裁剪区域。 Open subpaths must be implicitly closed when computing the clipping region, without affect the actual subpaths. new clipping region replaces the current clipping region. 计算裁剪区域时必须隐式关闭，而不影响实际子路径。 |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | 创建具有指定尺寸的新的空白 ImageData 对象。 新对象中的所有像素都是透明的黑色。 |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | 创建具有指定尺寸的新的空白 ImageData 对象。 新对象中的所有像素都是透明的黑色。 |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | 沿着由参数表示的坐标给定的线创建线性渐变。 |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, string) | 使用指定图像（CanvasImageSource）创建图案。 它按照重复参数指定的方向重复源。 |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, string) | 使用指定图像（CanvasImageSource）创建图案。 它按照重复参数指定的方向重复源。 |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | 创建由参数表示的两个圆的坐标给定的径向渐变。 |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | 如果给定元素获得焦点，此方法会在当前路径周围绘制一个焦点环。 |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | 绘制指定图像。 |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | 绘制指定图像。 |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | 绘制指定图像。 |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | 绘制指定图像。 |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | 绘制指定图像。 |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | 绘制指定图像。 |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | 使用当前填充样式和默认算法填充子路径 CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | 用当前填充样式填充子路径。 |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | 使用当前填充样式和默认算法填充子路径 CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | 用当前填充样式填充子路径。 |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | 在(x, y) 位置绘制一个填充矩形，其大小由宽度和高度决定。 |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(string, double, double) | 在给定的 (x,y) 位置绘制（填充）给定的文本。 |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(string, double, double, double) | 在给定的 (x,y) 位置绘制（填充）给定的文本。 |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | 返回一个 ImageData 对象，表示由矩形表示的画布区域的基础像素数据，该矩形从 (sx, sy) 开始并具有 sw 宽度和 sh 高度。 此方法不受画布变换矩阵的影响。 |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | 报告指定点是否包含在当前路径中。 |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | 报告指定点是否包含在当前路径中。 |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | 报告指定点是否包含在当前路径中。 |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | 报告指定点是否包含在当前路径中。 |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | 报告指定点是否在路径描边所包含的区域内。 |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | 报告指定点是否在路径描边所包含的区域内。 |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(string) | 返回一个 TextMetrics 对象。 |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | 将给定 ImageData 对象的数据绘制到位图上。 如果提供了脏矩形，则仅绘制该矩形的像素。 该方法不受画布变换矩阵的影响。 |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | 将给定 ImageData 对象的数据绘制到位图上。 如果提供了脏矩形，则仅绘制该矩形的像素。 该方法不受画布变换矩阵的影响。 |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(string) | 从画布中删除具有指定 id 的命中区域。 |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | 通过单位矩阵重置当前变换。 |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | 将绘图样式状态恢复为由 save() 保存的“状态堆栈”中的最后一个元素。 |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | 向变换矩阵添加旋转。 angle参数表示顺时针旋转的角度，单位为弧度。 |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | 使用堆栈保存当前绘图样式状态，以便您可以使用 restore() 恢复对其所做的任何更改。 |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | 以水平 x 和垂直 y 向画布单位添加缩放转换。 |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | 将当前转换重置为单位矩阵，然后使用相同的参数调用 transform() 方法。 |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | 使用当前笔划样式对子路径进行笔划。 |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | 使用当前笔划样式对子路径进行笔划。 |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | 在画布上绘制一个起点为 (x, y)、宽度为 w、高度为 h 的矩形，使用当前笔划样式。 |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(string, double, double) | 在给定的 (x, y) 位置绘制（描边）给定的文本。 |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(string, double, double, double?) | 在给定的 (x, y) 位置绘制（描边）给定的文本。 |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | 将当前变换矩阵与其参数描述的矩阵相乘。 |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | 通过在网格上水平移动画布及其原点 x 和垂直移动 y 来添加平移转换。 |

### 也可以看看

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* 命名空间 [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* 部件 [Aspose.HTML](../../)


