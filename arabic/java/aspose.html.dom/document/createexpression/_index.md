---
title: "Document.CreateExpression"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Document. ينشئ تعبير XPath محلل مع الحزم المحلولة. هذا مفيد عندما يتم إعادة استخدام التعبير في تطبيق لأنه يجعل من الممكن تجميع سلسلة التعبير `String` إلى شكل داخلي أكثر كفاءة وإعادة حل جميع بادئات الحزم التي تظهر داخل التعبير مسبقًا."
type: docs

url: /ar/java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

ينشئ تعبير XPath محلل مع حزم محلولة. يكون هذا مفيدًا عندما يُعاد استخدام التعبير في تطبيق لأنه يتيح تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وحل جميع بادئات الحزم الموجودة في التعبير مسبقًا.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| تعبير | String | سلسلة تعبير XPath التي سيتم تحليلها. |
| resolver | IXPathNSResolver | يسمح `resolver` بترجمة جميع البادئات، بما في ذلك بادئة الحزمة `xml`، داخل تعبير XPath إلى عناوين URI مناسبة للحزمة. إذا تم تحديده كـ `null`، فإن أي بادئة حزمة داخل التعبير ستؤدي إلى رمي [`DOMException`](../../domexception/) مع الرمز `NAMESPACE_ERR`. |

### قيمة الإرجاع

الصيغة المجمعة لتعبير XPath.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR: يُرفع إذا كان التعبير غير قانوني وفقًا لقواعد [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [dOMException](../../domexception/) | NAMESPACE_ERR: يُرفع إذا كان التعبير يحتوي على بادئات حزمة لا يمكن حلها بواسطة [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) المحدد. |

### انظر أيضًا

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
