---
title: Document class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 70
url: /python-net/aspose.html.dom/document/
is_root: false
---

## Document class

The Document represents the entire HTML, XML or SVG document. Conceptually, it is the root of the document tree, and provides the primary access to the document's data.



**Inheritance:** [`Document`](/html/python-net/aspose.html.dom/document) → 
[`Node`](/html/python-net/aspose.html.dom/node) → 
[`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The Document type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [node_type](/html/python-net/aspose.html.dom/document/node_type) | A code representing the type of the underlying object. |
| [local_name](/html/python-net/aspose.html.dom/document/local_name) | Returns the local part of the qualified name of this node. <br/>For nodes of any type other than [`Node.ELEMENT_NODE`](/html/python-net/aspose.html.dom/node) and [`Node.ATTRIBUTE_NODE`](/html/python-net/aspose.html.dom/node)<br/>and nodes created with a DOM Level 1 method, such as [`Document.create_element`](/html/python-net/aspose.html.dom/document/create_element), this is always null. |
| [namespace_uri](/html/python-net/aspose.html.dom/document/namespace_uri) | Returns the namespace URI of the element, or null if the element is not in a namespace. |
| [prefix](/html/python-net/aspose.html.dom/document/prefix) | Returns the namespace prefix of the specified element, or null if no prefix is specified. |
| [node_name](/html/python-net/aspose.html.dom/document/node_name) | The name of this node, depending on its type. |
| [base_uri](/html/python-net/aspose.html.dom/document/base_uri) | The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
| [owner_document](/html/python-net/aspose.html.dom/document/owner_document) | Gets the owner document. |
| [parent_node](/html/python-net/aspose.html.dom/document/parent_node) | Returns the parent of the specified node in the DOM tree.<br/><br/><br/>[`Document`](/html/python-net/aspose.html.dom/document) and [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment) nodes can never have a parent, so  will always return null. It also returns  if the node has just been created and is not yet attached to the tree. |
| [parent_element](/html/python-net/aspose.html.dom/document/parent_element) | Returns the DOM node's parent [`Element`](/html/python-net/aspose.html.dom/element), or if the node either has no parent, or its parent isn't a DOM Element. |
| [child_nodes](/html/python-net/aspose.html.dom/document/child_nodes) | Returns a live [`NodeList`](/html/python-net/aspose.html.collections/nodelist) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [first_child](/html/python-net/aspose.html.dom/document/first_child) | Returns the node's first child in the tree, or null if the node has no children.<br/><br/><br/>If the node is a Document, this property returns the first node in the list of its direct children. |
| [last_child](/html/python-net/aspose.html.dom/document/last_child) | Returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [previous_sibling](/html/python-net/aspose.html.dom/document/previous_sibling) | Returns the node immediately preceding the specified one in its parent's [`Node.child_nodes`](/html/python-net/aspose.html.dom/node#child_nodes) list, or if the specified node is the first in that list. |
| [next_sibling](/html/python-net/aspose.html.dom/document/next_sibling) | Returns the node immediately following the specified one in their parent's [`Node.child_nodes`](/html/python-net/aspose.html.dom/node#child_nodes), or returns null if the specified node is the last child in the parent element. |
| [node_value](/html/python-net/aspose.html.dom/document/node_value) | Returns or sets the value of the current node. |
| [text_content](/html/python-net/aspose.html.dom/document/text_content) | Represents the text content of the node and its descendants. |
| [ELEMENT_NODE](/html/python-net/aspose.html.dom/document/element_node) | An element node |
| [ATTRIBUTE_NODE](/html/python-net/aspose.html.dom/document/attribute_node) | An attribute node |
| [TEXT_NODE](/html/python-net/aspose.html.dom/document/text_node) | A text node |
| [CDATA_SECTION_NODE](/html/python-net/aspose.html.dom/document/cdata_section_node) | A cdata section node |
| [ENTITY_REFERENCE_NODE](/html/python-net/aspose.html.dom/document/entity_reference_node) | An entity reference node |
| [ENTITY_NODE](/html/python-net/aspose.html.dom/document/entity_node) | An entity node |
| [PROCESSING_INSTRUCTION_NODE](/html/python-net/aspose.html.dom/document/processing_instruction_node) | A processing instruction node |
| [COMMENT_NODE](/html/python-net/aspose.html.dom/document/comment_node) | A comment node |
| [DOCUMENT_NODE](/html/python-net/aspose.html.dom/document/document_node) | A document node |
| [DOCUMENT_TYPE_NODE](/html/python-net/aspose.html.dom/document/document_type_node) | A document type node |
| [DOCUMENT_FRAGMENT_NODE](/html/python-net/aspose.html.dom/document/document_fragment_node) | A document fragment node |
| [NOTATION_NODE](/html/python-net/aspose.html.dom/document/notation_node) | A notation node |
| [context](/html/python-net/aspose.html.dom/document/context) | Gets the current browsing context. |
| [implementation](/html/python-net/aspose.html.dom/document/implementation) | The DOMImplementation object that handles this document. |
| [location](/html/python-net/aspose.html.dom/document/location) | The location of the document. |
| [document_uri](/html/python-net/aspose.html.dom/document/document_uri) | The location of the document or null if undefined or if the Document was created using DOMImplementation.createDocument. |
| [origin](/html/python-net/aspose.html.dom/document/origin) | Gets the document origin. |
| [character_set](/html/python-net/aspose.html.dom/document/character_set) | Gets the document's encoding. |
| [charset](/html/python-net/aspose.html.dom/document/charset) | Gets the document's encoding. |
| [input_encoding](/html/python-net/aspose.html.dom/document/input_encoding) | Gets the document's encoding. |
| [content_type](/html/python-net/aspose.html.dom/document/content_type) | Gets the document content type. |
| [ready_state](/html/python-net/aspose.html.dom/document/ready_state) | Returns the document readiness. The "loading" while the Document is loading, "interactive" once it is finished parsing but still loading sub-resources, and "complete" once it has loaded. |
| [doctype](/html/python-net/aspose.html.dom/document/doctype) | The Document Type Declaration associated with this document. |
| [document_element](/html/python-net/aspose.html.dom/document/document_element) | This is a convenience attribute that allows direct access to the child node that is the document element of the document. |
| [first_element_child](/html/python-net/aspose.html.dom/document/first_element_child) | Returns the first child element node of this element. null if this element has no child elements. |
| [last_element_child](/html/python-net/aspose.html.dom/document/last_element_child) | Returns the last child element node of this element. null if this element has no child elements. |
| [previous_element_sibling](/html/python-net/aspose.html.dom/document/previous_element_sibling) | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [next_element_sibling](/html/python-net/aspose.html.dom/document/next_element_sibling) | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [child_element_count](/html/python-net/aspose.html.dom/document/child_element_count) | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [children](/html/python-net/aspose.html.dom/document/children) | Returns the child elements. |
| [xml_standalone](/html/python-net/aspose.html.dom/document/xml_standalone) | An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
| [xml_version](/html/python-net/aspose.html.dom/document/xml_version) | An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |
| [strict_error_checking](/html/python-net/aspose.html.dom/document/strict_error_checking) | An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [default_view](/html/python-net/aspose.html.dom/document/default_view) | The defaultView IDL attribute of the Document interface, on getting, <br/>must return this Document's browsing context's WindowProxy object, <br/>if this Document has an associated browsing context, or null otherwise. |
| [style_sheets](/html/python-net/aspose.html.dom/document/style_sheets) | A list containing all the style sheets explicitly linked into or embedded in a document. For HTML documents, this includes external style sheets, included via the HTML LINK element, and inline STYLE elements. |


### Methods
| Method | Description |
| :- | :- |
| [add_event_listener](/html/python-net/aspose.html.dom/document/add_event_listener/#str-aspose.html.dom.events.IEventListener) | Sets up a function that will be called whenever the specified event is delivered to the target.<br/><br/><br/>It works by adding a function, or an object that implements [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener),<br/>to the list of event listeners for the specified event type on the [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) on which it's called.<br/>If the function or object, is already in the list of event listeners for this target, they are not added a second time. |
| [add_event_listener](/html/python-net/aspose.html.dom/document/add_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | Sets up a function that will be called whenever the specified event is delivered to the target.<br/><br/><br/>It works by adding a function, or an object that implements [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener),<br/>to the list of event listeners for the specified event type on the [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) on which it's called.<br/>If the function or object, is already in the list of event listeners for this target, they are not added a second time. |
| [remove_event_listener](/html/python-net/aspose.html.dom/document/remove_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [remove_event_listener](/html/python-net/aspose.html.dom/document/remove_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [clone_node](/html/python-net/aspose.html.dom/document/clone_node/#) | Returns a duplicate of the node on which this method was called.<br/><br/><br/>Cloning a node copies all of its attributes and their values, including intrinsic (inline) listeners. It does not copy event listeners added using [`IEventTarget.add_event_listener`](/html/python-net/aspose.html.dom.events/ieventtarget/add_event_listener) or those assigned to element properties (e.g., node.onclick = someFunction). Additionally, for a HTMLCanvasElement element, the painted image is not copied. |
| [clone_node](/html/python-net/aspose.html.dom/document/clone_node/#bool) | Returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not.<br/><br/><br/>Cloning a node copies all of its attributes and their values, including intrinsic (inline) listeners. <br/>It does not copy event listeners added using [`IEventTarget.add_event_listener`](/html/python-net/aspose.html.dom.events/ieventtarget/add_event_listener)<br/>or those assigned to element properties (e.g., node.onclick = someFunction). Additionally, for a HTMLCanvasElement element, the painted image is not copied. |
| [navigate](/html/python-net/aspose.html.dom/document/navigate/#str) | Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content. |
| [navigate](/html/python-net/aspose.html.dom/document/navigate/#aspose.html.Url) | Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content. |
| [navigate](/html/python-net/aspose.html.dom/document/navigate/#str-str) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. |
| [navigate](/html/python-net/aspose.html.dom/document/navigate/#str-aspose.html.Url) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. |
| [navigate](/html/python-net/aspose.html.dom/document/navigate/#io.RawIOBase-str) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.<br/>Document loading starts from the current position in the stream. |
| [navigate](/html/python-net/aspose.html.dom/document/navigate/#io.RawIOBase-aspose.html.Url) | Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.<br/>Document loading starts from the current position in the stream. |
| [navigate](/html/python-net/aspose.html.dom/document/navigate/#aspose.html.net.RequestMessage) | Loads the document based on specified request object, replacing the previous content. |
| [create_node_iterator](/html/python-net/aspose.html.dom/document/create_node_iterator/#aspose.html.dom.Node) | Create a new NodeIterator over the subtree rooted at the<br/>specified node. |
| [create_node_iterator](/html/python-net/aspose.html.dom/document/create_node_iterator/#aspose.html.dom.Node-int) | Create a new NodeIterator over the subtree rooted at the<br/>specified node. |
| [create_node_iterator](/html/python-net/aspose.html.dom/document/create_node_iterator/#aspose.html.dom.Node-int-aspose.html.dom.traversal.INodeFilter) | Create a new NodeIterator over the subtree rooted at the<br/>specified node. |
| [create_tree_walker](/html/python-net/aspose.html.dom/document/create_tree_walker/#aspose.html.dom.Node) | Create a new TreeWalker over the subtree rooted at the<br/>specified node. |
| [create_tree_walker](/html/python-net/aspose.html.dom/document/create_tree_walker/#aspose.html.dom.Node-int) | Create a new TreeWalker over the subtree rooted at the<br/>specified node. |
| [create_tree_walker](/html/python-net/aspose.html.dom/document/create_tree_walker/#aspose.html.dom.Node-int-aspose.html.dom.traversal.INodeFilter) | Create a new TreeWalker over the subtree rooted at the<br/>specified node. |
| [get_platform_type](/html/python-net/aspose.html.dom/document/get_platform_type/#) | This method is used to retrieve the ECMAScript object Type. |
| [dispatch_event](/html/python-net/aspose.html.dom/document/dispatch_event/#aspose.html.dom.events.Event) | Dispatches an Event at the specified [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget), (synchronously) invoking<br/>the affected EventListeners in the appropriate order. <br/>The normal event processing rules (including the capturing and optional bubbling phase) also apply to events <br/>dispatched manually with [`IEventTarget.dispatch_event`](/html/python-net/aspose.html.dom.events/ieventtarget/dispatch_event). |
| [has_child_nodes](/html/python-net/aspose.html.dom/document/has_child_nodes/#) | Returns a boolean value indicating whether the given [`Node`](/html/python-net/aspose.html.dom/node) has child nodes or not. |
| [normalize](/html/python-net/aspose.html.dom/document/normalize/#) | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [is_equal_node](/html/python-net/aspose.html.dom/document/is_equal_node/#aspose.html.dom.Node) | Tests whether two nodes are equal.<br/>This method tests for equality of nodes, not sameness (i.e., whether the two nodes are references to the same object) which can be tested with Node.isSameNode(). All nodes that are the same will also be equal, though the reverse may not be true. |
| [is_same_node](/html/python-net/aspose.html.dom/document/is_same_node/#aspose.html.dom.Node) | Method is a legacy alias the for the  strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [lookup_prefix](/html/python-net/aspose.html.dom/document/lookup_prefix/#str) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. <br/>See Namespace Prefix Lookup for details on the algorithm used by this method. |
| [lookup_namespace_uri](/html/python-net/aspose.html.dom/document/lookup_namespace_uri/#str) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [is_default_namespace](/html/python-net/aspose.html.dom/document/is_default_namespace/#str) | This method checks if the specified namespaceURI is the default namespace or not. |
| [insert_before](/html/python-net/aspose.html.dom/document/insert_before/#aspose.html.dom.Node-aspose.html.dom.Node) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children.<br/>If child is a DocumentFragment object, all of its children are inserted, in the same order, before child. If the child is already in the tree, it is first removed. |
| [replace_child](/html/python-net/aspose.html.dom/document/replace_child/#aspose.html.dom.Node-aspose.html.dom.Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. <br/>If newChild is a DocumentFragment object, oldChild is replaced by all of the DocumentFragment children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [remove_child](/html/python-net/aspose.html.dom/document/remove_child/#aspose.html.dom.Node) | Removes a child node from the DOM and returns the removed node. |
| [append_child](/html/python-net/aspose.html.dom/document/append_child/#aspose.html.dom.Node) | Adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, [`Node.append_child`](/html/python-net/aspose.html.dom/node/append_child) moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node).<br/><br/><br/>This means that a node can't be in two points of the document simultaneously. So if the node already has a parent, the node is first removed, then appended at the new position. The [`Node.clone_node`](/html/python-net/aspose.html.dom/node/clone_node) method can be used to make a copy of the node before appending it under the new parent. Copies made with [`Node.clone_node`](/html/python-net/aspose.html.dom/node/clone_node) are not be automatically kept in sync. |
| [create_element](/html/python-net/aspose.html.dom/document/create_element/#str) | Creates the HTML element specified by , or an  if localName isn't recognized. |
| [create_element_ns](/html/python-net/aspose.html.dom/document/create_element_ns/#str-str) | Creates an element of the given qualified name and namespace URI. |
| [create_document_fragment](/html/python-net/aspose.html.dom/document/create_document_fragment/#) | Creates a new empty [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment) into which DOM nodes can be added to build an offscreen DOM tree. |
| [create_text_node](/html/python-net/aspose.html.dom/document/create_text_node/#str) | Creates a Text node given the specified string. |
| [create_comment](/html/python-net/aspose.html.dom/document/create_comment/#str) | Creates a Comment node given the specified string. |
| [create_cdata_section](/html/python-net/aspose.html.dom/document/create_cdata_section/#str) | Creates a CDATASection node whose value is the specified string. |
| [create_processing_instruction](/html/python-net/aspose.html.dom/document/create_processing_instruction/#str-str) | Creates a ProcessingInstruction node given the specified name and data strings. |
| [create_attribute](/html/python-net/aspose.html.dom/document/create_attribute/#str) | This method creates a new attribute node, and returns it. <br/>The object created is a node implementing the [`Attr`](/html/python-net/aspose.html.dom/attr) class. <br/>The DOM does not enforce what sort of attributes can be added to a particular element in this manner. |
| [create_attribute_ns](/html/python-net/aspose.html.dom/document/create_attribute_ns/#str-str) | This method creates a new attribute node, and returns it. <br/>The object created is a node implementing the [`Attr`](/html/python-net/aspose.html.dom/attr) class. <br/>The DOM does not enforce what sort of attributes can be added to a particular element in this manner. |
| [create_entity_reference](/html/python-net/aspose.html.dom/document/create_entity_reference/#str) | Creates an EntityReference object. In addition, if the referenced entity is known, the child list of the EntityReference node is made the same as that of the corresponding Entity node. |
| [create_document_type](/html/python-net/aspose.html.dom/document/create_document_type/#str-str-str-str) | The method returns a [`DocumentType`](/html/python-net/aspose.html.dom/documenttype) object which can either be used <br/>with [`IDOMImplementation.create_document`](/html/python-net/aspose.html.dom/idomimplementation/create_document) upon document creation or can be put into the document via methods <br/>like [`Node.insert_before`](/html/python-net/aspose.html.dom/node/insert_before) or [`Node.replace_child`](/html/python-net/aspose.html.dom/node/replace_child). |
| [get_elements_by_tag_name](/html/python-net/aspose.html.dom/document/get_elements_by_tag_name/#str) | This method returns an [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection) of elements with the given tag name.<br/><br/><br/>The complete document is searched, including the root node. <br/>The returned [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection) is live,<br/>meaning that it updates itself automatically to stay in sync with the DOM tree without having to call <br/>this method again. |
| [get_elements_by_tag_name_ns](/html/python-net/aspose.html.dom/document/get_elements_by_tag_name_ns/#str-str) | Returns a list of elements with the given tag name belonging to the given namespace.<br/>The complete document is searched, including the root node. |
| [get_element_by_id](/html/python-net/aspose.html.dom/document/get_element_by_id/#str) | This method returns an [`Element`](/html/python-net/aspose.html.dom/element) object representing the element whose id property matches the specified string. Since element IDs are required to be unique if specified, they're a useful way to get access to a specific element quickly.<br/><br/><br/>If you need to get access to an element which doesn't have an ID, you can use [`Document.query_selector`](/html/python-net/aspose.html.dom/document/query_selector) to find the element using any selector. |
| [get_elements_by_class_name](/html/python-net/aspose.html.dom/document/get_elements_by_class_name/#str) | This method returns an array-like object of all child elements which have all the given class name(s).<br/><br/><br/>When called on the document object, the complete document is searched, including the root node. <br/>You may also call this method on any element; it will return only elements which are descendants <br/>of the specified root element with the given class name(s). |
| [query_selector_all](/html/python-net/aspose.html.dom/document/query_selector_all/#str) | Returns a NodeList of all the Elements in document, which match selector |
| [query_selector](/html/python-net/aspose.html.dom/document/query_selector/#str) | Returns the first Element in document, which match selector |
| [import_node](/html/python-net/aspose.html.dom/document/import_node/#aspose.html.dom.Node-bool) | Imports a node from another document to this document, without altering or removing the source node from the original document; this method creates a new copy of the source node. |
| [create_event](/html/python-net/aspose.html.dom/document/create_event/#str) | Creates an [`Event`](/html/python-net/aspose.html.dom.events/event) of a type supported by the implementation. |
| [write](/html/python-net/aspose.html.dom/document/write/#list) | Write a string of text to a document stream opened by<br/>open(). Note that the function will produce a document<br/>which is not necessarily driven by a DTD and therefore might be<br/>produce an invalid result in the context of the document. |
| [write_ln](/html/python-net/aspose.html.dom/document/write_ln/#list) | Write a string of text followed by a newline character to a document<br/>stream opened by open(). Note that the function will<br/>produce a document which is not necessarily driven by a DTD and<br/>therefore might be produce an invalid result in the context of the<br/>document |
| [create_expression](/html/python-net/aspose.html.dom/document/create_expression/#str-aspose.html.dom.xpath.IXPathNSResolver) | Creates a parsed XPath expression with resolved namespaces. This is useful <br/>when an expression will be reused in an application since it makes it possible <br/>to compile the expression string into a more efficient internal form and <br/>preresolve all namespace prefixes which occur within the expression. |
| [create_ns_resolver](/html/python-net/aspose.html.dom/document/create_ns_resolver/#aspose.html.dom.Node) | Adapts any DOM node to resolve namespaces so that an XPath expression can be easily evaluated<br/>relative to the context of the node where it appeared within the document. This adapter works<br/>like the DOM Level 3 method `lookupNamespaceURI` on nodes in resolving the namespaceURI<br/>from a given prefix using the current information available in the node's hierarchy at the time<br/>lookupNamespaceURI is called, also correctly resolving the implicit xml prefix. |
| [evaluate](/html/python-net/aspose.html.dom/document/evaluate/#str-aspose.html.dom.Node-aspose.html.dom.xpath.IXPathNSResolver-aspose.html.dom.xpath.XPathResultType-any) | Evaluates an XPath expression string and returns a result of the specified type if possible. |
| [render_to](/html/python-net/aspose.html.dom/document/render_to/#aspose.html.rendering.IDevice) | This method is used to render the contents of the current document to a specified graphical device. |



### See Also
* module [`aspose.html.dom`](..)
* class [`Attr`](/html/python-net/aspose.html.dom/attr)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`Document`](/html/python-net/aspose.html.dom/document)
* class [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment)
* class [`DocumentType`](/html/python-net/aspose.html.dom/documenttype)
* class [`Element`](/html/python-net/aspose.html.dom/element)
* class [`Event`](/html/python-net/aspose.html.dom.events/event)
* class [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget)
* class [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget)
* class [`Node`](/html/python-net/aspose.html.dom/node)
* class [`NodeList`](/html/python-net/aspose.html.collections/nodelist)
