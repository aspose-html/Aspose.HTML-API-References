---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة SVGGraphicsElement. تُعيد مصفوفة التحويل من وحدات المستخدم الحالية أي بعد تطبيق سمة التحويل إن وجدت إلى ملاحظة الوكيل الأب للوحدة البكسلية. بالنسبة لأجهزة العرض تمثل عادة بكسل الشاشة الفعلي. بالنسبة للأجهزة أو البيئات التي لا تُعرف فيها أحجام البكسل الفعلية يمكن استخدام خوارزمية مشابهة لتعريف البكسل في CSS2. لاحظ أن القيمة Null تُعاد إذا لم يكن هذا العنصر مرتبطًا بشجرة المستند. كان من الأنسب تسمية هذه الطريقة getClientCTM لكن تم الإبقاء على الاسم getScreenCTM لأسباب تاريخية."
type: docs

url: /ar/java/com.aspose.html.dom.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

يرجع مصفوفة التحويل من وحدات المستخدم الحالية (أي بعد تطبيق سمة ‘transform’ إذا وجدت) إلى ملاحظة وكيل المستخدم الأب لـ "pixel". لأجهزة العرض، يمثل عادة بكسل الشاشة الفعلي. للأجهزة أو البيئات الأخرى التي لا تُعرف أحجام البكسل الفعلية، يمكن استخدام خوارزمية مشابهة لتعريف CSS2 للـ "pixel". لاحظ أن القيمة null تُعاد إذا لم يكن هذا العنصر مرتبطًا بشجرة المستند. كان من الأنسب تسمية هذه الطريقة getClientCTM، لكن تم الإبقاء على الاسم getScreenCTM لأسباب تاريخية.

```java
public SVGMatrix GetScreenCTM()
```

### قيمة الإرجاع

كائن SVGMatrix يحدد مصفوفة التحويل المعطاة.

### انظر أيضًا

* class [SVGMatrix](../../../com.aspose.html.dom.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
