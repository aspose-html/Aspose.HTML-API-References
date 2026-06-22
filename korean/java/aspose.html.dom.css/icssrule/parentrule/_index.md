---
title: "ICSSRule.ParentRule"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICSSRule 속성. 이 규칙이 다른 규칙 안에 포함되어 있는 경우(예: 미디어 블록 안의 스타일 규칙) 이는 포함하는 규칙입니다. 이 규칙이 다른 규칙 안에 중첩되지 않은 경우 null을 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icssrule/parentrule/
---
## ICSSRule.ParentRule property

이 규칙이 다른 규칙 안에 포함되어 있는 경우(예: @media 블록 안의 스타일 규칙), 이는 포함하는 규칙입니다. 이 규칙이 다른 규칙 안에 중첩되지 않은 경우 null을 반환합니다.

```java
public ICSSRule ParentRule { get; }
```

### Property Value

포함 규칙들의 타입인 [`CSSRule`](../)입니다. 현재 규칙이 미디어 쿼리 안에 있는 경우 [`CSSMediaRule`](../../icssmediarule/)을 반환합니다. 그렇지 않으면 null을 반환합니다.

### 또 보기

* interface [ICSSRule](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
