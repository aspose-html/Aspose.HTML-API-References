---
title: HTMLInputElement
second_title: Aspose.HTML for .NET API Reference
description: Form control. Depending upon the environment in which the page is being viewed the value property may be read-only for the file upload input type. For the password input type the actual value returned may be masked to prevent unauthorized use. See the INPUT element definition in HTML 4.01http//www.w3.org/TR/1999/REC-html401-19991224.See also the Document object Model DOM Level 2 HTML Specificationhttp//www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109.
type: docs
weight: 3320
url: /net/aspose.html/htmlinputelement/
---
## HTMLInputElement class

Form control. Depending upon the environment in which the page is being viewed, the value property may be read-only for the file upload input type. For the "password" input type, the actual value returned may be masked to prevent unauthorized use. See the INPUT element definition in [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)].See also the [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```csharp
public class HTMLInputElement : HTMLElement
```

## Properties

| Name | Description |
| --- | --- |
| [Accept](../../aspose.html/htmlinputelement/accept) { get; set; } | A comma-separated list of content types that a server processing this form will handle correctly. See the accept attribute definition in HTML 4.01. |
| [AccessKey](../../aspose.html/htmlinputelement/accesskey) { get; set; } | A single character access key to give access to the form control. See the accesskey attribute definition in HTML 4.01. |
| [Align](../../aspose.html/htmlinputelement/align) { get; set; } | Aligns this object (vertically or horizontally) with respect to its surrounding text. See the align attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
| [Alt](../../aspose.html/htmlinputelement/alt) { get; set; } | Alternate text for user agents not rendering the normal content of this element. See the alt attribute definition in HTML 4.01. |
| override [Attributes](../../aspose.html.dom/element/attributes) { get; } | A NamedNodeMap containing the attributes of this node (if it is an Element) or null otherwise. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | The read-only baseURI property of the Node interface returns the absolute base URL of the document containing the node. |
| [Checked](../../aspose.html/htmlinputelement/checked) { get; set; } | When the `type` attribute of the element has the value "radio" or "checkbox", this represents the current state of the form control, in an interactive user agent. Changes to this attribute change the state of the form control, but do not change the value of the HTML checked attribute of the INPUT element.During the handling of a click event on an input element with a type attribute that has the value "radio" or "checkbox", some implementations may change the value of this property before the event is being dispatched in the document. If the default action of the event is canceled, the value of the property may be changed back to its original value. This means that the value of this property during the handling of click events is implementation dependent. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount) { get; } | Returns the current number of element nodes that are children of this element. 0 if this element has no child nodes that are of nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | The read-only childNodes property of the Node interface returns a live [`NodeList`](../../aspose.html.collections/nodelist) of child nodes of the given element where the first child node is assigned index 0. Child nodes include elements, text and comments. |
| [Children](../../aspose.html.dom/element/children) { get; } | Returns the child elements of current element. |
| [ClassList](../../aspose.html.dom/element/classlist) { get; } | Returns a live DOMTokenList which contains tokens received from parsing the "class" attribute. |
| [ClassName](../../aspose.html/htmlelement/classname) { get; set; } | The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [DefaultChecked](../../aspose.html/htmlinputelement/defaultchecked) { get; set; } | When `type` has the value "radio" or "checkbox", this represents the HTML checked attribute of the element. The value of this attribute does not change if the state of the corresponding form control, in an interactive user agent, changes. See the checked attribute definition in HTML 4.01. |
| [DefaultValue](../../aspose.html/htmlinputelement/defaultvalue) { get; set; } | When the `type` attribute of the element has the value "text", "file" or "password", this represents the HTML value attribute of the element. The value of this attribute does not change if the contents of the corresponding form control, in an interactive user agent, changes. See the value attribute definition in HTML 4.01. |
| [Dir](../../aspose.html/htmlelement/dir) { get; set; } | Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
| [Disabled](../../aspose.html/htmlinputelement/disabled) { get; set; } | The control is unavailable in this context. See the disabled attribute definition in HTML 4.01. |
| [Files](../../aspose.html/htmlinputelement/files) { get; } | The files IDL attribute allows scripts to access the element’s selected files. On getting, if the IDL attribute applies, it must return a FileList object that represents the current selected files. The same object must be returned until the list of selected files changes. If the IDL attribute does not apply, then it must instead return null. [FILEAPI] |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | The read-only firstChild property of the [`Node`](../../aspose.html.dom/node) interface returns the node's first child in the tree, or null if the node has no children. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild) { get; } | Returns the first child element node of this element. null if this element has no child elements. |
| [Form](../../aspose.html/htmlinputelement/form) { get; set; } | Returns the `FORM` element containing this control. Returns `null` if this control is not within the context of a form. |
| [Id](../../aspose.html/htmlelement/id) { get; set; } | The element's identifier. See the id attribute definition in HTML 4.01. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml) { get; set; } | Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given string. |
| [Lang](../../aspose.html/htmlelement/lang) { get; set; } | Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | The read-only lastChild property of the [`Node`](../../aspose.html.dom/node) interface returns the last child of the node. If its parent is an element, then the child is generally an element node, a text node, or a comment node. It returns null if there are no child elements |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild) { get; } | Returns the last child element node of this element. null if this element has no child elements. |
| [List](../../aspose.html/htmlinputelement/list) { get; set; } | The list attribute is used to identify an element that lists predefined options suggested to the user. If present, its value must be the ID of a datalist element in the same document. |
| override [LocalName](../../aspose.html.dom/element/localname) { get; } | Returns the local part of the qualified name of this node. For nodes of any type other than ELEMENT_NODE and ATTRIBUTE_NODE and nodes created with a DOM Level 1 method, such as Document.createElement(), this is always null. |
| [MaxLength](../../aspose.html/htmlinputelement/maxlength) { get; set; } | Maximum number of characters for text fields, when `type`has the value "text" or "password". See the maxlength attribute definition in HTML 4.01. |
| [Name](../../aspose.html/htmlinputelement/name) { get; set; } | Form control or object name when submitted with a form. See the name attribute definition in HTML 4.01. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri) { get; } | The namespace URI of this node, or null if it is unspecified. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling) { get; } | Returns the next sibling element node of this element. null if this element has no element sibling nodes that come after this one in the document tree. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | The read-only nextSibling property of the [`Node`](../../aspose.html.dom/node) interface returns the node immediately following the specified one in their parent's [`childNodes`](../../aspose.html.dom/node/childnodes), or returns null if the specified node is the last child in the parent element. |
| override [NodeName](../../aspose.html.dom/element/nodename) { get; } | The name of this node, depending on its type. |
| override [NodeType](../../aspose.html.dom/element/nodetype) { get; } | A code representing the type of the underlying object. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | The nodeValue property of the [`Node `](../../aspose.html.dom/node)interface returns or sets the value of the current node. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml) { get; set; } | Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given string. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | The read-only ownerDocument property of the Node interface returns the top-level document object of the node. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | The read-only parentElement property of [`Node`](../../aspose.html.dom/node) interface returns the DOM node's parent [`Element`](../../aspose.html.dom/element), or null if the node either has no parent, or its parent isn't a DOM Element. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | The read-only parentNode property of the Node interface returns the parent of the specified node in the DOM tree. |
| override [Prefix](../../aspose.html.dom/element/prefix) { get; } | The namespace prefix of this node, or null if it is unspecified. When it is defined to be null, setting it has no effect |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling) { get; } | Returns the previous sibling element node of this element. null if this element has no element sibling nodes that come before this one in the document tree. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | The read-only previousSibling property of the [`Node`](../../aspose.html.dom/node) interface returns the node immediately preceding the specified one in its parent's [`childNodes`](../../aspose.html.dom/node/firstchild) list, or null if the specified node is the first in that list. |
| [ReadOnly](../../aspose.html/htmlinputelement/readonly) { get; set; } | This control is read-only. Relevant only when `type` has the value "text" or "password". See the readonly attribute definition in HTML 4.01. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo) { get; } | The type information associated with this element. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot) { get; } | Returns shadowRoot stored on this element or null if it's closed. |
| [Size](../../aspose.html/htmlinputelement/size) { get; set; } | Size information. The precise meaning is specific to each type of field. See the size attribute definition in HTML 4.01. @version DOM Level 2 |
| [Src](../../aspose.html/htmlinputelement/src) { get; set; } | When the `type` attribute has the value "image", this attribute specifies the location of the image to be used to decorate the graphical submit button. See the src attribute definition in HTML 4.01. |
| [Style](../../aspose.html/htmlelement/style) { get; } | Represents a style attribute that allows author to directly apply style information to specific element. |
| [TabIndex](../../aspose.html/htmlinputelement/tabindex) { get; set; } | Index that represents the element's position in the tabbing order. See the tabindex attribute definition in HTML 4.01. |
| [TagName](../../aspose.html.dom/element/tagname) { get; } | The name of the element. |
| override [TextContent](../../aspose.html.dom/element/textcontent) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new string is not empty or null, replaced by a single Text node containing the string this attribute is set to. |
| [Title](../../aspose.html/htmlelement/title) { get; set; } | The element's advisory title. See the title attribute definition in HTML 4.01. |
| [Type](../../aspose.html/htmlinputelement/type) { get; set; } | The type of control created (all lower case). See the type attribute definition in HTML 4.01. @version DOM Level 2 |
| [UseMap](../../aspose.html/htmlinputelement/usemap) { get; set; } | Use client-side image map. See the usemap attribute definition in HTML 4.01. |
| [Value](../../aspose.html/htmlinputelement/value) { get; set; } | When the `type` attribute of the element has the value "text", "file" or "password", this represents the current contents of the corresponding form control, in an interactive user agent. Changing this attribute changes the contents of the form control, but does not change the value of the HTML value attribute of the element. When the `type` attribute of the element has the value "button", "hidden", "submit", "reset", "image", "checkbox" or "radio", this represents the HTML value attribute of the element. See the value attribute definition in HTML 4.01. |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | The addEventListener() method of the [`EventTarget `](../../aspose.html.dom/eventtarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | The addEventListener() method of the [EventTarget ](T:Aspose.Html.Dom.EventTarget)interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | The appendChild() method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node). |
| [AttachShadow](../../aspose.html.dom/element/attachshadow)(ShadowRootMode) | Creates shadow root and attaches it to current element. |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | Dispatches an Event at the specified [`EventTarget`](../../aspose.html.dom.events/ieventtarget), (synchronously) invoking the affected EventListeners in the appropriate order. The normal event processing rules (including the capturing and optional bubbling phase) also apply to events dispatched manually with [`dispatchEvent()`](../../aspose.html.dom.events/ieventtarget/dispatchevent). |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [GetAttribute](../../aspose.html.dom/element/getattribute)(string) | Retrieves an attribute value by name. |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode)(string) | Retrieves an attribute node by name. |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens)(string, string) | Retrieves an Attr node by local name and namespace URI. |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens)(string, string) | Retrieves an attribute value by local name and namespace URI. |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname)(string) | Returns [`HTMLCollection`](../../aspose.html.collections/htmlcollection) object containing all the elements within [`element`](../../aspose.html.dom/element) that have all the classes specified in argument. |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname)(string) | Returns [`HTMLCollection`](../../aspose.html.collections/htmlcollection) object containing all [`elements`](../../aspose.html.dom/element) with a given tag name, in document order. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens)(string, string) | Returns [`HTMLCollection`](../../aspose.html.collections/htmlcollection) object containing all [`elements`](../../aspose.html.dom/element) with a given local name and namespace URI string in document order. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | This method is used to retrieve the ECMAScript object . |
| [HasAttribute](../../aspose.html.dom/element/hasattribute)(string) | Returns true when an attribute with a given name is specified on this element or has a default value, false otherwise. |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens)(string, string) | Returns true when an attribute with a given local name and namespace URI is specified on this element or has a default value, false otherwise. |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes)() | Returns whether this node (if it is an element) has any attributes |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | The hasChildNodes() method of the Node interface returns a boolean value indicating whether the given [`Node`](../../aspose.html.dom/node) has child nodes or not. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | The insertBefore() method of the Node interface inserts a node before a reference node as a child of a specified parent node. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | The isDefaultNamespace() method of the Node interface accepts a namespace URI as an argument. It returns a boolean value that is true if the namespace is the default namespace on the given node and false if not. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | The isEqualNode() method of the [`Node`](../../aspose.html.dom/node) interface tests whether two nodes are equal. Two nodes are equal when they have the same type, defining characteristics (for elements, this would be their ID, number of children, and so forth), its attributes match, and so on. The specific set of data points that must match varies depending on the types of the nodes. |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | The isSameNode() method of the Node interface is a legacy alias the for the === strict equality operator. That is, it tests whether two nodes are the same (in other words, whether they reference the same object). |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | The lookupNamespaceURI() method of the Node interface takes a prefix as parameter and returns the namespace URI associated with it on the given node if found (and null if not). |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | The lookupPrefix() method of the Node interface returns a String containing the prefix for a given namespace URI, if present, and null if not. When multiple prefixes are possible, the first prefix is returned. |
| [Normalize](../../aspose.html.dom/node/normalize)() | Puts all [`Text`](../../aspose.html.dom/text) nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., [`elements`](../../aspose.html.dom/element), [`comments`](../../aspose.html.dom/comment), [`processing instructions`](../../aspose.html.dom/processinginstruction), [`CDATA sections`](../../aspose.html.dom/cdatasection), and [`entity references`](../../aspose.html.dom/entityreference)) separates [`Text`](../../aspose.html.dom/text) nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the [`DOMConfiguration`](../configuration) object attached to the [`Node.ownerDocument`](../../aspose.html.dom/node/ownerdocument) is true, this method will also fully normalize the characters of the Text nodes. |
| [QuerySelector](../../aspose.html.dom/element/queryselector)(string) | Returns the first Element in document, which match selector |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall)(string) | Returns a NodeList of all the Elements in document, which match selector |
| [Remove](../../aspose.html.dom/element/remove)() | Removes this instance. |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute)(string) | Removes an attribute by name. |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode)(Attr) | Removes the specified attribute node. |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens)(string, string) | Removes an attribute by local name and namespace URI. |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | The removeChild() method of the Node interface removes a child node from the DOM and returns the removed node. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | Replaces the child node oldChild with newChild in the list of children, and returns the oldChild node. If newChild is a [`DocumentFragment`](../../aspose.html.dom/documentfragment) object, oldChild is replaced by all of the [`DocumentFragment`](../../aspose.html.dom/documentfragment) children, which are inserted in the same order. If the newChild is already in the tree, it is first removed. |
| [SetAttribute](../../aspose.html.dom/element/setattribute)(string, string) | Adds a new attribute. If an attribute with that name is already present in the element, its value is changed to be that of the value parameter |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode)(Attr) | Adds a new attribute node. If an attribute with that name (nodeName) is already present in the element, it is replaced by the new one. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens)(Attr) | Adds a new attribute. If an attribute with that local name and that namespace URI is already present in the element, it is replaced by the new one. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens)(string, string, string) | Adds a new attribute. If an attribute with the same local name and namespace URI is already present on the element, its prefix is changed to be the prefix part of the qualifiedName, and its value is changed to be the value parameter. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute)(string, bool) | If the parameter isId is true, this method declares the specified attribute to be a user-determined ID attribute. |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode)(Attr, bool) | If the parameter isId is true, this method declares the specified attribute to be a user-determined ID attribute. |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens)(string, string, bool) | If the parameter isId is true, this method declares the specified attribute to be a user-determined ID attribute. |
| override [ToString](../../aspose.html.dom/node/tostring)() | Returns a String that represents this instance. |

