---
title: Attr
second_title: Aspose.HTML for .NET API Reference
description: The Attr interface represents an attribute in an Element object. Typically the allowable values for the attribute are defined in a schema associated with the document.
type: docs
weight: 230
url: /net/aspose.html.dom/attr/
---
## Attr class

The Attr interface represents an attribute in an Element object. Typically the allowable values for the attribute are defined in a schema associated with the document.

```csharp
public sealed class Attr : Node
```

## Properties

| Name | Description |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes) { get; } | The attributes property returns a live collection of all attribute nodes registered to the specified node. Attributes is a key/value pair of strings that represents any information regarding that attribute. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | The read-only baseURI property of the Node interface returns the absolute base URL of the document containing the node. |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | The read-only childNodes property of the Node interface returns a live [`NodeList`](../../aspose.html.collections/nodelist) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | The read-only firstChild property of the [`Node`](../node) interface returns the node's first child in the tree, or null if the node has no children. |
| [IsId](../../aspose.html.dom/attr/isid) { get; } | Returns whether this attribute is known to be of type ID (i.e. to contain an identifier for its owner element) or not. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | The read-only lastChild property of the [`Node`](../node) interface returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| override [LocalName](../../aspose.html.dom/attr/localname) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| [Name](../../aspose.html.dom/attr/name) { get; } | Returns the name of this attribute. |
| override [NamespaceURI](../../aspose.html.dom/attr/namespaceuri) { get; } | The namespace URI of this node, or null if it is unspecified. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | The read-only nextSibling property of the [`Node`](../node) interface returns the node immediately following the specified one in their parent's [`childNodes`](../node/childnodes), or returns null if the specified node is the last child in the parent element. |
| override [NodeName](../../aspose.html.dom/attr/nodename) { get; } | The name of this node, depending on its type. |
| override [NodeType](../../aspose.html.dom/attr/nodetype) { get; } | A code representing the type of the underlying object. |
| override [NodeValue](../../aspose.html.dom/attr/nodevalue) { get; set; } | The value of this node, depending on its type. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | The read-only ownerDocument property of the Node interface returns the top-level document object of the node. |
| [OwnerElement](../../aspose.html.dom/attr/ownerelement) { get; } | The Element node this attribute is attached to or null if this attribute is not in use. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | The read-only parentElement property of [`Node`](../node) interface returns the DOM node's parent [`Element`](../element), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree. |
| override [Prefix](../../aspose.html.dom/attr/prefix) { get; } | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | The read-only previousSibling property of the [`Node`](../node) interface returns the node immediately preceding the specified one in its parent's [`childNodes`](../node/firstchild) list, or null if the specified node is the first in that list. |
| [SchemaTypeInfo](../../aspose.html.dom/attr/schematypeinfo) { get; } | The type information associated with this attribute. |
| [Specified](../../aspose.html.dom/attr/specified) { get; } | True if this attribute was explicitly given a value in the instance document, false otherwise. |
| override [TextContent](../../aspose.html.dom/attr/textcontent) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [Value](../../aspose.html.dom/attr/value) { get; set; } | On retrieval, the value of the attribute is returned as a string. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | The addEventListener() method of the [`EventTarget `](../eventtarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | The appendChild() method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node). |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | Dispatches an Event at the specified [`EventTarget`](../../aspose.html.dom.events/ieventtarget), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../aspose.html.dom.events/ieventtarget/dispatchevent). |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | This method is used to retrieve the ECMAScript object . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes)() | The hasAttributes() method of the [`Element`](../element) interface returns a boolean value indicating whether the current element has any attributes or not. |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | The hasChildNodes() method of the Node interface returns a boolean value indicating whether the given [`Node`](../node) has child nodes or not. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | The insertBefore() method of the Node interface inserts a node before a reference node as a child of a specified parent node. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | The isDefaultNamespace() method of the Node interface accepts a namespace URI as an argument. It returns a boolean value that is true if the namespace is the default namespace on the given node and false if not. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | The isEqualNode() method of the [`Node`](../node) interface tests whether two nodes are equal. Two nodes are equal when they have the same type, defining characteristics (for elements, this would be their ID, number of children, and so forth), its attributes match, and so on. The specific set of data points that must match varies depending on the types of the nodes. |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | The isSameNode() method of the Node interface is a legacy alias the for the === strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | The lookupNamespaceURI() method of the Node interface takes a prefix as parameter and returns the namespace URI associated with it on the given node if found (and null if not). |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | The lookupPrefix() method of the Node interface returns a String containing the prefix for a given namespace URI, if present, and null if not. When multiple prefixes are possible, the first prefix is returned. |
| [Normalize](../../aspose.html.dom/node/normalize)() | Puts all [`Text`](../text) nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., [`elements`](../element), [`comments`](../comment), [`processing instructions`](../processinginstruction), [`CDATA sections`](../cdatasection), and [`entity references`](../entityreference)) separates [`Text`](../text) nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the [`DOMConfiguration`](../../aspose.html/configuration) object attached to the [`Node.ownerDocument`](../node/ownerdocument) is true, this method will also fully normalize the characters of the Text nodes. |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | The removeChild() method of the Node interface removes a child node from the DOM and returns the removed node. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a [`DocumentFragment`](../documentfragment) object, oldChild is replaced by all of the [`DocumentFragment`](../documentfragment) children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| override [ToString](../../aspose.html.dom/node/tostring)() | Returns a String that represents this instance. |

### See Also

* class [Node](../node)
* namespace [Aspose.Html.Dom](../../aspose.html.dom)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
