---
title: "ICSSStyleSheet.InsertRule"
second_title: "Java용 Aspose.HTML API 참조"
description: "ICSSStyleSheet 메서드. CSSStyleSheet.insertRule 메서드는 현재 스타일 시트에 새로운 CSS 규칙을 일부 제한과 함께 삽입합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

CSSStyleSheet.insertRule() 메서드는 현재 스타일시트에 새로운 CSS 규칙을 삽입하지만, 몇 가지 제한이 있습니다.

참고: insertRule()는 [`CSSStyleSheet`](../)의 전용 메서드이지만, 실제로는 규칙을 CSSStyleSheet.cssRules — 내부 [`CSSRuleList`](../../icssrulelist/)에 삽입합니다.

```java
public long InsertRule(String rule, int index)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 규칙 | String | 삽입될 규칙을 포함하는 문자열입니다. 삽입된 규칙이 무엇을 포함해야 하는지는 그 유형에 따라 달라집니다: |
| index | Int32 | 양의 정수이며 stylesheet.cssRules.length 이하로, 새로 삽입된 규칙이 CSSStyleSheet.cssRules에서 차지하는 위치를 나타냅니다. 기본값은 0입니다. |

### 반환 값

스타일시트의 규칙 목록 내에서 새로 삽입된 규칙의 인덱스입니다.

## 비고

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### 또 보기

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
