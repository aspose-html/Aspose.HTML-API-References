---
title: "ICSSStyleDeclaration.GetPropertyCSSValue"
second_title: "Aspose.HTML for Java API 참조"
description: "ICSSStyleDeclaration 메서드. 이 선언 블록 내에서 명시적으로 설정된 CSS 속성의 값에 대한 객체 표현을 가져오는 데 사용됩니다. 속성이 축약 속성인 경우 이 메서드는 null을 반환합니다. 축약 속성 값은 getPropertyValue 및 setProperty 메서드를 사용하여 문자열로만 접근하고 수정할 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

이 선언 블록 내에서 명시적으로 설정된 경우 CSS 속성 값의 객체 표현을 검색하는 데 사용됩니다. 속성이 축약형 속성인 경우 이 메서드는 null을 반환합니다. 축약형 속성 값은 getPropertyValue 및 setProperty 메서드를 사용하여 문자열로만 접근하고 수정할 수 있습니다.

```java
public CSSValue GetPropertyCSSValue(String propertyName)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propertyName | String | propertyName은 가져올 속성 이름을 나타내는 문자열입니다. |

### 반환 값

value는 속성에 대한 CSS 값을 포함하는 CSSValue입니다. 값이 없으면 null을 반환합니다.

### 또 보기

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
