---
title: Document
second_title: Aspose.HTML for .NET API 参考
description: Document 代表整个 HTMLXML 或 SVG 文档从概念上讲它是文档树的根提供对文档数据的主要访问
type: docs
weight: 770
url: /zh/net/aspose.html.dom/document/
---
## Document class

Document 代表整个 HTML、XML 或 SVG 文档。从概念上讲，它是文档树的根，提供对文档数据的主要访问。

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes) { get; } | NamedNodeMap 包含此节点的属性（如果它是一个元素），否则为 null。 |
| override [BaseURI](../../aspose.html.dom/document/baseuri) { get; } | 此节点的绝对基本 URI 或 null 如果实现无法获得绝对 URI。 |
| [CharacterSet](../../aspose.html.dom/document/characterset) { get; } | 获取文档的编码。 |
| [Charset](../../aspose.html.dom/document/charset) { get; } | 获取文档的编码。 |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount) { get; } | 返回当前作为该元素子节点的元素节点数。如果此元素没有节点类型为 1 的子节点，则为 0。 |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | 一个包含该节点所有子节点的 NodeList。如果没有子节点，这是一个不包含节点的 NodeList.. |
| [Children](../../aspose.html.dom/document/children) { get; } | 返回子元素。 |
| [ContentType](../../aspose.html.dom/document/contenttype) { get; } | 获取文档内容类型。 |
| [Context](../../aspose.html.dom/document/context) { get; } | 获取当前浏览上下文。 |
| [DefaultView](../../aspose.html.dom/document/defaultview) { get; } | Document 接口的 defaultView IDL 属性，在获取时 必须返回此 Document 的浏览上下文的 WindowProxy 对象 如果此 Document 具有关联的浏览上下文，否则为 null。 |
| [Doctype](../../aspose.html.dom/document/doctype) { get; } | 与此文档相关的文档类型声明。 |
| [DocumentElement](../../aspose.html.dom/document/documentelement) { get; } | 这是一个方便属性，允许直接访问作为文档的文档元素的子节点。 |
| [DocumentURI](../../aspose.html.dom/document/documenturi) { get; } | 文档的位置，如果未定义或文档是使用 DOMImplementation.createDocument 创建的，则为 null。 |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | 此节点的第一个子节点。如果没有这样的节点，则返回 null。 |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild) { get; } | 返回此元素的第一个子元素节点。如果此元素没有子元素，则返回 null。 |
| [Implementation](../../aspose.html.dom/document/implementation) { get; } | 处理此文档的DOMImplementation 对象。 |
| [InputEncoding](../../aspose.html.dom/document/inputencoding) { get; } | 获取文档的编码。 |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | 该节点的最后一个子节点。如果没有这样的节点，则返回 null。 |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild) { get; } | 返回此元素的最后一个子元素节点。如果此元素没有子元素，则返回 null。 |
| virtual [LocalName](../../aspose.html.dom/node/localname) { get; } | 返回此节点的限定名称的本地部分。 对于除 ELEMENT_NODE 和 ATTRIBUTE_NODE 之外的任何类型的节点以及使用 DOM 级别 1 方法（例如 Document.createElement()）创建的节点，这始终为 null。 |
| [Location](../../aspose.html.dom/document/location) { get; } | 文档的位置。 |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri) { get; } | 此节点的命名空间 URI，如果未指定，则为 null。 |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling) { get; } | 返回此元素的下一个兄弟元素节点。如果此元素在文档树中没有位于该元素之后的元素兄弟节点，则返回 null。 |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | 紧跟该节点的节点。如果没有这样的节点，则返回 null。 |
| override [NodeName](../../aspose.html.dom/document/nodename) { get; } | 此节点的名称，取决于其类型。 |
| override [NodeType](../../aspose.html.dom/document/nodetype) { get; } | 表示底层对象类型的代码。 |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | 此节点的值，取决于其类型。 |
| [Origin](../../aspose.html.dom/document/origin) { get; } | 获取文档来源。 |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument) { get; } | 获取所有者文档。 |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | 获取此节点的父[`Element`](../element)。 |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | 该节点的父节点。除 Attr、Document、DocumentFragment、Entity 和 Notation 之外的所有节点都可以有父节点。但是，如果一个节点刚刚创建但尚未添加到树中，或者它已从树中删除，则为 null。 |
| virtual [Prefix](../../aspose.html.dom/node/prefix) { get; set; } | 此节点的命名空间前缀，如果未指定，则为 null。当定义为null时，设置没有效果 |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling) { get; } | 返回此元素的前一个兄弟元素节点。如果此元素在文档树中没有位于该元素之前的元素兄弟节点，则返回 null。 |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | 紧接在此节点之前的节点。如果没有这样的节点，则返回 null。 |
| [ReadyState](../../aspose.html.dom/document/readystate) { get; } | 返回文档就绪状态。文档加载时的“加载”，完成解析但仍在加载子资源后的“交互”，以及加载后的“完成”。 |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking) { get; set; } | 指定是否强制执行错误检查的属性。当设置为 false 时，实现可以自由地不测试通常在 DOM 操作上定义的每个可能的错误情况，并且在使用 Document.normalizeDocument() 时不会在 DOM 操作上引发任何 DOMException 或报告错误。如果出现错误，则行为未定义。此属性默认为 true。 |
| [StyleSheets](../../aspose.html.dom/document/stylesheets) { get; } | 包含所有显式链接或嵌入文档的样式表的列表。对于 HTML 文档，这包括通过 HTML LINK 元素包含的外部样式表和内联 STYLE 元素。 |
| virtual [TextContent](../../aspose.html.dom/node/textcontent) { get; set; } | 此属性返回此节点及其后代的文本内容。定义为null时，设置无效。设置时，此节点可能具有的任何可能的子节点都将被删除，如果新字符串不为空或 null，则替换为包含此属性设置为的字符串的单个 Text 节点。 |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone) { get; set; } | 作为 XML 声明的一部分，指定此文档是否为独立的属性。当未指定时，这是错误的。 |
| [XmlVersion](../../aspose.html.dom/document/xmlversion) { get; set; } | 作为 XML 声明的一部分，指定此文档的版本号的属性。如果没有声明并且该文档支持“XML”特性，则值为“1.0”。如果此文档不支持“XML”功能，则该值始终为空。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | 将节点 newChild 添加到该节点的子节点列表的末尾。如果 newChild 已经在树中，则首先将其移除。 |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空）并且没有用户数据。 |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空）并且没有用户数据。 |
| [CreateAttribute](../../aspose.html.dom/document/createattribute)(string) | 创建给定名称的 Attr。 |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens)(string, string) | 创建给定限定名称和命名空间 URI 的属性。 |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection)(string) | 创建一个值为指定字符串的 CDATASection 节点。 |
| [CreateComment](../../aspose.html.dom/document/createcomment)(string) | 在给定指定字符串的情况下创建一个评论节点。 |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment)() | 创建一个空的 DocumentFragment 对象。 |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype)(string, string, string, string) | 创建一个 DocumentType 节点。 |
| [CreateElement](../../aspose.html.dom/document/createelement)(string) | 创建指定类型的元素。请注意，返回的实例实现了 Element 接口，因此可以直接在返回的对象上指定属性。 |
| [CreateElementNS](../../aspose.html.dom/document/createelementns)(string, string) | 创建给定限定名称和命名空间 URI 的元素。 |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference)(string) | 创建一个 EntityReference 对象。另外，如果被引用实体已知，则EntityReference节点的子列表与对应Entity节点的子列表相同。 |
| [CreateEvent](../../aspose.html.dom/document/createevent)(string) | 创建实现支持的类型的[`Event`](../../aspose.html.dom.events/event)。 |
| [CreateExpression](../../aspose.html.dom/document/createexpression)(string, IXPathNSResolver) | 使用已解析的命名空间创建已解析的 XPath 表达式。这在应用程序中重用表达式时很有用 因为它可以将 编译为更有效的内部形式和 预解析表达式中出现的所有命名空间前缀。 |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator#createnodeiterator)(Node) | 在以 指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator#createnodeiterator_1)(Node, long) | 在以 指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator#createnodeiterator_2)(Node, long, INodeFilter) | 在以 指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver)(Node) | 调整任何 DOM 节点以解析名称空间，以便可以轻松评估 XPath 表达式 相对于它出现在文档。这个适配器工作 就像 DOM Level 3 方法` lookupNamespaceURI` 在节点上从给定前缀解析 namespaceURI 在调用 lookupNamespaceURI 时使用节点层次结构中可用的当前信息，也正确解析隐式 xml 前缀。 |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction)(string, string) | 在给定指定名称和数据字符串的情况下创建一个 ProcessingInstruction 节点。 |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode)(string) | 在给定指定字符串的情况下创建一个文本节点。 |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker#createtreewalker)(Node) | 在以 指定节点为根的子树上创建一个新的 TreeWalker。 |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker#createtreewalker_1)(Node, long) | 在以 指定节点为根的子树上创建一个新的 TreeWalker。 |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker#createtreewalker_2)(Node, long, INodeFilter) | 在以 指定节点为根的子树上创建一个新的 TreeWalker。 |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | 此方法允许将事件分派到实现事件模型中。 |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
| [Evaluate](../../aspose.html.dom/document/evaluate)(string, Node, IXPathNSResolver, XPathResultType, object) | 计算一个 XPath 表达式字符串，如果可能，返回指定类型的结果。 |
| [GetElementById](../../aspose.html.dom/document/getelementbyid)(string) | 返回具有给定值的 ID 属性的元素。如果不存在这样的元素，则返回 null。如果多个元素具有具有该值的 ID 属性，则返回的内容是未定义的。 |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname)(string) | 返回一个活动的 NodeList 对象，该对象包含文档中具有参数中指定的所有类的所有元素。 http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname)(string) | 以文档顺序返回具有给定标签名称并包含在文档中的所有元素的 NodeList。 |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens)(string, string) | 按文档顺序返回具有给定本地名称和命名空间 URI 的所有元素的 NodeList。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | 此方法用于检索 ECMAScript 对象Type。 |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes)() | 返回此节点（如果是元素）是否有任何属性 |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | 返回此节点是否有任何子节点。 |
| [ImportNode](../../aspose.html.dom/document/importnode)(Node, bool) | 将另一个文档中的节点导入到此文档中，而不更改或删除原始文档中的源节点；此方法创建源节点的新副本。 |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | 在现有子节点 child 之前插入节点。如果 child 为 null，则在子列表的末尾插入节点。 如果 child 是 DocumentFragment 对象，则它的所有孩子都以相同的顺序插入到 child 之前。如果孩子已经在树中，则首先将其移除。 |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | 此方法检查指定的 namespaceURI 是否为默认命名空间。 |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | 测试两个节点是否相等。 此方法测试节点的相等性，而不是相同性（即两个节点是否是对同一对象的引用），可以使用 Node.isSameNode() 测试。所有相同的节点也将相等，尽管反过来可能不正确。 |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | 返回此节点是否与给定节点相同。 该方法提供了一种方法来确定实现返回的两个 Node 引用是否引用同一个对象。当两个 Node 引用是对同一个对象的引用时，即使通过代理，这些引用也可以完全互换使用，这样所有属性都具有相同的值，并且在任一引用上调用相同的 DOM 方法总是具有完全相同的效果。 |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | 从该节点开始查找与给定前缀关联的命名空间 URI。 |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | 从该节点开始查找与给定命名空间 URI 关联的前缀。此方法忽略默认命名空间声明。 有关此方法使用的算法的详细信息，请参阅命名空间前缀查找。 |
| [Navigate](../../aspose.html.dom/document/navigate#navigate)(RequestMessage) | 根据指定的请求对象加载文档，替换之前的内容。 |
| [Navigate](../../aspose.html.dom/document/navigate#navigate_4)(string) | 将指定统一资源定位符 (URL) 处的文档加载到当前实例中，替换之前的内容。 |
| [Navigate](../../aspose.html.dom/document/navigate#navigate_1)(Url) | 将指定统一资源定位符 (URL) 处的文档加载到当前实例中，替换之前的内容。 |
| [Navigate](../../aspose.html.dom/document/navigate#navigate_3)(Stream, string) | 从指定内容加载文档并使用 baseUri 解析相关资源，替换之前的内容。 文档加载从流中的当前位置开始。 |
| [Navigate](../../aspose.html.dom/document/navigate#navigate_2)(Stream, Url) | 从指定内容加载文档并使用 baseUri 解析相关资源，替换之前的内容。 文档加载从流中的当前位置开始。 |
| [Navigate](../../aspose.html.dom/document/navigate#navigate_6)(string, string) | 从指定内容加载文档并使用 baseUri 解析相关资源，替换之前的内容。 |
| [Navigate](../../aspose.html.dom/document/navigate#navigate_5)(string, Url) | 从指定内容加载文档并使用 baseUri 解析相关资源，替换之前的内容。 |
| [Normalize](../../aspose.html.dom/node/normalize)() | 将所有位于该节点下的子树全深度的文本节点，包括属性节点，放入“正常”形式，其中只有结构（例如，元素，注释、处理指令、CDATA 部分和实体引用）分隔 Text 节点，即既没有相邻的 Text 节点，也没有空的 Text 节点。这可用于确保文档的 DOM 视图与保存和重新加载时相同，并且在依赖于特定文档树结构的操作（例如 XPointer [XPointer] 查找）时很有用使用。如果附加到 Node.ownerDocument 的 DOMConfiguration 对象的参数“normalize-characters”为 true，则此方法还将完全规范化 Text 节点的字符。 |
| [QuerySelector](../../aspose.html.dom/document/queryselector)(string) | 返回文档中与选择器匹配的第一个元素 |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall)(string) | 返回文档中与选择器匹配的所有元素的节点列表 |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | 从子节点列表中移除 oldChild 指示的子节点，并返回它。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | 此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../../aspose.html.dom.events/ieventlistener)从[`EventTarget`](../eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | 此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../../aspose.html.dom.events/ieventlistener)从[`EventTarget`](../eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | 此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../../aspose.html.dom.events/ieventlistener)从[`EventTarget`](../eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。 |
| virtual [RenderTo](../../aspose.html.dom/document/renderto)(IDevice) | 该方法用于将当前文档的内容渲染到指定的图形设备上。 |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | 将子节点列表中的子节点 oldChild 替换为 newChild，并返回 oldChild 节点。 如果 newChild 是 DocumentFragment 对象，则 oldChild 将替换为所有 DocumentFragment 子代，它们以相同的顺序插入。如果 newChild 已经在树中，则首先将其移除。 |
| override [ToString](../../aspose.html.dom/node/tostring)() | 返回代表此实例的String。 |
| [Write](../../aspose.html.dom/document/write)(params string[]) | 将文本字符串写入由 open() 打开的文档流。请注意，该函数将生成一个文档 不一定由 DTD 驱动，因此可能是 在文档上下文中产生无效结果。 |
| [WriteLn](../../aspose.html.dom/document/writeln)(params string[]) | 将后跟换行符的文本字符串写入由 open() 打开的文档 流。请注意，该函数将 生成不一定由 DTD 驱动的文档，并且 因此可能会在 的上下文中生成无效结果document |

### 也可以看看

* class [Node](../node)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent)
* interface [IDocumentStyle](../../aspose.html.dom.css/idocumentstyle)
* interface [IDocumentTraversal](../../aspose.html.dom.traversal/idocumenttraversal)
* interface [IGlobalEventHandlers](../iglobaleventhandlers)
* interface [INonElementParentNode](../inonelementparentnode)
* interface [IParentNode](../iparentnode)
* interface [IXPathEvaluator](../../aspose.html.dom.xpath/ixpathevaluator)
* 命名空间 [Aspose.Html.Dom](../../aspose.html.dom)
* 部件 [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->