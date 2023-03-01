---
title: Interface IMediaList
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Css.IMediaList واجهه المستخدم. توفر واجهة MediaList تجريدًا لمجموعة مرتبة من الوسائط  بدون تعريف أو تقييد كيفية تنفيذ هذه المجموعة. القائمة الفارغة هي نفس القائمة التي تحتوي على الوسيط الكل.
type: docs
weight: 580
url: /ar/net/aspose.html.dom.css/imedialist/
---
## IMediaList interface

توفر واجهة MediaList تجريدًا لمجموعة مرتبة من الوسائط ، بدون تعريف أو تقييد كيفية تنفيذ هذه المجموعة. القائمة الفارغة هي نفس القائمة التي تحتوي على الوسيط "الكل".

```csharp
public interface IMediaList : IEnumerable<string>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Item](../../aspose.html.dom.css/imedialist/item/) { get; } | إرجاع الفهرس في القائمة. إذا كان الفهرس أكبر من أو يساوي عدد الوسائط في القائمة ، فإن هذا يُرجع قيمة خالية.فهرس الوسائط. |
| [Length](../../aspose.html.dom.css/imedialist/length/) { get; } | عدد الوسائط في القائمة. نطاق الوسائط الصالحة هو من 0 إلى الطول -1 ضمناً . |
| [MediaText](../../aspose.html.dom.css/imedialist/mediatext/) { get; } | التمثيل النصي القابل للتحليل لقائمة الوسائط. هذه قائمة وسائط مفصولة بفواصل. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AppendMedium](../../aspose.html.dom.css/imedialist/appendmedium/)(string) | يضيف الوسيط newMedium إلى نهاية القائمة. إذا تم استخدام الوسيط الجديد بالفعل ، فسيتم إزالته أولاً. |
| [DeleteMedium](../../aspose.html.dom.css/imedialist/deletemedium/)(string) | حذف الوسيط المشار إليه بواسطة oldMedium من القائمة. |

### أنظر أيضا

* مساحة الاسم [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* المجسم [Aspose.HTML](../../)


