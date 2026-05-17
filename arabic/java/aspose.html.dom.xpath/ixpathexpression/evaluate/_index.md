---
title: "IXPathExpression.Evaluate"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة IXPathExpression. تقوم بتقييم هذا التعبير XPath وتعيد نتيجة."
type: docs

url: /ar/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

يقيم هذا التعبير XPath ويُرجع نتيجة.

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| contextNode | Node | الـ `context` هو عقدة السياق لتقييم هذا التعبير XPath. إذا تم الحصول على [`IXPathEvaluator`](../../ixpathevaluator/) عن طريق تحويل [`Document`](../../../com.aspose.html.dom/document/) فإن هذا يجب أن يكون مملوكًا لنفس المستند ويجب أن يكون إما [`Document`](../../../com.aspose.html.dom/document/)، [`Element`](../../../com.aspose.html.dom/element/)، [`Attr`](../../../com.aspose.html.dom/attr/)، [`Text`](../../../com.aspose.html.dom/text/)، [`CDATASection`](../../../com.aspose.html.dom/cdatasection/)، [`Comment`](../../../com.aspose.html.dom/comment/)، [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/)، أو عقدة XPathNamespace. إذا كانت عقدة السياق هي [`Text`](../../../com.aspose.html.dom/text/) أو [`CDATASection`](../../../com.aspose.html.dom/cdatasection/)، فسيتم تفسير السياق ككل عقدة نصية منطقية كما يراها XPath، ما لم تكن العقدة فارغة في هذه الحالة قد لا تُستخدم كسياق XPath. |
| type | XPathResultType | إذا تم تحديد `type` معين، فسيتم تحويل النتيجة لإرجاع النوع المحدد اعتمادًا على تحويلات XPath وستفشل إذا لم يكن التحويل المطلوب ممكنًا. يجب أن يكون هذا أحد قيم [`XPathResultType`](../../xpathresulttype/). |
| result | Object | الـ `result` يحدد كائن نتيجة محدد قد يُعاد استخدامه وتُرجع هذه الطريقة. إذا تم تحديده كـ `null` أو إذا لم تُعيد التنفيذية استخدام النتيجة المحددة، فسيتم إنشاء كائن نتيجة جديد وإرجاعه. بالنسبة لنتائج XPath 1.0، سيكون هذا الكائن من النوع [`IXPathResult`](../../ixpathresult/). |

### قيمة الإرجاع

نتيجة تقييم تعبير XPath. بالنسبة لنتائج XPath 1.0، سيكون هذا الكائن من النوع [`IXPathResult`](../../ixpathresult/).

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: يُرفع إذا تعذّر تحويل النتيجة لإرجاع النوع المحدد. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: العقدة Node من مستند غير مدعوم من قبل [`IXPathEvaluator`](../../ixpathevaluator/) الذي أنشأ هذا [`IXPathExpression`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: العقدة Node ليست من النوع المسموح به كعقدة سياق XPath أو أن نوع الطلب غير مسموح به من قبل هذا [`IXPathExpression`](../). |

### انظر أيضًا

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
