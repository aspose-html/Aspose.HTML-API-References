---
title: "ITreeWalker Interface"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.traversal.ITreeWalker. تُستخدم كائنات TreeWalker للتنقل في شجرة المستند أو شجرتها الفرعية باستخدام عرض المستند المحدد بواسطة أعلام whatToShow والفلتر إن وجد. أي دالة تقوم بالتنقل باستخدام TreeWalker ستدعم تلقائيًا أي عرض يُحدده TreeWalker."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

تُستخدم كائنات TreeWalker للتنقل في شجرة المستند أو شجرتها الفرعية باستخدام عرض المستند المحدد بأعلام whatToShow والفلتر (إن وجد). أي دالة تقوم بالتنقل باستخدام TreeWalker ستدعم تلقائيًا أي عرض يُعرفه TreeWalker.

إهمال العقد من العرض المنطقي لشجرة فرعية يمكن أن ينتج بنية تختلف اختلافًا كبيرًا عن نفس الشجرة الفرعية في المستند الكامل غير المفلتر. العقد التي تكون أخوة في عرض TreeWalker قد تكون أبناء لعقد مختلفة، متباعدة على نطاق واسع، في العرض الأصلي. على سبيل المثال، اعتبر NodeFilter يتخطى جميع العقد باستثناء عقد النص والعقدة الجذرية للمستند. في العرض المنطقي الناتج، جميع عقد النص ستكون أخوة وتظهر كأبناء مباشرة للعقدة الجذرية، بغض النظر عن عمق بنية المستند الأصلي.

انظر أيضًا إلى [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | ينقل TreeWalker إلى أول طفل مرئي للعقدة الحالية، ويعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية أطفال مرئيون، يُعيد null، ويحتفظ بالعقدة الحالية. |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | ينقل TreeWalker إلى آخر طفل مرئي للعقدة الحالية، ويعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية أطفال مرئيون، يُعيد null، ويحتفظ بالعقدة الحالية. |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | ينقل TreeWalker إلى العقدة المرئية التالية بترتيب المستند بالنسبة للعقدة الحالية، ويعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية عقدة تالية، أو إذا حاول البحث عن nextNode الصعود من عقدة الجذر الخاصة بـ TreeWalker، يُعيد null، ويحتفظ بالعقدة الحالية. |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | ينقل TreeWalker إلى الأخ التالي للعقدة الحالية، ويعيد العقدة الجديدة. إذا لم يكن للعقدة الحالية أخ مرئي التالي، يُعيد null، ويحتفظ بالعقدة الحالية. |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | ينقل ويعيد أقرب عقدة سلفية مرئية للعقدة الحالية. إذا حاول البحث عن parentNode الصعود من عقدة جذر TreeWalker، أو إذا فشل في العثور على عقدة سلفية مرئية، تحتفظ هذه الطريقة بالموقع الحالي وتعيد null. |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | ينقل الـ TreeWalker إلى العقدة المرئية السابقة بترتيب المستند بالنسبة للعقدة الحالية، ويعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية عقدة سابقة، أو إذا حاول البحث عن previousNode الصعود من عقدة الجذر الخاصة بالـ TreeWalker، يُعيد null، ويحتفظ بالعقدة الحالية. |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | ينقل الـ TreeWalker إلى الأخ السابق للعقدة الحالية، ويعيد العقدة الجديدة. إذا لم تكن للعقدة الحالية أخ مرئي سابق، يُعيد null، ويحتفظ بالعقدة الحالية. |

### انظر أيضًا

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
