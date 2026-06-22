---
title: "ICSSStyleDeclaration 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.css.ICSSStyleDeclaration 인터페이스. CSSStyleDeclaration 인터페이스는 CSS 선언 블록 객체를 나타내며 스타일 정보와 다양한 스타일 관련 메서드 및 속성을 노출합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration 인터페이스는 CSS 선언 블록인 객체를 나타내며, 스타일 정보와 다양한 스타일 관련 메서드 및 속성을 노출합니다.

CSSStyleDeclaration 객체는 세 가지 다른 API를 사용하여 노출될 수 있습니다:

단일 요소의 인라인 스타일을 처리하는 HTMLElement.style를 통해. [`CSSStyleSheet`](../icssstylesheet/) API를 통해. 예를 들어, document.styleSheets[0].cssRules[0].style은 문서 첫 번째 스타일시트의 첫 번째 CSS 규칙에 대한 `CSSStyleDeclaration` 객체를 반환합니다. Window.getComputedStyle()를 통해, `CSSStyleDeclaration` 객체를 읽기 전용 인터페이스로 노출합니다.

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## 속성

| 이름 | 설명 |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) 이 메서드는 선언 블록에서 명시적으로 설정된 속성을 검색하는 데 사용됩니다. 이 메서드로 검색된 속성들의 순서는 설정된 순서와 일치할 필요가 없습니다. 이 메서드는 선언 블록의 모든 속성을 반복하는 데 사용할 수 있습니다. |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) 읽기 전용 속성은 이 CSS 선언 블록에서 명시적으로 설정된 속성의 개수를 정수로 반환합니다. 유효한 인덱스 범위는 0부터 length-1까지 포함됩니다. |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) CSSStyleDeclaration.parentRule 읽기 전용 속성은 이 스타일 블록의 상위인 CSSRule을 반환합니다. 예를 들어, CSS 선택자에 대한 스타일을 나타내는 [`CSSStyleRule`](../icssstylerule/)이 될 수 있습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | 이 메서드는 선언 블록 내에서 명시적으로 설정된 CSS 속성의 값에 대한 객체 표현을 검색하는 데 사용됩니다. 속성이 축약형 속성인 경우 이 메서드는 null을 반환합니다. 축약형 속성 값은 문자열로만 접근 및 수정할 수 있으며, getPropertyValue와 setProperty 메서드를 사용합니다. |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | 이 메서드는 선언 블록에서 명시적으로 설정된 CSS 속성의 우선순위(예: "important" 한정자)를 검색하는 데 사용됩니다. |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | CSSStyleDeclaration.getPropertyValue() 메서드 인터페이스는 지정된 CSS 속성의 값을 포함하는 문자열을 반환합니다. |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | CSSStyleDeclaration.removeProperty() 메서드 인터페이스는 CSS 스타일 선언 객체에서 속성을 제거합니다. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | CSSStyleDeclaration.setProperty() 메서드 인터페이스는 이 선언 블록 내에서 기본 우선순위로 속성 값을 설정하는 데 사용됩니다. 기본 우선순위는 "important"가 아니며, 즉 String.Empty입니다. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | CSSStyleDeclaration.setProperty() 메서드 인터페이스는 이 선언 블록 내에서 기본 우선순위로 속성 값을 설정하는 데 사용됩니다. 기본 우선순위는 "important"가 아니며, 즉 String.Empty입니다. |

## 비고

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### 또 보기

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
