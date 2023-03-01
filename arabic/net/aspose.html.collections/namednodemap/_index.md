---
title: Class NamedNodeMap
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Collections.NamedNodeMap فصل. يمثل مجموعات من السمات التي يمكن الوصول إليها بالاسم.
type: docs
weight: 40
url: /ar/net/aspose.html.collections/namednodemap/
---
## NamedNodeMap class

يمثل مجموعات من السمات التي يمكن الوصول إليها بالاسم.

```csharp
public class NamedNodeMap : DOMObject, IDisposable, IEnumerable<Attr>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Item](../../aspose.html.collections/namednodemap/item/) { get; } | إرجاع عنصر الفهرس في الخريطة. إذا كان الفهرس أكبر من أو يساوي عدد العقد في هذه الخريطة ، فإن هذا يُرجع قيمة خالية. (2 indexers) |
| [Length](../../aspose.html.collections/namednodemap/length/) { get; } | عدد العقد في هذه الخريطة . |

## طُرق

| اسم | وصف |
| --- | --- |
| [GetEnumerator](../../aspose.html.collections/namednodemap/getenumerator/)() | إرجاع عداد يتكرر خلال المجموعة. |
| [GetNamedItem](../../aspose.html.collections/namednodemap/getnameditem/)(string) | استرداد العقدة المحددة بالاسم. |
| [GetNamedItemNS](../../aspose.html.collections/namednodemap/getnameditemns/)(string, string) | استرداد العقدة المحددة بواسطة الاسم المحلي ومساحة URI. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| [RemoveNamedItem](../../aspose.html.collections/namednodemap/removenameditem/)(string) | يزيل عقدة محددة بالاسم . |
| [RemoveNamedItemNS](../../aspose.html.collections/namednodemap/removenameditemns/)(string, string) | يزيل عقدة محددة بواسطة الاسم المحلي ومساحة URI. |
| [SetNamedItem](../../aspose.html.collections/namednodemap/setnameditem/)(Attr) | إضافة عقدة باستخدام السمة nodeName الخاصة بها. إذا كانت العقدة بهذا الاسم موجودة بالفعل في هذه الخريطة ، فسيتم استبدالها بالعقدة الجديدة. استبدال العقدة في حد ذاته ليس له أي تأثير. |
| [SetNamedItemNS](../../aspose.html.collections/namednodemap/setnameditemns/)(Attr) | يضيف عقدة باستخدام مساحة الاسم الخاصة بها UURI و localName. إذا كانت العقدة ذات مساحة الاسم URI وهذا الاسم المحلي موجودة بالفعل في هذه الخريطة ، فسيتم استبدالها بالاسم الجديد. استبدال العقدة في حد ذاته ليس له أي تأثير. |

### أنظر أيضا

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Attr](../../aspose.html.dom/attr/)
* مساحة الاسم [Aspose.Html.Collections](../../aspose.html.collections/)
* المجسم [Aspose.HTML](../../)


