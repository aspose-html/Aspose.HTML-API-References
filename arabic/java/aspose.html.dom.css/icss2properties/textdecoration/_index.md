---
title: "ICSS2Properties.TextDecoration"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "خاصية ICSS2Properties. تصف هذه الخاصية الزخارف التي تُضاف إلى نص العنصر. إذا تم تحديد الخاصية لعنصر من مستوى الكتلة فإنها تؤثر على جميع العناصر التابعة من مستوى السطر داخل العنصر. إذا تم تحديدها لعنصر من مستوى السطر داخل أو تؤثر عليه فإنها تؤثر على جميع الصناديق التي يولدها العنصر. إذا كان للعنصر لا محتوى أو لا نص (مثال: عنصر IMG في HTML) يجب على وكلاء المستخدم تجاهل هذه الخاصية."
type: docs

url: /ar/java/com.aspose.html.dom.css/icss2properties/textdecoration/
---
## ICSS2Properties.TextDecoration property

تصف هذه الخاصية الزخارف التي تُضاف إلى نص العنصر. إذا تم تحديد الخاصية لعنصر [block-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#block-level)، فإنها تؤثر على جميع العناصر التابعة من مستوى السطر داخل العنصر. إذا تم تحديدها لعنصر [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) (أو تؤثر عليه)، فإنها تؤثر على جميع الصناديق التي يولدها العنصر. إذا كان للعنصر لا محتوى أو لا نص (مثال، عنصر IMG في HTML)، يجب على وكلاء المستخدم [تجاهل](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#ignore) هذه الخاصية.

القيم لها المعاني التالية:

none - لا ينتج أي زخرفة نصية.underline - يُسطر كل سطر من النص. overline - يُضاف خط فوق كل سطر من النص. line-through - يُرسم خط عبر منتصف كل سطر من النص. blink - النص يومض (يتناوب بين الظهور والاختفاء).

```java
public String TextDecoration { get; set; }
```

### قيمة الإرجاع

خاصية text-decoration

### انظر أيضًا

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
