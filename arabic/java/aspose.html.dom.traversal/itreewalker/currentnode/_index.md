---
title: "ITreeWalker.CurrentNode"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "خاصية ITreeWalker. العقدة التي يقع فيها الـ TreeWalker حاليًا. قد تتسبب التغييرات في شجرة DOM في عدم قبول العقدة الحالية بواسطة الفلتر المرتبط بالـ TreeWalker. يمكن أيضًا تعيين currentNode صراحةً إلى أي عقدة سواء كانت ضمن الشجرة الفرعية المحددة بالعقدة الجذرية أو لا، أو ما إذا كانت ستُقبل بواسطة الفلتر وعلامات whatToShow. يستمر التجوال بالنسبة إلى currentNode حتى وإن لم تكن جزءًا من العرض الحالي عبر تطبيق الفلاتر في الاتجاه المطلوب؛ إذا لم يكن أي تجوال ممكنًا لا يتم تغيير currentNode"
type: docs

url: /ar/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

العقدة التي يقع فيها الـ TreeWalker حاليًا. قد تتسبب التغييرات في شجرة DOM في عدم قبول العقدة الحالية بواسطة الفلتر المرتبط بالـ TreeWalker. يمكن أيضًا تعيين currentNode صراحةً إلى أي عقدة، سواء كانت ضمن الشجرة الفرعية المحددة بالعقدة الجذرية أو لا، أو ما إذا كانت ستُقبل بواسطة الفلتر وعلامات whatToShow. يستمر التجوال بالنسبة إلى currentNode حتى وإن لم تكن جزءًا من العرض الحالي، عبر تطبيق الفلاتر في الاتجاه المطلوب؛ إذا لم يكن أي تجوال ممكنًا، لا يتم تغيير currentNode.

```java
public Node CurrentNode { get; set; }
```

### Property Value

العقدة الحالية.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: يُرفع إذا تم محاولة تعيين currentNode إلى null. |

### انظر أيضًا

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
