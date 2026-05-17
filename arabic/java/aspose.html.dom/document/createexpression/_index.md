---
title: "Document.CreateExpression"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Document. تنشئ تعبير XPath محلل مع حزم محلولة. هذا مفيد عندما يتم إعادة استخدام التعبير في تطبيق لأنه يجعل من الممكن تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وإجراء حل مسبق لجميع بادئات الحزم التي تظهر داخل التعبير."
type: docs

url: /ar/java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

ينشئ تعبير XPath محلل مع حزم محلولة. هذا مفيد عندما يُعاد استخدام التعبير في تطبيق لأنه يتيح تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وحل جميع بادئات الحزم مسبقًا داخل التعبير.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| expression | String | سلسلة تعبير XPath التي سيتم تحليلها. |
| resolver | IXPathNSResolver | يسمح `resolver` بترجمة جميع البادئات، بما في ذلك بادئة الحزمة `xml`، داخل تعبير XPath إلى عناوين URI للحزم المناسبة. إذا تم تحديده كـ `null`، فإن أي بادئة حزمة داخل التعبير ستؤدي إلى رمي [`DOMException`](../../domexception/) مع الرمز `NAMESPACE_ERR`. |

### قيمة الإرجاع

الصيغة المجمعة لتعبير XPath.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR: يُرفع إذا كان التعبير غير قانوني وفقًا لقواعد [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [dOMException](../../domexception/) | NAMESPACE_ERR: يُرفع إذا كان التعبير يحتوي على بادئات حزم لا يمكن حلها بواسطة [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) المحدد. |

### انظر أيضًا

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
