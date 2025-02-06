---
title: HTMLDocument Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.HTMLDocument class. Represents an HTML document. All top level HTML objects are added to this object. This class represents the HTML page as what we see in browser. All forms tables scripts ... are added to the HTML page via the interfaces of this class. HTMLDocument is html implementation of most general Document interface and both are core or root point of DOM - Document Object Model. These concepts are in full accordance with officical web development basis or standards. For the purposes of web development you can generally think of HTMLDocument as an alias for Document upon which HTMLDocument is based
type: docs
weight: 3200
url: /java/com.aspose.html/htmldocument/
---
## HTMLDocument class

Represents an HTML document. All top level HTML objects are added to this object. This class represents the HTML page as what we see in browser. All forms, tables, scripts, ... are added to the HTML page via the interfaces of this class. [HTMLDocument](https://dom.spec.whatwg.org/#ref-for-dom-domimplementation-createhtmldocument) is html implementation of most general [Document](https://dom.spec.whatwg.org/#document) interface and both are core or root point of [DOM](https://dom.spec.whatwg.org/) - Document Object Model. These concepts are in full accordance with officical web development basis or standards. For the purposes of web development, you can generally think of HTMLDocument as an alias for Document, upon which HTMLDocument is based.

```java
public class HTMLDocument : Document, IDocumentCSS
```

## Constructors

| Name | Description |
| --- | --- |
| [HTMLDocument](htmldocument/#constructor)() | The HTMLDocument constructor creates a new HTML Document object that is a web page loaded in the browser and serving as an entry point into the page's content. |
| [HTMLDocument](htmldocument/#constructor_1)(Configuration) | The HTMLDocument constructor creates a new HTML Document object that is a web page loaded in the browser and serving as an entry point into the page's content. |
| [HTMLDocument](htmldocument/#constructor_2)(RequestMessage) | Creates an HTML document from the [`RequestMessage`](../../com.aspose.html.net/requestmessage/) object. |
| [HTMLDocument](htmldocument/#constructor_10)(String) | Loads the HTML document from an address. |
| [HTMLDocument](htmldocument/#constructor_4)(Url) | Loads the HTML document from a URL. |
| [HTMLDocument](htmldocument/#constructor_3)(RequestMessage, Configuration) | Creates an HTML document from the [RequestMessage](T:com.aspose.html.net.RequestMessage) object. |
| [HTMLDocument](htmldocument/#constructor_8)(Stream, String) | Creates an HTML document from a [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content with specified base-uri that is used to resolve the relative resources' path. |
| [HTMLDocument](htmldocument/#constructor_6)(Stream, Url) | Creates an HTML document from a [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content with specified base-uri that is used to resolve the relative resources' path. |
| [HTMLDocument](htmldocument/#constructor_11)(String, Configuration) | Loads the HTML document from an address with specified environment configuration settings. |
| [HTMLDocument](htmldocument/#constructor_14)(String, String) | Creates an HTML document from a String content with specified base-uri. |
| [HTMLDocument](htmldocument/#constructor_12)(String, Url) | Creates an HTML document from a String content with specified base-uri. |
| [HTMLDocument](htmldocument/#constructor_5)(Url, Configuration) | Loads the HTML document from a URL with specified environment configuration settings. |
| [HTMLDocument](htmldocument/#constructor_9)(Stream, String, Configuration) | Creates an HTML document from a [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content with specified base-uri and environment configuration settings. |
| [HTMLDocument](htmldocument/#constructor_7)(Stream, Url, Configuration) | Creates an HTML document from a [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content with specified base-uri and environment configuration settings. |
| [HTMLDocument](htmldocument/#constructor_15)(String, String, Configuration) | Creates an HTML document from a String content with specified base-uri and environment configuration settings. |
| [HTMLDocument](htmldocument/#constructor_13)(String, Url, Configuration) | Creates an HTML document from a String content with specified base-uri and environment configuration settings. |

## Properties

| Name | Description |
| --- | --- |
| [getAnchors](../../com.aspose.html/htmldocument/anchors/) A collection of all the anchor (`A`) elements in a document with a value for the `name` attribute. For reasons of backward compatibility, the returned set of anchors only contains those anchors created with the `name` attribute, not those created with the `id` attribute. Note that in [[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801)], the `name` attribute (see section 4.10) has no semantics and is only present for legacy user agents: the `id` attribute is used instead. Users should prefer the iterator mechanisms provided by [[DOM Level 2 Traversal](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)] instead. |
| [getApplets](../../com.aspose.html/htmldocument/applets/) A collection of all the `OBJECT` elements that include applets and `APPLET` (deprecated) elements in a document. |
| [getAttributes](../../com.aspose.html.dom/node/attributes/) The attributes property returns a live collection of all attribute nodes registered to the specified node. Attributes is a key/value pair of Strings that represents any information regarding that attribute. |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
[getBody]
[setBody] The element that contains the content for the document. In documents with `BODY` contents, returns the `BODY`element. In frameset documents, this returns the outermost `FRAMESET` element. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) Gets the document's encoding. |
| [getCharset](../../com.aspose.html.dom/document/charset/) Gets the document's encoding. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) The read-only childNodes property of the Node interface returns a live [`NodeList`](../../com.aspose.html.collections/nodelist/) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [getChildren](../../com.aspose.html.dom/document/children/) Returns the child elements. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) Gets the document content type. |
| [getContext](../../com.aspose.html.dom/document/context/) Gets the current browsing context. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) The defaultView IDL attribute of the Document interface, on getting, must return this Document's browsing context's WindowProxy object, if this Document has an associated browsing context, or null otherwise. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) The Document Type Declaration associated with this document. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) This is a convenience attribute that allows direct access to the child node that is the document element of the document. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) The location of the document or null if undefined or if the Document was created using DOMImplementation.createDocument. |
| [getDomain](../../com.aspose.html/htmldocument/domain/) The domain name of the server that served the document, or `null` if the server cannot be identified by a domain name. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) The read-only firstChild property of the [`Node`](../../com.aspose.html.dom/node/) interface returns the node's first child in the tree, or null if the node has no children. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) Returns the first child element node of this element. null if this element has no child elements. |
| [getForms](../../com.aspose.html/htmldocument/forms/) A collection of all the forms of a document. |
| [getImages](../../com.aspose.html/htmldocument/images/) A collection of all the `IMG` elements in a document. The behavior is limited to `IMG` elements for backwards compatibility. As suggested by [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)], to include images, authors may use the `OBJECT` element or the `IMG` element. Therefore, it is recommended not to use this attribute to find the images in the document but `getElementsByTagName` with HTML 4.01 or `getElementsByTagNameNS` with XHTML 1.0. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) The DOMImplementation object that handles this document. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) Gets the document's encoding. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) The read-only lastChild property of the [`Node`](../../com.aspose.html.dom/node/) interface returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) Returns the last child element node of this element. null if this element has no child elements. |
| [getLinks](../../com.aspose.html/htmldocument/links/) A collection of all `AREA` elements and anchor (`A`) elements in a document with a value for the `href` attribute. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Returns the local part of the qualified name of this node. For nodes of any type other than [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) and [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) and nodes created with a DOM Level 1 method, such as [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/), this is always null. |
| [getLocation](../../com.aspose.html.dom/document/location/) The location of the document. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) The Element.packageURI read-only property returns the package URI of the element, or null if the element is not in a package. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) The read-only nextSibling property of the [`Node`](../../com.aspose.html.dom/node/) interface returns the node immediately following the specified one in their parent's [`childNodes`](../../com.aspose.html.dom/node/childnodes/), or returns null if the specified node is the last child in the parent element. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) The name of this node, depending on its type. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) A code representing the type of the underlying object. |
[getNodeValue]
[setNodeValue] The nodeValue property of the [`Node `](../../com.aspose.html.dom/node/)interface returns or sets the value of the current node. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) Gets the document origin. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) Gets the owner document. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) The read-only parentElement property of [`Node`](../../com.aspose.html.dom/node/) interface returns the DOM node's parent [`Element`](../../com.aspose.html.dom/element/), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree. |
[getPrefix]
[setPrefix] The prefix read-only property returns the package prefix of the specified element, or null if no prefix is specified. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) The read-only previousSibling property of the [`Node`](../../com.aspose.html.dom/node/) interface returns the node immediately preceding the specified one in its parent's [`childNodes`](../../com.aspose.html.dom/node/firstchild/) list, or null if the specified node is the first in that list. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) Returns the document readiness. The "loading" while the Document is loading, "interactive" once it is finished parsing but still loading sub-resources, and "complete" once it has loaded. |
| [getReferrer](../../com.aspose.html/htmldocument/referrer/) Returns the URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)] of the page that linked to this page. The value is an empty String if the user navigated to the page directly (not through a link, but, for example, via a bookmark). |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) A list containing all the style sheets explicitly linked into or embedded in a document. For HTML documents, this includes external style sheets, included via the HTML LINK element, and inline STYLE elements. |
[getTextContent]
[setTextContent] The textContent property of the [`Node`](../../com.aspose.html.dom/node/) interface represents the text content of the node and its descendants. |
[getTitle]
[setTitle] The title of a document as specified by the `TITLE` element in the head of the document. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Methods

