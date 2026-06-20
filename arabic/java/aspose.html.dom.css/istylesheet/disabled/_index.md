---
title: "IStyleSheet.Disabled"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "خاصية IStyleSheet. خاصية disabled في واجهة StyleSheet تحدد ما إذا كانت ورقة الأنماط محجوبة من التطبيق على المستند."
type: docs

url: /ar/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

خاصية disabled في واجهة [`StyleSheet`](../) تحدد ما إذا كانت ورقة الأنماط محجوبة من التطبيق على المستند.

يمكن إلغاء تفعيل ورقة الأنماط عن طريق تعيين هذه الخاصية إلى true يدويًا أو إذا كانت ورقة أنماط بديلة غير نشطة. لاحظ أن disabled == false لا يضمن تطبيق ورقة الأنماط (قد تُزال من المستند، على سبيل المثال).

قد يتسبب تعديل هذه الخاصية في إعادة حل النمط للمستند. تُطبق ورقة الأنماط فقط إذا كان تعريف الوسيط المناسب موجودًا وكانت خاصية disabled مساوية لـ false. لذا، إذا لم يطبق الوسيط على وكيل المستخدم الحالي، يتم تجاهل خاصية disabled.

```java
public bool Disabled { get; set; }
```

### قيمة الإرجاع

يجب أن تُعيد خاصية disabled، عند القراءة، القيمة true إذا كان علم disabled مُفعَّل، أو false خلاف ذلك. عند الضبط، يجب أن تُعيّن خاصية disabled علم disabled إذا كانت القيمة الجديدة true، أو تُزيل علم disabled خلاف ذلك.

### Property Value

يجب أن تُعيد خاصية disabled، عند القراءة، القيمة true إذا كان علم disabled مُفعَّل، أو false خلاف ذلك. عند الضبط، يجب أن تُعيّن خاصية disabled علم disabled إذا كانت القيمة الجديدة true، أو تُزيل علم disabled خلاف ذلك.

## ملاحظات

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

المرجع

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### انظر أيضًا

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
