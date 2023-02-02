---
title: HTMLDivElement
second_title: Aspose.HTML for .NET API Reference
description: Generic block container. See the DIV element definition in HTML 4.01.
type: docs
weight: 3180
url: /net/aspose.html/htmldivelement/
---
## HTMLDivElement class

Generic block container. See the DIV element definition in HTML 4.01.

See also the [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```csharp
public class HTMLDivElement : HTMLElement
```

## Properties

| Name | Description |
| --- | --- |
| [Align](../../aspose.html/htmldivelement/align/) { get; set; } | Horizontal text alignment. See the align attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
| override [Attributes](../../aspose.html.dom/element/attributes/) { get; } | A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | The read-only baseURI property of the Node interface returns the absolute base URL of the document containing the node. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount/) { get; } | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | The read-only childNodes property of the Node interface returns a live [`NodeList`](../../aspose.html.collections/nodelist/) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [Children](../../aspose.html.dom/element/children/) { get; } | Returns the child elements of current element. |
| [ClassList](../../aspose.html.dom/element/classlist/) { get; } | Returns a live DOMTokenList which contains tokens received from parsing the "class" attribute. |
| [ClassName](../../aspose.html/htmlelement/classname/) { get; set; } | The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [Dir](../../aspose.html/htmlelement/dir/) { get; set; } | Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | The read-only firstChild property of the [`Node`](../../aspose.html.dom/node/) interface returns the node's first child in the tree, or null if the node has no children. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | Returns the first child element node of this element. null if this element has no child elements. |
| [Id](../../aspose.html/htmlelement/id/) { get; set; } | The element's identifier. See the id attribute definition in HTML 4.01. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given string. |
| [Lang](../../aspose.html/htmlelement/lang/) { get; set; } | Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | The read-only lastChild property of the [`Node`](../../aspose.html.dom/node/) interface returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | Returns the last child element node of this element. null if this element has no child elements. |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | The namespace URI of this node, or null if it is unspecified. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | The read-only nextSibling property of the [`Node`](../../aspose.html.dom/node/) interface returns the node immediately following the specified one in their parent's [`childNodes`](../../aspose.html.dom/node/childnodes/), or returns null if the specified node is the last child in the parent element. |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | The name of this node, depending on its type. |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | A code representing the type of the underlying object. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | The nodeValue property of the [`Node `](../../aspose.html.dom/node/)interface returns or sets the value of the current node. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given string. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | The read-only ownerDocument property of the Node interface returns the top-level document object of the node. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | The read-only parentElement property of [`Node`](../../aspose.html.dom/node/) interface returns the DOM node's parent [`Element`](../../aspose.html.dom/element/), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree. |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | The read-only previousSibling property of the [`Node`](../../aspose.html.dom/node/) interface returns the node immediately preceding the specified one in its parent's [`childNodes`](../../aspose.html.dom/node/firstchild/) list, or null if the specified node is the first in that list. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo/) { get; } | The type information associated with this element. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | Returns shadowRoot stored on this element or null if it's closed. |
| [Style](../../aspose.html/htmlelement/style/) { get; } | Represents a style attribute that allows author to directly apply style information to specific element. |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | The name of the element. |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [Title](../../aspose.html/htmlelement/title/) { get; set; } | The element's advisory title. See the title attribute definition in HTML 4.01. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | The addEventListener() method of the [`EventTarget `](../../aspose.html.dom/eventtarget/)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | The appendChild() method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node). |
| [AttachShadow](../../aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Creates shadow root and attaches it to current element. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Dispatches an Event at the specified [`EventTarget`](../../aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [GetAttribute](../../aspose.html.dom/element/getattribute/)(string) | Retrieves an attribute value by name. |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode/)(string) | Retrieves an attribute node by name. |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens/)(string, string) | Retrieves an Attr node by local name and namespace URI. |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens/)(string, string) | Retrieves an attribute value by local name and namespace URI. |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | Returns [`HTMLCollection`](../../aspose.html.collections/htmlcollection/) object containing all the elements within [`element`](../../aspose.html.dom/element/) that have all the classes specified in argument. |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | Returns [`HTMLCollection`](../../aspose.html.collections/htmlcollection/) object containing all [`elements`](../../aspose.html.dom/element/) with a given tag name, in document order. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | Returns [`HTMLCollection`](../../aspose.html.collections/htmlcollection/) object containing all [`elements`](../../aspose.html.dom/element/) with a given local name and namespace URI string in document order. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [HasAttribute](../../aspose.html.dom/element/hasattribute/)(string) | Returns true when an attribute with a given name is specified on this element or has a default value, false otherwise. |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens/)(string, string) | Returns true when an attribute with a given local name and namespace URI is specified on this element or has a default value, false otherwise. |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes/)() | Returns whether this node (if it is an element) has any attributes |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | The hasChildNodes() method of the Node interface returns a boolean value indicating whether the given [`Node`](../../aspose.html.dom/node/) has child nodes or not. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | The insertBefore() method of the Node interface inserts a node before a reference node as a child of a specified parent node. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | The isDefaultNamespace() method of the Node interface accepts a namespace URI as an argument. It returns a boolean value that is true if the namespace is the default namespace on the given node and false if not. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | The isEqualNode() method of the [`Node`](../../aspose.html.dom/node/) interface tests whether two nodes are equal. Two nodes are equal when they have the same type, defining characteristics (for elements, this would be their ID, number of children, and so forth), its attributes match, and so on. The specific set of data points that must match varies depending on the types of the nodes. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | The isSameNode() method of the Node interface is a legacy alias the for the === strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | The lookupNamespaceURI() method of the Node interface takes a prefix as parameter and returns the namespace URI associated with it on the given node if found (and null if not). |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | The lookupPrefix() method of the Node interface returns a String containing the prefix for a given namespace URI, if present, and null if not. When multiple prefixes are possible, the first prefix is returned. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Puts all [`Text`](../../aspose.html.dom/text/) nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., [`elements`](../../aspose.html.dom/element/), [`comments`](../../aspose.html.dom/comment/), [`processing instructions`](../../aspose.html.dom/processinginstruction/), [`CDATA sections`](../../aspose.html.dom/cdatasection/), and [`entity references`](../../aspose.html.dom/entityreference/)) separates [`Text`](../../aspose.html.dom/text/) nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the [`DOMConfiguration`](../configuration/) object attached to the [`Node.ownerDocument`](../../aspose.html.dom/node/ownerdocument/) is true, this method will also fully normalize the characters of the Text nodes. |
| [QuerySelector](../../aspose.html.dom/element/queryselector/)(string) | Returns the first Element in document, which match selector |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall/)(string) | Returns a NodeList of all the Elements in document, which match selector |
| [Remove](../../aspose.html.dom/element/remove/)() | Removes this instance. |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute/)(string) | Removes an attribute by name. |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode/)(Attr) | Removes the specified attribute node. |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens/)(string, string) | Removes an attribute by local name and namespace URI. |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | The removeChild() method of the Node interface removes a child node from the DOM and returns the removed node. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a [`DocumentFragment`](../../aspose.html.dom/documentfragment/) object, oldChild is replaced by all of the [`DocumentFragment`](../../aspose.html.dom/documentfragment/) children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [SetAttribute](../../aspose.html.dom/element/setattribute/)(string, string) | Adds a new attribute. If an attribute with that name is already present in the element, its value is changed to be that of the value parameter |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode/)(Attr) | Adds a new attribute node. If an attribute with that name (nodeName) is already present in the element, it is replaced by the new one. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens/)(Attr) | Adds a new attribute. If an attribute with that local name and that namespace URI is already present in the element, it is replaced by the new one. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens/)(string, string, string) | Adds a new attribute. If an attribute with the same local name and namespace URI is already present on the element, its prefix is changed to be the prefix part of the qualifiedName, and its value is changed to be the value parameter. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute/)(string, bool) | If the parameter isId is true, this method declares the specified attribute to be a user-determined ID attribute. |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode/)(Attr, bool) | If the parameter isId is true, this method declares the specified attribute to be a user-determined ID attribute. |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens/)(string, string, bool) | If the parameter isId is true, this method declares the specified attribute to be a user-determined ID attribute. |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Returns a String that represents this instance. |

