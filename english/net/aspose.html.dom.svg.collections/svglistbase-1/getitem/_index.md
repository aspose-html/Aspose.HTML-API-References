---
title: SVGListBase-1.GetItem
second_title: Aspose.HTML for .NET API Reference
description: SVGListBase method. Returns the specified item from the list
type: docs
weight: 70
url: /net/aspose.html.dom.svg.collections/svglistbase-1/getitem/
---
## SVGListBase&lt;T&gt;.GetItem method

Returns the specified item from the list.

```csharp
public T GetItem(ulong index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | UInt64 | The index of the item from the list which is to be returned. The first item is number 0. |

### Return Value

The selected item.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). Raised if the index number is greater than or equal to numberOfItems. |

### See Also

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* assembly [Aspose.HTML](../../../)
