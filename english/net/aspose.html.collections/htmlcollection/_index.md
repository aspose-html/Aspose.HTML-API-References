---
title: HTMLCollection Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Collections.HTMLCollection class. The HTMLCollection represents a generic collection of Element
type: docs
weight: 190
url: /net/aspose.html.collections/htmlcollection/
---
## HTMLCollection class

The `HTMLCollection` represents a generic collection of [`Element`](../../aspose.html.dom/element/).

```csharp
public abstract class HTMLCollection : DOMObject, IEnumerable<Element>
```

## Public Members
## Properties

| Name | Description |
| --- | --- |
| abstract [Item](../../aspose.html.collections/htmlcollection/item/) { get; } | Returns the index-th item in the collection. If index is greater than or equal to the number of nodes in the list, this returns null. |
| abstract [Length](../../aspose.html.collections/htmlcollection/length/) { get; } | The number of nodes in the list. |

## Public Members
## Methods

| Name | Description |
| --- | --- |
| abstract [GetEnumerator](../../aspose.html.collections/htmlcollection/getenumerator/)() | Gets the enumerator. |
| override [GetPlatformType](../../aspose.html.collections/htmlcollection/getplatformtype/)() | This method is used to retrieve ECMAScript object Type. |
| [NamedItem](../../aspose.html.collections/htmlcollection/nameditem/)(*string*) | Returns the item in the collection matched specified name. |

### See Also

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Element](../../aspose.html.dom/element/)
* namespace [Aspose.Html.Collections](../../aspose.html.collections/)
* assembly [Aspose.HTML](../../)
