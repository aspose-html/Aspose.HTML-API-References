---
title: "FormEditor 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.forms.FormEditor 클래스. 이 클래스는 HTMLFormElement에 대한 편집기를 나타내며, .net 개발자가 HTML 폼을 보다 쉽게 편집할 수 있도록 합니다."
type: docs

url: /ko/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

이 클래스는 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)에 대한 편집기를 나타내며, .net 개발자가 HTML 폼을 보다 쉽게 편집할 수 있도록 합니다.

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## 속성

| 이름 | 설명 |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) 폼에 포함된 폼 컨트롤의 수입니다. |
| [getForm](../../com.aspose.html.forms/formeditor/form/) 현재 `FormEditor` 인스턴스와 연결된 원본 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)입니다. |
| [getItem](../../com.aspose.html.forms/formeditor/item/) 지정된 인덱스로 요소를 반환합니다. (2개의 인덱서) |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | 새로운 `FormEditor`를 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)를 기반으로 생성합니다. |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | 인덱스로 선택된 [`Forms`](../../com.aspose.html/htmldocument/forms/) 컬렉션의 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)을 기반으로 새로운 `FormEditor`를 생성합니다. |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | 문서에서 ID로 선택된 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)을 기반으로 새로운 `FormEditor`를 생성합니다. |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | 새로운 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)를 생성하고 이를 `FormEditor`와 연결합니다. [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)는 문서에서 분리된 상태로 생성됩니다; 이를 문서에 첨부하려면 적절한 위치를 선택하고 [`AppendChild`](../../com.aspose.html.dom/node/appendchild/) 메서드를 사용하십시오. |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | 새로운 [`HTMLElement`](../../com.aspose.html/htmlelement/)를 생성하고 폼의 끝에 추가합니다. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | 새로운 [`InputElement`](../inputelement/)를 생성하고 폼의 끝에 추가합니다. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | 새로운 [`InputElement`](../inputelement/)를 생성하고 폼의 끝에 추가합니다. |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | 관리되지 않는 리소스와 관리되는 리소스를 해제합니다. |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | 지정된 인덱스로 요소를 반환합니다. |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | 지정된 이름으로 요소를 반환합니다. |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | 열거자를 가져옵니다. |

### 또 보기

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
