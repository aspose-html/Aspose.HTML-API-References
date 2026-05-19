---
title: "ICSSRuleList 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.css.ICSSRuleList 인터페이스. CSSRuleList는 읽기 전용 CSSRule 객체들의 순서가 지정된 컬렉션을 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

CSSRuleList는 읽기 전용 [`CSSRule`](../icssrule/) 객체들의 순서가 지정된 컬렉션을 나타냅니다.

CSSRuleList 객체는 읽기 전용이며 직접 수정할 수 없지만, 내용이 시간이 지나면서 변경될 수 있기 때문에 라이브 객체로 간주됩니다.

[`CSSRule`](../icssrule/) 객체가 반환하는 기본 규칙을 편집하려면, [`CSSStyleSheet`](../icssstylesheet/)의 메서드인 CSSStyleSheet.insertRule() 및 CSSStyleSheet.deleteRule()를 사용하십시오.

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) item() 메서드(http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList)를 사용하여 CSS 규칙을 검색하는 데 사용됩니다. 이 컬렉션의 순서는 CSS 스타일 시트의 규칙 순서를 나타냅니다. 인덱스가 리스트의 규칙 수보다 크거나 같으면 null을 반환합니다. |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) `CSSRuleList` 인터페이스의 length 속성은 리스트에 있는 [`CSSRule`](../icssrule/) 객체의 수를 반환합니다. |

### 또 보기

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
