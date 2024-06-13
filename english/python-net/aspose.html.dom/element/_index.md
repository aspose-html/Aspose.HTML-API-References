﻿---
title: Element class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 100
url: /python-net/aspose.html.dom/element/
is_root: false
---

## Element class

The Element interface represents an element in an HTML or XML document.



**Inheritance:** [`Element`](/html/python-net/aspose.html.dom/element) → 
[`Node`](/html/python-net/aspose.html.dom/node) → 
[`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The Element type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/html/python-net/aspose.html.dom/element/__init__/#aspose.html.dom.QualifiedName-aspose.html.dom.Document) | Initializes a new instance of the [`Element`](/html/python-net/aspose.html.dom/element) class. Don't call this constructor directly, use [`Document.create_element`](/html/python-net/aspose.html.dom/document/create_element) or [`Document.create_element_ns`](/html/python-net/aspose.html.dom/document/create_element_ns). |


### Properties
| Property | Description |
| :- | :- |
| [node_type](/html/python-net/aspose.html.dom/element/node_type) | A code representing the type of the underlying object. |
| [local_name](/html/python-net/aspose.html.dom/element/local_name) | Returns the local part of the qualified name of this node.
| [namespace_uri](/html/python-net/aspose.html.dom/element/namespace_uri) | The namespace URI of this node, or null if it is unspecified. |
| [prefix](/html/python-net/aspose.html.dom/element/prefix) | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [node_name](/html/python-net/aspose.html.dom/element/node_name) | The name of this node, depending on its type. |
| [base_uri](/html/python-net/aspose.html.dom/element/base_uri) | The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
| [owner_document](/html/python-net/aspose.html.dom/element/owner_document) | The Document object associated with this node. This is also the Document object used to create new nodes. When this node is a Document or a DocumentType which is not used with any Document yet, this is null. |
| [parent_node](/html/python-net/aspose.html.dom/element/parent_node) | The parent of this node. All nodes, except Attr, Document, DocumentFragment, Entity, and Notation may have a parent. However, if a node has just been created and not yet added to the tree, or if it has been removed from the tree, this is null. |
| [parent_element](/html/python-net/aspose.html.dom/element/parent_element) | Gets the parent [`Element`](/html/python-net/aspose.html.dom/element) of this node. |
| [child_nodes](/html/python-net/aspose.html.dom/element/child_nodes) | A NodeList that contains all children of this node. If there are no children, this is a NodeList containing no nodes.. |
| [first_child](/html/python-net/aspose.html.dom/element/first_child) | The first child of this node. If there is no such node, this returns null. |
| [last_child](/html/python-net/aspose.html.dom/element/last_child) | The last child of this node. If there is no such node, this returns null. |
| [previous_sibling](/html/python-net/aspose.html.dom/element/previous_sibling) | The node immediately preceding this node. If there is no such node, this returns null. |
| [next_sibling](/html/python-net/aspose.html.dom/element/next_sibling) | The node immediately following this node. If there is no such node, this returns null. |
| [node_value](/html/python-net/aspose.html.dom/element/node_value) | The value of this node, depending on its type. |
| [text_content](/html/python-net/aspose.html.dom/element/text_content) | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [ELEMENT_NODE](/html/python-net/aspose.html.dom/element/element_node) | An element node |
| [ATTRIBUTE_NODE](/html/python-net/aspose.html.dom/element/attribute_node) | An attribute node |
| [TEXT_NODE](/html/python-net/aspose.html.dom/element/text_node) | A text node |
| [CDATA_SECTION_NODE](/html/python-net/aspose.html.dom/element/cdata_section_node) | A cdata section node |
| [ENTITY_REFERENCE_NODE](/html/python-net/aspose.html.dom/element/entity_reference_node) | An entity reference node |
| [ENTITY_NODE](/html/python-net/aspose.html.dom/element/entity_node) | An entity node |
| [PROCESSING_INSTRUCTION_NODE](/html/python-net/aspose.html.dom/element/processing_instruction_node) | A processing instruction node |
| [COMMENT_NODE](/html/python-net/aspose.html.dom/element/comment_node) | A comment node |
| [DOCUMENT_NODE](/html/python-net/aspose.html.dom/element/document_node) | A document node |
| [DOCUMENT_TYPE_NODE](/html/python-net/aspose.html.dom/element/document_type_node) | A document type node |
| [DOCUMENT_FRAGMENT_NODE](/html/python-net/aspose.html.dom/element/document_fragment_node) | A document fragment node |
| [NOTATION_NODE](/html/python-net/aspose.html.dom/element/notation_node) | A notation node |
| [class_list](/html/python-net/aspose.html.dom/element/class_list) | Returns a live DOMTokenList which contains tokens received from parsing the "class" attribute. |
| [tag_name](/html/python-net/aspose.html.dom/element/tag_name) | The name of the element. |
| [id](/html/python-net/aspose.html.dom/element/id) | The element's identifier. See the id attribute definition in HTML 4.01. |
| [class_name](/html/python-net/aspose.html.dom/element/class_name) | The class attribute of the element. This attribute has been renamed due
| [attributes](/html/python-net/aspose.html.dom/element/attributes) | A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| [first_element_child](/html/python-net/aspose.html.dom/element/first_element_child) | Returns the first child element node of this element. null if this element has no child elements. |
| [last_element_child](/html/python-net/aspose.html.dom/element/last_element_child) | Returns the last child element node of this element. null if this element has no child elements. |
| [previous_element_sibling](/html/python-net/aspose.html.dom/element/previous_element_sibling) | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [next_element_sibling](/html/python-net/aspose.html.dom/element/next_element_sibling) | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [child_element_count](/html/python-net/aspose.html.dom/element/child_element_count) | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [children](/html/python-net/aspose.html.dom/element/children) | Returns the child elements of current element. |
| [inner_html](/html/python-net/aspose.html.dom/element/inner_html) | Returns a fragment of HTML or XML that represents the element's contents.
| [outer_html](/html/python-net/aspose.html.dom/element/outer_html) | Returns a fragment of HTML or XML that represents the element and its contents.
| [shadow_root](/html/python-net/aspose.html.dom/element/shadow_root) | Returns shadowRoot stored on this element or null if it's closed. |


### Methods
| Method | Description |
| :- | :- |
| [add_event_listener](/html/python-net/aspose.html.dom/element/add_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the registration of event listeners on the event target. |
| [add_event_listener](/html/python-net/aspose.html.dom/element/add_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the registration of event listeners on the event target. |
| [remove_event_listener](/html/python-net/aspose.html.dom/element/remove_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the removal of event listeners from the event target.
| [remove_event_listener](/html/python-net/aspose.html.dom/element/remove_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the removal of event listeners from the event target.
| [clone_node](/html/python-net/aspose.html.dom/element/clone_node/#) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [clone_node](/html/python-net/aspose.html.dom/element/clone_node/#bool) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [toggle_attribute](/html/python-net/aspose.html.dom/element/toggle_attribute/#str) | If force is not given, "toggles" qualifiedName, removing it if it is present and adding it if it is not present. If force is true, adds qualifiedName.
| [toggle_attribute](/html/python-net/aspose.html.dom/element/toggle_attribute/#str-bool) | If force is not given, "toggles" qualifiedName, removing it if it is present and adding it if it is not present. If force is true, adds qualifiedName.
| [get_platform_type](/html/python-net/aspose.html.dom/element/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [dispatch_event](/html/python-net/aspose.html.dom/element/dispatch_event/#aspose.html.dom.events.Event) | This method allows the dispatch of events into the implementations event model. |
| [has_child_nodes](/html/python-net/aspose.html.dom/element/has_child_nodes/#) | Returns whether this node has any children. |
| [normalize](/html/python-net/aspose.html.dom/element/normalize/#) | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [is_equal_node](/html/python-net/aspose.html.dom/element/is_equal_node/#aspose.html.dom.Node) | Tests whether two nodes are equal.
| [is_same_node](/html/python-net/aspose.html.dom/element/is_same_node/#aspose.html.dom.Node) | Returns whether this node is the same node as the given one. 
| [lookup_prefix](/html/python-net/aspose.html.dom/element/lookup_prefix/#str) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. 
| [lookup_namespace_uri](/html/python-net/aspose.html.dom/element/lookup_namespace_uri/#str) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [is_default_namespace](/html/python-net/aspose.html.dom/element/is_default_namespace/#str) | This method checks if the specified namespaceURI is the default namespace or not. |
| [insert_before](/html/python-net/aspose.html.dom/element/insert_before/#aspose.html.dom.Node-aspose.html.dom.Node) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children.
| [replace_child](/html/python-net/aspose.html.dom/element/replace_child/#aspose.html.dom.Node-aspose.html.dom.Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. 
| [remove_child](/html/python-net/aspose.html.dom/element/remove_child/#aspose.html.dom.Node) | Removes the child node indicated by oldChild from the list of children, and returns it. |
| [append_child](/html/python-net/aspose.html.dom/element/append_child/#aspose.html.dom.Node) | Adds the node newChild to the end of the list of children of this node. If the newChild is already in the tree, it is first removed. |
| [get_attribute_names](/html/python-net/aspose.html.dom/element/get_attribute_names/#) | Returns the attribute names of the element as an Array of strings. If the element has no attributes it returns an empty array. |
| [has_attributes](/html/python-net/aspose.html.dom/element/has_attributes/#) | Returns whether this node (if it is an element) has any attributes |
| [get_attribute](/html/python-net/aspose.html.dom/element/get_attribute/#str) | Retrieves an attribute value by name. |
| [get_attribute_ns](/html/python-net/aspose.html.dom/element/get_attribute_ns/#str-str) | Retrieves an attribute value by local name and namespace URI. |
| [set_attribute](/html/python-net/aspose.html.dom/element/set_attribute/#str-str) | Adds a new attribute. If an attribute with that name is already present in the element, its value is changed to be that of the value parameter |
| [set_attribute_ns](/html/python-net/aspose.html.dom/element/set_attribute_ns/#str-str-str) | Adds a new attribute. If an attribute with the same local name and namespace URI is already present on the element, its prefix is changed to be the prefix part of the qualifiedName, and its value is changed to be the value parameter. |
| [remove_attribute](/html/python-net/aspose.html.dom/element/remove_attribute/#str) | Removes an attribute by name. |
| [remove_attribute_ns](/html/python-net/aspose.html.dom/element/remove_attribute_ns/#str-str) | Removes an attribute by local name and namespace URI. |
| [has_attribute](/html/python-net/aspose.html.dom/element/has_attribute/#str) | Returns true when an attribute with a given name is specified on this element or has a default value, false otherwise. |
| [has_attribute_ns](/html/python-net/aspose.html.dom/element/has_attribute_ns/#str-str) | Returns true when an attribute with a given local name and namespace URI is specified on this element or has a default value, false otherwise. |
| [get_attribute_node](/html/python-net/aspose.html.dom/element/get_attribute_node/#str) | Retrieves an attribute node by name. |
| [set_attribute_node](/html/python-net/aspose.html.dom/element/set_attribute_node/#aspose.html.dom.Attr) | Adds a new attribute node. If an attribute with that name (nodeName) is already present in the element, it is replaced by the new one. |
| [remove_attribute_node](/html/python-net/aspose.html.dom/element/remove_attribute_node/#aspose.html.dom.Attr) | Removes the specified attribute node. |
| [get_attribute_node_ns](/html/python-net/aspose.html.dom/element/get_attribute_node_ns/#str-str) | Retrieves an Attr node by local name and namespace URI. |
| [set_attribute_node_ns](/html/python-net/aspose.html.dom/element/set_attribute_node_ns/#aspose.html.dom.Attr) | Adds a new attribute. If an attribute with that local name and that namespace URI is already present in the element, it is replaced by the new one. |
| [get_elements_by_tag_name](/html/python-net/aspose.html.dom/element/get_elements_by_tag_name/#str) | Returns a NodeList of all descendant Elements with a given tag name, in document order. |
| [get_elements_by_tag_name_ns](/html/python-net/aspose.html.dom/element/get_elements_by_tag_name_ns/#str-str) | Returns a NodeList of all the descendant Elements with a given local name and namespace URI in document order. |
| [remove](/html/python-net/aspose.html.dom/element/remove/#) | Removes this instance. |
| [query_selector_all](/html/python-net/aspose.html.dom/element/query_selector_all/#str) | Returns a NodeList of all the Elements in document, which match selector |
| [query_selector](/html/python-net/aspose.html.dom/element/query_selector/#str) | Returns the first Element in document, which match selector |
| [attach_shadow](/html/python-net/aspose.html.dom/element/attach_shadow/#aspose.html.dom.ShadowRootMode) | Creates shadow root and attaches it to current element. |
| [get_elements_by_class_name](/html/python-net/aspose.html.dom/element/get_elements_by_class_name/#str) | Returns a live NodeList object containing all the elements in the document that have all the classes specified in argument.



### See Also
* module [`aspose.html.dom`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`Element`](/html/python-net/aspose.html.dom/element)
* class [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`Node`](/html/python-net/aspose.html.dom/node)