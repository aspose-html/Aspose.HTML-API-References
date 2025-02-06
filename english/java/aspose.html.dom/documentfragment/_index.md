---
title: DocumentFragment Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.DocumentFragment class. DocumentFragment is a lightweight or minimal Document object. It is very common to want to be able to extract a portion of a documents tree or to create a new fragment of a document
type: docs
weight: 680
url: /java/com.aspose.html.dom/documentfragment/
---
## DocumentFragment class

DocumentFragment is a "lightweight" or "minimal" Document object. It is very common to want to be able to extract a portion of a document's tree or to create a new fragment of a document.

```java
public class DocumentFragment : Node, IParentNode
```

## Properties

| Name | Description |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/node/attributes/) The attributes property returns a live collection of all attribute nodes registered to the specified node. Attributes is a key/value pair of Strings that represents any information regarding that attribute. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) The read-only baseURI property of the Node interface returns the absolute base URL of the document containing the node. |
| [getChildElementCount](../../com.aspose.html.dom/documentfragment/childelementcount/) Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) The read-only childNodes property of the Node interface returns a live [`NodeList`](../../com.aspose.html.collections/nodelist/) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [getChildren](../../com.aspose.html.dom/documentfragment/children/) Returns the child elements of current element. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) The read-only firstChild property of the [`Node`](../node/) interface returns the node's first child in the tree, or null if the node has no children. |
| [getFirstElementChild](../../com.aspose.html.dom/documentfragment/firstelementchild/) Returns the first child element node of this element. null if this element has no child elements. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) The read-only lastChild property of the [`Node`](../node/) interface returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [getLastElementChild](../../com.aspose.html.dom/documentfragment/lastelementchild/) Returns the last child element node of this element. null if this element has no child elements. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Returns the local part of the qualified name of this node. For nodes of any type other than [`ELEMENT_NODE`](../node/element_node/) and [`ATTRIBUTE_NODE`](../node/attribute_node/) and nodes created with a DOM Level 1 method, such as [`Document.createElement()`](../document/createelement/), this is always null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) The Element.packageURI read-only property returns the package URI of the element, or null if the element is not in a package. |
| [getNextElementSibling](../../com.aspose.html.dom/documentfragment/nextelementsibling/) Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) The read-only nextSibling property of the [`Node`](../node/) interface returns the node immediately following the specified one in their parent's [`childNodes`](../node/childnodes/), or returns null if the specified node is the last child in the parent element. |
| [getNodeName](../../com.aspose.html.dom/documentfragment/nodename/) The name of this node, depending on its type. |
| [getNodeType](../../com.aspose.html.dom/documentfragment/nodetype/) A code representing the type of the underlying object. |
[getNodeValue]
[setNodeValue] The nodeValue property of the [`Node `](../node/)interface returns or sets the value of the current node. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) The read-only ownerDocument property of the Node interface returns the top-level document object of the node. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) The read-only parentElement property of [`Node`](../node/) interface returns the DOM node's parent [`Element`](../element/), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree. |
[getPrefix]
[setPrefix] The prefix read-only property returns the package prefix of the specified element, or null if no prefix is specified. |
| [getPreviousElementSibling](../../com.aspose.html.dom/documentfragment/previouselementsibling/) Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) The read-only previousSibling property of the [`Node`](../node/) interface returns the node immediately preceding the specified one in its parent's [`childNodes`](../node/firstchild/) list, or null if the specified node is the first in that list. |
[getTextContent]
[setTextContent] This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new String is not empty or null, replaced by a single Text node containing the String this attribute is set to. |

## Methods

| Name | Description |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() method of the [`EventTarget `](../eventtarget/)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | The addEventListener() method of the [EventTarget ](T:com.aspose.html.dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | The addEventListener() method of the [EventTarget ](T:com.aspose.html.dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | The appendChild() method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Dispatches an Event at the specified [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [hasAttributes](../../com.aspose.html.dom/node/hasattributes/)() | The hasAttributes() method of the [`Element`](../element/) interface returns a boolean value indicating whether the current element has any attributes or not. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | The hasChildNodes() method of the Node interface returns a boolean value indicating whether the given [`Node`](../node/) has child nodes or not. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | The insertBefore() method of the Node interface inserts a node before a reference node as a child of a specified parent node. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | The isDefaultNamespace() method of the Node interface accepts a package URI as an argument. It returns a boolean value that is true if the package is the default package on the given node and false if not. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | The isEqualNode() method of the [`Node`](../node/) interface tests whether two nodes are equal. Two nodes are equal when they have the same type, defining characteristics (for elements, this would be their ID, number of children, and so forth), its attributes match, and so on. The specific set of data points that must match varies depending on the types of the nodes. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | The isSameNode() method of the Node interface is a legacy alias the for the === strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | The lookupNamespaceURI() method of the Node interface takes a prefix as parameter and returns the package URI associated with it on the given node if found (and null if not). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | The lookupPrefix() method of the Node interface returns a String containing the prefix for a given package URI, if present, and null if not. When multiple prefixes are possible, the first prefix is returned. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Puts all [`Text`](../text/) nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), and [`entity references`](../entityreference/)) separates [`Text`](../text/) nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the [`DOMConfiguration`](../../com.aspose.html/configuration/) object attached to the [`Node.ownerDocument`](../node/ownerdocument/) is true, this method will also fully normalize the characters of the Text nodes. |
| [querySelector](../../com.aspose.html.dom/documentfragment/queryselector/)(String) | Returns the first Element in document, which match selector |
| [querySelectorAll](../../com.aspose.html.dom/documentfragment/queryselectorall/)(String) | Returns a NodeList of all the Elements in document, which match selector |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | The removeChild() method of the Node interface removes a child node from the DOM and returns the removed node. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a `DocumentFragment` object, oldChild is replaced by all of the `DocumentFragment` children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Returns a String that represents this instance. |

### See Also

* class [Node](../node/)
* interface [IParentNode](../iparentnode/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
