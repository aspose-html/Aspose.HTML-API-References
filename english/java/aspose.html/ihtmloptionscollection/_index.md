---
title: IHTMLOptionsCollection Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.IHTMLOptionsCollection interface. An HTMLOptionsCollection is a list of nodes representing HTML option element. An individual node may be accessed by either ordinal index or the nodes name or id attributes. Collections in the HTML DOM are assumed to be live meaning that they are automatically updated when the underlying document is changed
type: docs
weight: 3910
url: /java/com.aspose.html/ihtmloptionscollection/
---
## IHTMLOptionsCollection interface

An `HTMLOptionsCollection` is a list of nodes representing HTML option element. An individual node may be accessed by either ordinal index or the node's `name` or `id` attributes. Collections in the HTML DOM are assumed to be live meaning that they are automatically updated when the underlying document is changed.

See also the [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109). @since DOM Level 2

```java
public interface IHTMLOptionsCollection : IEnumerable<Element>
```

## Properties

| Name | Description |
| --- | --- |
| [getItem](../../com.aspose.html/ihtmloptionscollection/item/) Returns the indexth item in the collection. If index is greater than or equal to the number of nodes in the list, this returns null. (2 indexers) |
| [getLength](../../com.aspose.html/ihtmloptionscollection/length/) The number of nodes in the list. |

## Methods

| Name | Description |
| --- | --- |
| [namedItem](../../com.aspose.html/ihtmloptionscollection/nameditem/)(String) | Method returns the indexth item in the collection. http://www.w3.org/TR/DOM-Level-2-HTML/html.html#HTMLOptionsCollection-namedItem |

### See Also

* class [Element](../../com.aspose.html.dom/element/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
