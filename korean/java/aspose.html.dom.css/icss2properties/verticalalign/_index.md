---
title: "ICSS2Properties.VerticalAlign"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICSS2Properties 속성. 이 속성은 인라인 레벨 요소에 의해 생성된 박스들의 라인 박스 내부에서의 수직 위치에 영향을 줍니다. 다음 값들은 부모 인라인 레벨 요소와의 관계에서만 의미가 있거나, 해당 요소가 익명 인라인 박스를 생성하는 경우 부모 블록 레벨 요소와의 관계에서만 의미가 있습니다. 해당 부모가 존재하지 않으면 효과가 없습니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/verticalalign/
---
## ICSS2Properties.VerticalAlign property

이 속성은 인라인 레벨 요소에 의해 생성된 박스들의 라인 박스 내부에서의 수직 위치에 영향을 줍니다. 다음 값들은 부모 인라인 레벨 요소와의 관계에서만 의미가 있거나, 해당 요소가 [anonymous inline boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous) 를 생성하는 경우 부모 블록 레벨 요소와의 관계에서만 의미가 있습니다; 해당 부모가 존재하지 않으면 효과가 없습니다.

Note. 이 속성의 값은 표(context)에서 약간 다른 의미를 가집니다. 자세한 내용은 [table height algorithms](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#height-layout) 섹션을 참고하십시오. baseline - 박스의 기준선을 부모 박스의 기준선에 맞춥니다. 박스에 기준선이 없으면 박스의 아래쪽을 부모의 기준선에 맞춥니다. middle - 박스의 수직 중간점을 부모 박스의 기준선에 부모의 x-높이 절반을 더한 위치에 맞춥니다. sub - 박스의 기준선을 부모 박스의 아래첨자에 맞는 적절한 위치로 낮춥니다. (이 값은 요소 텍스트의 글꼴 크기에 영향을 주지 않습니다.) super - 박스의 기준선을 부모 박스의 위첨자에 맞는 적절한 위치로 올립니다. (이 값은 요소 텍스트의 글꼴 크기에 영향을 주지 않습니다.) text-top - 박스의 위쪽을 부모 요소 글꼴의 위쪽에 맞춥니다. text-bottom - 박스의 아래쪽을 부모 요소 글꼴의 아래쪽에 맞춥니다. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - 이 거리를 양수이면 올리고(양수 값), 음수이면 내립니다(음수 값) (거리의 단위는 ['line-height'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-line-height) 값의 백분율). 값 '0%'는 'baseline'과 동일합니다. '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - 이 거리를 양수이면 올리고, 음수이면 내립니다. 값 '0cm'은 'baseline'과 동일합니다. top - 박스의 위쪽을 라인 박스의 위쪽에 맞춥니다. bottom - 박스의 아래쪽을 라인 박스의 아래쪽에 맞춥니다.

```java
public String VerticalAlign { get; set; }
```

### 반환 값

vertical-align 속성

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
