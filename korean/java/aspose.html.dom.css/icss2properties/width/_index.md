---
title: "ICSS2Properties.Width"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICSS2Properties 속성. 이 속성은 블록 레벨 및 교체된 요소에 의해 생성된 박스의 내용 너비를 지정합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

이 속성은 블록 레벨 및 [replaced](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element) 요소에 의해 생성된 박스의 [content width](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width)를 지정합니다.

이 속성은 교체되지 않은 [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) 요소에는 적용되지 않습니다. 교체되지 않은 인라인 요소의 박스 너비는 그 안에 렌더링된 콘텐츠의 너비와 같습니다(자식의 상대적 오프셋 적용 전). 인라인 박스는 [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box) 로 흐른다는 것을 기억하십시오. 라인 박스의 너비는 그들의 [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) 에 의해 결정되지만, [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats) 가 존재하면 짧아질 수 있습니다.

교체된 요소의 박스 너비는 [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic)이며, 이 속성 값이 'auto'와 다를 경우 사용자 에이전트에 의해 스케일될 수 있습니다.

값은 다음과 같은 의미를 가집니다:

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - 고정 너비를 지정합니다.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - 백분율 너비를 지정합니다. 백분율은 생성된 박스의 [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) 너비를 기준으로 계산됩니다. auto - 너비는 다른 속성 값에 따라 결정됩니다. 아래 섹션을 참조하십시오. 참고: ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) 에 대한 음수 값은 허용되지 않습니다.

```java
public String Width { get; set; }
```

### 반환 값

width 속성

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
