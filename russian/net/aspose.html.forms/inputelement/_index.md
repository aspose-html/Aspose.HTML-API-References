---
title: InputElement
second_title: Справочник по Aspose.HTML для .NET API
description: InputElement представляет оболочку связанную с HTMLInputElement.
type: docs
weight: 3060
url: /ru/net/aspose.html.forms/inputelement/
---
## InputElement class

InputElement представляет оболочку, связанную с HTMLInputElement.

```csharp
public class InputElement : FormElement<HTMLInputElement>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype) { get; } | Получает тип элемента. |
| [HtmlElement](../../aspose.html.forms/formelement`1/htmlelement) { get; } |  |
| override [Id](../../aspose.html.forms/inputelement/id) { get; set; } | Представляет атрибут Id элемента ввода. |
| [List](../../aspose.html.forms/inputelement/list) { get; } | Представляет список параметров |
| override [Name](../../aspose.html.forms/inputelement/name) { get; set; } | Представляет атрибут имени входного элемента. |
| [Type](../../aspose.html.forms/inputelement/type) { get; set; } | Тип элемента управления формы. |
| override [Value](../../aspose.html.forms/inputelement/value) { get; set; } | Представляет строковое значение элемента ввода, которое непосредственно отображается в атрибут 'value'. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddFile](../../aspose.html.forms/inputelement/addfile)(string) | Этот метод добавляет файлы в коллекцию[`Files`](../../aspose.html/htmlinputelement/files), которые будут отправлены во время следующего веб-запроса. |
| [GetCheckboxValue](../../aspose.html.forms/inputelement/getcheckboxvalue)() | Возвращает состояние проверки для элемента ввода с типом Checkbox. |
| [GetColorValue](../../aspose.html.forms/inputelement/getcolorvalue)() | Этот метод используется для получения значения в виде цвета. Этот метод действителен, если только тип входного элемента "color" |
| [GetDateTimeLocalValue](../../aspose.html.forms/inputelement/getdatetimelocalvalue)() | Этот метод используется для получения значения в виде объектного объектаDateTime. Этот метод действителен, если только тип элемента ввода "datetime-local" |
| [GetDateValue](../../aspose.html.forms/inputelement/getdatevalue)() | Этот метод используется для получения значения в виде объектаDateTime. Этот метод действителен, если только тип входного элемента "дата" |
| [GetEmailValue](../../aspose.html.forms/inputelement/getemailvalue)() | Этот метод используется для получения значения в виде объекта строки электронной почты. Этот метод действителен, если только тип элемента ввода "email" |
| [GetMonthValue](../../aspose.html.forms/inputelement/getmonthvalue)() | Этот метод используется для получения значения в виде объектаDateTime. Этот метод действителен, если только тип входного элемента "месяц" |
| [GetNumberValue](../../aspose.html.forms/inputelement/getnumbervalue)() | Этот метод используется для получения значения в виде числа. Этот метод действителен, если только тип входного элемента "число" |
| [GetPasswordValue](../../aspose.html.forms/inputelement/getpasswordvalue)() | Этот метод используется для получения значения в виде объекта строки пароля. Этот метод действителен, если только тип элемента ввода "пароль" |
| [GetRadioValue](../../aspose.html.forms/inputelement/getradiovalue)() | Возвращает состояние проверки для элемента ввода с типом радио. |
| [GetTimeValue](../../aspose.html.forms/inputelement/gettimevalue)() | Этот метод используется для получения значения в виде объектаTimeSpan. Этот метод действителен только в том случае, если типом входного элемента является "время" |
| [GetUrlValue](../../aspose.html.forms/inputelement/geturlvalue)() | Этот метод используется для получения значения как объекта[`Url`](../../aspose.html/url). Этот метод действителен, если только тип входного элемента "url" |
| [GetWeekValue](../../aspose.html.forms/inputelement/getweekvalue)() | Этот метод используется для получения значения в виде строки недели. Этот метод действителен, если только тип входного элемента "week" |
| [SetCheckboxValue](../../aspose.html.forms/inputelement/setcheckboxvalue)(bool) | Устанавливает состояние проверки для элемента ввода с типом Checkbox. |
| [SetColorValue](../../aspose.html.forms/inputelement/setcolorvalue)(Color) | Этот метод используется для установки цвета в качестве значения для входного элемента. Этот метод действителен только в том случае, если тип входного элемента "color" |
| [SetDateTimeLocalValue](../../aspose.html.forms/inputelement/setdatetimelocalvalue)(DateTime) | Этот метод используется для установки объектаDateTimeв качестве значения для входного элемента. Этот метод действителен только в том случае, если тип элемента ввода "datetime-local" |
| [SetDateValue](../../aspose.html.forms/inputelement/setdatevalue)(DateTime) | Этот метод используется для установки объектаDateTimeв качестве значения для входного элемента. Этот метод действителен только в том случае, если тип элемента ввода "дата" |
| [SetEmailValue](../../aspose.html.forms/inputelement/setemailvalue)(string) | Этот метод используется для установки строки электронной почты в качестве значения для элемента ввода. Этот метод действителен, если только тип элемента ввода "email" |
| [SetMonthValue](../../aspose.html.forms/inputelement/setmonthvalue)(DateTime) | Этот метод используется для установки объектаDateTimeв качестве значения для входного элемента. Этот метод действителен только в том случае, если тип входного элемента "month" |
| [SetNumberValue](../../aspose.html.forms/inputelement/setnumbervalue)(float) | Этот метод используется для установки числа в качестве значения для входного элемента. Этот метод действителен только в том случае, если тип входного элемента "число" |
| [SetPasswordValue](../../aspose.html.forms/inputelement/setpasswordvalue)(string) | Этот метод используется для установки строки пароля в качестве значения для элемента ввода. Этот метод действителен только в том случае, если тип элемента ввода "пароль" |
| [SetRadioValue](../../aspose.html.forms/inputelement/setradiovalue)(bool) | Устанавливает состояние проверки для элемента ввода с типом радио. |
| [SetTimeValue](../../aspose.html.forms/inputelement/settimevalue)(TimeSpan) | Этот метод используется для установки объектаTimeSpanв качестве значения для входного элемента. Этот метод действителен только в том случае, если тип входного элемента — «время» |
| [SetUrlValue](../../aspose.html.forms/inputelement/seturlvalue)(Url) | Этот метод используется для установки объекта[`Url`](../../aspose.html/url)в качестве значения для входного элемента. Этот метод действителен только в том случае, если тип входного элемента "url" |
| [SetWeekValue](../../aspose.html.forms/inputelement/setweekvalue)(string) | Этот метод используется для установки строки «неделя» в качестве значения для входного элемента. Этот метод действителен только в том случае, если тип входного элемента "week" |

### Смотрите также

* class [FormElement&lt;T&gt;](../formelement-1)
* class [HTMLInputElement](../../aspose.html/htmlinputelement)
* пространство имен [Aspose.Html.Forms](../../aspose.html.forms)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
