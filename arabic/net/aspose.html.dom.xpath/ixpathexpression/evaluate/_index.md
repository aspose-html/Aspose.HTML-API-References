---
title: IXPathExpression.Evaluate
second_title: Aspose.HTML لمرجع .NET API
description: IXPathExpression طريقة. بتقييم تعبير XPath هذا وإرجاع نتيجة.
type: docs
weight: 10
url: /ar/net/aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

بتقييم تعبير XPath هذا وإرجاع نتيجة.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| contextNode | Node | ال`سياق` هي عقدة سياق لتقييم تعبير XPath هذا. إذا كان ملف[`IXPathEvaluator`](../../ixpathevaluator/) تم الحصول عليها عن طريق صب[`Document`](../../../aspose.html.dom/document/) إذًا يجب أن يكون هذا مملوكًا لنفس المستند ويجب أن يكون ملف[`Document`](../../../aspose.html.dom/document/) و[`Element`](../../../aspose.html.dom/element/) و[`Attr`](../../../aspose.html.dom/attr/) ، [`Text`](../../../aspose.html.dom/text/) و[`CDATASection`](../../../aspose.html.dom/cdatasection/) و[`Comment`](../../../aspose.html.dom/comment/) و[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) أو أوXPathNamespace العقدة. إذا كانت عقدة السياق هي ملف[`Text`](../../../aspose.html.dom/text/) أو أ[`CDATASection`](../../../aspose.html.dom/cdatasection/)، ثم يتم تفسير السياق على أنه عقدة النص المنطقي بالكامل كما يراها XPath ، إلا إذا كانت العقدة فارغة وفي هذه الحالة قد لا تعمل كسياق XPath. |
| type | XPathResultType | إذا كان ملف`يكتب` تم تحديده ، ثم سيتم إجبار النتيجة على إرجاع النوع المحدد الذي يعتمد على تحويلات XPath والفشل إذا كان الإكراه المطلوب غير ممكن. يجب أن تكون إحدى قيم[`XPathResultType`](../../xpathresulttype/). |
| result | Object | ال`نتيجة` يحدد كائن نتيجة محدد يمكن إعادة استخدامه وإعادته بهذه الطريقة. إذا تم تحديد هذا على أنه`باطل`أو أن التطبيق لا يعيد استخدام نتيجة المحددة ، فسيتم إنشاء كائن نتيجة جديد وإرجاعه. بالنسبة لنتائج XPath 1.0 ، سيكون هذا الكائن من النوع[`IXPathResult`](../../ixpathresult/). |

### قيمة الإرجاع

نتيجة تقييم تعبير XPath. بالنسبة لنتائج XPath 1.0 ، سيكون هذا الكائن من النوع[`IXPathResult`](../../ixpathresult/).

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: يتم رفعه إذا تعذر تحويل النتيجة لإرجاع النوع المحدد. |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: العقدة من مستند لا يدعمه [`IXPathEvaluator`](../../ixpathevaluator/) التي خلقت هذا[`IXPathExpression`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: العقدة ليست نوعًا مسموحًا به كعقدة سياق XPath أو نوع الطلب غير مسموح به بواسطة هذا[`IXPathExpression`](../). |

### أنظر أيضا

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* مساحة الاسم [Aspose.Html.Dom.XPath](../../ixpathexpression/)
* المجسم [Aspose.HTML](../../../)


