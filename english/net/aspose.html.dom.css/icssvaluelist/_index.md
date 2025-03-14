---
title: ICSSValueList Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.ICSSValueList interface. The CSSValueList interface derives from the CSSValue interface and provides the abstraction of an ordered collection of CSS values
type: docs
weight: 700
url: /net/aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

The CSSValueList interface derives from the [`CSSValue`](../cssvalue/) interface and provides the abstraction of an ordered collection of CSS values.

Some properties allow an empty list in their syntax. In that case, these properties take the none identifier. So, an empty list means that the property has the value none.

The items in the CSSValueList are accessible via an integral index, starting from 0.

```csharp
public interface ICSSValueList
```

## Members
## Properties

| Name | Description |
| --- | --- |
| [Item](../../aspose.html.dom.css/icssvaluelist/item/) { get; } | This method is used to retrieve a CSSValue by ordinal index. The order in this collection represents the order of the values in the CSS style property. If index is greater than or equal to the number of values in the list, this returns null. |
| [Length](../../aspose.html.dom.css/icssvaluelist/length/) { get; } | The length read-only property of the CSSValueList interface represents the number of CSSValues in the list. The range of valid values of the indices is 0 to length-1 inclusive. |

## Remarks

This interface was part of an attempt to create a typed CSS Object Model. This attempt has been abandoned, and most browsers do not implement it.

To achieve your purpose, you can use:

the untyped [CSS Object Model](https://drafts.csswg.org/cssom/), widely supported, orthe modern [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects), less supported and considered experimental.

### See Also

* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
