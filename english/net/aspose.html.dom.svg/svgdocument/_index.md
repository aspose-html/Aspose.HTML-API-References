---
title: SVGDocument
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 2120
url: /net/aspose.html.dom.svg/svgdocument/
---
## SVGDocument class

An `SVGDocument` is the root of the SVG hierarchy and holds the entire content. Besides providing access to the hierarchy, it also provides some convenience methods for accessing certain sets of information from the document. When an ‘svg’ element is embedded inline as a component of a document from another namespace, such as when an ‘svg’ element is embedded inline within an XHTML document [XHTML], then an SVGDocument object will not exist; instead, the root object in the document object hierarchy will be a Document object of a different type, such as an HTMLDocument object. However, an SVGDocument object will indeed exist when the root element of the XML document hierarchy is an ‘svg’ element, such as when viewing a stand-alone SVG file(i.e., a file with MIME type "image/svg+xml"). In this case, the SVGDocument object will be the root object of the document object model hierarchy.

```csharp
public class SVGDocument : Document, IDocumentCSS
```

## Constructors

| Name | Description |
| --- | --- |
| [SVGDocument](svgdocument)() | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. |
| [SVGDocument](svgdocument)(Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. |
| [SVGDocument](svgdocument)(RequestMessage) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(string) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(Url) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(RequestMessage, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(Stream, string) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). Document loading starts from the current position in the stream. |
| [SVGDocument](svgdocument)(Stream, Url) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). Document loading starts from the current position in the stream. |
| [SVGDocument](svgdocument)(string, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(string, string) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(string, Url) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(Url, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(Stream, string, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). Document loading starts from the current position in the stream. |
| [SVGDocument](svgdocument)(Stream, Url, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). Document loading starts from the current position in the stream. |
| [SVGDocument](svgdocument)(string, string, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(string, Url, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |

## Properties

| Name | Description |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes) { get; } | A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| override [BaseURI](../../aspose.html.dom/document/baseuri) { get; } | The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
| [CharacterSet](../../aspose.html.dom/document/characterset) { get; } | Gets the document's encoding. |
| [Charset](../../aspose.html.dom/document/charset) { get; } | Gets the document's encoding. |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount) { get; } | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | A NodeList that contains all children of this node. If there are no children, this is a NodeList containing no nodes.. |
| [Children](../../aspose.html.dom/document/children) { get; } | Returns the child elements. |
| [ContentType](../../aspose.html.dom/document/contenttype) { get; } | Gets the document content type. |
| [Context](../../aspose.html.dom/document/context) { get; } | Gets the current browsing context. |
| [DefaultView](../../aspose.html.dom/document/defaultview) { get; } | The defaultView IDL attribute of the Document interface, on getting, must return this Document's browsing context's WindowProxy object, if this Document has an associated browsing context, or null otherwise. |
| [Doctype](../../aspose.html.dom/document/doctype) { get; } | The Document Type Declaration associated with this document. |
| [DocumentElement](../../aspose.html.dom/document/documentelement) { get; } | This is a convenience attribute that allows direct access to the child node that is the document element of the document. |
| [DocumentURI](../../aspose.html.dom/document/documenturi) { get; } | The location of the document or null if undefined or if the Document was created using DOMImplementation.createDocument. |
| [Domain](../../aspose.html.dom.svg/svgdocument/domain) { get; } | The domain name of the server that served the document, or a null string if the server cannot be identified by a domain name. |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | The first child of this node. If there is no such node, this returns null. |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild) { get; } | Returns the first child element node of this element. null if this element has no child elements. |
| [Implementation](../../aspose.html.dom/document/implementation) { get; } | The DOMImplementation object that handles this document. |
| [InputEncoding](../../aspose.html.dom/document/inputencoding) { get; } | Gets the document's encoding. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | The last child of this node. If there is no such node, this returns null. |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild) { get; } | Returns the last child element node of this element. null if this element has no child elements. |
| virtual [LocalName](../../aspose.html.dom/node/localname) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| [Location](../../aspose.html.dom/document/location) { get; } | The location of the document. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri) { get; } | The namespace URI of this node, or null if it is unspecified. |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling) { get; } | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | The node immediately following this node. If there is no such node, this returns null. |
| override [NodeName](../../aspose.html.dom/document/nodename) { get; } | The name of this node, depending on its type. |
| override [NodeType](../../aspose.html.dom/document/nodetype) { get; } | A code representing the type of the underlying object. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | The value of this node, depending on its type. |
| [Origin](../../aspose.html.dom/document/origin) { get; } | Gets the document origin. |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument) { get; } | Gets the owner document. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | Gets the parent [`Element`](../../aspose.html.dom/element) of this node. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | The parent of this node. All nodes, except Attr, Document, DocumentFragment, Entity, and Notation may have a parent. However, if a node has just been created and not yet added to the tree, or if it has been removed from the tree, this is null. |
| virtual [Prefix](../../aspose.html.dom/node/prefix) { get; set; } | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling) { get; } | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | The node immediately preceding this node. If there is no such node, this returns null. |
| [ReadyState](../../aspose.html.dom/document/readystate) { get; } | Returns the document readiness. The "loading" while the Document is loading, "interactive" once it is finished parsing but still loading sub-resources, and "complete" once it has loaded. |
| [Referrer](../../aspose.html.dom.svg/svgdocument/referrer) { get; } | Returns the URI of the page that linked to this page. The value is an empty string if the user navigated to the page directly (not through a link, but, for example, via a bookmark). |
| [RootElement](../../aspose.html.dom.svg/svgdocument/rootelement) { get; } | The root ‘svg’ in the document hierarchy. |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking) { get; set; } | An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [StyleSheets](../../aspose.html.dom/document/stylesheets) { get; } | A list containing all the style sheets explicitly linked into or embedded in a document. For HTML documents, this includes external style sheets, included via the HTML LINK element, and inline STYLE elements. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [Title](../../aspose.html.dom.svg/svgdocument/title) { get; } | The title of a document as specified by the ‘title’ sub-element of the ‘svg’ root element (i.e., Here is the title...) |
| [URL](../../aspose.html.dom.svg/svgdocument/url) { get; } | The complete URI of the document. |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone) { get; set; } | An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
| [XmlVersion](../../aspose.html.dom/document/xmlversion) { get; set; } | An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | This method allows the registration of event listeners on the event target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | This method allows the registration of event listeners on the event target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | This method allows the registration of event listeners on the event target. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | Adds the node newChild to the end of the list of children of this node. If the newChild is already in the tree, it is first removed. |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [CreateAttribute](../../aspose.html.dom/document/createattribute)(string) | Creates an Attr of the given name. |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens)(string, string) | Creates an attribute of the given qualified name and namespace URI. |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection)(string) | Creates a CDATASection node whose value is the specified string. |
| [CreateComment](../../aspose.html.dom/document/createcomment)(string) | Creates a Comment node given the specified string. |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment)() | Creates an empty DocumentFragment object. |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype)(string, string, string, string) | Creates a DocumentType node. |
| [CreateElement](../../aspose.html.dom/document/createelement)(string) | Creates an element of the type specified. Note that the instance returned implements the Element interface, so attributes can be specified directly on the returned object. |
| [CreateElementNS](../../aspose.html.dom/document/createelementns)(string, string) | Creates an element of the given qualified name and namespace URI. |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference)(string) | Creates an EntityReference object. In addition, if the referenced entity is known, the child list of the EntityReference node is made the same as that of the corresponding Entity node. |
| [CreateEvent](../../aspose.html.dom/document/createevent)(string) | Creates an [`Event`](../../aspose.html.dom.events/event) of a type supported by the implementation. |
| [CreateExpression](../../aspose.html.dom/document/createexpression)(string, IXPathNSResolver) | Creates a parsed XPath expression with resolved namespaces. This is useful when an expression will be reused in an application since it makes it possible to compile the expression string into a more efficient internal form and preresolve all namespace prefixes which occur within the expression. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator)(Node) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator)(Node, long) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator)(Node, long, INodeFilter) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver)(Node) | Adapts any DOM node to resolve namespaces so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method `lookupNamespaceURI` on nodes in resolving the namespaceURI from a given prefix using the current information available in the node's hierarchy at the time lookupNamespaceURI is called, also correctly resolving the implicit xml prefix. |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction)(string, string) | Creates a ProcessingInstruction node given the specified name and data strings. |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode)(string) | Creates a Text node given the specified string. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker)(Node) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker)(Node, long) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker)(Node, long, INodeFilter) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | This method allows the dispatch of events into the implementations event model. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [Evaluate](../../aspose.html.dom/document/evaluate)(string, Node, IXPathNSResolver, XPathResultType, object) | Evaluates an XPath expression string and returns a result of the specified type if possible. |
| [GetElementById](../../aspose.html.dom/document/getelementbyid)(string) | Returns the Element that has an ID attribute with the given value. If no such element exists, this returns null. If more than one element has an ID attribute with that value, what is returned is undefined. |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname)(string) | Returns a live NodeList object containing all the elements in the document that have all the classes specified in argument. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname)(string) | Returns a NodeList of all the Elements in document order with a given tag name and are contained in the document. |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens)(string, string) | Returns a NodeList of all the Elements with a given local name and namespace URI in document order. |
| [GetOverrideStyle](../../aspose.html.dom.svg/svgdocument/getoverridestyle)(Element, string) | This method is used to retrieve the override style declaration for a specified element and a specified pseudo-element. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | This method is used to retrieve ECMAScript object Type. |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes)() | Returns whether this node (if it is an element) has any attributes |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | Returns whether this node has any children. |
| [ImportNode](../../aspose.html.dom/document/importnode)(Node, bool) | Imports a node from another document to this document, without altering or removing the source node from the original document; this method creates a new copy of the source node. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children. If child is a DocumentFragment object, all of its children are inserted, in the same order, before child. If the child is already in the tree, it is first removed. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | This method checks if the specified namespaceURI is the default namespace or not. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | Tests whether two nodes are equal. This method tests for equality of nodes, not sameness (i.e., whether the two nodes are references to the same object) which can be tested with Node.isSameNode(). All nodes that are the same will also be equal, though the reverse may not be true. |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | Returns whether this node is the same node as the given one. This method provides a way to determine whether two Node references returned by the implementation reference the same object. When two Node references are references to the same object, even if through a proxy, the references may be used completely interchangeably, such that all attributes have the same values and calling the same DOM method on either reference always has exactly the same effect. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. See Namespace Prefix Lookup for details on the algorithm used by this method. |
| [Navigate](../../aspose.html.dom/document/navigate)(RequestMessage) | Loads the document based on specified request object, replacing the previous content. |
| [Navigate](../../aspose.html.dom/document/navigate)(string) | Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content. |
| [Navigate](../../aspose.html.dom/document/navigate)(Url) | Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content. |
| [Navigate](../../aspose.html.dom/document/navigate)(Stream, string) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream. |
| [Navigate](../../aspose.html.dom/document/navigate)(Stream, Url) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream. |
| [Navigate](../../aspose.html.dom/document/navigate)(string, string) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. |
| [Navigate](../../aspose.html.dom/document/navigate)(string, Url) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. |
| [Normalize](../../aspose.html.dom/node/normalize)() | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [QuerySelector](../../aspose.html.dom/document/queryselector)(string) | Returns the first Element in document, which match selector |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall)(string) | Returns a NodeList of all the Elements in document, which match selector |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | Removes the child node indicated by oldChild from the list of children, and returns it. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](../../aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](../../aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](../../aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| override [RenderTo](../../aspose.html.dom.svg/svgdocument/renderto)(IDevice) | This method is used to print the contents of the current document to the specified device. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a DocumentFragment object, oldChild is replaced by all of the DocumentFragment children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [Save](../../aspose.html.dom.svg/svgdocument/save)(IOutputStorage) | Saves the document content and resources to the output storage. |
| [Save](../../aspose.html.dom.svg/svgdocument/save)(string) | Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save)(Url) | Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save)(IOutputStorage, SVGSaveFormat) | Saves the document content and resources to the output storage. |
| [Save](../../aspose.html.dom.svg/svgdocument/save)(IOutputStorage, SVGSaveOptions) | Saves the document content and resources to the output storage. |
| [Save](../../aspose.html.dom.svg/svgdocument/save)(string, SVGSaveFormat) | Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save)(string, SVGSaveOptions) | Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save)(Url, SVGSaveFormat) | Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save)(Url, SVGSaveOptions) | Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| override [ToString](../../aspose.html.dom/node/tostring)() | Returns a String that represents this instance. |
| [Write](../../aspose.html.dom/document/write)(params string[]) | Write a string of text to a document stream opened by open(). Note that the function will produce a document which is not necessarily driven by a DTD and therefore might be produce an invalid result in the context of the document. |
| [WriteLn](../../aspose.html.dom/document/writeln)(params string[]) | Write a string of text followed by a newline character to a document stream opened by open(). Note that the function will produce a document which is not necessarily driven by a DTD and therefore might be produce an invalid result in the context of the document |

### See Also

* class [Document](../../aspose.html.dom/document)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss)
* namespace [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
