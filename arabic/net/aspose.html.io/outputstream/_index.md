---
title: Class OutputStream
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.IO.OutputStream فصل. يلف تيار بديل تدفق الإخراج الحقيقي ويتحكم في الوصول إليه.OutputStream يحتوي على بيانات URI التي تصف موقع تدفق الإخراج.
type: docs
weight: 3750
url: /ar/net/aspose.html.io/outputstream/
---
## OutputStream class

يلف تيار بديل تدفق الإخراج الحقيقي ويتحكم في الوصول إليه.`OutputStream` يحتوي على بيانات URI التي تصف موقع تدفق الإخراج.

```csharp
public class OutputStream : Stream
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [OutputStream](outputstream/)(Stream, string) | يقوم بتهيئة مثيل جديد لملف`OutputStream` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [CanRead](../../aspose.html.io/outputstream/canread/) { get; } | يحصل على قيمة تشير إلى ما إذا كان تدفق الإخراج المغلف يدعم القراءة. |
| override [CanSeek](../../aspose.html.io/outputstream/canseek/) { get; } | الحصول على قيمة تشير إلى ما إذا كان تدفق الإخراج المغلف يدعم البحث. |
| override [CanWrite](../../aspose.html.io/outputstream/canwrite/) { get; } | يحصل على قيمة تشير إلى ما إذا كان تدفق الإخراج المغلف يدعم الكتابة. |
| override [Length](../../aspose.html.io/outputstream/length/) { get; } | الحصول على الطول بالبايت لتدفق الإخراج المغلف. |
| override [Position](../../aspose.html.io/outputstream/position/) { get; set; } | الحصول على أو تحديد الموضع ضمن تيار الإخراج المغلف. |
| [Uri](../../aspose.html.io/outputstream/uri/) { get; } | يحصل على URI الخاص بموقع الدفق. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Close](../../aspose.html.io/outputstream/close/)() | لإغلاق دفق الإخراج المغلف والدفق الحالي. |
| override [Flush](../../aspose.html.io/outputstream/flush/)() | يمسح كافة المخازن المؤقتة لتدفق الإخراج المغلف ويسبب كتابة أي بيانات مخزنة إلى الجهاز الأساسي. |
| override [Read](../../aspose.html.io/outputstream/read/)(byte[], int, int) | يقرأ تسلسل البايت من تيار الإخراج المغلف ويقدم الموضع داخل التدفق بعدد البايتات المقروءة. |
| override [Seek](../../aspose.html.io/outputstream/seek/)(long, SeekOrigin) | يضبط الموضع ضمن تيار الإخراج المغلف. |
| override [SetLength](../../aspose.html.io/outputstream/setlength/)(long) | يحدد طول تيار الإخراج المغلف. |
| override [Write](../../aspose.html.io/outputstream/write/)(byte[], int, int) | يكتب تسلسلًا من البايتات إلى دفق الإخراج المغلف ويقدم الموضع الحالي ضمن هذا الدفق بعدد بايت مكتوب. |

### أنظر أيضا

* مساحة الاسم [Aspose.Html.IO](../../aspose.html.io/)
* المجسم [Aspose.HTML](../../)


