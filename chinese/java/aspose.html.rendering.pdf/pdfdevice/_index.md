---
title: "PdfDevice 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.rendering.pdf.PdfDevice 类。表示渲染到 PDF 文档"
type: docs

url: /zh/java/com.aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

表示渲染为 PDF 文档。

```java
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | 初始化 `PdfDevice` 类的新实例。 |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | 初始化 `PdfDevice` 类的新实例。 |
| [PdfDevice](pdfdevice/#constructor_5)(String) | 初始化 `PdfDevice` 类的新实例。 |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | 通过渲染选项和流提供程序初始化 `PdfDevice` 类的新实例。 |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | 通过渲染选项和输出流初始化 `PdfDevice` 类的新实例。 |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, String) | 通过渲染选项和输出文件名初始化 `PdfDevice` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## 方法

| 名称 | 描述 |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) |  |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) |  |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) |  |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) |  |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) |  |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() |  |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) |  |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) |  |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) |  |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() |  |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) |  |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) |  |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() |  |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) |  |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) |  |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() |  |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) |  |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) |  |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| class [PdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext) | 保存 PdfDevice 的当前图形控制参数。这些参数定义了图形操作符执行的全局框架。 |

### 另请参见

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
