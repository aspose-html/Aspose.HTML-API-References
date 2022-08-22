---
title: ICanvasRenderingContext2D
second_title: Aspose.HTML لمرجع .NET API
description: تُستخدم واجهة ICanvasRenderingContext2D لرسم المستطيلات والنصوص والصور والكائنات الأخرى على عنصر لوحة الرسم. يوفر سياق العرض ثنائي الأبعاد لسطح الرسم لعنصر قماش.
type: docs
weight: 270
url: /ar/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

تُستخدم واجهة ICanvasRenderingContext2D لرسم المستطيلات والنصوص والصور والكائنات الأخرى على عنصر لوحة الرسم. يوفر سياق العرض ثنائي الأبعاد لسطح الرسم لعنصر قماش.

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas) { get; } | مرجع خلفي للقراءة فقط إلى HTMLCanvasElement. قد يكون فارغًا إذا لم يكن مرتبطًا بعنصر لوحة الرسم . |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle) { get; set; } | لون أو نمط لاستخدام الأشكال الداخلية. الافتراضي: (أسود) . |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha) { get; set; } | قيمة Alpha التي يتم تطبيقها على الأشكال والصور قبل تكوينها على اللوحة القماشية. الافتراضي 1.0 (كامد) . |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation) { get; set; } | مع تطبيق globalAlpha ، يعيّن هذا كيفية رسم الأشكال والصور على الصورة النقطية الموجودة. الافتراضي: (المصدر أكثر) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled) { get; set; } | وضع تجانس الصورة ؛ إذا تم تعطيله ، فلن يتم تنعيم الصور إذا تم تحجيمها. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur) { get; set; } | يحدد تأثير التعتيم. الافتراضي 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor) { get; set; } | لون الظل. افتراضي أسود شفاف بالكامل. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx) { get; set; } | المسافة الأفقية سيتم تعويض الظل. الافتراضي 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety) { get; set; } | المسافة العمودية سيتم تعويض الظل. الافتراضي 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle) { get; set; } | اللون أو النمط المطلوب استخدامه للخطوط حول الأشكال. الافتراضي: (أسود) . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion)(Dictionary&lt;string, string&gt;) | يضيف منطقة نتائج إلى اللوحة القماشية. يتيح لك هذا تسهيل اكتشاف النتائج ، ويتيح لك توجيه الأحداث إلى عناصر DOM ، ويسمح للمستخدمين باستكشاف اللوحة دون رؤيتها. |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath)() | يبدأ مسارًا جديدًا بإفراغ قائمة المسارات الفرعية. قم باستدعاء هذه الطريقة عندما تريد إنشاء مسار جديد. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions)() | يزيل جميع مناطق النتائج من اللوحة . |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect)(double, double, double, double) | يضبط جميع وحدات البكسل في المستطيل المحدد بنقطة البداية (س ، ص) والحجم (العرض والارتفاع) إلى أسود شفاف ، مع محو أي محتوى تم رسمه مسبقًا. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip#clip)() | إنشاء منطقة قطع جديدة عن طريق حساب تقاطع منطقة القطع الحالية والمساحة الموصوفة بواسطة المسار ، باستخدام قاعدة رقم الملف غير الصفري. يجب إغلاق المسارات الفرعية المفتوحة بشكل ضمني عند حساب منطقة القطع ، دون التأثير على المسارات الفرعية الفعلية . تحل منطقة القطع الجديدة محل منطقة القطع الحالية. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip#clip_1)(CanvasFillRule) | إنشاء منطقة قطع جديدة عن طريق حساب تقاطع منطقة القطع الحالية والمنطقة الموصوفة بواسطة المسار ، باستخدام قاعدة الأرقام المتعرجة غير الصفرية. يجب إغلاق المسارات الفرعية المفتوحة بشكل ضمني عند حساب منطقة القطع ، دون التأثير على المسارات الفرعية الفعلية. تحل منطقة القطع الجديدة محل منطقة القطع الحالية. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip#clip_2)(Path2D, CanvasFillRule) | إنشاء منطقة قطع جديدة عن طريق حساب تقاطع منطقة القطع الحالية والمنطقة الموصوفة بواسطة المسار ، باستخدام قاعدة الأرقام المتعرجة غير الصفرية. يجب إغلاق المسارات الفرعية المفتوحة بشكل ضمني عند حساب منطقة القطع ، دون التأثير على المسارات الفرعية الفعلية. تحل منطقة القطع الجديدة محل منطقة القطع الحالية. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata#createimagedata)(IImageData) | إنشاء كائن ImageData جديد وفارغ بالأبعاد المحددة. جميع وحدات البكسل في الكائن الجديد سوداء شفافة. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata#createimagedata_1)(double, double) | إنشاء كائن ImageData جديد وفارغ بالأبعاد المحددة. جميع وحدات البكسل في الكائن الجديد سوداء شفافة. |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient)(double, double, double, double) | ينشئ تدرجًا خطيًا على طول الخط المعطى بواسطة الإحداثيات التي تمثلها المعلمات. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern#createpattern)(HTMLCanvasElement, string) | ينشئ نمطًا باستخدام الصورة المحددة (مصدر الصورة Canvas). يكرر المصدر في الاتجاهات المحددة بواسطة وسيطة التكرار. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern#createpattern_1)(HTMLImageElement, string) | ينشئ نمطًا باستخدام الصورة المحددة (مصدر الصورة Canvas). يكرر المصدر في الاتجاهات المحددة بواسطة وسيطة التكرار. |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient)(double, double, double, double, double, double) | ينشئ تدرجًا نصف قطريًا تعطى بإحداثيات الدائرتين التي تمثلها المعلمات. |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded)(Element) | إذا تم التركيز على عنصر معين ، فإن هذه الطريقة ترسم حلقة تركيز حول المسار الحالي. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage#drawimage)(HTMLCanvasElement, double, double) | يرسم الصورة المحددة . |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage#drawimage_3)(HTMLImageElement, double, double) | يرسم الصورة المحددة . |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage#drawimage_1)(HTMLCanvasElement, double, double, double, double) | يرسم الصورة المحددة . |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage#drawimage_4)(HTMLImageElement, double, double, double, double) | يرسم الصورة المحددة . |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | يرسم الصورة المحددة. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | يرسم الصورة المحددة. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill#fill)() | يملأ المسارات الفرعية بنمط التعبئة الحالي والخوارزمية الافتراضية CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill#fill_1)(CanvasFillRule) | يملأ المسارات الفرعية بنمط التعبئة الحالي. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill#fill_2)(Path2D) | يملأ المسارات الفرعية بنمط التعبئة الحالي والخوارزمية الافتراضية CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill#fill_3)(Path2D, CanvasFillRule) | يملأ المسارات الفرعية بنمط التعبئة الحالي. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect)(double, double, double, double) | رسم مستطيل ممتلئ عند موضع (س ، ص) يتحدد حجمه بالعرض والارتفاع. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext#filltext)(string, double, double) | رسم (يملأ) نصًا معينًا في الموضع المحدد (س ، ص) . |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext#filltext_1)(string, double, double, double) | رسم (يملأ) نصًا معينًا في الموضع المحدد (س ، ص) . |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata)(double, double, double, double) | إرجاع كائن ImageData يمثل بيانات البكسل الأساسية لمنطقة اللوحة القماشية المشار إليها بواسطة المستطيل الذي يبدأ عند (sx، sy) وله عرض sw وارتفاع sh . لا تتأثر هذه الطريقة بمصفوفة تحويل اللوحة القماشية. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath#ispointinpath_2)(double, double) | يبين ما إذا كانت النقطة المحددة متضمنة في المسار الحالي أم لا. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath#ispointinpath_3)(double, double, CanvasFillRule) | يبين ما إذا كانت النقطة المحددة متضمنة في المسار الحالي أم لا. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath#ispointinpath)(Path2D, double, double) | يبين ما إذا كانت النقطة المحددة متضمنة في المسار الحالي أم لا. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | يبين ما إذا كانت النقطة المحددة متضمنة في المسار الحالي أم لا. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke#ispointinstroke_1)(double, double) | يبين ما إذا كانت النقطة المحددة داخل المنطقة التي يتضمنها رسم المسار أم لا. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke#ispointinstroke)(Path2D, double, double) | يبين ما إذا كانت النقطة المحددة داخل المنطقة التي يتضمنها رسم المسار أم لا. |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext)(string) | إرجاع كائن TextMetrics . |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata#putimagedata)(IImageData, double, double) | يطلي البيانات من كائن ImageData المحدد على الصورة النقطية. في حالة توفير مستطيل متسخ ، يتم رسم وحدات البكسل من هذا المستطيل فقط. لا تتأثر هذه الطريقة بمصفوفة تحويل اللوحة القماشية. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata#putimagedata_1)(IImageData, double, double, double, double, double, double) | يطلي البيانات من كائن ImageData المحدد على الصورة النقطية. في حالة توفير مستطيل متسخ ، يتم رسم وحدات البكسل من هذا المستطيل فقط. لا تتأثر هذه الطريقة بمصفوفة تحويل اللوحة القماشية. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion)(string) | يزيل منطقة النتائج بالمعرف المحدد من اللوحة . |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform)() | يعيد تعيين التحويل الحالي بواسطة مصفوفة الهوية. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore)() | يعيد حالة نمط الرسم إلى العنصر الأخير في "مكدس الحالة" المحفوظ بواسطة الحفظ () . |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate)(double) | إضافة دوران إلى مصفوفة التحويل. تمثل وسيطة الزاوية زاوية دوران في اتجاه عقارب الساعة ويتم التعبير عنها بالراديان. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save)() | يحفظ حالة نمط الرسم الحالية باستخدام مكدس حتى تتمكن من التراجع عن أي تغيير تقوم بإجرائه عليه باستخدام الاستعادة () . |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale)(double, double) | يضيف تحويل تغيير الحجم إلى وحدات قماش الرسم بواسطة x أفقيًا وعموديًا . |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform)(double, double, double, double, double, double) | يعيد تعيين التحويل الحالي إلى مصفوفة الهوية ، ثم يستدعي طريقة التحويل () بنفس الوسائط. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke#stroke)() | رسم المسارات الفرعية بنمط الحد الحالي. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke#stroke_1)(Path2D) | رسم المسارات الفرعية بنمط الحد الحالي. |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect)(double, double, double, double) | يقوم بطلاء مستطيل له نقطة بداية عند (x، y) وله عرض aw و ارتفاع h على اللوحة القماشية ، باستخدام نمط الحد الحالي . |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext#stroketext)(string, double, double) | رسم (ضربات) نص معين في الموضع المحدد (x ، y) . |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext#stroketext_1)(string, double, double, double?) | رسم (ضربات) نص معين في الموضع المحدد (x ، y) . |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform)(double, double, double, double, double, double) | ضرب مصفوفة التحويل الحالية بالمصفوفة الموصوفة بواسطة وسيطاتها. |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate)(double, double) | يضيف تحويلًا للترجمة عن طريق تحريك اللوحة القماشية وأصلها x أفقيًا و y عموديًا على الشبكة. |

### أنظر أيضا

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles)
* interface [ICanvasPathMethods](../icanvaspathmethods)
* مساحة الاسم [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas)
* المجسم [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
