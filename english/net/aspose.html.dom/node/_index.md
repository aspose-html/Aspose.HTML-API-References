---
title: Node
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 1110
url: /net/aspose.html.dom/node/
---
## Node class

The Node interface is the primary datatype for the entire Document Object Model. It represents a single node in the document tree. While all objects implementing the Node interface expose methods for dealing with children, not all objects implementing the Node interface may have children. For example, [`Text`](../text) nodes may not have children, and adding children to such nodes results in a [`DOMException`](../domexception) being raised.

The attributes [`nodeName`](./nodename), [`nodeValue`](./nodevalue) and attributes are included as a mechanism to get at node information without casting down to the specific derived interface. In cases where there is no obvious mapping of these attributes for a specific [`nodeType`](./nodetype) (e.g., nodeValue for an [`Element`](../element) or attributes for a [`Comment`](../comment)), this returns null. Note that the specialized interfaces may contain additional and more convenient mechanisms to get and set the relevant information.

```csharp
public abstract class Node : EventTarget, IXPathNSResolver
```

## Properties

| Name | Description |
| --- | --- |
| virtual [Attributes](attributes) { get; } | The attributes property returns a live collection of all attribute nodes registered to the specified node. Attributes is a key/value pair of strings that represents any information regarding that attribute. |
| virtual [BaseURI](baseuri) { get; } | The read-only baseURI property of the Node interface returns the absolute base URL of the document containing the node. |
| [ChildNodes](childnodes) { get; } | The read-only childNodes property of the Node interface returns a live [`NodeList`](../../aspose.html.collections/nodelist) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [FirstChild](firstchild) { get; } | The read-only firstChild property of the [`Node`](../node) interface returns the node's first child in the tree, or null if the node has no children. |
| [LastChild](lastchild) { get; } | The read-only lastChild property of the [`Node`](../node) interface returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| virtual [LocalName](localname) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than [`ELEMENT_NODE`](./element_node) and [`ATTRIBUTE_NODE`](./attribute_node) and nodes created with a DOM Level 1 method, such as [`Document.createElement()`](../document/createelement), this is always null. |
| virtual [NamespaceURI](namespaceuri) { get; } | The Element.namespaceURI read-only property returns the namespace URI of the element, or null if the element is not in a namespace. |
| [NextSibling](nextsibling) { get; } | The read-only nextSibling property of the [`Node`](../node) interface returns the node immediately following the specified one in their parent's [`childNodes`](./childnodes), or returns null if the specified node is the last child in the parent element. |
| abstract [NodeName](nodename) { get; } | The read-only nodeName property of Node returns the name of the current node as a string. |
| abstract [NodeType](nodetype) { get; } | A code representing the type of the underlying object. |
| virtual [NodeValue](nodevalue) { get; set; } | The nodeValue property of the [`Node `](../node)interface returns or sets the value of the current node. |
| virtual [OwnerDocument](ownerdocument) { get; } | The read-only ownerDocument property of the Node interface returns the top-level document object of the node. |
| [ParentElement](parentelement) { get; } | The read-only parentElement property of [`Node`](../node) interface returns the DOM node's parent [`Element`](../element), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [ParentNode](parentnode) { get; } | The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree. |
| virtual [Prefix](prefix) { get; set; } | The prefix read-only property returns the namespace prefix of the specified element, or null if no prefix is specified. |
| [PreviousSibling](previoussibling) { get; } | The read-only previousSibling property of the [`Node`](../node) interface returns the node immediately preceding the specified one in its parent's [`childNodes`](./firstchild) list, or null if the specified node is the first in that list. |
| virtual [TextContent](textcontent) { get; set; } | The textContent property of the [`Node`](../node) interface represents the text content of the node and its descendants. |

## Methods

