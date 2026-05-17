---
title: "ICSS2Properties.PauseAfter"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "خاصية ICSS2Properties. تحدد هذه الخصائص وقفة يجب ملاحظتها قبل أو بعد نطق محتوى العنصر. القيم لها المعاني التالية"
type: docs

url: /ar/java/com.aspose.html.dom.css/icss2properties/pauseafter/
---
## ICSS2Properties.PauseAfter property

تحدد هذه الخصائص وقفة يجب ملاحظتها قبل (أو بعد) نطق محتوى العنصر. القيم لها المعاني التالية:

'[time](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-time)' - يعبر عن الوقفة بوحدات زمنية مطلقة (ثوانٍ وملليثوانٍ).'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - يشير إلى معكوس قيمة خاصية ['speech-rate'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-speech-rate). على سبيل المثال، إذا كان speech-rate هو 120 كلمة في الدقيقة (أي أن الكلمة تستغرق نصف ثانية، أو 500 ملليثانية) فإن ['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) بنسبة 100% يعني وقفة قدرها 500 ملليثانية و['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) بنسبة 20% يعني 100 ملليثانية.

```java
public String PauseAfter { get; set; }
```

### قيمة الإرجاع

خاصية pause-after

### انظر أيضًا

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
