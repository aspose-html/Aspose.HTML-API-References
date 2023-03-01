---
title: Class NodeFilter
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Traversal.Filters.NodeFilter فصل. الفلاتر هي كائنات تعرف كيفية تصفية العقد.
type: docs
weight: 2460
url: /ar/net/aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

الفلاتر هي كائنات تعرف كيفية "تصفية" العقد.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## طُرق

| اسم | وصف |
| --- | --- |
| abstract [AcceptNode](../../aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | اختبر ما إذا كانت العقدة المحددة مرئية في العرض المنطقي لـ a TreeWalker أو NodeIterator. سيتم استدعاء هذه function من خلال تطبيق TreeWalker and NodeIterator؛ لا يتم استدعاؤه عادةً مباشرةً من رمز المستخدم . (على الرغم من أنه يمكنك القيام بذلك إذا كنت تريد استخدام مرشح same لتوجيه منطق التطبيق الخاص بك.) |
| override [GetPlatformType](../../aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |

## مجالات

| اسم | وصف |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | اقبل العقدة. طرق التنقل المحددة لـ ستعيد NodeIterator أو TreeWalker هذه العقدة . |
| const [FILTER_REJECT](../../aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | ارفض العقدة. طرق التنقل المحددة لـ لن تقوم NodeIterator أو TreeWalker بإرجاع هذه العقدة. بالنسبة إلى TreeWalker ، سيتم أيضًا رفض أبناء هذه العقدة . تعامل NodeIterators هذا على أنه مرادف لـ FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | تخطي هذه العقدة المفردة. طرق التنقل المحددة لـ لن تقوم NodeIterator أو TreeWalker بإرجاع هذه العقدة. لكل من NodeIterator و TreeWalker ، سيظل اعتبار العناصر الفرعية لهذه العقدة . |
| const [SHOW_ALL](../../aspose.html.dom.traversal.filters/nodefilter/show_all/) | إظهار كافة العقد . |
| const [SHOW_ATTRIBUTE](../../aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | إظهار عقد Attr. هذا له معنى فقط عند إنشاء مكرر أو أداة مشي الشجرة مع عقدة سمة مثل جذرها ؛ في هذه الحالة ، فهذا يعني أن عقدة السمة ستظهر في الموضع الأول من التكرار أو الاجتياز. نظرًا لأن السمات ليست أبدًا تابعة للعقد الأخرى ، فإنها لا تظهر عند عبور شجرة المستند. |
| const [SHOW_CDATA_SECTION](../../aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | إظهار عقد قسم CDATA . |
| const [SHOW_COMMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_comment/) | إظهار عقد التعليق . |
| const [SHOW_DOCUMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document/) | إظهار عقد المستند . |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | إظهار عقد DocumentFragment . |
| const [SHOW_DOCUMENT_TYPE](../../aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | إظهار عقد DocumentType . |
| const [SHOW_ELEMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_element/) | إظهار عقد العنصر . |
| const [SHOW_ENTITY](../../aspose.html.dom.traversal.filters/nodefilter/show_entity/) | إظهار عقد الكيان. هذا مفيد فقط عند إنشاء مكرر أو مشي شجرة مع عقدة كيان كجذر ؛ في هذه الحالة ، فهذا يعني أن العقدة Entity ستظهر في الموضع الأول من الاجتياز. نظرًا لأن كيانات ليست جزءًا من شجرة المستند ، فإنها لا تظهر عند عبور فوق شجرة المستند. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | إظهار عقد مرجع الكيان. |
| const [SHOW_NOTATION](../../aspose.html.dom.traversal.filters/nodefilter/show_notation/) | إظهار عقد التدوين. هذا مفيد فقط عند إنشاء مكرر أو مشي شجرة مع عقدة تدوين كجذر ؛ في هذه الحالة ، فهذا يعني أن عقدة التدوين ستظهر في الموضع الأول من اجتياز . نظرًا لأن الملاحظات ليست جزءًا من شجرة المستند ، فإنها لا تظهر عند عبور شجرة المستند. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | عرض المعالجةالتعليمات العقد . |
| const [SHOW_TEXT](../../aspose.html.dom.traversal.filters/nodefilter/show_text/) | إظهار العقد النصية . |

### أنظر أيضا

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [INodeFilter](../../aspose.html.dom.traversal/inodefilter/)
* مساحة الاسم [Aspose.Html.Dom.Traversal.Filters](../../aspose.html.dom.traversal.filters/)
* المجسم [Aspose.HTML](../../)


