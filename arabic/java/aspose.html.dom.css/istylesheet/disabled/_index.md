---
title: "IStyleSheet.Disabled"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "خاصية IStyleSheet. خاصية disabled في واجهة StyleSheet تحدد ما إذا كانت الورقة النمطية مُمنعة من التطبيق على المستند."
type: docs

url: /ar/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

خاصية disabled في واجهة [`StyleSheet`](../) تحدد ما إذا كانت الورقة النمطية مُمنعة من التطبيق على المستند.

يمكن تعطيل ورقة نمطية عن طريق ضبط هذه الخاصية يدويًا إلى true أو إذا كانت ورقة نمطية بديلة غير نشطة. لاحظ أن disabled == false لا يضمن تطبيق الورقة النمطية (قد تُزال من المستند، على سبيل المثال).

قد يتسبب تعديل هذه الخاصية في حل جديد للأنماط للمستند. تُطبق ورقة النمط فقط إذا كان تعريف الوسيط المناسب موجودًا وكانت خاصية disabled تساوي false. لذا، إذا لم ينطبق الوسيط على وكيل المستخدم الحالي، يتم تجاهل خاصية disabled.

```java
public bool Disabled { get; set; }
```

### قيمة الإرجاع

The disabled attribute, on getting, must return true if the disabled flag is set, or false otherwise. On setting, the disabled attribute must set the disabled flag if the new value is true, or unset the disabled flag otherwise.

### Property Value

The disabled attribute, on getting, must return true if the disabled flag is set, or false otherwise. On setting, the disabled attribute must set the disabled flag if the new value is true, or unset the disabled flag otherwise.

## ملاحظات

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

المرجع

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### انظر أيضًا

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
