---
title: Class InputElement
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Forms.InputElement 班级. InputElement 表示与 HTMLInputElement 关联的包装器
type: docs
weight: 2980
url: /zh/net/aspose.html.forms/inputelement/
---
## InputElement class

InputElement 表示与 HTMLInputElement 关联的包装器。

```csharp
public class InputElement : FormElement<HTMLInputElement>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype/) { get; } | 获取元素的类型。 |
| [HtmlElement](../../aspose.html.forms/formelement-1/htmlelement/) { get; } |  |
| override [Id](../../aspose.html.forms/inputelement/id/) { get; set; } | 表示输入元素的Id属性。 |
| [List](../../aspose.html.forms/inputelement/list/) { get; } | 表示选项列表 |
| override [Name](../../aspose.html.forms/inputelement/name/) { get; set; } | 表示输入元素的name属性。 |
| [Type](../../aspose.html.forms/inputelement/type/) { get; set; } | 表单控件的类型。 |
| override [Value](../../aspose.html.forms/inputelement/value/) { get; set; } | 表示直接映射到'value'属性的输入元素的字符串值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddFile](../../aspose.html.forms/inputelement/addfile/)(string) | 此方法将文件添加到[`Files`](../../aspose.html/htmlinputelement/files/)将在下一次 Web 请求期间发送的集合。 |
| [GetCheckboxValue](../../aspose.html.forms/inputelement/getcheckboxvalue/)() | 返回 Checkbox 类型的输入元素的选中状态。 |
| [GetColorValue](../../aspose.html.forms/inputelement/getcolorvalue/)() | 此方法用于获取作为颜色的值。此方法仅在输入元素的类型为“color” 时有效 |
| [GetDateTimeLocalValue](../../aspose.html.forms/inputelement/getdatetimelocalvalue/)() | 此方法用于获取值作为DateTime对象对象。此方法仅在输入元素的类型为“datetime-local” 时才有效 |
| [GetDateValue](../../aspose.html.forms/inputelement/getdatevalue/)() | 此方法用于获取值作为DateTime目的。此方法仅在输入元素的类型为“date” 时才有效 |
| [GetEmailValue](../../aspose.html.forms/inputelement/getemailvalue/)() | 此方法用于获取作为电子邮件字符串对象的值。此方法仅在输入元素的类型为“email” 时有效 |
| [GetMonthValue](../../aspose.html.forms/inputelement/getmonthvalue/)() | 此方法用于获取值作为DateTime目的。此方法仅在输入元素的类型为“month” 时有效 |
| [GetNumberValue](../../aspose.html.forms/inputelement/getnumbervalue/)() | 此方法用于获取数字形式的值。此方法仅在输入元素的类型为“number” 时有效 |
| [GetPasswordValue](../../aspose.html.forms/inputelement/getpasswordvalue/)() | 此方法用于获取作为密码字符串对象的值。此方法仅在输入元素的类型为“password” 时有效 |
| [GetRadioValue](../../aspose.html.forms/inputelement/getradiovalue/)() | 返回具有无线电类型的输入元素的检查状态。 |
| [GetTimeValue](../../aspose.html.forms/inputelement/gettimevalue/)() | 此方法用于获取值作为TimeSpan目的。此方法仅在输入元素的类型为“time” 时才有效 |
| [GetUrlValue](../../aspose.html.forms/inputelement/geturlvalue/)() | 此方法用于获取值作为[`Url`](../../aspose.html/url/)目的。此方法仅在输入元素的类型为“url” 时有效 |
| [GetWeekValue](../../aspose.html.forms/inputelement/getweekvalue/)() | 此方法用于获取作为星期字符串的值。此方法仅在输入元素的类型为“week” 时有效 |
| [SetCheckboxValue](../../aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | 为 Checkbox 类型的输入元素设置选中状态。 |
| [SetColorValue](../../aspose.html.forms/inputelement/setcolorvalue/)(Color) | 此方法用于将颜色设置为输入元素的值。此方法仅在输入元素的类型为“color” 时有效 |
| [SetDateTimeLocalValue](../../aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | 这个方法用来设置DateTime对象作为输入元素的值。此方法仅在输入元素的类型为“datetime-local” 时有效 |
| [SetDateValue](../../aspose.html.forms/inputelement/setdatevalue/)(DateTime) | 这个方法用来设置DateTime对象作为输入元素的值。此方法仅在输入元素的类型为“date” 时有效 |
| [SetEmailValue](../../aspose.html.forms/inputelement/setemailvalue/)(string) | 此方法用于将电子邮件字符串设置为输入元素的值。此方法仅在输入元素的类型为“email” 时有效 |
| [SetMonthValue](../../aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | 这个方法用来设置DateTime对象作为输入元素的值。此方法仅在输入元素的类型为“month” 时有效 |
| [SetNumberValue](../../aspose.html.forms/inputelement/setnumbervalue/)(float) | 此方法用于将数字设置为输入元素的值。此方法仅在输入元素的类型为“number” 时有效 |
| [SetPasswordValue](../../aspose.html.forms/inputelement/setpasswordvalue/)(string) | 此方法用于将密码字符串设置为输入元素的值。只有输入元素的类型为“password” 时，该方法才有效 |
| [SetRadioValue](../../aspose.html.forms/inputelement/setradiovalue/)(bool) | 为具有无线电类型的输入元素设置检查状态。 |
| [SetTimeValue](../../aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | 这个方法用来设置TimeSpan对象作为输入元素的值。此方法仅在输入元素的类型为“time” 时有效 |
| [SetUrlValue](../../aspose.html.forms/inputelement/seturlvalue/)(Url) | 这个方法用来设置[`Url`](../../aspose.html/url/)对象作为输入元素的值。此方法仅在输入元素的类型为“url” 时有效 |
| [SetWeekValue](../../aspose.html.forms/inputelement/setweekvalue/)(string) | 此方法用于将“week”字符串设置为输入元素的值。此方法仅在输入元素的类型为“week” 时有效 |

### 也可以看看

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../aspose.html/htmlinputelement/)
* 命名空间 [Aspose.Html.Forms](../../aspose.html.forms/)
* 部件 [Aspose.HTML](../../)


