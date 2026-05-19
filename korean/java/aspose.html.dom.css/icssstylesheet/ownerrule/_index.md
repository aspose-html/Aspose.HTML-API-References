---
title: "ICSSStyleSheet.OwnerRule"
second_title: "Aspose.HTML for Java API 참조"
description: "ICSSStyleSheet 속성. 읽기 전용 CSSStyleSheet 속성 ownerRule은 스타일시트를 문서에 가져온 import at-rule에 해당하는 CSSImportRule을 반환합니다. 스타일시트가 import를 사용해 문서에 가져오지 않은 경우 반환값은 null입니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/icssstylesheet/ownerrule/
---
## ICSSStyleSheet.OwnerRule property

읽기 전용 CSSStyleSheet 속성 ownerRule은 스타일시트를 문서에 가져온 @import at-rule에 해당하는 [`CSSImportRule`](../../icssimportrule/)을 반환합니다. 스타일시트가 @import를 사용해 문서에 가져오지 않은 경우 반환값은 null입니다.

```java
public ICSSRule OwnerRule { get; }
```

### Property Value

@import 규칙에 해당하는 CSSImportRule이며, 이 규칙은 스타일시트를 문서에 가져왔습니다. 스타일시트가 @import를 사용해 문서에 가져오지 않은 경우 반환값은 null입니다.

## 비고

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-ownerrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-ownerrule) – The CSSOM definition.

### 또 보기

* interface [ICSSRule](../../icssrule/)
* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
