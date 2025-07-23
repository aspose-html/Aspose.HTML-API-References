---
title: Entity class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 110
url: /python-net/aspose.html.dom/entity/
is_root: false
---

## Entity class

Represents a known entity, either parsed or unparsed, in an XML document.



**Inheritance:** [`Entity`](/html/python-net/aspose.html.dom/entity) → 
[`Node`](/html/python-net/aspose.html.dom/node) → 
[`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The Entity type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [node_type](/html/python-net/aspose.html.dom/entity/node_type) | A code representing the type of the underlying object. |
| [local_name](/html/python-net/aspose.html.dom/entity/local_name) | Returns the local part of the qualified name of this node. <br/>For nodes of any type other than [`Node.ELEMENT_NODE`](/html/python-net/aspose.html.dom/node) and [`Node.ATTRIBUTE_NODE`](/html/python-net/aspose.html.dom/node)<br/>and nodes created with a DOM Level 1 method, such as [`Document.create_element`](/html/python-net/aspose.html.dom/document/create_element), this is always null. |
| [namespace_uri](/html/python-net/aspose.html.dom/entity/namespace_uri) | Returns the namespace URI of the element, or null if the element is not in a namespace. |
| [prefix](/html/python-net/aspose.html.dom/entity/prefix) | Returns the namespace prefix of the specified element, or null if no prefix is specified. |
| [node_name](/html/python-net/aspose.html.dom/entity/node_name) | The name of this node, depending on its type. |
| [base_uri](/html/python-net/aspose.html.dom/entity/base_uri) | Returns the absolute base URL of the document containing the node.<br/><br/><br/>The base URL is used to resolve relative URLs when the browser needs to obtain an absolute URL, <br/>for example when processing the HTML img element's src attribute or the xlink:href or href attributes in SVG. |
| [owner_document](/html/python-net/aspose.html.dom/entity/owner_document) | Returns the top-level document object of the node. |
| [parent_node](/html/python-net/aspose.html.dom/entity/parent_node) | Returns the parent of the specified node in the DOM tree.<br/><br/><br/>[`Document`](/html/python-net/aspose.html.dom/document) and [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment) nodes can never have a parent, so  will always return null. It also returns  if the node has just been created and is not yet attached to the tree. |
| [parent_element](/html/python-net/aspose.html.dom/entity/parent_element) | Returns the DOM node's parent [`Element`](/html/python-net/aspose.html.dom/element), or if the node either has no parent, or its parent isn't a DOM Element. |
| [child_nodes](/html/python-net/aspose.html.dom/entity/child_nodes) | Returns a live [`NodeList`](/html/python-net/aspose.html.collections/nodelist) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [first_child](/html/python-net/aspose.html.dom/entity/first_child) | Returns the node's first child in the tree, or null if the node has no children.<br/><br/><br/>If the node is a Document, this property returns the first node in the list of its direct children. |
| [last_child](/html/python-net/aspose.html.dom/entity/last_child) | Returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [previous_sibling](/html/python-net/aspose.html.dom/entity/previous_sibling) | Returns the node immediately preceding the specified one in its parent's [`Node.child_nodes`](/html/python-net/aspose.html.dom/node#child_nodes) list, or if the specified node is the first in that list. |
| [next_sibling](/html/python-net/aspose.html.dom/entity/next_sibling) | Returns the node immediately following the specified one in their parent's [`Node.child_nodes`](/html/python-net/aspose.html.dom/node#child_nodes), or returns null if the specified node is the last child in the parent element. |
| [node_value](/html/python-net/aspose.html.dom/entity/node_value) | Returns or sets the value of the current node. |
| [text_content](/html/python-net/aspose.html.dom/entity/text_content) | Represents the text content of the node and its descendants. |
| [ELEMENT_NODE](/html/python-net/aspose.html.dom/entity/element_node) | An element node |
| [ATTRIBUTE_NODE](/html/python-net/aspose.html.dom/entity/attribute_node) | An attribute node |
| [TEXT_NODE](/html/python-net/aspose.html.dom/entity/text_node) | A text node |
| [CDATA_SECTION_NODE](/html/python-net/aspose.html.dom/entity/cdata_section_node) | A cdata section node |
| [ENTITY_REFERENCE_NODE](/html/python-net/aspose.html.dom/entity/entity_reference_node) | An entity reference node |
| [ENTITY_NODE](/html/python-net/aspose.html.dom/entity/entity_node) | An entity node |
| [PROCESSING_INSTRUCTION_NODE](/html/python-net/aspose.html.dom/entity/processing_instruction_node) | A processing instruction node |
| [COMMENT_NODE](/html/python-net/aspose.html.dom/entity/comment_node) | A comment node |
| [DOCUMENT_NODE](/html/python-net/aspose.html.dom/entity/document_node) | A document node |
| [DOCUMENT_TYPE_NODE](/html/python-net/aspose.html.dom/entity/document_type_node) | A document type node |
| [DOCUMENT_FRAGMENT_NODE](/html/python-net/aspose.html.dom/entity/document_fragment_node) | A document fragment node |
| [NOTATION_NODE](/html/python-net/aspose.html.dom/entity/notation_node) | A notation node |
| [public_id](/html/python-net/aspose.html.dom/entity/public_id) | The public identifier associated with the entity if specified, and null otherwise. |
| [system_id](/html/python-net/aspose.html.dom/entity/system_id) | The system identifier associated with the entity if specified, and null otherwise. This may be an absolute URI or not. |
| [notation_name](/html/python-net/aspose.html.dom/entity/notation_name) | For unparsed entities, the name of the notation for the entity. For parsed entities, this is null. |
| [input_encoding](/html/python-net/aspose.html.dom/entity/input_encoding) | An attribute specifying the encoding used for this entity at the time of parsing, when it is an external parsed entity. This is null if it an entity from the internal subset or if it is not known. |
| [xml_encoding](/html/python-net/aspose.html.dom/entity/xml_encoding) | An attribute specifying, as part of the text declaration, the encoding of this entity, when it is an external parsed entity. This is null otherwise. |
| [xml_version](/html/python-net/aspose.html.dom/entity/xml_version) | An attribute specifying, as part of the text declaration, the version number of this entity, when it is an external parsed entity. This is null otherwise. |


### Methods
| Method | Description |
| :- | :- |
| [add_event_listener](/html/python-net/aspose.html.dom/entity/add_event_listener/#str-aspose.html.dom.events.IEventListener) | Sets up a function that will be called whenever the specified event is delivered to the target.<br/><br/><br/>It works by adding a function, or an object that implements [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener),<br/>to the list of event listeners for the specified event type on the [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) on which it's called.<br/>If the function or object, is already in the list of event listeners for this target, they are not added a second time. |
| [add_event_listener](/html/python-net/aspose.html.dom/entity/add_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | Sets up a function that will be called whenever the specified event is delivered to the target.<br/><br/><br/>It works by adding a function, or an object that implements [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener),<br/>to the list of event listeners for the specified event type on the [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) on which it's called.<br/>If the function or object, is already in the list of event listeners for this target, they are not added a second time. |
| [remove_event_listener](/html/python-net/aspose.html.dom/entity/remove_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [remove_event_listener](/html/python-net/aspose.html.dom/entity/remove_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the removal of event listeners from the event target.<br/>If an [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions.<br/>Event Listeners can never be invoked after being removed. |
| [clone_node](/html/python-net/aspose.html.dom/entity/clone_node/#) | Returns a duplicate of the node on which this method was called.<br/><br/><br/>Cloning a node copies all of its attributes and their values, including intrinsic (inline) listeners. It does not copy event listeners added using [`IEventTarget.add_event_listener`](/html/python-net/aspose.html.dom.events/ieventtarget/add_event_listener) or those assigned to element properties (e.g., node.onclick = someFunction). Additionally, for a HTMLCanvasElement element, the painted image is not copied. |
| [clone_node](/html/python-net/aspose.html.dom/entity/clone_node/#bool) | Returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not.<br/><br/><br/>Cloning a node copies all of its attributes and their values, including intrinsic (inline) listeners. <br/>It does not copy event listeners added using [`IEventTarget.add_event_listener`](/html/python-net/aspose.html.dom.events/ieventtarget/add_event_listener)<br/>or those assigned to element properties (e.g., node.onclick = someFunction). Additionally, for a HTMLCanvasElement element, the painted image is not copied. |
| [get_platform_type](/html/python-net/aspose.html.dom/entity/get_platform_type/#) | This method is used to retrieve the ECMAScript object Type. |
| [dispatch_event](/html/python-net/aspose.html.dom/entity/dispatch_event/#aspose.html.dom.events.Event) | Dispatches an Event at the specified [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget), (synchronously) invoking<br/>the affected EventListeners in the appropriate order. <br/>The normal event processing rules (including the capturing and optional bubbling phase) also apply to events <br/>dispatched manually with [`IEventTarget.dispatch_event`](/html/python-net/aspose.html.dom.events/ieventtarget/dispatch_event). |
| [has_child_nodes](/html/python-net/aspose.html.dom/entity/has_child_nodes/#) | Returns a boolean value indicating whether the given [`Node`](/html/python-net/aspose.html.dom/node) has child nodes or not. |
| [normalize](/html/python-net/aspose.html.dom/entity/normalize/#) | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [is_equal_node](/html/python-net/aspose.html.dom/entity/is_equal_node/#aspose.html.dom.Node) | Tests whether two nodes are equal.<br/>This method tests for equality of nodes, not sameness (i.e., whether the two nodes are references to the same object) which can be tested with Node.isSameNode(). All nodes that are the same will also be equal, though the reverse may not be true. |
| [is_same_node](/html/python-net/aspose.html.dom/entity/is_same_node/#aspose.html.dom.Node) | Method is a legacy alias the for the  strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [lookup_prefix](/html/python-net/aspose.html.dom/entity/lookup_prefix/#str) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. <br/>See Namespace Prefix Lookup for details on the algorithm used by this method. |
| [lookup_namespace_uri](/html/python-net/aspose.html.dom/entity/lookup_namespace_uri/#str) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [is_default_namespace](/html/python-net/aspose.html.dom/entity/is_default_namespace/#str) | This method checks if the specified namespaceURI is the default namespace or not. |
| [insert_before](/html/python-net/aspose.html.dom/entity/insert_before/#aspose.html.dom.Node-aspose.html.dom.Node) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children.<br/>If child is a DocumentFragment object, all of its children are inserted, in the same order, before child. If the child is already in the tree, it is first removed. |
| [replace_child](/html/python-net/aspose.html.dom/entity/replace_child/#aspose.html.dom.Node-aspose.html.dom.Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. <br/>If newChild is a DocumentFragment object, oldChild is replaced by all of the DocumentFragment children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [remove_child](/html/python-net/aspose.html.dom/entity/remove_child/#aspose.html.dom.Node) | Removes a child node from the DOM and returns the removed node. |
| [append_child](/html/python-net/aspose.html.dom/entity/append_child/#aspose.html.dom.Node) | Adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, [`Node.append_child`](/html/python-net/aspose.html.dom/node/append_child) moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node).<br/><br/><br/>This means that a node can't be in two points of the document simultaneously. So if the node already has a parent, the node is first removed, then appended at the new position. The [`Node.clone_node`](/html/python-net/aspose.html.dom/node/clone_node) method can be used to make a copy of the node before appending it under the new parent. Copies made with [`Node.clone_node`](/html/python-net/aspose.html.dom/node/clone_node) are not be automatically kept in sync. |



### See Also
* module [`aspose.html.dom`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`Document`](/html/python-net/aspose.html.dom/document)
* class [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment)
* class [`Element`](/html/python-net/aspose.html.dom/element)
* class [`Entity`](/html/python-net/aspose.html.dom/entity)
* class [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget)
* class [`Node`](/html/python-net/aspose.html.dom/node)
* class [`NodeList`](/html/python-net/aspose.html.collections/nodelist)
