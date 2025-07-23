---
title: HTMLFormElement class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 240
url: /python-net/aspose.html/htmlformelement/
is_root: false
---

## HTMLFormElement class

The `FORM` element encompasses behavior similar to a collection 
and an element. It provides direct access to the contained form controls 
as well as the attributes of the form element. See the FORM element 
definition in HTML 4.01.

See also the [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).



**Inheritance:** [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement) → 
[`HTMLElement`](/html/python-net/aspose.html/htmlelement) → 
[`Element`](/html/python-net/aspose.html.dom/element) → 
[`Node`](/html/python-net/aspose.html.dom/node) → 
[`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The HTMLFormElement type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [node_type](/html/python-net/aspose.html/htmlformelement/node_type) | A code representing the type of the underlying object. |
| [local_name](/html/python-net/aspose.html/htmlformelement/local_name) | Returns the local part of the qualified name of this node.<br/>For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| [namespace_uri](/html/python-net/aspose.html/htmlformelement/namespace_uri) | The namespace URI of this node, or null if it is unspecified. |
| [prefix](/html/python-net/aspose.html/htmlformelement/prefix) | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [node_name](/html/python-net/aspose.html/htmlformelement/node_name) | The name of this node, depending on its type. |
| [base_uri](/html/python-net/aspose.html/htmlformelement/base_uri) | Returns the absolute base URL of the document containing the node.<br/><br/><br/>The base URL is used to resolve relative URLs when the browser needs to obtain an absolute URL, <br/>for example when processing the HTML img element's src attribute or the xlink:href or href attributes in SVG. |
| [owner_document](/html/python-net/aspose.html/htmlformelement/owner_document) | Returns the top-level document object of the node. |
| [parent_node](/html/python-net/aspose.html/htmlformelement/parent_node) | Returns the parent of the specified node in the DOM tree.<br/><br/><br/>[`Document`](/html/python-net/aspose.html.dom/document) and [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment) nodes can never have a parent, so  will always return null. It also returns  if the node has just been created and is not yet attached to the tree. |
| [parent_element](/html/python-net/aspose.html/htmlformelement/parent_element) | Returns the DOM node's parent [`Element`](/html/python-net/aspose.html.dom/element), or if the node either has no parent, or its parent isn't a DOM Element. |
| [child_nodes](/html/python-net/aspose.html/htmlformelement/child_nodes) | Returns a live [`NodeList`](/html/python-net/aspose.html.collections/nodelist) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [first_child](/html/python-net/aspose.html/htmlformelement/first_child) | Returns the node's first child in the tree, or null if the node has no children.<br/><br/><br/>If the node is a Document, this property returns the first node in the list of its direct children. |
| [last_child](/html/python-net/aspose.html/htmlformelement/last_child) | Returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [previous_sibling](/html/python-net/aspose.html/htmlformelement/previous_sibling) | Returns the node immediately preceding the specified one in its parent's [`Node.child_nodes`](/html/python-net/aspose.html.dom/node#child_nodes) list, or if the specified node is the first in that list. |
| [next_sibling](/html/python-net/aspose.html/htmlformelement/next_sibling) | Returns the node immediately following the specified one in their parent's [`Node.child_nodes`](/html/python-net/aspose.html.dom/node#child_nodes), or returns null if the specified node is the last child in the parent element. |
| [node_value](/html/python-net/aspose.html/htmlformelement/node_value) | Returns or sets the value of the current node. |
| [text_content](/html/python-net/aspose.html/htmlformelement/text_content) | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [ELEMENT_NODE](/html/python-net/aspose.html/htmlformelement/element_node) | An element node |
| [ATTRIBUTE_NODE](/html/python-net/aspose.html/htmlformelement/attribute_node) | An attribute node |
| [TEXT_NODE](/html/python-net/aspose.html/htmlformelement/text_node) | A text node |
| [CDATA_SECTION_NODE](/html/python-net/aspose.html/htmlformelement/cdata_section_node) | A cdata section node |
| [ENTITY_REFERENCE_NODE](/html/python-net/aspose.html/htmlformelement/entity_reference_node) | An entity reference node |
| [ENTITY_NODE](/html/python-net/aspose.html/htmlformelement/entity_node) | An entity node |
| [PROCESSING_INSTRUCTION_NODE](/html/python-net/aspose.html/htmlformelement/processing_instruction_node) | A processing instruction node |
| [COMMENT_NODE](/html/python-net/aspose.html/htmlformelement/comment_node) | A comment node |
| [DOCUMENT_NODE](/html/python-net/aspose.html/htmlformelement/document_node) | A document node |
| [DOCUMENT_TYPE_NODE](/html/python-net/aspose.html/htmlformelement/document_type_node) | A document type node |
| [DOCUMENT_FRAGMENT_NODE](/html/python-net/aspose.html/htmlformelement/document_fragment_node) | A document fragment node |
| [NOTATION_NODE](/html/python-net/aspose.html/htmlformelement/notation_node) | A notation node |
| [class_list](/html/python-net/aspose.html/htmlformelement/class_list) | Returns a live DOMTokenList which contains tokens received from parsing the "class" attribute. |
| [tag_name](/html/python-net/aspose.html/htmlformelement/tag_name) | The name of the element. |
| [id](/html/python-net/aspose.html/htmlformelement/id) | The element's identifier. See the id attribute definition in HTML 4.01. |
| [class_name](/html/python-net/aspose.html/htmlformelement/class_name) | The class attribute of the element. This attribute has been renamed due <br/>to conflicts with the "class" keyword exposed by many languages. See <br/>the class attribute definition in HTML 4.01. |
| [attributes](/html/python-net/aspose.html/htmlformelement/attributes) | A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| [first_element_child](/html/python-net/aspose.html/htmlformelement/first_element_child) | Returns the first child element node of this element. null if this element has no child elements. |
| [last_element_child](/html/python-net/aspose.html/htmlformelement/last_element_child) | Returns the last child element node of this element. null if this element has no child elements. |
| [previous_element_sibling](/html/python-net/aspose.html/htmlformelement/previous_element_sibling) | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [next_element_sibling](/html/python-net/aspose.html/htmlformelement/next_element_sibling) | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [child_element_count](/html/python-net/aspose.html/htmlformelement/child_element_count) | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [children](/html/python-net/aspose.html/htmlformelement/children) | Returns the child elements of current element. |
| [inner_html](/html/python-net/aspose.html/htmlformelement/inner_html) | Returns a fragment of HTML or XML that represents the element's contents.<br/>Can be set, to replace the contents of the element with nodes parsed from the given string. |
| [outer_html](/html/python-net/aspose.html/htmlformelement/outer_html) | Returns a fragment of HTML or XML that represents the element and its contents.<br/>Can be set, to replace the element with nodes parsed from the given string. |
| [shadow_root](/html/python-net/aspose.html/htmlformelement/shadow_root) | Returns shadowRoot stored on this element or null if it's closed. |
| [title](/html/python-net/aspose.html/htmlformelement/title) | The element's advisory title. See the title attribute definition in <br/>HTML 4.01. |
| [lang](/html/python-net/aspose.html/htmlformelement/lang) | Language code defined in RFC 1766. See the lang attribute definition in <br/>HTML 4.01. |
| [dir](/html/python-net/aspose.html/htmlformelement/dir) | Specifies the base direction of directionally neutral text and the <br/>directionality of tables. See the dir attribute definition in HTML <br/>4.01. |
| [style](/html/python-net/aspose.html/htmlformelement/style) | Represents a style attribute that allows author to directly apply style information to specific element. |
| [elements](/html/python-net/aspose.html/htmlformelement/elements) | Returns a collection of all form control elements in the form. |
| [length](/html/python-net/aspose.html/htmlformelement/length) | The number of form controls in the form. |
| [name](/html/python-net/aspose.html/htmlformelement/name) | Names the form. |
| [accept_charset](/html/python-net/aspose.html/htmlformelement/accept_charset) | List of character sets supported by the server. See the accept-charset <br/>attribute definition in HTML 4.01. |
| [action](/html/python-net/aspose.html/htmlformelement/action) | Server-side form handler. See the action attribute definition in HTML 4.01. |
| [enctype](/html/python-net/aspose.html/htmlformelement/enctype) | The content type of the submitted form, generally <br/>"application/x-www-form-urlencoded". See the enctype attribute <br/>definition in HTML 4.01. The onsubmit even handler is not guaranteed <br/>to be triggered when invoking this method. The behavior is <br/>inconsistent for historical reasons and authors should not rely on a <br/>particular one. |
| [method](/html/python-net/aspose.html/htmlformelement/method) | HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |
| [target](/html/python-net/aspose.html/htmlformelement/target) | Frame to render the resource in. See the target attribute definition in <br/>HTML 4.01. |


### Methods
| Method | Description |
| :- | :- |
| [add_event_listener](/html/python-net/aspose.html/htmlformelement/add_event_listener/#str-aspose.html.dom.events.IEventListener) | Sets up a function that will be called whenever the specified event is delivered to the target.<br/><br/><br/>It works by adding a function, or an object that implements [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener),<br/>to the list of event listeners for the specified event type on the [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) on which it's called.<br/>If the function or object, is already in the list of event listeners for this target, they are not added a second time. |
| [add_event_listener](/html/python-net/aspose.html/htmlformelement/add_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | Sets up a function that will be called whenever the specified event is delivered to the target.<br/><br/><br/>It works by adding a function, or an object that implements [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener),<br/>to the list of event listeners for the specified event type on the [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) on which it's called.<br/>If the function or object, is already in the list of event listeners for this target, they are not added a second time. |
| [remove_event_listener](/html/python-net/aspose.html/htmlformelement/remove_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [remove_event_listener](/html/python-net/aspose.html/htmlformelement/remove_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [clone_node](/html/python-net/aspose.html/htmlformelement/clone_node/#) | Returns a duplicate of the node on which this method was called.<br/><br/><br/>Cloning a node copies all of its attributes and their values, including intrinsic (inline) listeners. It does not copy event listeners added using [`IEventTarget.add_event_listener`](/html/python-net/aspose.html.dom.events/ieventtarget/add_event_listener) or those assigned to element properties (e.g., node.onclick = someFunction). Additionally, for a HTMLCanvasElement element, the painted image is not copied. |
| [clone_node](/html/python-net/aspose.html/htmlformelement/clone_node/#bool) | Returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not.<br/><br/><br/>Cloning a node copies all of its attributes and their values, including intrinsic (inline) listeners. <br/>It does not copy event listeners added using [`IEventTarget.add_event_listener`](/html/python-net/aspose.html.dom.events/ieventtarget/add_event_listener)<br/>or those assigned to element properties (e.g., node.onclick = someFunction). Additionally, for a HTMLCanvasElement element, the painted image is not copied. |
| [toggle_attribute](/html/python-net/aspose.html/htmlformelement/toggle_attribute/#str) | If force is not given, "toggles" qualifiedName, removing it if it is present and adding it if it is not present. If force is true, adds qualifiedName.<br/>If force is false, removes qualifiedName. |
| [toggle_attribute](/html/python-net/aspose.html/htmlformelement/toggle_attribute/#str-bool) | If force is not given, "toggles" qualifiedName, removing it if it is present and adding it if it is not present. If force is true, adds qualifiedName.<br/>If force is false, removes qualifiedName. |
| [get_platform_type](/html/python-net/aspose.html/htmlformelement/get_platform_type/#) | This method is used to retrieve the ECMAScript object Type. |
| [dispatch_event](/html/python-net/aspose.html/htmlformelement/dispatch_event/#aspose.html.dom.events.Event) | Dispatches an Event at the specified [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget), (synchronously) invoking<br/>the affected EventListeners in the appropriate order. <br/>The normal event processing rules (including the capturing and optional bubbling phase) also apply to events <br/>dispatched manually with [`IEventTarget.dispatch_event`](/html/python-net/aspose.html.dom.events/ieventtarget/dispatch_event). |
| [has_child_nodes](/html/python-net/aspose.html/htmlformelement/has_child_nodes/#) | Returns a boolean value indicating whether the given [`Node`](/html/python-net/aspose.html.dom/node) has child nodes or not. |
| [normalize](/html/python-net/aspose.html/htmlformelement/normalize/#) | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [is_equal_node](/html/python-net/aspose.html/htmlformelement/is_equal_node/#aspose.html.dom.Node) | Tests whether two nodes are equal.<br/>This method tests for equality of nodes, not sameness (i.e., whether the two nodes are references to the same object) which can be tested with Node.isSameNode(). All nodes that are the same will also be equal, though the reverse may not be true. |
| [is_same_node](/html/python-net/aspose.html/htmlformelement/is_same_node/#aspose.html.dom.Node) | Method is a legacy alias the for the  strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [lookup_prefix](/html/python-net/aspose.html/htmlformelement/lookup_prefix/#str) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. <br/>See Namespace Prefix Lookup for details on the algorithm used by this method. |
| [lookup_namespace_uri](/html/python-net/aspose.html/htmlformelement/lookup_namespace_uri/#str) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [is_default_namespace](/html/python-net/aspose.html/htmlformelement/is_default_namespace/#str) | This method checks if the specified namespaceURI is the default namespace or not. |
| [insert_before](/html/python-net/aspose.html/htmlformelement/insert_before/#aspose.html.dom.Node-aspose.html.dom.Node) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children.<br/>If child is a DocumentFragment object, all of its children are inserted, in the same order, before child. If the child is already in the tree, it is first removed. |
| [replace_child](/html/python-net/aspose.html/htmlformelement/replace_child/#aspose.html.dom.Node-aspose.html.dom.Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. <br/>If newChild is a DocumentFragment object, oldChild is replaced by all of the DocumentFragment children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [remove_child](/html/python-net/aspose.html/htmlformelement/remove_child/#aspose.html.dom.Node) | Removes a child node from the DOM and returns the removed node. |
| [append_child](/html/python-net/aspose.html/htmlformelement/append_child/#aspose.html.dom.Node) | Adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, [`Node.append_child`](/html/python-net/aspose.html.dom/node/append_child) moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node).<br/><br/><br/>This means that a node can't be in two points of the document simultaneously. So if the node already has a parent, the node is first removed, then appended at the new position. The [`Node.clone_node`](/html/python-net/aspose.html.dom/node/clone_node) method can be used to make a copy of the node before appending it under the new parent. Copies made with [`Node.clone_node`](/html/python-net/aspose.html.dom/node/clone_node) are not be automatically kept in sync. |
| [get_attribute_names](/html/python-net/aspose.html/htmlformelement/get_attribute_names/#) | Returns the attribute names of the element as an Array of strings. If the element has no attributes it returns an empty array. |
| [has_attributes](/html/python-net/aspose.html/htmlformelement/has_attributes/#) | Returns whether this node (if it is an element) has any attributes |
| [get_attribute](/html/python-net/aspose.html/htmlformelement/get_attribute/#str) | Retrieves an attribute value by name. |
| [get_attribute_ns](/html/python-net/aspose.html/htmlformelement/get_attribute_ns/#str-str) | Retrieves an attribute value by local name and namespace URI. |
| [set_attribute](/html/python-net/aspose.html/htmlformelement/set_attribute/#str-str) | Adds a new attribute. If an attribute with that name is already present in the element, its value is changed to be that of the value parameter |
| [set_attribute_ns](/html/python-net/aspose.html/htmlformelement/set_attribute_ns/#str-str-str) | Adds a new attribute. If an attribute with the same local name and namespace URI is already present on the element, its prefix is changed to be the prefix part of the qualifiedName, and its value is changed to be the value parameter. |
| [remove_attribute](/html/python-net/aspose.html/htmlformelement/remove_attribute/#str) | Removes an attribute by name. |
| [remove_attribute_ns](/html/python-net/aspose.html/htmlformelement/remove_attribute_ns/#str-str) | Removes an attribute by local name and namespace URI. |
| [has_attribute](/html/python-net/aspose.html/htmlformelement/has_attribute/#str) | Returns true when an attribute with a given name is specified on this element or has a default value, false otherwise. |
| [has_attribute_ns](/html/python-net/aspose.html/htmlformelement/has_attribute_ns/#str-str) | Returns true when an attribute with a given local name and namespace URI is specified on this element or has a default value, false otherwise. |
| [get_attribute_node](/html/python-net/aspose.html/htmlformelement/get_attribute_node/#str) | Retrieves an attribute node by name. |
| [set_attribute_node](/html/python-net/aspose.html/htmlformelement/set_attribute_node/#aspose.html.dom.Attr) | Adds a new attribute node. If an attribute with that name (nodeName) is already present in the element, it is replaced by the new one. |
| [remove_attribute_node](/html/python-net/aspose.html/htmlformelement/remove_attribute_node/#aspose.html.dom.Attr) | Removes the specified attribute node. |
| [get_attribute_node_ns](/html/python-net/aspose.html/htmlformelement/get_attribute_node_ns/#str-str) | Retrieves an Attr node by local name and namespace URI. |
| [set_attribute_node_ns](/html/python-net/aspose.html/htmlformelement/set_attribute_node_ns/#aspose.html.dom.Attr) | Adds a new attribute. If an attribute with that local name and that namespace URI is already present in the element, it is replaced by the new one. |
| [get_elements_by_tag_name](/html/python-net/aspose.html/htmlformelement/get_elements_by_tag_name/#str) | Returns [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection) object containing all [`Element`](/html/python-net/aspose.html.dom/element) with a given tag name, in document order. |
| [get_elements_by_tag_name_ns](/html/python-net/aspose.html/htmlformelement/get_elements_by_tag_name_ns/#str-str) | Returns [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection) object containing all [`Element`](/html/python-net/aspose.html.dom/element) with a given local name and namespace URI string in document order. |
| [remove](/html/python-net/aspose.html/htmlformelement/remove/#) | Removes this instance. |
| [query_selector_all](/html/python-net/aspose.html/htmlformelement/query_selector_all/#str) | Returns a NodeList of all the Elements in document, which match selector |
| [query_selector](/html/python-net/aspose.html/htmlformelement/query_selector/#str) | Returns the first Element in document, which match selector |
| [attach_shadow](/html/python-net/aspose.html/htmlformelement/attach_shadow/#aspose.html.dom.ShadowRootMode) | Creates shadow root and attaches it to current element. |
| [get_elements_by_class_name](/html/python-net/aspose.html/htmlformelement/get_elements_by_class_name/#str) | Returns [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection) object containing all the elements within [`Element`](/html/python-net/aspose.html.dom/element) that have all the classes specified in argument. |
| [submit](/html/python-net/aspose.html/htmlformelement/submit/#) | Submits the form. It performs the same action as a submit button. |
| [reset](/html/python-net/aspose.html/htmlformelement/reset/#) | Restores a form element's default values. It performs the same action <br/>as a reset button. |



### See Also
* module [`aspose.html`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`Document`](/html/python-net/aspose.html.dom/document)
* class [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment)
* class [`Element`](/html/python-net/aspose.html.dom/element)
* class [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget)
* class [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection)
* class [`HTMLElement`](/html/python-net/aspose.html/htmlelement)
* class [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget)
* class [`Node`](/html/python-net/aspose.html.dom/node)
* class [`NodeList`](/html/python-net/aspose.html.collections/nodelist)
