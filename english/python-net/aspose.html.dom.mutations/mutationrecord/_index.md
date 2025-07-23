---
title: MutationRecord class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/aspose.html.dom.mutations/mutationrecord/
is_root: false
---

## MutationRecord class

A MutationRecord represents an individual DOM mutation. It is the object that is passed to [`MutationObserver`](/html/python-net/aspose.html.dom.mutations/mutationobserver)'s MutationCallback.



**Inheritance:** [`MutationRecord`](/html/python-net/aspose.html.dom.mutations/mutationrecord) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The MutationRecord type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [type](/html/python-net/aspose.html.dom.mutations/mutationrecord/type) | Returns "attributes" if it was an attribute mutation, "characterData" if it was a mutation to a CharacterData node and "childList" if it was a mutation to the tree of nodes. |
| [target](/html/python-net/aspose.html.dom.mutations/mutationrecord/target) | Returns the node the mutation affected, depending on the type. For "attributes", it is the element whose attribute changed. For "characterData", it is the CharacterData node. For "childList", it is the node whose children changed. |
| [added_nodes](/html/python-net/aspose.html.dom.mutations/mutationrecord/added_nodes) | Return the nodes added. |
| [removed_nodes](/html/python-net/aspose.html.dom.mutations/mutationrecord/removed_nodes) | Return the nodes removed. |
| [previous_sibling](/html/python-net/aspose.html.dom.mutations/mutationrecord/previous_sibling) | Returns the previous sibling of the added or removed nodes, or null. |
| [next_sibling](/html/python-net/aspose.html.dom.mutations/mutationrecord/next_sibling) | Return the next sibling of the added or removed nodes, or null. |
| [attribute_name](/html/python-net/aspose.html.dom.mutations/mutationrecord/attribute_name) | Returns the local name of the changed attribute, and null otherwise. |
| [attribute_namespace](/html/python-net/aspose.html.dom.mutations/mutationrecord/attribute_namespace) | Returns the namespace of the changed attribute, and null otherwise. |
| [old_value](/html/python-net/aspose.html.dom.mutations/mutationrecord/old_value) | The return value depends on type. For "attributes", it is the value of the changed attribute before the change.<br/>For "characterData", it is the data of the changed node before the change.<br/>For "childList", it is null. |


### Methods
| Method | Description |
| :- | :- |
| [get_platform_type](/html/python-net/aspose.html.dom.mutations/mutationrecord/get_platform_type/#) | This method is used to retrieve the ECMAScript object Type. |



### See Also
* module [`aspose.html.dom.mutations`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`MutationObserver`](/html/python-net/aspose.html.dom.mutations/mutationobserver)
* class [`MutationRecord`](/html/python-net/aspose.html.dom.mutations/mutationrecord)
