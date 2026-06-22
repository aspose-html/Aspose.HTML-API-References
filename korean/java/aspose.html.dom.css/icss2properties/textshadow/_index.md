---
title: "ICSS2Properties.TextShadow"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICSS2Properties 속성. 이 속성은 요소의 텍스트에 적용될 그림자 효과들의 콤마 구분 목록을 허용합니다. 그림자 효과는 지정된 순서대로 적용되며 서로 겹칠 수 있지만 텍스트 자체를 가리지는 않습니다. 그림자 효과는 박스의 크기를 변경하지 않지만 경계를 넘어 확장될 수 있습니다. 그림자 효과의 스택 레벨은 요소 자체와 동일합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/textshadow/
---
## ICSS2Properties.TextShadow property

This property accepts a comma-separated list of shadow effects to be applied to the text of the element. The shadow effects are applied in the order specified and may thus overlay each other, but they will never overlay the text itself. Shadow effects do not alter the size of a box, but may extend beyond its boundaries. The [stack level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#stack-level) of the shadow effects is the same as for the element itself.

각 그림자 효과는 그림자 오프셋을 지정해야 하며 선택적으로 블러 반경 및 그림자 색상을 지정할 수 있습니다.

그림자 오프셋은 텍스트로부터의 거리를 나타내는 두 개의 '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' 값으로 지정됩니다. 첫 번째 길이 값은 텍스트 오른쪽의 수평 거리를 지정합니다. 음수 수평 길이 값은 그림자를 텍스트 왼쪽에 배치합니다. 두 번째 길이 값은 텍스트 아래의 수직 거리를 지정합니다. 음수 수직 길이 값은 그림자를 텍스트 위에 배치합니다.

블러 반경은 그림자 오프셋 뒤에 선택적으로 지정할 수 있습니다. 블러 반경은 블러 효과의 경계를 나타내는 길이 값입니다. 블러 효과를 계산하는 정확한 알고리즘은 명시되지 않았습니다.

색상 값은 그림자 효과의 길이 값 앞이나 뒤에 선택적으로 지정할 수 있습니다. 색상 값은 그림자 효과의 기반으로 사용됩니다. 색상이 지정되지 않으면 ['color'](https://www.w3.org/TR/1998/REC-CSS2-19980512/colors.html#propdef-color) 속성의 값이 대신 사용됩니다.

```java
public String TextShadow { get; set; }
```

### 반환 값

text-shadow 속성

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
