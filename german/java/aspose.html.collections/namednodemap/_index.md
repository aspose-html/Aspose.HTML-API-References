---
title: "NamedNodeMap Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.collections.NamedNodeMap Klasse. Stellt Sammlungen von Attributen dar, die über ihren Namen zugänglich sind"
type: docs

url: /de/java/com.aspose.html.collections/namednodemap/
---
## NamedNodeMap class

Stellt Sammlungen von Attributen dar, die über ihren Namen zugänglich sind.

```java
public class NamedNodeMap : DOMObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getItem](../../com.aspose.html.collections/namednodemap/item/) Gibt das Element an der angegebenen Indexposition in der Map zurück. Wenn der Index größer oder gleich der Anzahl der Knoten in dieser Map ist, wird null zurückgegeben. (2 Indexer) |
| [getLength](../../com.aspose.html.collections/namednodemap/length/) Die Anzahl der Knoten in dieser Map. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getNamedItem](../../com.aspose.html.collections/namednodemap/getnameditem/)(String) | Ruft einen Knoten ab, der durch den Namen angegeben ist. |
| [getNamedItemNS](../../com.aspose.html.collections/namednodemap/getnameditemns/)(String, String) | Ruft einen Knoten ab, der durch lokalen Namen und Paket-URI angegeben ist. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript‑Objekt abzurufen. |
| [removeNamedItem](../../com.aspose.html.collections/namednodemap/removenameditem/)(String) | Entfernt einen Knoten, der durch den Namen angegeben ist. |
| [removeNamedItemNS](../../com.aspose.html.collections/namednodemap/removenameditemns/)(String, String) | Entfernt einen Knoten, der durch lokalen Namen und Paket-URI angegeben ist. |
| [setNamedItem](../../com.aspose.html.collections/namednodemap/setnameditem/)(Attr) | Fügt einen Knoten über sein nodeName-Attribut hinzu. Wenn bereits ein Knoten mit diesem Namen in dieser Map vorhanden ist, wird er durch den neuen ersetzt. Das Ersetzen eines Knotens durch sich selbst hat keine Wirkung. |
| [setNamedItemNS](../../com.aspose.html.collections/namednodemap/setnameditemns/)(Attr) | Fügt einen Knoten über sein packageURI und localName hinzu. Wenn bereits ein Knoten mit diesem Paket-URI und diesem lokalen Namen in dieser Map vorhanden ist, wird er durch den neuen ersetzt. Das Ersetzen eines Knotens durch sich selbst hat keine Wirkung. |

### Siehe auch

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.collections](../../com.aspose.html.collections/)
* package [Aspose.HTML](../../)
