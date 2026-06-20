---
title: "IXPathEvaluator.Evaluate"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة IXPathEvaluator. تُقيِّم سلسلة تعبير XPath وتعيد نتيجة من النوع المحدد إذا كان ذلك ممكنًا."
type: docs

url: /ar/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

يقيم سلسلة تعبير XPath ويعيد نتيجة من النوع المحدد إذا كان ذلك ممكنًا.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| تعبير | String | سلسلة تعبير XPath التي سيتم تحليلها وتقييمها. |
| contextNode | Node | الـ `context` هو عقدة السياق لتقييم هذا التعبير XPath. إذا تم الحصول على [`IXPathEvaluator`](../) عن طريق تحويل [`Document`](../../../com.aspose.html.dom/document/) فإن هذه يجب أن تكون مملوكة لنفس المستند ويجب أن تكون [`Document`](../../../com.aspose.html.dom/document/)، [`Element`](../../../com.aspose.html.dom/element/)، [`Attr`](../../../com.aspose.html.dom/attr/)، [`Text`](../../../com.aspose.html.dom/text/)، [`CDATASection`](../../../com.aspose.html.dom/cdatasection/)، [`Comment`](../../../com.aspose.html.dom/comment/)، [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/)، أو عقدة XPathNamespace. إذا كانت عقدة السياق هي [`Text`](../../../com.aspose.html.dom/text/) أو [`CDATASection`](../../../com.aspose.html.dom/cdatasection/)، فإن السياق يُفسَّر كعقدة النص المنطقي بالكامل كما يراها XPath، ما لم تكن العقدة فارغة وفي هذه الحالة قد لا تُستخدم كسياق XPath. |
| resolver | IXPathNSResolver | يسمح `resolver` بترجمة جميع البادئات، بما في ذلك بادئة الحزمة `xml`، داخل تعبير XPath إلى عناوين URI للحزم المناسبة. إذا تم تحديده كـ `null`، فإن أي بادئة حزمة داخل التعبير ستؤدي إلى رمي [`DOMException`](../../../com.aspose.html.dom/domexception/) مع الرمز `NAMESPACE_ERR`. |
| type | XPathResultType | إذا تم تحديد `type` معين، فستُعاد النتيجة كنوع مطابق. بالنسبة لنتائج XPath 1.0، يجب أن يكون هذا أحد قيم تعداد [`XPathResultType`](../../xpathresulttype/). |
| result | Object | الـ`result` يحدد كائن نتيجة محدد يمكن إعادة استخدامه وإرجاعه بواسطة هذه الطريقة. إذا تم تحديده كـ`null` أو إذا لم تقم التنفيذية بإعادة استخدام النتيجة المحددة، فسيتم إنشاء كائن نتيجة جديد وإرجاعه. بالنسبة لنتائج XPath 1.0، سيكون هذا الكائن من النوع [`IXPathResult`](../../ixpathresult/). |

### قيمة الإرجاع

نتيجة تقييم تعبير XPath. بالنسبة لنتائج XPath 1.0، سيكون هذا الكائن من النوع [`IXPathResult`](../../ixpathresult/).

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: يُرفع إذا كان التعبير غير قانوني وفقًا لقواعد [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: يُرفع إذا تعذّر تحويل النتيجة لإرجاع النوع المحدد. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: يُرفع إذا كان التعبير يحتوي على بادئات حزم لا يمكن حلها بواسطة [`IXPathNSResolver`](../../ixpathnsresolver/) المحدد. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: العقدة من مستند غير مدعوم من قبل هذا [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: العقدة ليست من النوع المسموح به كعقدة سياق XPath أو نوع الطلب غير مسموح به من قبل هذا [`IXPathEvaluator`](../). |

### انظر أيضًا

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
