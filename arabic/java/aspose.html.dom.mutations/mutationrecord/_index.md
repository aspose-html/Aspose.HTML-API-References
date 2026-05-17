---
title: "فئة MutationRecord"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.dom.mutations.MutationRecord. تمثل MutationRecord تعديلًا فرديًا في DOM. إنه الكائن الذي يُمرَّر إلى MutationCallback الخاص بـ MutationObservers."
type: docs

url: /ar/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

تمثل MutationRecord تعديلًا فرديًا في DOM. إنه الكائن الذي يُمرَّر إلى [`MutationObserver`](../mutationobserver/) الخاص بـ [`MutationCallback`](../mutationcallback/).

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
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) إرجاع العقدة التي تأثرت بالتعديل، حسب النوع. بالنسبة لـ "attributes"، تكون العنصر الذي تغيرت خاصيته. بالنسبة لـ "characterData"، تكون عقدة CharacterData. بالنسبة لـ "childList"، تكون العقدة التي تغير أطفالها. |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) إرجاع "attributes" إذا كان تعديلًا على خاصية، "characterData" إذا كان تعديلًا على عقدة CharacterData و "childList" إذا كان تعديلًا على شجرة العقد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |

### انظر أيضًا

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
