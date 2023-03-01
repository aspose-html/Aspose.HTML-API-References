---
title: INodeIterator.PointerBeforeReferenceNode
second_title: Aspose.HTML لمرجع .NET API
description: INodeIterator ملكية. تحدد قيمة هذه العلامة ما إذا كانت العناصر الفرعية للعقد المرجعية للكيان مرئية للمكرر. إذا كانت خاطئة  فسيتم رفضهم and أحفادهم. لاحظ أن هذا الرفض يأخذ الأسبقية على whatToShow والمرشح. لاحظ أيضًا أن هذا هو الموقف الوحيد حاليًا حيث قد ترفض NodeIterators شجرة فرعية كاملة بدلاً من تخطي العقد الفردية. قم بإخفاء مرجع الكيان node وقم بتعيين expandEntityReferences إلى true عند إنشاء the iterator. لإنتاج طريقة عرض للمستند تحتوي على عقد كيان ولكن بدون توسيع كيان  استخدم whatToShow flags لإظهار عقدة مرجع الكيان و set expandEntityReferences to false .
type: docs
weight: 10
url: /ar/net/aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

تحدد قيمة هذه العلامة ما إذا كانت العناصر الفرعية للعقد المرجعية للكيان مرئية للمكرر. إذا كانت خاطئة ، فسيتم رفضهم and أحفادهم. لاحظ أن هذا الرفض يأخذ الأسبقية على whatToShow والمرشح. لاحظ أيضًا أن هذا هو الموقف الوحيد حاليًا حيث قد ترفض NodeIterators شجرة فرعية كاملة بدلاً من تخطي العقد الفردية. قم بإخفاء مرجع الكيان node وقم بتعيين expandEntityReferences إلى true عند إنشاء the iterator. لإنتاج طريقة عرض للمستند تحتوي على عقد كيان ولكن بدون توسيع كيان ، استخدم whatToShow flags لإظهار عقدة مرجع الكيان و set expandEntityReferences to false .

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Property_Value

`حقيقي`إذا [توسيع مراجع الكيان] ؛ خلاف ذلك،`خطأ شنيع` .

### أنظر أيضا

* interface [INodeIterator](../)
* مساحة الاسم [Aspose.Html.Dom.Traversal](../../inodeiterator/)
* المجسم [Aspose.HTML](../../../)


