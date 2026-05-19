---
title: "ICSS2Properties.Display"
second_title: "Aspose.HTML for Java API 참조"
description: "ICSS2Properties 속성. 이 속성의 값은 다음과 같은 의미를 가집니다"
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

이 속성의 값은 다음과 같은 의미를 가집니다:

block - 이 값은 요소가 기본 블록 박스를 생성하도록 합니다. inline - 이 값은 요소가 하나 이상의 인라인 박스를 생성하도록 합니다. list-item - 이 값은 요소(예: HTML의 LI)가 기본 블록 박스와 리스트 아이템 인라인 박스를 생성하도록 합니다. 리스트와 리스트 포맷팅 예제에 대한 정보는 [lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists) 섹션을 참고하십시오. marker - 이 값은 박스 앞이나 뒤에 [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html)을 마커로 선언합니다. 이 값은 블록 레벨 요소에 붙은 [:before 및 :after 의사 요소](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content)와 함께 사용할 때만 사용해야 합니다. 다른 경우에는 이 값을 'inline'으로 해석합니다. 자세한 내용은 [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) 섹션을 참고하십시오. none - 이 값은 요소가 [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure)에 박스를 전혀 생성하지 않게 합니다(즉, 레이아웃에 영향을 주지 않음). 하위 요소도 박스를 생성하지 않으며, 이 동작은 하위 요소에 ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) 속성을 설정해도 무시할 수 없습니다. 'none' 디스플레이는 보이지 않는 박스를 만들지 않으며, 박스 자체가 전혀 생성되지 않음을 유의하십시오. CSS에는 포맷팅에 영향을 주지만 자체적으로는 보이지 않는 박스를 생성하도록 하는 메커니즘이 포함되어 있습니다. 자세한 내용은 [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) 섹션을 참고하십시오. run-in 및 compact - 이 값들은 상황에 따라 블록 박스 또는 인라인 박스를 생성합니다. 속성은 최종 상태(인라인 레벨 또는 블록 레벨)에 따라 run-in 및 compact 박스에 적용됩니다. 예를 들어, ['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space) 속성은 박스가 블록 박스로 변할 때만 적용됩니다. table, inline-table, table-row-group, [table-column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column), table-column-group, table-header-group, table-footer-group, table-row, table-cell, 그리고 table-caption - 이 값들은 요소가 테이블 요소처럼 동작하도록 합니다( [tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html) 장에 설명된 제한 사항을 따름).

```java
public String Display { get; set; }
```

### 반환 값

display 속성

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
