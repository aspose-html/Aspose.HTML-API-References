---
title: Class NamedNodeMap
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Collections.NamedNodeMap klas. Stellt Sammlungen von Attributen dar auf die über den Namen zugegriffen werden kann.
type: docs
weight: 40
url: /de/net/aspose.html.collections/namednodemap/
---
## NamedNodeMap class

Stellt Sammlungen von Attributen dar, auf die über den Namen zugegriffen werden kann.

```csharp
public class NamedNodeMap : DOMObject, IDisposable, IEnumerable<Attr>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.html.collections/namednodemap/item/) { get; } | Gibt das index-te Element in der Map zurück. Wenn der Index größer oder gleich der Anzahl der Knoten in dieser Karte ist, wird null zurückgegeben. (2 indexers) |
| [Length](../../aspose.html.collections/namednodemap/length/) { get; } | Die Anzahl der Knoten in dieser Karte. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetEnumerator](../../aspose.html.collections/namednodemap/getenumerator/)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [GetNamedItem](../../aspose.html.collections/namednodemap/getnameditem/)(string) | Ruft einen namentlich angegebenen Knoten ab. |
| [GetNamedItemNS](../../aspose.html.collections/namednodemap/getnameditemns/)(string, string) | Ruft einen Knoten ab, der durch lokalen Namen und Namensraum-URI angegeben ist. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [RemoveNamedItem](../../aspose.html.collections/namednodemap/removenameditem/)(string) | Entfernt einen namentlich angegebenen Knoten. |
| [RemoveNamedItemNS](../../aspose.html.collections/namednodemap/removenameditemns/)(string, string) | Entfernt einen Knoten, der durch lokalen Namen und Namespace-URI angegeben ist. |
| [SetNamedItem](../../aspose.html.collections/namednodemap/setnameditem/)(Attr) | Fügt einen Knoten mit seinem nodeName-Attribut hinzu. Wenn ein Knoten mit diesem Namen bereits in dieser Map vorhanden ist, wird er durch den neuen ersetzt. Das Ersetzen eines Knotens durch sich selbst hat keine Auswirkung. |
| [SetNamedItemNS](../../aspose.html.collections/namednodemap/setnameditemns/)(Attr) | Fügt einen Knoten mit seinem NamespaceURI und localName hinzu. Wenn ein Knoten mit diesem Namensraum-URI und diesem lokalen Namen bereits in dieser Zuordnung vorhanden ist, wird er durch den neuen ersetzt. Das Ersetzen eines Knotens durch sich selbst hat keine Auswirkung. |

### Siehe auch

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Attr](../../aspose.html.dom/attr/)
* namensraum [Aspose.Html.Collections](../../aspose.html.collections/)
* Montage [Aspose.HTML](../../)


