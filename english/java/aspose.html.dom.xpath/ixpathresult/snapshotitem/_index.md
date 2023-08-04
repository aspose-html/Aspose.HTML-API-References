---
title: IXPathResult.SnapshotItem
second_title: Aspose.HTML for Java API Reference
description: IXPathResult method. Returns the indexth item in the snapshot collection. If index is greater than or equal to the number of nodes in the list this method returns null. Unlike the iterator result the snapshot does not become invalid but may not correspond to the current document if it is mutated
type: docs
weight: 90
url: /java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Returns the `index`th item in the snapshot collection. If `index` is greater than or equal to the number of nodes in the list, this method returns `null`. Unlike the iterator result, the snapshot does not become invalid, but may not correspond to the current document if it is mutated.

```java
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
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: raised if `resultType` is not `UnorderedNodeSnapshot` type or `OrderedNodeSnapshot` type. |

### See Also

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.Dom.XPath](../../ixpathresult/)
* package [Aspose.HTML](../../../)
