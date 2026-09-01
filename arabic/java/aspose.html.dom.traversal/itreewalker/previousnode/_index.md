---
title: "ITreeWalker.PreviousNode"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة ITreeWalker. تنقل الـ TreeWalker إلى العقدة المرئية السابقة في ترتيب المستند بالنسبة للعقدة الحالية وتعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية عقدة سابقة أو إذا حاول البحث عن previousNode الصعود من عقدة الجذر للـ TreeWalker فإنها تُعيد null وتحتفظ بالعقدة الحالية."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/itreewalker/previousnode/
---
## ITreeWalker.PreviousNode method

ينقل الـ TreeWalker إلى العقدة المرئية السابقة في ترتيب المستند بالنسبة للعقدة الحالية، ويعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية عقدة سابقة، أو إذا حاول البحث عن previousNode الصعود من عقدة الجذر الخاصة بالـ TreeWalker، يُرجع null، ويحتفظ بالعقدة الحالية.

```java
public Node PreviousNode()
```

### قيمة الإرجاع

العقدة الجديدة، أو null إذا لم تكن للعقدة الحالية عقدة سابقة في العرض المنطقي للـ TreeWalker.

### انظر أيضًا

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
