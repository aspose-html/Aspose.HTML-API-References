---
title: SVGPathElement Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.svg.SVGPathElement class. The SVGPathElement interface corresponds to the path element
type: docs

url: /java/com.aspose.html.dom.svg/svgpathelement/
---
## SVGPathElement class

The SVGPathElement interface corresponds to the ‘path’ element.

```java
public class SVGPathElement : SVGGeometryElement, ISVGAnimatedPathData
```

## Properties

| Name | Description |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg/svgpathelement/animatedpathseglist/) Provides access to the current animated contents of the ‘d’ attribute in a form which matches one-for-one with SVG's syntax. If the given attribute or property is being animated, contains the current animated value of the attribute or property, and both the object itself and its contents are read only. If the given attribute or property is not currently being animated, contains the same value as pathSegList. |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) The read-only baseURI property of the Node interface returns the absolute base URL of the document containing the node. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) The read-only childNodes property of the Node interface returns a live [`NodeList`](../../com.aspose.html.collections/nodelist/) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [getChildren](../../com.aspose.html.dom/element/children/) Returns the child elements of current element. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) Returns a live DOMTokenList which contains tokens received from parsing the "class" attribute. |
| [getClassName](../../com.aspose.html.dom.svg/svgelement/classname/) Corresponds to attribute ‘class’ on the given element. |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [getFarthestViewportElement](../../com.aspose.html.dom.svg/svggraphicselement/farthestviewportelement/) The farthest ancestor ‘svg’ element. Null if the current element is the outermost svg element. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) The read-only firstChild property of the [`Node`](../../com.aspose.html.dom/node/) interface returns the node's first child in the tree, or null if the node has no children. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Returns the first child element node of this element. null if this element has no child elements. |
[getId]
[setId] The value of the ‘id’ attribute on the given element, or the empty String if ‘id’ is not present. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) The read-only lastChild property of the [`Node`](../../com.aspose.html.dom/node/) interface returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Returns the last child element node of this element. null if this element has no child elements. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Returns the local part of the qualified name of this node. For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) The package URI of this node, or null if it is unspecified. |
| [getNearestViewportElement](../../com.aspose.html.dom.svg/svggraphicselement/nearestviewportelement/) The element which established the current viewport. Often, the nearest ancestor ‘svg’ element. Null if the current element is the outermost svg element. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) The read-only nextSibling property of the [`Node`](../../com.aspose.html.dom/node/) interface returns the node immediately following the specified one in their parent's [`childNodes`](../../com.aspose.html.dom/node/childnodes/), or returns null if the specified node is the last child in the parent element. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) The name of this node, depending on its type. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) A code representing the type of the underlying object. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | The nodeValue property of the [`Node `](../../com.aspose.html.dom/node/)interface returns or sets the value of the current node. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) The read-only ownerDocument property of the Node interface returns the top-level document object of the node. |
| [getOwnerSVGElement](../../com.aspose.html.dom.svg/svgelement/ownersvgelement/) The nearest ancestor ‘svg’ element. Null if the given element is the outermost svg element. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) The read-only parentElement property of [`Node`](../../com.aspose.html.dom/node/) interface returns the DOM node's parent [`Element`](../../com.aspose.html.dom/element/), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree. |
| [getPathLength](../../com.aspose.html.dom.svg/svggeometryelement/pathlength/) Corresponds to attribute pathLength on the given element. |
[getPathSegList]
[setPathSegList] Provides access to the base (i.e., static) contents of the ‘d’ attribute in a form which matches one-for-one with SVG's syntax. Thus, if the ‘d’ attribute has an "absolute moveto (M)" and an "absolute arcto (A)" command, then pathSegList will have two entries: a SVG_PATHSEG_MOVETO_ABS and a SVG_PATHSEG_ARC_ABS. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) The package prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) The read-only previousSibling property of the [`Node`](../../com.aspose.html.dom/node/) interface returns the node immediately preceding the specified one in its parent's [`childNodes`](../../com.aspose.html.dom/node/firstchild/) list, or null if the specified node is the first in that list. |
| [getRequiredExtensions](../../com.aspose.html.dom.svg/svggraphicselement/requiredextensions/) Corresponds to attribute ‘requiredExtensions’ on the given element. |
| [getRequiredFeatures](../../com.aspose.html.dom.svg/svggraphicselement/requiredfeatures/) Corresponds to attribute ‘requiredFeatures’ on the given element. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Returns shadowRoot stored on this element or null if it's closed. |
| [getStyle](../../com.aspose.html.dom.svg/svgelement/style/) Corresponds to attribute ‘style’ on the given element. If the user agent does not support styling with CSS, then this attribute must always have the value of null. |
| [getSystemLanguage](../../com.aspose.html.dom.svg/svggraphicselement/systemlanguage/) Corresponds to attribute ‘systemLanguage’ on the given element. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) The name of the element. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new String is not empty or null, replaced by a single Text node containing the String this attribute is set to. |
| [getTransform](../../com.aspose.html.dom.svg/svggraphicselement/transform/) Corresponds to attribute ‘transform’ on the given element. |
| [getViewportElement](../../com.aspose.html.dom.svg/svgelement/viewportelement/) The element which established the current viewport. Often, the nearest ancestor ‘svg’ element. Null if the given element is the outermost svg element. |

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
| [createSVGPathSegArcAbs](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathsegarcabs/)(float, float, float, float, float, bool, bool) | Returns a stand-alone, parentless SVGPathSegArcAbs object. |
| [createSVGPathSegArcRel](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathsegarcrel/)(float, float, float, float, float, bool, bool) | Returns a stand-alone, parentless SVGPathSegArcRel object. |
| [createSVGPathSegClosePath](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathsegclosepath/)() | Returns a stand-alone, parentless SVGPathSegClosePath object. |
| [createSVGPathSegCurvetoCubicAbs](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathsegcurvetocubicabs/)(float, float, float, float, float, float) | Returns a stand-alone, parentless SVGPathSegCurvetoCubicAbs object. |
| [createSVGPathSegCurvetoCubicRel](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathsegcurvetocubicrel/)(float, float, float, float, float, float) | Returns a stand-alone, parentless SVGPathSegCurvetoCubicRel object. |
| [createSVGPathSegCurvetoCubicSmoothAbs](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathsegcurvetocubicsmoothabs/)(float, float, float, float) | Returns a stand-alone, parentless SVGPathSegCurvetoCubicSmoothAbs object. |
| [createSVGPathSegCurvetoCubicSmoothRel](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathsegcurvetocubicsmoothrel/)(float, float, float, float) | Returns a stand-alone, parentless SVGPathSegCurvetoCubicSmoothRel object. |
| [createSVGPathSegCurvetoQuadraticAbs](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathsegcurvetoquadraticabs/)(float, float, float, float) | Returns a stand-alone, parentless SVGPathSegCurvetoQuadraticAbs object. |
| [createSVGPathSegCurvetoQuadraticRel](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathsegcurvetoquadraticrel/)(float, float, float, float) | Returns a stand-alone, parentless SVGPathSegCurvetoQuadraticRel object. |
| [createSVGPathSegCurvetoQuadraticSmoothAbs](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathsegcurvetoquadraticsmoothabs/)(float, float) | Returns a stand-alone, parentless SVGPathSegCurvetoQuadraticSmoothAbs object. |
| [createSVGPathSegCurvetoQuadraticSmoothRel](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathsegcurvetoquadraticsmoothrel/)(float, float) | Returns a stand-alone, parentless SVGPathSegCurvetoQuadraticSmoothRel object. |
| [createSVGPathSegLinetoAbs](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathseglinetoabs/)(float, float) | Returns a stand-alone, parentless SVGPathSegLinetoAbs object. |
| [createSVGPathSegLinetoHorizontalAbs](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathseglinetohorizontalabs/)(float) | Returns a stand-alone, parentless SVGPathSegLinetoHorizontalAbs object. |
| [createSVGPathSegLinetoHorizontalRel](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathseglinetohorizontalrel/)(float) | Returns a stand-alone, parentless SVGPathSegLinetoHorizontalRel object. |
| [createSVGPathSegLinetoRel](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathseglinetorel/)(float, float) | Returns a stand-alone, parentless SVGPathSegLinetoRel object. |
| [createSVGPathSegLinetoVerticalAbs](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathseglinetoverticalabs/)(float) | Returns a stand-alone, parentless SVGPathSegLinetoVerticalAbs object. |
| [createSVGPathSegLinetoVerticalRel](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathseglinetoverticalrel/)(float) | Returns a stand-alone, parentless SVGPathSegLinetoVerticalRel object. |
| [createSVGPathSegMovetoAbs](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathsegmovetoabs/)(float, float) | Returns a stand-alone, parentless SVGPathSegMovetoAbs object. |
| [createSVGPathSegMovetoRel](../../com.aspose.html.dom.svg/svgpathelement/createsvgpathsegmovetorel/)(float, float) | Returns a stand-alone, parentless SVGPathSegMovetoRel object. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Dispatches an Event at the specified [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Retrieves an attribute value by name. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Returns the attribute names of the element as an Array of Strings. If the element has no attributes it returns an empty array. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Retrieves an attribute node by name. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Retrieves an Attr node by local name and package URI. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Retrieves an attribute value by local name and package URI. |
| [getBBox](../../com.aspose.html.dom.svg/svggraphicselement/getbbox/)() | Returns the tight bounding box in current user space (i.e., after application of the ‘transform’ attribute, if any) on the geometry of all contained graphics elements, exclusive of stroking, clipping, masking and filter effects). Note that getBBox must return the actual bounding box at the time the method was called, even in case the element has not yet been rendered. |
| [getCTM](../../com.aspose.html.dom.svg/svggraphicselement/getctm/)() | Returns the transformation matrix from current user units (i.e., after application of the ‘transform’ attribute, if any) to the viewport coordinate system for the nearestViewportElement. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Returns [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) object containing all the elements within [`element`](../../com.aspose.html.dom/element/) that have all the classes specified in argument. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Returns [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) object containing all [`elements`](../../com.aspose.html.dom/element/) with a given tag name, in document order. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Returns [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) object containing all [`elements`](../../com.aspose.html.dom/element/) with a given local name and package URI String in document order. |
| [getEquivalentPath](../../com.aspose.html.dom.svg/svggeometryelement/getequivalentpath/)() | Returns a new instance instance of the [`SVGPathSegList`](../../com.aspose.html.dom.svg.paths/svgpathseglist/) which represents [`SVGGeometryElement`](../svggeometryelement/) as path segments. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [getPointAtLength](../../com.aspose.html.dom.svg/svggeometryelement/getpointatlength/)(float) | Returns the (x,y) coordinate in user space which is distance units along the path, utilizing the user agent's distance-along-a-path algorithm. |
| [getScreenCTM](../../com.aspose.html.dom.svg/svggraphicselement/getscreenctm/)() | Returns the transformation matrix from current user units (i.e., after application of the ‘transform’ attribute, if any) to the parent user agent's notice of a "pixel". For display devices, ideally this represents a physical screen pixel. For other devices or environments where physical pixel sizes are not known, then an algorithm similar to the CSS2 definition of a "pixel" can be used instead. Note that null is returned if this element is not hooked into the document tree. This method would have been more aptly named as getClientCTM, but the name getScreenCTM is kept for historical reasons. |
| [getTotalLength](../../com.aspose.html.dom.svg/svggeometryelement/gettotallength/)() | Returns the user agent's computed value for the total length of the path using the user agent's distance-along-a-path algorithm, as a distance in the current user coordinate system. |
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
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Puts all [`Text`](../../com.aspose.html.dom/text/) nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), and [`entity references`](../../com.aspose.html.dom/entityreference/)) separates [`Text`](../../com.aspose.html.dom/text/) nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the [`DOMConfiguration`](../../com.aspose.html/configuration/) object attached to the [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) is true, this method will also fully normalize the characters of the Text nodes. |
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

### See Also

* class [SVGGeometryElement](../svggeometryelement/)
* interface [ISVGAnimatedPathData](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
