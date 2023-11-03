---
title: SVGListBaseT Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Svg.Collections.SVGListBase1T class. This interface defines a base list of all SVG lists
type: docs
weight: 1210
url: /net/aspose.html.dom.svg.collections/svglistbase-1/
---
## SVGListBase&lt;T&gt; class

This interface defines a base list of all SVG lists.

```csharp
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| Parameter | Description |
| --- | --- |
| T | Type of item stored in list. |

## Properties

| Name | Description |
| --- | --- |
| [Item](../../aspose.html.dom.svg.collections/svglistbase-1/item/) { get; set; } | Returns the indexth item in the list. |
| [Length](../../aspose.html.dom.svg.collections/svglistbase-1/length/) { get; } | The number of items in the list. |
| [NumberOfItems](../../aspose.html.dom.svg.collections/svglistbase-1/numberofitems/) { get; } | The number of items in the list. |

## Methods

| Name | Description |
| --- | --- |
| [AppendItem](../../aspose.html.dom.svg.collections/svglistbase-1/appenditem/)(T) | Inserts a new item at the end of the list. |
| [Clear](../../aspose.html.dom.svg.collections/svglistbase-1/clear/)() | Clears all existing current items from the list, with the result being an empty list. |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [GetEnumerator](../../aspose.html.dom.svg.collections/svglistbase-1/getenumerator/)() | Gets the enumerator. |
| [GetItem](../../aspose.html.dom.svg.collections/svglistbase-1/getitem/)(ulong) | Returns the specified item from the list. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [Initialize](../../aspose.html.dom.svg.collections/svglistbase-1/initialize/)(T) | Clears all existing current items from the list and re-initializes the list to hold the single item specified by the parameter. |
| [InsertItemBefore](../../aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/)(T, ulong) | Inserts a new item into the list at the specified position. The first item is number 0. |
| [RemoveItem](../../aspose.html.dom.svg.collections/svglistbase-1/removeitem/)(ulong) | Removes an existing item from the list. |
| [ReplaceItem](../../aspose.html.dom.svg.collections/svglistbase-1/replaceitem/)(T, ulong) | Replaces an existing item in the list with a new item. |

### See Also

* class [SVGValueType](../../aspose.html.dom.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Html.Dom.Svg.Collections](../../aspose.html.dom.svg.collections/)
* assembly [Aspose.HTML](../../)
