---
title: "فئة NodeFilter"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.dom.traversal.filters.NodeFilter. الفلاتر هي كائنات تعرف كيفية تصفية العقد"
type: docs

url: /ar/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

الفلاتر هي كائنات تعرف كيفية "تصفية" العقد.

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | اختبر ما إذا كانت عقدة محددة مرئية في العرض المنطقي لـ TreeWalker أو NodeIterator. سيتم استدعاء هذه الدالة من قبل تنفيذ TreeWalker و NodeIterator؛ عادةً لا يتم استدعاؤها مباشرةً من كود المستخدم. (مع ذلك يمكنك فعل ذلك إذا أردت استخدام نفس الفلتر لتوجيه منطق تطبيقك.) |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | تُستخدم هذه الطريقة لاسترجاع نوع كائن ECMAScript. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | قبول العقدة. طرق التنقل المعرفة لـ NodeIterator أو TreeWalker ستعيد هذه العقدة. |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | رفض العقدة. طرق التنقل المعرفة لـ NodeIterator أو TreeWalker لن تُعيد هذه العقدة. بالنسبة لـ TreeWalker، سيتم رفض أبناء هذه العقدة أيضًا. يعتبر NodeIterators هذا مرادفًا لـ FILTER_SKIP. |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | تخطي هذه العقدة الوحيدة. طرق التنقل المعرفة لـ NodeIterator أو TreeWalker لن تُعيد هذه العقدة. بالنسبة لكل من NodeIterator و TreeWalker، سيُنظر إلى أبناء هذه العقدة. |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | إظهار جميع العقد. |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | إظهار عقد Attr. هذا ذو معنى فقط عند إنشاء مُكرِّر أو متجول شجري بجذر عقدة صفة؛ في هذه الحالة، يعني أن عقدة الصفة ستظهر في الموضع الأول من التكرار أو التجوال. نظرًا لأن الصفات لا تكون أبدًا أبناء لعقد أخرى، فهي لا تظهر عند التجول في شجرة المستند. |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | إظهار عقد CDATASection. |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | إظهار عقد التعليق. |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | إظهار عقد المستند. |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | إظهار عقد DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | إظهار عقد DocumentType. |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | إظهار عقد العنصر. |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | إظهار عقد Entity. هذا ذو معنى فقط عند إنشاء مُكرِّر أو متجول شجري بجذر عقدة Entity؛ في هذه الحالة، يعني أن عقدة Entity ستظهر في الموضع الأول من التجوال. نظرًا لأن الكيانات ليست جزءًا من شجرة المستند، فهي لا تظهر عند التجول في شجرة المستند. |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | إظهار عقد EntityReference. |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | إظهار عقد Notation. هذا ذو معنى فقط عند إنشاء iterator أو tree-walker مع عقدة Notation كجذر لها؛ في هذه الحالة، يعني أن عقدة Notation ستظهر في الموضع الأول من التجوال. بما أن Notation ليست جزءًا من شجرة المستند، فهي لا تظهر عند التجول عبر شجرة المستند. |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | إظهار عقد ProcessingInstruction. |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | إظهار عقد Text. |

### انظر أيضًا

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
