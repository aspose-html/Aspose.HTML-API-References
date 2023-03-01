---
title: Class MutationRecord
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Mutations.MutationRecord فصل. يمثل سجل الطفرة طفرة DOM فردية. إنه الكائن الذي يتم تمريره إليهMutationObserver سMutationCallback .
type: docs
weight: 990
url: /ar/net/aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

يمثل سجل الطفرة طفرة DOM فردية. إنه الكائن الذي يتم تمريره إليه[`MutationObserver`](../mutationobserver/) س[`MutationCallback`](../mutationcallback/) .

```csharp
public class MutationRecord : DOMObject
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AddedNodes](../../aspose.html.dom.mutations/mutationrecord/addednodes/) { get; } | إرجاع العقد المضافة . |
| [AttributeName](../../aspose.html.dom.mutations/mutationrecord/attributename/) { get; } | تُرجع الاسم المحلي للسمة التي تم تغييرها ، وتكون خالية بخلاف ذلك. |
| [AttributeNamespace](../../aspose.html.dom.mutations/mutationrecord/attributenamespace/) { get; } | إرجاع مساحة الاسم للسمة التي تم تغييرها ، وبخلاف ذلك خالية. |
| [NextSibling](../../aspose.html.dom.mutations/mutationrecord/nextsibling/) { get; } | إرجاع الشقيق التالي للعقد المضافة أو التي تمت إزالتها ، أو فارغة. |
| [OldValue](../../aspose.html.dom.mutations/mutationrecord/oldvalue/) { get; } | تعتمد القيمة المعادة على النوع. بالنسبة إلى "السمات" ، فهي قيمة السمة التي تم تغييرها قبل التغيير. |
| [PreviousSibling](../../aspose.html.dom.mutations/mutationrecord/previoussibling/) { get; } | إرجاع الشقيق السابق للعقد المضافة أو التي تمت إزالتها ، أو فارغة. |
| [RemovedNodes](../../aspose.html.dom.mutations/mutationrecord/removednodes/) { get; } | قم بإرجاع العقد التي تمت إزالتها. |
| [Target](../../aspose.html.dom.mutations/mutationrecord/target/) { get; } | تُرجع العقدة التي تأثرت بها الطفرة ، اعتمادًا على النوع. بالنسبة إلى "السمات" ، هو العنصر الذي تغيرت صفته. بالنسبة لـ "CharacterData" ، فهي عقدة CharacterData. بالنسبة إلى "قائمة الأطفال" ، فإن العقدة هي التي تغيرت عناصرها الفرعية. |
| [Type](../../aspose.html.dom.mutations/mutationrecord/type/) { get; } | تُرجع "السمات" إذا كانت طفرة في السمة ، و "characterData" إذا كانت طفرة في عقدة CharacterData و "قائمة الأطفال" إذا كانت طفرة في شجرة العقد. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |

### أنظر أيضا

* class [DOMObject](../../aspose.html.dom/domobject/)
* مساحة الاسم [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* المجسم [Aspose.HTML](../../)


