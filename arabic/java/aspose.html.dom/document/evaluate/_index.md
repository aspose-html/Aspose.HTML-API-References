---
title: "Document.Evaluate"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Document. تقيم سلسلة تعبير XPath وتعيد نتيجة من النوع المحدد إذا كان ذلك ممكنًا"
type: docs

url: /ar/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

يقيم سلسلة تعبير XPath ويعيد نتيجة من النوع المحدد إذا كان ذلك ممكنًا.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| expression | String | سلسلة تعبير XPath التي سيتم تحليلها وتقييمها. |
| contextNode | Node | السياق هو عقدة السياق لتقييم هذا التعبير XPath. |
| resolver | IXPathNSResolver | يسمح المحلّل بترجمة جميع البادئات، بما في ذلك بادئة حزمة xml، داخل تعبير XPath إلى عناوين URI للحزمة المناسبة. |
| النوع | XPathResultType | إذا تم تحديد نوع معين، فستُعاد النتيجة كنوع مطابق. |
| result | كائن | تحدد النتيجة كائن نتيجة محدد قد يُعاد استخدامه وتُعيده هذه الطريقة. |

### قيمة الإرجاع

نتيجة تقييم تعبير XPath.

### انظر أيضًا

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
