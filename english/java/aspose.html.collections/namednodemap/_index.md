---
title: NamedNodeMap Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Collections.NamedNodeMap class. Represents collections of attributes that can be accessed by name
type: docs
weight: 40
url: /net/com.aspose.html.collections/namednodemap/
---
## NamedNodeMap class

Represents collections of attributes that can be accessed by name.

```java
public class NamedNodeMap : DOMObject, IDisposable, IEnumerable<Attr>
```

## Properties

| Name | Description |
| --- | --- |
| [getItem](../../com.aspose.html.collections/namednodemap/item/) Returns the index-th item in the map. If index is greater than or equal to the number of nodes in this map, this returns null. (2 indexers) |
| [getLength](../../com.aspose.html.collections/namednodemap/length/) The number of nodes in this map. |

## Methods

| Name | Description |
| --- | --- |
| [getEnumerator](../../com.aspose.html.collections/namednodemap/getenumerator/)() | Returns an enumerator that iterates through the collection. |
| [getNamedItem](../../com.aspose.html.collections/namednodemap/getnameditem/)(String) | Retrieves a node specified by name. |
| [getNamedItemNS](../../com.aspose.html.collections/namednodemap/getnameditemns/)(String, String) | Retrieves a node specified by local name and package URI. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [removeNamedItem](../../com.aspose.html.collections/namednodemap/removenameditem/)(String) | Removes a node specified by name. |
| [removeNamedItemNS](../../com.aspose.html.collections/namednodemap/removenameditemns/)(String, String) | Removes a node specified by local name and package URI. |
| [setNamedItem](../../com.aspose.html.collections/namednodemap/setnameditem/)(Attr) | Adds a node using its nodeName attribute. If a node with that name is already present in this map, it is replaced by the new one. Replacing a node by itself has no effect. |
| [setNamedItemNS](../../com.aspose.html.collections/namednodemap/setnameditemns/)(Attr) | Adds a node using its packageURI and localName. If a node with that package URI and that local name is already present in this map, it is replaced by the new one. Replacing a node by itself has no effect. |

### See Also

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* class [Attr](../../com.aspose.html.dom/attr/)
* package [com.aspose.html.Collections](../../com.aspose.html.collections/)
* package [Aspose.HTML](../../)
