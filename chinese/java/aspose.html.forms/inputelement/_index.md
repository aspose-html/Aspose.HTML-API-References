---
title: "InputElement 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.forms.InputElement 类。InputElement 表示一个与 HTMLInputElement 关联的包装器。"
type: docs

url: /zh/java/com.aspose.html.forms/inputelement/
---
## InputElement class

InputElement 表示与 HTMLInputElement 关联的包装器。

```java
public class InputElement : FormElement<HTMLInputElement>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) 获取元素的类型。 |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/inputelement/id/) { get; set; } | 表示输入元素的 Id 属性。 |
| [getList](../../com.aspose.html.forms/inputelement/list/) 表示一个选项列表 |
| [name](../../com.aspose.html.forms/inputelement/name/) { get; set; } | 表示输入元素的 name 属性。 |
[getType]
[setType] Type of the form control. |
| [value](../../com.aspose.html.forms/inputelement/value/) { get; set; } | 表示直接映射到 'value' 属性的输入元素的字符串值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [addFile](../../com.aspose.html.forms/inputelement/addfile/)(String) | 此方法将文件添加到 [`Files`](../../com.aspose.html/htmlinputelement/files/) 集合中，这些文件将在下一个 Web 请求中发送。 |
| [getCheckboxValue](../../com.aspose.html.forms/inputelement/getcheckboxvalue/)() | 返回复选框类型输入元素的选中状态。 |
| [getColorValue](../../com.aspose.html.forms/inputelement/getcolorvalue/)() | 此方法用于获取颜色值。仅当输入元素的类型为 "color" 时，此方法有效。 |
| [getDateTimeLocalValue](../../com.aspose.html.forms/inputelement/getdatetimelocalvalue/)() | 此方法用于获取 DateTime 对象值。仅当输入元素的类型为 "datetime-local" 时，此方法有效。 |
| [getDateValue](../../com.aspose.html.forms/inputelement/getdatevalue/)() | 此方法用于获取 DateTime 对象值。仅当输入元素的类型为 "date" 时，此方法有效。 |
| [getEmailValue](../../com.aspose.html.forms/inputelement/getemailvalue/)() | 此方法用于获取电子邮件字符串对象的值。仅当输入元素的类型为 "email" 时，此方法有效。 |
| [getMonthValue](../../com.aspose.html.forms/inputelement/getmonthvalue/)() | 此方法用于获取 DateTime 对象值。仅当输入元素的类型为 "month" 时，此方法有效。 |
| [getNumberValue](../../com.aspose.html.forms/inputelement/getnumbervalue/)() | 此方法用于获取数值。仅当输入元素的类型为 "number" 时，此方法有效。 |
| [getPasswordValue](../../com.aspose.html.forms/inputelement/getpasswordvalue/)() | 此方法用于获取密码字符串对象的值。仅当输入元素的类型为 "password" 时，此方法有效。 |
| [getRadioValue](../../com.aspose.html.forms/inputelement/getradiovalue/)() | 返回单选按钮类型输入元素的选中状态。 |
| [getTimeValue](../../com.aspose.html.forms/inputelement/gettimevalue/)() | 此方法用于获取 TimeSpan 对象值。仅当输入元素的类型为 "time" 时，此方法有效。 |
| [getUrlValue](../../com.aspose.html.forms/inputelement/geturlvalue/)() | 此方法用于获取 [`Url`](../../com.aspose.html/url/) 对象值。仅当输入元素的类型为 "url" 时，此方法有效。 |
| [getWeekValue](../../com.aspose.html.forms/inputelement/getweekvalue/)() | 此方法用于获取周字符串值。仅当输入元素的类型为 "week" 时，此方法有效。 |
| [setCheckboxValue](../../com.aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | 设置复选框类型输入元素的选中状态。 |
| [setColorValue](../../com.aspose.html.forms/inputelement/setcolorvalue/)(Color) | 此方法用于将颜色设置为输入元素的值。仅当输入元素的类型为 "color" 时，此方法有效。 |
| [setDateTimeLocalValue](../../com.aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | 此方法用于将 DateTime 对象设置为输入元素的值。仅当输入元素的类型为 "datetime-local" 时，此方法有效。 |
| [setDateValue](../../com.aspose.html.forms/inputelement/setdatevalue/)(DateTime) | 此方法用于将 DateTime 对象设置为输入元素的值。仅当输入元素的类型为 "date" 时，此方法有效。 |
| [setEmailValue](../../com.aspose.html.forms/inputelement/setemailvalue/)(String) | 此方法用于将电子邮件字符串设置为输入元素的值。仅当输入元素的类型为 "email" 时，此方法有效。 |
| [setMonthValue](../../com.aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | 此方法用于将 DateTime 对象设置为输入元素的值。仅当输入元素的类型为 "month" 时，此方法有效。 |
| [setNumberValue](../../com.aspose.html.forms/inputelement/setnumbervalue/)(float) | 此方法用于将数字设置为输入元素的值。仅当输入元素的类型为 "number" 时，此方法有效。 |
| [setPasswordValue](../../com.aspose.html.forms/inputelement/setpasswordvalue/)(String) | 此方法用于将密码字符串设置为输入元素的值。仅当输入元素的类型为 "password" 时，此方法有效。 |
| [setRadioValue](../../com.aspose.html.forms/inputelement/setradiovalue/)(bool) | 设置单选按钮类型输入元素的选中状态。 |
| [setTimeValue](../../com.aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | 此方法用于将 TimeSpan 对象设置为输入元素的值。仅当输入元素的类型为 "time" 时，此方法有效。 |
| [setUrlValue](../../com.aspose.html.forms/inputelement/seturlvalue/)(Url) | 此方法用于将 [`Url`](../../com.aspose.html/url/) 对象设置为输入元素的值。仅当输入元素的类型为 "url" 时，此方法有效。 |
| [setWeekValue](../../com.aspose.html.forms/inputelement/setweekvalue/)(String) | 此方法用于将 'week' 字符串设置为输入元素的值。仅当输入元素的类型为 "week" 时，此方法有效。 |

### 另请参阅

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../com.aspose.html/htmlinputelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
