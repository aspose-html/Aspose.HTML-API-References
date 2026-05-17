---
title: "IXPathEvaluator.CreateExpression"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة IXPathEvaluator. تُنشئ تعبير XPath مُحلَّل مع حزم مُحلَّة. هذا مفيد عندما يُعاد استخدام التعبير في تطبيق لأن ذلك يجعل من الممكن تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وإعادة حل جميع بادئات الحزم التي تظهر داخل التعبير."
type: docs

url: /ar/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

ينشئ تعبير XPath محلل مع حزم محلولة. هذا مفيد عندما يُعاد استخدام التعبير في تطبيق لأنه يتيح تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وحل جميع بادئات الحزم مسبقًا داخل التعبير.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| expression | String | سلسلة تعبير XPath التي سيتم تحليلها. |
| resolver | IXPathNSResolver | الـ `resolver` يسمح بترجمة جميع البادئات، بما في ذلك بادئة الحزمة `xml`، داخل تعبير XPath إلى عناوين URI مناسبة للحزم. إذا تم تحديده كـ `null`، فإن أي بادئة حزمة داخل التعبير ستؤدي إلى رمي [`DOMException`](../../../com.aspose.html.dom/domexception/) مع الرمز `NAMESPACE_ERR`. |

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
