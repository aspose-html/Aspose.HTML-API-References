---
title: "واجهة ICanvasPathMethods"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "com.aspose.html.dom.canvas.ICanvasPathMethods واجهة. تُستخدم واجهة ICanvasPathMethods للتلاعب بمسارات الكائنات."
type: docs

url: /ar/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

واجهة ICanvasPathMethods تُستخدم للتعامل مع مسارات الكائنات.

```java
public interface ICanvasPathMethods
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | يضيف قوسًا إلى المسار يكون مركزه عند الموقع (x, y) بنصف قطر r يبدأ عند startAngle وينتهي عند endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي باتجاه عقارب الساعة). |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | يضيف قوسًا إلى المسار يكون مركزه عند الموقع (x, y) بنصف قطر r يبدأ عند startAngle وينتهي عند endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي باتجاه عقارب الساعة). |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | يضيف قوسًا إلى المسار باستخدام نقاط التحكم المعطاة ونصف القطر، متصلًا بالنقطة السابقة بخط مستقيم. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | يضيف منحنى بيزيه مكعب إلى المسار. يتطلب ثلاث نقاط. النقطتان الأوليتان هما نقاط التحكم والنقطة الثالثة هي نقطة النهاية. نقطة البداية هي آخر نقطة في المسار الحالي، ويمكن تغييرها باستخدام moveTo() قبل إنشاء منحنى بيزيه. |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | يتسبب في إرجاع نقطة القلم إلى بداية الجزء الفرعي الحالي من المسار. يحاول رسم خط مستقيم من النقطة الحالية إلى البداية. إذا كان الشكل مغلقًا بالفعل أو يحتوي على نقطة واحدة فقط، فإن هذه الدالة لا تفعل شيئًا. |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | يضيف إهليلجًا إلى المسار يكون مركزه عند الموقع (x, y) بنصف القطرين radiusX و radiusY يبدأ عند startAngle وينتهي عند endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي باتجاه عقارب الساعة). |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | يضيف إهليلجًا إلى المسار يكون مركزه عند الموقع (x, y) بنصف القطرين radiusX و radiusY يبدأ عند startAngle وينتهي عند endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي باتجاه عقارب الساعة). |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | يوصل آخر نقطة في الجزء الفرعي إلى إحداثيات x, y بخط مستقيم. |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | ينقل نقطة البداية لمسار فرعي جديد إلى إحداثيات (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | يضيف منحنى بيزيه تربيعي إلى المسار الحالي. |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | ينشئ مسارًا لمستطيل في الموقع (x, y) بحجم يحدده العرض والارتفاع. |

### انظر أيضًا

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
