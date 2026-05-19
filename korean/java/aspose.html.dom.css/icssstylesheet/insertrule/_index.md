---
title: "ICSSStyleSheet.InsertRule"
second_title: "Aspose.HTML for Java API 참조"
description: "ICSSStyleSheet 메서드. CSSStyleSheet.insertRule 메서드는 현재 스타일 시트에 새로운 CSS 규칙을 일부 제한 사항과 함께 삽입합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

CSSStyleSheet.insertRule() 메서드는 현재 스타일시트에 새로운 CSS 규칙을 삽입하지만, 몇 가지 제한이 있습니다.

참고: insertRule()는 [`CSSStyleSheet`](../)의 전용 메서드이지만, 실제로는 CSSStyleSheet.cssRules — 내부 [`CSSRuleList`](../../icssrulelist/)에 규칙을 삽입합니다.

```java
public long InsertRule(String rule, int index)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 규칙 | String | 삽입될 규칙을 포함하는 문자열입니다. 삽입된 규칙이 포함해야 하는 내용은 유형에 따라 다릅니다: |
| index | Int32 | stylesheet.cssRules.length보다 작거나 같은 양의 정수로, CSSStyleSheet.cssRules에서 새로 삽입된 규칙의 위치를 나타냅니다. 기본값은 0입니다. |

### 반환 값

새로 삽입된 규칙이 스타일시트의 규칙 목록 내에서 차지하는 인덱스입니다.

## 비고

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### 또 보기

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
