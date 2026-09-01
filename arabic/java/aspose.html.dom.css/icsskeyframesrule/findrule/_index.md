---
title: "ICSSKeyframesRule.FindRule"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة ICSSKeyframesRule. تقوم طريقة findRule بإرجاع القاعدة التي لها مفتاح يطابق المفتاح الممرّ. إذا لم توجد مثل هذه القاعدة يتم إرجاع قيمة فارغة (null)."
type: docs

url: /ar/java/com.aspose.html.dom.css/icsskeyframesrule/findrule/
---
## ICSSKeyframesRule.FindRule method

طريقة findRule تُعيد القاعدة التي يطابق مفتاحها المفتاح الممرّر. إذا لم توجد مثل هذه القاعدة، تُرجع قيمة null.

```java
public ICSSKeyframeRule FindRule(String key)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| key | String | المفتاح الذي يصف القاعدة المراد العثور عليها. يجب أن يكون المفتاح رقمًا بين 0 و 1، وإلا يتم تجاهل القاعدة. |

### قيمة الإرجاع

إرجاع آخر [`CSSKeyframeRule`](../../icsskeyframerule/) مُعلن يطابق محدد الإطار المفتاح المحدد. إذا لم توجد قاعدة مطابقة، لا تقوم الطريقة بأي شيء.

### انظر أيضًا

* interface [ICSSKeyframeRule](../../icsskeyframerule/)
* interface [ICSSKeyframesRule](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
