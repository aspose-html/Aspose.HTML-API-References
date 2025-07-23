---
title: HTMLInputElement class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 330
url: /python-net/aspose.html/htmlinputelement/
is_root: false
---

## HTMLInputElement class

Form control.Depending upon the environment in which the page is being 
viewed, the value property may be read-only for the file upload input 
type. For the "password" input type, the actual value returned may be 
masked to prevent unauthorized use. See the INPUT element definition in [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)].

See also the [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).



**Inheritance:** [`HTMLInputElement`](/html/python-net/aspose.html/htmlinputelement) → 
[`HTMLElement`](/html/python-net/aspose.html/htmlelement) → 
[`Element`](/html/python-net/aspose.html.dom/element) → 
[`Node`](/html/python-net/aspose.html.dom/node) → 
[`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The HTMLInputElement type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [node_type](/html/python-net/aspose.html/htmlinputelement/node_type) | A code representing the type of the underlying object. |
| [local_name](/html/python-net/aspose.html/htmlinputelement/local_name) | Returns the local part of the qualified name of this node.<br/>For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| [namespace_uri](/html/python-net/aspose.html/htmlinputelement/namespace_uri) | The namespace URI of this node, or null if it is unspecified. |
| [prefix](/html/python-net/aspose.html/htmlinputelement/prefix) | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [node_name](/html/python-net/aspose.html/htmlinputelement/node_name) | The name of this node, depending on its type. |
| [base_uri](/html/python-net/aspose.html/htmlinputelement/base_uri) | Returns the absolute base URL of the document containing the node.<br/><br/><br/>The base URL is used to resolve relative URLs when the browser needs to obtain an absolute URL, <br/>for example when processing the HTML img element's src attribute or the xlink:href or href attributes in SVG. |
| [owner_document](/html/python-net/aspose.html/htmlinputelement/owner_document) | Returns the top-level document object of the node. |
| [parent_node](/html/python-net/aspose.html/htmlinputelement/parent_node) | Returns the parent of the specified node in the DOM tree.<br/><br/><br/>[`Document`](/html/python-net/aspose.html.dom/document) and [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment) nodes can never have a parent, so  will always return null. It also returns  if the node has just been created and is not yet attached to the tree. |
| [parent_element](/html/python-net/aspose.html/htmlinputelement/parent_element) | Returns the DOM node's parent [`Element`](/html/python-net/aspose.html.dom/element), or if the node either has no parent, or its parent isn't a DOM Element. |
| [child_nodes](/html/python-net/aspose.html/htmlinputelement/child_nodes) | Returns a live [`NodeList`](/html/python-net/aspose.html.collections/nodelist) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [first_child](/html/python-net/aspose.html/htmlinputelement/first_child) | Returns the node's first child in the tree, or null if the node has no children.<br/><br/><br/>If the node is a Document, this property returns the first node in the list of its direct children. |
| [last_child](/html/python-net/aspose.html/htmlinputelement/last_child) | Returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [previous_sibling](/html/python-net/aspose.html/htmlinputelement/previous_sibling) | Returns the node immediately preceding the specified one in its parent's [`Node.child_nodes`](/html/python-net/aspose.html.dom/node#child_nodes) list, or if the specified node is the first in that list. |
| [next_sibling](/html/python-net/aspose.html/htmlinputelement/next_sibling) | Returns the node immediately following the specified one in their parent's [`Node.child_nodes`](/html/python-net/aspose.html.dom/node#child_nodes), or returns null if the specified node is the last child in the parent element. |
| [node_value](/html/python-net/aspose.html/htmlinputelement/node_value) | Returns or sets the value of the current node. |
| [text_content](/html/python-net/aspose.html/htmlinputelement/text_content) | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [ELEMENT_NODE](/html/python-net/aspose.html/htmlinputelement/element_node) | An element node |
| [ATTRIBUTE_NODE](/html/python-net/aspose.html/htmlinputelement/attribute_node) | An attribute node |
| [TEXT_NODE](/html/python-net/aspose.html/htmlinputelement/text_node) | A text node |
| [CDATA_SECTION_NODE](/html/python-net/aspose.html/htmlinputelement/cdata_section_node) | A cdata section node |
| [ENTITY_REFERENCE_NODE](/html/python-net/aspose.html/htmlinputelement/entity_reference_node) | An entity reference node |
| [ENTITY_NODE](/html/python-net/aspose.html/htmlinputelement/entity_node) | An entity node |
| [PROCESSING_INSTRUCTION_NODE](/html/python-net/aspose.html/htmlinputelement/processing_instruction_node) | A processing instruction node |
| [COMMENT_NODE](/html/python-net/aspose.html/htmlinputelement/comment_node) | A comment node |
| [DOCUMENT_NODE](/html/python-net/aspose.html/htmlinputelement/document_node) | A document node |
| [DOCUMENT_TYPE_NODE](/html/python-net/aspose.html/htmlinputelement/document_type_node) | A document type node |
| [DOCUMENT_FRAGMENT_NODE](/html/python-net/aspose.html/htmlinputelement/document_fragment_node) | A document fragment node |
| [NOTATION_NODE](/html/python-net/aspose.html/htmlinputelement/notation_node) | A notation node |
| [class_list](/html/python-net/aspose.html/htmlinputelement/class_list) | Returns a live DOMTokenList which contains tokens received from parsing the "class" attribute. |
| [tag_name](/html/python-net/aspose.html/htmlinputelement/tag_name) | The name of the element. |
| [id](/html/python-net/aspose.html/htmlinputelement/id) | The element's identifier. See the id attribute definition in HTML 4.01. |
| [class_name](/html/python-net/aspose.html/htmlinputelement/class_name) | The class attribute of the element. This attribute has been renamed due <br/>to conflicts with the "class" keyword exposed by many languages. See <br/>the class attribute definition in HTML 4.01. |
| [attributes](/html/python-net/aspose.html/htmlinputelement/attributes) | A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| [first_element_child](/html/python-net/aspose.html/htmlinputelement/first_element_child) | Returns the first child element node of this element. null if this element has no child elements. |
| [last_element_child](/html/python-net/aspose.html/htmlinputelement/last_element_child) | Returns the last child element node of this element. null if this element has no child elements. |
| [previous_element_sibling](/html/python-net/aspose.html/htmlinputelement/previous_element_sibling) | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [next_element_sibling](/html/python-net/aspose.html/htmlinputelement/next_element_sibling) | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [child_element_count](/html/python-net/aspose.html/htmlinputelement/child_element_count) | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [children](/html/python-net/aspose.html/htmlinputelement/children) | Returns the child elements of current element. |
| [inner_html](/html/python-net/aspose.html/htmlinputelement/inner_html) | Returns a fragment of HTML or XML that represents the element's contents.<br/>Can be set, to replace the contents of the element with nodes parsed from the given string. |
| [outer_html](/html/python-net/aspose.html/htmlinputelement/outer_html) | Returns a fragment of HTML or XML that represents the element and its contents.<br/>Can be set, to replace the element with nodes parsed from the given string. |
| [shadow_root](/html/python-net/aspose.html/htmlinputelement/shadow_root) | Returns shadowRoot stored on this element or null if it's closed. |
| [title](/html/python-net/aspose.html/htmlinputelement/title) | The element's advisory title. See the title attribute definition in <br/>HTML 4.01. |
| [lang](/html/python-net/aspose.html/htmlinputelement/lang) | Language code defined in RFC 1766. See the lang attribute definition in <br/>HTML 4.01. |
| [dir](/html/python-net/aspose.html/htmlinputelement/dir) | Specifies the base direction of directionally neutral text and the <br/>directionality of tables. See the dir attribute definition in HTML <br/>4.01. |
| [style](/html/python-net/aspose.html/htmlinputelement/style) | Represents a style attribute that allows author to directly apply style information to specific element. |
| [default_value](/html/python-net/aspose.html/htmlinputelement/default_value) | When the `type` attribute of the element has the value <br/>"text", "file" or "password", this represents the HTML value <br/>attribute of the element. The value of this attribute does not change <br/>if the contents of the corresponding form control, in an interactive <br/>user agent, changes. See the value attribute definition in HTML 4.01. |
| [default_checked](/html/python-net/aspose.html/htmlinputelement/default_checked) | When `type` has the value "radio" or "checkbox", this <br/>represents the HTML checked attribute of the element. The value of <br/>this attribute does not change if the state of the corresponding form <br/>control, in an interactive user agent, changes. See the checked <br/>attribute definition in HTML 4.01. |
| [form](/html/python-net/aspose.html/htmlinputelement/form) | Returns the `FORM` element containing this control. Returns <br/>`null` if this control is not within the context of a <br/>form. |
| [files](/html/python-net/aspose.html/htmlinputelement/files) | The files IDL attribute allows scripts to access the element’s selected files.<br/>On getting, if the IDL attribute applies, it must return a FileList object that represents the current selected files. <br/>The same object must be returned until the list of selected files changes. If the IDL attribute does not apply, then it must instead return null.  [FILEAPI] |
| [accept](/html/python-net/aspose.html/htmlinputelement/accept) | A comma-separated list of content types that a server processing this <br/>form will handle correctly. See the accept attribute definition in <br/>HTML 4.01. |
| [access_key](/html/python-net/aspose.html/htmlinputelement/access_key) | A single character access key to give access to the form control. See <br/>the accesskey attribute definition in HTML 4.01. |
| [align](/html/python-net/aspose.html/htmlinputelement/align) | Aligns this object (vertically or horizontally) with respect to its <br/>surrounding text. See the align attribute definition in HTML 4.01. <br/>This attribute is deprecated in HTML 4.01. |
| [alt](/html/python-net/aspose.html/htmlinputelement/alt) | Alternate text for user agents not rendering the normal content of this <br/>element. See the alt attribute definition in HTML 4.01. |
| [checked](/html/python-net/aspose.html/htmlinputelement/checked) | When the `type` attribute of the element has the value <br/>"radio" or "checkbox", this represents the current state of the form <br/>control, in an interactive user agent. Changes to this attribute <br/>change the state of the form control, but do not change the value of <br/>the HTML checked attribute of the INPUT element.During the handling <br/>of a click event on an input element with a type attribute that has <br/>the value "radio" or "checkbox", some implementations may change the <br/>value of this property before the event is being dispatched in the <br/>document. If the default action of the event is canceled, the value <br/>of the property may be changed back to its original value. This means <br/>that the value of this property during the handling of click events <br/>is implementation dependent. |
| [disabled](/html/python-net/aspose.html/htmlinputelement/disabled) | The control is unavailable in this context. See the disabled attribute <br/>definition in HTML 4.01. |
| [list](/html/python-net/aspose.html/htmlinputelement/list) | The list attribute is used to identify an element that lists predefined options suggested to the user.<br/>If present, its value must be the ID of a datalist element in the same document. |
| [max_length](/html/python-net/aspose.html/htmlinputelement/max_length) | Maximum number of characters for text fields, when `type` <br/>has the value "text" or "password". See the maxlength attribute <br/>definition in HTML 4.01. |
| [name](/html/python-net/aspose.html/htmlinputelement/name) | Form control or object name when submitted with a form. See the name <br/>attribute definition in HTML 4.01. |
| [read_only](/html/python-net/aspose.html/htmlinputelement/read_only) | This control is read-only. Relevant only when `type` has the <br/>value "text" or "password". See the readonly attribute definition in <br/>HTML 4.01. |
| [size](/html/python-net/aspose.html/htmlinputelement/size) | Size information. The precise meaning is specific to each type of <br/>field. See the size attribute definition in HTML 4.01.<br/>@version DOM Level 2 |
| [src](/html/python-net/aspose.html/htmlinputelement/src) | When the `type` attribute has the value "image", this <br/>attribute specifies the location of the image to be used to decorate <br/>the graphical submit button. See the src attribute definition in HTML <br/>4.01. |
| [tab_index](/html/python-net/aspose.html/htmlinputelement/tab_index) | Index that represents the element's position in the tabbing order. See <br/>the tabindex attribute definition in HTML 4.01. |
| [type](/html/python-net/aspose.html/htmlinputelement/type) | The type of control created (all lower case). See the type attribute definition in HTML 4.01. @version DOM Level 2 |
| [use_map](/html/python-net/aspose.html/htmlinputelement/use_map) | Use client-side image map. See the usemap attribute definition in HTML <br/>4.01. |
| [value](/html/python-net/aspose.html/htmlinputelement/value) | When the `type` attribute of the element has the value <br/>"text", "file" or "password", this represents the current contents of <br/>the corresponding form control, in an interactive user agent. <br/>Changing this attribute changes the contents of the form control, but <br/>does not change the value of the HTML value attribute of the element. <br/>When the `type` attribute of the element has the value <br/>"button", "hidden", "submit", "reset", "image", "checkbox" or <br/>"radio", this represents the HTML value attribute of the element. See <br/>the value attribute definition in HTML 4.01. |


### Methods
| Method | Description |
| :- | :- |
| [add_event_listener](/html/python-net/aspose.html/htmlinputelement/add_event_listener/#str-aspose.html.dom.events.IEventListener) | Sets up a function that will be called whenever the specified event is delivered to the target.<br/><br/><br/>It works by adding a function, or an object that implements [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener),<br/>to the list of event listeners for the specified event type on the [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) on which it's called.<br/>If the function or object, is already in the list of event listeners for this target, they are not added a second time. |
| [add_event_listener](/html/python-net/aspose.html/htmlinputelement/add_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | Sets up a function that will be called whenever the specified event is delivered to the target.<br/><br/><br/>It works by adding a function, or an object that implements [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener),<br/>to the list of event listeners for the specified event type on the [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) on which it's called.<br/>If the function or object, is already in the list of event listeners for this target, they are not added a second time. |
| [remove_event_listener](/html/python-net/aspose.html/htmlinputelement/remove_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [remove_event_listener](/html/python-net/aspose.html/htmlinputelement/remove_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [clone_node](/html/python-net/aspose.html/htmlinputelement/clone_node/#) | Returns a duplicate of the node on which this method was called.<br/><br/><br/>Cloning a node copies all of its attributes and their values, including intrinsic (inline) listeners. It does not copy event listeners added using [`IEventTarget.add_event_listener`](/html/python-net/aspose.html.dom.events/ieventtarget/add_event_listener) or those assigned to element properties (e.g., node.onclick = someFunction). Additionally, for a HTMLCanvasElement element, the painted image is not copied. |
| [clone_node](/html/python-net/aspose.html/htmlinputelement/clone_node/#bool) | Returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not.<br/><br/><br/>Cloning a node copies all of its attributes and their values, including intrinsic (inline) listeners. <br/>It does not copy event listeners added using [`IEventTarget.add_event_listener`](/html/python-net/aspose.html.dom.events/ieventtarget/add_event_listener)<br/>or those assigned to element properties (e.g., node.onclick = someFunction). Additionally, for a HTMLCanvasElement element, the painted image is not copied. |
| [toggle_attribute](/html/python-net/aspose.html/htmlinputelement/toggle_attribute/#str) | If force is not given, "toggles" qualifiedName, removing it if it is present and adding it if it is not present. If force is true, adds qualifiedName.<br/>If force is false, removes qualifiedName. |
| [toggle_attribute](/html/python-net/aspose.html/htmlinputelement/toggle_attribute/#str-bool) | If force is not given, "toggles" qualifiedName, removing it if it is present and adding it if it is not present. If force is true, adds qualifiedName.<br/>If force is false, removes qualifiedName. |
| [get_platform_type](/html/python-net/aspose.html/htmlinputelement/get_platform_type/#) | This method is used to retrieve the ECMAScript object Type. |
| [dispatch_event](/html/python-net/aspose.html/htmlinputelement/dispatch_event/#aspose.html.dom.events.Event) | Dispatches an Event at the specified [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget), (synchronously) invoking<br/>the affected EventListeners in the appropriate order. <br/>The normal event processing rules (including the capturing and optional bubbling phase) also apply to events <br/>dispatched manually with [`IEventTarget.dispatch_event`](/html/python-net/aspose.html.dom.events/ieventtarget/dispatch_event). |
| [has_child_nodes](/html/python-net/aspose.html/htmlinputelement/has_child_nodes/#) | Returns a boolean value indicating whether the given [`Node`](/html/python-net/aspose.html.dom/node) has child nodes or not. |
| [normalize](/html/python-net/aspose.html/htmlinputelement/normalize/#) | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [is_equal_node](/html/python-net/aspose.html/htmlinputelement/is_equal_node/#aspose.html.dom.Node) | Tests whether two nodes are equal.<br/>This method tests for equality of nodes, not sameness (i.e., whether the two nodes are references to the same object) which can be tested with Node.isSameNode(). All nodes that are the same will also be equal, though the reverse may not be true. |
| [is_same_node](/html/python-net/aspose.html/htmlinputelement/is_same_node/#aspose.html.dom.Node) | Method is a legacy alias the for the  strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [lookup_prefix](/html/python-net/aspose.html/htmlinputelement/lookup_prefix/#str) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. <br/>See Namespace Prefix Lookup for details on the algorithm used by this method. |
| [lookup_namespace_uri](/html/python-net/aspose.html/htmlinputelement/lookup_namespace_uri/#str) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [is_default_namespace](/html/python-net/aspose.html/htmlinputelement/is_default_namespace/#str) | This method checks if the specified namespaceURI is the default namespace or not. |
| [insert_before](/html/python-net/aspose.html/htmlinputelement/insert_before/#aspose.html.dom.Node-aspose.html.dom.Node) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children.<br/>If child is a DocumentFragment object, all of its children are inserted, in the same order, before child. If the child is already in the tree, it is first removed. |
| [replace_child](/html/python-net/aspose.html/htmlinputelement/replace_child/#aspose.html.dom.Node-aspose.html.dom.Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. <br/>If newChild is a DocumentFragment object, oldChild is replaced by all of the DocumentFragment children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [remove_child](/html/python-net/aspose.html/htmlinputelement/remove_child/#aspose.html.dom.Node) | Removes a child node from the DOM and returns the removed node. |
| [append_child](/html/python-net/aspose.html/htmlinputelement/append_child/#aspose.html.dom.Node) | Adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, [`Node.append_child`](/html/python-net/aspose.html.dom/node/append_child) moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node).<br/><br/><br/>This means that a node can't be in two points of the document simultaneously. So if the node already has a parent, the node is first removed, then appended at the new position. The [`Node.clone_node`](/html/python-net/aspose.html.dom/node/clone_node) method can be used to make a copy of the node before appending it under the new parent. Copies made with [`Node.clone_node`](/html/python-net/aspose.html.dom/node/clone_node) are not be automatically kept in sync. |
| [get_attribute_names](/html/python-net/aspose.html/htmlinputelement/get_attribute_names/#) | Returns the attribute names of the element as an Array of strings. If the element has no attributes it returns an empty array. |
| [has_attributes](/html/python-net/aspose.html/htmlinputelement/has_attributes/#) | Returns whether this node (if it is an element) has any attributes |
| [get_attribute](/html/python-net/aspose.html/htmlinputelement/get_attribute/#str) | Retrieves an attribute value by name. |
| [get_attribute_ns](/html/python-net/aspose.html/htmlinputelement/get_attribute_ns/#str-str) | Retrieves an attribute value by local name and namespace URI. |
| [set_attribute](/html/python-net/aspose.html/htmlinputelement/set_attribute/#str-str) | Adds a new attribute. If an attribute with that name is already present in the element, its value is changed to be that of the value parameter |
| [set_attribute_ns](/html/python-net/aspose.html/htmlinputelement/set_attribute_ns/#str-str-str) | Adds a new attribute. If an attribute with the same local name and namespace URI is already present on the element, its prefix is changed to be the prefix part of the qualifiedName, and its value is changed to be the value parameter. |
| [remove_attribute](/html/python-net/aspose.html/htmlinputelement/remove_attribute/#str) | Removes an attribute by name. |
| [remove_attribute_ns](/html/python-net/aspose.html/htmlinputelement/remove_attribute_ns/#str-str) | Removes an attribute by local name and namespace URI. |
| [has_attribute](/html/python-net/aspose.html/htmlinputelement/has_attribute/#str) | Returns true when an attribute with a given name is specified on this element or has a default value, false otherwise. |
| [has_attribute_ns](/html/python-net/aspose.html/htmlinputelement/has_attribute_ns/#str-str) | Returns true when an attribute with a given local name and namespace URI is specified on this element or has a default value, false otherwise. |
| [get_attribute_node](/html/python-net/aspose.html/htmlinputelement/get_attribute_node/#str) | Retrieves an attribute node by name. |
| [set_attribute_node](/html/python-net/aspose.html/htmlinputelement/set_attribute_node/#aspose.html.dom.Attr) | Adds a new attribute node. If an attribute with that name (nodeName) is already present in the element, it is replaced by the new one. |
| [remove_attribute_node](/html/python-net/aspose.html/htmlinputelement/remove_attribute_node/#aspose.html.dom.Attr) | Removes the specified attribute node. |
| [get_attribute_node_ns](/html/python-net/aspose.html/htmlinputelement/get_attribute_node_ns/#str-str) | Retrieves an Attr node by local name and namespace URI. |
| [set_attribute_node_ns](/html/python-net/aspose.html/htmlinputelement/set_attribute_node_ns/#aspose.html.dom.Attr) | Adds a new attribute. If an attribute with that local name and that namespace URI is already present in the element, it is replaced by the new one. |
| [get_elements_by_tag_name](/html/python-net/aspose.html/htmlinputelement/get_elements_by_tag_name/#str) | Returns [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection) object containing all [`Element`](/html/python-net/aspose.html.dom/element) with a given tag name, in document order. |
| [get_elements_by_tag_name_ns](/html/python-net/aspose.html/htmlinputelement/get_elements_by_tag_name_ns/#str-str) | Returns [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection) object containing all [`Element`](/html/python-net/aspose.html.dom/element) with a given local name and namespace URI string in document order. |
| [remove](/html/python-net/aspose.html/htmlinputelement/remove/#) | Removes this instance. |
| [query_selector_all](/html/python-net/aspose.html/htmlinputelement/query_selector_all/#str) | Returns a NodeList of all the Elements in document, which match selector |
| [query_selector](/html/python-net/aspose.html/htmlinputelement/query_selector/#str) | Returns the first Element in document, which match selector |
| [attach_shadow](/html/python-net/aspose.html/htmlinputelement/attach_shadow/#aspose.html.dom.ShadowRootMode) | Creates shadow root and attaches it to current element. |
| [get_elements_by_class_name](/html/python-net/aspose.html/htmlinputelement/get_elements_by_class_name/#str) | Returns [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection) object containing all the elements within [`Element`](/html/python-net/aspose.html.dom/element) that have all the classes specified in argument. |



### See Also
* module [`aspose.html`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`Document`](/html/python-net/aspose.html.dom/document)
* class [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment)
* class [`Element`](/html/python-net/aspose.html.dom/element)
* class [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget)
* class [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection)
* class [`HTMLElement`](/html/python-net/aspose.html/htmlelement)
* class [`HTMLInputElement`](/html/python-net/aspose.html/htmlinputelement)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget)
* class [`Node`](/html/python-net/aspose.html.dom/node)
* class [`NodeList`](/html/python-net/aspose.html.collections/nodelist)
