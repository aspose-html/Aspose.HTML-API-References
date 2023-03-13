---
title: Class SVGDocument
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Svg.SVGDocument 班级. 一个SVG文档是 SVG 层次结构的根包含全部内容除了提供对层次结构的访问外它还提供了一些方便的方法来访问文档中的某些信息集 当svg元素作为来自另一个命名空间的文档的组件内联嵌入时例如当svg元素内联嵌入到 XHTML 文档 XHTML 中那么 SVGDocument 对象将不存在相反文档对象层次结构中的根对象将是不同类型的文档对象例如 HTMLDocument 对象 但是当 XML 文档层次结构的根元素是svg元素时SVGDocument 对象确实存在例如在查看独立的 SVG 文件即 MIME 类型为image/svgxml的文件时在这种情况下SVGDocument 对象将是文档对象模型层次结构的根对象
type: docs
weight: 2010
url: /zh/net/aspose.html.dom.svg/svgdocument/
---
## SVGDocument class

一个`SVG文档`是 SVG 层次结构的根，包含全部内容。除了提供对层次结构的访问外，它还提供了一些方便的方法来访问文档中的某些信息集。 当“svg”元素作为来自另一个命名空间的文档的组件内联嵌入时，例如当“svg”元素内联嵌入到 XHTML 文档 [XHTML] 中，那么 SVGDocument 对象将不存在；相反，文档对象层次结构中的根对象将是不同类型的文档对象，例如 HTMLDocument 对象。 但是，当 XML 文档层次结构的根元素是“svg”元素时，SVGDocument 对象确实存在，例如在查看独立的 SVG 文件（即 MIME 类型为“image/svg+xml”的文件）时。在这种情况下，SVGDocument 对象将是文档对象模型层次结构的根对象。

