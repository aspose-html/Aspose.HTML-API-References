---
title: SVGListBase-1.RemoveItem
second_title: Aspose.HTML for Java API Reference
description: SVGListBase method. Removes an existing item from the list
type: docs

url: /java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Removes an existing item from the list.

```java
public T RemoveItem(ulong index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | UInt64 | The index of the item which is to be removed. The first item is number 0. |

### Return Value

The removed item.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Raised when the list cannot be modified. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Raised if the index number is greater than or equal to numberOfItems. |

### See Also

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
