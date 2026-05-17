---
title: "ICSS2Properties.Volume"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "خاصية ICSS2Properties. يشير الحجم إلى متوسط حجم الموجة. بمعنى آخر قد يتجاوز صوت عالي النبرة عند مستوى حجم 50 القمة بشكل كبير. من المحتمل أن تكون القيم القابلة للتعديل يدوياً للراحة، على سبيل المثال باستخدام تحكم مادي في الحجم يزيد من القيم 0 و 100 بنسبة متناسبة. ما تفعله هذه الخاصية هو تعديل النطاق الديناميكي."
type: docs

url: /ar/java/com.aspose.html.dom.css/icss2properties/volume/
---
## ICSS2Properties.Volume property

يشير الحجم إلى متوسط حجم الموجة. بمعنى آخر قد يتجاوز صوت عالي النبرة عند مستوى حجم 50 القمة بشكل كبير. من المحتمل أن تكون القيم القابلة للتعديل يدوياً للراحة، على سبيل المثال باستخدام تحكم مادي في الحجم (الذي يزيد من القيم 0 و 100 بنسبة متناسبة)؛ ما تفعله هذه الخاصية هو تعديل النطاق الديناميكي.

القيم لها المعاني التالية:

'[number](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-number)' - أي رقم بين '0' و '100'. '0' تمثل الحد الأدنى لمستوى الصوت المسموع و 100 تمثل الحد الأقصى المريح. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - تُحسب قيم النسبة المئوية نسبةً إلى القيمة الموروثة، ثم تُقَص إلى النطاق '0' إلى '100'. silent - لا صوت على الإطلاق. القيمة '0' لا تعني نفس معنى 'silent'. x-soft - نفس '0'. soft - نفس '25'. medium - نفس '50'. loud - نفس '75'. x-loud - نفس '100'.

```java
public String Volume { get; set; }
```

### قيمة الإرجاع

خاصية volume

### انظر أيضًا

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
