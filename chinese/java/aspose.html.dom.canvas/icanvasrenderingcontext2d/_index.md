---
title: "ICanvasRenderingContext2D 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.canvas.ICanvasRenderingContext2D 接口。ICanvasRenderingContext2D 接口用于在 canvas 元素上绘制矩形、文本、图像和其他对象。它为 canvas 元素的绘图表面提供 2D 渲染上下文。"
type: docs

url: /zh/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

ICanvasRenderingContext2D 接口用于在 canvas 元素上绘制矩形、文本、图像和其他对象。它为 canvas 元素的绘图表面提供 2D 渲染上下文。

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) 只读的对 HTMLCanvasElement 的回溯引用。如果未关联到 canvas 元素，可能为 null。 |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## 方法

| 名称 | 描述 |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | 通过清空子路径列表开始一个新路径。当您想创建新路径时调用此方法。 |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | 从 canvas 中移除所有点击区域。 |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | 将由起始点 (x, y) 和尺寸 (width, height) 定义的矩形中的所有像素设置为透明黑色，擦除任何先前绘制的内容。 |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | 通过计算当前裁剪区域与路径描述的区域的交集（使用非零环绕数规则）创建新的裁剪区域。在计算裁剪区域时，必须隐式闭合开放的子路径，但不影响实际的子路径。新的裁剪区域将替代当前裁剪区域。 |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | 通过计算当前裁剪区域与路径描述的区域的交集（使用非零环绕数规则）创建新的裁剪区域。在计算裁剪区域时，必须隐式闭合开放的子路径，但不影响实际的子路径。新的裁剪区域将替代当前裁剪区域。 |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | 通过计算当前裁剪区域与路径描述的区域的交集（使用非零环绕数规则）创建新的裁剪区域。在计算裁剪区域时，必须隐式闭合开放的子路径，但不影响实际的子路径。新的裁剪区域将替代当前裁剪区域。 |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | 创建一个具有指定尺寸的全新空白 ImageData 对象。新对象中的所有像素均为透明黑色。 |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | 创建一个具有指定尺寸的全新空白 ImageData 对象。新对象中的所有像素均为透明黑色。 |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | 沿参数表示的坐标线创建线性渐变。 |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | 使用指定的图像（CanvasImageSource）创建图案。它按照 repetition 参数指定的方向重复源图像。 |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | 使用指定的图像（CanvasImageSource）创建图案。它按照 repetition 参数指定的方向重复源图像。 |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | 根据参数表示的两个圆的坐标创建径向渐变。 |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | 如果给定元素获得焦点，此方法将在当前路径周围绘制焦点环。 |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | 绘制指定的图像。 |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | 绘制指定的图像。 |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | 绘制指定的图像。 |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | 绘制指定的图像。 |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | 绘制指定的图像。 |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | 绘制指定的图像。 |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | 使用当前填充样式和默认算法 CanvasFillRule.Nonzero 填充子路径。 |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | 使用当前填充样式填充子路径。 |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | 使用当前填充样式和默认算法 CanvasFillRule.Nonzero 填充子路径。 |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | 使用当前填充样式填充子路径。 |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | 在 (x, y) 位置绘制一个填充矩形，其大小由宽度和高度决定。 |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | 在给定的 (x,y) 位置绘制（填充）指定文本。 |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | 在给定的 (x,y) 位置绘制（填充）指定文本。 |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | 返回一个 ImageData 对象，表示由矩形指定的画布区域的底层像素数据，该矩形起始于 (sx, sy)，宽度为 sw，高度为 sh。此方法不受画布变换矩阵的影响。 |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | 报告指定点是否包含在当前路径中。 |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | 报告指定点是否包含在当前路径中。 |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | 报告指定点是否包含在当前路径中。 |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | 报告指定点是否包含在当前路径中。 |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | 报告指定点是否位于路径描边所包含的区域内。 |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | 报告指定点是否位于路径描边所包含的区域内。 |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | 返回一个 TextMetrics 对象。 |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | 将给定 ImageData 对象的数据绘制到位图上。如果提供了脏矩形，则仅绘制该矩形中的像素。此方法不受画布变换矩阵的影响。 |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | 将给定 ImageData 对象的数据绘制到位图上。如果提供了脏矩形，则仅绘制该矩形中的像素。此方法不受画布变换矩阵的影响。 |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | 从画布中移除具有指定 id 的点击区域。 |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | 使用单位矩阵重置当前变换。 |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | 将绘图样式状态恢复到由 save() 保存的“状态栈”中的最后一个元素。 |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | 向变换矩阵添加旋转。angle 参数表示顺时针旋转角度，单位为弧度。 |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | 使用栈保存当前绘图样式状态，以便您可以通过 restore() 恢复对其所做的任何更改。 |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | 在水平上按 x、垂直上按 y 为画布单位添加缩放变换。 |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | 将当前变换重置为单位矩阵，然后使用相同的参数调用 transform() 方法。 |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | 使用当前描边样式描绘子路径。 |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | 使用当前描边样式描绘子路径。 |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | 使用当前描边样式在画布上绘制一个矩形，其起始点为 (x, y)，宽度为 w，高度为 h。 |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | 在给定的 (x, y) 位置绘制（描边）指定文本。 |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | 在给定的 (x, y) 位置绘制（描边）指定文本。 |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | 将当前变换矩阵与其参数描述的矩阵相乘。 |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | 通过在网格上水平移动画布及其原点 x，垂直移动 y，添加平移变换。 |

### 另请参阅

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
