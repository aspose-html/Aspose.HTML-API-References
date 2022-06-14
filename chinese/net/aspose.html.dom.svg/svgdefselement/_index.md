---
title: SVGDefsElement
second_title: Aspose.HTML for .NET API 参考
description: SVGDefsElement 接口对应于 defs 元素
type: docs
weight: 2100
url: /zh/net/aspose.html.dom.svg/svgdefselement/
---
## SVGDefsElement class

SVGDefsElement 接口对应于 'defs' 元素。

```csharp
public class SVGDefsElement : SVGGraphicsElement
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Attributes](../../aspose.html.dom/element/attributes) { get; } | NamedNodeMap 包含此节点的属性（如果它是一个元素），否则为 null。 |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | 此节点的绝对基本 URI 或 null 如果实现无法获得绝对 URI。 |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount) { get; } | 返回当前作为该元素子节点的元素节点数。如果此元素没有节点类型为 1 的子节点，则为 0。 |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | 一个包含该节点所有子节点的 NodeList。如果没有子节点，这是一个不包含节点的 NodeList.. |
| [Children](../../aspose.html.dom/element/children) { get; } | 返回当前元素的子元素。 |
| [ClassList](../../aspose.html.dom/element/classlist) { get; } | 返回一个实时 DOMTokenList，其中包含从解析“类”属性接收到的令牌。 |
| [ClassName](../../aspose.html.dom.svg/svgelement/classname) { get; } | 对应于给定元素的属性“类”。 |
| [ClassName](../../aspose.html.dom/element/classname) { get; set; } | 元素的类属性。由于 与许多语言公开的“类”关键字冲突，此属性已被重命名。请参阅 HTML 4.01 中的类属性定义。 |
| [FarthestViewportElement](../../aspose.html.dom.svg/svggraphicselement/farthestviewportelement) { get; } | 最远的祖先'svg'元素。如果当前元素是最外层的 svg 元素，则为 Null。 |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | 此节点的第一个子节点。如果没有这样的节点，则返回 null。 |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild) { get; } | 返回此元素的第一个子元素节点。如果此元素没有子元素，则返回 null。 |
| [Id](../../aspose.html.dom.svg/svgelement/id) { get; set; } | 给定元素的“id”属性的值，如果“id”不存在，则为空字符串。 |
| [InnerHTML](../../aspose.html.dom/element/innerhtml) { get; set; } | 返回代表元素内容的 HTML 或 XML 片段。 可以设置，用从给定字符串解析的节点替换元素的内容。 |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | 该节点的最后一个子节点。如果没有这样的节点，则返回 null。 |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild) { get; } | 返回此元素的最后一个子元素节点。如果此元素没有子元素，则返回 null。 |
| override [LocalName](../../aspose.html.dom/element/localname) { get; } | 返回此节点的限定名称的本地部分。 对于除 ELEMENT_NODE 和 ATTRIBUTE_NODE 之外的任何类型的节点以及使用 DOM 级别 1 方法（例如 Document.createElement()）创建的节点，这始终为 null。 |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri) { get; } | 此节点的命名空间 URI，如果未指定，则为 null。 |
| [NearestViewportElement](../../aspose.html.dom.svg/svggraphicselement/nearestviewportelement) { get; } | 建立当前视口的元素。通常，最近的祖先 'svg' 元素。如果当前元素是最外层的 svg 元素，则为 Null。 |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling) { get; } | 返回此元素的下一个兄弟元素节点。如果此元素在文档树中没有位于该元素之后的元素兄弟节点，则返回 null。 |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | 紧跟该节点的节点。如果没有这样的节点，则返回 null。 |
| override [NodeName](../../aspose.html.dom/element/nodename) { get; } | 此节点的名称，取决于其类型。 |
| override [NodeType](../../aspose.html.dom/element/nodetype) { get; } | 表示底层对象类型的代码。 |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | 此节点的值，取决于其类型。 |
| [OuterHTML](../../aspose.html.dom/element/outerhtml) { get; set; } | 返回表示元素及其内容的 HTML 或 XML 片段。 可以设置，用从给定字符串解析的节点替换元素。 |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | 与此节点关联的 Document 对象。这也是用于创建新节点的 Document 对象。当此节点是尚未与任何 Document 一起使用的 Document 或 DocumentType 时，此节点为 null。 |
| [OwnerSVGElement](../../aspose.html.dom.svg/svgelement/ownersvgelement) { get; } | 最近的祖先'svg'元素。如果给定元素是最外层的 svg 元素，则为 Null。 |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | 获取此节点的父[`Element`](../../aspose.html.dom/element)。 |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | 该节点的父节点。除 Attr、Document、DocumentFragment、Entity 和 Notation 之外的所有节点都可以有父节点。但是，如果一个节点刚刚创建但尚未添加到树中，或者它已从树中删除，则为 null。 |
| override [Prefix](../../aspose.html.dom/element/prefix) { get; } | 此节点的命名空间前缀，如果未指定，则为 null。定义为null时，设置无效 |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling) { get; } | 返回此元素的前一个兄弟元素节点。如果此元素在文档树中没有位于该元素之前的元素兄弟节点，则返回 null。 |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | 紧接在此节点之前的节点。如果没有这样的节点，则返回 null。 |
| [RequiredExtensions](../../aspose.html.dom.svg/svggraphicselement/requiredextensions) { get; } | 对应于给定元素上的属性“requiredExtensions”。 |
| [RequiredFeatures](../../aspose.html.dom.svg/svggraphicselement/requiredfeatures) { get; } | 对应于给定元素上的属性“requiredFeatures”。 |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo) { get; } | 与此元素关联的类型信息。 |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot) { get; } | 返回存储在此元素上的 shadowRoot，如果它已关闭，则返回 null。 |
| [Style](../../aspose.html.dom.svg/svgelement/style) { get; } | 对应于给定元素的属性“样式”。如果用户代理不支持 CSS 样式，则此属性必须始终具有 null 值。 |
| [SystemLanguage](../../aspose.html.dom.svg/svggraphicselement/systemlanguage) { get; } | 对应于给定元素上的属性“systemLanguage”。 |
| [TagName](../../aspose.html.dom/element/tagname) { get; } | 元素的名称。 |
| override [TextContent](../../aspose.html.dom/element/textcontent) { get; set; } | 此属性返回此节点及其后代的文本内容。定义为null时，设置无效。设置时，此节点可能具有的任何可能的子节点都将被删除，如果新字符串不为空或 null，则替换为包含此属性设置为的字符串的单个 Text 节点。 |
| [Transform](../../aspose.html.dom.svg/svggraphicselement/transform) { get; } | 对应于给定元素的属性“transform”。 |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement) { get; } | 建立当前视口的元素。通常，最近的祖先 'svg' 元素。如果给定元素是最外层的 svg 元素，则为 Null。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | 将节点 newChild 添加到该节点的子节点列表的末尾。如果 newChild 已经在树中，则首先将其移除。 |
| [AttachShadow](../../aspose.html.dom/element/attachshadow)(ShadowRootMode) | 创建影子根并将其附加到当前元素。 |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空）并且没有用户数据。 |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空）并且没有用户数据。 |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | 此方法允许将事件分派到实现事件模型中。 |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
| [GetAttribute](../../aspose.html.dom/element/getattribute)(string) | 按名称检索属性值。 |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode)(string) | 按名称检索属性节点。 |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens)(string, string) | 通过本地名称和命名空间 URI 检索 Attr 节点。 |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens)(string, string) | 通过本地名称和命名空间 URI 检索属性值。 |
| [GetBBox](../../aspose.html.dom.svg/svggraphicselement/getbbox)() | 返回当前用户空间中的紧密边界框（即，在应用 'transform' 属性后，如果有的话）在所有包含的图形元素的几何上，不包括描边、剪裁、遮罩和滤镜效果）。请注意，getBBox 必须在调用该方法时返回实际的边界框，即使元素尚未被渲染也是如此。 |
| [GetCTM](../../aspose.html.dom.svg/svggraphicselement/getctm)() | 返回从当前用户单元（即，在应用'transform' 属性后，如果有的话）到最近ViewportElement 的视口坐标系的变换矩阵。 |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname)(string) | 返回一个活动的 NodeList 对象，该对象包含文档中具有参数中指定的所有类的所有元素。 http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname)(string) | 按文档顺序返回具有给定标签名称的所有后代元素的 NodeList。 |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens)(string, string) | 按文档顺序返回具有给定本地名称和命名空间 URI 的所有后代元素的 NodeList。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | 此方法用于检索 ECMAScript 对象Type。 |
| [GetScreenCTM](../../aspose.html.dom.svg/svggraphicselement/getscreenctm)() | 从当前用户单元（即，应用'transform'属性后，如果有的话）返回转换矩阵到父用户代理的“像素”通知。对于显示设备，理想情况下这表示物理屏幕像素。对于不知道物理像素大小的其他设备或环境，可以使用类似于 CSS2 定义的“像素”的算法。请注意，如果此元素未挂接到文档树，则返回 null。这种方法更贴切地命名为 getClientCTM，但由于历史原因保留了名称 getScreenCTM。 |
| [HasAttribute](../../aspose.html.dom/element/hasattribute)(string) | 当在此元素上指定具有给定名称的属性或具有默认值时返回 true，否则返回 false。 |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens)(string, string) | 如果在此元素上指定了具有给定本地名称和命名空间 URI 的属性或具有默认值，则返回 true，否则返回 false。 |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes)() | 返回此节点（如果是元素）是否有任何属性 |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | 返回此节点是否有任何子节点。 |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | 在现有子节点 child 之前插入节点。如果 child 为 null，则在子列表的末尾插入节点。 如果 child 是 DocumentFragment 对象，则它的所有孩子都以相同的顺序插入到 child 之前。如果孩子已经在树中，则首先将其移除。 |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | 此方法检查指定的 namespaceURI 是否为默认命名空间。 |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | 测试两个节点是否相等。 此方法测试节点的相等性，而不是相同性（即两个节点是否是对同一对象的引用），可以使用 Node.isSameNode() 测试。所有相同的节点也将相等，尽管反过来可能不正确。 |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | 返回此节点是否与给定节点相同。 该方法提供了一种方法来确定实现返回的两个 Node 引用是否引用同一个对象。当两个 Node 引用是对同一个对象的引用时，即使通过代理，这些引用也可以完全互换使用，这样所有属性都具有相同的值，并且在任一引用上调用相同的 DOM 方法总是具有完全相同的效果。 |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | 从该节点开始查找与给定前缀关联的命名空间 URI。 |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | 从该节点开始查找与给定命名空间 URI 关联的前缀。此方法忽略默认命名空间声明。 有关此方法使用的算法的详细信息，请参阅命名空间前缀查找。 |
| [Normalize](../../aspose.html.dom/node/normalize)() | 将所有位于该节点下的子树全深度的文本节点，包括属性节点，放入“正常”形式，其中只有结构（例如，元素，注释、处理指令、CDATA 部分和实体引用）分隔 Text 节点，即既没有相邻的 Text 节点，也没有空的 Text 节点。这可用于确保文档的 DOM 视图与保存和重新加载时相同，并且在依赖于特定文档树结构的操作（例如 XPointer [XPointer] 查找）时很有用使用。如果附加到 Node.ownerDocument 的 DOMConfiguration 对象的参数“normalize-characters”为 true，则此方法还将完全规范化 Text 节点的字符。 |
| [QuerySelector](../../aspose.html.dom/element/queryselector)(string) | 返回文档中与选择器匹配的第一个元素 |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall)(string) | 返回文档中与选择器匹配的所有元素的节点列表 |
| [Remove](../../aspose.html.dom/element/remove)() | 删除此实例。 |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute)(string) | 按名称删除属性。 |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode)(Attr) | 移除指定的属性节点。 |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens)(string, string) | 通过本地名称和命名空间 URI 删除属性。 |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | 从子节点列表中移除 oldChild 指示的子节点，并返回它。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | 此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../../aspose.html.dom.events/ieventlistener)从[`EventTarget`](../../aspose.html.dom/eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | 此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../../aspose.html.dom.events/ieventlistener)从[`EventTarget`](../../aspose.html.dom/eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | 此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../../aspose.html.dom.events/ieventlistener)从[`EventTarget`](../../aspose.html.dom/eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。 |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | 将子节点列表中的子节点 oldChild 替换为 newChild，并返回 oldChild 节点。 如果 newChild 是 DocumentFragment 对象，则 oldChild 将替换为所有 DocumentFragment 子代，它们以相同的顺序插入。如果 newChild 已经在树中，则首先将其移除。 |
| [SetAttribute](../../aspose.html.dom/element/setattribute)(string, string) | 添加一个新属性。如果元素中已存在具有该名称的属性，则其值将更改为值参数 |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode)(Attr) | 添加一个新的属性节点。如果元素中已经存在具有该名称 (nodeName) 的属性，则将其替换为新属性。 |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens)(Attr) | 添加一个新属性。如果元素中已经存在具有该本地名称和该名称空间 URI 的属性，则将其替换为新属性。 |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens)(string, string, string) | 添加一个新属性。如果元素上已经存在具有相同本地名称和命名空间 URI 的属性，则将其前缀更改为qualifiedName 的前缀部分，并将其值更改为值参数。 |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute)(string, bool) | 如果参数 isId 为真，则该方法将指定的属性声明为用户确定的 ID 属性。 |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode)(Attr, bool) | 如果参数 isId 为真，则该方法将指定的属性声明为用户确定的 ID 属性。 |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens)(string, string, bool) | 如果参数 isId 为真，则该方法将指定的属性声明为用户确定的 ID 属性。 |
| override [ToString](../../aspose.html.dom/node/tostring)() | 返回代表此实例的String。 |

### 也可以看看

* class [SVGGraphicsElement](../svggraphicselement)
* 命名空间 [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg)
* 部件 [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
