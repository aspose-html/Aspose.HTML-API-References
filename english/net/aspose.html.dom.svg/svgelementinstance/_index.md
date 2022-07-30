---
title: SVGElementInstance
second_title: Aspose.HTML for .NET API Reference
description: The root object of each use-element shadow tree implements the SVGUseElementShadowRoot interface. This interface does not currently define any extensions to the properties and methods defined for the ShadowRoot interface and DocumentOrShadowRoot mixin. However the tree rooted at this node is entirely read-only from the perspective of author scripts.
type: docs
weight: 2040
url: /net/aspose.html.dom.svg/svgelementinstance/
---
## SVGElementInstance class

The root object of each use-element shadow tree implements the SVGUseElementShadowRoot interface. This interface does not currently define any extensions to the properties and methods defined for the ShadowRoot interface and DocumentOrShadowRoot mixin. However, the tree rooted at this node is entirely read-only from the perspective of author scripts.

```csharp
public class SVGElementInstance : ShadowRoot
```

## Properties

| Name | Description |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes) { get; } | The attributes property returns a live collection of all attribute nodes registered to the specified node. Attributes is a key/value pair of strings that represents any information regarding that attribute. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | The read-only baseURI property of the Node interface returns the absolute base URL of the document containing the node. |
| [ChildElementCount](../../aspose.html.dom/documentfragment/childelementcount) { get; } | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | The read-only childNodes property of the Node interface returns a live [`NodeList`](../../aspose.html.collections/nodelist) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [Children](../../aspose.html.dom/documentfragment/children) { get; } | Returns the child elements of current element. |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | The read-only firstChild property of the [`Node`](../../aspose.html.dom/node) interface returns the node's first child in the tree, or null if the node has no children. |
| [FirstElementChild](../../aspose.html.dom/documentfragment/firstelementchild) { get; } | Returns the first child element node of this element. null if this element has no child elements. |
| [Host](../../aspose.html.dom/shadowroot/host) { get; } | Host is an element which contains this ShadowRoot. |
| [InnerHTML](../../aspose.html.dom/documentfragment/innerhtml) { get; set; } | Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given string. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | The read-only lastChild property of the [`Node`](../../aspose.html.dom/node) interface returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [LastElementChild](../../aspose.html.dom/documentfragment/lastelementchild) { get; } | Returns the last child element node of this element. null if this element has no child elements. |
| virtual [LocalName](../../aspose.html.dom/node/localname) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than [`ELEMENT_NODE`](../../aspose.html.dom/node/element_node) and [`ATTRIBUTE_NODE`](../../aspose.html.dom/node/attribute_node) and nodes created with a DOM Level 1 method, such as [`Document.createElement()`](../../aspose.html.dom/document/createelement), this is always null. |
| [Mode](../../aspose.html.dom/shadowroot/mode) { get; } | Mode in which this ShadowRoot operates. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri) { get; } | The Element.namespaceURI read-only property returns the namespace URI of the element, or null if the element is not in a namespace. |
| [NextElementSibling](../../aspose.html.dom/documentfragment/nextelementsibling) { get; } | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | The read-only nextSibling property of the [`Node`](../../aspose.html.dom/node) interface returns the node immediately following the specified one in their parent's [`childNodes`](../../aspose.html.dom/node/childnodes), or returns null if the specified node is the last child in the parent element. |
| override [NodeName](../../aspose.html.dom/documentfragment/nodename) { get; } | The name of this node, depending on its type. |
| override [NodeType](../../aspose.html.dom/documentfragment/nodetype) { get; } | A code representing the type of the underlying object. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | The nodeValue property of the [`Node `](../../aspose.html.dom/node)interface returns or sets the value of the current node. |
| [OuterHTML](../../aspose.html.dom/documentfragment/outerhtml) { get; set; } | Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given string. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | The read-only ownerDocument property of the Node interface returns the top-level document object of the node. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | The read-only parentElement property of [`Node`](../../aspose.html.dom/node) interface returns the DOM node's parent [`Element`](../../aspose.html.dom/element), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree. |
| virtual [Prefix](../../aspose.html.dom/node/prefix) { get; set; } | The prefix read-only property returns the namespace prefix of the specified element, or null if no prefix is specified. |
| [PreviousElementSibling](../../aspose.html.dom/documentfragment/previouselementsibling) { get; } | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | The read-only previousSibling property of the [`Node`](../../aspose.html.dom/node) interface returns the node immediately preceding the specified one in its parent's [`childNodes`](../../aspose.html.dom/node/firstchild) list, or null if the specified node is the first in that list. |
| override [TextContent](../../aspose.html.dom/documentfragment/textcontent) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | The addEventListener() method of the [`EventTarget `](../../aspose.html.dom/eventtarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | The appendChild() method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node). |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | Dispatches an Event at the specified [`EventTarget`](../../aspose.html.dom.events/ieventtarget), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../aspose.html.dom.events/ieventtarget/dispatchevent). |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | This method is used to retrieve the ECMAScript object . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes)() | The hasAttributes() method of the [`Element`](../../aspose.html.dom/element) interface returns a boolean value indicating whether the current element has any attributes or not. |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | The hasChildNodes() method of the Node interface returns a boolean value indicating whether the given [`Node`](../../aspose.html.dom/node) has child nodes or not. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | The insertBefore() method of the Node interface inserts a node before a reference node as a child of a specified parent node. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | The isDefaultNamespace() method of the Node interface accepts a namespace URI as an argument. It returns a boolean value that is true if the namespace is the default namespace on the given node and false if not. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | The isEqualNode() method of the [`Node`](../../aspose.html.dom/node) interface tests whether two nodes are equal. Two nodes are equal when they have the same type, defining characteristics (for elements, this would be their ID, number of children, and so forth), its attributes match, and so on. The specific set of data points that must match varies depending on the types of the nodes. |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | The isSameNode() method of the Node interface is a legacy alias the for the === strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | The lookupNamespaceURI() method of the Node interface takes a prefix as parameter and returns the namespace URI associated with it on the given node if found (and null if not). |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | The lookupPrefix() method of the Node interface returns a String containing the prefix for a given namespace URI, if present, and null if not. When multiple prefixes are possible, the first prefix is returned. |
| [Normalize](../../aspose.html.dom/node/normalize)() | Puts all [`Text`](../../aspose.html.dom/text) nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., [`elements`](../../aspose.html.dom/element), [`comments`](../../aspose.html.dom/comment), [`processing instructions`](../../aspose.html.dom/processinginstruction), [`CDATA sections`](../../aspose.html.dom/cdatasection), and [`entity references`](../../aspose.html.dom/entityreference)) separates [`Text`](../../aspose.html.dom/text) nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the [`DOMConfiguration`](../../aspose.html/configuration) object attached to the [`Node.ownerDocument`](../../aspose.html.dom/node/ownerdocument) is true, this method will also fully normalize the characters of the Text nodes. |
| [QuerySelector](../../aspose.html.dom/documentfragment/queryselector)(string) | Returns the first Element in document, which match selector |
| [QuerySelectorAll](../../aspose.html.dom/documentfragment/queryselectorall)(string) | Returns a NodeList of all the Elements in document, which match selector |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | The removeChild() method of the Node interface removes a child node from the DOM and returns the removed node. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a [`DocumentFragment`](../../aspose.html.dom/documentfragment) object, oldChild is replaced by all of the [`DocumentFragment`](../../aspose.html.dom/documentfragment) children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| override [ToString](../../aspose.html.dom/node/tostring)() | Returns a String that represents this instance. |

### See Also

* class [ShadowRoot](../../aspose.html.dom/shadowroot)
* namespace [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