## Events

| Name | Description |
| --- | --- |
| event [OnAbort](../../aspose.html/htmlelement/onabort/) | Gets or sets event handler for OnAbort event. |
| event [OnBlur](../../aspose.html/htmlelement/onblur/) | Gets or sets event handler for OnBlur event. |
| event [OnCancel](../../aspose.html/htmlelement/oncancel/) | Gets or sets event handler for OnCancel event. |
| event [OnCanplay](../../aspose.html/htmlelement/oncanplay/) | Gets or sets event handler for OnCanplay event. |
| event [OnCanPlayThrough](../../aspose.html/htmlelement/oncanplaythrough/) | Gets or sets event handler for OnCanPlayThrough event. |
| event [OnChange](../../aspose.html/htmlelement/onchange/) | Gets or sets event handler for OnChange event. |
| event [OnClick](../../aspose.html/htmlelement/onclick/) | Gets or sets event handler for OnClick event. |
| event [OnCueChange](../../aspose.html/htmlelement/oncuechange/) | Gets or sets event handler for OnCueChange event. |
| event [OnDblClick](../../aspose.html/htmlelement/ondblclick/) | Gets or sets event handler for OnDblClick event. |
| event [OnDurationChange](../../aspose.html/htmlelement/ondurationchange/) | Gets or sets event handler for OnDurationChange event. |
| event [OnEmptied](../../aspose.html/htmlelement/onemptied/) | Gets or sets event handler for OnEmptied event. |
| event [OnEnded](../../aspose.html/htmlelement/onended/) | Gets or sets event handler for OnEnded event. |
| event [OnError](../../aspose.html/htmlelement/onerror/) | Gets or sets event handler for OnError event. |
| event [OnFocus](../../aspose.html/htmlelement/onfocus/) | Gets or sets event handler for OnFocus event. |
| event [OnInput](../../aspose.html/htmlelement/oninput/) | Gets or sets event handler for OnInput event. |
| event [OnInvalid](../../aspose.html/htmlelement/oninvalid/) | Gets or sets event handler for OnInvalid event. |
| event [OnKeyDown](../../aspose.html/htmlelement/onkeydown/) | Gets or sets event handler for OnKeyDown event. |
| event [OnKeyPress](../../aspose.html/htmlelement/onkeypress/) | Gets or sets event handler for OnKeyPress event. |
| event [OnKeyUp](../../aspose.html/htmlelement/onkeyup/) | Gets or sets event handler for OnKeyUp event. |
| event [OnLoad](../../aspose.html/htmlelement/onload/) | Gets or sets event handler for OnLoad event. |
| event [OnLoadedData](../../aspose.html/htmlelement/onloadeddata/) | Gets or sets event handler for OnLoadedData event. |
| event [OnLoadedMetadata](../../aspose.html/htmlelement/onloadedmetadata/) | Gets or sets event handler for OnLoadedMetadata event. |
| event [OnLoadStart](../../aspose.html/htmlelement/onloadstart/) | Gets or sets event handler for OnLoadStart event. |
| event [OnMouseDown](../../aspose.html/htmlelement/onmousedown/) | Gets or sets event handler for OnMouseDown event. |
| event [OnMouseEnter](../../aspose.html/htmlelement/onmouseenter/) | Gets or sets event handler for OnMouseEnter event. |
| event [OnMouseLeave](../../aspose.html/htmlelement/onmouseleave/) | Gets or sets event handler for OnMouseLeave event. |
| event [OnMouseMove](../../aspose.html/htmlelement/onmousemove/) | Gets or sets event handler for OnMouseMove event. |
| event [OnMouseOut](../../aspose.html/htmlelement/onmouseout/) | Gets or sets event handler for OnMouseOut event. |
| event [OnMouseOver](../../aspose.html/htmlelement/onmouseover/) | Gets or sets event handler for OnMouseOver event. |
| event [OnMouseUp](../../aspose.html/htmlelement/onmouseup/) | Gets or sets event handler for OnMouseUp event. |
| event [OnMouseWheel](../../aspose.html/htmlelement/onmousewheel/) | Gets or sets event handler for OnMouseWheel event. |
| event [OnPause](../../aspose.html/htmlelement/onpause/) | Gets or sets event handler for OnPause event. |
| event [OnPlay](../../aspose.html/htmlelement/onplay/) | Gets or sets event handler for OnPlay event. |
| event [OnPlaying](../../aspose.html/htmlelement/onplaying/) | Gets or sets event handler for OnPlaying event. |
| event [OnProgress](../../aspose.html/htmlelement/onprogress/) | Gets or sets event handler for OnProgress event. |
| event [OnRateChange](../../aspose.html/htmlelement/onratechange/) | Gets or sets event handler for OnRateChange event. |
| event [OnReset](../../aspose.html/htmlelement/onreset/) | Gets or sets event handler for OnReset event. |
| event [OnResize](../../aspose.html/htmlelement/onresize/) | Gets or sets event handler for OnResize event. |
| event [OnScroll](../../aspose.html/htmlelement/onscroll/) | Gets or sets event handler for OnScroll event. |
| event [OnSeeked](../../aspose.html/htmlelement/onseeked/) | Gets or sets event handler for OnSeeked event. |
| event [OnSeeking](../../aspose.html/htmlelement/onseeking/) | Gets or sets event handler for OnSeeking event. |
| event [OnSelect](../../aspose.html/htmlelement/onselect/) | Gets or sets event handler for OnSelect event. |
| event [OnShow](../../aspose.html/htmlelement/onshow/) | Gets or sets event handler for OnShow event. |
| event [OnStalled](../../aspose.html/htmlelement/onstalled/) | Gets or sets event handler for OnStalled event. |
| event [OnSubmit](../../aspose.html/htmlelement/onsubmit/) | Gets or sets event handler for OnSubmit event. |
| event [OnSuspend](../../aspose.html/htmlelement/onsuspend/) | Gets or sets event handler for OnSuspend event. |
| event [OnTimeUpdate](../../aspose.html/htmlelement/ontimeupdate/) | Gets or sets event handler for OnTimeUpdate event. |
| event [OnToggle](../../aspose.html/htmlelement/ontoggle/) | Gets or sets event handler for OnToggle event. |
| event [OnVolumeChange](../../aspose.html/htmlelement/onvolumechange/) | Gets or sets event handler for OnVolumeChange event. |
| event [OnWaiting](../../aspose.html/htmlelement/onwaiting/) | Gets or sets event handler for OnWaiting event. |

### Examples

```csharp
using System;
using System.IO;
using Aspose.Html;
using Aspose.Html.Dom.Events;
using Aspose.Html.Saving;
...
using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement divElement = (HTMLDivElement)document.CreateElement("div");
	divElement.TextContent = "DIV element content goes here...";
	divElement.Style.TextAlign = "center";
	divElement.Style.Color = "magenta";
	divElement.Id = "original";

	HTMLDivElement clonedDivElement = (HTMLDivElement)divElement.CloneNode(true);
	document.Body.AppendChild(clonedDivElement);
	clonedDivElement.Id = "cloned";

	for (int i = 0; i < 3; i++)
	{
		var newFormedDivElement = document.CreateElement("div");
		newFormedDivElement.TextContent = $"Added in loop {i}";
		clonedDivElement.AppendChild(newFormedDivElement);
	}
         
	document.Body.AppendChild(divElement);
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
    
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### See Also

* class [HTMLElement](../htmlelement/)
* namespace [Aspose.Html](../../aspose.html/)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
