---
title: IXPathResult class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 50
url: /python-net/aspose.html.dom.xpath/ixpathresult/
is_root: false
---

## IXPathResult class

The `XPathResult` interface represents the result of the evaluation of an 
XPath 1.0 expression within the context of a particular node. Since evaluation 
of an XPath expression can result in various result types, this object makes it 
possible to discover and manipulate the type and value of the result.



The IXPathResult type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [result_type](/html/python-net/aspose.html.dom.xpath/ixpathresult/result_type) | A code representing the type of this result, as defined by the <br/>http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult<br/>[`XPathResultType`](/html/python-net/aspose.html.dom.xpath/xpathresulttype) enum. |
| [number_value](/html/python-net/aspose.html.dom.xpath/ixpathresult/number_value) | The value of this number result. |
| [string_value](/html/python-net/aspose.html.dom.xpath/ixpathresult/string_value) | The value of this string result. |
| [boolean_value](/html/python-net/aspose.html.dom.xpath/ixpathresult/boolean_value) | The value of this boolean result. |
| [single_node_value](/html/python-net/aspose.html.dom.xpath/ixpathresult/single_node_value) | The value of this single node result, which may be `null`. |
| [invalid_iterator_state](/html/python-net/aspose.html.dom.xpath/ixpathresult/invalid_iterator_state) | Signifies that the iterator has become invalid. True if `resultType` <br/>is `UnorderedNodeIterator` type or `OrderedNodeIterator` type and <br/>the document has been modified since this result was returned. |
| [snapshot_length](/html/python-net/aspose.html.dom.xpath/ixpathresult/snapshot_length) | The number of nodes in the result snapshot. Valid values for snapshotItem <br/>indices are `0` to `snapshotLength-1` inclusive. |


### Methods
| Method | Description |
| :- | :- |
| [iterate_next](/html/python-net/aspose.html.dom.xpath/ixpathresult/iterate_next/#) | Iterates and returns the next node from the node set or `null` if there are no more nodes. |
| [snapshot_item](/html/python-net/aspose.html.dom.xpath/ixpathresult/snapshot_item/#int) | Returns the `index`th item in the snapshot collection. If `index` is greater than <br/>or equal to the number of nodes in the list, this method returns `null`. Unlike the <br/>iterator result, the snapshot does not become invalid, but may not correspond to the current <br/>document if it is mutated. |



### See Also
* module [`aspose.html.dom.xpath`](..)
* class [`XPathResultType`](/html/python-net/aspose.html.dom.xpath/xpathresulttype)
