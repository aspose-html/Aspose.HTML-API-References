---
title: "ICSSStyleDeclaration.RemoveProperty"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICSSStyleDeclaration 메서드. CSSStyleDeclaration.removeProperty 메서드 인터페이스는 CSS 스타일 선언 객체에서 속성을 제거합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icssstyledeclaration/removeproperty/
---
## ICSSStyleDeclaration.RemoveProperty method

CSSStyleDeclaration.removeProperty() 메서드 인터페이스는 CSS 스타일 선언 객체에서 속성을 제거합니다.

```java
public String RemoveProperty(String propertyName)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| propertyName | String | propertyName은 제거할 속성 이름을 나타내는 문자열입니다. 다중 단어 속성 이름은 하이픈으로 구분되며 카멜 표기법이 아니라는 점에 유의하세요. |

### 반환 값

oldValue는 속성이 제거되기 전 CSS 속성 값과 동일한 DOMString입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| DOMException | NO_MODIFICATION_ALLOWED_ERR: 속성이나 선언 블록이 읽기 전용인 경우. |

### 또 보기

* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
