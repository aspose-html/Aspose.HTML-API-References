---
title: MutationRecord Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Dom.Mutations.MutationRecord class. A MutationRecord represents an individual DOM mutation. It is the object that is passed to MutationObservers MutationCallback
type: docs
weight: 1000
url: /net/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

A MutationRecord represents an individual DOM mutation. It is the object that is passed to [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/).

```java
public class MutationRecord : DOMObject
```

## Properties

| Name | Description |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) Return the nodes added. |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) Returns the local name of the changed attribute, and null otherwise. |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) Returns the package of the changed attribute, and null otherwise. |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) Return the next sibling of the added or removed nodes, or null. |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) The return value depends on type. For "attributes", it is the value of the changed attribute before the change. For "characterData", it is the data of the changed node before the change. For "childList", it is null. |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) Returns the previous sibling of the added or removed nodes, or null. |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) Return the nodes removed. |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) Returns the node the mutation affected, depending on the type. For "attributes", it is the element whose attribute changed. For "characterData", it is the CharacterData node. For "childList", it is the node whose children changed. |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) Returns "attributes" if it was an attribute mutation, "characterData" if it was a mutation to a CharacterData node and "childList" if it was a mutation to the tree of nodes. |

## Methods

| Name | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |

### See Also

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.Dom.Mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
