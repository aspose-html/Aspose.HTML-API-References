---
title: "Path2D فئة"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "com.aspose.html.dom.canvas.Path2D فئة. واجهة Path2D في واجهة برمجة تطبيقات Canvas 2D تُستخدم لإعلان المسارات التي تُستَخدم لاحقًا على كائنات CanvasRenderingContext2D. طرق المسار في واجهة CanvasRenderingContext2D موجودة أيضًا في هذه الواجهة وتسمح لك بإنشاء مسارات يمكنك الاحتفاظ بها وإعادة تشغيلها حسب الحاجة على لوحة الرسم."
type: docs

url: /ar/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

واجهة Path2D في API Canvas 2D تُستخدم لإعلان المسارات التي تُستَخدم لاحقًا على كائنات CanvasRenderingContext2D. طرق المسار في واجهة CanvasRenderingContext2D موجودة أيضًا في هذه الواجهة وتتيح لك إنشاء مسارات يمكنك الاحتفاظ بها وإعادة تشغيلها حسب الحاجة على لوحة الرسم.

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Path2D](path2d/#constructor)() | يعيد كائن Path2D تم إنشاؤه حديثًا |
| [Path2D](path2d/#constructor_1)(Path2D) | يعيد كائن Path2D تم إنشاؤه حديثًا مع مسار آخر كمعامل (ينشئ نسخة) |
| [Path2D](path2d/#constructor_2)(String) | يعيد كائن Path2D تم إنشاؤه حديثًا مع سلسلة تتكون من بيانات مسار SVG. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | يضيف إلى المسار المسار المقدم كمعامل. |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | يضيف إلى المسار المسار المقدم كمعامل. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | يضيف قوسًا إلى المسار يكون مركزه عند الموضع (x, y) بنصف قطر r يبدأ من الزاوية startAngle وينتهي عند الزاوية endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي هو مع عقارب الساعة). |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | يضيف قوسًا إلى المسار يكون مركزه عند الموضع (x, y) بنصف قطر r يبدأ من الزاوية startAngle وينتهي عند الزاوية endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي هو مع عقارب الساعة). |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | يضيف قوسًا إلى المسار باستخدام نقاط التحكم المحددة والنصف قطر، متصلًا بالنقطة السابقة بخط مستقيم. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | يضيف منحنى بيزير تكعيبي إلى المسار. يتطلب ثلاث نقاط. النقطتان الأوليتان هما نقاط التحكم والنقطة الثالثة هي نقطة النهاية. نقطة البداية هي آخر نقطة في المسار الحالي، ويمكن تغييرها باستخدام moveTo() قبل إنشاء منحنى بيزير. |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | يتسبب في عودة نقطة القلم إلى بداية المسار الفرعي الحالي. يحاول رسم خط مستقيم من النقطة الحالية إلى البداية. إذا كان الشكل مغلقًا بالفعل أو يحتوي على نقطة واحدة فقط، فإن هذه الدالة لا تفعل شيئًا. |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | يفرغ الكائن. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | يضيف إهليلجًا إلى المسار يكون مركزه عند الموضع (x, y) بنصفَي القطر radiusX و radiusY يبدأ من الزاوية startAngle وينتهي عند الزاوية endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي هو مع عقارب الساعة). |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | يضيف إهليلجًا إلى المسار يكون مركزه عند الموضع (x, y) بنصفَي القطر radiusX و radiusY يبدأ من الزاوية startAngle وينتهي عند الزاوية endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي هو مع عقارب الساعة). |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | يوصل آخر نقطة في المسار الفرعي إلى إحداثيات x, y بخط مستقيم. |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | ينقل نقطة البداية لمسار فرعي جديد إلى إحداثيات (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | يضيف منحنى بيزير تربيعي إلى المسار الحالي. |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | ينشئ مسارًا لمستطيل في الموضع (x, y) بحجم يُحدَّد بواسطة العرض والارتفاع. |

### انظر أيضًا

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
