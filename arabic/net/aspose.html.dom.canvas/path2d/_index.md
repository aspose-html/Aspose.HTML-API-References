---
title: Class Path2D
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Canvas.Path2D فصل. يتم استخدام واجهة Path2D لواجهة Canvas 2D API للإعلان عن المسارات التي يتم استخدامها لاحقًا في كائنات CanvasRenderingContext2D. توجد طرق مسار واجهة CanvasRenderingContext2D على هذه الواجهة أيضًا وتسمح لك بإنشاء مسارات يمكنك الاحتفاظ بها وإعادة تشغيلها كما هو مطلوب على لوحة قماشية.
type: docs
weight: 290
url: /ar/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

يتم استخدام واجهة Path2D لواجهة Canvas 2D API للإعلان عن المسارات التي يتم استخدامها لاحقًا في كائنات CanvasRenderingContext2D. توجد طرق مسار واجهة CanvasRenderingContext2D على هذه الواجهة أيضًا وتسمح لك بإنشاء مسارات يمكنك الاحتفاظ بها وإعادة تشغيلها كما هو مطلوب على لوحة قماشية.

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Path2D](path2d/#constructor)() | إرجاع كائن Path2D تم إنشاؤه حديثًا |
| [Path2D](path2d/#constructor_1)(Path2D) | إرجاع كائن Path2D تم إنشاؤه حديثًا بمسار آخر كوسيطة (يُنشئ نسخة) |
| [Path2D](path2d/#constructor_2)(string) | يقوم بإرجاع كائن Path2D تم إنشاؤه حديثًا بسلسلة تتكون من بيانات مسار SVG. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | يضيف إلى المسار المسار الذي توفره الوسيطة. |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | يضيف إلى المسار المسار الذي توفره الوسيطة. |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | يضيف قوسًا إلى المسار الذي يتركز عند الموضع (س ، ص) مع بدء نصف القطر r عند زاوية البداية وينتهي عند الزاوية في الاتجاه المحدد بعكس اتجاه عقارب الساعة (الافتراضي إلى اتجاه عقارب الساعة) . |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | يضيف قوسًا إلى المسار الذي يتركز عند الموضع (س ، ص) مع بدء نصف القطر r عند زاوية البداية وينتهي عند الزاوية في الاتجاه المحدد بعكس اتجاه عقارب الساعة (الافتراضي إلى اتجاه عقارب الساعة) . |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | يضيف قوسًا إلى المسار بنقاط التحكم ونصف القطر المحددة ، المتصل بالنقطة السابقة بخط مستقيم. |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | يضيف منحنى بيزير مكعبًا إلى المسار. يتطلب ثلاث نقاط. أول نقطتين هما نقطتا تحكم والثالثة هي نقطة النهاية. نقطة البداية هي النقطة الأخيرة في المسار الحالي ، والتي يمكن تغييرها باستخدام moveTo () قبل إنشاء منحنى بيزير. |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath/)() | يتسبب في عودة نقطة القلم إلى بداية المسار الفرعي الحالي. يحاول رسم خط مستقيم من النقطة الحالية إلى البداية. إذا كان الشكل مغلقًا بالفعل أو يحتوي على نقطة واحدة فقط ، فإن هذه الوظيفة لا تفعل شيئًا. |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose/)() | التخلص من الكائن . |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | يضيف قطعًا ناقصًا إلى المسار الذي يتم توسيطه عند موضع (س ، ص) مع نصف قطر نصف قطر X و نصف قطر Y بدءًا من startAngle وينتهي عند endAngle يسير في الاتجاه المحدد بعكس اتجاه عقارب الساعة (افتراضيًا إلى اتجاه عقارب الساعة) . |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | يضيف قطعًا ناقصًا إلى المسار الذي يتم توسيطه عند موضع (س ، ص) مع نصف قطر نصف قطر X و نصف قطر Y بدءًا من startAngle وينتهي عند endAngle يسير في الاتجاه المحدد بعكس اتجاه عقارب الساعة (افتراضيًا إلى اتجاه عقارب الساعة) . |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto/)(double, double) | يربط النقطة الأخيرة في المسار الفرعي بإحداثيات x و y بخط مستقيم. |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto/)(double, double) | ينقل نقطة البداية لمسار فرعي جديد إلى إحداثيات (س ، ص). |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | يضيف منحنى بيزير تربيعيًا إلى المسار الحالي. |
| [Rect](../../aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | إنشاء مسار لمستطيل في الموضع (س ، ص) بحجم يُحدد بالعرض والارتفاع. |

### أنظر أيضا

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* مساحة الاسم [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* المجسم [Aspose.HTML](../../)


