---
title: Class InputElement
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Forms.InputElement فصل. يمثل InputElement غلافًا مرتبطًا بـ HTMLInputElement.
type: docs
weight: 2980
url: /ar/net/aspose.html.forms/inputelement/
---
## InputElement class

يمثل InputElement غلافًا مرتبطًا بـ HTMLInputElement.

```csharp
public class InputElement : FormElement<HTMLInputElement>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype/) { get; } | يحصل على نوع العنصر. |
| [HtmlElement](../../aspose.html.forms/formelement-1/htmlelement/) { get; } |  |
| override [Id](../../aspose.html.forms/inputelement/id/) { get; set; } | يمثل سمة المعرف لعنصر الإدخال. |
| [List](../../aspose.html.forms/inputelement/list/) { get; } | يمثل قائمة من الخيارات |
| override [Name](../../aspose.html.forms/inputelement/name/) { get; set; } | يمثل سمة الاسم لعنصر الإدخال . |
| [Type](../../aspose.html.forms/inputelement/type/) { get; set; } | نوع عنصر تحكم النموذج . |
| override [Value](../../aspose.html.forms/inputelement/value/) { get; set; } | يمثل قيمة السلسلة لعنصر الإدخال الذي تم تعيينه مباشرةً لسمة "القيمة". |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddFile](../../aspose.html.forms/inputelement/addfile/)(string) | تضيف هذه الطريقة الملفات إلى ملف[`Files`](../../aspose.html/htmlinputelement/files/) المجموعة التي سيتم إرسالها أثناء طلب الويب التالي. |
| [GetCheckboxValue](../../aspose.html.forms/inputelement/getcheckboxvalue/)() | إرجاع حالة الفحص لعنصر الإدخال بنوع خانة الاختيار . |
| [GetColorValue](../../aspose.html.forms/inputelement/getcolorvalue/)() | تُستخدم هذه الطريقة للحصول على القيمة كلون. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال فقط هو "اللون" |
| [GetDateTimeLocalValue](../../aspose.html.forms/inputelement/getdatetimelocalvalue/)() | تُستخدم هذه الطريقة للحصول على القيمة كملفDateTime كائن كائن. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال فقط هو "التاريخ والوقت المحلي" |
| [GetDateValue](../../aspose.html.forms/inputelement/getdatevalue/)() | تُستخدم هذه الطريقة للحصول على القيمة كملفDateTime هدف. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال هو "التاريخ" |
| [GetEmailValue](../../aspose.html.forms/inputelement/getemailvalue/)() | تُستخدم هذه الطريقة للحصول على القيمة ككائن سلسلة بريد إلكتروني. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال فقط هو "البريد الإلكتروني" |
| [GetMonthValue](../../aspose.html.forms/inputelement/getmonthvalue/)() | تُستخدم هذه الطريقة للحصول على القيمة كملفDateTime هدف. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال فقط هو "شهر" |
| [GetNumberValue](../../aspose.html.forms/inputelement/getnumbervalue/)() | تُستخدم هذه الطريقة للحصول على القيمة كرقم. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال فقط هو "رقم" |
| [GetPasswordValue](../../aspose.html.forms/inputelement/getpasswordvalue/)() | تُستخدم هذه الطريقة للحصول على القيمة ككائن سلسلة كلمة المرور. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال هو "كلمة المرور" |
| [GetRadioValue](../../aspose.html.forms/inputelement/getradiovalue/)() | إرجاع حالة الفحص لعنصر الإدخال بنوع الراديو. |
| [GetTimeValue](../../aspose.html.forms/inputelement/gettimevalue/)() | تُستخدم هذه الطريقة للحصول على القيمة كملفTimeSpan هدف. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال فقط هو "الوقت" |
| [GetUrlValue](../../aspose.html.forms/inputelement/geturlvalue/)() | تُستخدم هذه الطريقة للحصول على القيمة كـ[`Url`](../../aspose.html/url/) هدف. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال فقط هو "url" |
| [GetWeekValue](../../aspose.html.forms/inputelement/getweekvalue/)() | تُستخدم هذه الطريقة للحصول على القيمة كسلسلة أسبوع. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال هو "الأسبوع" |
| [SetCheckboxValue](../../aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | يضبط حالة الفحص لعنصر الإدخال بنوع خانة الاختيار. |
| [SetColorValue](../../aspose.html.forms/inputelement/setcolorvalue/)(Color) | تُستخدم هذه الطريقة لتعيين اللون كقيمة لعنصر الإدخال. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال هو "color" |
| [SetDateTimeLocalValue](../../aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | تُستخدم هذه الطريقة للتعيينDateTimeالكائن كقيمة لعنصر الإدخال. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال هو "datetime-local" |
| [SetDateValue](../../aspose.html.forms/inputelement/setdatevalue/)(DateTime) | تُستخدم هذه الطريقة للتعيينDateTime الكائن كقيمة لعنصر الإدخال. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال هو "التاريخ" |
| [SetEmailValue](../../aspose.html.forms/inputelement/setemailvalue/)(string) | تُستخدم هذه الطريقة لتعيين سلسلة البريد الإلكتروني كقيمة لعنصر الإدخال. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال هو "البريد الإلكتروني" |
| [SetMonthValue](../../aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | تُستخدم هذه الطريقة للتعيينDateTimeالكائن كقيمة لعنصر الإدخال. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال هو "شهر" |
| [SetNumberValue](../../aspose.html.forms/inputelement/setnumbervalue/)(float) | تُستخدم هذه الطريقة لتعيين الرقم كقيمة لعنصر الإدخال. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال هو "رقم" |
| [SetPasswordValue](../../aspose.html.forms/inputelement/setpasswordvalue/)(string) | تُستخدم هذه الطريقة لتعيين سلسلة كلمة المرور كقيمة لعنصر الإدخال. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال هو "كلمة المرور" |
| [SetRadioValue](../../aspose.html.forms/inputelement/setradiovalue/)(bool) | يضبط حالة الفحص لعنصر الإدخال بنوع الراديو. |
| [SetTimeValue](../../aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | تُستخدم هذه الطريقة للتعيينTimeSpan الكائن كقيمة لعنصر الإدخال. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال هو "الوقت" |
| [SetUrlValue](../../aspose.html.forms/inputelement/seturlvalue/)(Url) | تُستخدم هذه الطريقة للتعيين[`Url`](../../aspose.html/url/) الكائن كقيمة لعنصر الإدخال. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال هو "url" |
| [SetWeekValue](../../aspose.html.forms/inputelement/setweekvalue/)(string) | تُستخدم هذه الطريقة لتعيين سلسلة "الأسبوع" كقيمة لعنصر الإدخال. هذه الطريقة صالحة فقط إذا كان نوع عنصر الإدخال هو "week" |

### أنظر أيضا

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../aspose.html/htmlinputelement/)
* مساحة الاسم [Aspose.Html.Forms](../../aspose.html.forms/)
* المجسم [Aspose.HTML](../../)


