---
title: Document.Evaluate
second_title: Aspose.HTML لمرجع .NET API
description: Document طريقة. بتقييم سلسلة تعبير XPath وإرجاع نتيجة من النوع المحدد إن أمكن.
type: docs
weight: 950
url: /ar/net/aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

بتقييم سلسلة تعبير XPath وإرجاع نتيجة من النوع المحدد إن أمكن.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| expression | String | سلسلة تعبير XPath المراد تحليلها وتقييمها. |
| contextNode | Node | السياق هو عقدة السياق لتقييم تعبير XPath هذا. |
| resolver | IXPathNSResolver | يسمح المحلل بترجمة جميع البادئات ، بما في ذلك بادئة مساحة الاسم xml ، ضمن تعبير XPath إلى URIs لمساحة الاسم المناسبة. |
| type | XPathResultType | إذا تم تحديد نوع معين ، فسيتم إرجاع النتيجة كنوع مطابق. |
| result | Object | تحدد النتيجة كائن نتيجة محدد يمكن إعادة استخدامه وإعادته بهذه الطريقة. |

### قيمة الإرجاع

نتيجة تقييم تعبير XPath .

### أنظر أيضا

* interface [IXPathResult](../../../aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* مساحة الاسم [Aspose.Html.Dom](../../document/)
* المجسم [Aspose.HTML](../../../)


