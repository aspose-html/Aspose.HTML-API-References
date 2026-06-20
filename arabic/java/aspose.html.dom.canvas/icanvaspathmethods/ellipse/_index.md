---
title: "ICanvasPathMethods.Ellipse"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة ICanvasPathMethods. تضيف إهليلجًا إلى المسار يكون مركزه عند موضع س ص مع نصفَي القطر radiusX و radiusY يبدأ عند startAngle وينتهي عند endAngle ويتحرك في الاتجاه المحدد عكس اتجاه عقارب الساعة مع الافتراضية باتجاه عقارب الساعة"
type: docs

url: /ar/java/com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/
---
## Ellipse(double, double, double, double, double, double, double) {#ellipse}

يضيف إهليلجًا إلى المسار يكون مركزه عند الموقع (x, y) بنصف القطرين radiusX و radiusY يبدأ عند startAngle وينتهي عند endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي باتجاه عقارب الساعة).

```java
public void Ellipse(double x, double y, double radiusX, double radiusY, double rotation, 
    double startAngle, double endAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | محور x للإحداثي لمركز القطع الناقص. |
| y | Double | محور y للإحداثي لمركز القطع الناقص. |
| radiusX | Double | نصف قطر المحور الرئيسي للقطع الناقص. |
| radiusY | Double | نصف قطر المحور الثانوي للقطع الناقص. |
| rotation | Double | الدوران لهذا القطع الناقص، معبرًا عنه بالراديان. |
| startAngle | Double | نقطة البداية، مقاسة من محور x، التي سيتم رسمها منها، معبرًا عنها بالراديان. |
| endAngle | Double | زاوية نهاية القطع الناقص التي سيتم رسمها، معبرًا عنها بالراديان. |

### انظر أيضًا

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Ellipse(double, double, double, double, double, double, double, bool) {#ellipse_1}

يضيف إهليلجًا إلى المسار يكون مركزه عند الموقع (x, y) بنصف القطرين radiusX و radiusY يبدأ عند startAngle وينتهي عند endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي باتجاه عقارب الساعة).

```java
public void Ellipse(double x, double y, double radiusX, double radiusY, double rotation, 
    double startAngle, double endAngle, bool anticlockwise)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | محور x للإحداثي لمركز القطع الناقص. |
| y | Double | محور y للإحداثي لمركز القطع الناقص. |
| radiusX | Double | نصف قطر المحور الرئيسي للقطع الناقص. |
| radiusY | Double | نصف قطر المحور الثانوي للقطع الناقص. |
| rotation | Double | الدوران لهذا القطع الناقص، معبرًا عنه بالراديان. |
| startAngle | Double | نقطة البداية، مقاسة من محور x، التي سيتم رسمها منها، معبرًا عنها بالراديان. |
| endAngle | Double | زاوية نهاية القطع الناقص التي سيتم رسمها، معبرًا عنها بالراديان. |
| anticlockwise | Boolean | قيمة منطقية اختيارية، إذا كانت true، ترسم القطع الناقص عكس اتجاه عقارب الساعة (counter-clockwise)، وإلا في اتجاه عقارب الساعة. |

### انظر أيضًا

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
