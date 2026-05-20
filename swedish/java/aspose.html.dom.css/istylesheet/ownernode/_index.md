---
title: "IStyleSheet.OwnerNode"
second_title: "Aspose.HTML för Java API-referens"
description: "IStyleSheet‑egenskap. Noden som associerar detta stilark med dokumentet. För HTML kan detta vara motsvarande LINK‑ eller STYLE‑element. För XML kan det vara den länkande processinstruktionen. För stilark som inkluderas av andra stilark är värdet för detta attribut null."
type: docs

url: /sv/java/com.aspose.html.dom.css/istylesheet/ownernode/
---
## IStyleSheet.OwnerNode property

Noden som associerar detta stilark med dokumentet. För HTML kan detta vara motsvarande LINK‑ eller STYLE‑element. För XML kan det vara den länkande processinstruktionen. För stilark som inkluderas av andra stilark är värdet för detta attribut null.

```java
public Node OwnerNode { get; }
```

### Property Value

ownerNode‑attributet måste returnera ägarnoden.

## Anmärkningar

För stilark som inkluderas av andra stilark, till exempel med @import, är värdet för denna egenskap null.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-ownernode](https://drafts.csswg.org/cssom/#dom-stylesheet-ownernode) – The CSSOM definition.

### Se även

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
