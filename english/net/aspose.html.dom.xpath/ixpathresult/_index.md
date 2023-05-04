---
title: IXPathResult Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.XPath.IXPathResult interface. The XPathResult interface represents the result of the evaluation of an XPath 1.0 expression within the context of a particular node. Since evaluation of an XPath expression can result in various result types this object makes it possible to discover and manipulate the type and value of the result
type: docs
weight: 2610
url: /net/aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

The `XPathResult` interface represents the result of the evaluation of an XPath 1.0 expression within the context of a particular node. Since evaluation of an XPath expression can result in various result types, this object makes it possible to discover and manipulate the type and value of the result.

```csharp
public interface IXPathResult
```

## Properties

| Name | Description |
| --- | --- |
| [BooleanValue](../../aspose.html.dom.xpath/ixpathresult/booleanvalue/) { get; } | The value of this boolean result. |
| [InvalidIteratorState](../../aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Signifies that the iterator has become invalid. True if `resultType`is `UnorderedNodeIterator` type or `OrderedNodeIterator` type and the document has been modified since this result was returned. |
| [NumberValue](../../aspose.html.dom.xpath/ixpathresult/numbervalue/) { get; } | The value of this number result. |
| [ResultType](../../aspose.html.dom.xpath/ixpathresult/resulttype/) { get; } | A code representing the type of this result, as defined by the http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/) enum. |
| [SingleNodeValue](../../aspose.html.dom.xpath/ixpathresult/singlenodevalue/) { get; } | The value of this single node result, which may be `null`. |
| [SnapshotLength](../../aspose.html.dom.xpath/ixpathresult/snapshotlength/) { get; } | The number of nodes in the result snapshot. Valid values for snapshotItem indices are `0` to `snapshotLength-1` inclusive. |
| [StringValue](../../aspose.html.dom.xpath/ixpathresult/stringvalue/) { get; } | The value of this string result. |

## Methods

| Name | Description |
| --- | --- |
| [IterateNext](../../aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Iterates and returns the next node from the node set or `null` if there are no more nodes. |
| [SnapshotItem](../../aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Returns the `index`th item in the snapshot collection. If `index` is greater than or equal to the number of nodes in the list, this method returns `null`. Unlike the iterator result, the snapshot does not become invalid, but may not correspond to the current document if it is mutated. |

### See Also

* namespace [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* assembly [Aspose.HTML](../../)
