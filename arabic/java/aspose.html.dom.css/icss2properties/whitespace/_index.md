---
title: "ICSS2Properties.WhiteSpace"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "خاصية ICSS2Properties. تُعلن هذه الخاصية عن كيفية معالجة المسافات البيضاء داخل العنصر. القيم لها المعاني التالية"
type: docs

url: /ar/java/com.aspose.html.dom.css/icss2properties/whitespace/
---
## ICSS2Properties.WhiteSpace property

تُعلن هذه الخاصية عن كيفية معالجة [whitespace](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#whitespace) داخل العنصر. القيم لها المعاني التالية:

normal - تُوجّه هذه القيمة عوامل المستخدم إلى دمج تسلسلات المسافات البيضاء، وكسر الأسطر حسب الضرورة لملء صناديق السطر. قد تُنشأ فواصل أسطر إضافية بوجود \"\\A\" في المحتوى المُولد (مثال، للعنصر BR في HTML). pre - تمنع هذه القيمة عوامل المستخدم من دمج تسلسلات المسافات البيضاء. تُكسر الأسطر فقط عند فواصل الأسطر في المصدر، أو عند وجود \"\\A\" في المحتوى المُولد. nowrap - تُدمج المسافات البيضاء كما في 'normal'، لكن تُقمع فواصل الأسطر داخل النص باستثناء تلك التي تُنشأ بوجود \"\\A\" في المحتوى المُولد (مثال، للعنصر BR في HTML).

```java
public String WhiteSpace { get; set; }
```

### قيمة الإرجاع

خاصية white-space

### انظر أيضًا

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
