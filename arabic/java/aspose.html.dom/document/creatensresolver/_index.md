---
title: "Document.CreateNSResolver"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Document. يكيّف أي عقدة DOM لحل الحزم بحيث يمكن تقييم تعبير XPath بسهولة بالنسبة لسياق العقدة التي ظهرت فيها داخل المستند. يعمل هذا المكيّف مثل طريقة DOM Level 3 lookupNamespaceURI على العقد في حل packageURI من بادئة معينة باستخدام المعلومات الحالية المتاحة في هيكلية العقد في الوقت الذي يتم فيه استدعاء lookupNamespaceURI، كما يحل بشكل صحيح البادئة الضمنية xml."
type: docs

url: /ar/java/com.aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

يقوم بتكييف أي عقدة DOM لحل الحزم بحيث يمكن تقييم تعبير XPath بسهولة بالنسبة لسياق العقدة التي ظهر فيها داخل المستند. يعمل هذا المكيّف مثل طريقة DOM Level 3 `lookupNamespaceURI` على العقد في حل packageURI من بادئة معينة باستخدام المعلومات الحالية المتوفرة في تسلسل العقدة الهرمي عند استدعاء lookupNamespaceURI، كما يحل البادئة الضمنية xml بشكل صحيح.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| nodeResolver | Node | The العقدة التي ستُستخدم كسياق لحل الحزم. |

### قيمة الإرجاع

[`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### انظر أيضًا

* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
