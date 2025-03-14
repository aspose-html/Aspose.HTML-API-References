---
title: ICSSValueList.Item
second_title: Aspose.HTML for .NET API Reference
description: ICSSValueList Item property. This method is used to retrieve a CSSValue by ordinal index. The order in this collection represents the order of the values in the CSS style property. If index is greater than or equal to the number of values in the list this returns null
type: docs
weight: 10
url: /net/aspose.html.dom.css/icssvaluelist/item/
---
## ICSSValueList indexer

This method is used to retrieve a CSSValue by ordinal index. The order in this collection represents the order of the values in the CSS style property. If index is greater than or equal to the number of values in the list, this returns null.

See also the [CSSOM](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList)[#CSSValueList](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList).

```csharp
public CSSValue this[int index] { get; }
```

### Return Value

The [`CSSValue`](../../cssvalue/) at the index position in the [`CSSValueList`](../../cssvaluelist/), or null if that is not a valid index.

### Property Value

The index into the collection.

## Remarks

This feature was originally defined in the [DOM Style Level 2](https://www.w3.org/TR/DOM-Level-2-Style) specification, but has been dropped from any standardization effort since then.

It has been superseded by a modern, but incompatible, [CSS Typed Object Model API](https://developer.mozilla.org/en-US/docs/Web/API/CSS_Typed_OM_API) that is now on the standard track.

### See Also

* class [CSSValue](../../cssvalue/)
* interface [ICSSValueList](../)
* namespace [Aspose.Html.Dom.Css](../../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../../)
