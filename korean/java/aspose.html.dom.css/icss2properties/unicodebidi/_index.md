---
title: "ICSS2Properties.UnicodeBidi"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICSS2Properties 속성. 이 속성의 값은 다음과 같은 의미를 가집니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

이 속성의 값은 다음과 같은 의미를 가집니다:

normal - 요소가 양방향 알고리즘에 대해 추가적인 임베딩 레벨을 열지 않습니다. 인라인 레벨 요소의 경우, 암시적 재배열이 요소 경계를 넘어 작동합니다. embed - 요소가 인라인 레벨이면, 이 값은 양방향 알고리즘에 대해 추가적인 임베딩 레벨을 엽니다. 이 임베딩 레벨의 방향은 ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) 속성으로 지정됩니다. 요소 내부에서는 재배열이 암시적으로 수행됩니다. 이는 요소 시작에 LRE (U+202A; 'direction: ltr'인 경우) 또는 RLE (U+202B; 'direction: rtl'인 경우)를 추가하고, 끝에 PDF (U+202C)를 추가하는 것과 같습니다. bidi-override - 요소가 인라인 레벨이거나 인라인 레벨 요소만 포함하는 블록 레벨 요소인 경우, 이것은 오버라이드를 생성합니다. 이는 요소 내부에서 재배열이 ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction) 속성에 따라 순서대로 엄격히 이루어지며, 양방향 알고리즘의 암시적 부분이 무시됨을 의미합니다. 이는 요소 시작에 LRO (U+202D; 'direction: ltr'인 경우) 또는 RLO (U+202E; 'direction: rtl'인 경우)를 추가하고, 끝에 PDF (U+202C)를 추가하는 것과 같습니다.

```java
public String UnicodeBidi { get; set; }
```

### 반환 값

unicode-bidi 속성

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
