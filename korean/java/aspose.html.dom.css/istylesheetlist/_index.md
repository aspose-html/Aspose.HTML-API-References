---
title: "IStyleSheetList 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.css.IStyleSheetList 인터페이스. StyleSheetList 인터페이스는 CSSStyleSheet 객체들의 목록을 나타냅니다. 이 객체의 인스턴스는 Document.styleSheets를 통해 반환될 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

StyleSheetList 인터페이스는 [`CSSStyleSheet`](../icssstylesheet/) 객체들의 목록을 나타냅니다. 이 객체의 인스턴스는 [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/)를 통해 반환될 수 있습니다.

객체가 지원하는 속성 인덱스는 컬렉션이 나타내는 CSS 스타일 시트 수보다 하나 적은 0부터 시작하는 숫자 범위입니다. 해당 CSS 스타일 시트가 없으면 지원되는 속성 인덱스도 없습니다.

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) item(index) 메서드는 컬렉션에서 지정된 인덱스에 해당하는 [`CSS style sheet`](../icssstylesheet/)을 반환해야 합니다. 컬렉션에 해당 인덱스의 객체가 없으면 메서드는 null을 반환해야 합니다. |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) length 속성은 컬렉션이 나타내는 CSS 스타일 시트의 개수를 반환해야 합니다. 유효한 자식 스타일시트 인덱스 범위는 0부터 length‑1까지 포함됩니다. |

## 비고

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### 또 보기

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
