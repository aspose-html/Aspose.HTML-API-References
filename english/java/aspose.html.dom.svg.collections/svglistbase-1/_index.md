---
title: SVGListBaseT Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.svg.collections.SVGListBase1T class. This interface defines a base list of all SVG lists
type: docs
weight: 1220
url: /java/com.aspose.html.dom.svg.collections/svglistbase-1/
---
## SVGListBase&lt;T&gt; class

This interface defines a base list of all SVG lists.

```java
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| Parameter | Description |
| --- | --- |
| T | Type of item stored in list. |

## Properties

| Name | Description |
| --- | --- |
[getItem]
[setItem] Returns the indexth item in the list. |
| [getLength](../../com.aspose.html.dom.svg.collections/svglistbase-1/length/) The number of items in the list. |
| [getNumberOfItems](../../com.aspose.html.dom.svg.collections/svglistbase-1/numberofitems/) The number of items in the list. |

## Methods

| Name | Description |
| --- | --- |
| [appendItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/appenditem/)(T) | Inserts a new item at the end of the list. |
| [clear](../../com.aspose.html.dom.svg.collections/svglistbase-1/clear/)() | Clears all existing current items from the list, with the result being an empty list. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [getEnumerator](../../com.aspose.html.dom.svg.collections/svglistbase-1/getenumerator/)() | Gets the enumerator. |
| [getItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/getitem/)(ulong) | Returns the specified item from the list. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [initialize](../../com.aspose.html.dom.svg.collections/svglistbase-1/initialize/)(T) | Clears all existing current items from the list and re-initializes the list to hold the single item specified by the parameter. |
| [insertItemBefore](../../com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/)(T, ulong) | Inserts a new item into the list at the specified position. The first item is number 0. |
| [removeItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/)(ulong) | Removes an existing item from the list. |
| [replaceItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/)(T, ulong) | Replaces an existing item in the list with a new item. |

### See Also

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.collections](../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../)
