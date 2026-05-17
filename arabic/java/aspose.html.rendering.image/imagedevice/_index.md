---
title: "ImageDevice فئة"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "com.aspose.html.rendering.image.ImageDevice class. تمثّل عملية التصيير إلى صيغ الراستر jpeg png bmp gif tiff"
type: docs

url: /ar/java/com.aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

تمثل التصيير إلى صيغ نقطية: jpeg، png، bmp، gif، tiff.

```java
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | ينشئ مثيلًا جديدًا للفئة `ImageDevice`. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | ينشئ مثيلًا جديدًا للفئة `ImageDevice`. |
| [ImageDevice](imagedevice/#constructor_5)(String) | ينشئ مثيلًا جديدًا للفئة `ImageDevice`. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | يُنشئ مثيلاً جديدًا لفئة `ImageDevice` باستخدام خيارات التصيير ومزود الدفق. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | يُنشئ مثيلاً جديدًا لفئة `ImageDevice` باستخدام خيارات التصيير وتدفق الإخراج. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, String) | يُنشئ مثيلاً جديدًا لفئة `ImageDevice` باستخدام خيارات التصيير واسم ملف الإخراج. |

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
| class [ImageGraphicContext](../../com.aspose.html.rendering.image/imagedevice.imagegraphiccontext) | يحتفظ بمعلمات التحكم الرسومية الحالية لـ `ImageDevice`. تُحدد هذه المعلمات الإطار العام الذي تُنفّذ فيه عمليات الرسوميات. |

### انظر أيضًا

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
