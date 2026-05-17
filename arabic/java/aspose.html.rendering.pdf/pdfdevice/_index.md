---
title: "فئة PdfDevice"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "الفئة com.aspose.html.rendering.pdf.PdfDevice. تمثل التصيير إلى وثيقة PDF"
type: docs

url: /ar/java/com.aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

يمثل العرض إلى مستند PDF.

```java
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | ينشئ مثلاً جديداً من الفئة `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | ينشئ مثلاً جديداً من الفئة `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_5)(String) | ينشئ مثلاً جديداً من الفئة `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | ينشئ مثلاً جديداً من الفئة `PdfDevice` باستخدام خيارات التصيير ومزود التدفق. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | ينشئ مثلاً جديداً من الفئة `PdfDevice` باستخدام خيارات التصيير وتدفق الإخراج. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, String) | ينشئ مثلاً جديداً من الفئة `PdfDevice` باستخدام خيارات التصيير واسم ملف الإخراج. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## الطرق

| الاسم | الوصف |
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

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| class [PdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext) | تحتفظ بمعلمات التحكم الرسومية الحالية لجهاز PdfDevice. هذه المعلمات تحدد الإطار العام الذي تنفذ فيه عمليات الرسوميات. |

### انظر أيضًا

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
