---
title: HTMLDirectoryElement Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.HTMLDirectoryElement class. Directory list. See the DIR element definition in HTML 4.01. This element is deprecated in HTML 4.01
type: docs

url: /java/com.aspose.html/htmldirectoryelement/
---
## HTMLDirectoryElement class

Directory list. See the DIR element definition in HTML 4.01. This element is deprecated in HTML 4.01.

See also the [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```java
public class HTMLDirectoryElement : HTMLElement
```

## Properties

| Name | Description |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) The read-only baseURI property of the Node interface returns the absolute base URL of the document containing the node. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) The read-only childNodes property of the Node interface returns a live [`NodeList`](../../com.aspose.html.collections/nodelist/) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [getChildren](../../com.aspose.html.dom/element/children/) Returns the child elements of current element. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) Returns a live DOMTokenList which contains tokens received from parsing the "class" attribute. |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
[getCompact]
[setCompact] Reduce spacing between list items. See the compact attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) The read-only firstChild property of the [`Node`](../../com.aspose.html.dom/node/) interface returns the node's first child in the tree, or null if the node has no children. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Returns the first child element node of this element. null if this element has no child elements. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) The read-only lastChild property of the [`Node`](../../com.aspose.html.dom/node/) interface returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Returns the last child element node of this element. null if this element has no child elements. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Returns the local part of the qualified name of this node. For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) The package URI of this node, or null if it is unspecified. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) The read-only nextSibling property of the [`Node`](../../com.aspose.html.dom/node/) interface returns the node immediately following the specified one in their parent's [`childNodes`](../../com.aspose.html.dom/node/childnodes/), or returns null if the specified node is the last child in the parent element. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) The name of this node, depending on its type. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) A code representing the type of the underlying object. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | The nodeValue property of the [`Node `](../../com.aspose.html.dom/node/)interface returns or sets the value of the current node. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) The read-only ownerDocument property of the Node interface returns the top-level document object of the node. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) The read-only parentElement property of [`Node`](../../com.aspose.html.dom/node/) interface returns the DOM node's parent [`Element`](../../com.aspose.html.dom/element/), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) The package prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) The read-only previousSibling property of the [`Node`](../../com.aspose.html.dom/node/) interface returns the node immediately preceding the specified one in its parent's [`childNodes`](../../com.aspose.html.dom/node/firstchild/) list, or null if the specified node is the first in that list. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Returns shadowRoot stored on this element or null if it's closed. |
| [getStyle](../../com.aspose.html/htmlelement/style/) Represents a style attribute that allows author to directly apply style information to specific element. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) The name of the element. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new String is not empty or null, replaced by a single Text node containing the String this attribute is set to. |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |

## Methods

