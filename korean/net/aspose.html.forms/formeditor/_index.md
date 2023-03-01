---
title: Class FormEditor
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Forms.FormEditor 수업. 이 클래스는HTMLFormElement .net 개발자가 html 양식을 쉽게 편집할 수 있는 방법을 제공합니다.
type: docs
weight: 2930
url: /ko/net/aspose.html.forms/formeditor/
---
## FormEditor class

이 클래스는[`HTMLFormElement`](../../aspose.html/htmlformelement/) .net 개발자가 html 양식을 쉽게 편집할 수 있는 방법을 제공합니다.

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | 서버 측 양식 핸들러. HTML 4.01. 의 action 속성 정의를 참조하십시오. |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | 양식의 양식 컨트롤 수입니다. |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | 원본[`HTMLFormElement`](../../aspose.html/htmlformelement/) 현재 인스턴스와 연결된`FormEditor` . |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | 지정된 인덱스로 요소를 반환합니다. (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | HTTP 메서드 [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt) 양식을 제출하는 데 사용됩니다. HTML 4.01. 의 메소드 속성 정의를 참조하십시오. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | 새로 만들기`FormEditor` 기반으로[`HTMLFormElement`](../../aspose.html/htmlformelement/) . |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | 새로 만들기`FormEditor` 기반으로[`HTMLFormElement`](../../aspose.html/htmlformelement/) 에서 선택한[`Forms`](../../aspose.html/htmldocument/forms/) index. 로 수집 |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | 새로 만들기`FormEditor` 기반으로[`HTMLFormElement`](../../aspose.html/htmlformelement/) id. 로 문서에서 선택됨 |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | 새로 만들기[`HTMLFormElement`](../../aspose.html/htmlformelement/) 그리고 그것을 연결`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/) 문서 상태에서 분리된 상태로 생성됩니다. 문서에 첨부하기 위해서는 적절한 위치를 선택하여 사용하시기 바랍니다.[`AppendChild`](../../aspose.html.dom/node/appendchild/) 방법. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | 새로 만들기[`HTMLElement`](../../aspose.html/htmlelement/) 양식의 끝에 추가합니다. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | 새로 만들기[`InputElement`](../inputelement/) 양식의 끝에 추가합니다. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | 새로 만들기[`InputElement`](../inputelement/) 양식의 끝에 추가합니다. |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | 비관리 및 관리 리소스를 해제합니다. |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | 이 메서드는 지정된 값으로 전체 양식을 채웁니다. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | 지정된 인덱스로 요소를 반환합니다. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | 지정된 이름으로 요소를 반환합니다. |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | 열거자를 가져옵니다. |

### 또한보십시오

* class [FormElement](../formelement/)
* 네임스페이스 [Aspose.Html.Forms](../../aspose.html.forms/)
* 집회 [Aspose.HTML](../../)


