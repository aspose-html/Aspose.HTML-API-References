---
title: SVGListBase-1.Item
second_title: Aspose.HTML for Java API Reference
description: SVGListBase property. Returns the indexth item in the list
type: docs
weight: 10
url: /java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Returns the indexth item in the list.

```java
public T this[ulong index] { get; set; }
```

| Parameter | Description |
| --- | --- |
| index | Index in the list. |

### Return Value

The stored object at the indexth position in the list.

### Property Value

The type of item stored in list.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Raised when the list cannot be modified. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Raised if the index number is greater than or equal to numberOfItems. |

### See Also

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
