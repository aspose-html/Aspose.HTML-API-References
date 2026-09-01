---
title: "فئة DeviceTGraphicContextTRenderingOptions"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.rendering.Device2TGraphicContextTRenderingOptions. تمثل الفئة الأساسية لتنفيذ أجهزة التصيير الخاصة."
type: docs

url: /ar/java/com.aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

يمثل الفئة الأساسية لتنفيذ أجهزة العرض المحددة.

```java
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| معامل | الوصف |
| --- | --- |
| TGraphicContext | سياق رسومي يحتفظ بمعلمات التحكم الرسومية الحالية |
| TRenderingOptions | خيارات التصيير |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) يحصل على سياق الرسوم |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) يحصل على خيارات التصيير. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) | يضيف مستطيلًا إلى المسار الحالي كمسار فرعي كامل. |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) | يبدأ تصيير المستند. |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | يبدأ تصيير العقدة. |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) | يبدأ تصيير الصفحة الجديدة. |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) | يعدّل مسار القص الحالي عن طريق تقاطعه مع المسار الحالي، باستخدام FillRule لتحديد المنطقة التي يجب ملؤها. تنهي هذه الطريقة المسار الحالي. |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() | يغلق المسار الفرعي الحالي بإضافة مقطع خط مستقيم من النقطة الحالية إلى نقطة بدء المسار الفرعي. إذا كان المسار الفرعي الحالي مغلقًا بالفعل، فإن \"ClosePath\" لا يفعل شيئًا. هذا المشغل ينهي المسار الفرعي الحالي. إضافة مقطع آخر إلى المسار الحالي يبدأ مسارًا فرعيًا جديدًا، حتى إذا بدأ المقطع الجديد عند نقطة النهاية التي وصل إليها أسلوب \"ClosePath\". |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | يضيف منحنى بيزيه مكعب إلى المسار الحالي. يمتد المنحنى من النقطة الحالية إلى النقطة pt2، باستخدام pt1 و pt2 كنقاط تحكم بيزيه. النقطة الحالية الجديدة هي pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() | ينفّذ مهامًا معرفة من قبل التطبيق مرتبطة بتحرير أو تحرير أو إعادة ضبط الموارد غير المُدارة. |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) | يرسم الصورة المحددة. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() | ينهي تصيير المستند. |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) | ينهي تصيير العقدة. |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() | ينهي عرض الصفحة الحالية. |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) | يملأ المنطقة الكاملة التي تحيط بها المسار الحالي. إذا كان المسار يتكون من عدة مسارات فرعية غير متصلة، فإنه يملأ داخل جميع المسارات الفرعية معًا. هذه الطريقة تنهي المسار الحالي. |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) | يملأ سلسلة النص المحددة في الموقع المحدد. |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() | يفرغ جميع البيانات إلى تدفق الإخراج. |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) | يضيف قطعة خط مستقيم من النقطة الحالية إلى النقطة (pt). النقطة الحالية الجديدة هي pt. |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) | يبدأ مسارًا فرعيًا جديدًا بنقل النقطة الحالية إلى إحداثيات المعامل pt، متجنبًا أي قطعة خطية ربطية. إذا كانت طريقة إنشاء المسار السابقة في المسار الحالي هي أيضًا "MoveTo"، فإن "MoveTo" الجديد يتجاوزها؛ لا يبقى أي أثر لعملية "MoveTo" السابقة في المسار. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() | يعيد سياق الرسوم بالكامل إلى قيمته السابقة عن طريق إزالته من المكدس. |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() | يدفع نسخة من سياق الرسوم بالكامل إلى المكدس. |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() | يرسم خطًا على طول المسار الحالي. يتبع الخط المرسوم كل قطعة مستقيمة أو منحنية في المسار، متمركزًا على القطعة مع جوانب موازية لها. يتم معالجة كل مسار فرعي للمسار بشكل منفصل. هذه الطريقة تنهي المسار الحالي. |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) | يرسم ويملأ المسار الحالي. هذه الطريقة تنهي المسار الحالي. |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) | يرسم سلسلة النص المحددة في الموقع المحدد. |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.pagewritingstrategy-2) | يحدد أنواع الاستراتيجيات لكتابة الصفحات إلى تدفق الإخراج\التدفقات. |

### انظر أيضًا

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
