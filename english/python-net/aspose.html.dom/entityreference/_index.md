﻿---
title: EntityReference class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 120
url: /python-net/aspose.html.dom/entityreference/
is_root: false
---

## EntityReference class

EntityReference nodes may be used to represent an entity reference in the tree.



**Inheritance:** [`EntityReference`](/html/python-net/aspose.html.dom/entityreference) → 
[`Node`](/html/python-net/aspose.html.dom/node) → 
[`EventTarget`](/html/python-net/aspose.html.dom/eventtarget) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The EntityReference type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [node_type](/html/python-net/aspose.html.dom/entityreference/node_type) | A code representing the type of the underlying object. |
| [local_name](/html/python-net/aspose.html.dom/entityreference/local_name) | Returns the local part of the qualified name of this node.
| [namespace_uri](/html/python-net/aspose.html.dom/entityreference/namespace_uri) | The namespace URI of this node, or null if it is unspecified. |
| [prefix](/html/python-net/aspose.html.dom/entityreference/prefix) | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [node_name](/html/python-net/aspose.html.dom/entityreference/node_name) | The name of this node, depending on its type. |
| [base_uri](/html/python-net/aspose.html.dom/entityreference/base_uri) | The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
| [owner_document](/html/python-net/aspose.html.dom/entityreference/owner_document) | The Document object associated with this node. This is also the Document object used to create new nodes. When this node is a Document or a DocumentType which is not used with any Document yet, this is null. |
| [parent_node](/html/python-net/aspose.html.dom/entityreference/parent_node) | The parent of this node. All nodes, except Attr, Document, DocumentFragment, Entity, and Notation may have a parent. However, if a node has just been created and not yet added to the tree, or if it has been removed from the tree, this is null. |
| [parent_element](/html/python-net/aspose.html.dom/entityreference/parent_element) | Gets the parent [`Element`](/html/python-net/aspose.html.dom/element) of this node. |
| [child_nodes](/html/python-net/aspose.html.dom/entityreference/child_nodes) | A NodeList that contains all children of this node. If there are no children, this is a NodeList containing no nodes.. |
| [first_child](/html/python-net/aspose.html.dom/entityreference/first_child) | The first child of this node. If there is no such node, this returns null. |
| [last_child](/html/python-net/aspose.html.dom/entityreference/last_child) | The last child of this node. If there is no such node, this returns null. |
| [previous_sibling](/html/python-net/aspose.html.dom/entityreference/previous_sibling) | The node immediately preceding this node. If there is no such node, this returns null. |
| [next_sibling](/html/python-net/aspose.html.dom/entityreference/next_sibling) | The node immediately following this node. If there is no such node, this returns null. |
| [node_value](/html/python-net/aspose.html.dom/entityreference/node_value) | The value of this node, depending on its type. |
| [text_content](/html/python-net/aspose.html.dom/entityreference/text_content) | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [ELEMENT_NODE](/html/python-net/aspose.html.dom/entityreference/element_node) | An element node |
| [ATTRIBUTE_NODE](/html/python-net/aspose.html.dom/entityreference/attribute_node) | An attribute node |
| [TEXT_NODE](/html/python-net/aspose.html.dom/entityreference/text_node) | A text node |
| [CDATA_SECTION_NODE](/html/python-net/aspose.html.dom/entityreference/cdata_section_node) | A cdata section node |
| [ENTITY_REFERENCE_NODE](/html/python-net/aspose.html.dom/entityreference/entity_reference_node) | An entity reference node |
| [ENTITY_NODE](/html/python-net/aspose.html.dom/entityreference/entity_node) | An entity node |
| [PROCESSING_INSTRUCTION_NODE](/html/python-net/aspose.html.dom/entityreference/processing_instruction_node) | A processing instruction node |
| [COMMENT_NODE](/html/python-net/aspose.html.dom/entityreference/comment_node) | A comment node |
| [DOCUMENT_NODE](/html/python-net/aspose.html.dom/entityreference/document_node) | A document node |
| [DOCUMENT_TYPE_NODE](/html/python-net/aspose.html.dom/entityreference/document_type_node) | A document type node |
| [DOCUMENT_FRAGMENT_NODE](/html/python-net/aspose.html.dom/entityreference/document_fragment_node) | A document fragment node |
| [NOTATION_NODE](/html/python-net/aspose.html.dom/entityreference/notation_node) | A notation node |


### Methods
| Method | Description |
| :- | :- |
| [add_event_listener](/html/python-net/aspose.html.dom/entityreference/add_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the registration of event listeners on the event target. |
| [add_event_listener](/html/python-net/aspose.html.dom/entityreference/add_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the registration of event listeners on the event target. |
| [remove_event_listener](/html/python-net/aspose.html.dom/entityreference/remove_event_listener/#str-aspose.html.dom.events.IEventListener) | This method allows the removal of event listeners from the event target.
| [remove_event_listener](/html/python-net/aspose.html.dom/entityreference/remove_event_listener/#str-aspose.html.dom.events.IEventListener-bool) | This method allows the removal of event listeners from the event target.
| [clone_node](/html/python-net/aspose.html.dom/entityreference/clone_node/#) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [clone_node](/html/python-net/aspose.html.dom/entityreference/clone_node/#bool) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [get_platform_type](/html/python-net/aspose.html.dom/entityreference/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [dispatch_event](/html/python-net/aspose.html.dom/entityreference/dispatch_event/#aspose.html.dom.events.Event) | This method allows the dispatch of events into the implementations event model. |
| [has_child_nodes](/html/python-net/aspose.html.dom/entityreference/has_child_nodes/#) | Returns whether this node has any children. |
| [normalize](/html/python-net/aspose.html.dom/entityreference/normalize/#) | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [is_equal_node](/html/python-net/aspose.html.dom/entityreference/is_equal_node/#aspose.html.dom.Node) | Tests whether two nodes are equal.
| [is_same_node](/html/python-net/aspose.html.dom/entityreference/is_same_node/#aspose.html.dom.Node) | Returns whether this node is the same node as the given one. 
| [lookup_prefix](/html/python-net/aspose.html.dom/entityreference/lookup_prefix/#str) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. 
| [lookup_namespace_uri](/html/python-net/aspose.html.dom/entityreference/lookup_namespace_uri/#str) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [is_default_namespace](/html/python-net/aspose.html.dom/entityreference/is_default_namespace/#str) | This method checks if the specified namespaceURI is the default namespace or not. |
| [insert_before](/html/python-net/aspose.html.dom/entityreference/insert_before/#aspose.html.dom.Node-aspose.html.dom.Node) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children.
| [replace_child](/html/python-net/aspose.html.dom/entityreference/replace_child/#aspose.html.dom.Node-aspose.html.dom.Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. 
| [remove_child](/html/python-net/aspose.html.dom/entityreference/remove_child/#aspose.html.dom.Node) | Removes the child node indicated by oldChild from the list of children, and returns it. |
| [append_child](/html/python-net/aspose.html.dom/entityreference/append_child/#aspose.html.dom.Node) | Adds the node newChild to the end of the list of children of this node. If the newChild is already in the tree, it is first removed. |



### See Also
* module [`aspose.html.dom`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`Element`](/html/python-net/aspose.html.dom/element)
* class [`EntityReference`](/html/python-net/aspose.html.dom/entityreference)
* class [`EventTarget`](/html/python-net/aspose.html.dom/eventtarget)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`Node`](/html/python-net/aspose.html.dom/node)