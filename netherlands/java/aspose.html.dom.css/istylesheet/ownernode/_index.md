---
title: "IStyleSheet.OwnerNode"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IStyleSheet-eigenschap. Het knooppunt dat dit stijlblad aan het document koppelt. Voor HTML kan dit het bijbehorende LINK‑ of STYLE‑element zijn. Voor XML kan dit de koppelings‑verwerkingsinstructie zijn. Voor stijlbladen die door andere stijlbladen worden opgenomen, is de waarde van dit attribuut null."
type: docs

url: /nl/java/com.aspose.html.dom.css/istylesheet/ownernode/
---
## IStyleSheet.OwnerNode property

Het knooppunt dat dit stijlblad aan het document koppelt. Voor HTML kan dit het bijbehorende LINK‑ of STYLE‑element zijn. Voor XML kan dit de koppelings‑verwerkingsinstructie zijn. Voor stijlbladen die door andere stijlbladen worden opgenomen, is de waarde van dit attribuut null.

```java
public Node OwnerNode { get; }
```

### Property Value

Het ownerNode‑attribuut moet het eigenaarsknooppunt retourneren.

## Opmerkingen

Voor stijlbladen die door andere stijlbladen worden opgenomen, zoals met @import, is de waarde van deze eigenschap null.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referentie

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-ownernode](https://drafts.csswg.org/cssom/#dom-stylesheet-ownernode) – The CSSOM definition.

### Zie ook

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
