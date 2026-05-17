---
title: "IXPathResult.IterateNext"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة IXPathResult. تتنقل وتعيد العقدة التالية من مجموعة العقد أو `null` إذا لم يتبقَ أي عقد."
type: docs

url: /ar/java/com.aspose.html.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

يتكرر ويعيد العقدة التالية من مجموعة العقد أو `null` إذا لم يتبق أي عقد.

```java
public Node IterateNext()
```

### قيمة الإرجاع

تُعيد العقدة التالية.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: يُرفع إذا لم يكن `resultType` من نوع `UnorderedNodeIterator` أو `OrderedNodeIterator`. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: تم تعديل المستند منذ إرجاع النتيجة. |

### انظر أيضًا

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
