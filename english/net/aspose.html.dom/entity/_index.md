---
title: Entity
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 810
url: /net/aspose.html.dom/entity/
---
## Entity class

Represents a known entity, either parsed or unparsed, in an XML document.

```csharp
public class Entity : Node
```

## Properties

| Name | Description |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes) { get; } | A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | A NodeList that contains all children of this node. If there are no children, this is a NodeList containing no nodes.. |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | The first child of this node. If there is no such node, this returns null. |
| [InputEncoding](../../aspose.html.dom/entity/inputencoding) { get; } | An attribute specifying the encoding used for this entity at the time of parsing, when it is an external parsed entity. This is null if it an entity from the internal subset or if it is not known. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | The last child of this node. If there is no such node, this returns null. |
| virtual [LocalName](../../aspose.html.dom/node/localname) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri) { get; } | The namespace URI of this node, or null if it is unspecified. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | The node immediately following this node. If there is no such node, this returns null. |
| override [NodeName](../../aspose.html.dom/entity/nodename) { get; } | The name of this node, depending on its type. |
| override [NodeType](../../aspose.html.dom/entity/nodetype) { get; } | A code representing the type of the underlying object. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | The value of this node, depending on its type. |
| [NotationName](../../aspose.html.dom/entity/notationname) { get; } | For unparsed entities, the name of the notation for the entity. For parsed entities, this is null. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | The Document object associated with this node. This is also the Document object used to create new nodes. When this node is a Document or a DocumentType which is not used with any Document yet, this is null. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | Gets the parent [`Element`](../element) of this node. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | The parent of this node. All nodes, except Attr, Document, DocumentFragment, Entity, and Notation may have a parent. However, if a node has just been created and not yet added to the tree, or if it has been removed from the tree, this is null. |
| virtual [Prefix](../../aspose.html.dom/node/prefix) { get; set; } | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | The node immediately preceding this node. If there is no such node, this returns null. |
| [PublicId](../../aspose.html.dom/entity/publicid) { get; } | The public identifier associated with the entity if specified, and null otherwise. |
| [SystemId](../../aspose.html.dom/entity/systemid) { get; } | The system identifier associated with the entity if specified, and null otherwise. This may be an absolute URI or not. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [XmlEncoding](../../aspose.html.dom/entity/xmlencoding) { get; } | An attribute specifying, as part of the text declaration, the encoding of this entity, when it is an external parsed entity. This is null otherwise. |
| [XmlVersion](../../aspose.html.dom/entity/xmlversion) { get; } | An attribute specifying, as part of the text declaration, the version number of this entity, when it is an external parsed entity. This is null otherwise. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | This method allows the registration of event listeners on the event target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | This method allows the registration of event listeners on the event target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | This method allows the registration of event listeners on the event target. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | Adds the node newChild to the end of the list of children of this node. If the newChild is already in the tree, it is first removed. |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | This method allows the dispatch of events into the implementations event model. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | This method is used to retrieve ECMAScript object Type. |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes)() | Returns whether this node (if it is an element) has any attributes |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | Returns whether this node has any children. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children. If child is a DocumentFragment object, all of its children are inserted, in the same order, before child. If the child is already in the tree, it is first removed. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | This method checks if the specified namespaceURI is the default namespace or not. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | Tests whether two nodes are equal. This method tests for equality of nodes, not sameness (i.e., whether the two nodes are references to the same object) which can be tested with Node.isSameNode(). All nodes that are the same will also be equal, though the reverse may not be true. |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | Returns whether this node is the same node as the given one. This method provides a way to determine whether two Node references returned by the implementation reference the same object. When two Node references are references to the same object, even if through a proxy, the references may be used completely interchangeably, such that all attributes have the same values and calling the same DOM method on either reference always has exactly the same effect. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. See Namespace Prefix Lookup for details on the algorithm used by this method. |
| [Normalize](../../aspose.html.dom/node/normalize)() | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | Removes the child node indicated by oldChild from the list of children, and returns it. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](../eventtarget) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](../eventtarget) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](../eventtarget) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a DocumentFragment object, oldChild is replaced by all of the DocumentFragment children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| override [ToString](../../aspose.html.dom/node/tostring)() | Returns a String that represents this instance. |

### See Also

* class [Node](../node)
* namespace [Aspose.Html.Dom](../../aspose.html.dom)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
