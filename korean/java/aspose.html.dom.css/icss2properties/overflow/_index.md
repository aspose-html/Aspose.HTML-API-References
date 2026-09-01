---
title: "ICSS2Properties.Overflow"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICSS2Properties 속성. 이 속성은 블록 레벨 요소의 콘텐츠가 해당 요소의 박스를 초과하여 내용이 포함 블록으로 작용하는 경우 클립되는지를 지정합니다. 값은 다음과 같은 의미를 가집니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icss2properties/overflow/
---
## ICSS2Properties.Overflow property

이 속성은 블록 레벨 요소의 콘텐츠가 요소의 박스(내용을 포함하는 블록 역할을 함)를 초과할 때 클립되는지를 지정합니다. 값은 다음과 같은 의미를 가집니다:

visible - 이 값은 콘텐츠가 클립되지 않음을 나타내며, 즉 블록 박스 밖으로 렌더링될 수 있음을 의미합니다. hidden - 이 값은 콘텐츠가 클립되고 클립 영역 밖의 콘텐츠를 보기 위한 스크롤 메커니즘이 제공되지 않음을 나타냅니다; 사용자는 클립된 콘텐츠에 접근할 수 없습니다. 클립 영역의 크기와 형태는 ['clip'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#propdef-clip) 속성으로 지정됩니다. scroll - 이 값은 콘텐츠가 클립되지만 사용자 에이전트가 화면에 보이는 스크롤 메커니즘(스크롤 바나 패너 등)을 사용하는 경우, 해당 메커니즘이 박스에 대해 콘텐츠가 클립되었는지 여부와 관계없이 표시되어야 함을 나타냅니다. 이는 동적 환경에서 스크롤 바가 나타났다 사라지는 문제를 방지합니다. 이 값이 지정되고 대상 매체가 'print' 또는 'projection'인 경우, 초과된 콘텐츠는 인쇄되어야 합니다. auto - 'auto' 값의 동작은 사용자 에이전트에 따라 다르지만, 초과된 박스에 스크롤 메커니즘이 제공되어야 합니다.

```java
public String Overflow { get; set; }
```

### 반환 값

overflow 속성

### 또 보기

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
