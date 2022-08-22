---
title: DeviceTGraphicContextTRenderingOptions
second_title: Aspose.HTML لمرجع .NET API
description: يمثل فئة أساسية لتنفيذ أجهزة عرض معينة.
type: docs
weight: 4130
url: /ar/net/aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

يمثل فئة أساسية لتنفيذ أجهزة عرض معينة.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| معامل | وصف |
| --- | --- |
| TGraphicContext | السياق الرسومي الذي يحتفظ بمعلمات التحكم في الرسومات الحالية |
| TRenderingOptions | خيارات التقديم |

## الخصائص

| اسم | وصف |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device`2/graphiccontext) { get; } | يحصل على سياق الرسم |
| [Options](../../aspose.html.rendering/device`2/options) { get; } | يحصل على خيارات التقديم . |

## طُرق

| اسم | وصف |
| --- | --- |
| abstract [AddRect](../../aspose.html.rendering/device`2/addrect)(RectangleF) | إلحاق مستطيل بالمسار الحالي كمسار فرعي كامل. |
| virtual [BeginDocument](../../aspose.html.rendering/device`2/begindocument)(Document) | يبدأ عرض المستند. |
| abstract [BeginElement](../../aspose.html.rendering/device`2/beginelement)(Element, RectangleF) | يبدأ عرض العقدة . |
| virtual [BeginPage](../../aspose.html.rendering/device`2/beginpage)(SizeF) | يبدأ عرض الصفحة الجديدة. |
| abstract [Clip](../../aspose.html.rendering/device`2/clip)(FillMode) | يعدل مسار القطع الحالي من خلال تقاطعه مع المسار الحالي ، باستخدام قاعدة FillMode لتحديد المنطقة المراد تعبئتها. تنهي هذه الطريقة المسار الحالي. |
| abstract [ClosePath](../../aspose.html.rendering/device`2/closepath)() | لإغلاق المسار الفرعي الحالي بإلحاق مقطع بخط مستقيم من النقطة الحالية إلى نقطة بداية المسار الفرعي. إذا كان المسار الفرعي الحالي مغلقًا بالفعل ، فلن يفعل "ClosePath" شيئًا . ينهي عامل التشغيل هذا المسار الفرعي الحالي. يؤدي إلحاق مقطع آخر بالمسار الحالي إلى بدء مسار فرعي جديد ، حتى إذا بدأ المقطع الجديد عند نقطة النهاية التي تم الوصول إليها بواسطة طريقة "ClosePath" . |
| abstract [CubicBezierTo](../../aspose.html.rendering/device`2/cubicbezierto)(PointF, PointF, PointF) | لإلحاق منحنى بيزير مكعب بالمسار الحالي. يمتد المنحنى من النقطة الحالية إلى النقطة pt2 ، باستخدام pt1 و pt2 كنقاط تحكم Bézier. النقطة الحالية الجديدة هي pt3. |
| [Dispose](../../aspose.html.rendering/device`2/dispose)() | تنفيذ مهام محددة بواسطة التطبيق مرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| abstract [DrawImage](../../aspose.html.rendering/device`2/drawimage)(byte[], ImageType, RectangleF) | يرسم الصورة المحددة . |
| virtual [EndDocument](../../aspose.html.rendering/device`2/enddocument)() | ينتهي عرض المستند. |
| abstract [EndElement](../../aspose.html.rendering/device`2/endelement)(Element) | ينتهي عرض العقدة . |
| virtual [EndPage](../../aspose.html.rendering/device`2/endpage)() | ينتهي عرض الصفحة الحالية. |
| abstract [Fill](../../aspose.html.rendering/device`2/fill)(FillMode) | يملأ المنطقة بأكملها المحاطة بالمسار الحالي. إذا كان المسار يتكون من عدة مسارات فرعية غير متصلة ، فإنه يملأ الدواخل لجميع المسارات الفرعية ، تعتبر معًا. تنهي هذه الطريقة المسار الحالي. |
| abstract [FillText](../../aspose.html.rendering/device`2/filltext)(string, PointF) | يملأ السلسلة النصية المحددة في المكان المحدد. |
| virtual [Flush](../../aspose.html.rendering/device`2/flush)() | مسح جميع البيانات لإخراج التدفق. |
| abstract [LineTo](../../aspose.html.rendering/device`2/lineto)(PointF) | لإلحاق مقطع خط مستقيم من النقطة الحالية بالنقطة (نقطة). النقطة الحالية الجديدة هي pt. |
| abstract [MoveTo](../../aspose.html.rendering/device`2/moveto)(PointF) | يبدأ مسارًا فرعيًا جديدًا عن طريق تحريك النقطة الحالية إلى إحداثيات المعلمة pt ، مع حذف أي مقطع خط متصل. إذا كانت طريقة إنشاء المسار السابقة في المسار الحالي هي أيضًا "MoveTo" ، فإن "MoveTo" الجديد يتجاوزها ؛ لا توجد آثار لعملية "MoveTo" السابقة في المسار. |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device`2/restoregraphiccontext)() | يعيد سياق الرسومات بالكامل إلى قيمته السابقة عن طريق إخراجه من المكدس. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device`2/savegraphiccontext)() | يدفع نسخة من سياق الرسوم بأكمله إلى المكدس. |
| abstract [Stroke](../../aspose.html.rendering/device`2/stroke)() | رسم خط بطول المسار الحالي. يتبع الخط المحدد كل مقطع مستقيم أو منحني في المسار ، متمركزًا على المقطع مع جوانب موازية له. يتم التعامل مع كل من المسارات الفرعية للمسار بشكل منفصل. تنهي هذه الطريقة المسار الحالي. |
| abstract [StrokeAndFill](../../aspose.html.rendering/device`2/strokeandfill)(FillMode) | ضربات وملء المسار الحالي. تنهي هذه الطريقة المسار الحالي. |
| abstract [StrokeText](../../aspose.html.rendering/device`2/stroketext)(string, PointF) | ضربات السلسلة النصية المحددة في الموقع المحدد. |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](device-2.deviceconfiguration-2) | يمثل كائن التكوين للأجهزة. |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](device-2.pagewritingstrategy-2) | يحدد أنواع الاستراتيجيات لكتابة الصفحات في تدفق الإخراج \ تدفقات. |

### أنظر أيضا

* interface [IDevice](../idevice)
* class [GraphicContext](../graphiccontext)
* class [RenderingOptions](../renderingoptions)
* مساحة الاسم [Aspose.Html.Rendering](../../aspose.html.rendering)
* المجسم [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
