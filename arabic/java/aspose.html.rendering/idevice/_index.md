---
title: "واجهة IDevice"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.rendering.IDevice. تُعرّف الطرق والخصائص التي تدعم التصيير المخصص لعناصر الرسوم مثل المسارات والنصوص والصور"
type: docs

url: /ar/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

يحدد الطرق والخصائص التي تدعم العرض المخصص لعناصر الرسومات مثل المسارات والنصوص والصور.

```java
public interface IDevice : IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) يحصل على سياق الرسوم. |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) يحصل على خيارات التصيير. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | يضيف مستطيلًا إلى المسار الحالي كمسار فرعي كامل. |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | يبدأ تصيير المستند. |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | يبدأ تصيير العنصر. |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | يبدأ تصيير الصفحة الجديدة. |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | يُعدِّل مسار القص الحالي عن طريق تقاطعه مع المسار الحالي، باستخدام FillRule لتحديد المنطقة التي يجب ملؤها. هذه الطريقة تُنهي المسار الحالي. |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | يغلق المسار الفرعي الحالي بإضافة قطعة خط مستقيم من النقطة الحالية إلى نقطة بدء المسار الفرعي. إذا كان المسار الفرعي الحالي مغلقًا بالفعل، فإن "ClosePath" لا يفعل شيئًا. هذا المشغل ينهي المسار الفرعي الحالي. إضافة قطعة أخرى إلى المسار الحالي يبدأ مسارًا فرعيًا جديدًا، حتى وإن بدأت القطعة الجديدة عند نقطة النهاية التي وصل إليها أسلوب "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | يضيف منحنى بيزييه مكعب إلى المسار الحالي. يمتد المنحنى من النقطة الحالية إلى النقطة pt3، باستخدام pt1 و pt2 كنقاط تحكم بيزييه. النقطة الحالية الجديدة هي pt3. |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | يرسم الصورة المحددة. |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | ينهي تصيير المستند. |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | ينهي تصيير العنصر. |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | ينهي عرض الصفحة الحالية. |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | يملى المنطقة الكاملة المحاطة بالمسار الحالي. إذا كان المسار يتكون من عدة مسارات فرعية غير متصلة، فإنه يملأ داخل جميع المسارات الفرعية معًا. هذه الطريقة تنهي المسار الحالي. |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | يملى سلسلة النص المحددة في الموقع المحدد. |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | يفرغ جميع البيانات إلى تدفق الإخراج. |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | يضيف قطعة خط مستقيم من النقطة الحالية إلى النقطة (pt). النقطة الحالية الجديدة هي pt. |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | يبدأ مسارًا فرعيًا جديدًا بنقل النقطة الحالية إلى إحداثيات المعامل pt، متجنبًا أي قطعة خطية ربطية. إذا كانت طريقة بناء المسار السابقة في المسار الحالي هي أيضًا "MoveTo"، فإن "MoveTo" الجديد يتجاوزها؛ لا يبقى أي أثر لعملية "MoveTo" السابقة في المسار. |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | يستعيد سياق الرسوم بالكامل إلى قيمته السابقة عن طريق إزالته من المكدس. |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | يدفع نسخة من سياق الرسوم بالكامل إلى المكدس. |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | يرسم خطًا على طول المسار الحالي. يتبع الخط المرسوم كل قطعة مستقيمة أو منحنية في المسار، مركزيًا على القطعة مع جوانب موازية لها. يتم معالجة كل مسار فرعي للمسار بشكل منفصل. هذه الطريقة تنهي المسار الحالي. |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | يرسم ويملأ المسار الحالي. هذه الطريقة تنهي المسار الحالي. |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | يرسم سلسلة النص المحددة في الموقع المحدد. |

### انظر أيضًا

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
