---
title: CSSValueList Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.CSSValueList class. The CSSValueList interface provides the abstraction of an ordered collection of CSS values
type: docs
weight: 520
url: /net/aspose.html.dom.css/cssvaluelist/
---
## CSSValueList class

The CSSValueList interface provides the abstraction of an ordered collection of CSS values.

Note: This interface was part of an attempt to create a typed CSS Object Model. This attempt has been abandoned, and most browsers do not implement it.

```csharp
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## Constructors

| Name | Description |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | Initializes a new instance of the `CSSValueList` class. |
| [CSSValueList](cssvaluelist/#constructor_1)(*params CSSValue[]*) | Initializes a new instance of the `CSSValueList` class. |
| [CSSValueList](cssvaluelist/#constructor_2)(*IEnumerable&lt;CSSValue&gt;*) | Initializes a new instance of the `CSSValueList` class. |

## Properties

| Name | Description |
| --- | --- |
| override [CSSText](../../aspose.html.dom.css/cssvaluelist/csstext/) { get; set; } | The cssText property of the [`CSSValue`](../cssvalue/) interface represents the current computed CSS property value. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | A code defining the type of the value. |
| [Item](../../aspose.html.dom.css/cssvaluelist/item/) { get; } | The item() method of the CSSValueList interface is used to retrieve a CSSValue by ordinal index. |
| [Length](../../aspose.html.dom.css/cssvaluelist/length/) { get; } | The length read-only property of the CSSValueList interface represents the number of CSSValues in the list. The range of valid values of the indices is 0 to length-1 inclusive. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(*object*) | Determines whether the specified Object is equal to this instance. |
| [GetEnumerator](../../aspose.html.dom.css/cssvaluelist/getenumerator/)() | Returns an enumerator that iterates through the collection. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Returns a hash code for this instance. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvaluelist/getplatformtype/)() | This method is used to retrieve ECMAScript object Type. |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | Returns a String that represents this instance. |

### See Also

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
