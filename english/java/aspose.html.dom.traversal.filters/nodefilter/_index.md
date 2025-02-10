---
title: NodeFilter Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.traversal.filters.NodeFilter class. Filters are objects that know how to filter out nodes
type: docs

url: /java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filters are objects that know how to "filter out" nodes.

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Methods

| Name | Description |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Test whether a specified node is visible in the logical view of a TreeWalker or NodeIterator. This function will be called by the implementation of TreeWalker and NodeIterator; it is not normally called directly from user code. (Though you could do so if you wanted to use the same filter to guide your own application logic.) |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | This method is used to retrieve ECMAScript object Type. |

## Fields

| Name | Description |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Accept the node. Navigation methods defined for NodeIterator or TreeWalker will return this node. |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Reject the node. Navigation methods defined for NodeIterator or TreeWalker will not return this node. For TreeWalker, the children of this node will also be rejected. NodeIterators treat this as a synonym for FILTER_SKIP. |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Skip this single node. Navigation methods defined for NodeIterator or TreeWalker will not return this node. For both NodeIterator and TreeWalker, the children of this node will still be considered. |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | Show all Nodes. |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Show Attr nodes. This is meaningful only when creating an iterator or tree-walker with an attribute node as its root; in this case, it means that the attribute node will appear in the first position of the iteration or traversal. Since attributes are never children of other nodes, they do not appear when traversing over the document tree. |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Show CDATASection nodes. |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Show Comment nodes. |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | Show Document nodes. |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Show DocumentFragment nodes. |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Show DocumentType nodes. |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | Show Element nodes. |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Show Entity nodes. This is meaningful only when creating an iterator or tree-walker with an Entity node as its root; in this case, it means that the Entity node will appear in the first position of the traversal. Since entities are not part of the document tree, they do not appear when traversing over the document tree. |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Show EntityReference nodes. |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Show Notation nodes. This is meaningful only when creating an iterator or tree-walker with a Notation node as its root; in this case, it means that the Notation node will appear in the first position of the traversal. Since notations are not part of the document tree, they do not appear when traversing over the document tree. |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Show ProcessingInstruction nodes. |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | Show Text nodes. |

### See Also

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
