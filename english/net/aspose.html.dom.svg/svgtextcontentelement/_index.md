---
title: SVGTextContentElement
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 2450
url: /net/aspose.html.dom.svg/svgtextcontentelement/
---
## SVGTextContentElement class

The SVGTextContentElement is inherited by various text-related interfaces, such as SVGTextElement, SVGTSpanElement, SVGTRefElement, SVGAltGlyphElement and SVGTextPathElement. For the methods on this interface that refer to an index to a character or a number of characters, these references are to be interpreted as an index to a UTF-16 code unit or a number of UTF-16 code units, respectively. This is for consistency with DOM Level 2 Core, where methods on the CharacterData interface use UTF-16 code units as indexes and counts within the character data.Thus for example, if the text content of a ‘text’ element is a single non-BMP character, such as U+10000, then invoking getNumberOfChars on that element will return 2 since there are two UTF-16 code units(the surrogate pair) used to represent that one character.

```csharp
public class SVGTextContentElement : SVGGraphicsElement
```

## Properties

| Name | Description |
| --- | --- |
| override [Attributes](../../aspose.html.dom/element/attributes) { get; } | A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | The absolute base URI of this node or null if the implementation wasn't able to obtain an absolute URI. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount) { get; } | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | A NodeList that contains all children of this node. If there are no children, this is a NodeList containing no nodes.. |
| [Children](../../aspose.html.dom/element/children) { get; } | Returns the child elements of current element. |
| [ClassList](../../aspose.html.dom/element/classlist) { get; } | Returns a live DOMTokenList which contains tokens received from parsing the "class" attribute. |
| [ClassName](../../aspose.html.dom.svg/svgelement/classname) { get; } | Corresponds to attribute ‘class’ on the given element. |
| [ClassName](../../aspose.html.dom/element/classname) { get; set; } | The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [FarthestViewportElement](../../aspose.html.dom.svg/svggraphicselement/farthestviewportelement) { get; } | The farthest ancestor ‘svg’ element. Null if the current element is the outermost svg element. |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | The first child of this node. If there is no such node, this returns null. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild) { get; } | Returns the first child element node of this element. null if this element has no child elements. |
| [Id](../../aspose.html.dom.svg/svgelement/id) { get; set; } | The value of the ‘id’ attribute on the given element, or the empty string if ‘id’ is not present. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml) { get; set; } | Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given string. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | The last child of this node. If there is no such node, this returns null. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild) { get; } | Returns the last child element node of this element. null if this element has no child elements. |
| [LengthAdjust](../../aspose.html.dom.svg/svgtextcontentelement/lengthadjust) { get; } | Corresponds to attribute ‘lengthAdjust’ on the given element. The value must be one of the length adjust constants defined on this interface. |
| override [LocalName](../../aspose.html.dom/element/localname) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri) { get; } | The namespace URI of this node, or null if it is unspecified. |
| [NearestViewportElement](../../aspose.html.dom.svg/svggraphicselement/nearestviewportelement) { get; } | The element which established the current viewport. Often, the nearest ancestor ‘svg’ element. Null if the current element is the outermost svg element. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling) { get; } | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | The node immediately following this node. If there is no such node, this returns null. |
| override [NodeName](../../aspose.html.dom/element/nodename) { get; } | The name of this node, depending on its type. |
| override [NodeType](../../aspose.html.dom/element/nodetype) { get; } | A code representing the type of the underlying object. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | The value of this node, depending on its type. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml) { get; set; } | Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given string. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | The Document object associated with this node. This is also the Document object used to create new nodes. When this node is a Document or a DocumentType which is not used with any Document yet, this is null. |
| [OwnerSVGElement](../../aspose.html.dom.svg/svgelement/ownersvgelement) { get; } | The nearest ancestor ‘svg’ element. Null if the given element is the outermost svg element. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | Gets the parent [`Element`](../../aspose.html.dom/element) of this node. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | The parent of this node. All nodes, except Attr, Document, DocumentFragment, Entity, and Notation may have a parent. However, if a node has just been created and not yet added to the tree, or if it has been removed from the tree, this is null. |
| override [Prefix](../../aspose.html.dom/element/prefix) { get; } | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling) { get; } | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | The node immediately preceding this node. If there is no such node, this returns null. |
| [RequiredExtensions](../../aspose.html.dom.svg/svggraphicselement/requiredextensions) { get; } | Corresponds to attribute ‘requiredExtensions’ on the given element. |
| [RequiredFeatures](../../aspose.html.dom.svg/svggraphicselement/requiredfeatures) { get; } | Corresponds to attribute ‘requiredFeatures’ on the given element. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo) { get; } | The type information associated with this element. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot) { get; } | Returns shadowRoot stored on this element or null if it's closed. |
| [Style](../../aspose.html.dom.svg/svgelement/style) { get; } | Corresponds to attribute ‘style’ on the given element. If the user agent does not support styling with CSS, then this attribute must always have the value of null. |
| [SystemLanguage](../../aspose.html.dom.svg/svggraphicselement/systemlanguage) { get; } | Corresponds to attribute ‘systemLanguage’ on the given element. |
| [TagName](../../aspose.html.dom/element/tagname) { get; } | The name of the element. |
| override [TextContent](../../aspose.html.dom/element/textcontent) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [TextLength](../../aspose.html.dom.svg/svgtextcontentelement/textlength) { get; } | Corresponds to attribute ‘textLength’ on the given element. |
| [Transform](../../aspose.html.dom.svg/svggraphicselement/transform) { get; } | Corresponds to attribute ‘transform’ on the given element. |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement) { get; } | The element which established the current viewport. Often, the nearest ancestor ‘svg’ element. Null if the given element is the outermost svg element. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | This method allows the registration of event listeners on the event target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | This method allows the registration of event listeners on the event target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | This method allows the registration of event listeners on the event target. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | Adds the node newChild to the end of the list of children of this node. If the newChild is already in the tree, it is first removed. |
| [AttachShadow](../../aspose.html.dom/element/attachshadow)(ShadowRootMode) | Creates shadow root and attaches it to current element. |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | Returns a duplicate of this node, i.e., serves as a generic copy constructor for nodes. The duplicate node has no parent (parentNode is null) and no user data. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | This method allows the dispatch of events into the implementations event model. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [GetAttribute](../../aspose.html.dom/element/getattribute)(string) | Retrieves an attribute value by name. |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode)(string) | Retrieves an attribute node by name. |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens)(string, string) | Retrieves an Attr node by local name and namespace URI. |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens)(string, string) | Retrieves an attribute value by local name and namespace URI. |
| [GetBBox](../../aspose.html.dom.svg/svggraphicselement/getbbox)() | Returns the tight bounding box in current user space (i.e., after application of the ‘transform’ attribute, if any) on the geometry of all contained graphics elements, exclusive of stroking, clipping, masking and filter effects). Note that getBBox must return the actual bounding box at the time the method was called, even in case the element has not yet been rendered. |
| [GetComputedTextLength](../../aspose.html.dom.svg/svgtextcontentelement/getcomputedtextlength)() | The total sum of all of the advance values from rendering all of the characters within this element, including the advance value on the glyphs (horizontal or vertical), the effect of properties ‘kerning’, ‘letter-spacing’ and ‘word-spacing’ and adjustments due to attributes ‘dx’ and ‘dy’ on ‘tspan’ elements. For non-rendering environments, the user agent shall make reasonable assumptions about glyph metrics. |
| [GetCTM](../../aspose.html.dom.svg/svggraphicselement/getctm)() | Returns the transformation matrix from current user units (i.e., after application of the ‘transform’ attribute, if any) to the viewport coordinate system for the nearestViewportElement. |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname)(string) | Returns a live NodeList object containing all the elements in the document that have all the classes specified in argument. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname)(string) | Returns a NodeList of all descendant Elements with a given tag name, in document order. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens)(string, string) | Returns a NodeList of all the descendant Elements with a given local name and namespace URI in document order. |
| [GetNumberOfChars](../../aspose.html.dom.svg/svgtextcontentelement/getnumberofchars)() | Returns the total number of characters available for rendering within the current element, which includes referenced characters from ‘tref’ reference, regardless of whether they will be rendered. Effectively, this is equivalent to the length of the Node::textContent attribute from DOM Level 3 Core ([DOM3], section 1.4), if that attribute also expanded ‘tref’ elements. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | This method is used to retrieve ECMAScript object Type. |
| [GetScreenCTM](../../aspose.html.dom.svg/svggraphicselement/getscreenctm)() | Returns the transformation matrix from current user units (i.e., after application of the ‘transform’ attribute, if any) to the parent user agent's notice of a "pixel". For display devices, ideally this represents a physical screen pixel. For other devices or environments where physical pixel sizes are not known, then an algorithm similar to the CSS2 definition of a "pixel" can be used instead. Note that null is returned if this element is not hooked into the document tree. This method would have been more aptly named as getClientCTM, but the name getScreenCTM is kept for historical reasons. |
| [HasAttribute](../../aspose.html.dom/element/hasattribute)(string) | Returns true when an attribute with a given name is specified on this element or has a default value, false otherwise. |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens)(string, string) | Returns true when an attribute with a given local name and namespace URI is specified on this element or has a default value, false otherwise. |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes)() | Returns whether this node (if it is an element) has any attributes |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | Returns whether this node has any children. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children. If child is a DocumentFragment object, all of its children are inserted, in the same order, before child. If the child is already in the tree, it is first removed. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | This method checks if the specified namespaceURI is the default namespace or not. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | Tests whether two nodes are equal. This method tests for equality of nodes, not sameness (i.e., whether the two nodes are references to the same object) which can be tested with Node.isSameNode(). All nodes that are the same will also be equal, though the reverse may not be true. |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | Returns whether this node is the same node as the given one. This method provides a way to determine whether two Node references returned by the implementation reference the same object. When two Node references are references to the same object, even if through a proxy, the references may be used completely interchangeably, such that all attributes have the same values and calling the same DOM method on either reference always has exactly the same effect. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | Look up the namespace URI associated to the given prefix, starting from this node. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | Look up the prefix associated to the given namespace URI, starting from this node. The default namespace declarations are ignored by this method. See Namespace Prefix Lookup for details on the algorithm used by this method. |
| [Normalize](../../aspose.html.dom/node/normalize)() | Puts all Text nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., elements, comments, processing instructions, CDATA sections, and entity references) separates Text nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the DOMConfiguration object attached to the Node.ownerDocument is true, this method will also fully normalize the characters of the Text nodes. |
| [QuerySelector](../../aspose.html.dom/element/queryselector)(string) | Returns the first Element in document, which match selector |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall)(string) | Returns a NodeList of all the Elements in document, which match selector |
| [Remove](../../aspose.html.dom/element/remove)() | Removes this instance. |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute)(string) | Removes an attribute by name. |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode)(Attr) | Removes the specified attribute node. |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens)(string, string) | Removes an attribute by local name and namespace URI. |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | Removes the child node indicated by oldChild from the list of children, and returns it. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](../../aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](../../aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an [`IEventListener`](../../aspose.html.dom.events/ieventlistener) is removed from an [`EventTarget`](../../aspose.html.dom/eventtarget) while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a DocumentFragment object, oldChild is replaced by all of the DocumentFragment children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [SetAttribute](../../aspose.html.dom/element/setattribute)(string, string) | Adds a new attribute. If an attribute with that name is already present in the element, its value is changed to be that of the value parameter |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode)(Attr) | Adds a new attribute node. If an attribute with that name (nodeName) is already present in the element, it is replaced by the new one. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens)(Attr) | Adds a new attribute. If an attribute with that local name and that namespace URI is already present in the element, it is replaced by the new one. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens)(string, string, string) | Adds a new attribute. If an attribute with the same local name and namespace URI is already present on the element, its prefix is changed to be the prefix part of the qualifiedName, and its value is changed to be the value parameter. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute)(string, bool) | If the parameter isId is true, this method declares the specified attribute to be a user-determined ID attribute. |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode)(Attr, bool) | If the parameter isId is true, this method declares the specified attribute to be a user-determined ID attribute. |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens)(string, string, bool) | If the parameter isId is true, this method declares the specified attribute to be a user-determined ID attribute. |
| override [ToString](../../aspose.html.dom/node/tostring)() | Returns a String that represents this instance. |

## Other Members

| Name | Description |
| --- | --- |
| const [LENGTHADJUST_SPACING](lengthadjust_spacing) | Corresponds to value 'spacing'. |
| const [LENGTHADJUST_SPACINGANDGLYPHS](lengthadjust_spacingandglyphs) | Corresponds to value 'spacingAndGlyphs'. |
| const [LENGTHADJUST_UNKNOWN](lengthadjust_unknown) | The enumeration was set to a value that is not one of predefined types. It is invalid to attempt to define a new value of this type or to attempt to switch an existing value to this type. |

### See Also

* class [SVGElement](../svgelement)
* class [SVGGraphicsElement](../svggraphicselement)
* namespace [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
