---
title: "ICanvasPathMethods.Ellipse"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة ICanvasPathMethods. تضيف إهليلجًا إلى المسار يكون مركزه عند موقع س ص مع نصف القطرين radiusX و radiusY يبدأ عند startAngle وينتهي عند endAngle ويتحرك في الاتجاه المعاكس لعقارب الساعة مع الافتراضية إلى اتجاه عقارب الساعة."
type: docs

url: /ar/java/com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/
---
## Ellipse(double, double, double, double, double, double, double) {#ellipse}

يضيف إهليلجًا إلى المسار يكون مركزه عند الموضع (x, y) بنصفَي القطر radiusX و radiusY يبدأ من الزاوية startAngle وينتهي عند الزاوية endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي هو مع عقارب الساعة).

```java
public void Ellipse(double x, double y, double radiusX, double radiusY, double rotation, 
    double startAngle, double endAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | محور x للإحداثيات لمركز القطع الناقص. |
| y | Double | محور y للإحداثيات لمركز القطع الناقص. |
| radiusX | Double | نصف قطر المحور الرئيسي للقطع الناقص. |
| radiusY | Double | نصف قطر المحور الثانوي للقطع الناقص. |
| rotation | Double | دوران هذا القطع الناقص، معبرًا عنه بالراديان. |
| startAngle | Double | نقطة البدء، مقاسة من محور x، التي سيُرسم منها، معبرًا عنها بالراديان. |
| endAngle | Double | زاوية النهاية للقطع الناقص التي سيُرسم إليها، معبرًا عنها بالراديان. |

### انظر أيضًا

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Ellipse(double, double, double, double, double, double, double, bool) {#ellipse_1}

يضيف إهليلجًا إلى المسار يكون مركزه عند الموضع (x, y) بنصفَي القطر radiusX و radiusY يبدأ من الزاوية startAngle وينتهي عند الزاوية endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي هو مع عقارب الساعة).

```java
public void Ellipse(double x, double y, double radiusX, double radiusY, double rotation, 
    double startAngle, double endAngle, bool anticlockwise)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | محور x للإحداثيات لمركز القطع الناقص. |
| y | Double | محور y للإحداثيات لمركز القطع الناقص. |
| radiusX | Double | نصف قطر المحور الرئيسي للقطع الناقص. |
| radiusY | Double | نصف قطر المحور الثانوي للقطع الناقص. |
| rotation | Double | دوران هذا القطع الناقص، معبرًا عنه بالراديان. |
| startAngle | Double | نقطة البدء، مقاسة من محور x، التي سيُرسم منها، معبرًا عنها بالراديان. |
| endAngle | Double | زاوية النهاية للقطع الناقص التي سيُرسم إليها، معبرًا عنها بالراديان. |
| anticlockwise | Boolean | قيمة منطقية اختيارية، إذا كانت true، ترسم القطع الناقص anticlockwise (counter-clockwise)، وإلا في اتجاه عقارب الساعة. |

### انظر أيضًا

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
