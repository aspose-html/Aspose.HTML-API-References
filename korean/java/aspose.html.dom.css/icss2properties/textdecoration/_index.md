---
title: "ICSS2Properties.TextDecoration"
second_title: "Aspose.HTML for Java API 참조"
description: "ICSS2Properties 속성. 이 속성은 요소의 텍스트에 추가되는 장식을 설명합니다. 블록 레벨 요소에 지정된 경우 해당 요소의 모든 인라인 레벨 하위 요소에 영향을 미칩니다. 인라인 레벨 요소에 지정되거나 영향을 미치는 경우 해당 요소가 생성한 모든 박스에 영향을 줍니다. 요소에 내용이나 텍스트 내용이 없을 경우(예: HTML의 IMG 요소) 사용자 에이전트는 이 속성을 무시해야 합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/textdecoration/
---
## ICSS2Properties.TextDecoration property

이 속성은 요소의 텍스트에 추가되는 장식을 설명합니다. 속성이 [block-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#block-level) 요소에 지정된 경우 해당 요소의 모든 인라인 레벨 하위 요소에 영향을 미칩니다. 속성이 (또는 영향을 미치는) [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) 요소에 지정된 경우 해당 요소가 생성한 모든 박스에 영향을 줍니다. 요소에 내용이나 텍스트 내용이 없을 경우(예: HTML의 IMG 요소), 사용자 에이전트는 이 속성을 [ignore](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#ignore) 해야 합니다.

값은 다음과 같은 의미를 가집니다:

none - 텍스트 장식을 생성하지 않음. underline - 각 텍스트 줄에 밑줄이 표시됨. overline - 각 텍스트 줄 위에 선이 표시됨. line-through - 각 텍스트 줄에 가운데 선이 표시됨. blink - 텍스트가 깜박임(보이기와 숨기기를 번갈아 가며).

```java
public String TextDecoration { get; set; }
```

### 반환 값

text-decoration 속성

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
