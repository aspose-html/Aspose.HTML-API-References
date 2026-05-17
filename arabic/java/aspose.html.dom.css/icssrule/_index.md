---
title: "واجهة ICSSRule"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.css.ICSSRule. واجهة CSSRule هي الواجهة الأساسية المجردة لأي نوع من عبارات CSS. يشمل ذلك مجموعات القواعد والقواعد الخاصة (at-rules). من المتوقع أن تحتفظ التنفيذ بجميع القواعد المحددة في ورقة أنماط CSS حتى إذا لم يتعرف المحلل على القاعدة. القواعد غير المعروفة يتم تمثيلها باستخدام الواجهة."
type: docs

url: /ar/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

واجهة CSSRule هي الواجهة الأساسية المجردة لأي نوع من بيانات CSS. وتشمل مجموعات القواعد والقواعد الخاصة. من المتوقع أن تحتفظ أي تنفيذ بجميع القواعد المحددة في ورقة أنماط CSS، حتى إذا لم يتعرف المُحلل على القاعدة. تُمثَّل القواعد غير المعروفة باستخدام هذه الواجهة.

```java
public interface ICSSRule
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) إذا كانت هذه القاعدة محتواة داخل قاعدة أخرى (مثل قاعدة نمط داخل كتلة @media)، فهذه هي القاعدة الحاوية. إذا لم تكن هذه القاعدة متداخلة داخل أي قواعد أخرى، فإنها تُعيد null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) خاصية parentStyleSheet في واجهة `CSSRule` تُعيد كائن [`StyleSheet`](../istylesheet/) الذي تُعرّف فيه القاعدة الحالية. |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) نوع القاعدة، كما هو مُعرّف في [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type). من المتوقع أن تُستخدم طرق التحويل الخاصة بالربط للتحويل من مثيل لواجهة CSSRule إلى الواجهة المشتقة المحددة بالنوع. |

### انظر أيضًا

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
