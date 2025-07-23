---
title: Node Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Node class. The Node interface is the primary datatype for the entire Document object Model. It represents a single node in the document tree
type: docs
weight: 1160
url: /net/aspose.html.dom/node/
---
## Node class

The Node interface is the primary datatype for the entire Document object Model. It represents a single node in the document tree.

```csharp
public abstract class Node : EventTarget, IXPathNSResolver
```

## Properties

| Name | Description |
| --- | --- |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | Returns the absolute base URL of the document containing the node. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Returns a live [`NodeList`](../../aspose.html.collections/nodelist/) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Returns the node's first child in the tree, or null if the node has no children. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than [`ELEMENT_NODE`](./element_node/) and [`ATTRIBUTE_NODE`](./attribute_node/) and nodes created with a DOM Level 1 method, such as [`CreateElement`](../document/createelement/), this is always null. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | Returns the namespace URI of the element, or null if the element is not in a namespace. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Returns the node immediately following the specified one in their parent's [`ChildNodes`](./childnodes/), or returns null if the specified node is the last child in the parent element. |
| abstract [NodeName](../../aspose.html.dom/node/nodename/) { get; } | Returns the name of the current node as a string. |
| abstract [NodeType](../../aspose.html.dom/node/nodetype/) { get; } | A code representing the type of the underlying object. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Returns or sets the value of the current node. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | Returns the top-level document object of the node. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Returns the DOM node's parent [`Element`](../element/), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Returns the parent of the specified node in the DOM tree. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | Returns the namespace prefix of the specified element, or null if no prefix is specified. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Returns the node immediately preceding the specified one in its parent's [`ChildNodes`](./childnodes/) list, or null if the specified node is the first in that list. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent/) { get; set; } | Represents the text content of the node and its descendants. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.html.dom.events/ieventlistener/)*) | Sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.html.dom.events/domeventhandler/), bool*) | Sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.html.dom.events/ieventlistener/), bool*) | Sets up a function that will be called whenever the specified event is delivered to the target. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(*Node*) | Adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, [`AppendChild`](./appendchild/) moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node). |
| [CloneNode](../../aspose.html.dom/node/clonenode/#clonenode)() | Returns a duplicate of the node on which this method was called. |
| [CloneNode](../../aspose.html.dom/node/clonenode/#clonenode_1)(*bool*) | Returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.html.dom.events/event/)*) | Dispatches an Event at the specified [`IEventTarget`](../../aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`DispatchEvent`](../../aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object Type. |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Returns a boolean value indicating whether the given `Node` has child nodes or not. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(*Node, Node*) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children. If child is a DocumentFragment object, all of its children are inserted, in the same order, before child. If the child is already in the tree, it is first removed. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(*string*) | This method checks if the specified namespaceURI is the default namespace or not. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(*Node*) | Tests whether two nodes are equal. This method tests for equality of nodes, not sameness (i.e., whether the two nodes are references to the same object) which can be tested with Node.isSameNode(). All nodes that are the same will also be equal, though the reverse may not be true. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(*Node*) | Method is a legacy alias the for the === strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(*string*) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(*string*) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. See Namespace Prefix Lookup for details on the algorithm used by this method. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(*Node*) | Removes a child node from the DOM and returns the removed node. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.html.dom.events/ieventlistener/)*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener/) is removed from an [`EventTarget`](../eventtarget/) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.html.dom.events/domeventhandler/), bool*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener/) is removed from an [`EventTarget`](../eventtarget/) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.html.dom.events/ieventlistener/), bool*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener/) is removed from an [`EventTarget`](../eventtarget/) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(*Node, Node*) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a DocumentFragment object, oldChild is replaced by all of the DocumentFragment children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [ATTRIBUTE_NODE](../../aspose.html.dom/node/attribute_node/) | An attribute node |
| const [CDATA_SECTION_NODE](../../aspose.html.dom/node/cdata_section_node/) | A cdata section node |
| const [COMMENT_NODE](../../aspose.html.dom/node/comment_node/) | A comment node |
| const [DOCUMENT_FRAGMENT_NODE](../../aspose.html.dom/node/document_fragment_node/) | A document fragment node |
| const [DOCUMENT_NODE](../../aspose.html.dom/node/document_node/) | A document node |
| const [DOCUMENT_TYPE_NODE](../../aspose.html.dom/node/document_type_node/) | A document type node |
| const [ELEMENT_NODE](../../aspose.html.dom/node/element_node/) | An element node |
| const [ENTITY_NODE](../../aspose.html.dom/node/entity_node/) | An entity node |
| const [ENTITY_REFERENCE_NODE](../../aspose.html.dom/node/entity_reference_node/) | An entity reference node |
| const [NOTATION_NODE](../../aspose.html.dom/node/notation_node/) | A notation node |
| const [PROCESSING_INSTRUCTION_NODE](../../aspose.html.dom/node/processing_instruction_node/) | A processing instruction node |
| const [TEXT_NODE](../../aspose.html.dom/node/text_node/) | A text node |

### See Also

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../aspose.html.dom.xpath/ixpathnsresolver/)
* namespace [Aspose.Html.Dom](../../aspose.html.dom/)
* assembly [Aspose.HTML](../../)
