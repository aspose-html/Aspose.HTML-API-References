---
title: Interface IXPathEvaluator
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.XPath.IXPathEvaluator koppel. Die Auswertung von XPathAusdrücken wird bereitgestellt vonIXPathEvaluator .
type: docs
weight: 2560
url: /de/net/aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Die Auswertung von XPath-Ausdrücken wird bereitgestellt von`IXPathEvaluator` .

```csharp
public interface IXPathEvaluator
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateExpression](../../aspose.html.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | Erstellt einen geparsten XPath-Ausdruck mit aufgelösten Namespaces. Dies ist nützlich, wenn ein Ausdruck in einer Anwendung wiederverwendet wird, da es ermöglicht, die Ausdruckszeichenfolge in eine effizientere interne Form zu kompilieren und alle Namensraumpräfixe vorab aufzulösen, die innerhalb des Ausdrucks vorkommen. |
| [CreateNSResolver](../../aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Passt jeden DOM-Knoten an, um Namespaces aufzulösen, so dass ein XPath-Ausdruck leicht ausgewertet werden kann relativ zum Kontext des Knotens, in dem er im Dokument vorkam. Dieser Adapter funktioniert wie die DOM-Level-3-Methode`lookupNamespace-URI` auf Knoten beim Auflösen des Namensraum-URI aus einem gegebenen Präfix unter Verwendung der aktuellen Informationen, die in der Knotenhierarchie zu dem Zeitpunkt verfügbar sind, an dem lookupNamespaceURI aufgerufen wird, wobei auch das implizite XML-Präfix korrekt aufgelöst wird. |
| [Evaluate](../../aspose.html.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Wertet eine XPath-Ausdruckszeichenfolge aus und gibt, wenn möglich, ein Ergebnis des angegebenen Typs zurück. |

### Siehe auch

* namensraum [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* Montage [Aspose.HTML](../../)


