---
title: Document
second_title: Aspose.HTML for .NET API Reference
description: The Document represents the entire HTML XML or SVG document. Conceptually it is the root of the document tree and provides the primary access to the documents data.
type: docs
weight: 660
url: /net/aspose.html.dom/document/
---
## Document class

The Document represents the entire HTML, XML or SVG document. Conceptually, it is the root of the document tree, and provides the primary access to the document's data.

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Properties

| Name | Description |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | The attributes property returns a live collection of all attribute nodes registered to the specified node. Attributes is a key/value pair of strings that represents any information regarding that attribute. |
| override [BaseURI](../../aspose.html.dom/document/baseuri/) { get; } | The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
| [CharacterSet](../../aspose.html.dom/document/characterset/) { get; } | Gets the document's encoding. |
| [Charset](../../aspose.html.dom/document/charset/) { get; } | Gets the document's encoding. |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount/) { get; } | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | The read-only childNodes property of the Node interface returns a live [`NodeList`](../../aspose.html.collections/nodelist/) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [Children](../../aspose.html.dom/document/children/) { get; } | Returns the child elements. |
| [ContentType](../../aspose.html.dom/document/contenttype/) { get; } | Gets the document content type. |
| [Context](../../aspose.html.dom/document/context/) { get; } | Gets the current browsing context. |
| [DefaultView](../../aspose.html.dom/document/defaultview/) { get; } | The defaultView IDL attribute of the Document interface, on getting, must return this Document's browsing context's WindowProxy object, if this Document has an associated browsing context, or null otherwise. |
| [Doctype](../../aspose.html.dom/document/doctype/) { get; } | The Document Type Declaration associated with this document. |
| [DocumentElement](../../aspose.html.dom/document/documentelement/) { get; } | This is a convenience attribute that allows direct access to the child node that is the document element of the document. |
| [DocumentURI](../../aspose.html.dom/document/documenturi/) { get; } | The location of the document or null if undefined or if the Document was created using DOMImplementation.createDocument. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | The read-only firstChild property of the [`Node`](../node/) interface returns the node's first child in the tree, or null if the node has no children. |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild/) { get; } | Returns the first child element node of this element. null if this element has no child elements. |
| [Implementation](../../aspose.html.dom/document/implementation/) { get; } | The DOMImplementation object that handles this document. |
| [InputEncoding](../../aspose.html.dom/document/inputencoding/) { get; } | Gets the document's encoding. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | The read-only lastChild property of the [`Node`](../node/) interface returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild/) { get; } | Returns the last child element node of this element. null if this element has no child elements. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than [`ELEMENT_NODE`](../node/element_node/) and [`ATTRIBUTE_NODE`](../node/attribute_node/) and nodes created with a DOM Level 1 method, such as [`Document.createElement()`](./createelement/), this is always null. |
| [Location](../../aspose.html.dom/document/location/) { get; } | The location of the document. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | The Element.namespaceURI read-only property returns the namespace URI of the element, or null if the element is not in a namespace. |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling/) { get; } | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | The read-only nextSibling property of the [`Node`](../node/) interface returns the node immediately following the specified one in their parent's [`childNodes`](../node/childnodes/), or returns null if the specified node is the last child in the parent element. |
| override [NodeName](../../aspose.html.dom/document/nodename/) { get; } | The name of this node, depending on its type. |
| override [NodeType](../../aspose.html.dom/document/nodetype/) { get; } | A code representing the type of the underlying object. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | The nodeValue property of the [`Node `](../node/)interface returns or sets the value of the current node. |
| [Origin](../../aspose.html.dom/document/origin/) { get; } | Gets the document origin. |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument/) { get; } | Gets the owner document. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | The read-only parentElement property of [`Node`](../node/) interface returns the DOM node's parent [`Element`](../element/), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | The prefix read-only property returns the namespace prefix of the specified element, or null if no prefix is specified. |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling/) { get; } | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | The read-only previousSibling property of the [`Node`](../node/) interface returns the node immediately preceding the specified one in its parent's [`childNodes`](../node/firstchild/) list, or null if the specified node is the first in that list. |
| [ReadyState](../../aspose.html.dom/document/readystate/) { get; } | Returns the document readiness. The "loading" while the Document is loading, "interactive" once it is finished parsing but still loading sub-resources, and "complete" once it has loaded. |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking/) { get; set; } | An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [StyleSheets](../../aspose.html.dom/document/stylesheets/) { get; } | A list containing all the style sheets explicitly linked into or embedded in a document. For HTML documents, this includes external style sheets, included via the HTML LINK element, and inline STYLE elements. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent/) { get; set; } | The textContent property of the [`Node`](../node/) interface represents the text content of the node and its descendants. |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone/) { get; set; } | An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
| [XmlVersion](../../aspose.html.dom/document/xmlversion/) { get; set; } | An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | The addEventListener() method of the [`EventTarget `](../eventtarget/)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | The appendChild() method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node). |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [CreateAttribute](../../aspose.html.dom/document/createattribute/)(string) | The Document.createAttribute() method creates a new attribute node, and returns it. The object created a node implementing the [`Attr`](../attr/) interface. The DOM does not enforce what sort of attributes can be added to a particular element in this manner. |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens/)(string, string) | The Document.createAttribute() method creates a new attribute node, and returns it. The object created a node implementing the [Attr](T:Aspose.Html.Dom.Attr) interface. The DOM does not enforce what sort of attributes can be added to a particular element in this manner. |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection/)(string) | Creates a [`CDATASection`](../cdatasection/) node whose value is the specified string. |
| [CreateComment](../../aspose.html.dom/document/createcomment/)(string) | Creates a [`Comment`](../comment/) node given the specified string. |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment/)() | Creates a new empty [`DocumentFragment`](../documentfragment/) into which DOM nodes can be added to build an offscreen DOM tree. |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype/)(string, string, string, string) | The method returns a [`DocumentType`](../documenttype/) object which can either be used with DOMImplementation.createDocument upon document creation or can be put into the document via methods like Node.insertBefore() or Node.replaceChild(). |
| [CreateElement](../../aspose.html.dom/document/createelement/)(string) | In an HTML document, the document.createElement() method creates the HTML element specified by tagName, or an [`HTMLUnknownElement`](../../aspose.html/htmlunknownelement/) if tagName isn't recognized. |
| [CreateElementNS](../../aspose.html.dom/document/createelementns/)(string, string) | Creates an element of the given qualified name and namespace URI. |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference/)(string) | Creates an EntityReference object. In addition, if the referenced entity is known, the child list of the EntityReference node is made the same as that of the corresponding Entity node. |
| [CreateEvent](../../aspose.html.dom/document/createevent/)(string) | Creates an [`Event`](../../aspose.html.dom.events/event/) of a type supported by the implementation. |
| [CreateExpression](../../aspose.html.dom/document/createexpression/)(string, IXPathNSResolver) | Creates a parsed XPath expression with resolved namespaces. This is useful when an expression will be reused in an application since it makes it possible to compile the expression string into a more efficient internal form and preresolve all namespace prefixes which occur within the expression. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/#createnodeiterator)(Node) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/#createnodeiterator_1)(Node, long) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver/)(Node) | Adapts any DOM node to resolve namespaces so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method `lookupNamespaceURI` on nodes in resolving the namespaceURI from a given prefix using the current information available in the node's hierarchy at the time lookupNamespaceURI is called, also correctly resolving the implicit xml prefix. |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction/)(string, string) | Creates a ProcessingInstruction node given the specified name and data strings. |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode/)(string) | Creates a Text node given the specified string. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/#createtreewalker)(Node) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/#createtreewalker_1)(Node, long) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Dispatches an Event at the specified [`EventTarget`](../../aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [Evaluate](../../aspose.html.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Evaluates an XPath expression string and returns a result of the specified type if possible. |
| [GetElementById](../../aspose.html.dom/document/getelementbyid/)(string) | The Document method getElementById() returns an [`Element`](../element/) object representing the element whose id property matches the specified string. Since element IDs are required to be unique if specified, they're a useful way to get access to a specific element quickly. |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname/)(string) | The getElementsByClassName method of [`Document`](./document/) interface returns an array-like object of all child elements which have all of the given class name(s). |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname/)(string) | The getElementsByTagName method of [`Document`](./document/) interface returns an [`HTMLCollection`](../../aspose.html.collections/htmlcollection/) of elements with the given tag name. |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens/)(string, string) | Returns a list of elements with the given tag name belonging to the given namespace. The complete document is searched, including the root node. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | The hasAttributes() method of the [`Element`](../element/) interface returns a boolean value indicating whether the current element has any attributes or not. |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | The hasChildNodes() method of the Node interface returns a boolean value indicating whether the given [`Node`](../node/) has child nodes or not. |
| [ImportNode](../../aspose.html.dom/document/importnode/)(Node, bool) | Imports a node from another document to this document, without altering or removing the source node from the original document; this method creates a new copy of the source node. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | The insertBefore() method of the Node interface inserts a node before a reference node as a child of a specified parent node. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | The isDefaultNamespace() method of the Node interface accepts a namespace URI as an argument. It returns a boolean value that is true if the namespace is the default namespace on the given node and false if not. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | The isEqualNode() method of the [`Node`](../node/) interface tests whether two nodes are equal. Two nodes are equal when they have the same type, defining characteristics (for elements, this would be their ID, number of children, and so forth), its attributes match, and so on. The specific set of data points that must match varies depending on the types of the nodes. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | The isSameNode() method of the Node interface is a legacy alias the for the === strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | The lookupNamespaceURI() method of the Node interface takes a prefix as parameter and returns the namespace URI associated with it on the given node if found (and null if not). |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | The lookupPrefix() method of the Node interface returns a String containing the prefix for a given namespace URI, if present, and null if not. When multiple prefixes are possible, the first prefix is returned. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate)(RequestMessage) | Loads the document based on specified request object, replacing the previous content. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_4)(string) | Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_1)(Url) | Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_3)(Stream, string) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_2)(Stream, Url) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_6)(string, string) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_5)(string, Url) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Puts all [`Text`](../text/) nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), and [`entity references`](../entityreference/)) separates [`Text`](../text/) nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the [`DOMConfiguration`](../../aspose.html/configuration/) object attached to the [`Node.ownerDocument`](../node/ownerdocument/) is true, this method will also fully normalize the characters of the Text nodes. |
| [QuerySelector](../../aspose.html.dom/document/queryselector/)(string) | Returns the first Element in document, which match selector |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall/)(string) | Returns a NodeList of all the Elements in document, which match selector |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | The removeChild() method of the Node interface removes a child node from the DOM and returns the removed node. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| virtual [RenderTo](../../aspose.html.dom/document/renderto/)(IDevice) | This method is used to render the contents of the current document to a specified graphical device. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a [`DocumentFragment`](../documentfragment/) object, oldChild is replaced by all of the [`DocumentFragment`](../documentfragment/) children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Returns a String that represents this instance. |
| [Write](../../aspose.html.dom/document/write/)(params string[]) | Write a string of text to a document stream opened by open(). Note that the function will produce a document which is not necessarily driven by a DTD and therefore might be produce an invalid result in the context of the document. |
| [WriteLn](../../aspose.html.dom/document/writeln/)(params string[]) | Write a string of text followed by a newline character to a document stream opened by open(). Note that the function will produce a document which is not necessarily driven by a DTD and therefore might be produce an invalid result in the context of the document |

