---
title: "واجهة ICanvasRenderingContext2D"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الواجهة com.aspose.html.dom.canvas.ICanvasRenderingContext2D. تُستخدم واجهة ICanvasRenderingContext2D لرسم المستطيلات والنصوص والصور والكائنات الأخرى على عنصر القماش. توفر سياق العرض ثنائي الأبعاد لسطح الرسم لعنصر القماش."
type: docs

url: /ar/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

واجهة ICanvasRenderingContext2D تُستخدم لرسم المستطيلات والنصوص والصور والكائنات الأخرى على عنصر القماش. وهي توفر سياق العرض ثنائي الأبعاد لسطح الرسم لعنصر القماش.

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) إشارة خلفية للقراءة فقط إلى HTMLCanvasElement. قد تكون null إذا لم تكن مرتبطة بعنصر قماش. |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | يبدأ مسارًا جديدًا عن طريق إفراغ قائمة المسارات الفرعية. استدعِ هذه الطريقة عندما تريد إنشاء مسار جديد. |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | يزيل جميع مناطق الضربة من القماش. |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | يضبط جميع البكسلات في المستطيل المحدد بنقطة البداية (x, y) والحجم (العرض, الارتفاع) إلى اللون الأسود الشفاف، مما يمحو أي محتوى مرسوم مسبقًا. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | ينشئ منطقة قص جديدة بحساب تقاطع منطقة القص الحالية والمساحة الموصوفة بالمسار، باستخدام قاعدة عدد اللف غير الصفري. يجب إغلاق المسارات الفرعية المفتوحة ضمنيًا عند حساب منطقة القص، دون التأثير على المسارات الفرعية الفعلية. تستبدل منطقة القص الجديدة منطقة القص الحالية. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | ينشئ منطقة قص جديدة بحساب تقاطع منطقة القص الحالية والمساحة الموصوفة بالمسار، باستخدام قاعدة عدد اللف غير الصفري. يجب إغلاق المسارات الفرعية المفتوحة ضمنيًا عند حساب منطقة القص، دون التأثير على المسارات الفرعية الفعلية. تستبدل منطقة القص الجديدة منطقة القص الحالية. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | ينشئ منطقة قص جديدة بحساب تقاطع منطقة القص الحالية والمساحة الموصوفة بالمسار، باستخدام قاعدة عدد اللف غير الصفري. يجب إغلاق المسارات الفرعية المفتوحة ضمنيًا عند حساب منطقة القص، دون التأثير على المسارات الفرعية الفعلية. تستبدل منطقة القص الجديدة منطقة القص الحالية. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | ينشئ كائن ImageData جديد وفارغ بالأبعاد المحددة. جميع البكسلات في الكائن الجديد هي باللون الأسود الشفاف. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | ينشئ كائن ImageData جديد وفارغ بالأبعاد المحددة. جميع البكسلات في الكائن الجديد هي باللون الأسود الشفاف. |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | ينشئ تدرجًا خطيًا على طول الخط المحدد بالإحداثيات الممثلة بالمعاملات. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | ينشئ نمطًا باستخدام الصورة المحددة (CanvasImageSource). يكرر المصدر في الاتجاهات المحددة بواسطة معامل التكرار. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | ينشئ نمطًا باستخدام الصورة المحددة (CanvasImageSource). يكرر المصدر في الاتجاهات المحددة بواسطة معامل التكرار. |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | ينشئ تدرجًا شعاعيًا بناءً على إحداثيات الدائرتين الممثلتين بالمعاملات. |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | إذا كان العنصر المحدد مركّزًا، فإن هذه الطريقة ترسم حلقة تركيز حول المسار الحالي. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | يرسم الصورة المحددة. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | يرسم الصورة المحددة. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | يرسم الصورة المحددة. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | يرسم الصورة المحددة. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | يرسم الصورة المحددة. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | يرسم الصورة المحددة. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | يملأ المسارات الفرعية بنمط التعبئة الحالي والخوارزمية الافتراضية CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | يملأ المسارات الفرعية بنمط التعبئة الحالي. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | يملأ المسارات الفرعية بنمط التعبئة الحالي والخوارزمية الافتراضية CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | يملأ المسارات الفرعية بنمط التعبئة الحالي. |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | يرسم مستطيلًا مملوءًا عند الموضع (x, y) حيث يتم تحديد حجمه بواسطة العرض والارتفاع. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | يرسم (يملأ) نصًا معينًا عند الموضع (x,y) المحدد. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | يرسم (يملأ) نصًا معينًا عند الموضع (x,y) المحدد. |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | يرجع كائن ImageData يمثل بيانات البكسل الأساسية للمنطقة على القماش المحددة بالمستطيل الذي يبدأ عند (sx, sy) وله عرض sw وارتفاع sh. لا تتأثر هذه الطريقة بمصفوفة تحويل القماش. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | يبلغ عما إذا كانت النقطة المحددة موجودة داخل المسار الحالي أم لا. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | يبلغ عما إذا كانت النقطة المحددة موجودة داخل المسار الحالي أم لا. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | يبلغ عما إذا كانت النقطة المحددة موجودة داخل المسار الحالي أم لا. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | يبلغ عما إذا كانت النقطة المحددة موجودة داخل المسار الحالي أم لا. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | يبلغ عما إذا كانت النقطة المحددة داخل المنطقة التي يحدّدها تخطيط (stroke) مسار. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | يبلغ عما إذا كانت النقطة المحددة داخل المنطقة التي يحدّدها تخطيط (stroke) مسار. |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | يرجع كائن TextMetrics. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | يرسم البيانات من كائن ImageData المعطى على الصورة النقطية. إذا تم توفير مستطيل متسخ، يتم رسم البكسلات الموجودة فقط في ذلك المستطيل. لا تتأثر هذه الطريقة بمصفوفة تحويل القماش. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | يرسم البيانات من كائن ImageData المعطى على الصورة النقطية. إذا تم توفير مستطيل متسخ، يتم رسم البكسلات الموجودة فقط في ذلك المستطيل. لا تتأثر هذه الطريقة بمصفوفة تحويل القماش. |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | يزيل منطقة الضربة ذات المعرف المحدد من القماش. |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | يعيد تعيين التحويل الحالي إلى مصفوفة الهوية. |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | يستعيد حالة نمط الرسم إلى العنصر الأخير في 'مكدس الحالة' الذي تم حفظه بواسطة save(). |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | يضيف دورانًا إلى مصفوفة التحويل. تمثل قيمة الزاوية دورانًا باتجاه عقارب الساعة وتُعبّر عنها بالراديان. |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | يحفظ حالة نمط الرسم الحالية باستخدام مكدس حتى يمكنك إرجاع أي تغيير تجريه باستخدام restore(). |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | يضيف تحويلًا للتكبير إلى وحدات القماش بمقدار x أفقياً و y عمودياً. |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | يعيد تعيين التحويل الحالي إلى مصفوفة الهوية، ثم يستدعي طريقة transform() بنفس المعطيات. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | يرسم حدود المسارات الفرعية بنمط الحد الحالي. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | يرسم حدود المسارات الفرعية بنمط الحد الحالي. |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | يرسم مستطيلًا يبدأ نقطته عند (x, y) وله عرض w وارتفاع h على القماش، باستخدام نمط الحد الحالي. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | يرسم (يرسم حدود) نصًا معينًا عند الموضع (x, y) المحدد. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | يرسم (يرسم حدود) نصًا معينًا عند الموضع (x, y) المحدد. |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | يضرب مصفوفة التحويل الحالية بالمصفوفة الموصوفة بالمعطيات. |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | يضيف تحويلًا إزاحيًا عن طريق تحريك القماش وأصلّه أفقياً بمقدار x وعمودياً بمقدار y على الشبكة. |

### انظر أيضًا

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
