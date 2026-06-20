---
title: "فئة XpsDevice"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.rendering.xps.XpsDevice. تمثل عملية العرض إلى مستند xps"
type: docs

url: /ar/java/com.aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

يمثل العرض إلى مستند xps.

```java
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | يُنشئ مثيلًا جديدًا من الفئة `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | يُنشئ مثيلًا جديدًا من الفئة `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_5)(String) | يُنشئ مثيلًا جديدًا من الفئة `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | يُنشئ مثيلًا جديدًا من الفئة `XpsDevice` باستخدام خيارات العرض ومزود التدفق. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | يُنشئ مثيلًا جديدًا من الفئة `XpsDevice` باستخدام خيارات العرض وتدفق الإخراج. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, String) | يُنشئ مثيلًا جديدًا من الفئة `XpsDevice` باستخدام خيارات العرض واسم ملف الإخراج. |

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
| class [XpsGraphicContext](../../com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext) | يحتفظ بمعلمات التحكم الرسومية الحالية لـ XpsDevice. تُعرّف هذه المعلمات الإطار العام الذي تُنفّذ فيه عمليات الرسوميات. |

### انظر أيضًا

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* package [com.aspose.html.rendering.xps](../../com.aspose.html.rendering.xps/)
* package [Aspose.HTML](../../)
