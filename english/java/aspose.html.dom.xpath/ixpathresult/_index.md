---
title: IXPathResult Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.xpath.IXPathResult interface. The XPathResult interface represents the result of the evaluation of an XPath 1.0 expression within the context of a particular node. Since evaluation of an XPath expression can result in various result types this object makes it possible to discover and manipulate the type and value of the result
type: docs

url: /java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

The `XPathResult` interface represents the result of the evaluation of an XPath 1.0 expression within the context of a particular node. Since evaluation of an XPath expression can result in various result types, this object makes it possible to discover and manipulate the type and value of the result.

```java
public interface IXPathResult
```

## Properties

| Name | Description |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) The value of this boolean result. |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) Signifies that the iterator has become invalid. True if `resultType`is `UnorderedNodeIterator` type or `OrderedNodeIterator` type and the document has been modified since this result was returned. |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) The value of this number result. |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) A code representing the type of this result, as defined by the http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/) enum. |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) The value of this single node result, which may be `null`. |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) The number of nodes in the result snapshot. Valid values for snapshotItem indices are `0` to `snapshotLength-1` inclusive. |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) The value of this String result. |

## Methods

| Name | Description |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Iterates and returns the next node from the node set or `null` if there are no more nodes. |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Returns the `index`th item in the snapshot collection. If `index` is greater than or equal to the number of nodes in the list, this method returns `null`. Unlike the iterator result, the snapshot does not become invalid, but may not correspond to the current document if it is mutated. |

### See Also

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
