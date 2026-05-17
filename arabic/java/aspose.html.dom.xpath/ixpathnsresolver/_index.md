---
title: "واجهة IXPathNSResolver"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "com.aspose.html.dom.xpath.IXPathNSResolver interface. تسمح واجهة XPathNSResolver بربط سلاسل البادئة في التعبير بسلاسل packageURI بشكل صحيح. يمكن لـ IXPathEvaluator إنشاء تنفيذ لـ IXPathNSResolver من عقدة أو قد تُنفذ الواجهة من قبل أي تطبيق."
type: docs

url: /ar/java/com.aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

واجهة `XPathNSResolver` تسمح بسلاسل `prefix` في التعبير بأن تُربط بشكل صحيح بسلاسل `packageURI`. يمكن لـ [`IXPathEvaluator`](../ixpathevaluator/) إنشاء تنفيذ لـ `IXPathNSResolver` من عقدة، أو قد تُنفذ الواجهة من قبل أي تطبيق.

```java
public interface IXPathNSResolver
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [lookupNamespaceURI](../../com.aspose.html.dom.xpath/ixpathnsresolver/lookuppackageuri/)(String) | ابحث عن URI الحزمة المرتبط بالبادئة المحددة. يجب ألا يستدعي مقيم XPath هذا أبداً مع قيمة `null` أو فارغة، لأن نتيجة ذلك غير معرفة. |

### انظر أيضًا

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
