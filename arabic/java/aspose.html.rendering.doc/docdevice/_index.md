---
title: "DocDevice Class"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "com.aspose.html.rendering.doc.DocDevice class. يمثل عملية التصيير إلى مستند DOCX"
type: docs

url: /ar/java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

يمثّل عملية العرض إلى مستند DOCX.

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | يُنشئ نسخة جديدة من الفئة `DocDevice`. |
| [DocDevice](docdevice/#constructor_4)(Stream) | يُنشئ نسخة جديدة من الفئة `DocDevice` عبر تدفق الإخراج. |
| [DocDevice](docdevice/#constructor_5)(String) | يُنشئ نسخة جديدة من الفئة `DocDevice` عبر اسم ملف الإخراج. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | يُنشئ نسخة جديدة من الفئة `DocDevice` عبر خيارات التصيير ومزود التدفق. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | يُنشئ نسخة جديدة من الفئة `DocDevice` عبر خيارات التصيير وتدفق الإخراج. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | يُنشئ نسخة جديدة من الفئة `DocDevice` عبر خيارات التصيير واسم ملف الإخراج. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | يضيف مستطيلًا إلى المسار الحالي كمسار فرعي كامل. |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | يبدأ تصيير المستند. |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | يبدأ تصيير عقدة html. |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | يبدأ تصيير الصفحة الجديدة. |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillRule) | يعدّل مسار القص الحالي عبر تقاطعه مع المسار الحالي، باستخدام قاعدة FillMode لتحديد المنطقة التي يجب ملؤها. هذه الطريقة تنهي المسار الحالي. |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | يغلق المسار الفرعي الحالي بإضافة مقطع خط مستقيم من النقطة الحالية إلى نقطة بدء المسار الفرعي. إذا كان المسار الفرعي الحالي مغلقًا بالفعل، فإن \"ClosePath\" لا يفعل شيئًا. هذا المشغل ينهي المسار الفرعي الحالي. إضافة مقطع آخر إلى المسار الحالي يبدأ مسارًا فرعيًا جديدًا، حتى إذا بدأ المقطع الجديد عند نقطة النهاية التي وصل إليها أسلوب \"ClosePath\". |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | يضيف منحنى بيزيه مكعب إلى المسار الحالي. يمتد المنحنى من النقطة الحالية إلى النقطة pt2، باستخدام pt1 و pt2 كنقاط تحكم بيزيه. النقطة الحالية الجديدة هي pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], WebImageFormat, RectangleF) | يرسم الصورة المحددة. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | ينهي تصيير عقدة html. |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | ينهي عرض الصفحة الحالية. |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillRule) | يملأ المنطقة الكاملة التي تحيط بها المسار الحالي. إذا كان المسار يتكون من عدة مسارات فرعية غير متصلة، فإنه يملأ داخل جميع المسارات الفرعية معًا. هذه الطريقة تنهي المسار الحالي. |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | يملأ سلسلة النص المحددة في الموقع المحدد. |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | يفرغ جميع البيانات إلى تدفق الإخراج. |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | يضيف قطعة خط مستقيم من النقطة الحالية إلى النقطة (pt). النقطة الحالية الجديدة هي pt. |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | يبدأ مسارًا فرعيًا جديدًا بنقل النقطة الحالية إلى إحداثيات المعامل pt، متجنبًا أي قطعة خطية ربطية. إذا كانت طريقة إنشاء المسار السابقة في المسار الحالي هي أيضًا "MoveTo"، فإن "MoveTo" الجديد يتجاوزها؛ لا يبقى أي أثر لعملية "MoveTo" السابقة في المسار. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | يرسم خطًا على طول المسار الحالي. يتبع الخط المرسوم كل قطعة مستقيمة أو منحنية في المسار، متمركزًا على القطعة مع جوانب موازية لها. يتم معالجة كل مسار فرعي للمسار بشكل منفصل. هذه الطريقة تنهي المسار الحالي. |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillRule) | يرسم ويملأ المسار الحالي. هذه الطريقة تنهي المسار الحالي. |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | يرسم سلسلة النص المحددة في الموقع المحدد. |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | يحافظ على معلمات التحكم الرسومية الحالية لجهاز DocDevice. هذه المعلمات تحدد الإطار العام الذي تنفذ ضمنه عمليات الرسوميات. |

### انظر أيضًا

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
