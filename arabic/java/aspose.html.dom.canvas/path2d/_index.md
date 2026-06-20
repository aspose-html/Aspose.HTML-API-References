---
title: "فئة Path2D"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "فئة com.aspose.html.dom.canvas.Path2D. تُستخدم واجهة Path2D في Canvas 2D API للإعلان عن المسارات التي تُستَخدم لاحقًا على كائنات CanvasRenderingContext2D. طرق المسار في واجهة CanvasRenderingContext2D موجودة أيضًا في هذه الواجهة وتسمح لك بإنشاء مسارات يمكنك الاحتفاظ بها وإعادة تشغيلها حسب الحاجة على القماش"
type: docs

url: /ar/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

واجهة Path2D في API Canvas 2D تُستخدم لتصريح المسارات التي تُستَخدم لاحقًا على كائنات CanvasRenderingContext2D. طرق المسار في واجهة CanvasRenderingContext2D موجودة أيضًا في هذه الواجهة وتتيح لك إنشاء مسارات يمكنك الاحتفاظ بها وإعادة تشغيلها حسب الحاجة على القماش.

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Path2D](path2d/#constructor)() | يعيد كائن Path2D تم إنشاؤه حديثًا. |
| [Path2D](path2d/#constructor_1)(Path2D) | يعيد كائن Path2D تم إنشاؤه حديثًا مع مسار آخر كمعامل (ينشئ نسخة). |
| [Path2D](path2d/#constructor_2)(String) | يعيد كائن Path2D تم إنشاؤه حديثًا مع سلسلة تتكون من بيانات مسار SVG. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | يضيف إلى المسار المسار المُعطى كمعامل. |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | يضيف إلى المسار المسار المُعطى كمعامل. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | يضيف قوسًا إلى المسار يكون مركزه عند الموقع (x, y) بنصف قطر r يبدأ عند startAngle وينتهي عند endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي باتجاه عقارب الساعة). |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | يضيف قوسًا إلى المسار يكون مركزه عند الموقع (x, y) بنصف قطر r يبدأ عند startAngle وينتهي عند endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي باتجاه عقارب الساعة). |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | يضيف قوسًا إلى المسار باستخدام نقاط التحكم المعطاة ونصف القطر، متصلًا بالنقطة السابقة بخط مستقيم. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | يضيف منحنى بيزيه مكعب إلى المسار. يتطلب ثلاث نقاط. النقطتان الأوليتان هما نقاط التحكم والنقطة الثالثة هي نقطة النهاية. نقطة البداية هي آخر نقطة في المسار الحالي، ويمكن تغييرها باستخدام moveTo() قبل إنشاء منحنى بيزيه. |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | يتسبب في إرجاع نقطة القلم إلى بداية الجزء الفرعي الحالي من المسار. يحاول رسم خط مستقيم من النقطة الحالية إلى البداية. إذا كان الشكل مغلقًا بالفعل أو يحتوي على نقطة واحدة فقط، فإن هذه الدالة لا تفعل شيئًا. |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | يُفرغ الكائن. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | يضيف إهليلجًا إلى المسار يكون مركزه عند الموقع (x, y) بنصف القطرين radiusX و radiusY يبدأ عند startAngle وينتهي عند endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي باتجاه عقارب الساعة). |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | يضيف إهليلجًا إلى المسار يكون مركزه عند الموقع (x, y) بنصف القطرين radiusX و radiusY يبدأ عند startAngle وينتهي عند endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي باتجاه عقارب الساعة). |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | يوصل آخر نقطة في الجزء الفرعي إلى إحداثيات x, y بخط مستقيم. |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | ينقل نقطة البداية لمسار فرعي جديد إلى إحداثيات (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | يضيف منحنى بيزيه تربيعي إلى المسار الحالي. |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | ينشئ مسارًا لمستطيل في الموقع (x, y) بحجم يحدده العرض والارتفاع. |

### انظر أيضًا

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
