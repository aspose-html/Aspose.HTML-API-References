---
title: "واجهة INodeIterator"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.traversal.INodeIterator. تُستخدم المتكررات (Iterators) للتنقل عبر مجموعة من العقد مثل مجموعة العقد في NodeList، أو شجرة المستند الفرعية التي تحكمها عقدة معينة، أو نتائج استعلام أو أي مجموعة أخرى من العقد. تُحدّد مجموعة العقد التي سيتم تكرارها من قبل تنفيذ NodeIterator. يحدد DOM Level 2 تنفيذًا واحدًا لـ NodeIterator لتجوال شجرة المستند بترتيب المستند. تُنشأ مثيلات هذه المتكررات عن طريق استدعاء DocumentTraversal .createNodeIterator."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

تُستخدم المتكررات للانتقال عبر مجموعة من العقد، مثل مجموعة العقد في NodeList، أو شجرة المستند الفرعية التي يتحكم فيها عقدة معينة، أو نتائج استعلام، أو أي مجموعة أخرى من العقد. تُحدد مجموعة العقد التي سيتم تكرارها بواسطة تنفيذ NodeIterator. يحدد DOM Level 2 تنفيذًا واحدًا لـ NodeIterator لتصفح شجرة المستند الفرعية بترتيب المستند. تُنشأ مثيلات هذه المتكررات باستدعاء DocumentTraversal .createNodeIterator().

انظر أيضًا إلى [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) قيمة هذه العلامة تحدد ما إذا كانت أبناء عقد مراجع الكيانات مرئية للمكرّر. إذا كانت false، فسيتم رفضها وتوابعها. لاحظ أن هذا الرفض له أولوية على whatToShow والمرشح. كما لاحظ أن هذه هي الحالة الوحيدة حاليًا التي قد يرفض فيها NodeIterators شجرة فرعية كاملة بدلاً من تخطي العقد الفردية. لإنشاء عرض للمستند يحتوي على مراجع الكيانات موسعة ولا يكشف عن عقدة مرجع الكيان نفسها، استخدم علامات whatToShow لإخفاء عقدة مرجع الكيان واضبط expandEntityReferences إلى true عند إنشاء المكرّر. لإنشاء عرض للمستند يحتوي على عقد مراجع الكيانات دون توسيع الكيان، استخدم علامات whatToShow لإظهار عقدة مرجع الكيان واضبط expandEntityReferences إلى false. |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) عقدة المرجع الحالية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | يفصل NodeIterator عن المجموعة التي كان يتجول فيها، محررًا أي موارد حسابية ومُضعًا المكرّر في الحالة INVALID. بعد استدعاء detach، ستؤدي الاستدعاءات إلى nextNode أو previousNode إلى رفع الاستثناء INVALID_STATE_ERR. |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | يعيد العقدة التالية في المجموعة ويُقدّم موضع المكرّر في المجموعة. بعد إنشاء NodeIterator، تُعيد الاستدعاءة الأولى لـ nextNode() العقدة الأولى في المجموعة. |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | يعيد العقدة السابقة في المجموعة وينقل موضع NodeIterator إلى الخلف في المجموعة. |

### انظر أيضًا

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
