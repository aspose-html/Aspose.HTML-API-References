---
title: "واجهة IXPathEvaluator"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "com.aspose.html.dom.xpath.IXPathEvaluator interface. يتم توفير تقييم تعبيرات XPath عبر IXPathEvaluator"
type: docs

url: /ar/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

يتم توفير تقييم تعبيرات XPath بواسطة `IXPathEvaluator`.

```java
public interface IXPathEvaluator
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | ينشئ تعبير XPath محلل مع حزم محلولة. هذا مفيد عندما يُعاد استخدام التعبير في تطبيق لأنه يتيح تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وحل جميع بادئات الحزم مسبقًا داخل التعبير. |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | يقوم بتكييف أي عقدة DOM لحل الحزم بحيث يمكن تقييم تعبير XPath بسهولة بالنسبة لسياق العقدة التي ظهر فيها داخل المستند. يعمل هذا المكيّف مثل طريقة DOM Level 3 `lookupNamespaceURI` على العقد في حل packageURI من بادئة معينة باستخدام المعلومات الحالية المتوفرة في تسلسل العقدة الهرمي عند استدعاء lookupNamespaceURI، كما يحل البادئة الضمنية xml بشكل صحيح. |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | يقيم سلسلة تعبير XPath ويعيد نتيجة من النوع المحدد إذا كان ذلك ممكنًا. |

### انظر أيضًا

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
