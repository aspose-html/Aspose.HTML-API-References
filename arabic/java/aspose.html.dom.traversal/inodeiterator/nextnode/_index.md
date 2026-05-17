---
title: "INodeIterator.NextNode"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة INodeIterator. تُعيد العقدة التالية في المجموعة وتُقدم موضع المتكرر داخل المجموعة. بعد إنشاء NodeIterator، تُعيد الاستدعاء الأول لـ nextNode العقدة الأولى في المجموعة."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

يعيد العقدة التالية في المجموعة ويُقدّم موضع المكرّر في المجموعة. بعد إنشاء NodeIterator، تُعيد الاستدعاءة الأولى لـ nextNode() العقدة الأولى في المجموعة.

```java
public Node NextNode()
```

### قيمة الإرجاع

العقدة التالية في المجموعة التي يتم تكرارها، أو null إذا لم يتبق أي أعضاء في تلك المجموعة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: يُرفع إذا تم استدعاء هذه الطريقة بعد استدعاء طريقة detach. |

### انظر أيضًا

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
