---
title: Document
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 770
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
| override [BaseURI](baseuri) { get; } | The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
| [CharacterSet](characterset) { get; } | Gets the document's encoding. |
| [Charset](charset) { get; } | Gets the document's encoding. |
| [ChildElementCount](childelementcount) { get; } | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [Children](children) { get; } | Returns the child elements. |
| [ContentType](contenttype) { get; } | Gets the document content type. |
| [Context](context) { get; } | Gets the current browsing context. |
| [DefaultView](defaultview) { get; } | The defaultView IDL attribute of the Document interface, on getting, must return this Document's browsing context's WindowProxy object, if this Document has an associated browsing context, or null otherwise. |
| [Doctype](doctype) { get; } | The Document Type Declaration associated with this document. |
| [DocumentElement](documentelement) { get; } | This is a convenience attribute that allows direct access to the child node that is the document element of the document. |
| [DocumentURI](documenturi) { get; } | The location of the document or null if undefined or if the Document was created using DOMImplementation.createDocument. |
| [FirstElementChild](firstelementchild) { get; } | Returns the first child element node of this element. null if this element has no child elements. |
| [Implementation](implementation) { get; } | The DOMImplementation object that handles this document. |
| [InputEncoding](inputencoding) { get; } | Gets the document's encoding. |
| [LastElementChild](lastelementchild) { get; } | Returns the last child element node of this element. null if this element has no child elements. |
| [Location](location) { get; } | The location of the document. |
| [NextElementSibling](nextelementsibling) { get; } | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| override [NodeName](nodename) { get; } | The name of this node, depending on its type. |
| override [NodeType](nodetype) { get; } | A code representing the type of the underlying object. |
| [Origin](origin) { get; } | Gets the document origin. |
| override [OwnerDocument](ownerdocument) { get; } | Gets the owner document. |
| [PreviousElementSibling](previouselementsibling) { get; } | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [ReadyState](readystate) { get; } | Returns the document readiness. The "loading" while the Document is loading, "interactive" once it is finished parsing but still loading sub-resources, and "complete" once it has loaded. |
| [StrictErrorChecking](stricterrorchecking) { get; set; } | An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [StyleSheets](stylesheets) { get; } | A list containing all the style sheets explicitly linked into or embedded in a document. For HTML documents, this includes external style sheets, included via the HTML LINK element, and inline STYLE elements. |
| [XmlStandalone](xmlstandalone) { get; set; } | An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
| [XmlVersion](xmlversion) { get; set; } | An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Methods

