---
title: NodeFilter Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Traversal.Filters.NodeFilter class. Filters are objects that know how to filter out nodes
type: docs
weight: 2630
url: /net/aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filters are objects that know how to "filter out" nodes.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Methods

| Name | Description |
| --- | --- |
| abstract [AcceptNode](../../aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(*[Node](../../aspose.html.dom/node/)*) | Test whether a specified node is visible in the logical view of a TreeWalker or NodeIterator. This function will be called by the implementation of TreeWalker and NodeIterator; it is not normally called directly from user code. (Though you could do so if you wanted to use the same filter to guide your own application logic.) |
| override [GetPlatformType](../../aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | This method is used to retrieve ECMAScript object Type. |

## Fields

| Name | Description |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Accept the node. Navigation methods defined for NodeIterator or TreeWalker will return this node. |
| const [FILTER_REJECT](../../aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Reject the node. Navigation methods defined for NodeIterator or TreeWalker will not return this node. For TreeWalker, the children of this node will also be rejected. NodeIterators treat this as a synonym for FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Skip this single node. Navigation methods defined for NodeIterator or TreeWalker will not return this node. For both NodeIterator and TreeWalker, the children of this node will still be considered. |
| const [SHOW_ALL](../../aspose.html.dom.traversal.filters/nodefilter/show_all/) | Show all Nodes. |
| const [SHOW_ATTRIBUTE](../../aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Show Attr nodes. This is meaningful only when creating an iterator or tree-walker with an attribute node as its root; in this case, it means that the attribute node will appear in the first position of the iteration or traversal. Since attributes are never children of other nodes, they do not appear when traversing over the document tree. |
| const [SHOW_CDATA_SECTION](../../aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Show CDATASection nodes. |
| const [SHOW_COMMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Show Comment nodes. |
| const [SHOW_DOCUMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document/) | Show Document nodes. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Show DocumentFragment nodes. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Show DocumentType nodes. |
| const [SHOW_ELEMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_element/) | Show Element nodes. |
| const [SHOW_ENTITY](../../aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Show Entity nodes. This is meaningful only when creating an iterator or tree-walker with an Entity node as its root; in this case, it means that the Entity node will appear in the first position of the traversal. Since entities are not part of the document tree, they do not appear when traversing over the document tree. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Show EntityReference nodes. |
| const [SHOW_NOTATION](../../aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Show Notation nodes. This is meaningful only when creating an iterator or tree-walker with a Notation node as its root; in this case, it means that the Notation node will appear in the first position of the traversal. Since notations are not part of the document tree, they do not appear when traversing over the document tree. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Show ProcessingInstruction nodes. |
| const [SHOW_TEXT](../../aspose.html.dom.traversal.filters/nodefilter/show_text/) | Show Text nodes. |

### See Also

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [INodeFilter](../../aspose.html.dom.traversal/inodefilter/)
* namespace [Aspose.Html.Dom.Traversal.Filters](../../aspose.html.dom.traversal.filters/)
* assembly [Aspose.HTML](../../)
