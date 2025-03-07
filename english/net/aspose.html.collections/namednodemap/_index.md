---
title: NamedNodeMap Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Collections.NamedNodeMap class. Represents collections of attributes that can be accessed by name
type: docs
weight: 200
url: /net/aspose.html.collections/namednodemap/
---
## NamedNodeMap class

Represents collections of attributes that can be accessed by name.

```csharp
public class NamedNodeMap : DOMObject
```

## Properties

| Name | Description |
| --- | --- |
| [Item](../../aspose.html.collections/namednodemap/item/) { get; } | Returns the index-th item in the map. If index is greater than or equal to the number of nodes in this map, this returns null. (2 indexers) |
| [Length](../../aspose.html.collections/namednodemap/length/) { get; } | The number of nodes in this map. |

## Methods

| Name | Description |
| --- | --- |
| [GetNamedItem](../../aspose.html.collections/namednodemap/getnameditem/)(*string*) | Retrieves a node specified by name. |
| [GetNamedItemNS](../../aspose.html.collections/namednodemap/getnameditemns/)(*string, string*) | Retrieves a node specified by local name and namespace URI. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [RemoveNamedItem](../../aspose.html.collections/namednodemap/removenameditem/)(*string*) | Removes a node specified by name. |
| [RemoveNamedItemNS](../../aspose.html.collections/namednodemap/removenameditemns/)(*string, string*) | Removes a node specified by local name and namespace URI. |
| [SetNamedItem](../../aspose.html.collections/namednodemap/setnameditem/)(*[Attr](../../aspose.html.dom/attr/)*) | Adds a node using its nodeName attribute. If a node with that name is already present in this map, it is replaced by the new one. Replacing a node by itself has no effect. |
| [SetNamedItemNS](../../aspose.html.collections/namednodemap/setnameditemns/)(*[Attr](../../aspose.html.dom/attr/)*) | Adds a node using its namespaceURI and localName. If a node with that namespace URI and that local name is already present in this map, it is replaced by the new one. Replacing a node by itself has no effect. |

### See Also

* class [DOMObject](../../aspose.html.dom/domobject/)
* namespace [Aspose.Html.Collections](../../aspose.html.collections/)
* assembly [Aspose.HTML](../../)
