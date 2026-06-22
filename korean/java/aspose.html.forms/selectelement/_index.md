---
title: "SelectElement 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.forms.SelectElement 클래스. SelectElement는 HTMLSelectElement와 연결된 래퍼를 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.forms/selectelement/
---
## SelectElement class

SelectElement는 HTMLSelectElement와 연결된 래퍼를 나타냅니다.

```java
public class SelectElement : FormElement<HTMLSelectElement>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) 요소의 유형을 가져옵니다. |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/selectelement/id/) { get; set; } | 입력 요소의 Id 속성을 나타냅니다. |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
| [name](../../com.aspose.html.forms/selectelement/name/) { get; set; } | 입력 요소의 name 속성을 나타냅니다. |
| [getOptions](../../com.aspose.html.forms/selectelement/options/) 옵션 목록을 반환합니다. |
| [getSelectedOptions](../../com.aspose.html.forms/selectelement/selectedoptions/) 선택된 옵션 목록을 반환합니다. |
| [getType](../../com.aspose.html.forms/selectelement/type/) 이 폼 컨트롤의 유형입니다. multiple 속성이 `true`일 때는 문자열 "select-multiple"이며, `false`일 때는 문자열 "select-one"입니다. |
| [value](../../com.aspose.html.forms/selectelement/value/) { get; set; } | 읽을 때, 옵션 목록에서 트리 순서대로 첫 번째로 selectedness가 true로 설정된 옵션 요소의 값을 반환해야 합니다(존재하는 경우). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | 이 메서드는 인덱스를 사용하여 여러 옵션을 선택할 수 있게 합니다. |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems_1)(params String[]) | 이 메서드는 값을 사용하여 여러 옵션을 선택할 수 있게 합니다. |

### 또 보기

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../com.aspose.html/htmlselectelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
