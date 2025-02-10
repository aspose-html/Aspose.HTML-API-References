---
title: SVGListBase-1.ReplaceItem
second_title: Aspose.HTML for Java API Reference
description: SVGListBase method. Replaces an existing item in the list with a new item
type: docs
weight: 110
url: /java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Replaces an existing item in the list with a new item.

```java
public T ReplaceItem(T newItem, ulong index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newItem | T | The item which is to be inserted into the list. |
| index | UInt64 | The index of the item which is to be replaced. The first item is number 0. |

### Return Value

The inserted item.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Raised when the list cannot be modified. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Raised if the index number is greater than or equal to numberOfItems. |

### See Also

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
