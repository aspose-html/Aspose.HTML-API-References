---
title: IBlob
second_title: Aspose.HTML لمرجع .NET API
description: يشير كائن Blob إلى تسلسل البايت  وله سمة الحجم وهي العدد الإجمالي للبايت في تسلسل البايت  وسمة النوع  وهي سلسلة مشفرة بواسطة ASCII بأحرف صغيرة تمثل نوع الوسائط لتسلسل البايت .
type: docs
weight: 3690
url: /ar/net/aspose.html.io/iblob/
---
## IBlob interface

يشير كائن Blob إلى تسلسل البايت ، وله سمة الحجم وهي العدد الإجمالي للبايت في تسلسل البايت ، وسمة النوع ، وهي سلسلة مشفرة بواسطة ASCII بأحرف صغيرة تمثل نوع الوسائط لتسلسل البايت .

```csharp
public interface IBlob
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Size](../../aspose.html.io/iblob/size) { get; } | إرجاع حجم تسلسل البايت بعدد البايت . عند الحصول ، يجب أن يُرجع وكلاء المستخدم المطابق العدد الإجمالي للبايتات التي يمكن قراءتها بواسطة كائن FileReader أو FileReaderSync ، أو 0 إذا كان Blob لا يحتوي على وحدات بايت ليتم قراءتها . |
| [Type](../../aspose.html.io/iblob/type) { get; } | السلسلة المشفرة ASCII بأحرف صغيرة تمثل نوع وسائط Blob. عند الحصول عليها ، يجب على وكلاء المستخدم إرجاع نوع Blob كسلسلة بتشفير ASCII بأحرف صغيرة ، بحيث يتم تحويلها إلى بايت التسلسل ، هو نوع MIME قابل للتحليل ، أو السلسلة الفارغة - 0 بايت - إذا تعذر تحديد النوع. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Slice](../../aspose.html.io/iblob/slice)(ulong, ulong, string) | يُرجع كائن Blob جديدًا ببايتات تتراوح من معلمة البدء الاختيارية حتى ولكن لا تتضمن معلمة النهاية الاختيارية ، وبسمة النوع التي تمثل قيمة المعلمة contentType الاختيارية. |

### أنظر أيضا

* مساحة الاسم [Aspose.Html.IO](../../aspose.html.io)
* المجسم [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->