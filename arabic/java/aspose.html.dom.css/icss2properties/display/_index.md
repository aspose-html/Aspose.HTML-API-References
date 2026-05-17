---
title: "ICSS2Properties.Display"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "خاصية ICSS2Properties. قيم هذه الخاصية لها المعاني التالية"
type: docs

url: /ar/java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

قيم هذه الخاصية لها المعاني التالية:

block - هذه القيمة تجعل العنصر يولد صندوق كتلة رئيسي. inline - هذه القيمة تجعل العنصر يولد صندوقًا داخليًا واحدًا أو أكثر. list-item - هذه القيمة تجعل العنصر (مثال، LI في HTML) يولد صندوق كتلة رئيسي وصندوق قائمة داخلية. للحصول على معلومات حول القوائم وأمثلة على تنسيق القوائم، يرجى مراجعة القسم المتعلق بـ [lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists). marker - هذه القيمة تعلن عن [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html) قبل أو بعد الصندوق لتكون علامة. يجب استخدام هذه القيمة فقط مع [:before و :after pseudo-elements](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content) المرتبطة بعناصر مستوى كتلة. في الحالات الأخرى، تُفسَّر هذه القيمة كـ 'inline'. يرجى مراجعة القسم المتعلق بـ [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) لمزيد من المعلومات. none - هذه القيمة تجعل العنصر لا يولد أي صناديق في [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure) (أي أن العنصر لا يؤثر على التخطيط). العناصر المتفرعة لا تولد أي صناديق أيضًا؛ لا يمكن تجاوز هذا السلوك بتعيين خاصية ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) على المتفرعات. يرجى ملاحظة أن display بقيمة 'none' لا ينشئ صندوقًا غير مرئي؛ إنه لا ينشئ أي صندوق على الإطلاق. يتضمن CSS آليات تمكّن العنصر من توليد صناديق في بنية التنسيق تؤثر على التنسيق لكنها غير مرئية نفسها. يرجى مراجعة القسم المتعلق بـ [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) للتفاصيل. run-in and compact - هذه القيم تُنشئ إما صناديق كتلية أو داخلية، حسب السياق. تُطبق الخصائص على صناديق run-in و compact بناءً على وضعها النهائي (مستوى داخلي أو كتلة). على سبيل المثال، خاصية ['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space) تُطبق فقط إذا أصبح الصندوق صندوق كتلة. table, inline-table, table-row-group, [table-column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column), table-column-group, table-header-group, table-footer-group, table-row, table-cell, and table-caption - هذه القيم تجعل العنصر يتصرف كعنصر جدول (مع مراعاة القيود الموضحة في الفصل المتعلق بـ [tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html)).

```java
public String Display { get; set; }
```

### قيمة الإرجاع

خاصية display

### انظر أيضًا

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
