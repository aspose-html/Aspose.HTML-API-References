---
title: Class NamedNodeMap
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Collections.NamedNodeMap klas. Vertegenwoordigt verzamelingen attributen die toegankelijk zijn op naam.
type: docs
weight: 40
url: /nl/net/aspose.html.collections/namednodemap/
---
## NamedNodeMap class

Vertegenwoordigt verzamelingen attributen die toegankelijk zijn op naam.

```csharp
public class NamedNodeMap : DOMObject, IDisposable, IEnumerable<Attr>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Item](../../aspose.html.collections/namednodemap/item/) { get; } | Geeft het index-de item op de kaart terug. Als index groter is dan of gelijk is aan het aantal knooppunten in deze kaart, retourneert dit null. (2 indexers) |
| [Length](../../aspose.html.collections/namednodemap/length/) { get; } | Het aantal knooppunten op deze kaart. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [GetEnumerator](../../aspose.html.collections/namednodemap/getenumerator/)() | Retourneert een enumerator die de verzameling herhaalt. |
| [GetNamedItem](../../aspose.html.collections/namednodemap/getnameditem/)(string) | Haalt een node op gespecificeerd door name. |
| [GetNamedItemNS](../../aspose.html.collections/namednodemap/getnameditemns/)(string, string) | Haalt een knooppunt op gespecificeerd door lokale naam en naamruimte-URI op. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| [RemoveNamedItem](../../aspose.html.collections/namednodemap/removenameditem/)(string) | Verwijdert een knooppunt gespecificeerd door name. |
| [RemoveNamedItemNS](../../aspose.html.collections/namednodemap/removenameditemns/)(string, string) | Verwijdert een knooppunt gespecificeerd door lokale naam en naamruimte-URI. |
| [SetNamedItem](../../aspose.html.collections/namednodemap/setnameditem/)(Attr) | Voegt een knooppunt toe met behulp van het kenmerk nodeName. Als er al een knooppunt met die naam op deze kaart aanwezig is, wordt het vervangen door het nieuwe. Het vervangen van een node op zichzelf heeft geen effect. |
| [SetNamedItemNS](../../aspose.html.collections/namednodemap/setnameditemns/)(Attr) | Voegt een knooppunt toe met zijn namespaceURI en localName. Als een knooppunt met die naamruimte-URI en die lokale naam al aanwezig is in deze kaart, wordt deze vervangen door de nieuwe. Het vervangen van een node op zichzelf heeft geen effect. |

### Zie ook

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Attr](../../aspose.html.dom/attr/)
* naamruimte [Aspose.Html.Collections](../../aspose.html.collections/)
* montage [Aspose.HTML](../../)


