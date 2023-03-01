---
title: Interface INodeIterator
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Traversal.INodeIterator واجهه المستخدم. يتم استخدام التكرارات للدخول إلى مجموعة من العقد  على سبيل المثال مجموعة العقد في NodeList  أو الشجرة الفرعية للمستند التي تحكمها عقدة معينة  أو نتائج استعلام  أو أي مجموعة أخرى من العقد. يتم تحديد مجموعة العقد المراد تكرارها من خلال تنفيذ لـ NodeIterator. يحدد DOM المستوى 2 تنفيذ NodeIterator الفردي لأمر المستندات اجتياز الشجرة الفرعية للمستند. يتم إنشاء مثيلات هذه التكرارات عن طريق استدعاء DocumentTraversal .createNodeIterator  .
type: docs
weight: 2500
url: /ar/net/aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

يتم استخدام التكرارات للدخول إلى مجموعة من العقد ، على سبيل المثال مجموعة العقد في NodeList ، أو الشجرة الفرعية للمستند التي تحكمها عقدة معينة ، أو نتائج استعلام ، أو أي مجموعة أخرى من العقد. يتم تحديد مجموعة العقد المراد تكرارها من خلال تنفيذ لـ NodeIterator. يحدد DOM المستوى 2 تنفيذ NodeIterator الفردي لأمر المستندات اجتياز الشجرة الفرعية للمستند. يتم إنشاء مثيلات هذه التكرارات عن طريق استدعاء DocumentTraversal .createNodeIterator () .

انظر أيضا[نموذج كائن المستند (DOM) المستوى 2 الاجتياز وتحديد النطاق](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @ منذ DOM المستوى 2

```csharp
public interface INodeIterator : ITraversal
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | تحدد قيمة هذه العلامة ما إذا كانت العناصر الفرعية للعقد المرجعية للكيان مرئية للمكرر. إذا كانت خاطئة ، فسيتم رفضهم and أحفادهم. لاحظ أن هذا الرفض يأخذ الأسبقية على whatToShow والمرشح. لاحظ أيضًا أن هذا هو الموقف الوحيد حاليًا حيث قد ترفض NodeIterators شجرة فرعية كاملة بدلاً من تخطي العقد الفردية. قم بإخفاء مرجع الكيان node وقم بتعيين expandEntityReferences إلى true عند إنشاء the iterator. لإنتاج طريقة عرض للمستند تحتوي على عقد كيان ولكن بدون توسيع كيان ، استخدم whatToShow flags لإظهار عقدة مرجع الكيان و set expandEntityReferences to false . |
| [ReferenceNode](../../aspose.html.dom.traversal/inodeiterator/referencenode/) { get; } | العقدة المرجعية الحالية . |

## طُرق

| اسم | وصف |
| --- | --- |
| [Detach](../../aspose.html.dom.traversal/inodeiterator/detach/)() | يفصل NodeIterator عن المجموعة التي تكررت مرة أخرى ، وإطلاق أي موارد حسابية ووضع مكرر في حالة INVALID. بعد استدعاء الفصل ، المكالمات إلى nextNode أو العقدة السابقة will سترفع الاستثناء INVALID_STATE_ERR. |
| [NextNode](../../aspose.html.dom.traversal/inodeiterator/nextnode/)() | تُرجع العقدة التالية في المجموعة وتقدم موضع مكرر في المجموعة. بعد إنشاء NodeIterator ، تُرجع المكالمة الأولى لـ nextNode () العقدة الأولى in المجموعة. |
| [PreviousNode](../../aspose.html.dom.traversal/inodeiterator/previousnode/)() | إرجاع العقدة السابقة في المجموعة ونقل موضع NodeIterator للخلف في المجموعة. |

### أنظر أيضا

* interface [ITraversal](../itraversal/)
* مساحة الاسم [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* المجسم [Aspose.HTML](../../)


