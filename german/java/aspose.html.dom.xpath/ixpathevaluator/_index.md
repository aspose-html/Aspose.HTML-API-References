---
title: "IXPathEvaluator‑Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.xpath.IXPathEvaluator‑Schnittstelle. Die Auswertung von XPath‑Ausdrücken wird von IXPathEvaluator bereitgestellt"
type: docs

url: /de/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Die Auswertung von XPath‑Ausdrücken wird von `IXPathEvaluator` bereitgestellt.

```java
public interface IXPathEvaluator
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | Erstellt einen geparsten XPath‑Ausdruck mit aufgelösten Paketen. Dies ist nützlich, wenn ein Ausdruck in einer Anwendung wiederverwendet werden soll, da er es ermöglicht, die Ausdruckszeichenkette in eine effizientere interne Form zu kompilieren und alle im Ausdruck vorkommenden Paket‑Präfixe vorab aufzulösen. |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Passt jeden DOM‑Knoten an, um Pakete aufzulösen, sodass ein XPath‑Ausdruck leicht relativ zum Kontext des Knotens, in dem er im Dokument erschien, ausgewertet werden kann. Dieser Adapter funktioniert wie die DOM‑Level‑3‑Methode `lookupNamespaceURI` auf Knoten, indem er die packageURI aus einem gegebenen Präfix mithilfe der zum Zeitpunkt des Aufrufs von lookupNamespaceURI verfügbaren Informationen in der Knotenhierarchie auflöst und dabei auch das implizite xml‑Präfix korrekt behandelt. |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Evaluert eine XPath‑Ausdruck‑Zeichenkette und gibt, falls möglich, ein Ergebnis des angegebenen Typs zurück. |

### Siehe auch

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
