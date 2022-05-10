---
title: Element
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 800
url: /net/aspose.html.dom/element/
---
## Element class

The Element interface represents an element in an HTML or XML document.

```csharp
public class Element : Node, IChildNode, IParentNode
```

## Constructors

| Name | Description |
| --- | --- |
| [Element](element)(IElementInit) | Initializes a new instance of the [`Element`](../element) class. Don't call this constructor directly, use [`CreateElement`](../document/createelement) or [`CreateElementNS`](../document/createelementns). |

## Properties

| Name | Description |
| --- | --- |
| override [Attributes](attributes) { get; } | A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| [ChildElementCount](childelementcount) { get; } | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [Children](children) { get; } | Returns the child elements of current element. |
| [ClassList](classlist) { get; } | Returns a live DOMTokenList which contains tokens received from parsing the "class" attribute. |
| [ClassName](classname) { get; set; } | The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [FirstElementChild](firstelementchild) { get; } | Returns the first child element node of this element. null if this element has no child elements. |
| [Id](id) { get; set; } | The element's identifier. See the id attribute definition in HTML 4.01. |
| [InnerHTML](innerhtml) { get; set; } | Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given string. |
| [LastElementChild](lastelementchild) { get; } | Returns the last child element node of this element. null if this element has no child elements. |
| override [LocalName](localname) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| override [NamespaceURI](namespaceuri) { get; } | The namespace URI of this node, or null if it is unspecified. |
| [NextElementSibling](nextelementsibling) { get; } | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| override [NodeName](nodename) { get; } | The name of this node, depending on its type. |
| override [NodeType](nodetype) { get; } | A code representing the type of the underlying object. |
| [OuterHTML](outerhtml) { get; set; } | Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given string. |
| override [Prefix](prefix) { get; } | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [PreviousElementSibling](previouselementsibling) { get; } | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [SchemaTypeInfo](schematypeinfo) { get; } | The type information associated with this element. |
| [ShadowRoot](shadowroot) { get; } | Returns shadowRoot stored on this element or null if it's closed. |
| [TagName](tagname) { get; } | The name of the element. |
| override [TextContent](textcontent) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |

## Methods

| Name | Description |
| --- | --- |
| [AttachShadow](attachshadow)(ShadowRootMode) | Creates shadow root and attaches it to current element. |
| [GetAttribute](getattribute)(string) | Retrieves an attribute value by name. |
| [GetAttributeNode](getattributenode)(string) | Retrieves an attribute node by name. |
| [GetAttributeNodeNS](getattributenodens)(string, string) | Retrieves an Attr node by local name and namespace URI. |
| [GetAttributeNS](getattributens)(string, string) | Retrieves an attribute value by local name and namespace URI. |
| [GetElementsByClassName](getelementsbyclassname)(string) | Returns a live NodeList object containing all the elements in the document that have all the classes specified in argument. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](getelementsbytagname)(string) | Returns a NodeList of all descendant Elements with a given tag name, in document order. |
| [GetElementsByTagNameNS](getelementsbytagnamens)(string, string) | Returns a NodeList of all the descendant Elements with a given local name and namespace URI in document order. |
| [HasAttribute](hasattribute)(string) | Returns true when an attribute with a given name is specified on this element or has a default value, false otherwise. |
| [HasAttributeNS](hasattributens)(string, string) | Returns true when an attribute with a given local name and namespace URI is specified on this element or has a default value, false otherwise. |
| override [HasAttributes](hasattributes)() | Returns whether this node (if it is an element) has any attributes |
| [QuerySelector](queryselector)(string) | Returns the first Element in document, which match selector |
| [QuerySelectorAll](queryselectorall)(string) | Returns a NodeList of all the Elements in document, which match selector |
| [Remove](remove)() | Removes this instance. |
| [RemoveAttribute](removeattribute)(string) | Removes an attribute by name. |
| [RemoveAttributeNode](removeattributenode)(Attr) | Removes the specified attribute node. |
| [RemoveAttributeNS](removeattributens)(string, string) | Removes an attribute by local name and namespace URI. |
| [SetAttribute](setattribute)(string, string) | Adds a new attribute. If an attribute with that name is already present in the element, its value is changed to be that of the value parameter |
| [SetAttributeNode](setattributenode)(Attr) | Adds a new attribute node. If an attribute with that name (nodeName) is already present in the element, it is replaced by the new one. |
| [SetAttributeNodeNS](setattributenodens)(Attr) | Adds a new attribute. If an attribute with that local name and that namespace URI is already present in the element, it is replaced by the new one. |
| [SetAttributeNS](setattributens)(string, string, string) | Adds a new attribute. If an attribute with the same local name and namespace URI is already present on the element, its prefix is changed to be the prefix part of the qualifiedName, and its value is changed to be the value parameter. |
| [SetIdAttribute](setidattribute)(string, bool) | If the parameter isId is true, this method declares the specified attribute to be a user-determined ID attribute. |
| [SetIdAttributeNode](setidattributenode)(Attr, bool) | If the parameter isId is true, this method declares the specified attribute to be a user-determined ID attribute. |
| [SetIdAttributeNS](setidattributens)(string, string, bool) | If the parameter isId is true, this method declares the specified attribute to be a user-determined ID attribute. |

### See Also

* class [Node](../node)
* interface [IChildNode](../ichildnode)
* interface [IParentNode](../iparentnode)
* namespace [Aspose.Html.Dom](../../aspose.html.dom)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