| Name | Description |
| --- | --- |
| [CreateAttribute](createattribute)(string) | Creates an Attr of the given name. |
| [CreateAttributeNS](createattributens)(string, string) | Creates an attribute of the given qualified name and namespace URI. |
| [CreateCDATASection](createcdatasection)(string) | Creates a CDATASection node whose value is the specified string. |
| [CreateComment](createcomment)(string) | Creates a Comment node given the specified string. |
| [CreateDocumentFragment](createdocumentfragment)() | Creates an empty DocumentFragment object. |
| [CreateDocumentType](createdocumenttype)(string, string, string, string) | Creates a DocumentType node. |
| [CreateElement](createelement)(string) | Creates an element of the type specified. Note that the instance returned implements the Element interface, so attributes can be specified directly on the returned object. |
| [CreateElementNS](createelementns)(string, string) | Creates an element of the given qualified name and namespace URI. |
| [CreateEntityReference](createentityreference)(string) | Creates an EntityReference object. In addition, if the referenced entity is known, the child list of the EntityReference node is made the same as that of the corresponding Entity node. |
| [CreateEvent](createevent)(string) | Creates an [`Event`](../../aspose.html.dom.events/event) of a type supported by the implementation. |
| [CreateExpression](createexpression)(string, IXPathNSResolver) | Creates a parsed XPath expression with resolved namespaces. This is useful when an expression will be reused in an application since it makes it possible to compile the expression string into a more efficient internal form and preresolve all namespace prefixes which occur within the expression. |
| [CreateNodeIterator](createnodeiterator)(Node) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [CreateNodeIterator](createnodeiterator)(Node, long) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [CreateNodeIterator](createnodeiterator)(Node, long, INodeFilter) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [CreateNSResolver](creatensresolver)(Node) | Adapts any DOM node to resolve namespaces so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method `lookupNamespaceURI` on nodes in resolving the namespaceURI from a given prefix using the current information available in the node's hierarchy at the time lookupNamespaceURI is called, also correctly resolving the implicit xml prefix. |
| [CreateProcessingInstruction](createprocessinginstruction)(string, string) | Creates a ProcessingInstruction node given the specified name and data strings. |
| [CreateTextNode](createtextnode)(string) | Creates a Text node given the specified string. |
| [CreateTreeWalker](createtreewalker)(Node) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [CreateTreeWalker](createtreewalker)(Node, long) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [CreateTreeWalker](createtreewalker)(Node, long, INodeFilter) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [Evaluate](evaluate)(string, Node, IXPathNSResolver, XPathResultType, object) | Evaluates an XPath expression string and returns a result of the specified type if possible. |
| [GetElementById](getelementbyid)(string) | Returns the Element that has an ID attribute with the given value. If no such element exists, this returns null. If more than one element has an ID attribute with that value, what is returned is undefined. |
| [GetElementsByClassName](getelementsbyclassname)(string) | Returns a live NodeList object containing all the elements in the document that have all the classes specified in argument. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](getelementsbytagname)(string) | Returns a NodeList of all the Elements in document order with a given tag name and are contained in the document. |
| [GetElementsByTagNameNS](getelementsbytagnamens)(string, string) | Returns a NodeList of all the Elements with a given local name and namespace URI in document order. |
| [ImportNode](importnode)(Node, bool) | Imports a node from another document to this document, without altering or removing the source node from the original document; this method creates a new copy of the source node. |
| [Navigate](navigate)(RequestMessage) | Loads the document based on specified request object, replacing the previous content. |
| [Navigate](navigate)(string) | Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content. |
| [Navigate](navigate)(Url) | Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content. |
| [Navigate](navigate)(Stream, string) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream. |
| [Navigate](navigate)(Stream, Url) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream. |
| [Navigate](navigate)(string, string) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. |
| [Navigate](navigate)(string, Url) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. |
| [QuerySelector](queryselector)(string) | Returns the first Element in document, which match selector |
| [QuerySelectorAll](queryselectorall)(string) | Returns a NodeList of all the Elements in document, which match selector |
| virtual [RenderTo](renderto)(IDevice) | This method is used to render the contents of the current document to a specified graphical device. |
| [Write](write)(params string[]) | Write a string of text to a document stream opened by open(). Note that the function will produce a document which is not necessarily driven by a DTD and therefore might be produce an invalid result in the context of the document. |
| [WriteLn](writeln)(params string[]) | Write a string of text followed by a newline character to a document stream opened by open(). Note that the function will produce a document which is not necessarily driven by a DTD and therefore might be produce an invalid result in the context of the document |

## Other Members

