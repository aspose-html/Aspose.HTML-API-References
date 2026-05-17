---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة IXPathEvaluator. تُكيّف أي عقدة DOM لحل الحزم بحيث يمكن تقييم تعبير XPath بسهولة بالنسبة لسياق العقدة التي ظهرت فيها داخل المستند. يعمل هذا المُكيّف مثل طريقة DOM Level 3 lookupNamespaceURI على العقد في حل packageURI من بادئة معينة باستخدام المعلومات الحالية المتوفرة في هيكلية العقد في وقت استدعاء lookupNamespaceURI، كما يحل البادئة الضمنية xml بشكل صحيح."
type: docs

url: /ar/java/com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

يقوم بتكييف أي عقدة DOM لحل الحزم بحيث يمكن تقييم تعبير XPath بسهولة بالنسبة لسياق العقدة التي ظهر فيها داخل المستند. يعمل هذا المكيّف مثل طريقة DOM Level 3 `lookupNamespaceURI` على العقد في حل packageURI من بادئة معينة باستخدام المعلومات الحالية المتوفرة في تسلسل العقدة الهرمي عند استدعاء lookupNamespaceURI، كما يحل البادئة الضمنية xml بشكل صحيح.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| nodeResolver | Node | The العقدة التي ستُستخدم كسياق لحل الحزم. |

### قيمة الإرجاع

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### انظر أيضًا

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
