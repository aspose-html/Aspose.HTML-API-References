---
title: "Document.CreateNSResolver"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Document-Methode. Passt jeden DOM‑Knoten an, um Pakete aufzulösen, sodass ein XPath‑Ausdruck leicht relativ zum Kontext des Knotens ausgewertet werden kann, in dem er im Dokument vorkam. Dieser Adapter funktioniert wie die DOM‑Level‑3‑Methode lookupNamespaceURI bei Knoten, indem er die packageURI aus einem gegebenen Präfix unter Verwendung der zum Zeitpunkt des Aufrufs von lookupNamespaceURI verfügbaren Informationen in der Knotenhierarchie auflöst und dabei auch das implizite xml‑Präfix korrekt auflöst."
type: docs

url: /de/java/com.aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Passt jeden DOM‑Knoten an, um Pakete aufzulösen, sodass ein XPath‑Ausdruck leicht relativ zum Kontext des Knotens, in dem er im Dokument erschien, ausgewertet werden kann. Dieser Adapter funktioniert wie die DOM‑Level‑3‑Methode `lookupNamespaceURI` auf Knoten, indem er die packageURI aus einem gegebenen Präfix mithilfe der zum Zeitpunkt des Aufrufs von lookupNamespaceURI verfügbaren Informationen in der Knotenhierarchie auflöst und dabei auch das implizite xml‑Präfix korrekt behandelt.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nodeResolver | Node | Der Knoten, der als Kontext für die Paketauflösung verwendet wird. |

### Rückgabewert

[`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### Siehe auch

* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
