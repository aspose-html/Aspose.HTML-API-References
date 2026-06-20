---
title: "MutationRecord الفئة"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "com.aspose.html.dom.mutations.MutationRecord class. يمثل MutationRecord تحوّلاً فرديًا في DOM. هو الكائن الذي يُمرّر إلى MutationObservers MutationCallback"
type: docs

url: /ar/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

يمثل MutationRecord تحوّلاً فرديًا في DOM. هو الكائن الذي يُمرّر إلى [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/).

```java
public class MutationRecord : DOMObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) إرجاع العقد المضافة. |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) إرجاع الاسم المحلي للخاصية المتغيّرة، وإلا null. |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) إرجاع الحزمة للخاصية المتغيّرة، وإلا null. |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) إرجاع الأخ التالي للعقد المضافة أو المُزالة، أو null. |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) قيمة الإرجاع تعتمد على النوع. بالنسبة لـ "attributes"، تكون قيمة الخاصية المتغيّرة قبل التغيير. بالنسبة لـ "characterData"، تكون بيانات العقدة المتغيّرة قبل التغيير. بالنسبة لـ "childList"، تكون null. |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) إرجاع الأخ السابق للعقد المضافة أو المُزالة، أو null. |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) إرجاع العقد المُزالة. |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) إرجاع العقدة التي تأثرت بالتحوّل، حسب النوع. بالنسبة لـ "attributes"، تكون العنصر الذي تغيرت خاصيته. بالنسبة لـ "characterData"، تكون عقدة CharacterData. بالنسبة لـ "childList"، تكون العقدة التي تغير أطفالها. |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) إرجاع "attributes" إذا كان تحوّلاً في خاصية، "characterData" إذا كان تحوّلاً في عقدة CharacterData و "childList" إذا كان تحوّلاً في شجرة العقد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |

### انظر أيضًا

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
