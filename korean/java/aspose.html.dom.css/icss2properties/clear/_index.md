---
title: "ICSS2Properties.Clear"
second_title: "Aspose.HTML for Java API 참조"
description: "ICSS2Properties 속성. 이 속성은 요소의 박스 중 어느 면이 이전에 떠 있는 박스와 인접할 수 없는지를 나타냅니다. 요소 자체에 떠 있는 자식 요소가 있을 경우 clear 속성은 그들에 영향을 주지 않을 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/clear/
---
## ICSS2Properties.Clear property

이 속성은 요소의 박스(들)의 어느 면이 이전에 떠 있는 박스와 인접할 수 없는지를 나타냅니다. (요소 자체에 떠 있는 자식 요소가 있을 경우, 'clear' 속성은 그들에 영향을 주지 않습니다.)

이 속성은 블록 레벨 요소(플로트 포함)에만 지정할 수 있습니다. 컴팩트 및 런인 박스의 경우, 이 속성은 해당 컴팩트 또는 런인 박스가 속한 최종 블록 박스에 적용됩니다.

값은 비플로팅 블록 박스에 적용될 때 다음과 같은 의미를 가집니다:

left - 생성된 박스의 상단 여백이 충분히 증가되어, 상단 테두리 가장자리가 소스 문서에서 앞선 요소들에 의해 생성된 왼쪽 플로팅 박스들의 하단 외부 가장자리 아래에 위치합니다.right - 생성된 박스의 상단 여백이 충분히 증가되어, 상단 테두리 가장자리가 소스 문서에서 앞선 요소들에 의해 생성된 오른쪽 플로팅 박스들의 하단 외부 가장자리 아래에 위치합니다.both - 생성된 박스가 소스 문서에서 앞선 요소들의 모든 플로팅 박스 아래로 이동합니다..none - 플로팅에 대한 박스 위치에 제한이 없습니다.

```java
public String Clear { get; set; }
```

### 반환 값

clear 속성

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