### Examples

```csharp
using System;
using System.IO;
using Aspose.Html;
using Aspose.Html.Forms;
...
using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLFormElement formElement = (HTMLFormElement) document.CreateElement("form");
	// Label Element - First name
	// <label for="fname">First name:</label><br>
	HTMLLabelElement labelFirstName = (HTMLLabelElement)document.CreateElement("label");
	labelFirstName.For = "fname";
	labelFirstName.InnerHTML = "First name:";
	formElement.AppendChild(labelFirstName);
	formElement.AppendChild(document.CreateElement("br"));

	// Input Element for First name
	// <input type="text" id="fname" name="fname"><br>
	HTMLInputElement inputFirstName = (HTMLInputElement)document.CreateElement("input");
	inputFirstName.Type = InputElementType.Text.ToString(); // "text";
	inputFirstName.Id = "fname";
	inputFirstName.Name = "fname";
	formElement.AppendChild(inputFirstName);
	formElement.AppendChild(document.CreateElement("br"));

	// Label Element - Last name
	// <label for="lname">Last name:</label><br>
	HTMLLabelElement labelLastName = (HTMLLabelElement)document.CreateElement("label");
	labelLastName.For = "lname";
	labelLastName.InnerHTML = "Last name:";
	formElement.AppendChild(labelLastName);
	formElement.AppendChild(document.CreateElement("br"));

	// Input Element for Last name
	// <input type="text" id="lname" name="lname"><br><br>
	HTMLInputElement inputLastName = (HTMLInputElement)document.CreateElement("input");
	inputLastName.Type = InputElementType.Text.ToString(); // "text";
	inputLastName.Id = "lname";
	inputLastName.Name = "lname";
	formElement.AppendChild(inputLastName);
	formElement.AppendChild(document.CreateElement("br"));
	formElement.AppendChild(document.CreateElement("br"));

	// Input Element - Submit
	HTMLInputElement inputSubmit = (HTMLInputElement)document.CreateElement("input");
	inputSubmit.Type = InputElementType.Submit.ToString(); // "submit";
	inputSubmit.Value = "Submit";
	formElement.AppendChild(inputSubmit);
         
	document.Body.AppendChild(formElement);
         
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### See Also

* class [HTMLElement](../htmlelement)
* namespace [Aspose.Html](../../aspose.html)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
