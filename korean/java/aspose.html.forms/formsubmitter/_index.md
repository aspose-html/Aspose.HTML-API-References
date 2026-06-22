---
title: "FormSubmitter 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.forms.FormSubmitter 클래스. 이 클래스는 지정된 HTMLFormElement를 준비하고, 폼 요소에서 값을 수집하여 원격 서버에 제출하고 응답을 받습니다."
type: docs

url: /ko/java/com.aspose.html.forms/formsubmitter/
---
## FormSubmitter class

이 클래스는 지정된 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)를 준비하고, 폼 요소에서 값을 수집하여 원격 서버에 제출하고 응답을 받습니다.

```java
public class FormSubmitter : IDisposable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FormSubmitter](formsubmitter/#constructor)(FormEditor) | `FormSubmitter` 클래스의 새 인스턴스를 초기화합니다. |
| [FormSubmitter](formsubmitter/#constructor_3)(HTMLFormElement) | [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)을 기반으로 `FormSubmitter` 클래스의 새 인스턴스를 초기화합니다. |
| [FormSubmitter](formsubmitter/#constructor_1)(HTMLDocument, int) | [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)을 인덱스로 선택한 [`HTMLDocument`](../../com.aspose.html/htmldocument/)에서 선택하여 `FormSubmitter` 클래스의 새 인스턴스를 초기화합니다. |
| [FormSubmitter](formsubmitter/#constructor_2)(HTMLDocument, String) | [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)을 식별자로 선택한 [`HTMLDocument`](../../com.aspose.html/htmldocument/)에서 선택하여 `FormSubmitter` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [dispose](../../com.aspose.html.forms/formsubmitter/dispose/)() | 관리되지 않는 리소스와 (옵션으로) 관리되는 리소스를 해제합니다. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit)() | 폼 데이터를 서버에 제출합니다. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_1)(CookieContainer) | 지정된 쿠키와 함께 폼 데이터를 서버에 제출합니다. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_2)(ICredentials) | 지정된 사용자 자격 증명을 사용하여 폼 데이터를 서버에 제출합니다. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_8)(TimeSpan) | 지정된 시간 제한을 사용하여 폼 데이터를 서버에 제출합니다. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_3)(ICredentials, CookieContainer) | 지정된 사용자 자격 증명 및 쿠키를 사용하여 폼 데이터를 서버에 제출합니다. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_4)(ICredentials, TimeSpan) | 지정된 사용자 자격 증명 및 시간 제한을 사용하여 폼 데이터를 서버에 제출합니다. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_9)(TimeSpan, CookieContainer) | 지정된 시간 제한 및 쿠키를 사용하여 폼 데이터를 서버에 제출합니다. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_5)(ICredentials, TimeSpan, bool) | 지정된 사용자 자격 증명을 사용하여 폼 데이터를 서버에 제출합니다. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_7)(ICredentials, TimeSpan, CookieContainer) | 지정된 사용자 자격 증명, 시간 제한 및 쿠키를 사용하여 폼 데이터를 서버에 제출합니다. |
| [submit](../../com.aspose.html.forms/formsubmitter/submit/#submit_6)(ICredentials, TimeSpan, bool, CookieContainer) | 지정된 사용자 자격 증명 및 쿠키를 사용하여 폼 데이터를 서버에 제출합니다. |

### 또 보기

* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
