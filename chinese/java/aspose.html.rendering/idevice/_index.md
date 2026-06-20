---
title: "IDevice 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.rendering.IDevice 接口。定义支持自定义渲染路径、文本和图像等图形元素的方法和属性。"
type: docs

url: /zh/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

定义支持对路径、文本和图像等图形元素进行自定义渲染的方法和属性。

```java
public interface IDevice : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) 获取图形上下文。 |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) 获取渲染选项。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | 将矩形追加到当前路径，作为完整的子路径。 |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | 开始渲染文档。 |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | 开始渲染元素。 |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | 开始渲染新页面。 |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | 通过使用 FillRule 确定填充区域，将当前剪裁路径与当前路径相交来修改剪裁路径。此方法会终止当前路径。 |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | 通过从当前点到子路径起始点追加直线段来关闭当前子路径。如果当前子路径已经关闭，\"ClosePath\" 不执行任何操作。此操作符会终止当前子路径。向当前路径追加另一段会开始一个新子路径，即使新段的起点是由 \"ClosePath\" 方法达到的端点。 |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | 向当前路径追加三次 Bézier 曲线。该曲线从当前点延伸到点 pt3，使用 pt1 和 pt2 作为 Bézier 控制点。新的当前点为 pt3。 |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | 绘制指定的图像。 |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | 结束文档的渲染。 |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | 结束元素的渲染。 |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | 结束当前页面的渲染。 |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | 填充当前路径所围成的整个区域。如果路径由多个不相连的子路径组成，则会一起填充所有子路径的内部。此方法结束当前路径。 |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | 在指定位置填充指定的文本字符串。 |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | 将所有数据刷新到输出流。 |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | 在当前点到点 (pt) 之间追加一段直线段。新的当前点为 pt。 |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | 通过将当前点移动到参数 pt 的坐标来开始一个新的子路径，省略任何连接的线段。如果当前路径中的前一个路径构造方法也是 "MoveTo"，则新的 "MoveTo" 会覆盖它；路径中不再保留之前的 "MoveTo" 操作的痕迹。 |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | 通过从堆栈弹出，恢复整个图形上下文到先前的值。 |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | 将整个图形上下文的副本压入堆栈。 |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | 沿当前路径描边。描边线沿路径的每条直线或曲线段绘制，位于段的中心，两侧与段平行。路径的每个子路径分别处理。此方法结束当前路径。 |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | 描边并填充当前路径。此方法结束当前路径。 |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | 在指定位置描绘指定的文本字符串。 |

### 另请参见

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
