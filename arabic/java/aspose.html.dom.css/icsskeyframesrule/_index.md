---
title: "واجهة ICSSKeyframesRule"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.css.ICSSKeyframesRule. الخاصية name في واجهة CSSKeyframeRule تحصل على اسم الرسوم المتحركة وتضبطه كما يستخدم في خاصية animation-name."
type: docs

url: /ar/java/com.aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

تسترجع وتعيّن خاصية name في واجهة CSSKeyframeRule اسم الرسوم المتحركة كما يُستخدم في خاصية animation-name.

```java
public interface ICSSKeyframesRule : ICSSRule
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icsskeyframesrule/cssrules/) الخاصية read-only cssRules في واجهة [`CSSKeyframeRule`](../icsskeyframerule/) تُعيد [`CSSRuleList`](../icssrulelist/) يحتوي على القواعد في قاعدة at-rule الخاصة بالـ keyframes. |
| [getName](../../com.aspose.html.dom.css/icsskeyframesrule/name/) الخاصية name في واجهة [`CSSKeyframeRule`](../icsskeyframerule/) تحصل على اسم الرسوم المتحركة وتضبطه كما يستخدم في خاصية animation-name. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [appendRule](../../com.aspose.html.dom.css/icsskeyframesrule/appendrule/)(String) | طريقة appendRule تُضيف [`CSSKeyframeRule`](../icsskeyframerule/) الممررة في نهاية مجموعة قواعد الـ keyframes. |
| [deleteRule](../../com.aspose.html.dom.css/icsskeyframesrule/deleterule/)(String) | طريقة deleteRule تحذف [`CSSKeyframeRule`](../icsskeyframerule/) بالمفتاح الممرر. إذا لم توجد قاعدة بهذا المفتاح، لا تفعل الطريقة شيئًا. |
| [findRule](../../com.aspose.html.dom.css/icsskeyframesrule/findrule/)(String) | طريقة findRule تُعيد القاعدة التي لها مفتاح يطابق المفتاح الممرر. إذا لم توجد مثل هذه القاعدة، تُرجع قيمة null. |

### انظر أيضًا

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
