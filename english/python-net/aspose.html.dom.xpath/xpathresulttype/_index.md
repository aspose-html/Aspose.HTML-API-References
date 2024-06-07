---
title: XPathResultType enumeration
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 60
url: /aspose.html.dom.xpath/xpathresulttype/
is_root: false
---

## XPathResultType enumeration

An unsigned short indicating what type of result this is. If a specific 
`type` is specified, then the result will be returned as the corresponding 
type, using XPath type conversions where required and possible.



The XPathResultType type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| ANY | This code does not represent a specific type. An evaluation of an XPath expression <br/>will never produce this type. If this type is requested, then the evaluation returns <br/>whatever type naturally results from evaluation of the expression. If the natural <br/>result is a node set when `Any` type was requested, then `UnorderedNodeIterator` <br/>is always the resulting type. Any other representation of a node set must be <br/>explicitly requested. |
| NUMBER | The result is a number as defined by [XPath 1.0]. Document modification does not <br/>invalidate the number, but may mean that reevaluation would not yield the same number. |
| STRING | The result is a string as defined by [XPath 1.0]. Document modification does not <br/>invalidate the string, but may mean that the string no longer corresponds to the <br/>current document. |
| BOOLEAN | The result is a boolean as defined by [XPath 1.0]. Document modification does not <br/>invalidate the boolean, but may mean that reevaluation would not yield the same boolean. |
| UNORDERED_NODE_ITERATOR | The result is a node set as defined by [XPath 1.0] that will be accessed iteratively, <br/>which may not produce nodes in a particular order. Document modification invalidates the <br/>iteration. This is the default type returned if the result is a node set and `Any` <br/>type is requested. |
| ORDERED_NODE_ITERATOR | The result is a node set as defined by [XPath 1.0] that will be accessed iteratively, <br/>which will produce document-ordered nodes. Document modification invalidates the iteration. |
| UNORDERED_NODE_SNAPSHOT | The result is a node set as defined by [XPath 1.0] that will be accessed as a snapshot <br/>list of nodes that may not be in a particular order. Document modification does not <br/>invalidate the snapshot but may mean that reevaluation would not yield the same snapshot <br/>and nodes in the snapshot may have been altered, moved, or removed from the document. |
| ORDERED_NODE_SNAPSHOT | The result is a node set as defined by [XPath 1.0] that will be accessed as a snapshot <br/>list of nodes that will be in original document order. Document modification does not <br/>invalidate the snapshot but may mean that reevaluation would not yield the same snapshot <br/>and nodes in the snapshot may have been altered, moved, or removed from the document. |
| ANY_UNORDERED_NODE | The result is a node set as defined by [XPath 1.0] and will be accessed as a single node, <br/>which may be `null` if the node set is empty. Document modification does not invalidate <br/>the node, but may mean that the result node no longer corresponds to the current document. <br/>This is a convenience that permits optimization since the implementation can stop once any <br/>node in the resulting set has been found. If there is more than one node in the actual result, <br/>the single node returned might not be the first in document order. |
| FIRST_ORDERED_NODE | The result is a node set as defined by [XPath 1.0] and will be accessed as a single node, <br/>which may be `null` if the node set is empty. Document modification does not invalidate <br/>the node, but may mean that the result node no longer corresponds to the current document. <br/>This is a convenience that permits optimization since the implementation can stop once the <br/>first node in document order of the resulting set has been found. If there are more than one <br/>node in the actual result, the single node returned will be the first in document order. |



### See Also
* module [`aspose.html.dom.xpath`](..)
