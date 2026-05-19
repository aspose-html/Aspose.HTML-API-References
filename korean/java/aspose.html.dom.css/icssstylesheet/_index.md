---
title: "ICSSStyleSheet 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.css.ICSSStyleSheet 인터페이스. CSSStyleSheet 인터페이스는 단일 CSS 스타일시트를 나타내며 스타일시트에 포함된 규칙 목록을 검사하고 수정할 수 있게 합니다. 부모인 IStyleSheet으로부터 속성과 메서드를 상속합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

CSSStyleSheet 인터페이스는 단일 CSS 스타일시트를 나타내며, 스타일시트에 포함된 규칙 목록을 검사하고 수정할 수 있게 합니다. 부모인 [`IStyleSheet`](../istylesheet/)로부터 속성과 메서드를 상속합니다.

스타일시트는 스타일시트의 각 규칙을 나타내는 [`ICSSRule`](../icssrule/) 객체들의 컬렉션으로 구성됩니다. 규칙들은 [`ICSSRuleList`](../icssrulelist/)에 포함되어 있으며, 이는 스타일시트의 cssRules 속성을 통해 얻을 수 있습니다.

예를 들어, 하나의 규칙은 다음과 같은 스타일을 포함하는 [`ICSSStyleRule`](../icssstylerule/) 객체일 수 있습니다.

```java
h1, h2 {   font-size: 16pt; }
```

다른 규칙은 @import 또는 @media와 같은 at-rule일 수 있으며, 그 외에도 다양합니다.

```java
public interface ICSSStyleSheet : IStyleSheet
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) 읽기 전용 CSSStyleSheet 속성인 cssRules는 실시간으로 스타일시트를 구성하는 모든 CSS 규칙의 최신 목록을 제공하는 살아있는 [`CSSRuleList`](../icssrulelist/)를 반환합니다. 목록의 각 항목은 단일 규칙을 정의하는 [`CSSRule`](../icssrule/)입니다. |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) 읽기 전용 CSSStyleSheet 속성인 ownerRule은 스타일시트를 문서에 가져온 @import at-rule에 해당하는 [`CSSImportRule`](../icssimportrule/)을 반환합니다. 스타일시트가 @import를 사용해 문서에 가져오지 않았다면 반환값은 null입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | `CSSStyleSheet` 메서드 deleteRule()는 스타일시트 객체에서 규칙을 제거합니다. |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | CSSStyleSheet.insertRule() 메서드는 현재 스타일시트에 새로운 CSS 규칙을 삽입하지만, 몇 가지 제한이 있습니다. |

## 비고

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### 또 보기

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
