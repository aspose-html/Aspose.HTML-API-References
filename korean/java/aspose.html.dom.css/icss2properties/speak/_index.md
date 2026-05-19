---
title: "ICSS2Properties.Speak"
second_title: "Aspose.HTML for Java API 참조"
description: "ICSS2Properties 속성. 이 속성은 텍스트가 청각적으로 렌더링되는지 여부와, 그렇다면 어떤 방식으로 렌더링되는지를 지정합니다(대략 display 속성과 유사합니다). 가능한 값은 다음과 같습니다"
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/speak/
---
## ICSS2Properties.Speak property

이 속성은 텍스트가 청각적으로 렌더링되는지 여부와, 그렇다면 어떤 방식으로 렌더링되는지를 지정합니다(대략 ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) 속성과 유사합니다). 가능한 값은 다음과 같습니다:

none - 요소가 렌더링되는 데 시간이 전혀 소요되지 않도록 청각 렌더링을 억제합니다. 단, 하위 요소가 이 값을 무시하고 읽힐 수 있습니다. (요소와 그 하위 요소의 렌더링을 확실히 억제하려면 ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) 속성을 사용하십시오).normal - 요소와 그 자식들을 렌더링할 때 언어에 따라 달라지는 발음 규칙을 사용합니다. spell-out - 텍스트를 한 글자씩 철자합니다(약어와 두문자어에 유용합니다).

```java
public String Speak { get; set; }
```

### 반환 값

speak 속성

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
