---
title: "InputElement 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.forms.InputElement 클래스. InputElement는 HTMLInputElement와 연결된 래퍼를 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.forms/inputelement/
---
## InputElement class

InputElement는 HTMLInputElement와 연결된 래퍼를 나타냅니다.

```java
public class InputElement : FormElement<HTMLInputElement>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) 요소의 유형을 가져옵니다. |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/inputelement/id/) { get; set; } | 입력 요소의 Id 속성을 나타냅니다. |
| [getList](../../com.aspose.html.forms/inputelement/list/) 옵션 목록을 나타냅니다 |
| [name](../../com.aspose.html.forms/inputelement/name/) { get; set; } | 입력 요소의 name 속성을 나타냅니다. |
[getType]
[setType] Type of the form control. |
| [value](../../com.aspose.html.forms/inputelement/value/) { get; set; } | 'value' 속성에 직접 매핑되는 입력 요소의 문자열 값을 나타냅니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addFile](../../com.aspose.html.forms/inputelement/addfile/)(String) | 이 메서드는 다음 웹 요청 시 전송될 [`Files`](../../com.aspose.html/htmlinputelement/files/) 컬렉션에 파일을 추가합니다. |
| [getCheckboxValue](../../com.aspose.html.forms/inputelement/getcheckboxvalue/)() | Checkbox 유형의 입력 요소에 대한 선택 상태를 반환합니다. |
| [getColorValue](../../com.aspose.html.forms/inputelement/getcolorvalue/)() | 이 메서드는 값을 색상으로 가져오는 데 사용됩니다. 입력 요소의 유형이 "color"인 경우에만 유효합니다. |
| [getDateTimeLocalValue](../../com.aspose.html.forms/inputelement/getdatetimelocalvalue/)() | 이 메서드는 값을 DateTime 객체로 가져오는 데 사용됩니다. 입력 요소의 유형이 "datetime-local"인 경우에만 유효합니다. |
| [getDateValue](../../com.aspose.html.forms/inputelement/getdatevalue/)() | 이 메서드는 값을 DateTime 객체로 가져오는 데 사용됩니다. 입력 요소의 유형이 "date"인 경우에만 유효합니다. |
| [getEmailValue](../../com.aspose.html.forms/inputelement/getemailvalue/)() | 이 메서드는 값을 이메일 문자열 객체로 가져오는 데 사용됩니다. 입력 요소의 유형이 "email"인 경우에만 유효합니다. |
| [getMonthValue](../../com.aspose.html.forms/inputelement/getmonthvalue/)() | 이 메서드는 값을 DateTime 객체로 가져오는 데 사용됩니다. 입력 요소의 유형이 "month"인 경우에만 유효합니다. |
| [getNumberValue](../../com.aspose.html.forms/inputelement/getnumbervalue/)() | 이 메서드는 값을 숫자로 가져오는 데 사용됩니다. 입력 요소의 유형이 "number"인 경우에만 유효합니다. |
| [getPasswordValue](../../com.aspose.html.forms/inputelement/getpasswordvalue/)() | 이 메서드는 값을 비밀번호 문자열 객체로 가져오는 데 사용됩니다. 입력 요소의 유형이 "password"인 경우에만 유효합니다. |
| [getRadioValue](../../com.aspose.html.forms/inputelement/getradiovalue/)() | radio 유형의 입력 요소에 대한 선택 상태를 반환합니다. |
| [getTimeValue](../../com.aspose.html.forms/inputelement/gettimevalue/)() | 이 메서드는 값을 TimeSpan 객체로 가져오는 데 사용됩니다. 입력 요소의 유형이 "time"인 경우에만 유효합니다. |
| [getUrlValue](../../com.aspose.html.forms/inputelement/geturlvalue/)() | 이 메서드는 값을 [`Url`](../../com.aspose.html/url/) 객체로 가져오는 데 사용됩니다. 입력 요소의 유형이 "url"인 경우에만 유효합니다. |
| [getWeekValue](../../com.aspose.html.forms/inputelement/getweekvalue/)() | 이 메서드는 값을 주 문자열로 가져오는 데 사용됩니다. 입력 요소의 유형이 "week"인 경우에만 유효합니다. |
| [setCheckboxValue](../../com.aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | Checkbox 유형의 입력 요소에 대한 선택 상태를 설정합니다. |
| [setColorValue](../../com.aspose.html.forms/inputelement/setcolorvalue/)(Color) | 이 메서드는 색상을 입력 요소의 값으로 설정하는 데 사용됩니다. 입력 요소의 유형이 "color"인 경우에만 유효합니다. |
| [setDateTimeLocalValue](../../com.aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | 이 메서드는 DateTime 객체를 입력 요소의 값으로 설정하는 데 사용됩니다. 입력 요소의 유형이 "datetime-local"인 경우에만 유효합니다. |
| [setDateValue](../../com.aspose.html.forms/inputelement/setdatevalue/)(DateTime) | 이 메서드는 DateTime 객체를 입력 요소의 값으로 설정하는 데 사용됩니다. 입력 요소의 유형이 "date"인 경우에만 유효합니다. |
| [setEmailValue](../../com.aspose.html.forms/inputelement/setemailvalue/)(String) | 이 메서드는 이메일 문자열을 입력 요소의 값으로 설정하는 데 사용됩니다. 입력 요소의 유형이 "email"인 경우에만 유효합니다. |
| [setMonthValue](../../com.aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | 이 메서드는 DateTime 객체를 입력 요소의 값으로 설정하는 데 사용됩니다. 입력 요소의 유형이 "month"인 경우에만 유효합니다. |
| [setNumberValue](../../com.aspose.html.forms/inputelement/setnumbervalue/)(float) | 이 메서드는 숫자를 입력 요소의 값으로 설정하는 데 사용됩니다. 입력 요소의 유형이 "number"인 경우에만 유효합니다. |
| [setPasswordValue](../../com.aspose.html.forms/inputelement/setpasswordvalue/)(String) | 이 메서드는 비밀번호 문자열을 입력 요소의 값으로 설정하는 데 사용됩니다. 입력 요소의 유형이 "password"인 경우에만 유효합니다. |
| [setRadioValue](../../com.aspose.html.forms/inputelement/setradiovalue/)(bool) | radio 유형의 입력 요소에 대한 선택 상태를 설정합니다. |
| [setTimeValue](../../com.aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | 이 메서드는 TimeSpan 객체를 입력 요소의 값으로 설정하는 데 사용됩니다. 입력 요소의 유형이 "time"인 경우에만 유효합니다. |
| [setUrlValue](../../com.aspose.html.forms/inputelement/seturlvalue/)(Url) | 이 메서드는 입력 요소의 값으로 [`Url`](../../com.aspose.html/url/) 객체를 설정하는 데 사용됩니다. 입력 요소의 유형이 "url"인 경우에만 이 메서드를 사용할 수 있습니다. |
| [setWeekValue](../../com.aspose.html.forms/inputelement/setweekvalue/)(String) | 이 메서드는 입력 요소의 값으로 'week' 문자열을 설정하는 데 사용됩니다. 입력 요소의 유형이 "week"인 경우에만 이 메서드를 사용할 수 있습니다. |

### 또 보기

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../com.aspose.html/htmlinputelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
