---
title: IXPathResult.SnapshotItem
second_title: Aspose.HTML for .NET API Reference
description: IXPathResult SnapshotItem method. Returns the indexth item in the snapshot collection. If index is greater than or equal to the number of nodes in the list this method returns null. Unlike the iterator result the snapshot does not become invalid but may not correspond to the current document if it is mutated
type: docs
weight: 90
url: /net/aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Returns the `index`th item in the snapshot collection. If `index` is greater than or equal to the number of nodes in the list, this method returns `null`. Unlike the iterator result, the snapshot does not become invalid, but may not correspond to the current document if it is mutated.

```csharp
public Node SnapshotItem(int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | Index into the snapshot collection. |

### Return Value

The node at the `index`th position in the `NodeList`, or `null` if that is not a valid index.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: raised if `resultType` is not `UnorderedNodeSnapshot` type or `OrderedNodeSnapshot` type. |

### See Also

* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Html.Dom.XPath](../../../aspose.html.dom.xpath/)
* assembly [Aspose.HTML](../../../)
