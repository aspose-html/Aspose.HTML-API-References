---
title: IXPathResult.IterateNext
second_title: Aspose.HTML for Java API Reference
description: IXPathResult method. Iterates and returns the next node from the node set or null if there are no more nodes
type: docs
weight: 80
url: /java/com.aspose.html.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

Iterates and returns the next node from the node set or `null` if there are no more nodes.

```java
public Node IterateNext()
```

### Return Value

Returns the next node.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: raised if `resultType` is not `UnorderedNodeIterator` type or `OrderedNodeIterator` type. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: The document has been mutated since the result was returned. |

### See Also

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
