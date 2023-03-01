---
title: Class DocDevice
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Rendering.Doc.DocDevice فصل. يمثل التقديم إلى مستند DOCX.
type: docs
weight: 4170
url: /ar/net/aspose.html.rendering.doc/docdevice/
---
## DocDevice class

يمثل التقديم إلى مستند DOCX.

```csharp
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | يقوم بتهيئة مثيل جديد لملف`DocDevice` فئة . |
| [DocDevice](docdevice/#constructor_4)(Stream) | يقوم بتهيئة مثيل جديد لملف`DocDevice` فئة من خلال تيار الإخراج. |
| [DocDevice](docdevice/#constructor_5)(string) | يقوم بتهيئة مثيل جديد لملف`DocDevice` فئة حسب اسم ملف الإخراج. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | يقوم بتهيئة مثيل جديد لملف`DocDevice` class عن طريق تقديم الخيارات وموفر البث. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | يقوم بتهيئة مثيل جديد لملف`DocDevice` class عن طريق تقديم الخيارات ودفق الإخراج. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, string) | يقوم بتهيئة مثيل جديد لملف`DocDevice` class عن طريق تقديم الخيارات واسم ملف الإخراج. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## طُرق

| اسم | وصف |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | إلحاق مستطيل بالمسار الحالي كمسار فرعي كامل. |
| override [BeginDocument](../../aspose.html.rendering.doc/docdevice/begindocument/)(Document) | يبدأ عرض المستند. |
| override [BeginElement](../../aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | يبدأ عرض عقدة html . |
| override [BeginPage](../../aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | يبدأ عرض الصفحة الجديدة . |
| override [Clip](../../aspose.html.rendering.doc/docdevice/clip/)(FillMode) | يعدل مسار القطع الحالي عن طريق تقاطعه مع المسار الحالي ، باستخدام قاعدة FillMode لتحديد المنطقة المراد تعبئتها. تنهي هذه الطريقة المسار الحالي. |
| override [ClosePath](../../aspose.html.rendering.doc/docdevice/closepath/)() | لإغلاق المسار الفرعي الحالي بإلحاق مقطع بخط مستقيم من النقطة الحالية إلى نقطة بداية المسار الفرعي. إذا كان المسار الفرعي الحالي مغلقًا بالفعل ، فإن "ClosePath" لا يفعل شيئًا . ينهي عامل التشغيل هذا المسار الفرعي الحالي. يؤدي إلحاق مقطع آخر بالمسار الحالي إلى بدء مسار فرعي جديد ، حتى إذا بدأ المقطع الجديد عند نقطة النهاية التي تم الوصول إليها بواسطة طريقة "ClosePath" . |
| override [CubicBezierTo](../../aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | لإلحاق منحنى بيزير مكعب بالمسار الحالي. يمتد المنحنى من النقطة الحالية إلى النقطة pt2 ، باستخدام pt1 و pt2 كنقاط تحكم Bézier. النقطة الحالية الجديدة هي pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.doc/docdevice/drawimage/)(byte[], ImageType, RectangleF) | يرسم الصورة المحددة . |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.doc/docdevice/endelement/)(Element) | ينتهي عرض عقدة html . |
| override [EndPage](../../aspose.html.rendering.doc/docdevice/endpage/)() | ينتهي عرض الصفحة الحالية. |
| override [Fill](../../aspose.html.rendering.doc/docdevice/fill/)(FillMode) | يملأ المنطقة بأكملها المحاطة بالمسار الحالي. إذا كان المسار يتكون من عدة مسارات فرعية غير متصلة ، فإنه يملأ الدواخل لجميع المسارات الفرعية ، تعتبر معًا. تنهي هذه الطريقة المسار الحالي. |
| override [FillText](../../aspose.html.rendering.doc/docdevice/filltext/)(string, PointF) | يملأ السلسلة النصية المحددة في المكان المحدد. |
| override [Flush](../../aspose.html.rendering.doc/docdevice/flush/)() | مسح جميع البيانات لإخراج التدفق. |
| override [LineTo](../../aspose.html.rendering.doc/docdevice/lineto/)(PointF) | لإلحاق مقطع خط مستقيم من النقطة الحالية بالنقطة (نقطة). النقطة الحالية الجديدة هي pt. |
| override [MoveTo](../../aspose.html.rendering.doc/docdevice/moveto/)(PointF) | يبدأ مسارًا فرعيًا جديدًا عن طريق تحريك النقطة الحالية إلى إحداثيات المعلمة pt ، مع حذف أي مقطع خط متصل. إذا كانت طريقة إنشاء المسار السابقة في المسار الحالي هي أيضًا "MoveTo" ، فإن "MoveTo" الجديد يتجاوزها ؛ لا توجد آثار لعملية "MoveTo" السابقة في المسار. |
| override [RestoreGraphicContext](../../aspose.html.rendering.doc/docdevice/restoregraphiccontext/)() | يعيد سياق الرسومات بالكامل إلى قيمته السابقة عن طريق إخراجه من المكدس. |
| override [SaveGraphicContext](../../aspose.html.rendering.doc/docdevice/savegraphiccontext/)() | يدفع نسخة من سياق الرسوم بأكمله إلى المكدس. |
| override [Stroke](../../aspose.html.rendering.doc/docdevice/stroke/)() | رسم خط بطول المسار الحالي. يتبع الخط المحدد كل مقطع مستقيم أو منحني في المسار ، متمركزًا على المقطع مع جوانب موازية له. يتم التعامل مع كل من المسارات الفرعية للمسار بشكل منفصل. تنهي هذه الطريقة المسار الحالي. |
| override [StrokeAndFill](../../aspose.html.rendering.doc/docdevice/strokeandfill/)(FillMode) | ضربات وملء المسار الحالي. تنهي هذه الطريقة المسار الحالي. |
| override [StrokeText](../../aspose.html.rendering.doc/docdevice/stroketext/)(string, PointF) | ضربات السلسلة النصية المحددة في الموقع المحدد. |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| class [DocGraphicContext](docdevice.docgraphiccontext/) | يحمل معلمات التحكم في الرسومات الحالية لـ DocDevice. تحدد هذه المعلمات إطار العمل العام الذي ينفذ فيه مشغلو الرسومات . |

### أنظر أيضا

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* مساحة الاسم [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* المجسم [Aspose.HTML](../../)


