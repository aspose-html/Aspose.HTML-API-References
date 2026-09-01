---
title: "IXPathEvaluator.CreateExpression"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة IXPathEvaluator. تُنشئ تعبير XPath مُحلَّل مع حزم محلولة. هذا مفيد عندما يُعاد استخدام تعبير في تطبيق لأنه يتيح تجميع سلسلة التعبير String إلى شكل داخلي أكثر كفاءة وإعادة حل جميع بادئات الحزم التي تظهر داخل التعبير."
type: docs

url: /ar/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

ينشئ تعبير XPath محلل مع حزم محلولة. يكون هذا مفيدًا عندما يُعاد استخدام التعبير في تطبيق لأنه يتيح تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وحل جميع بادئات الحزم الموجودة في التعبير مسبقًا.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| تعبير | String | سلسلة تعبير XPath التي سيتم تحليلها. |
| resolver | IXPathNSResolver | يسمح `resolver` بترجمة جميع البادئات، بما في ذلك بادئة الحزمة `xml`، داخل تعبير XPath إلى عناوين URI للحزم المناسبة. إذا تم تحديده كـ `null`، فإن أي بادئة حزمة داخل التعبير ستؤدي إلى رمي [`DOMException`](../../../com.aspose.html.dom/domexception/) مع الرمز `NAMESPACE_ERR`. |

### قيمة الإرجاع

الصيغة المجمعة لتعبير XPath.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: يُرفع إذا كان التعبير غير قانوني وفقًا لقواعد [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: يُرفع إذا كان التعبير يحتوي على بادئات حزم لا يمكن حلها بواسطة [`IXPathNSResolver`](../../ixpathnsresolver/) المحدد. |

### انظر أيضًا

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
