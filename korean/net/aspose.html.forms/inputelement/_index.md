---
title: Class InputElement
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Forms.InputElement 수업. InputElement는 HTMLInputElement. 와 연결된 래퍼를 나타냅니다.
type: docs
weight: 2980
url: /ko/net/aspose.html.forms/inputelement/
---
## InputElement class

InputElement는 HTMLInputElement. 와 연결된 래퍼를 나타냅니다.

```csharp
public class InputElement : FormElement<HTMLInputElement>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype/) { get; } | 요소의 유형을 가져옵니다. |
| [HtmlElement](../../aspose.html.forms/formelement-1/htmlelement/) { get; } |  |
| override [Id](../../aspose.html.forms/inputelement/id/) { get; set; } | 입력 요소의 Id 특성을 나타냅니다. |
| [List](../../aspose.html.forms/inputelement/list/) { get; } | options 목록을 나타냅니다. |
| override [Name](../../aspose.html.forms/inputelement/name/) { get; set; } | 입력 요소의 이름 속성을 나타냅니다. |
| [Type](../../aspose.html.forms/inputelement/type/) { get; set; } | 양식 컨트롤의 유형입니다. |
| override [Value](../../aspose.html.forms/inputelement/value/) { get; set; } | 'value' 속성에 직접 매핑되는 입력 요소의 문자열 값을 나타냅니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddFile](../../aspose.html.forms/inputelement/addfile/)(string) | 이 메서드는 파일을[`Files`](../../aspose.html/htmlinputelement/files/) 다음 웹 요청 중에 전송될 컬렉션입니다. |
| [GetCheckboxValue](../../aspose.html.forms/inputelement/getcheckboxvalue/)() | 체크박스 유형이 . 인 입력 요소의 체크 상태를 반환합니다. |
| [GetColorValue](../../aspose.html.forms/inputelement/getcolorvalue/)() | 이 메서드는 값을 색상으로 가져오는 데 사용됩니다. 이 방법은 입력 요소의 유형만 "color" 인 경우에만 유효합니다. |
| [GetDateTimeLocalValue](../../aspose.html.forms/inputelement/getdatetimelocalvalue/)() | 이 방법은 값을DateTime 객체 객체. 이 방법은 입력 요소의 유형만 "datetime-local" 인 경우에만 유효합니다. |
| [GetDateValue](../../aspose.html.forms/inputelement/getdatevalue/)() | 이 방법은 값을DateTime 물체. 이 방법은 입력 요소의 유형만 "날짜" 인 경우에만 유효합니다. |
| [GetEmailValue](../../aspose.html.forms/inputelement/getemailvalue/)() | 이 메서드는 이메일 문자열 개체로 값을 가져오는 데 사용됩니다. 이 방법은 입력 요소의 유형만 "email" 인 경우에만 유효합니다. |
| [GetMonthValue](../../aspose.html.forms/inputelement/getmonthvalue/)() | 이 방법은 값을DateTime 물체. 이 방법은 입력 요소의 유형만 "month" 인 경우에만 유효합니다. |
| [GetNumberValue](../../aspose.html.forms/inputelement/getnumbervalue/)() | 이 방법은 값을 숫자로 가져오는 데 사용됩니다. 이 방법은 입력 요소의 유형만 "숫자" 인 경우에만 유효합니다. |
| [GetPasswordValue](../../aspose.html.forms/inputelement/getpasswordvalue/)() | 이 메서드는 암호 문자열 개체로 값을 가져오는 데 사용됩니다. 이 방법은 입력 요소의 유형만 "password" 인 경우에만 유효합니다. |
| [GetRadioValue](../../aspose.html.forms/inputelement/getradiovalue/)() | 라디오 유형이 있는 입력 요소의 검사 상태를 반환합니다. |
| [GetTimeValue](../../aspose.html.forms/inputelement/gettimevalue/)() | 이 방법은 값을TimeSpan 물체. 이 방법은 입력 요소의 유형만 "time" 인 경우에만 유효합니다. |
| [GetUrlValue](../../aspose.html.forms/inputelement/geturlvalue/)() | 이 방법은 값을 다음과 같이 가져오는 데 사용됩니다.[`Url`](../../aspose.html/url/) 물체. 이 방법은 입력 요소의 유형만 "url" 인 경우에만 유효합니다. |
| [GetWeekValue](../../aspose.html.forms/inputelement/getweekvalue/)() | 이 방법은 값을 주 문자열로 가져오는 데 사용됩니다. 이 방법은 입력 요소의 유형만 "주" 인 경우에만 유효합니다. |
| [SetCheckboxValue](../../aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | 체크박스 유형의 입력 요소에 대한 체크 상태를 설정합니다. |
| [SetColorValue](../../aspose.html.forms/inputelement/setcolorvalue/)(Color) | 이 메서드는 입력 요소에 대한 값으로 색상을 설정하는 데 사용됩니다. 이 방법은 입력 요소의 유형이 "color" 인 경우에만 유효합니다. |
| [SetDateTimeLocalValue](../../aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | 이 방법은 설정하는 데 사용됩니다.DateTime개체를 입력 요소의 값으로 사용합니다. 이 방법은 입력 요소의 유형이 "datetime-local" 인 경우에만 유효합니다. |
| [SetDateValue](../../aspose.html.forms/inputelement/setdatevalue/)(DateTime) | 이 방법은 설정하는 데 사용됩니다.DateTime 개체를 입력 요소의 값으로 사용합니다. 이 방법은 입력 요소의 유형이 "날짜" 인 경우에만 유효합니다. |
| [SetEmailValue](../../aspose.html.forms/inputelement/setemailvalue/)(string) | 이 메소드는 이메일 문자열을 입력 요소의 값으로 설정하는 데 사용됩니다. 이 방법은 입력 요소의 유형이 "email" 인 경우에만 유효합니다. |
| [SetMonthValue](../../aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | 이 방법은 설정하는 데 사용됩니다.DateTime개체를 입력 요소의 값으로 사용합니다. 이 방법은 입력 요소의 유형이 "month" 인 경우에만 유효합니다. |
| [SetNumberValue](../../aspose.html.forms/inputelement/setnumbervalue/)(float) | 이 메소드는 입력 요소에 대한 값으로 숫자를 설정하는 데 사용됩니다. 이 방법은 입력 요소의 유형이 "숫자" 인 경우에만 유효합니다. |
| [SetPasswordValue](../../aspose.html.forms/inputelement/setpasswordvalue/)(string) | 이 메소드는 입력 요소에 대한 값으로 비밀번호 문자열을 설정하는 데 사용됩니다. 이 방법은 입력 요소의 유형이 "password" 인 경우에만 유효합니다. |
| [SetRadioValue](../../aspose.html.forms/inputelement/setradiovalue/)(bool) | 라디오 유형이 있는 입력 요소의 검사 상태를 설정합니다. |
| [SetTimeValue](../../aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | 이 방법은 설정하는 데 사용됩니다.TimeSpan 개체를 입력 요소의 값으로 사용합니다. 이 방법은 입력 요소의 유형이 "time" 인 경우에만 유효합니다. |
| [SetUrlValue](../../aspose.html.forms/inputelement/seturlvalue/)(Url) | 이 방법은 설정하는 데 사용됩니다.[`Url`](../../aspose.html/url/) 개체를 입력 요소의 값으로 사용합니다. 이 방법은 입력 요소의 유형이 "url" 인 경우에만 유효합니다. |
| [SetWeekValue](../../aspose.html.forms/inputelement/setweekvalue/)(string) | 이 메소드는 'week' 문자열을 입력 요소의 값으로 설정하는 데 사용됩니다. 이 방법은 입력 요소의 유형이 "주" 인 경우에만 유효합니다. |

### 또한보십시오

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../aspose.html/htmlinputelement/)
* 네임스페이스 [Aspose.Html.Forms](../../aspose.html.forms/)
* 집회 [Aspose.HTML](../../)


