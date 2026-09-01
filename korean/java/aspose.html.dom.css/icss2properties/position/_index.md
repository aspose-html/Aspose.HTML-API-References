---
title: "ICSS2Properties.Position"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICSS2Properties 속성. 이 속성의 값은 다음과 같은 의미를 가집니다"
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/position/
---
## ICSS2Properties.Position property

이 속성의 값은 다음과 같은 의미를 가집니다:

static - 박스는 일반 박스로, [normal flow](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow)에 따라 배치됩니다. ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left)와 ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top) 속성은 적용되지 않습니다. relative - 박스의 위치는 [normal flow](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow)(이를 정상 흐름 내 위치라고 합니다)에 따라 계산됩니다. 그런 다음 박스는 [relative](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#relative-positioning)으로 정상 위치에서 오프셋됩니다. 박스 B가 상대적으로 배치되면, 뒤따르는 박스의 위치는 B가 오프셋되지 않은 것처럼 계산됩니다. absolute - 박스의 위치(및 경우에 따라 크기)는 ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left), ['right'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-right), ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top), ['bottom'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-bottom) 속성으로 지정됩니다. 이 속성들은 박스의 [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block)을 기준으로 오프셋을 정의합니다. 절대 위치 지정된 박스는 정상 흐름에서 제외됩니다. 즉, 이후 형제 요소들의 레이아웃에 영향을 주지 않습니다. 또한 [absolutely positioned](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#absolutely-positioned) 박스는 여백을 가질 수 있지만, 다른 여백과 [collapse](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#collapsing-margins)되지 않습니다. fixed - 박스의 위치는 'absolute' 모델에 따라 계산되지만, 추가로 박스는 [fixed](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#fixed-positioning)되어 특정 기준에 고정됩니다. [continuous media](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#continuous-media-group)인 경우, 박스는 [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport)(스크롤해도 움직이지 않음)에 상대적으로 고정됩니다. [paged media](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#paged-media-group)인 경우, 박스는 페이지에 고정되며, 해당 페이지가 [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport)를 통해 표시되더라도 고정됩니다(예: 인쇄 미리보기). 작성자는 미디어에 따라 'fixed'를 지정하고 싶을 수 있습니다.

```java
public String Position { get; set; }
```

### 반환 값

position 속성

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
