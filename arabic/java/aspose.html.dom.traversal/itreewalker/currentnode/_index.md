---
title: "ITreeWalker.CurrentNode"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "خاصية ITreeWalker. العقدة التي يقع فيها TreeWalker حاليًا. قد تؤدي التعديلات على شجرة DOM إلى عدم قبول العقدة الحالية من قبل الفلتر المرتبط بـ TreeWalker. يمكن أيضًا تعيين currentNode صراحةً إلى أي عقدة سواء كانت ضمن الشجرة الفرعية المحددة بواسطة العقدة الجذرية أو لا، أو ما إذا كانت ستُقبل بواسطة الفلتر وعلامات whatToShow. تستمر عملية التجوال الإضافية بالنسبة إلى currentNode حتى وإن لم تكن جزءًا من العرض الحالي عن طريق تطبيق الفلاتر في الاتجاه المطلوب؛ إذا لم يكن أي تجوال ممكنًا لا يتم تغيير currentNode."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

العقدة التي يقع فيها TreeWalker حاليًا. قد تؤدي التعديلات على شجرة DOM إلى عدم قبول العقدة الحالية من قبل الفلتر المرتبط بـ TreeWalker. يمكن أيضًا تعيين currentNode صراحةً إلى أي عقدة، سواء كانت ضمن الشجرة الفرعية المحددة بواسطة العقدة الجذرية أو لا، أو ما إذا كانت ستُقبل بواسطة الفلتر وعلامات whatToShow. تستمر عملية التجوال الإضافية بالنسبة إلى currentNode حتى وإن لم تكن جزءًا من العرض الحالي، عن طريق تطبيق الفلاتر في الاتجاه المطلوب؛ إذا لم يكن أي تجوال ممكنًا، لا يتم تغيير currentNode.

```java
public Node CurrentNode { get; set; }
```

### Property Value

العقدة الحالية.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: يُثار إذا تم محاولة تعيين currentNode إلى null. |

### انظر أيضًا

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
