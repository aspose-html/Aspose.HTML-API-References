---
title: "ICSSStyleSheet.InsertRule"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة ICSSStyleSheet. طريقة CSSStyleSheet.insertRule تُدرج قاعدة CSS جديدة في ورقة الأنماط الحالية مع بعض القيود"
type: docs

url: /ar/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

طريقة CSSStyleSheet.insertRule() تُدرج قاعدة CSS جديدة في ورقة الأنماط الحالية، مع بعض القيود.

ملاحظة: على الرغم من أن insertRule() هي طريقة حصرية لـ [`CSSStyleSheet`](../)، إلا أنها في الواقع تُدرج القاعدة في CSSStyleSheet.cssRules — قائمة القواعد الداخلية [`CSSRuleList`](../../icssrulelist/).

```java
public long InsertRule(String rule, int index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| قاعدة | String | سلسلة نصية تحتوي على القاعدة التي سيتم إدراجها. ما يجب أن تحتويه القاعدة المُدرجة يعتمد على نوعها: |
| index | Int32 | عدد صحيح موجب أصغر من أو يساوي stylesheet.cssRules.length، يمثل موضع القاعدة المُدرجة حديثًا في CSSStyleSheet.cssRules. القيمة الافتراضية هي 0. |

### قيمة الإرجاع

فهرس القاعدة المُدرجة حديثًا داخل قائمة قواعد ورقة الأنماط.

## ملاحظات

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

المرجع

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### انظر أيضًا

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