| Name | Description |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() method of the [`EventTarget `](../../com.aspose.html.dom/eventtarget/)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | The addEventListener() method of the [EventTarget ](T:com.aspose.html.dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | The addEventListener() method of the [EventTarget ](T:com.aspose.html.dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | The appendChild() method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | The Document.createAttribute() method creates a new attribute node, and returns it. The object created a node implementing the [`Attr`](../../com.aspose.html.dom/attr/) interface. The DOM does not enforce what sort of attributes can be added to a particular element in this manner. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | The Document.createAttribute() method creates a new attribute node, and returns it. The object created a node implementing the [Attr](T:com.aspose.html.dom.Attr) interface. The DOM does not enforce what sort of attributes can be added to a particular element in this manner. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | Creates a [`CDATASection`](../../com.aspose.html.dom/cdatasection/) node whose value is the specified String. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | Creates a [`Comment`](../../com.aspose.html.dom/comment/) node given the specified String. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | Creates a new empty [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) into which DOM nodes can be added to build an offscreen DOM tree. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | The method returns a [`DocumentType`](../../com.aspose.html.dom/documenttype/) object which can either be used with DOMImplementation.createDocument upon document creation or can be put into the document via methods like Node.insertBefore() or Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | In an HTML document, the document.createElement() method creates the HTML element specified by tagName, or an [`HTMLUnknownElement`](../htmlunknownelement/) if tagName isn't recognized. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | Creates an element of the given qualified name and package URI. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | Creates an EntityReference object. In addition, if the referenced entity is known, the child list of the EntityReference node is made the same as that of the corresponding Entity node. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | Creates an [`Event`](../../com.aspose.html.dom.events/event/) of a type supported by the implementation. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | Creates a parsed XPath expression with resolved packages. This is useful when an expression will be reused in an application since it makes it possible to compile the expression String into a more efficient internal form and preresolve all package prefixes which occur within the expression. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Create a new NodeIterator over the subtree rooted at the specified node. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | Adapts any DOM node to resolve packages so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method `lookupNamespaceURI` on nodes in resolving the packageURI from a given prefix using the current information available in the node's hierarchy at the time lookupNamespaceURI is called, also correctly resolving the implicit xml prefix. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | Creates a ProcessingInstruction node given the specified name and data Strings. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | Creates a Text node given the specified String. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | Create a new TreeWalker over the subtree rooted at the specified node. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Dispatches an Event at the specified [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Evaluates an XPath expression String and returns a result of the specified type if possible. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | The Document method getElementById() returns an [`Element`](../../com.aspose.html.dom/element/) object representing the element whose id property matches the specified String. Since element IDs are required to be unique if specified, they're a useful way to get access to a specific element quickly. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | The getElementsByClassName method of [`Document`](../../com.aspose.html.dom/document/) interface returns an array-like object of all child elements which have all of the given class name(s). |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | The getElementsByTagName method of [`Document`](../../com.aspose.html.dom/document/) interface returns an [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) of elements with the given tag name. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | Returns a list of elements with the given tag name belonging to the given package. The complete document is searched, including the root node. |
| [getOverrideStyle](../../com.aspose.html/htmldocument/getoverridestyle/)(Element, String) | This method is used to retrieve the override style declaration for a specified element and a specified pseudo-element. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [hasAttributes](../../com.aspose.html.dom/node/hasattributes/)() | The hasAttributes() method of the [`Element`](../../com.aspose.html.dom/element/) interface returns a boolean value indicating whether the current element has any attributes or not. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | The hasChildNodes() method of the Node interface returns a boolean value indicating whether the given [`Node`](../../com.aspose.html.dom/node/) has child nodes or not. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | Imports a node from another document to this document, without altering or removing the source node from the original document; this method creates a new copy of the source node. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | The insertBefore() method of the Node interface inserts a node before a reference node as a child of a specified parent node. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | The isDefaultNamespace() method of the Node interface accepts a package URI as an argument. It returns a boolean value that is true if the package is the default package on the given node and false if not. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | The isEqualNode() method of the [`Node`](../../com.aspose.html.dom/node/) interface tests whether two nodes are equal. Two nodes are equal when they have the same type, defining characteristics (for elements, this would be their ID, number of children, and so forth), its attributes match, and so on. The specific set of data points that must match varies depending on the types of the nodes. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | The isSameNode() method of the Node interface is a legacy alias the for the === strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | The lookupNamespaceURI() method of the Node interface takes a prefix as parameter and returns the package URI associated with it on the given node if found (and null if not). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | The lookupPrefix() method of the Node interface returns a String containing the prefix for a given package URI, if present, and null if not. When multiple prefixes are possible, the first prefix is returned. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(RequestMessage) | Loads the document based on specified request object, replacing the previous content. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String) | Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Url) | Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, String) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, Url) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, String) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, Url) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Puts all [`Text`](../../com.aspose.html.dom/text/) nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), and [`entity references`](../../com.aspose.html.dom/entityreference/)) separates [`Text`](../../com.aspose.html.dom/text/) nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the [`DOMConfiguration`](../configuration/) object attached to the [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) is true, this method will also fully normalize the characters of the Text nodes. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | Returns the first Element in document, which match selector |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | Returns a NodeList of all the Elements in document, which match selector |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | The removeChild() method of the Node interface removes a child node from the DOM and returns the removed node. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [renderTo](../../com.aspose.html/htmldocument/renderto/)(IDevice) | This method is used to print the contents of the current document to the specified device. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) object, oldChild is replaced by all of the [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [save](../../com.aspose.html/htmldocument/save/#save)(IOutputStorage) | Saves the document content and resources to the output storage. |
| [save](../../com.aspose.html/htmldocument/save/#save_10)(String) | Saves the document to a local file specified by path. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_5)(Url) | Saves the document to a local file specified by url. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_1)(IOutputStorage, HTMLSaveFormat) | Saves the document content and resources to the output storage. |
| [save](../../com.aspose.html/htmldocument/save/#save_2)(IOutputStorage, HTMLSaveOptions) | Saves the document content and resources to the output storage. |
| [save](../../com.aspose.html/htmldocument/save/#save_3)(IOutputStorage, MarkdownSaveOptions) | Saves the document content and resources to the output storage. |
| [save](../../com.aspose.html/htmldocument/save/#save_4)(IOutputStorage, MHTMLSaveOptions) | Saves the document content and resources to the output storage. |
| [save](../../com.aspose.html/htmldocument/save/#save_11)(String, HTMLSaveFormat) | Saves the document to a local file specified by path. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_12)(String, HTMLSaveOptions) | Saves the document to a local file specified by path. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_13)(String, MarkdownSaveOptions) | Saves the document to a local file specified by path. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_14)(String, MHTMLSaveOptions) | Saves the document to a local file specified by path. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_6)(Url, HTMLSaveFormat) | Saves the document to a local file specified by url. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_7)(Url, HTMLSaveOptions) | Saves the document to a local file specified by url. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_8)(Url, MarkdownSaveOptions) | Saves the document to a local file specified by url. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_9)(Url, MHTMLSaveOptions) | Saves the document to a local file specified by url. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [toString](../../com.aspose.html.dom/node/toString/)() | Returns a String that represents this instance. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | Write a String of text to a document stream opened by open(). Note that the function will produce a document which is not necessarily driven by a DTD and therefore might be produce an invalid result in the context of the document. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | Write a String of text followed by a newline character to a document stream opened by open(). Note that the function will produce a document which is not necessarily driven by a DTD and therefore might be produce an invalid result in the context of the document |

## Events

| Name | Description |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | Gets or sets event handler for OnAbort event. |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | Gets or sets event handler for OnBlur event. |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | Gets or sets event handler for OnCancel event. |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | Gets or sets event handler for OnCanplay event. |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | Gets or sets event handler for OnCanPlayThrough event. |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | Gets or sets event handler for OnChange event. |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | Gets or sets event handler for OnClick event. |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | Gets or sets event handler for OnCueChange event. |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | Gets or sets event handler for OnDblClick event. |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | Gets or sets event handler for OnDurationChange event. |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | Gets or sets event handler for OnEmptied event. |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | Gets or sets event handler for OnEnded event. |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | Gets or sets event handler for OnError event. |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | Gets or sets event handler for OnFocus event. |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | Gets or sets event handler for OnInput event. |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | Gets or sets event handler for OnInvalid event. |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | Gets or sets event handler for OnKeyDown event. |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | Gets or sets event handler for OnKeyPress event. |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | Gets or sets event handler for OnKeyUp event. |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | Gets or sets event handler for OnLoad event. |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | Gets or sets event handler for OnLoadedData event. |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | Gets or sets event handler for OnLoadedMetadata event. |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | Gets or sets event handler for OnLoadStart event. |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | Gets or sets event handler for OnMouseDown event. |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | Gets or sets event handler for OnMouseEnter event. |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | Gets or sets event handler for OnMouseLeave event. |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | Gets or sets event handler for OnMouseMove event. |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | Gets or sets event handler for OnMouseOut event. |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | Gets or sets event handler for OnMouseOver event. |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | Gets or sets event handler for OnMouseUp event. |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | Gets or sets event handler for OnMouseWheel event. |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | Gets or sets event handler for OnPause event. |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | Gets or sets event handler for OnPlay event. |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | Gets or sets event handler for OnPlaying event. |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | Gets or sets event handler for OnProgress event. |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | Gets or sets event handler for OnRateChange event. |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | Gets or sets event handler for OnReadyStateChange event. |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | Gets or sets event handler for OnReset event. |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | Gets or sets event handler for OnResize event. |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | Gets or sets event handler for OnScroll event. |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | Gets or sets event handler for OnSeeked event. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | Gets or sets event handler for OnSeeking event. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | Gets or sets event handler for OnSelect event. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | Gets or sets event handler for OnShow event. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | Gets or sets event handler for OnStalled event. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | Gets or sets event handler for OnSubmit event. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | Gets or sets event handler for OnSuspend event. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | Gets or sets event handler for OnTimeUpdate event. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | Gets or sets event handler for OnToggle event. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | Gets or sets event handler for OnVolumeChange event. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | Gets or sets event handler for OnWaiting event. |

## Remarks

More info about HTMLDocument, Document and DOM can be obtained in popular web development resources:

[General Document interface](https://developer.mozilla.org/en-US/docs/Web/API/Document).[Html specific HTMLDocument interface](https://developer.mozilla.org/en-US/docs/Web/API/HTMLDocument).[What is the HTML DOM](https://www.w3schools.com/js/js_htmldom.asp).

Standards Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Examples

```java
    // Create an instance of an HTML document
	using (var document = new HTMLDocument())
      {
        // Create a style element and assign the green color for all elements with class-name equals 'gr'.
        var style = document.CreateElement("style");
        style.TextContent = ".gr { color: green }";

        // Find the document header element and append style element to the header
        var head = document.GetElementsByTagName("head").First();
        head.AppendChild(style);

        // Create a paragraph element with class-name 'gr'.
        var p = (HTMLParagraphElement)document.CreateElement("p");
        p.ClassName = "gr";

        // Create a text node
        var text = document.CreateTextNode("Hello World!!");

        // Append the text node to the paragraph
        p.AppendChild(text);

        // Append the paragraph to the document body element
        document.Body.AppendChild(p);

        // Save the HTML document to a file 
        document.Save(Path.Combine(OutputDir, "using-dom.html"));

        // Create an instance of the PDF output device and render the document into this device
        using (var device = new PdfDevice(Path.Combine(OutputDir, "using-dom.pdf")))
        {
          // Render HTML to PDF
          document.RenderTo(device);
        }
      }       
```

### See Also

* class [Document](../../com.aspose.html.dom/document/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
