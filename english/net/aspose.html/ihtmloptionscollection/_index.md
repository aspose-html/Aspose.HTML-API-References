---
title: IHTMLOptionsCollection Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.IHTMLOptionsCollection interface. An HTMLOptionsCollection is a list of nodes representing HTML option element. An individual node may be accessed by either ordinal index or the nodes name or id attributes. Collections in the HTML DOM are assumed to be live meaning that they are automatically updated when the underlying document is changed
type: docs
weight: 3910
url: /net/aspose.html/ihtmloptionscollection/
---
## IHTMLOptionsCollection interface

An `HTMLOptionsCollection` is a list of nodes representing HTML option element. An individual node may be accessed by either ordinal index or the node's `name` or `id` attributes. Collections in the HTML DOM are assumed to be live meaning that they are automatically updated when the underlying document is changed.

See also the [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109). @since DOM Level 2

```csharp
public interface IHTMLOptionsCollection : IEnumerable<Element>
```

## Members
## Properties

| Name | Description |
| --- | --- |
| [Item](../../aspose.html/ihtmloptionscollection/item/) { get; } | Returns the indexth item in the collection. If index is greater than or equal to the number of nodes in the list, this returns null. (2 indexers) |
| [Length](../../aspose.html/ihtmloptionscollection/length/) { get; } | The number of nodes in the list. |

## Members
## Methods

| Name | Description |
| --- | --- |
| [NamedItem](../../aspose.html/ihtmloptionscollection/nameditem/)(*string*) | Method returns the indexth item in the collection. http://www.w3.org/TR/DOM-Level-2-HTML/html.html#HTMLOptionsCollection-namedItem |

### See Also

* class [Element](../../aspose.html.dom/element/)
* namespace [Aspose.Html](../../aspose.html/)
* assembly [Aspose.HTML](../../)
