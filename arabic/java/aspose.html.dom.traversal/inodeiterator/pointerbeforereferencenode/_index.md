---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "خاصية INodeIterator. تحدد قيمة هذه العلامة ما إذا كانت أبناء عقد مراجع الكيان مرئية للمتكرر. إذا كانت false فإنهم وأحفادهم سيُرفضون. لاحظ أن هذا الرفض له أولوية على whatToShow والفلاتر. كما لاحظ أن هذه هي الحالة الوحيدة حاليًا التي قد يرفض فيها NodeIterators شجرة فرعية كاملة بدلاً من تخطي العقد الفردية. لإنشاء عرض للوثيقة يحتوي على مراجع الكيان موسعة ولا يكشف عن عقدة مرجع الكيان نفسها، استخدم علامات whatToShow لإخفاء عقدة مرجع الكيان واضبط expandEntityReferences إلى true عند إنشاء المتكرر. لإنشاء عرض للوثيقة يحتوي على عقد مراجع الكيان دون توسيع الكيان، استخدم علامات whatToShow لإظهار عقدة مرجع الكيان واضبط expandEntityReferences إلى false."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

قيمة هذه العلامة تحدد ما إذا كانت أبناء عقد مراجع الكيان مرئية للمتكرر. إذا كانت false، فإنهم وأحفادهم سيُرفضون. لاحظ أن هذا الرفض له أولوية على whatToShow والفلاتر. كما لاحظ أن هذه هي الحالة الوحيدة حاليًا التي قد يرفض فيها NodeIterators شجرة فرعية كاملة بدلاً من تخطي العقد الفردية. لإنشاء عرض للوثيقة يحتوي على مراجع الكيان موسعة ولا يكشف عن عقدة مرجع الكيان نفسها، استخدم علامات whatToShow لإخفاء عقدة مرجع الكيان واضبط expandEntityReferences إلى true عند إنشاء المتكرر. لإنشاء عرض للوثيقة يحتوي على عقد مراجع الكيان دون توسيع الكيان، استخدم علامات whatToShow لإظهار عقدة مرجع الكيان واضبط expandEntityReferences إلى false.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` إذا [expand entity references]؛ وإلا `false`.

### انظر أيضًا

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
