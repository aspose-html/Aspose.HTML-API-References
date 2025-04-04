---
title: Text Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.Text class. The Text interface inherits from CharacterData and represents the textual content termed character data in XML of an Element or Attr
type: docs

url: /java/com.aspose.html.dom/text/
---
## Text class

The Text interface inherits from CharacterData and represents the textual content (termed character data in XML) of an Element or Attr.

```java
public class Text : CharacterData
```

## Properties

| Name | Description |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) The read-only baseURI property of the Node interface returns the absolute base URL of the document containing the node. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) The read-only childNodes property of the Node interface returns a live [`NodeList`](../../com.aspose.html.collections/nodelist/) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [data](../../com.aspose.html.dom/characterdata/data/) { get; set; } | The character data of the node that implements this interface. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) The read-only firstChild property of the [`Node`](../node/) interface returns the node's first child in the tree, or null if the node has no children. |
| [getIsElementContentWhitespace](../../com.aspose.html.dom/text/iselementcontentwhitespace/) Returns whether this text node contains element content whitespace, often abusively called "ignorable whitespace". |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) The read-only lastChild property of the [`Node`](../node/) interface returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [getLength](../../com.aspose.html.dom/characterdata/length/) The number of 16-bit units that are available through data and the subStringData method below. This may have the value zero, i.e., CharacterData nodes may be empty. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Returns the local part of the qualified name of this node. For nodes of any type other than [`ELEMENT_NODE`](../node/element_node/) and [`ATTRIBUTE_NODE`](../node/attribute_node/) and nodes created with a DOM Level 1 method, such as [`Document.createElement()`](../document/createelement/), this is always null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) The Element.packageURI read-only property returns the package URI of the element, or null if the element is not in a package. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) The read-only nextSibling property of the [`Node`](../node/) interface returns the node immediately following the specified one in their parent's [`childNodes`](../node/childnodes/), or returns null if the specified node is the last child in the parent element. |
| [getNodeName](../../com.aspose.html.dom/text/nodename/) The name of this node, depending on its type. |
| [getNodeType](../../com.aspose.html.dom/text/nodetype/) A code representing the type of the underlying object. |
| [nodeValue](../../com.aspose.html.dom/text/nodevalue/) { get; set; } | The value of this node, depending on its type. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) The read-only ownerDocument property of the Node interface returns the top-level document object of the node. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) The read-only parentElement property of [`Node`](../node/) interface returns the DOM node's parent [`Element`](../element/), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | The prefix read-only property returns the package prefix of the specified element, or null if no prefix is specified. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) The read-only previousSibling property of the [`Node`](../node/) interface returns the node immediately preceding the specified one in its parent's [`childNodes`](../node/firstchild/) list, or null if the specified node is the first in that list. |
| [textContent](../../com.aspose.html.dom/text/textcontent/) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new String is not empty or null, replaced by a single Text node containing the String this attribute is set to. |
| [getWholeText](../../com.aspose.html.dom/text/wholetext/) Returns all text of Text nodes logically-adjacent text nodes to this node, concatenated in document order. |

## Methods

| Name | Description |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() method of the [`EventTarget `](../eventtarget/)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | The addEventListener() method of the [EventTarget ](T:com.aspose.html.dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | The addEventListener() method of the [EventTarget ](T:com.aspose.html.dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | The appendChild() method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node). |
| [appendData](../../com.aspose.html.dom/characterdata/appenddata/)(String) | Append the String to the end of the character data of the node. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [deleteData](../../com.aspose.html.dom/characterdata/deletedata/)(int, int) | Remove a range of 16-bit units from the node. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Dispatches an Event at the specified [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | The hasChildNodes() method of the Node interface returns a boolean value indicating whether the given [`Node`](../node/) has child nodes or not. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | The insertBefore() method of the Node interface inserts a node before a reference node as a child of a specified parent node. |
| [insertData](../../com.aspose.html.dom/characterdata/insertdata/)(int, String) | Insert a String at the specified 16-bit unit offset. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | The isDefaultNamespace() method of the Node interface accepts a package URI as an argument. It returns a boolean value that is true if the package is the default package on the given node and false if not. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | The isEqualNode() method of the [`Node`](../node/) interface tests whether two nodes are equal. Two nodes are equal when they have the same type, defining characteristics (for elements, this would be their ID, number of children, and so forth), its attributes match, and so on. The specific set of data points that must match varies depending on the types of the nodes. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | The isSameNode() method of the Node interface is a legacy alias the for the === strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | The lookupNamespaceURI() method of the Node interface takes a prefix as parameter and returns the package URI associated with it on the given node if found (and null if not). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | The lookupPrefix() method of the Node interface returns a String containing the prefix for a given package URI, if present, and null if not. When multiple prefixes are possible, the first prefix is returned. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Puts all `Text` nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), and [`entity references`](../entityreference/)) separates `Text` nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the [`DOMConfiguration`](../../com.aspose.html/configuration/) object attached to the [`Node.ownerDocument`](../node/ownerdocument/) is true, this method will also fully normalize the characters of the Text nodes. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | The removeChild() method of the Node interface removes a child node from the DOM and returns the removed node. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a [`DocumentFragment`](../documentfragment/) object, oldChild is replaced by all of the [`DocumentFragment`](../documentfragment/) children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [replaceData](../../com.aspose.html.dom/characterdata/replacedata/)(int, int, String) | Replace the characters starting at the specified 16-bit unit offset with the specified String. |
| [replaceWholeText](../../com.aspose.html.dom/text/replacewholetext/)(String) | Replaces the text of the current node and all logically-adjacent text nodes with the specified text. All logically-adjacent text nodes are removed including the current node unless it was the recipient of the replacement text. |
| [splitText](../../com.aspose.html.dom/text/splittext/)(int) | Breaks this node into two nodes at the specified offset, keeping both in the tree as siblings. |
| [subStringData](../../com.aspose.html.dom/characterdata/subStringdata/)(int, int) | Extracts a range of data from the node. |
| [toString](../../com.aspose.html.dom/characterdata/toString/)() | Returns a String that represents this instance. |

### See Also

* class [CharacterData](../characterdata/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
