---
title: Class InputElement
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Forms.InputElement sınıf. InputElement HTMLInputElement. ile ilişkilendirilmiş bir sarmalayıcıyı temsil eder.
type: docs
weight: 2980
url: /tr/net/aspose.html.forms/inputelement/
---
## InputElement class

InputElement, HTMLInputElement. ile ilişkilendirilmiş bir sarmalayıcıyı temsil eder.

```csharp
public class InputElement : FormElement<HTMLInputElement>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype/) { get; } | Öğenin türünü alır. |
| [HtmlElement](../../aspose.html.forms/formelement-1/htmlelement/) { get; } |  |
| override [Id](../../aspose.html.forms/inputelement/id/) { get; set; } | Giriş öğesinin Id özniteliğini temsil eder. |
| [List](../../aspose.html.forms/inputelement/list/) { get; } | Bir seçenekler listesini temsil eder |
| override [Name](../../aspose.html.forms/inputelement/name/) { get; set; } | Giriş öğesinin ad özniteliğini temsil eder. |
| [Type](../../aspose.html.forms/inputelement/type/) { get; set; } | Form denetimi türü. |
| override [Value](../../aspose.html.forms/inputelement/value/) { get; set; } | Doğrudan "değer" özniteliğine eşlenen giriş öğesinin dize değerini temsil eder. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddFile](../../aspose.html.forms/inputelement/addfile/)(string) | Bu yöntem, dosyaları[`Files`](../../aspose.html/htmlinputelement/files/) sonraki web isteği sırasında gönderilecek koleksiyon. |
| [GetCheckboxValue](../../aspose.html.forms/inputelement/getcheckboxvalue/)() | Onay Kutusu türü . olan giriş öğesi için denetlenmişlik durumunu döndürür |
| [GetColorValue](../../aspose.html.forms/inputelement/getcolorvalue/)() | Bu metod renk olarak değer elde etmek için kullanılır. Bu yöntem, yalnızca giriş öğesinin türü "color" ise geçerlidir. |
| [GetDateTimeLocalValue](../../aspose.html.forms/inputelement/getdatetimelocalvalue/)() | Bu yöntem, değeri bir değer olarak almak için kullanılır.DateTime nesne nesnesi. Bu yöntem, yalnızca giriş öğesinin türü "datetime-local" ise geçerlidir. |
| [GetDateValue](../../aspose.html.forms/inputelement/getdatevalue/)() | Bu yöntem, değeri bir değer olarak almak için kullanılır.DateTime nesne. Bu yöntem, yalnızca giriş öğesinin türü "date" ise geçerlidir. |
| [GetEmailValue](../../aspose.html.forms/inputelement/getemailvalue/)() | Bu yöntem, değeri bir e-posta dizesi nesnesi olarak almak için kullanılır. Bu yöntem, yalnızca giriş öğesinin türü "email" ise geçerlidir. |
| [GetMonthValue](../../aspose.html.forms/inputelement/getmonthvalue/)() | Bu yöntem, değeri bir değer olarak almak için kullanılır.DateTime nesne. Bu yöntem, yalnızca giriş öğesinin türü "ay" ise geçerlidir. |
| [GetNumberValue](../../aspose.html.forms/inputelement/getnumbervalue/)() | Bu metot değeri sayı olarak almak için kullanılır. Bu yöntem, yalnızca giriş öğesinin türü "number" ise geçerlidir. |
| [GetPasswordValue](../../aspose.html.forms/inputelement/getpasswordvalue/)() | Bu yöntem, değeri bir parola dizesi nesnesi olarak almak için kullanılır. Bu yöntem, yalnızca giriş öğesinin türü "password" ise geçerlidir. |
| [GetRadioValue](../../aspose.html.forms/inputelement/getradiovalue/)() | Radyo türüyle giriş öğesi için kontrol durumunu döndürür. |
| [GetTimeValue](../../aspose.html.forms/inputelement/gettimevalue/)() | Bu yöntem, değeri bir değer olarak almak için kullanılır.TimeSpan nesne. Bu yöntem, yalnızca giriş öğesinin türü "zaman" ise geçerlidir. |
| [GetUrlValue](../../aspose.html.forms/inputelement/geturlvalue/)() | Bu yöntem, değeri şu şekilde almak için kullanılır:[`Url`](../../aspose.html/url/) nesne. Bu yöntem, yalnızca giriş öğesinin türü "url" ise geçerlidir. |
| [GetWeekValue](../../aspose.html.forms/inputelement/getweekvalue/)() | Bu yöntem, değeri bir hafta dizisi olarak almak için kullanılır. Bu yöntem, yalnızca giriş öğesinin türü "hafta" ise geçerlidir. |
| [SetCheckboxValue](../../aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | Onay Kutusu türüyle giriş öğesi için denetlenmişlik durumunu ayarlar. |
| [SetColorValue](../../aspose.html.forms/inputelement/setcolorvalue/)(Color) | Bu yöntem, rengi giriş öğesi için bir değer olarak ayarlamak için kullanılır. Bu yöntem, yalnızca giriş öğesinin türü "color" ise geçerlidir. |
| [SetDateTimeLocalValue](../../aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | Bu yöntem, ayarlamak için kullanılırDateTimegiriş öğesi için bir değer olarak nesne. Bu yöntem, yalnızca giriş öğesinin türü "datetime-local" ise geçerlidir. |
| [SetDateValue](../../aspose.html.forms/inputelement/setdatevalue/)(DateTime) | Bu yöntem, ayarlamak için kullanılırDateTime giriş öğesi için bir değer olarak nesne. Bu yöntem, yalnızca giriş öğesinin türü "date" ise geçerlidir. |
| [SetEmailValue](../../aspose.html.forms/inputelement/setemailvalue/)(string) | Bu yöntem, e-posta dizesini giriş öğesi için bir değer olarak ayarlamak için kullanılır. Bu yöntem, yalnızca giriş öğesinin türü "email" ise geçerlidir. |
| [SetMonthValue](../../aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | Bu yöntem, ayarlamak için kullanılırDateTimegiriş öğesi için bir değer olarak nesne. Bu yöntem, yalnızca giriş öğesinin türü "ay" ise geçerlidir. |
| [SetNumberValue](../../aspose.html.forms/inputelement/setnumbervalue/)(float) | Bu yöntem, sayıyı giriş öğesi için bir değer olarak ayarlamak için kullanılır. Bu yöntem, yalnızca giriş öğesinin türü "number" ise geçerlidir. |
| [SetPasswordValue](../../aspose.html.forms/inputelement/setpasswordvalue/)(string) | Bu yöntem, giriş öğesi için bir değer olarak parola dizisini ayarlamak için kullanılır. Bu yöntem, yalnızca giriş öğesinin türü "password" ise geçerlidir. |
| [SetRadioValue](../../aspose.html.forms/inputelement/setradiovalue/)(bool) | Radyo tipi ile giriş elemanı için kontrol durumunu ayarlar. |
| [SetTimeValue](../../aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | Bu yöntem, ayarlamak için kullanılırTimeSpan giriş öğesi için bir değer olarak nesne. Bu yöntem, yalnızca giriş öğesinin türü "zaman" ise geçerlidir. |
| [SetUrlValue](../../aspose.html.forms/inputelement/seturlvalue/)(Url) | Bu yöntem, ayarlamak için kullanılır[`Url`](../../aspose.html/url/) giriş öğesi için bir değer olarak nesne. Bu yöntem, yalnızca giriş öğesinin türü "url" ise geçerlidir. |
| [SetWeekValue](../../aspose.html.forms/inputelement/setweekvalue/)(string) | Bu yöntem, 'hafta' dizesini giriş öğesi için bir değer olarak ayarlamak için kullanılır. Bu yöntem, yalnızca giriş öğesinin türü "hafta" ise geçerlidir. |

### Ayrıca bakınız

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../aspose.html/htmlinputelement/)
* ad alanı [Aspose.Html.Forms](../../aspose.html.forms/)
* toplantı [Aspose.HTML](../../)


