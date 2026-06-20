---
title: "IXPathResult.SnapshotItem"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "IXPathResult الطريقة. تُرجع العنصر رقم index في مجموعة اللقطات. إذا كان index أكبر من أو يساوي عدد العقد في القائمة فإن هذه الطريقة تُرجع null. على عكس نتيجة المُكرِّر، لا تصبح اللقطة غير صالحة ولكن قد لا تتطابق مع المستند الحالي إذا تم تعديلّه."
type: docs

url: /ar/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

يعيد العنصر رقم `index` في مجموعة اللقطة. إذا كان `index` أكبر من أو يساوي عدد العقد في القائمة، فإن هذه الطريقة تُعيد `null`. على عكس نتيجة المتكرر، لا تصبح اللقطة غير صالحة، لكن قد لا تتطابق مع المستند الحالي إذا تم تغييره.

```java
public Node SnapshotItem(int index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| index | Int32 | فهرس في مجموعة اللقطات. |

### قيمة الإرجاع

العقدة في الموضع `index` في `NodeList`، أو `null` إذا لم يكن ذلك فهرسًا صالحًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: يُرفع إذا كان `resultType` ليس من نوع `UnorderedNodeSnapshot` أو `OrderedNodeSnapshot`. |

### انظر أيضًا

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