## Events

| Name | Description |
| --- | --- |
| event [OnAbort](../../aspose.html.dom/document/onabort/) | Gets or sets event handler for OnAbort event. |
| event [OnBlur](../../aspose.html.dom/document/onblur/) | Gets or sets event handler for OnBlur event. |
| event [OnCancel](../../aspose.html.dom/document/oncancel/) | Gets or sets event handler for OnCancel event. |
| event [OnCanplay](../../aspose.html.dom/document/oncanplay/) | Gets or sets event handler for OnCanplay event. |
| event [OnCanPlayThrough](../../aspose.html.dom/document/oncanplaythrough/) | Gets or sets event handler for OnCanPlayThrough event. |
| event [OnChange](../../aspose.html.dom/document/onchange/) | Gets or sets event handler for OnChange event. |
| event [OnClick](../../aspose.html.dom/document/onclick/) | Gets or sets event handler for OnClick event. |
| event [OnCueChange](../../aspose.html.dom/document/oncuechange/) | Gets or sets event handler for OnCueChange event. |
| event [OnDblClick](../../aspose.html.dom/document/ondblclick/) | Gets or sets event handler for OnDblClick event. |
| event [OnDurationChange](../../aspose.html.dom/document/ondurationchange/) | Gets or sets event handler for OnDurationChange event. |
| event [OnEmptied](../../aspose.html.dom/document/onemptied/) | Gets or sets event handler for OnEmptied event. |
| event [OnEnded](../../aspose.html.dom/document/onended/) | Gets or sets event handler for OnEnded event. |
| event [OnError](../../aspose.html.dom/document/onerror/) | Gets or sets event handler for OnError event. |
| event [OnFocus](../../aspose.html.dom/document/onfocus/) | Gets or sets event handler for OnFocus event. |
| event [OnInput](../../aspose.html.dom/document/oninput/) | Gets or sets event handler for OnInput event. |
| event [OnInvalid](../../aspose.html.dom/document/oninvalid/) | Gets or sets event handler for OnInvalid event. |
| event [OnKeyDown](../../aspose.html.dom/document/onkeydown/) | Gets or sets event handler for OnKeyDown event. |
| event [OnKeyPress](../../aspose.html.dom/document/onkeypress/) | Gets or sets event handler for OnKeyPress event. |
| event [OnKeyUp](../../aspose.html.dom/document/onkeyup/) | Gets or sets event handler for OnKeyUp event. |
| event [OnLoad](../../aspose.html.dom/document/onload/) | Gets or sets event handler for OnLoad event. |
| event [OnLoadedData](../../aspose.html.dom/document/onloadeddata/) | Gets or sets event handler for OnLoadedData event. |
| event [OnLoadedMetadata](../../aspose.html.dom/document/onloadedmetadata/) | Gets or sets event handler for OnLoadedMetadata event. |
| event [OnLoadStart](../../aspose.html.dom/document/onloadstart/) | Gets or sets event handler for OnLoadStart event. |
| event [OnMouseDown](../../aspose.html.dom/document/onmousedown/) | Gets or sets event handler for OnMouseDown event. |
| event [OnMouseEnter](../../aspose.html.dom/document/onmouseenter/) | Gets or sets event handler for OnMouseEnter event. |
| event [OnMouseLeave](../../aspose.html.dom/document/onmouseleave/) | Gets or sets event handler for OnMouseLeave event. |
| event [OnMouseMove](../../aspose.html.dom/document/onmousemove/) | Gets or sets event handler for OnMouseMove event. |
| event [OnMouseOut](../../aspose.html.dom/document/onmouseout/) | Gets or sets event handler for OnMouseOut event. |
| event [OnMouseOver](../../aspose.html.dom/document/onmouseover/) | Gets or sets event handler for OnMouseOver event. |
| event [OnMouseUp](../../aspose.html.dom/document/onmouseup/) | Gets or sets event handler for OnMouseUp event. |
| event [OnMouseWheel](../../aspose.html.dom/document/onmousewheel/) | Gets or sets event handler for OnMouseWheel event. |
| event [OnPause](../../aspose.html.dom/document/onpause/) | Gets or sets event handler for OnPause event. |
| event [OnPlay](../../aspose.html.dom/document/onplay/) | Gets or sets event handler for OnPlay event. |
| event [OnPlaying](../../aspose.html.dom/document/onplaying/) | Gets or sets event handler for OnPlaying event. |
| event [OnProgress](../../aspose.html.dom/document/onprogress/) | Gets or sets event handler for OnProgress event. |
| event [OnRateChange](../../aspose.html.dom/document/onratechange/) | Gets or sets event handler for OnRateChange event. |
| event [OnReadyStateChange](../../aspose.html.dom/document/onreadystatechange/) | Gets or sets event handler for OnReadyStateChange event. |
| event [OnReset](../../aspose.html.dom/document/onreset/) | Gets or sets event handler for OnReset event. |
| event [OnResize](../../aspose.html.dom/document/onresize/) | Gets or sets event handler for OnResize event. |
| event [OnScroll](../../aspose.html.dom/document/onscroll/) | Gets or sets event handler for OnScroll event. |
| event [OnSeeked](../../aspose.html.dom/document/onseeked/) | Gets or sets event handler for OnSeeked event. |
| event [OnSeeking](../../aspose.html.dom/document/onseeking/) | Gets or sets event handler for OnSeeking event. |
| event [OnSelect](../../aspose.html.dom/document/onselect/) | Gets or sets event handler for OnSelect event. |
| event [OnShow](../../aspose.html.dom/document/onshow/) | Gets or sets event handler for OnShow event. |
| event [OnStalled](../../aspose.html.dom/document/onstalled/) | Gets or sets event handler for OnStalled event. |
| event [OnSubmit](../../aspose.html.dom/document/onsubmit/) | Gets or sets event handler for OnSubmit event. |
| event [OnSuspend](../../aspose.html.dom/document/onsuspend/) | Gets or sets event handler for OnSuspend event. |
| event [OnTimeUpdate](../../aspose.html.dom/document/ontimeupdate/) | Gets or sets event handler for OnTimeUpdate event. |
| event [OnToggle](../../aspose.html.dom/document/ontoggle/) | Gets or sets event handler for OnToggle event. |
| event [OnVolumeChange](../../aspose.html.dom/document/onvolumechange/) | Gets or sets event handler for OnVolumeChange event. |
| event [OnWaiting](../../aspose.html.dom/document/onwaiting/) | Gets or sets event handler for OnWaiting event. |

### See Also

* class [Node](../node/)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../aspose.html.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../aspose.html.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../aspose.html.dom.xpath/ixpathevaluator/)
* namespace [Aspose.Html.Dom](../../aspose.html.dom/)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
