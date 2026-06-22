---
title: "ICSS2Properties.WhiteSpace"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICSS2Properties 속성. 이 속성은 요소 내부의 공백이 어떻게 처리되는지를 선언합니다. 값은 다음과 같은 의미를 가집니다"
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/whitespace/
---
## ICSS2Properties.WhiteSpace property

이 속성은 요소 내부의 [whitespace](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#whitespace) 가 어떻게 처리되는지를 선언합니다. 값은 다음과 같은 의미를 가집니다:

normal - 이 값은 사용자 에이전트가 공백 시퀀스를 축소하고, 라인 박스를 채우기 위해 필요에 따라 줄을 나누도록 지시합니다. 추가 줄 바꿈은 생성된 콘텐츠에서 "\A" 가 나타날 때 생성될 수 있습니다 (예: HTML의 BR 요소).pre - 이 값은 사용자 에이전트가 공백 시퀀스를 축소하는 것을 방지합니다. 줄은 소스의 새줄 문자에서만, 또는 생성된 콘텐츠에서 "\A" 가 나타날 때만 나뉩니다.nowrap - 이 값은 'normal'과 같이 공백을 축소하지만, 텍스트 내에서 "\A" 로 생성된 경우를 제외하고 줄 바꿈을 억제합니다 (예: HTML의 BR 요소).

```java
public String WhiteSpace { get; set; }
```

### 반환 값

white-space 속성

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
