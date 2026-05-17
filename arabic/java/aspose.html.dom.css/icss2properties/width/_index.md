---
title: "ICSS2Properties.Width"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "خاصية ICSS2Properties. تحدد هذه الخاصية عرض المحتوى للصناديق التي تُنشأ بواسطة عناصر مستوى الكتلة والعناصر المستبدلة."
type: docs

url: /ar/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

تحدد هذه الخاصية [عرض المحتوى](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) للصناديق التي تُنشأ بواسطة عناصر مستوى الكتلة و[العناصر المستبدلة](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element).

هذه الخاصية لا تنطبق على العناصر غير المستبدلة [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) elements. عرض صناديق العنصر غير المستبدل داخل السطر هو عرض المحتوى المرسوم داخلها (قبل أي إزاحة نسبية للأطفال). تذكر أن صناديق السطر تتدفق إلى [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box). عرض صناديق السطر يُحدد بواسطة [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block)، لكن قد يتم تقصيره بوجود [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats).

عرض صندوق العنصر المستبدل هو [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic) وقد يتم تحجيمه بواسطة وكيل المستخدم إذا كانت قيمة هذه الخاصية مختلفة عن 'auto'.

القيم لها المعاني التالية:

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - يحدد عرضًا ثابتًا.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - يحدد عرضًا كنسبة مئوية. تُحسب النسبة المئوية بالنسبة إلى عرض [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block).auto - يعتمد العرض على قيم الخصائص الأخرى. راجع الأقسام أدناه. ملاحظة: القيم السالبة لـ ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) غير قانونية.

```java
public String Width { get; set; }
```

### قيمة الإرجاع

خاصية العرض

### انظر أيضًا

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
