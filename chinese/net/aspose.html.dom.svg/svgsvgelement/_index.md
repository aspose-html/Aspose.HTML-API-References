---
title: Class SVGSVGElement
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Svg.SVGSVGElement 班级. 一个关键的接口定义是 SVGSVGElement 接口它是对应于svg元素的接口该接口包含各种杂项常用的实用方法例如矩阵运算和控制视觉渲染设备重绘时间的能力
type: docs
weight: 2260
url: /zh/net/aspose.html.dom.svg/svgsvgelement/
---
## SVGSVGElement class

一个关键的接口定义是 SVGSVGElement 接口，它是对应于“svg”元素的接口。该接口包含各种杂项常用的实用方法，例如矩阵运算和控制视觉渲染设备重绘时间的能力。

```csharp
public class SVGSVGElement : SVGGraphicsElement, IDocumentEvent, ISVGFitToViewBox, ISVGZoomAndPan
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Attributes](../../aspose.html.dom/element/attributes/) { get; } | 包含此节点属性的 NamedNodeMap（如果它是一个元素）或 null 否则。 |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | 此节点的绝对基础 URI，如果实现无法获得绝对 URI，则为 null。 |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount/) { get; } | 返回作为该元素子元素的元素节点的当前数量。如果此元素没有节点类型为 1. 的子节点，则为 0 |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | 包含此节点的所有子节点的 NodeList。如果没有孩子，这是一个不包含节点的 NodeList.. |
| [Children](../../aspose.html.dom/element/children/) { get; } | 返回当前元素的子元素。 |
| [ClassList](../../aspose.html.dom/element/classlist/) { get; } | 返回一个实时 DOMTokenList，其中包含从解析“类”属性中收到的令牌。 |
| [ClassName](../../aspose.html.dom.svg/svgelement/classname/) { get; } | 对应于给定元素上的属性“类”。 |
| [ClassName](../../aspose.html.dom/element/classname/) { get; set; } | 元素的类属性。此属性已重命名为 due 以与许多语言公开的“class”关键字冲突。请参阅 HTML 4.01. 中的类属性定义 |
| [CurrentScale](../../aspose.html.dom.svg/svgsvgelement/currentscale/) { get; set; } | 在最外层的 svg 元素上，此属性指示当前相对于初始视图的比例因子，以考虑用户放大和平移操作，如放大和平移中所述。 DOM 属性 currentScale 和 currentTranslate 相当于 2x3 矩阵 [abcdef] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]。如果启用“放大”（即 zoomAndPan="magnify"），那么效果就像在 SVG 文档片段的最外层（即最外层 svg 元素之外）放置了一个额外的转换。 访问时不是最外层 svg 元素的“svg”元素，未定义此属性的行为。 |
| [CurrentTranslate](../../aspose.html.dom.svg/svgsvgelement/currenttranslate/) { get; } | 在最外层的 svg 元素上，考虑用户“放大”的相应转换因子。 在不是最外层 svg 元素的“svg”元素上访问时，未定义此属性具有什么行为。 |
| [FarthestViewportElement](../../aspose.html.dom.svg/svggraphicselement/farthestviewportelement/) { get; } | 最远的祖先“svg”元素。如果当前元素是最外层的 svg 元素，则为空。 |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | 此节点的第一个子节点。如果没有这样的节点，则返回 null. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | 返回该元素的第一个子元素节点。如果此元素没有子元素，则为 null. |
| [Height](../../aspose.html.dom.svg/svgsvgelement/height/) { get; } | 对应于给定“svg”元素上的属性“height”。 |
| [Id](../../aspose.html.dom.svg/svgelement/id/) { get; set; } | 给定元素上“id”属性的值，如果“id”不存在则为空字符串。 |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | 返回表示元素内容的 HTML 或 XML 片段。 可以设置，用从给定字符串解析的节点替换元素的内容。 |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | 此节点的最后一个子节点。如果没有这样的节点，则返回 null. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | 返回该元素的最后一个子元素节点。如果此元素没有子元素，则为 null. |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | 返回此节点限定名称的本地部分。 对于除 ELEMENT_NODE 和 ATTRIBUTE_NODE 以外的任何类型的节点以及使用 DOM Level 1 方法创建的节点，例如 Document.createElement()，这始终为空。 |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | 此节点的名称空间 URI，如果未指定则为 null。 |
| [NearestViewportElement](../../aspose.html.dom.svg/svggraphicselement/nearestviewportelement/) { get; } | 建立当前视口的元素。通常，最近的祖先“svg”元素。如果当前元素是最外层的 svg 元素，则为空。 |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | 返回此元素的下一个兄弟元素节点。如果此元素在文档树中没有此元素之后的元素兄弟节点，则为 null. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | 紧接此节点之后的节点。如果没有这样的节点，则返回 null. |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | 此节点的名称，取决于其类型。 |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | 表示底层对象类型的代码。 |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | 这个节点的值，取决于它的类型。 |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | 返回表示元素及其内容的 HTML 或 XML 片段。 可以设置，用从给定字符串解析的节点替换元素。 |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | 与此节点关联的文档对象。这也是用于创建新节点的文档对象。当此节点是尚未与任何文档一起使用的文档或文档类型时，这是 null. |
| [OwnerSVGElement](../../aspose.html.dom.svg/svgelement/ownersvgelement/) { get; } | 最近的祖先“svg”元素。如果给定元素是最外层的 svg 元素，则为空。 |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | 获取父级[`Element`](../../aspose.html.dom/element/)这个节点的. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | 此节点的父节点。除了 Attr、Document、DocumentFragment、Entity 和 Notation 之外的所有节点都可以有一个父节点。但是，如果一个节点刚刚被创建，还没有添加到树中，或者它已经从树中移除，这就是 null. |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | 此节点的名称空间前缀，如果未指定则为 null。定义为null时，设置无效 |
| [PreserveAspectRatio](../../aspose.html.dom.svg/svgsvgelement/preserveaspectratio/) { get; } | 对应于给定元素上的属性“preserveAspectRatio”。 |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | 返回该元素的前一个兄弟元素节点。如果此元素在文档树中没有出现在该元素之前的元素兄弟节点，则为 null. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | 紧接此节点之前的节点。如果没有这样的节点，则返回 null. |
| [RequiredExtensions](../../aspose.html.dom.svg/svggraphicselement/requiredextensions/) { get; } | 对应于给定元素上的属性“requiredExtensions”。 |
| [RequiredFeatures](../../aspose.html.dom.svg/svggraphicselement/requiredfeatures/) { get; } | 对应于给定元素上的属性“requiredFeatures”。 |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo/) { get; } | 与此元素关联的类型信息。 |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | 返回存储在此元素上的 shadowRoot，如果关闭则返回 null。 |
| [Style](../../aspose.html.dom.svg/svgelement/style/) { get; } | 对应于给定元素上的属性“样式”。如果用户代理不支持 CSS 样式，则此属性的值必须始终为 null. |
| [SystemLanguage](../../aspose.html.dom.svg/svggraphicselement/systemlanguage/) { get; } | 对应于给定元素上的属性“systemLanguage”。 |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | 元素的名称。 |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | 该属性返回该节点及其后代的文本内容。当它被定义为空时，设置它是无效的。在设置时，此节点可能具有的任何可能的子节点都将被删除，如果新字符串不为空或为空，则替换为包含此属性设置为的字符串的单个文本节点。 |
| [Transform](../../aspose.html.dom.svg/svggraphicselement/transform/) { get; } | 对应于给定元素上的属性“转换”。 |
| [ViewBox](../../aspose.html.dom.svg/svgsvgelement/viewbox/) { get; } | 对应于给定元素上的属性“viewBox”。 |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement/) { get; } | 建立当前视口的元素。通常，最近的祖先“svg”元素。如果给定元素是最外层的 svg 元素，则为空。 |
| [Width](../../aspose.html.dom.svg/svgsvgelement/width/) { get; } | 对应于给定“svg”元素上的属性“width”。 |
| [X](../../aspose.html.dom.svg/svgsvgelement/x/) { get; } | 对应于给定“svg”元素上的属性“x”。 |
| [Y](../../aspose.html.dom.svg/svgsvgelement/y/) { get; } | 对应于给定“svg”元素上的属性“y”。 |
| [ZoomAndPan](../../aspose.html.dom.svg/svgsvgelement/zoomandpan/) { get; set; } | 对应于给定元素上的属性“zoomAndPan”。该值必须是在此接口上定义的 SVG_ZOOMANDPAN_* 常量之一。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AnimationsPaused](../../aspose.html.dom.svg/svgsvgelement/animationspaused/)() | 如果此 SVG 文档片段处于暂停状态，则返回 true。 |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | 将节点 newChild 添加到该节点的子节点列表的末尾。如果 newChild 已经在树中，则首先将其删除。 |
| [AttachShadow](../../aspose.html.dom/element/attachshadow/)(ShadowRootMode) | 创建阴影根并将其附加到当前元素。 |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空），也没有用户数据。 |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空），也没有用户数据。 |
| [CreateEvent](../../aspose.html.dom.svg/svgsvgelement/createevent/)(string) | 创建一个[`Event`](../../aspose.html.dom.events/event/)实现支持的类型。 |
| [CreateSVGAngle](../../aspose.html.dom.svg/svgsvgelement/createsvgangle/)() | 在任何文档树之外创建一个 SVGAngle 对象。对象被初始化为值 0 度（无单位）. |
| [CreateSVGLength](../../aspose.html.dom.svg/svgsvgelement/createsvglength/)() | 在任何文档树之外创建一个 SVGLength 对象。该对象被初始化为 0 个用户单位的值。 |
| [CreateSVGMatrix](../../aspose.html.dom.svg/svgsvgelement/createsvgmatrix/)() | 在任何文档树之外创建一个 SVGMatrix 对象。对象被初始化为单位矩阵. |
| [CreateSVGNumber](../../aspose.html.dom.svg/svgsvgelement/createsvgnumber/)() | 在任何文档树之外创建一个 SVGNumber 对象。该对象被初始化为零值。 |
| [CreateSVGPoint](../../aspose.html.dom.svg/svgsvgelement/createsvgpoint/)() | 在任何文档树之外创建一个 SVGPoint 对象。对象初始化为用户坐标系中的点(0,0). |
| [CreateSVGRect](../../aspose.html.dom.svg/svgsvgelement/createsvgrect/)() | 在任何文档树之外创建一个 SVGRect 对象。对象被初始化，所有值都设置为 0 个用户单位。 |
| [CreateSVGTransform](../../aspose.html.dom.svg/svgsvgelement/createsvgtransform/)() | 在任何文档树之外创建一个 SVGTransform 对象。该对象被初始化为单位矩阵变换 (SVG_TRANSFORM_MATRIX). |
| [CreateSVGTransformFromMatrix](../../aspose.html.dom.svg/svgsvgelement/createsvgtransformfrommatrix/)(SVGMatrix) | 在任何文档树之外创建一个 SVGTransform 对象。该对象被初始化为给定的矩阵变换（即 SVG_TRANSFORM_MATRIX）。复制参数矩阵的值，不采用矩阵参数作为 SVGTransform::matrix. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | 此方法允许将事件分派到实现事件模型中。 |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | 执行与释放、释放或重置非托管资源相关的应用程序定义的任务。 |
| [GetAttribute](../../aspose.html.dom/element/getattribute/)(string) | 按名称检索属性值。 |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode/)(string) | 按名称检索属性节点。 |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens/)(string, string) | 通过本地名称和命名空间 URI 检索 Attr 节点。 |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens/)(string, string) | 通过本地名称和命名空间 URI 检索属性值。 |
| [GetBBox](../../aspose.html.dom.svg/svggraphicselement/getbbox/)() | 返回当前用户空间中的紧密边界框（即，在应用“变换”属性之后，如果有的话）所有包含的图形元素的几何图形，不包括描边、剪裁、遮罩和过滤效果）。请注意，getBBox 必须在调用该方法时返回实际的边界框，即使元素尚未呈现。 |
| [GetCTM](../../aspose.html.dom.svg/svggraphicselement/getctm/)() | 返回从当前用户单位（即，在应用“转换”属性后，如果有的话）到最近的 ViewportElement 的视口坐标系的转换矩阵。 |
| [GetCurrentTime](../../aspose.html.dom.svg/svgsvgelement/getcurrenttime/)() | 返回相对于当前 SVG 文档片段开始时间的当前时间（以秒为单位）。如果在文档时间线开始之前调用 getCurrentTime（例如，在调度文档的 SVGLoad 事件之前通过在“script”元素中运行的脚本），则返回 0。 |
| [GetElementById](../../aspose.html.dom.svg/svgsvgelement/getelementbyid/)(string) | 搜索此 SVG 文档片段（即，搜索仅限于文档树的子集）以查找其 ID 由 elementId 给出的元素。如果找到一个元素，则返回该元素。如果不存在这样的元素，则返回 null。如果多个元素具有此 id. ，则行为未定义 |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | 返回一个实时 NodeList 对象，其中包含文档中所有元素，这些元素具有参数中指定的所有类。 http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | 按文档顺序返回具有给定标签名称的所有后代元素的节点列表。 |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | 以文档顺序返回具有给定本地名称和命名空间 URI 的所有后代元素的节点列表。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [GetScreenCTM](../../aspose.html.dom.svg/svggraphicselement/getscreenctm/)() | 返回从当前用户单元（即，在应用“转换”属性后，如果有的话）到父用户代理对“像素”的通知的转换矩阵。对于显示设备，理想情况下这代表一个物理屏幕像素。对于物理像素大小未知的其他设备或环境，则可以改用类似于 CSS2 定义“像素”的算法。请注意，如果此元素未挂接到文档树中，则返回 null。此方法更恰当地命名为 getClientCTM，但由于历史原因保留了名称 getScreenCTM. |
| [HasAttribute](../../aspose.html.dom/element/hasattribute/)(string) | 当在此元素上指定具有给定名称的属性或具有默认值时返回 true，否则返回 false。 |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens/)(string, string) | 当在此元素上指定具有给定本地名称和名称空间 URI 的属性或具有默认值时返回 true，否则返回 false。 |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes/)() | 返回这个节点（如果它是一个元素）是否有任何属性 |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | 返回此节点是否有任何子节点。 |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | 在现有子节点 child 之前插入节点。如果 child 为 null，则在子节点列表的末尾插入节点。 如果 child 是 DocumentFragment 对象，则其所有子节点均按相同顺序插入到 child 之前。如果孩子已经在树中，则首先将其删除。 |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | 此方法检查指定的命名空间 URI 是否为默认命名空间。 |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | 测试两个节点是否相等。 此方法测试节点的相等性，而不是相同性（即两个节点是否是对同一对象的引用），可以使用 Node.isSameNode() 进行测试。所有相同的节点也将相等，但反过来可能不正确。 |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | 返回此节点是否与给定节点相同。 此方法提供了一种方法来确定实现返回的两个 Node 引用是否引用同一对象。当两个 Node 引用是对同一对象的引用时，即使通过代理，引用也可以完全互换使用，这样所有属性都具有相同的值，并且在任一引用上调用相同的 DOM 方法始终具有完全相同的效果。 |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | 查找与给定前缀关联的名称空间 URI，从该节点开始。 |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | 从该节点开始查找与给定名称空间 URI 关联的前缀。此方法忽略默认名称空间声明。 有关此方法使用的算法的详细信息，请参阅命名空间前缀查找。 |
| [Normalize](../../aspose.html.dom/node/normalize/)() | 将所有文本节点在此节点下的子树的完整深度（包括属性节点）放入“正常”形式，其中只有结构（例如，元素、注释、处理指令、CDATA 部分和实体引用）将文本分隔开节点，即既没有相邻的文本节点，也没有空文本节点。这可用于确保文档的 DOM 视图与保存和重新加载时相同，并且在依赖于特定文档树结构的操作（例如 XPointer [XPointer] 查找）要执行时很有用使用。如果附加到 Node.ownerDocument 的 DOMConfiguration 对象的参数“normalize-characters”为 true，则此方法也会完全规范化 Text 节点的字符。 |
| [PauseAnimations](../../aspose.html.dom.svg/svgsvgelement/pauseanimations/)() | 暂停（即暂停）在对应于此“svg”元素的 SVG 文档片段中定义的所有当前正在运行的动画，导致对应于此文档片段的动画时钟保持静止，直到它被取消暂停。 |
| [QuerySelector](../../aspose.html.dom/element/queryselector/)(string) | 返回文档中第一个匹配 selector 的元素 |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall/)(string) | 返回文档中所有元素的节点列表，匹配 selector |
| [Remove](../../aspose.html.dom/element/remove/)() | 删除此实例。 |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute/)(string) | 按名称删除属性。 |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode/)(Attr) | 删除指定的属性节点。 |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens/)(string, string) | 通过本地名称和命名空间 URI 删除属性。 |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | 从子列表中移除 oldChild 指示的子节点，并返回它。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)从中删除[`EventTarget`](../../aspose.html.dom/eventtarget/)当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)从中删除[`EventTarget`](../../aspose.html.dom/eventtarget/)当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)从中删除[`EventTarget`](../../aspose.html.dom/eventtarget/)当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | 将子节点列表中的子节点oldChild替换为newChild，并返回oldChild节点。 如果 newChild 是一个 DocumentFragment 对象，则 oldChild 将替换为所有 DocumentFragment 子对象，它们以相同的顺序插入。如果 newChild 已经在树中，则首先将其删除。 |
| [SetAttribute](../../aspose.html.dom/element/setattribute/)(string, string) | 添加新属性。如果具有该名称的属性已存在于元素中，则其值将更改为值 parameter 的值 |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode/)(Attr) | 添加一个新的属性节点。如果元素中已经存在具有该名称 (nodeName) 的属性，则它会被新的替换。 |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens/)(Attr) | 添加新属性。如果具有该本地名称和该命名空间 URI 的属性已存在于元素中，则它会被新的替换。 |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens/)(string, string, string) | 添加新属性。如果元素上已经存在具有相同本地名称和名称空间 URI 的属性，则其前缀更改为 qualifiedName 的前缀部分，其值更改为值参数. |
| [SetCurrentTime](../../aspose.html.dom.svg/svgsvgelement/setcurrenttime/)(float) | 调整此 SVG 文档片段的时钟，建立新的当前时间。如果在文档时间线开始之前调用 setCurrentTime（例如，通过在分派文档的 SVGLoad 事件之前在“script”元素中运行的脚本），则最后一次调用该方法的秒值给出文档的时间一旦文档时间线开始，将寻求。 |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute/)(string, bool) | 如果参数isId为真，则此方法声明指定属性为用户确定的ID属性。 |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode/)(Attr, bool) | 如果参数isId为真，则此方法声明指定属性为用户确定的ID属性。 |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens/)(string, string, bool) | 如果参数isId为真，则此方法声明指定属性为用户确定的ID属性。 |
| override [ToString](../../aspose.html.dom/node/tostring/)() | 返回一个String代表这个实例. |
| [UnpauseAnimations](../../aspose.html.dom.svg/svgsvgelement/unpauseanimations/)() | 取消暂停（即取消暂停）在 SVG 文档片段中定义的当前正在运行的动画，导致动画时钟从暂停时继续。 |

### 也可以看看

* class [SVGGraphicsElement](../svggraphicselement/)
* interface [ISVGFitToViewBox](../isvgfittoviewbox/)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent/)
* interface [IViewCSS](../../aspose.html.dom.css/iviewcss/)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss/)
* interface [ISVGZoomAndPan](../isvgzoomandpan/)
* 命名空间 [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* 部件 [Aspose.HTML](../../)


