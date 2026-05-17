---
title: "واجهة ICSSStyleSheet"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.css.ICSSStyleSheet. تمثل واجهة CSSStyleSheet ورقة أنماط CSS واحدة وتتيح لك فحص وتعديل قائمة القواعد الموجودة في ورقة الأنماط. إنها ترث الخصائص والطرق من الواجهة الأم IStyleSheet."
type: docs

url: /ar/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

تمثل واجهة CSSStyleSheet ورقة أنماط CSS واحدة، وتتيح لك فحص وتعديل قائمة القواعد الموجودة في ورقة الأنماط. إنها ترث الخصائص والطرق من الواجهة الأم، [`IStyleSheet`](../istylesheet/).

تتكون ورقة الأنماط من مجموعة من كائنات [`ICSSRule`](../icssrule/) التي تمثل كل قاعدة في ورقة الأنماط. القواعد موجودة في [`ICSSRuleList`](../icssrulelist/)، والتي يمكن الحصول عليها من خاصية cssRules لورقة الأنماط.

على سبيل المثال، قد تكون إحدى القواعد كائنًا من نوع [`ICSSStyleRule`](../icssstylerule/) يحتوي على نمط مثل

```java
h1, h2 {   font-size: 16pt; }
```

قد تكون قاعدة أخرى قاعدة at-rule مثل @import أو @media، وما إلى ذلك.

```java
public interface ICSSStyleSheet : IStyleSheet
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) الخاصية للقراءة فقط cssRules في CSSStyleSheet تُرجع [`CSSRuleList`](../icssrulelist/) حيًا يوفر قائمة لحظية ومُحدَّثة لكل قاعدة CSS تشكل ورقة الأنماط. كل عنصر في القائمة هو [`CSSRule`](../icssrule/) يعرّف قاعدة واحدة. |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) الخاصية للقراءة فقط ownerRule في CSSStyleSheet تُرجع [`CSSImportRule`](../icssimportrule/) المقابلة لقاعدة at-rule @import التي استوردت ورقة الأنماط إلى المستند. إذا لم يتم استيراد ورقة الأنماط إلى المستند باستخدام @import، فإن القيمة المرجعة تكون null. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | طريقة `CSSStyleSheet` deleteRule() تُزيل قاعدة من كائن ورقة الأنماط. |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | طريقة CSSStyleSheet.insertRule() تُدرج قاعدة CSS جديدة في ورقة الأنماط الحالية، مع بعض القيود. |

## ملاحظات

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

المرجع

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### انظر أيضًا

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
