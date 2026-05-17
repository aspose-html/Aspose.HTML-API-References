---
title: "INodeIterator.PreviousNode"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة INodeIterator. تُعيد العقدة السابقة في المجموعة وتُحرك موضع NodeIterator إلى الخلف داخل المجموعة."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/inodeiterator/previousnode/
---
## INodeIterator.PreviousNode method

يعيد العقدة السابقة في المجموعة وينقل موضع NodeIterator إلى الخلف في المجموعة.

```java
public Node PreviousNode()
```

### قيمة الإرجاع

العقدة السابقة في المجموعة التي يتم تكرارها، أو null إذا لم يتبق أي أعضاء في تلك المجموعة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: يُرفع إذا تم استدعاء هذه الطريقة بعد استدعاء طريقة detach. |

### انظر أيضًا

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
