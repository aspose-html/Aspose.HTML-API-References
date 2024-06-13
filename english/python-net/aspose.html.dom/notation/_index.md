﻿---
title: Notation class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 230
url: /python-net/aspose.html.dom/notation/
is_root: false
---

## Notation class

Represents a notation declared in the DTD.



**Inheritance:** [`Notation`](/html/python-net/aspose.html.dom/notation) → 
[`Node`](/html/python-net/aspose.html.dom/node) → 
[`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The Notation type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [node_type](/html/python-net/aspose.html.dom/notation/node_type) | A code representing the type of the underlying object. |
| [local_name](/html/python-net/aspose.html.dom/notation/local_name) | Returns the local part of the qualified name of this node.
| [namespace_uri](/html/python-net/aspose.html.dom/notation/namespace_uri) | The namespace URI of this node, or null if it is unspecified. |
| [prefix](/html/python-net/aspose.html.dom/notation/prefix) | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [node_name](/html/python-net/aspose.html.dom/notation/node_name) | The name of this node, depending on its type. |
| [base_uri](/html/python-net/aspose.html.dom/notation/base_uri) | The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
| [owner_document](/html/python-net/aspose.html.dom/notation/owner_document) | The Document object associated with this node. This is also the Document object used to create new nodes. When this node is a Document or a DocumentType which is not used with any Document yet, this is null. |
| [parent_node](/html/python-net/aspose.html.dom/notation/parent_node) | The parent of this node. All nodes, except Attr, Document, DocumentFragment, Entity, and Notation may have a parent. However, if a node has just been created and not yet added to the tree, or if it has been removed from the tree, this is null. |
| [parent_element](/html/python-net/aspose.html.dom/notation/parent_element) | Gets the parent [`Element`](/html/python-net/aspose.html.dom/element) of this node. |
| [child_nodes](/html/python-net/aspose.html.dom/notation/child_nodes) | A NodeList that contains all children of this node. If there are no children, this is a NodeList containing no nodes.. |
| [first_child](/html/python-net/aspose.html.dom/notation/first_child) | The first child of this node. If there is no such node, this returns null. |
| [last_child](/html/python-net/aspose.html.dom/notation/last_child) | The last child of this node. If there is no such node, this returns null. |
| [previous_sibling](/html/python-net/aspose.html.dom/notation/previous_sibling) | The node immediately preceding this node. If there is no such node, this returns null. |
| [next_sibling](/html/python-net/aspose.html.dom/notation/next_sibling) | The node immediately following this node. If there is no such node, this returns null. |
| [node_value](/html/python-net/aspose.html.dom/notation/node_value) | The value of this node, depending on its type. |
| [text_content](/html/python-net/aspose.html.dom/notation/text_content) | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [ELEMENT_NODE](/html/python-net/aspose.html.dom/notation/element_node) | An element node |
| [ATTRIBUTE_NODE](/html/python-net/aspose.html.dom/notation/attribute_node) | An attribute node |
| [TEXT_NODE](/html/python-net/aspose.html.dom/notation/text_node) | A text node |
| [CDATA_SECTION_NODE](/html/python-net/aspose.html.dom/notation/cdata_section_node) | A cdata section node |
| [ENTITY_REFERENCE_NODE](/html/python-net/aspose.html.dom/notation/entity_reference_node) | An entity reference node |
| [ENTITY_NODE](/html/python-net/aspose.html.dom/notation/entity_node) | An entity node |
| [PROCESSING_INSTRUCTION_NODE](/html/python-net/aspose.html.dom/notation/processing_instruction_node) | A processing instruction node |
| [COMMENT_NODE](/html/python-net/aspose.html.dom/notation/comment_node) | A comment node |
| [DOCUMENT_NODE](/html/python-net/aspose.html.dom/notation/document_node) | A document node |
| [DOCUMENT_TYPE_NODE](/html/python-net/aspose.html.dom/notation/document_type_node) | A document type node |
| [DOCUMENT_FRAGMENT_NODE](/html/python-net/aspose.html.dom/notation/document_fragment_node) | A document fragment node |
| [NOTATION_NODE](/html/python-net/aspose.html.dom/notation/notation_node) | A notation node |
| [public_id](/html/python-net/aspose.html.dom/notation/public_id) | The public identifier of this notation. If the public identifier was not specified, this is null. |
| [system_id](/html/python-net/aspose.html.dom/notation/system_id) | The system identifier of this notation. If the system identifier was not specified, this is null. This may be an absolute URI or not. |


### Methods
| Method | Description |
| :- | :- |
| [add_event_listener](/html/python-net/aspose.html.dom/notation/add_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the registration of event listeners on the event target. |
| [add_event_listener](/html/python-net/aspose.html.dom/notation/add_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the registration of event listeners on the event target. |
| [remove_event_listener](/html/python-net/aspose.html.dom/notation/remove_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the removal of event listeners from the event target.
| [remove_event_listener](/html/python-net/aspose.html.dom/notation/remove_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the removal of event listeners from the event target.
| [clone_node](/html/python-net/aspose.html.dom/notation/clone_node/#) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [clone_node](/html/python-net/aspose.html.dom/notation/clone_node/#bool) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [get_platform_type](/html/python-net/aspose.html.dom/notation/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [dispatch_event](/html/python-net/aspose.html.dom/notation/dispatch_event/#aspose.html.dom.events.Event) | This method allows the dispatch of events into the implementations event model. |
| [has_child_nodes](/html/python-net/aspose.html.dom/notation/has_child_nodes/#) | Returns whether this node has any children. |
| [normalize](/html/python-net/aspose.html.dom/notation/normalize/#) | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [is_equal_node](/html/python-net/aspose.html.dom/notation/is_equal_node/#aspose.html.dom.Node) | Tests whether two nodes are equal.
| [is_same_node](/html/python-net/aspose.html.dom/notation/is_same_node/#aspose.html.dom.Node) | Returns whether this node is the same node as the given one. 
| [lookup_prefix](/html/python-net/aspose.html.dom/notation/lookup_prefix/#str) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. 
| [lookup_namespace_uri](/html/python-net/aspose.html.dom/notation/lookup_namespace_uri/#str) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [is_default_namespace](/html/python-net/aspose.html.dom/notation/is_default_namespace/#str) | This method checks if the specified namespaceURI is the default namespace or not. |
| [insert_before](/html/python-net/aspose.html.dom/notation/insert_before/#aspose.html.dom.Node-aspose.html.dom.Node) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children.
| [replace_child](/html/python-net/aspose.html.dom/notation/replace_child/#aspose.html.dom.Node-aspose.html.dom.Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. 
| [remove_child](/html/python-net/aspose.html.dom/notation/remove_child/#aspose.html.dom.Node) | Removes the child node indicated by oldChild from the list of children, and returns it. |
| [append_child](/html/python-net/aspose.html.dom/notation/append_child/#aspose.html.dom.Node) | Adds the node newChild to the end of the list of children of this node. If the newChild is already in the tree, it is first removed. |



### See Also
* module [`aspose.html.dom`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`Element`](/html/python-net/aspose.html.dom/element)
* class [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`Node`](/html/python-net/aspose.html.dom/node)
* class [`Notation`](/html/python-net/aspose.html.dom/notation)