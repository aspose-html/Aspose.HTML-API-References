---
title: "ICSS2Properties.UnicodeBidi"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "خاصية ICSS2Properties. القيم لهذه الخاصية لها المعاني التالية"
type: docs

url: /ar/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

القيم لهذه الخاصية لها المعاني التالية:

normal - لا يفتح العنصر مستوى إضافيًا من الإدراج بالنسبة إلى خوارزمية الاتجاه الثنائي. بالنسبة للعناصر ذات المستوى داخل السطر، يعمل إعادة الترتيب الضمني عبر حدود العنصر. embed - إذا كان العنصر داخل سطر، فإن هذه القيمة تفتح مستوى إضافيًا من الإدراج بالنسبة إلى خوارزمية الاتجاه الثنائي. يتم تحديد اتجاه هذا المستوى بواسطة خاصية ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction). داخل العنصر، يتم إعادة الترتيب ضمنيًا. وهذا يعادل إضافة LRE (U+202A؛ لـ 'direction: ltr') أو RLE (U+202B؛ لـ 'direction: rtl') في بداية العنصر و PDF (U+202C) في نهايته. bidi-override - إذا كان العنصر داخل سطر أو عنصر كتلي يحتوي فقط على عناصر داخل سطر، فإن هذا يخلق تجاوزًا. هذا يعني أنه داخل العنصر، يتم إعادة الترتيب بصرامة وفقًا لخاصية ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction)؛ يتم تجاهل الجزء الضمني من خوارزمية الاتجاه الثنائي. وهذا يعادل إضافة LRO (U+202D؛ لـ 'direction: ltr') أو RLO (U+202E؛ لـ 'direction: rtl') في بداية العنصر و PDF (U+202C) في نهايته.

```java
public String UnicodeBidi { get; set; }
```

### قيمة الإرجاع

خاصية unicode-bidi

### انظر أيضًا

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
