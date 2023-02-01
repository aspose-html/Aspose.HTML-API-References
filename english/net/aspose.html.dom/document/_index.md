---
title: Document
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 660
url: /net/aspose.html.dom/document/
---
## Document class

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Properties

| Name | Description |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } |  |
| override [BaseURI](../../aspose.html.dom/document/baseuri/) { get; } |  |
| [CharacterSet](../../aspose.html.dom/document/characterset/) { get; } |  |
| [Charset](../../aspose.html.dom/document/charset/) { get; } |  |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount/) { get; } |  |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } |  |
| [Children](../../aspose.html.dom/document/children/) { get; } |  |
| [ContentType](../../aspose.html.dom/document/contenttype/) { get; } |  |
| [Context](../../aspose.html.dom/document/context/) { get; } |  |
| [DefaultView](../../aspose.html.dom/document/defaultview/) { get; } |  |
| [Doctype](../../aspose.html.dom/document/doctype/) { get; } |  |
| [DocumentElement](../../aspose.html.dom/document/documentelement/) { get; } |  |
| [DocumentURI](../../aspose.html.dom/document/documenturi/) { get; } |  |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } |  |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild/) { get; } |  |
| [Implementation](../../aspose.html.dom/document/implementation/) { get; } |  |
| [InputEncoding](../../aspose.html.dom/document/inputencoding/) { get; } |  |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } |  |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild/) { get; } |  |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } |  |
| [Location](../../aspose.html.dom/document/location/) { get; } |  |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } |  |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling/) { get; } |  |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } |  |
| override [NodeName](../../aspose.html.dom/document/nodename/) { get; } |  |
| override [NodeType](../../aspose.html.dom/document/nodetype/) { get; } |  |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } |  |
| [Origin](../../aspose.html.dom/document/origin/) { get; } |  |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument/) { get; } |  |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } |  |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } |  |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } |  |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling/) { get; } |  |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } |  |
| [ReadyState](../../aspose.html.dom/document/readystate/) { get; } |  |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking/) { get; set; } |  |
| [StyleSheets](../../aspose.html.dom/document/stylesheets/) { get; } |  |
| virtual [TextContent](../../aspose.html.dom/node/textcontent/) { get; set; } |  |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone/) { get; set; } |  |
| [XmlVersion](../../aspose.html.dom/document/xmlversion/) { get; set; } |  |

## Methods

| Name | Description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) |  |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) |  |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) |  |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) |  |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() |  |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) |  |
| [CreateAttribute](../../aspose.html.dom/document/createattribute/)(string) |  |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens/)(string, string) |  |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection/)(string) |  |
| [CreateComment](../../aspose.html.dom/document/createcomment/)(string) |  |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment/)() |  |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype/)(string, string, string, string) |  |
| [CreateElement](../../aspose.html.dom/document/createelement/)(string) |  |
| [CreateElementNS](../../aspose.html.dom/document/createelementns/)(string, string) |  |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference/)(string) |  |
| [CreateEvent](../../aspose.html.dom/document/createevent/)(string) |  |
| [CreateExpression](../../aspose.html.dom/document/createexpression/)(string, IXPathNSResolver) |  |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/#createnodeiterator)(Node) |  |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/#createnodeiterator_1)(Node, long) |  |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) |  |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver/)(Node) |  |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction/)(string, string) |  |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode/)(string) |  |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/#createtreewalker)(Node) |  |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/#createtreewalker_1)(Node, long) |  |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) |  |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) |  |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() |  |
| [Evaluate](../../aspose.html.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) |  |
| [GetElementById](../../aspose.html.dom/document/getelementbyid/)(string) |  |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname/)(string) |  |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname/)(string) |  |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens/)(string, string) |  |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() |  |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() |  |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() |  |
| [ImportNode](../../aspose.html.dom/document/importnode/)(Node, bool) |  |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) |  |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) |  |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) |  |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) |  |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) |  |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) |  |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate)(RequestMessage) |  |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_4)(string) |  |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_1)(Url) |  |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_3)(Stream, string) |  |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_2)(Stream, Url) |  |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_6)(string, string) |  |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_5)(string, Url) |  |
| [Normalize](../../aspose.html.dom/node/normalize/)() |  |
| [QuerySelector](../../aspose.html.dom/document/queryselector/)(string) |  |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall/)(string) |  |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) |  |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) |  |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) |  |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) |  |
| virtual [RenderTo](../../aspose.html.dom/document/renderto/)(IDevice) |  |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) |  |
| override [ToString](../../aspose.html.dom/node/tostring/)() |  |
| [Write](../../aspose.html.dom/document/write/)(params string[]) |  |
| [WriteLn](../../aspose.html.dom/document/writeln/)(params string[]) |  |

