---
title: "ICSSRule 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.css.ICSSRule 인터페이스. CSSRule 인터페이스는 모든 유형의 CSS 구문에 대한 추상 기본 인터페이스입니다. 여기에는 규칙 집합과 at-rule이 모두 포함됩니다. 구현은 파서가 인식하지 못하는 규칙이라도 CSS 스타일 시트에 지정된 모든 규칙을 보존해야 합니다. 인식되지 않은 규칙은 이 인터페이스를 사용해 표현됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

CSSRule 인터페이스는 모든 유형의 CSS 구문에 대한 추상 기본 인터페이스입니다. 여기에는 규칙 집합과 at-rule이 모두 포함됩니다. 구현은 파서가 인식하지 못하더라도 CSS 스타일시트에 지정된 모든 규칙을 보존해야 합니다. 인식되지 않은 규칙은 이 인터페이스를 사용하여 표현됩니다.

```java
public interface ICSSRule
```

## 속성

| 이름 | 설명 |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) 이 규칙이 다른 규칙 내부에 포함되어 있으면(예: @media 블록 내부의 스타일 규칙) 해당 포함 규칙을 반환합니다. 이 규칙이 다른 규칙에 중첩되지 않은 경우 null을 반환합니다. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) `CSSRule` 인터페이스의 parentStyleSheet 속성은 현재 규칙이 정의된 [`StyleSheet`](../istylesheet/) 객체를 반환합니다. |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) 규칙의 유형은 [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type) 에 정의되어 있습니다. 기대되는 바는 바인딩별 캐스팅 메서드를 사용해 CSSRule 인터페이스 인스턴스를 해당 유형이 암시하는 특정 파생 인터페이스로 다운캐스팅할 수 있다는 것입니다. |

### 또 보기

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
