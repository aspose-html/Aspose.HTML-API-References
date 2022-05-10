---
title: Node
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 1110
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
| virtual [Attributes](attributes) { get; } | A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| virtual [BaseURI](baseuri) { get; } | The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
| [ChildNodes](childnodes) { get; } | A NodeList that contains all children of this node. If there are no children, this is a NodeList containing no nodes.. |
| [FirstChild](firstchild) { get; } | The first child of this node. If there is no such node, this returns null. |
| [LastChild](lastchild) { get; } | The last child of this node. If there is no such node, this returns null. |
| virtual [LocalName](localname) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| virtual [NamespaceURI](namespaceuri) { get; } | The namespace URI of this node, or null if it is unspecified. |
| [NextSibling](nextsibling) { get; } | The node immediately following this node. If there is no such node, this returns null. |
| abstract [NodeName](nodename) { get; } | The name of this node, depending on its type. |
| abstract [NodeType](nodetype) { get; } | A code representing the type of the underlying object. |
| virtual [NodeValue](nodevalue) { get; set; } | The value of this node, depending on its type. |
| virtual [OwnerDocument](ownerdocument) { get; } | The Document object associated with this node. This is also the Document object used to create new nodes. When this node is a Document or a DocumentType which is not used with any Document yet, this is null. |
| [ParentElement](parentelement) { get; } | Gets the parent [`Element`](../element) of this node. |
| [ParentNode](parentnode) { get; } | The parent of this node. All nodes, except Attr, Document, DocumentFragment, Entity, and Notation may have a parent. However, if a node has just been created and not yet added to the tree, or if it has been removed from the tree, this is null. |
| virtual [Prefix](prefix) { get; set; } | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [PreviousSibling](previoussibling) { get; } | The node immediately preceding this node. If there is no such node, this returns null. |
| virtual [TextContent](textcontent) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |

## Methods

| Name | Description |
| --- | --- |
| [AppendChild](appendchild)(Node) | Adds the node newChild to the end of the list of children of this node. If the newChild is already in the tree, it is first removed. |
| [CloneNode](clonenode)() | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [CloneNode](clonenode)(bool) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| virtual [HasAttributes](hasattributes)() | Returns whether this node (if it is an element) has any attributes |
| [HasChildNodes](haschildnodes)() | Returns whether this node has any children. |
| [InsertBefore](insertbefore)(Node, Node) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children. If child is a DocumentFragment object, all of its children are inserted, in the same order, before child. If the child is already in the tree, it is first removed. |
| [IsDefaultNamespace](isdefaultnamespace)(string) | This method checks if the specified namespaceURI is the default namespace or not. |
| [IsEqualNode](isequalnode)(Node) | Tests whether two nodes are equal. This method tests for equality of nodes, not sameness (i.e., whether the two nodes are references to the same object) which can be tested with Node.isSameNode(). All nodes that are the same will also be equal, though the reverse may not be true. |
| [IsSameNode](issamenode)(Node) | Returns whether this node is the same node as the given one. This method provides a way to determine whether two Node references returned by the implementation reference the same object. When two Node references are references to the same object, even if through a proxy, the references may be used completely interchangeably, such that all attributes have the same values and calling the same DOM method on either reference always has exactly the same effect. |
| [LookupNamespaceURI](lookupnamespaceuri)(string) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [LookupPrefix](lookupprefix)(string) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. See Namespace Prefix Lookup for details on the algorithm used by this method. |
| [Normalize](normalize)() | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [RemoveChild](removechild)(Node) | Removes the child node indicated by oldChild from the list of children, and returns it. |
| [ReplaceChild](replacechild)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a DocumentFragment object, oldChild is replaced by all of the DocumentFragment children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| override [ToString](tostring)() | Returns a String that represents this instance. |

## Other Members

| Name | Description |
| --- | --- |
| const [ATTRIBUTE_NODE](attribute_node) | An attribute node |
| const [CDATA_SECTION_NODE](cdata_section_node) | A cdata section node |
| const [COMMENT_NODE](comment_node) | A comment node |
| const [DOCUMENT_FRAGMENT_NODE](document_fragment_node) | A document fragment node |
| const [DOCUMENT_NODE](document_node) | A document node |
| const [DOCUMENT_TYPE_NODE](document_type_node) | A document type node |
| const [ELEMENT_NODE](element_node) | An element node |
| const [ENTITY_NODE](entity_node) | An entity node |
| const [ENTITY_REFERENCE_NODE](entity_reference_node) | An entity reference node |
| const [NOTATION_NODE](notation_node) | A notation node |
| const [PROCESSING_INSTRUCTION_NODE](processing_instruction_node) | A processing instruction node |
| const [TEXT_NODE](text_node) | A text node |

### See Also

* class [EventTarget](../eventtarget)
* interface [IXPathNSResolver](../../aspose.html.dom.xpath/ixpathnsresolver)
* namespace [Aspose.Html.Dom](../../aspose.html.dom)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
