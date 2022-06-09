---
title: CDATASection
second_title: Aspose.HTML for .NET API Reference
description: CDATA sections are used to escape blocks of text containing characters that would otherwise be regarded as markup.
type: docs
weight: 310
url: /net/aspose.html.dom/cdatasection/
---
## CDATASection class

CDATA sections are used to escape blocks of text containing characters that would otherwise be regarded as markup.

```csharp
public class CDATASection : Text
```

## Properties

| Name | Description |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes) { get; } | The attributes property returns a live collection of all attribute nodes registered to the specified node. Attributes is a key/value pair of strings that represents any information regarding that attribute. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | The read-only baseURI property of the Node interface returns the absolute base URL of the document containing the node. |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | The read-only childNodes property of the Node interface returns a live [`NodeList`](../../aspose.html.collections/nodelist) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| virtual [Data](../../aspose.html.dom/characterdata/data) { get; set; } | The character data of the node that implements this interface. |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | The read-only firstChild property of the [`Node`](../node) interface returns the node's first child in the tree, or null if the node has no children. |
| [IsElementContentWhitespace](../../aspose.html.dom/text/iselementcontentwhitespace) { get; } | Returns whether this text node contains element content whitespace, often abusively called "ignorable whitespace". |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | The read-only lastChild property of the [`Node`](../node) interface returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [Length](../../aspose.html.dom/characterdata/length) { get; } | The number of 16-bit units that are available through data and the substringData method below. This may have the value zero, i.e., CharacterData nodes may be empty. |
| virtual [LocalName](../../aspose.html.dom/node/localname) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than [`ELEMENT_NODE`](../node/element_node) and [`ATTRIBUTE_NODE`](../node/attribute_node) and nodes created with a DOM Level 1 method, such as [`Document.createElement()`](../document/createelement), this is always null. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri) { get; } | The Element.namespaceURI read-only property returns the namespace URI of the element, or null if the element is not in a namespace. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | The read-only nextSibling property of the [`Node`](../node) interface returns the node immediately following the specified one in their parent's [`childNodes`](../node/childnodes), or returns null if the specified node is the last child in the parent element. |
| override [NodeName](../../aspose.html.dom/cdatasection/nodename) { get; } | The name of this node, depending on its type. |
| override [NodeType](../../aspose.html.dom/cdatasection/nodetype) { get; } | A code representing the type of the underlying object. |
| override [NodeValue](../../aspose.html.dom/text/nodevalue) { get; set; } | The value of this node, depending on its type. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | The read-only ownerDocument property of the Node interface returns the top-level document object of the node. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | The read-only parentElement property of [`Node`](../node) interface returns the DOM node's parent [`Element`](../element), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree. |
| virtual [Prefix](../../aspose.html.dom/node/prefix) { get; set; } | The prefix read-only property returns the namespace prefix of the specified element, or null if no prefix is specified. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | The read-only previousSibling property of the [`Node`](../node) interface returns the node immediately preceding the specified one in its parent's [`childNodes`](../node/firstchild) list, or null if the specified node is the first in that list. |
| override [TextContent](../../aspose.html.dom/text/textcontent) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [WholeText](../../aspose.html.dom/text/wholetext) { get; } | Returns all text of Text nodes logically-adjacent text nodes to this node, concatenated in document order. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | The addEventListener() method of the [`EventTarget `](../eventtarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | The appendChild() method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node). |
| virtual [AppendData](../../aspose.html.dom/characterdata/appenddata)(string) | Append the string to the end of the character data of the node. |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| virtual [DeleteData](../../aspose.html.dom/characterdata/deletedata)(int, int) | Remove a range of 16-bit units from the node. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | Dispatches an Event at the specified [`EventTarget`](../../aspose.html.dom.events/ieventtarget), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../aspose.html.dom.events/ieventtarget/dispatchevent). |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | This method is used to retrieve the ECMAScript object . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes)() | The hasAttributes() method of the [`Element`](../element) interface returns a boolean value indicating whether the current element has any attributes or not. |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | The hasChildNodes() method of the Node interface returns a boolean value indicating whether the given [`Node`](../node) has child nodes or not. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | The insertBefore() method of the Node interface inserts a node before a reference node as a child of a specified parent node. |
| virtual [InsertData](../../aspose.html.dom/characterdata/insertdata)(int, string) | Insert a string at the specified 16-bit unit offset. |
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
| virtual [ReplaceData](../../aspose.html.dom/characterdata/replacedata)(int, int, string) | Replace the characters starting at the specified 16-bit unit offset with the specified string. |
| [ReplaceWholeText](../../aspose.html.dom/text/replacewholetext)(string) | Replaces the text of the current node and all logically-adjacent text nodes with the specified text. All logically-adjacent text nodes are removed including the current node unless it was the recipient of the replacement text. |
| [SplitText](../../aspose.html.dom/text/splittext)(int) | Breaks this node into two nodes at the specified offset, keeping both in the tree as siblings. |
| virtual [SubstringData](../../aspose.html.dom/characterdata/substringdata)(int, int) | Extracts a range of data from the node. |
| override [ToString](../../aspose.html.dom/characterdata/tostring)() | Returns a String that represents this instance. |

### See Also

* class [Text](../text)
* namespace [Aspose.Html.Dom](../../aspose.html.dom)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