```csharp
public class SVGDocument : Document, IDocumentCSS
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SVGDocument](svgdocument/#constructor)() | 初始化一个新的实例`SVGDocument`类. |
| [SVGDocument](svgdocument/#constructor_1)(Configuration) | 初始化一个新的实例`SVGDocument`类. |
| [SVGDocument](svgdocument/#constructor_2)(RequestMessage) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_10)(string) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_4)(Url) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_3)(RequestMessage, Configuration) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_8)(Stream, string) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . 文档加载从流中的当前位置开始。 |
| [SVGDocument](svgdocument/#constructor_6)(Stream, Url) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . 文档加载从流中的当前位置开始。 |
| [SVGDocument](svgdocument/#constructor_11)(string, Configuration) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_14)(string, string) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_12)(string, Url) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_5)(Url, Configuration) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_9)(Stream, string, Configuration) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . 文档加载从流中的当前位置开始。 |
| [SVGDocument](svgdocument/#constructor_7)(Stream, Url, Configuration) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . 文档加载从流中的当前位置开始。 |
| [SVGDocument](svgdocument/#constructor_15)(string, string, Configuration) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_13)(string, Url, Configuration) | 初始化一个新的实例`SVGDocument`班级。构造函数同步工作，它等待加载所有外部资源（图像、脚本等）。 异步加载文档使用方法[`Navigate`](../../aspose.html.dom/document/navigate/)或其重载。 或者您可以通过在中设置适当的标志来禁用某些外部资源的加载[`Security`](../../aspose.html.dom/ibrowsingcontext/security/). |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | 包含此节点属性的 NamedNodeMap（如果它是一个元素）或 null 否则。 |
| override [BaseURI](../../aspose.html.dom/document/baseuri/) { get; } | 此节点的绝对基 URI，如果实现无法获得绝对 URI，则为 null。 |
| [CharacterSet](../../aspose.html.dom/document/characterset/) { get; } | 获取文档的编码。 |
| [Charset](../../aspose.html.dom/document/charset/) { get; } | 获取文档的编码。 |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount/) { get; } | 返回作为该元素子元素的元素节点的当前数量。如果此元素没有节点类型为 1. 的子节点，则为 0 |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | 包含此节点的所有子节点的 NodeList。如果没有孩子，这是一个不包含节点的 NodeList.. |
| [Children](../../aspose.html.dom/document/children/) { get; } | 返回子元素。 |
| [ContentType](../../aspose.html.dom/document/contenttype/) { get; } | 获取文档内容类型。 |
| [Context](../../aspose.html.dom/document/context/) { get; } | 获取当前浏览上下文。 |
| [DefaultView](../../aspose.html.dom/document/defaultview/) { get; } | Document 接口的 defaultView IDL 属性，在获取时， 必须返回此 Document 的浏览上下文的 WindowProxy 对象， 如果此 Document 具有关联的浏览上下文，否则返回 null. |
| [Doctype](../../aspose.html.dom/document/doctype/) { get; } | 与此文档关联的文档类型声明。 |
| [DocumentElement](../../aspose.html.dom/document/documentelement/) { get; } | 这是一个方便的属性，允许直接访问作为文档的文档元素的子节点。 |
| [DocumentURI](../../aspose.html.dom/document/documenturi/) { get; } | 文档的位置，如果未定义或文档是使用 DOMImplementation.createDocument. 创建的，则为 null |
| [Domain](../../aspose.html.dom.svg/svgdocument/domain/) { get; } | 为文档提供服务的服务器的域名，如果无法通过域名识别服务器，则为空字符串。 |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | 此节点的第一个子节点。如果没有这样的节点，则返回 null. |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild/) { get; } | 返回该元素的第一个子元素节点。如果此元素没有子元素，则为 null. |
| [Implementation](../../aspose.html.dom/document/implementation/) { get; } | 处理此文档的 DOMImplementation 对象。 |
| [InputEncoding](../../aspose.html.dom/document/inputencoding/) { get; } | 获取文档的编码。 |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | 此节点的最后一个子节点。如果没有这样的节点，则返回 null. |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild/) { get; } | 返回该元素的最后一个子元素节点。如果此元素没有子元素，则为 null. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | 返回此节点限定名称的本地部分。 对于除 ELEMENT_NODE 和 ATTRIBUTE_NODE 以外的任何类型的节点以及使用 DOM Level 1 方法创建的节点，例如 Document.createElement()，这始终为空。 |
| [Location](../../aspose.html.dom/document/location/) { get; } | 文档的位置。 |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | 此节点的名称空间 URI，如果未指定则为 null。 |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling/) { get; } | 返回此元素的下一个兄弟元素节点。如果此元素在文档树中没有此元素之后的元素兄弟节点，则为 null. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | 紧接此节点之后的节点。如果没有这样的节点，则返回 null. |
| override [NodeName](../../aspose.html.dom/document/nodename/) { get; } | 此节点的名称，取决于其类型。 |
| override [NodeType](../../aspose.html.dom/document/nodetype/) { get; } | 表示底层对象类型的代码。 |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | 这个节点的值，取决于它的类型。 |
| [Origin](../../aspose.html.dom/document/origin/) { get; } | 获取文档来源。 |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument/) { get; } | 获取所有者文件。 |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | 获取父级[`Element`](../../aspose.html.dom/element/)这个节点的. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | 此节点的父节点。除了 Attr、Document、DocumentFragment、Entity 和 Notation 之外的所有节点都可以有一个父节点。但是，如果一个节点刚刚被创建，还没有添加到树中，或者它已经从树中移除，这就是 null. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | 此节点的名称空间前缀，如果未指定则为 null。定义为null时，设置无效 |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling/) { get; } | 返回该元素的前一个兄弟元素节点。如果此元素在文档树中没有出现在该元素之前的元素兄弟节点，则为 null. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | 紧接此节点之前的节点。如果没有这样的节点，则返回 null. |
| [ReadyState](../../aspose.html.dom/document/readystate/) { get; } | 返回文档就绪状态。加载文档时的“加载”，完成解析但仍在加载子资源时的“交互”，加载后的“完成”. |
| [Referrer](../../aspose.html.dom.svg/svgdocument/referrer/) { get; } | 返回链接到该页面的页面的 URI。如果用户直接导航到页面（不是通过链接，而是通过书签等），则该值为空字符串。 |
| [RootElement](../../aspose.html.dom.svg/svgdocument/rootelement/) { get; } | 文档层次结构中的根“svg”。 |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking/) { get; set; } | 指定是否执行错误检查的属性。当设置为 false 时，实现可以自由地不测试通常在 DOM 操作上定义的每个可能的错误情况，并且在使用 Document.normalizeDocument() 时不会在 DOM 操作上引发任何 DOMException 或报告错误。如果出现错误，行为是未定义的。该属性默认为真。 |
| [StyleSheets](../../aspose.html.dom/document/stylesheets/) { get; } | 包含所有样式表的列表，这些样式表明确链接到或嵌入到文档中。对于 HTML 文档，这包括通过 HTML LINK 元素包含的外部样式表和内联 STYLE 元素。 |
| virtual [TextContent](../../aspose.html.dom/node/textcontent/) { get; set; } | 该属性返回该节点及其后代的文本内容。当它被定义为空时，设置它是无效的。在设置时，此节点可能具有的任何可能的子节点都将被删除，如果新字符串不为空或为空，则替换为包含此属性设置为的字符串的单个文本节点。 |
| [Title](../../aspose.html.dom.svg/svgdocument/title/) { get; } | 由“svg”根元素的“title”子元素指定的文档标题（即，这是标题... ) |
| [URL](../../aspose.html.dom.svg/svgdocument/url/) { get; } | 文档的完整 URI。 |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone/) { get; set; } | 作为 XML 声明的一部分，指定此文档是否独立的属性。未指定时为假。 |
| [XmlVersion](../../aspose.html.dom/document/xmlversion/) { get; set; } | 作为 XML 声明的一部分，指定此文档版本号的属性。如果没有声明并且此文档支持“XML”功能，则值为“1.0”。如果此文档不支持“XML”功能，则该值始终为空。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | 将节点 newChild 添加到该节点的子节点列表的末尾。如果 newChild 已经在树中，则首先将其删除。 |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空），也没有用户数据。 |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空），也没有用户数据。 |
| [CreateAttribute](../../aspose.html.dom/document/createattribute/)(string) | 创建给定名称的属性。 |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens/)(string, string) | 创建给定限定名称和命名空间 URI 的属性。 |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection/)(string) | 创建一个值为指定字符串的 CDATASection 节点。 |
| [CreateComment](../../aspose.html.dom/document/createcomment/)(string) | 在给定指定字符串的情况下创建 Comment 节点。 |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment/)() | 创建一个空的 DocumentFragment 对象。 |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype/)(string, string, string, string) | 创建一个 DocumentType 节点。 |
| [CreateElement](../../aspose.html.dom/document/createelement/)(string) | 创建指定类型的元素。请注意，返回的实例实现了 Element 接口，因此可以直接在返回的对象上指定属性。 |
| [CreateElementNS](../../aspose.html.dom/document/createelementns/)(string, string) | 创建给定限定名称和命名空间 URI 的元素。 |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference/)(string) | 创建一个 EntityReference 对象。另外，如果引用的实体是已知的，则EntityReference节点的子列表与对应的Entity节点的子列表相同。 |
| [CreateEvent](../../aspose.html.dom/document/createevent/)(string) | 创建一个[`Event`](../../aspose.html.dom.events/event/)实现支持的类型。 |
| [CreateExpression](../../aspose.html.dom/document/createexpression/)(string, IXPathNSResolver) | 使用已解析的命名空间创建已解析的 XPath 表达式。当表达式将在应用程序中重用时，这很有用 ，因为它可以 将表达式字符串编译为更有效的内部形式，并 预解析表达式中出现的所有名称空间前缀。 |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node) | 在以 the 指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long) | 在以 the 指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | 在以 the 指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver/)(Node) | 调整任何 DOM 节点以解析名称空间，以便可以相对于它在文档中出现的节点的上下文轻松地评估 XPath 表达式 。这个适配器像 DOM Level 3 方法一样工作 `查找命名空间URI`在调用 time lookupNamespaceURI 时使用节点层次结构中可用的当前信息从给定前缀解析 namespaceURI 的节点上，还正确解析隐式 xml 前缀. |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction/)(string, string) | 根据指定的名称和数据字符串创建 ProcessingInstruction 节点。 |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode/)(string) | 根据指定的字符串创建一个文本节点。 |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node) | 在以 the 指定节点为根的子树上创建一个新的 TreeWalker。 |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long) | 在以 the 指定节点为根的子树上创建一个新的 TreeWalker。 |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | 在以 the 指定节点为根的子树上创建一个新的 TreeWalker。 |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | 此方法允许将事件分派到实现事件模型中。 |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | 执行与释放、释放或重置非托管资源相关的应用程序定义的任务。 |
| [Evaluate](../../aspose.html.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | 计算 XPath 表达式字符串并在可能的情况下返回指定类型的结果。 |
| [GetElementById](../../aspose.html.dom/document/getelementbyid/)(string) | 返回具有给定值的 ID 属性的元素。如果不存在这样的元素，则返回 null。如果多个元素具有具有该值的 ID 属性，则返回未定义的内容。 |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname/)(string) | 返回一个实时 NodeList 对象，其中包含文档中所有元素，这些元素具有参数中指定的所有类。 http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname/)(string) | 按文档顺序返回所有元素的节点列表，这些元素具有给定的标签名称并包含在文档中。 |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens/)(string, string) | 按文档顺序返回具有给定本地名称和命名空间 URI 的所有元素的节点列表。 |
| [GetOverrideStyle](../../aspose.html.dom.svg/svgdocument/getoverridestyle/)(Element, string) | 此方法用于检索指定元素和指定伪元素的覆盖样式声明。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | 返回这个节点（如果它是一个元素）是否有任何属性 |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | 返回此节点是否有任何子节点。 |
| [ImportNode](../../aspose.html.dom/document/importnode/)(Node, bool) | 将节点从另一个文档导入到此文档，而不更改或删除原始文档中的源节点；此方法创建源节点的新副本。 |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | 在现有子节点 child 之前插入节点。如果 child 为 null，则在子节点列表的末尾插入节点。 如果 child 是 DocumentFragment 对象，则其所有子节点均按相同顺序插入到 child 之前。如果孩子已经在树中，则首先将其删除。 |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | 此方法检查指定的命名空间 URI 是否为默认命名空间。 |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | 测试两个节点是否相等。 此方法测试节点的相等性，而不是相同性（即两个节点是否是对同一对象的引用），可以使用 Node.isSameNode() 进行测试。所有相同的节点也将相等，但反过来可能不正确。 |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | 返回此节点是否与给定节点相同。 此方法提供了一种方法来确定实现返回的两个 Node 引用是否引用同一对象。当两个 Node 引用是对同一对象的引用时，即使通过代理，引用也可以完全互换使用，这样所有属性都具有相同的值，并且在任一引用上调用相同的 DOM 方法始终具有完全相同的效果。 |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | 查找与给定前缀关联的名称空间 URI，从该节点开始。 |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | 从该节点开始查找与给定名称空间 URI 关联的前缀。此方法忽略默认名称空间声明。 有关此方法使用的算法的详细信息，请参阅命名空间前缀查找。 |
| [Navigate](../../aspose.html.dom/document/navigate/)(RequestMessage) | 根据指定的请求对象加载文档，替换之前的内容。 |
| [Navigate](../../aspose.html.dom/document/navigate/)(string) | 将指定统一资源定位符 (URL) 处的文档加载到当前实例中，替换之前的内容。 |
| [Navigate](../../aspose.html.dom/document/navigate/)(Url) | 将指定统一资源定位符 (URL) 处的文档加载到当前实例中，替换之前的内容。 |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, string) | 从指定内容加载文档并使用baseUri 解析相对资源，替换之前的内容。 从流中的当前位置开始加载文档。 |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, Url) | 从指定内容加载文档并使用baseUri 解析相对资源，替换之前的内容。 从流中的当前位置开始加载文档。 |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, string) | 从指定内容加载文档并使用baseUri 解析相关资源，替换之前的内容. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, Url) | 从指定内容加载文档并使用baseUri 解析相关资源，替换之前的内容. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | 将所有文本节点在此节点下的子树的完整深度（包括属性节点）放入“正常”形式，其中只有结构（例如，元素、注释、处理指令、CDATA 部分和实体引用）将文本分隔开节点，即既没有相邻的文本节点，也没有空文本节点。这可用于确保文档的 DOM 视图与保存和重新加载时相同，并且在依赖于特定文档树结构的操作（例如 XPointer [XPointer] 查找）要执行时很有用使用。如果附加到 Node.ownerDocument 的 DOMConfiguration 对象的参数“normalize-characters”为 true，则此方法也会完全规范化 Text 节点的字符。 |
| [QuerySelector](../../aspose.html.dom/document/queryselector/)(string) | 返回文档中第一个匹配 selector 的元素 |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall/)(string) | 返回文档中所有元素的节点列表，匹配 selector |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | 从子列表中移除 oldChild 指示的子节点，并返回它。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)从中删除[`EventTarget`](../../aspose.html.dom/eventtarget/)当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)从中删除[`EventTarget`](../../aspose.html.dom/eventtarget/)当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)从中删除[`EventTarget`](../../aspose.html.dom/eventtarget/)当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |
| override [RenderTo](../../aspose.html.dom.svg/svgdocument/renderto/)(IDevice) | 该方法用于将当前文档的内容打印到指定设备上。 |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | 将子节点列表中的子节点oldChild替换为newChild，并返回oldChild节点。 如果 newChild 是一个 DocumentFragment 对象，则 oldChild 将替换为所有 DocumentFragment 子对象，它们以相同的顺序插入。如果 newChild 已经在树中，则首先将其删除。 |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save)(IOutputStorage) | 将文档内容和资源保存到输出存储。 |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_6)(string) | 将文档保存到指定的本地文件`小路`.本文档中使用的所有资源将保存在 到相邻文件夹中，其名称将构造为：output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_3)(Url) | 将文档保存到指定的本地文件`网址`.本文档中使用的所有资源将保存在 到相邻文件夹中，其名称将构造为：output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_1)(IOutputStorage, SVGSaveFormat) | 将文档内容和资源保存到输出存储。 |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_2)(IOutputStorage, SVGSaveOptions) | 将文档内容和资源保存到输出存储。 |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_7)(string, SVGSaveFormat) | 将文档保存到指定的本地文件`小路`.本文档中使用的所有资源将保存在 到相邻文件夹中，其名称将构造为：output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_8)(string, SVGSaveOptions) | 将文档保存到指定的本地文件`小路`.本文档中使用的所有资源将保存在 到相邻文件夹中，其名称将构造为：output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_4)(Url, SVGSaveFormat) | 将文档保存到指定的本地文件`网址`.本文档中使用的所有资源将保存在 到相邻文件夹中，其名称将构造为：output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_5)(Url, SVGSaveOptions) | 将文档保存到指定的本地文件`网址`.本文档中使用的所有资源将保存在 到相邻文件夹中，其名称将构造为：output_file_name + "_files". |
| override [ToString](../../aspose.html.dom/node/tostring/)() | 返回一个String代表这个实例. |
| [Write](../../aspose.html.dom/document/write/)(params string[]) | 将文本字符串写入由 open() 打开的文档流。请注意，该函数将生成一个不一定由 DTD 驱动的 document ，因此可能 在文档的上下文中生成无效结果。 |
| [WriteLn](../../aspose.html.dom/document/writeln/)(params string[]) | 将文本字符串后跟一个换行符写入由 open() 打开的 document 流。请注意，函数 will 生成的文档不一定由 DTD 驱动，因此 可能会在 the document 的上下文中生成无效结果 |

## 活动

| 姓名 | 描述 |
| --- | --- |
| event [OnAbort](../../aspose.html.dom/document/onabort/) | 获取或设置 OnAbort 事件的事件处理程序。 |
| event [OnBlur](../../aspose.html.dom/document/onblur/) | 获取或设置 OnBlur 事件的事件处理程序。 |
| event [OnCancel](../../aspose.html.dom/document/oncancel/) | 获取或设置 OnCancel 事件的事件处理程序。 |
| event [OnCanplay](../../aspose.html.dom/document/oncanplay/) | 获取或设置 OnCanplay 事件的事件处理程序。 |
| event [OnCanPlayThrough](../../aspose.html.dom/document/oncanplaythrough/) | 获取或设置 OnCanPlayThrough 事件的事件处理程序。 |
| event [OnChange](../../aspose.html.dom/document/onchange/) | 获取或设置 OnChange 事件的事件处理程序。 |
| event [OnClick](../../aspose.html.dom/document/onclick/) | 获取或设置 OnClick 事件的事件处理程序。 |
| event [OnCueChange](../../aspose.html.dom/document/oncuechange/) | 获取或设置 OnCueChange 事件的事件处理程序。 |
| event [OnDblClick](../../aspose.html.dom/document/ondblclick/) | 获取或设置 OnDblClick 事件的事件处理程序。 |
| event [OnDurationChange](../../aspose.html.dom/document/ondurationchange/) | 获取或设置 OnDurationChange 事件的事件处理程序。 |
| event [OnEmptied](../../aspose.html.dom/document/onemptied/) | 获取或设置 OnEmptied 事件的事件处理程序。 |
| event [OnEnded](../../aspose.html.dom/document/onended/) | 获取或设置 OnEnded 事件的事件处理程序。 |
| event [OnError](../../aspose.html.dom/document/onerror/) | 获取或设置 OnError 事件的事件处理程序。 |
| event [OnFocus](../../aspose.html.dom/document/onfocus/) | 获取或设置 OnFocus 事件的事件处理程序。 |
| event [OnInput](../../aspose.html.dom/document/oninput/) | 获取或设置 OnInput 事件的事件处理程序。 |
| event [OnInvalid](../../aspose.html.dom/document/oninvalid/) | 获取或设置 OnInvalid 事件的事件处理程序。 |
| event [OnKeyDown](../../aspose.html.dom/document/onkeydown/) | 获取或设置 OnKeyDown 事件的事件处理程序。 |
| event [OnKeyPress](../../aspose.html.dom/document/onkeypress/) | 获取或设置 OnKeyPress 事件的事件处理程序。 |
| event [OnKeyUp](../../aspose.html.dom/document/onkeyup/) | 获取或设置 OnKeyUp 事件的事件处理程序。 |
| event [OnLoad](../../aspose.html.dom/document/onload/) | 获取或设置 OnLoad 事件的事件处理程序。 |
| event [OnLoadedData](../../aspose.html.dom/document/onloadeddata/) | 获取或设置 OnLoadedData 事件的事件处理程序。 |
| event [OnLoadedMetadata](../../aspose.html.dom/document/onloadedmetadata/) | 获取或设置 OnLoadedMetadata 事件的事件处理程序。 |
| event [OnLoadStart](../../aspose.html.dom/document/onloadstart/) | 获取或设置 OnLoadStart 事件的事件处理程序。 |
| event [OnMouseDown](../../aspose.html.dom/document/onmousedown/) | 获取或设置 OnMouseDown 事件的事件处理程序。 |
| event [OnMouseEnter](../../aspose.html.dom/document/onmouseenter/) | 获取或设置 OnMouseEnter 事件的事件处理程序。 |
| event [OnMouseLeave](../../aspose.html.dom/document/onmouseleave/) | 获取或设置 OnMouseLeave 事件的事件处理程序。 |
| event [OnMouseMove](../../aspose.html.dom/document/onmousemove/) | 获取或设置 OnMouseMove 事件的事件处理程序。 |
| event [OnMouseOut](../../aspose.html.dom/document/onmouseout/) | 获取或设置 OnMouseOut 事件的事件处理程序。 |
| event [OnMouseOver](../../aspose.html.dom/document/onmouseover/) | 获取或设置 OnMouseOver 事件的事件处理程序。 |
| event [OnMouseUp](../../aspose.html.dom/document/onmouseup/) | 获取或设置 OnMouseUp 事件的事件处理程序。 |
| event [OnMouseWheel](../../aspose.html.dom/document/onmousewheel/) | 获取或设置 OnMouseWheel 事件的事件处理程序。 |
| event [OnPause](../../aspose.html.dom/document/onpause/) | 获取或设置 OnPause 事件的事件处理程序。 |
| event [OnPlay](../../aspose.html.dom/document/onplay/) | 获取或设置 OnPlay 事件的事件处理程序。 |
| event [OnPlaying](../../aspose.html.dom/document/onplaying/) | 获取或设置 OnPlaying 事件的事件处理程序。 |
| event [OnProgress](../../aspose.html.dom/document/onprogress/) | 获取或设置 OnProgress 事件的事件处理程序。 |
| event [OnRateChange](../../aspose.html.dom/document/onratechange/) | 获取或设置 OnRateChange 事件的事件处理程序。 |
| event [OnReadyStateChange](../../aspose.html.dom/document/onreadystatechange/) | 获取或设置 OnReadyStateChange 事件的事件处理程序。 |
| event [OnReset](../../aspose.html.dom/document/onreset/) | 获取或设置 OnReset 事件的事件处理程序。 |
| event [OnResize](../../aspose.html.dom/document/onresize/) | 获取或设置 OnResize 事件的事件处理程序。 |
| event [OnScroll](../../aspose.html.dom/document/onscroll/) | 获取或设置 OnScroll 事件的事件处理程序。 |
| event [OnSeeked](../../aspose.html.dom/document/onseeked/) | 获取或设置 OnSeeked 事件的事件处理程序。 |
| event [OnSeeking](../../aspose.html.dom/document/onseeking/) | 获取或设置 OnSeeking 事件的事件处理程序。 |
| event [OnSelect](../../aspose.html.dom/document/onselect/) | 获取或设置 OnSelect 事件的事件处理程序。 |
| event [OnShow](../../aspose.html.dom/document/onshow/) | 获取或设置 OnShow 事件的事件处理程序。 |
| event [OnStalled](../../aspose.html.dom/document/onstalled/) | 获取或设置 OnStalled 事件的事件处理程序。 |
| event [OnSubmit](../../aspose.html.dom/document/onsubmit/) | 获取或设置 OnSubmit 事件的事件处理程序。 |
| event [OnSuspend](../../aspose.html.dom/document/onsuspend/) | 获取或设置 OnSuspend 事件的事件处理程序。 |
| event [OnTimeUpdate](../../aspose.html.dom/document/ontimeupdate/) | 获取或设置 OnTimeUpdate 事件的事件处理程序。 |
| event [OnToggle](../../aspose.html.dom/document/ontoggle/) | 获取或设置 OnToggle 事件的事件处理程序。 |
| event [OnVolumeChange](../../aspose.html.dom/document/onvolumechange/) | 获取或设置 OnVolumeChange 事件的事件处理程序。 |
| event [OnWaiting](../../aspose.html.dom/document/onwaiting/) | 获取或设置 OnWaiting 事件的事件处理程序。 |

### 也可以看看

* class [Document](../../aspose.html.dom/document/)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent/)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss/)
* 命名空间 [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* 部件 [Aspose.HTML](../../)


