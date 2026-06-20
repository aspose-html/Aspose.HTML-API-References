---
title: "ICanvasPathMethods.Arc"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة ICanvasPathMethods. تضيف قوسًا إلى المسار يكون مركزه عند موضع س ص مع نصف القطر r يبدأ عند startAngle وينتهي عند endAngle ويتحرك في الاتجاه المحدد عكس اتجاه عقارب الساعة مع الافتراضية باتجاه عقارب الساعة"
type: docs

url: /ar/java/com.aspose.html.dom.canvas/icanvaspathmethods/arc/
---
## Arc(double, double, double, double, double) {#arc}

يضيف قوسًا إلى المسار يكون مركزه عند الموقع (x, y) بنصف قطر r يبدأ عند startAngle وينتهي عند endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي باتجاه عقارب الساعة).

```java
public void Arc(double x, double y, double radius, double startAngle, double endAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | الإحداثي س لمركز القوس. |
| y | Double | الإحداثي ص لمركز القوس. |
| نصف القطر | Double | نصف قطر القوس. |
| startAngle | Double | الزاوية التي يبدأ عندها القوس، مقاسة باتجاه عقارب الساعة من المحور س الموجب ومعبَّرة بالراديان. |
| endAngle | Double | الزاوية التي ينتهي عندها القوس، مقاسة باتجاه عقارب الساعة من المحور س الموجب ومعبَّرة بالراديان. |

### انظر أيضًا

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Arc(double, double, double, double, double, bool) {#arc_1}

يضيف قوسًا إلى المسار يكون مركزه عند الموقع (x, y) بنصف قطر r يبدأ عند startAngle وينتهي عند endAngle ويتجه في الاتجاه المحدد عكس عقارب الساعة (الافتراضي باتجاه عقارب الساعة).

```java
public void Arc(double x, double y, double radius, double startAngle, double endAngle, 
    bool counterclockwise)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | الإحداثي س لمركز القوس. |
| y | Double | الإحداثي ص لمركز القوس. |
| نصف القطر | Double | نصف قطر القوس. |
| startAngle | Double | الزاوية التي يبدأ عندها القوس، مقاسة باتجاه عقارب الساعة من المحور س الموجب ومعبَّرة بالراديان. |
| endAngle | Double | الزاوية التي ينتهي عندها القوس، مقاسة باتجاه عقارب الساعة من المحور س الموجب ومعبَّرة بالراديان. |
| عكس اتجاه عقارب الساعة | Boolean | تجعل القوس يُرسم عكس اتجاه عقارب الساعة بين الزاويتين. بشكل افتراضي يُرسم باتجاه عقارب الساعة. |

### انظر أيضًا

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
