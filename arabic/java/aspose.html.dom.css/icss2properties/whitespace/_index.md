---
title: "ICSS2Properties.WhiteSpace"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "خاصية ICSS2Properties. هذه الخاصية تصف كيفية معالجة الفراغ داخل العنصر. القيم لها المعاني التالية"
type: docs

url: /ar/java/com.aspose.html.dom.css/icss2properties/whitespace/
---
## ICSS2Properties.WhiteSpace property

هذه الخاصية تصف كيفية معالجة [الفراغ](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#whitespace) داخل العنصر. القيم لها المعاني التالية:

normal - هذه القيمة توجه وكلاء المستخدم إلى دمج تسلسلات الفراغ، وكسر الأسطر حسب الحاجة لملء صناديق السطر. قد تُنشأ فواصل أسطر إضافية بوجود "\A" في المحتوى المُولد (مثال، للعنصر BR في HTML). pre - هذه القيمة تمنع وكلاء المستخدم من دمج تسلسلات الفراغ. تُكسر الأسطر فقط عند فواصل الأسطر في المصدر، أو عند وجود "\A" في المحتوى المُولد. nowrap - هذه القيمة تُدمج الفراغ كما في 'normal'، لكنها تُقمع فواصل الأسطر داخل النص باستثناء تلك التي تُنشأ بوجود "\A" في المحتوى المُولد (مثال، للعنصر BR في HTML).

```java
public String WhiteSpace { get; set; }
```

### قيمة الإرجاع

خاصية white-space

### انظر أيضًا

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
