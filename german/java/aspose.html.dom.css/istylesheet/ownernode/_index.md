---
title: "IStyleSheet.OwnerNode"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IStyleSheet‑Eigenschaft. Der Knoten, der dieses Stylesheet mit dem Dokument verknüpft. Für HTML kann dies das entsprechende LINK‑ oder STYLE‑Element sein. Für XML kann es die verknüpfende Verarbeitungsanweisung sein. Für Stylesheets, die von anderen Stylesheets eingebunden werden, ist der Wert dieses Attributs null."
type: docs

url: /de/java/com.aspose.html.dom.css/istylesheet/ownernode/
---
## IStyleSheet.OwnerNode property

Der Knoten, der dieses Stylesheet mit dem Dokument verknüpft. Für HTML kann dies das entsprechende LINK‑ oder STYLE‑Element sein. Für XML kann es die verknüpfende Verarbeitungsanweisung sein. Für Stylesheets, die von anderen Stylesheets eingebunden werden, ist der Wert dieses Attributs null.

```java
public Node OwnerNode { get; }
```

### Property Value

Das ownerNode‑Attribut muss den Eigentümerknoten zurückgeben.

## Hinweise

Für Stylesheets, die von anderen Stylesheets eingebunden werden, z. B. mit @import, ist der Wert dieser Eigenschaft null.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referenz

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-ownernode](https://drafts.csswg.org/cssom/#dom-stylesheet-ownernode) – The CSSOM definition.

### Siehe auch

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
