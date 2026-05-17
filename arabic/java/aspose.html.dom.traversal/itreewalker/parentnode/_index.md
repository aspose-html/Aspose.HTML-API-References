---
title: "ITreeWalker.ParentNode"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة ITreeWalker. تتحرك إلى أقرب عقدة سلف مرئية للعقدة الحالية وتعيدها. إذا حاول البحث عن parentNode الصعود من عقدة جذر الـ TreeWalker أو إذا فشل في العثور على عقدة سلف مرئية، فإن هذه الطريقة تحتفظ بالموقع الحالي وتعيد null."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/itreewalker/parentnode/
---
## ITreeWalker.ParentNode method

ينقل ويعيد أقرب عقدة سلفية مرئية للعقدة الحالية. إذا حاول البحث عن parentNode الصعود من عقدة جذر TreeWalker، أو إذا فشل في العثور على عقدة سلفية مرئية، تحتفظ هذه الطريقة بالموقع الحالي وتعيد null.

```java
public Node ParentNode()
```

### قيمة الإرجاع

العقدة الأصلية الجديدة، أو null إذا لم تكن للعقدة الحالية أصل في العرض المنطقي للـ TreeWalker.

### انظر أيضًا

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