| Name | Description |
| --- | --- |
| [AppendChild](appendchild)(Node) | The appendChild() method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node). |
| [CloneNode](clonenode)() | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [CloneNode](clonenode)(bool) | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| virtual [HasAttributes](hasattributes)() | The hasAttributes() method of the [`Element`](../element) interface returns a boolean value indicating whether the current element has any attributes or not. |
| [HasChildNodes](haschildnodes)() | The hasChildNodes() method of the Node interface returns a boolean value indicating whether the given [`Node`](../node) has child nodes or not. |
| [InsertBefore](insertbefore)(Node, Node) | The insertBefore() method of the Node interface inserts a node before a reference node as a child of a specified parent node. |
| [IsDefaultNamespace](isdefaultnamespace)(string) | The isDefaultNamespace() method of the Node interface accepts a namespace URI as an argument. It returns a boolean value that is true if the namespace is the default namespace on the given node and false if not. |
| [IsEqualNode](isequalnode)(Node) | The isEqualNode() method of the [`Node`](../node) interface tests whether two nodes are equal. Two nodes are equal when they have the same type, defining characteristics (for elements, this would be their ID, number of children, and so forth), its attributes match, and so on. The specific set of data points that must match varies depending on the types of the nodes. |
| [IsSameNode](issamenode)(Node) | The isSameNode() method of the Node interface is a legacy alias the for the === strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [LookupNamespaceURI](lookupnamespaceuri)(string) | The lookupNamespaceURI() method of the Node interface takes a prefix as parameter and returns the namespace URI associated with it on the given node if found (and null if not). |
| [LookupPrefix](lookupprefix)(string) | The lookupPrefix() method of the Node interface returns a String containing the prefix for a given namespace URI, if present, and null if not. When multiple prefixes are possible, the first prefix is returned. |
| [Normalize](normalize)() | Puts all [`Text`](../text) nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., [`elements`](../element), [`comments`](../comment), [`processing instructions`](../processinginstruction), [`CDATA sections`](../cdatasection), and [`entity references`](../entityreference)) separates [`Text`](../text) nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the [`DOMConfiguration`](../../aspose.html/configuration) object attached to the [`Node.ownerDocument`](./ownerdocument) is true, this method will also fully normalize the characters of the Text nodes. |
| [RemoveChild](removechild)(Node) | The removeChild() method of the Node interface removes a child node from the DOM and returns the removed node. |
| [ReplaceChild](replacechild)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a [`DocumentFragment`](../documentfragment) object, oldChild is replaced by all of the [`DocumentFragment`](../documentfragment) children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| override [ToString](tostring)() | Returns a String that represents this instance. |

## Other Members

| Name | Description |
| --- | --- |
| const [ATTRIBUTE_NODE](attribute_node) | An [`Attribute`](../attr) of an [`Element`](../element). |
| const [CDATA_SECTION_NODE](cdata_section_node) | A [`CDATASection`](../cdatasection), such as &lt;!CDATA[[ … ]]&gt;. |
| const [COMMENT_NODE](comment_node) | A [`Comment`](../comment) node, such as &lt;!-- … --&gt;. |
| const [DOCUMENT_FRAGMENT_NODE](document_fragment_node) | A [`DocumentFragment`](../documentfragment) node. |
| const [DOCUMENT_NODE](document_node) | A [`Document`](../document) node. |
| const [DOCUMENT_TYPE_NODE](document_type_node) | A [`DocumentType`](../documenttype) node, such as &lt;!DOCTYPE html&gt;. |
| const [ELEMENT_NODE](element_node) | An [`Element`](../element) node like &lt;p&gt; or &lt;div&gt;. |
| const [ENTITY_NODE](entity_node) | An [`Entity`](../entity) node. |
| const [ENTITY_REFERENCE_NODE](entity_reference_node) | An [`EntityReference`](../entityreference) node. |
| const [NOTATION_NODE](notation_node) | A [`Notation`](../notation) node |
| const [PROCESSING_INSTRUCTION_NODE](processing_instruction_node) | A [`ProcessingInstruction`](../processinginstruction) of an XML document, such as &lt;?xml-stylesheet … ?&gt;. |
| const [TEXT_NODE](text_node) | The actual [`Text`](../text) inside an [`Element`](../element) or [`Attr`](../attr). |

### Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### See Also

* class [EventTarget](../eventtarget)
* interface [IXPathNSResolver](../../aspose.html.dom.xpath/ixpathnsresolver)
* namespace [Aspose.Html.Dom](../../aspose.html.dom)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->