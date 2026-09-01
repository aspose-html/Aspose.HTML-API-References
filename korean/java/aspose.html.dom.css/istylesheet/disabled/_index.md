---
title: "IStyleSheet.Disabled"
second_title: "Java용 Aspose.HTML API 참조"
description: "IStyleSheet 속성. StyleSheet 인터페이스의 disabled 속성은 스타일 시트가 문서에 적용되는 것을 방지하는지 여부를 결정합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

[`StyleSheet`](../) 인터페이스의 disabled 속성은 스타일 시트가 문서에 적용되는 것을 방지하는지 여부를 결정합니다.

스타일 시트는 이 속성을 true로 수동 설정하거나 비활성 대체 스타일 시트인 경우 비활성화될 수 있습니다. disabled == false라고 해서 스타일 시트가 적용된다는 보장은 없습니다(예를 들어 문서에서 제거될 수 있습니다).

이 속성을 수정하면 문서에 대한 스타일 해석이 새로 이루어질 수 있습니다. 스타일 시트는 적절한 매체 정의가 존재하고 disabled 속성이 false인 경우에만 적용됩니다. 따라서 매체가 현재 사용자 에이전트에 적용되지 않으면 disabled 속성은 무시됩니다.

```java
public bool Disabled { get; set; }
```

### 반환 값

disabled 속성은 읽을 때 disabled 플래그가 설정되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환해야 합니다. 설정할 때, disabled 속성은 새 값이 true이면 disabled 플래그를 설정하고, 그렇지 않으면 disabled 플래그를 해제해야 합니다.

### Property Value

disabled 속성은 읽을 때 disabled 플래그가 설정되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환해야 합니다. 설정할 때, disabled 속성은 새 값이 true이면 disabled 플래그를 설정하고, 그렇지 않으면 disabled 플래그를 해제해야 합니다.

## 비고

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### 또 보기

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