| Name | Description |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() method of the [`EventTarget `](../../com.aspose.html.dom/eventtarget/)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | The addEventListener() method of the [EventTarget ](T:com.aspose.html.dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | The addEventListener() method of the [EventTarget ](T:com.aspose.html.dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | The appendChild() method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Creates shadow root and attaches it to current element. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Dispatches an Event at the specified [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Retrieves an attribute value by name. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Returns the attribute names of the element as an Array of Strings. If the element has no attributes it returns an empty array. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Retrieves an attribute node by name. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Retrieves an Attr node by local name and package URI. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Retrieves an attribute value by local name and package URI. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Returns [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) object containing all the elements within [`element`](../../com.aspose.html.dom/element/) that have all the classes specified in argument. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Returns [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) object containing all [`elements`](../../com.aspose.html.dom/element/) with a given tag name, in document order. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Returns [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) object containing all [`elements`](../../com.aspose.html.dom/element/) with a given local name and package URI String in document order. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | Returns true when an attribute with a given name is specified on this element or has a default value, false otherwise. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | Returns true when an attribute with a given local name and package URI is specified on this element or has a default value, false otherwise. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | Returns whether this node (if it is an element) has any attributes |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | The hasChildNodes() method of the Node interface returns a boolean value indicating whether the given [`Node`](../../com.aspose.html.dom/node/) has child nodes or not. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | The insertBefore() method of the Node interface inserts a node before a reference node as a child of a specified parent node. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | The isDefaultNamespace() method of the Node interface accepts a package URI as an argument. It returns a boolean value that is true if the package is the default package on the given node and false if not. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | The isEqualNode() method of the [`Node`](../../com.aspose.html.dom/node/) interface tests whether two nodes are equal. Two nodes are equal when they have the same type, defining characteristics (for elements, this would be their ID, number of children, and so forth), its attributes match, and so on. The specific set of data points that must match varies depending on the types of the nodes. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | The isSameNode() method of the Node interface is a legacy alias the for the === strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | The lookupNamespaceURI() method of the Node interface takes a prefix as parameter and returns the package URI associated with it on the given node if found (and null if not). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | The lookupPrefix() method of the Node interface returns a String containing the prefix for a given package URI, if present, and null if not. When multiple prefixes are possible, the first prefix is returned. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Puts all [`Text`](../../com.aspose.html.dom/text/) nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), and [`entity references`](../../com.aspose.html.dom/entityreference/)) separates [`Text`](../../com.aspose.html.dom/text/) nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the [`DOMConfiguration`](../configuration/) object attached to the [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) is true, this method will also fully normalize the characters of the Text nodes. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | Returns the first Element in document, which match selector |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | Returns a NodeList of all the Elements in document, which match selector |
| [remove](../../com.aspose.html.dom/element/remove/)() | Removes this instance. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | Removes an attribute by name. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | Removes the specified attribute node. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | Removes an attribute by local name and package URI. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | The removeChild() method of the Node interface removes a child node from the DOM and returns the removed node. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) object, oldChild is replaced by all of the [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | Adds a new attribute. If an attribute with that name is already present in the element, its value is changed to be that of the value parameter |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | Adds a new attribute node. If an attribute with that name (nodeName) is already present in the element, it is replaced by the new one. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | Adds a new attribute. If an attribute with that local name and that package URI is already present in the element, it is replaced by the new one. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | Adds a new attribute. If an attribute with the same local name and package URI is already present on the element, its prefix is changed to be the prefix part of the qualifiedName, and its value is changed to be the value parameter. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | If force is not given, "toggles" qualifiedName, removing it if it is present and adding it if it is not present. If force is true, adds qualifiedName. If force is false, removes qualifiedName. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | If force is not given, "toggles" qualifiedName, removing it if it is present and adding it if it is not present. If force is true, adds qualifiedName. If force is false, removes qualifiedName. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Returns a String that represents this instance. |

## Events

| Name | Description |
| --- | --- |
| event [OnAbort](../../com.aspose.html/htmlelement/onabort/) | Gets or sets event handler for OnAbort event. |
| event [OnBlur](../../com.aspose.html/htmlelement/onblur/) | Gets or sets event handler for OnBlur event. |
| event [OnCancel](../../com.aspose.html/htmlelement/oncancel/) | Gets or sets event handler for OnCancel event. |
| event [OnCanplay](../../com.aspose.html/htmlelement/oncanplay/) | Gets or sets event handler for OnCanplay event. |
| event [OnCanPlayThrough](../../com.aspose.html/htmlelement/oncanplaythrough/) | Gets or sets event handler for OnCanPlayThrough event. |
| event [OnChange](../../com.aspose.html/htmlelement/onchange/) | Gets or sets event handler for OnChange event. |
| event [OnClick](../../com.aspose.html/htmlelement/onclick/) | Gets or sets event handler for OnClick event. |
| event [OnCueChange](../../com.aspose.html/htmlelement/oncuechange/) | Gets or sets event handler for OnCueChange event. |
| event [OnDblClick](../../com.aspose.html/htmlelement/ondblclick/) | Gets or sets event handler for OnDblClick event. |
| event [OnDurationChange](../../com.aspose.html/htmlelement/ondurationchange/) | Gets or sets event handler for OnDurationChange event. |
| event [OnEmptied](../../com.aspose.html/htmlelement/onemptied/) | Gets or sets event handler for OnEmptied event. |
| event [OnEnded](../../com.aspose.html/htmlelement/onended/) | Gets or sets event handler for OnEnded event. |
| event [OnError](../../com.aspose.html/htmlelement/onerror/) | Gets or sets event handler for OnError event. |
| event [OnFocus](../../com.aspose.html/htmlelement/onfocus/) | Gets or sets event handler for OnFocus event. |
| event [OnInput](../../com.aspose.html/htmlelement/oninput/) | Gets or sets event handler for OnInput event. |
| event [OnInvalid](../../com.aspose.html/htmlelement/oninvalid/) | Gets or sets event handler for OnInvalid event. |
| event [OnKeyDown](../../com.aspose.html/htmlelement/onkeydown/) | Gets or sets event handler for OnKeyDown event. |
| event [OnKeyPress](../../com.aspose.html/htmlelement/onkeypress/) | Gets or sets event handler for OnKeyPress event. |
| event [OnKeyUp](../../com.aspose.html/htmlelement/onkeyup/) | Gets or sets event handler for OnKeyUp event. |
| event [OnLoad](../../com.aspose.html/htmlelement/onload/) | Gets or sets event handler for OnLoad event. |
| event [OnLoadedData](../../com.aspose.html/htmlelement/onloadeddata/) | Gets or sets event handler for OnLoadedData event. |
| event [OnLoadedMetadata](../../com.aspose.html/htmlelement/onloadedmetadata/) | Gets or sets event handler for OnLoadedMetadata event. |
| event [OnLoadStart](../../com.aspose.html/htmlelement/onloadstart/) | Gets or sets event handler for OnLoadStart event. |
| event [OnMouseDown](../../com.aspose.html/htmlelement/onmousedown/) | Gets or sets event handler for OnMouseDown event. |
| event [OnMouseEnter](../../com.aspose.html/htmlelement/onmouseenter/) | Gets or sets event handler for OnMouseEnter event. |
| event [OnMouseLeave](../../com.aspose.html/htmlelement/onmouseleave/) | Gets or sets event handler for OnMouseLeave event. |
| event [OnMouseMove](../../com.aspose.html/htmlelement/onmousemove/) | Gets or sets event handler for OnMouseMove event. |
| event [OnMouseOut](../../com.aspose.html/htmlelement/onmouseout/) | Gets or sets event handler for OnMouseOut event. |
| event [OnMouseOver](../../com.aspose.html/htmlelement/onmouseover/) | Gets or sets event handler for OnMouseOver event. |
| event [OnMouseUp](../../com.aspose.html/htmlelement/onmouseup/) | Gets or sets event handler for OnMouseUp event. |
| event [OnMouseWheel](../../com.aspose.html/htmlelement/onmousewheel/) | Gets or sets event handler for OnMouseWheel event. |
| event [OnPause](../../com.aspose.html/htmlelement/onpause/) | Gets or sets event handler for OnPause event. |
| event [OnPlay](../../com.aspose.html/htmlelement/onplay/) | Gets or sets event handler for OnPlay event. |
| event [OnPlaying](../../com.aspose.html/htmlelement/onplaying/) | Gets or sets event handler for OnPlaying event. |
| event [OnProgress](../../com.aspose.html/htmlelement/onprogress/) | Gets or sets event handler for OnProgress event. |
| event [OnRateChange](../../com.aspose.html/htmlelement/onratechange/) | Gets or sets event handler for OnRateChange event. |
| event [OnReset](../../com.aspose.html/htmlelement/onreset/) | Gets or sets event handler for OnReset event. |
| event [OnResize](../../com.aspose.html/htmlelement/onresize/) | Gets or sets event handler for OnResize event. |
| event [OnScroll](../../com.aspose.html/htmlelement/onscroll/) | Gets or sets event handler for OnScroll event. |
| event [OnSeeked](../../com.aspose.html/htmlelement/onseeked/) | Gets or sets event handler for OnSeeked event. |
| event [OnSeeking](../../com.aspose.html/htmlelement/onseeking/) | Gets or sets event handler for OnSeeking event. |
| event [OnSelect](../../com.aspose.html/htmlelement/onselect/) | Gets or sets event handler for OnSelect event. |
| event [OnShow](../../com.aspose.html/htmlelement/onshow/) | Gets or sets event handler for OnShow event. |
| event [OnStalled](../../com.aspose.html/htmlelement/onstalled/) | Gets or sets event handler for OnStalled event. |
| event [OnSubmit](../../com.aspose.html/htmlelement/onsubmit/) | Gets or sets event handler for OnSubmit event. |
| event [OnSuspend](../../com.aspose.html/htmlelement/onsuspend/) | Gets or sets event handler for OnSuspend event. |
| event [OnTimeUpdate](../../com.aspose.html/htmlelement/ontimeupdate/) | Gets or sets event handler for OnTimeUpdate event. |
| event [OnToggle](../../com.aspose.html/htmlelement/ontoggle/) | Gets or sets event handler for OnToggle event. |
| event [OnVolumeChange](../../com.aspose.html/htmlelement/onvolumechange/) | Gets or sets event handler for OnVolumeChange event. |
| event [OnWaiting](../../com.aspose.html/htmlelement/onwaiting/) | Gets or sets event handler for OnWaiting event. |

### See Also

* class [HTMLElement](../htmlelement/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
