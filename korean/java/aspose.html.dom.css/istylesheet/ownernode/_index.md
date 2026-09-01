---
title: "IStyleSheet.OwnerNode"
second_title: "Java용 Aspose.HTML API 참조"
description: "IStyleSheet 속성. 이 노드는 스타일 시트를 문서와 연결합니다. HTML의 경우 해당 LINK 또는 STYLE 요소가 될 수 있습니다. XML의 경우 연결 처리 지시문이 될 수 있습니다. 다른 스타일 시트에 포함된 스타일 시트의 경우 이 속성의 값은 null입니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/istylesheet/ownernode/
---
## IStyleSheet.OwnerNode property

스타일 시트를 문서와 연결하는 노드입니다. HTML의 경우 해당 LINK 또는 STYLE 요소가 될 수 있습니다. XML의 경우 연결 처리 지시문이 될 수 있습니다. 다른 스타일 시트에 포함된 스타일 시트의 경우 이 속성의 값은 null입니다.

```java
public Node OwnerNode { get; }
```

### Property Value

ownerNode 속성은 소유자 노드를 반환해야 합니다.

## 비고

다른 스타일 시트에 포함된 스타일 시트(예: @import)의 경우, 이 속성의 값은 null입니다.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-ownernode](https://drafts.csswg.org/cssom/#dom-stylesheet-ownernode) – The CSSOM definition.

### 또 보기

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
