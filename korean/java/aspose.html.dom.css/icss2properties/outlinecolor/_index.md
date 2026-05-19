---
title: "이 속성의 값은 다음과 같은 의미를 가집니다:"
second_title: "Aspose.HTML for Java API 참조"
description: "ICSS2Properties 속성. outline 속성으로 만든 외곽선은 박스 위에 그려지며, 즉 외곽선은 항상 최상위에 표시되고 박스나 다른 박스의 위치나 크기에 영향을 주지 않습니다. 따라서 외곽선을 표시하거나 숨겨도 레이아웃 재계산이 발생하지 않습니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/outlinecolor/
---
## ICSS2Properties.OutlineColor property

outline 속성으로 만든 외곽선은 박스 "위에" 그려지며, 즉 외곽선은 항상 최상위에 표시되고 박스나 다른 박스의 위치나 크기에 영향을 주지 않습니다. 따라서 외곽선을 표시하거나 숨겨도 레이아웃 재계산이 발생하지 않습니다.

```java
public String OutlineColor { get; set; }
```

### 반환 값

normal - 요소는 양방향 알고리즘에 대해 추가적인 임베딩 레벨을 열지 않습니다. 인라인 레벨 요소의 경우, 암시적 재배열이 요소 경계 전체에서 작동합니다. embed - 요소가 인라인 레벨이면, 이 값은 양방향 알고리즘에 대해 추가적인 임베딩 레벨을 엽니다. 이 임베딩 레벨의 방향은 ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) 속성에 의해 지정됩니다. 요소 내부에서는 재배열이 암시적으로 수행됩니다. 이는 요소 시작에 LRE (U+202A; 'direction: ltr'용) 또는 RLE (U+202B; 'direction: rtl'용)를 추가하고, 요소 끝에 PDF (U+202C)를 추가하는 것과 같습니다. bidi-override - 요소가 인라인 레벨이거나 인라인 레벨 요소만 포함하는 블록 레벨 요소인 경우, 이것은 오버라이드를 생성합니다. 이는 요소 내부에서 재배열이 ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) 속성에 따라 순서대로 엄격히 이루어지며, 양방향 알고리즘의 암시적 부분이 무시된다는 의미입니다. 이는 요소 시작에 LRO (U+202D; 'direction: ltr'용) 또는 RLO (U+202E; 'direction: rtl'용)를 추가하고, 요소 끝에 PDF (U+202C)를 추가하는 것과 같습니다.

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
