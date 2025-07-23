---
title: SVGElement Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Svg.SVGElement class. All of the SVG DOM interfaces that correspond directly to elements in the SVG language such as the SVGPathElement interface for the path element derive from the SVGElement interface
type: docs
weight: 2190
url: /net/aspose.html.dom.svg/svgelement/
---
## SVGElement class

All of the SVG DOM interfaces that correspond directly to elements in the SVG language (such as the SVGPathElement interface for the ‘path’ element) derive from the SVGElement interface.

```csharp
public class SVGElement : Element, IElementCSSInlineStyle
```

## Properties

| Name | Description |
| --- | --- |
| [Attributes](../../aspose.html.dom/element/attributes/) { get; } | A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | Returns the absolute base URL of the document containing the node. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount/) { get; } | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Returns a live [`NodeList`](../../aspose.html.collections/nodelist/) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [Children](../../aspose.html.dom/element/children/) { get; } | Returns the child elements of current element. |
| [ClassList](../../aspose.html.dom/element/classlist/) { get; } | Returns a live DOMTokenList which contains tokens received from parsing the "class" attribute. |
| [ClassName](../../aspose.html.dom.svg/svgelement/classname/) { get; } | Corresponds to attribute ‘class’ on the given element. |
| [ClassName](../../aspose.html.dom/element/classname/) { get; set; } | The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Returns the node's first child in the tree, or null if the node has no children. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | Returns the first child element node of this element. null if this element has no child elements. |
| [Id](../../aspose.html.dom.svg/svgelement/id/) { get; set; } | The value of the ‘id’ attribute on the given element, or the empty string if ‘id’ is not present. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given string. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | Returns the last child element node of this element. null if this element has no child elements. |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | The namespace URI of this node, or null if it is unspecified. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Returns the node immediately following the specified one in their parent's [`ChildNodes`](../../aspose.html.dom/node/childnodes/), or returns null if the specified node is the last child in the parent element. |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | The name of this node, depending on its type. |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | A code representing the type of the underlying object. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Returns or sets the value of the current node. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given string. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | Returns the top-level document object of the node. |
| [OwnerSVGElement](../../aspose.html.dom.svg/svgelement/ownersvgelement/) { get; } | The nearest ancestor ‘svg’ element. Null if the given element is the outermost svg element. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Returns the DOM node's parent [`Element`](../../aspose.html.dom/element/), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Returns the parent of the specified node in the DOM tree. |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Returns the node immediately preceding the specified one in its parent's [`ChildNodes`](../../aspose.html.dom/node/childnodes/) list, or null if the specified node is the first in that list. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | Returns shadowRoot stored on this element or null if it's closed. |
| [Style](../../aspose.html.dom.svg/svgelement/style/) { get; } | Corresponds to attribute ‘style’ on the given element. If the user agent does not support styling with CSS, then this attribute must always have the value of null. |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | The name of the element. |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement/) { get; } | The element which established the current viewport. Often, the nearest ancestor ‘svg’ element. Null if the given element is the outermost svg element. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.html.dom.events/ieventlistener/)*) | Sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.html.dom.events/domeventhandler/), bool*) | Sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.html.dom.events/ieventlistener/), bool*) | Sets up a function that will be called whenever the specified event is delivered to the target. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(*[Node](../../aspose.html.dom/node/)*) | Adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, [`AppendChild`](../../aspose.html.dom/node/appendchild/) moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node). |
| [AttachShadow](../../aspose.html.dom/element/attachshadow/)(*[ShadowRootMode](../../aspose.html.dom/shadowrootmode/)*) | Creates shadow root and attaches it to current element. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Returns a duplicate of the node on which this method was called. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(*bool*) | Returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.html.dom.events/event/)*) | Dispatches an Event at the specified [`IEventTarget`](../../aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`DispatchEvent`](../../aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [GetAttribute](../../aspose.html.dom/element/getattribute/)(*string*) | Retrieves an attribute value by name. |
| [GetAttributeNames](../../aspose.html.dom/element/getattributenames/)() | Returns the attribute names of the element as an Array of strings. If the element has no attributes it returns an empty array. |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode/)(*string*) | Retrieves an attribute node by name. |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens/)(*string, string*) | Retrieves an Attr node by local name and namespace URI. |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens/)(*string, string*) | Retrieves an attribute value by local name and namespace URI. |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(*string*) | Returns [`HTMLCollection`](../../aspose.html.collections/htmlcollection/) object containing all the elements within [`element`](../../aspose.html.dom/element/) that have all the classes specified in argument. |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(*string*) | Returns [`HTMLCollection`](../../aspose.html.collections/htmlcollection/) object containing all [`elements`](../../aspose.html.dom/element/) with a given tag name, in document order. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(*string, string*) | Returns [`HTMLCollection`](../../aspose.html.collections/htmlcollection/) object containing all [`elements`](../../aspose.html.dom/element/) with a given local name and namespace URI string in document order. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object Type. |
| [HasAttribute](../../aspose.html.dom/element/hasattribute/)(*string*) | Returns true when an attribute with a given name is specified on this element or has a default value, false otherwise. |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens/)(*string, string*) | Returns true when an attribute with a given local name and namespace URI is specified on this element or has a default value, false otherwise. |
| [HasAttributes](../../aspose.html.dom/element/hasattributes/)() | Returns whether this node (if it is an element) has any attributes |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Returns a boolean value indicating whether the given [`Node`](../../aspose.html.dom/node/) has child nodes or not. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(*[Node](../../aspose.html.dom/node/), [Node](../../aspose.html.dom/node/)*) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children. If child is a DocumentFragment object, all of its children are inserted, in the same order, before child. If the child is already in the tree, it is first removed. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(*string*) | This method checks if the specified namespaceURI is the default namespace or not. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(*[Node](../../aspose.html.dom/node/)*) | Tests whether two nodes are equal. This method tests for equality of nodes, not sameness (i.e., whether the two nodes are references to the same object) which can be tested with Node.isSameNode(). All nodes that are the same will also be equal, though the reverse may not be true. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(*[Node](../../aspose.html.dom/node/)*) | Method is a legacy alias the for the === strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(*string*) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(*string*) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. See Namespace Prefix Lookup for details on the algorithm used by this method. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [QuerySelector](../../aspose.html.dom/element/queryselector/)(*string*) | Returns the first Element in document, which match selector |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall/)(*string*) | Returns a NodeList of all the Elements in document, which match selector |
| [Remove](../../aspose.html.dom/element/remove/)() | Removes this instance. |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute/)(*string*) | Removes an attribute by name. |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode/)(*[Attr](../../aspose.html.dom/attr/)*) | Removes the specified attribute node. |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens/)(*string, string*) | Removes an attribute by local name and namespace URI. |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(*[Node](../../aspose.html.dom/node/)*) | Removes a child node from the DOM and returns the removed node. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.html.dom.events/ieventlistener/)*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener/) is removed from an [`EventTarget`](../../aspose.html.dom/eventtarget/) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.html.dom.events/domeventhandler/), bool*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener/) is removed from an [`EventTarget`](../../aspose.html.dom/eventtarget/) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.html.dom.events/ieventlistener/), bool*) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener/) is removed from an [`EventTarget`](../../aspose.html.dom/eventtarget/) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(*[Node](../../aspose.html.dom/node/), [Node](../../aspose.html.dom/node/)*) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a DocumentFragment object, oldChild is replaced by all of the DocumentFragment children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [SetAttribute](../../aspose.html.dom/element/setattribute/)(*string, string*) | Adds a new attribute. If an attribute with that name is already present in the element, its value is changed to be that of the value parameter |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode/)(*[Attr](../../aspose.html.dom/attr/)*) | Adds a new attribute node. If an attribute with that name (nodeName) is already present in the element, it is replaced by the new one. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens/)(*[Attr](../../aspose.html.dom/attr/)*) | Adds a new attribute. If an attribute with that local name and that namespace URI is already present in the element, it is replaced by the new one. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens/)(*string, string, string*) | Adds a new attribute. If an attribute with the same local name and namespace URI is already present on the element, its prefix is changed to be the prefix part of the qualifiedName, and its value is changed to be the value parameter. |
| [ToggleAttribute](../../aspose.html.dom/element/toggleattribute/)(*string*) | If force is not given, "toggles" qualifiedName, removing it if it is present and adding it if it is not present. If force is true, adds qualifiedName. If force is false, removes qualifiedName. |
| [ToggleAttribute](../../aspose.html.dom/element/toggleattribute/)(*string, bool*) | If force is not given, "toggles" qualifiedName, removing it if it is present and adding it if it is not present. If force is true, adds qualifiedName. If force is false, removes qualifiedName. |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Returns a String that represents this instance. |

### See Also

* class [Element](../../aspose.html.dom/element/)
* interface [IElementCSSInlineStyle](../../aspose.html.dom.css/ielementcssinlinestyle/)
* namespace [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* assembly [Aspose.HTML](../../)