## Events

| Name | Description |
| --- | --- |
| event [OnAbort](../../aspose.html.dom/document/onabort/) |  |
| event [OnBlur](../../aspose.html.dom/document/onblur/) |  |
| event [OnCancel](../../aspose.html.dom/document/oncancel/) |  |
| event [OnCanplay](../../aspose.html.dom/document/oncanplay/) |  |
| event [OnCanPlayThrough](../../aspose.html.dom/document/oncanplaythrough/) |  |
| event [OnChange](../../aspose.html.dom/document/onchange/) |  |
| event [OnClick](../../aspose.html.dom/document/onclick/) |  |
| event [OnCueChange](../../aspose.html.dom/document/oncuechange/) |  |
| event [OnDblClick](../../aspose.html.dom/document/ondblclick/) |  |
| event [OnDurationChange](../../aspose.html.dom/document/ondurationchange/) |  |
| event [OnEmptied](../../aspose.html.dom/document/onemptied/) |  |
| event [OnEnded](../../aspose.html.dom/document/onended/) |  |
| event [OnError](../../aspose.html.dom/document/onerror/) |  |
| event [OnFocus](../../aspose.html.dom/document/onfocus/) |  |
| event [OnInput](../../aspose.html.dom/document/oninput/) |  |
| event [OnInvalid](../../aspose.html.dom/document/oninvalid/) |  |
| event [OnKeyDown](../../aspose.html.dom/document/onkeydown/) |  |
| event [OnKeyPress](../../aspose.html.dom/document/onkeypress/) |  |
| event [OnKeyUp](../../aspose.html.dom/document/onkeyup/) |  |
| event [OnLoad](../../aspose.html.dom/document/onload/) |  |
| event [OnLoadedData](../../aspose.html.dom/document/onloadeddata/) |  |
| event [OnLoadedMetadata](../../aspose.html.dom/document/onloadedmetadata/) |  |
| event [OnLoadStart](../../aspose.html.dom/document/onloadstart/) |  |
| event [OnMouseDown](../../aspose.html.dom/document/onmousedown/) |  |
| event [OnMouseEnter](../../aspose.html.dom/document/onmouseenter/) |  |
| event [OnMouseLeave](../../aspose.html.dom/document/onmouseleave/) |  |
| event [OnMouseMove](../../aspose.html.dom/document/onmousemove/) |  |
| event [OnMouseOut](../../aspose.html.dom/document/onmouseout/) |  |
| event [OnMouseOver](../../aspose.html.dom/document/onmouseover/) |  |
| event [OnMouseUp](../../aspose.html.dom/document/onmouseup/) |  |
| event [OnMouseWheel](../../aspose.html.dom/document/onmousewheel/) |  |
| event [OnPause](../../aspose.html.dom/document/onpause/) |  |
| event [OnPlay](../../aspose.html.dom/document/onplay/) |  |
| event [OnPlaying](../../aspose.html.dom/document/onplaying/) |  |
| event [OnProgress](../../aspose.html.dom/document/onprogress/) |  |
| event [OnRateChange](../../aspose.html.dom/document/onratechange/) |  |
| event [OnReadyStateChange](../../aspose.html.dom/document/onreadystatechange/) |  |
| event [OnReset](../../aspose.html.dom/document/onreset/) |  |
| event [OnResize](../../aspose.html.dom/document/onresize/) |  |
| event [OnScroll](../../aspose.html.dom/document/onscroll/) |  |
| event [OnSeeked](../../aspose.html.dom/document/onseeked/) |  |
| event [OnSeeking](../../aspose.html.dom/document/onseeking/) |  |
| event [OnSelect](../../aspose.html.dom/document/onselect/) |  |
| event [OnShow](../../aspose.html.dom/document/onshow/) |  |
| event [OnStalled](../../aspose.html.dom/document/onstalled/) |  |
| event [OnSubmit](../../aspose.html.dom/document/onsubmit/) |  |
| event [OnSuspend](../../aspose.html.dom/document/onsuspend/) |  |
| event [OnTimeUpdate](../../aspose.html.dom/document/ontimeupdate/) |  |
| event [OnToggle](../../aspose.html.dom/document/ontoggle/) |  |
| event [OnVolumeChange](../../aspose.html.dom/document/onvolumechange/) |  |
| event [OnWaiting](../../aspose.html.dom/document/onwaiting/) |  |

### See Also

* class [Node](../node/)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../aspose.html.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../aspose.html.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../aspose.html.dom.xpath/ixpathevaluator/)
* namespace [Aspose.Html.Dom](../../aspose.html.dom/)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