| Name | Description |
| --- | --- |
| event [OnAbort](onabort) | Gets or sets event handler for OnAbort event. |
| event [OnBlur](onblur) | Gets or sets event handler for OnBlur event. |
| event [OnCancel](oncancel) | Gets or sets event handler for OnCancel event. |
| event [OnCanplay](oncanplay) | Gets or sets event handler for OnCanplay event. |
| event [OnCanPlayThrough](oncanplaythrough) | Gets or sets event handler for OnCanPlayThrough event. |
| event [OnChange](onchange) | Gets or sets event handler for OnChange event. |
| event [OnClick](onclick) | Gets or sets event handler for OnClick event. |
| event [OnCueChange](oncuechange) | Gets or sets event handler for OnCueChange event. |
| event [OnDblClick](ondblclick) | Gets or sets event handler for OnDblClick event. |
| event [OnDurationChange](ondurationchange) | Gets or sets event handler for OnDurationChange event. |
| event [OnEmptied](onemptied) | Gets or sets event handler for OnEmptied event. |
| event [OnEnded](onended) | Gets or sets event handler for OnEnded event. |
| event [OnError](onerror) | Gets or sets event handler for OnError event. |
| event [OnFocus](onfocus) | Gets or sets event handler for OnFocus event. |
| event [OnInput](oninput) | Gets or sets event handler for OnInput event. |
| event [OnInvalid](oninvalid) | Gets or sets event handler for OnInvalid event. |
| event [OnKeyDown](onkeydown) | Gets or sets event handler for OnKeyDown event. |
| event [OnKeyPress](onkeypress) | Gets or sets event handler for OnKeyPress event. |
| event [OnKeyUp](onkeyup) | Gets or sets event handler for OnKeyUp event. |
| event [OnLoad](onload) | Gets or sets event handler for OnLoad event. |
| event [OnLoadedData](onloadeddata) | Gets or sets event handler for OnLoadedData event. |
| event [OnLoadedMetadata](onloadedmetadata) | Gets or sets event handler for OnLoadedMetadata event. |
| event [OnLoadStart](onloadstart) | Gets or sets event handler for OnLoadStart event. |
| event [OnMouseDown](onmousedown) | Gets or sets event handler for OnMouseDown event. |
| event [OnMouseEnter](onmouseenter) | Gets or sets event handler for OnMouseEnter event. |
| event [OnMouseLeave](onmouseleave) | Gets or sets event handler for OnMouseLeave event. |
| event [OnMouseMove](onmousemove) | Gets or sets event handler for OnMouseMove event. |
| event [OnMouseOut](onmouseout) | Gets or sets event handler for OnMouseOut event. |
| event [OnMouseOver](onmouseover) | Gets or sets event handler for OnMouseOver event. |
| event [OnMouseUp](onmouseup) | Gets or sets event handler for OnMouseUp event. |
| event [OnMouseWheel](onmousewheel) | Gets or sets event handler for OnMouseWheel event. |
| event [OnPause](onpause) | Gets or sets event handler for OnPause event. |
| event [OnPlay](onplay) | Gets or sets event handler for OnPlay event. |
| event [OnPlaying](onplaying) | Gets or sets event handler for OnPlaying event. |
| event [OnProgress](onprogress) | Gets or sets event handler for OnProgress event. |
| event [OnRateChange](onratechange) | Gets or sets event handler for OnRateChange event. |
| event [OnReadyStateChange](onreadystatechange) | Gets or sets event handler for OnReadyStateChange event. |
| event [OnReset](onreset) | Gets or sets event handler for OnReset event. |
| event [OnResize](onresize) | Gets or sets event handler for OnResize event. |
| event [OnScroll](onscroll) | Gets or sets event handler for OnScroll event. |
| event [OnSeeked](onseeked) | Gets or sets event handler for OnSeeked event. |
| event [OnSeeking](onseeking) | Gets or sets event handler for OnSeeking event. |
| event [OnSelect](onselect) | Gets or sets event handler for OnSelect event. |
| event [OnShow](onshow) | Gets or sets event handler for OnShow event. |
| event [OnStalled](onstalled) | Gets or sets event handler for OnStalled event. |
| event [OnSubmit](onsubmit) | Gets or sets event handler for OnSubmit event. |
| event [OnSuspend](onsuspend) | Gets or sets event handler for OnSuspend event. |
| event [OnTimeUpdate](ontimeupdate) | Gets or sets event handler for OnTimeUpdate event. |
| event [OnToggle](ontoggle) | Gets or sets event handler for OnToggle event. |
| event [OnVolumeChange](onvolumechange) | Gets or sets event handler for OnVolumeChange event. |
| event [OnWaiting](onwaiting) | Gets or sets event handler for OnWaiting event. |

### See Also

* class [Node](../node)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent)
* interface [IDocumentStyle](../../aspose.html.dom.css/idocumentstyle)
* interface [IDocumentTraversal](../../aspose.html.dom.traversal/idocumenttraversal)
* interface [IGlobalEventHandlers](../iglobaleventhandlers)
* interface [INonElementParentNode](../inonelementparentnode)
* interface [IParentNode](../iparentnode)
* interface [IXPathEvaluator](../../aspose.html.dom.xpath/ixpathevaluator)
* namespace [Aspose.Html.Dom](../../aspose.html.dom)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
