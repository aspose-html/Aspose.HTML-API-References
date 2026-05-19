---
title: "IStyleSheet.ParentStyleSheet"
second_title: "Aspose.HTML for Java API 참조"
description: "IStyleSheet property. 스타일 시트 포함 개념을 지원하는 스타일 시트 언어의 경우, 이 속성은 포함하는 스타일 시트가 존재하면 이를 나타냅니다. 스타일 시트가 최상위 스타일 시트이거나 스타일 시트 언어가 포함을 지원하지 않으면 이 속성의 값은 null입니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

스타일 시트 포함 개념을 지원하는 스타일 시트 언어의 경우, 이 속성은 포함하는 스타일 시트가 존재하면 이를 나타냅니다. 스타일 시트가 최상위 스타일 시트이거나 스타일 시트 언어가 포함을 지원하지 않으면 이 속성의 값은 null입니다.

```java
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

parentStyleSheet 속성은 부모 [`CSS style sheet`](../../icssstylesheet/)를 반환해야 합니다.

## 비고

현재 스타일시트가 최상위 스타일시트이거나 스타일시트 포함이 지원되지 않는 경우 이 속성은 null을 반환합니다.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### 또 보기

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
