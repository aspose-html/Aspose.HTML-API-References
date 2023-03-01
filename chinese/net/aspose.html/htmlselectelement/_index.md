---
title: Class HTMLSelectElement
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.HTMLSelectElement 班级. 选择元素允许选择一个选项包含的选项 可以通过 select 元素作为集合直接访问请参阅 HTML 4.01. 中的 SELECT 元素定义
type: docs
weight: 3520
url: /zh/net/aspose.html/htmlselectelement/
---
## HTMLSelectElement class

选择元素允许选择一个选项。包含的选项 可以通过 select 元素作为集合直接访问。请参阅 HTML 4.01. 中的 SELECT 元素定义

另见[文档对象模型 (DOM) 2 级 HTML 规范](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```csharp
public class HTMLSelectElement : HTMLElement
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
| [ClassName](../../aspose.html/htmlelement/classname/) { get; set; } | 元素的类属性。由于 与许多语言公开的“class”关键字冲突，此属性已重命名。请参阅 HTML 4.01. 中的类属性定义 |
| [Dir](../../aspose.html/htmlelement/dir/) { get; set; } | 指定方向性中性文本的基本方向和表格的 方向性。请参阅 HTML 4.01. 中的 dir 属性定义 |
| [Disabled](../../aspose.html/htmlselectelement/disabled/) { get; set; } | 控件在此上下文中不可用。请参阅 HTML 4.01. 中的禁用属性 定义 |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | 此节点的第一个子节点。如果没有这样的节点，则返回 null. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | 返回该元素的第一个子元素节点。如果此元素没有子元素，则为 null. |
| [Form](../../aspose.html/htmlselectelement/form/) { get; } | 这个选项的个数`选择` . |
| [Id](../../aspose.html/htmlelement/id/) { get; set; } | 元素的标识符。参见 HTML 4.01. 中的 id 属性定义 |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | 返回表示元素内容的 HTML 或 XML 片段。 可以设置，用从给定字符串解析的节点替换元素的内容。 |
| [Lang](../../aspose.html/htmlelement/lang/) { get; set; } | RFC 1766 中定义的语言代码。请参阅 HTML 4.01. 中的 lang 属性定义 |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | 此节点的最后一个子节点。如果没有这样的节点，则返回 null. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | 返回该元素的最后一个子元素节点。如果此元素没有子元素，则为 null. |
| [Length](../../aspose.html/htmlselectelement/length/) { get; set; } | 这个选项的个数`选择` @version DOM 级别 2 |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | 返回此节点限定名称的本地部分。 对于除 ELEMENT_NODE 和 ATTRIBUTE_NODE 以外的任何类型的节点以及使用 DOM Level 1 方法创建的节点，例如 Document.createElement()，这始终为空。 |
| [Multiple](../../aspose.html/htmlselectelement/multiple/) { get; set; } | 如果为真，则为多个`选项`可以在此选择元素`选择`.请参阅 HTML 4.01. 中的多属性定义 |
| [Name](../../aspose.html/htmlselectelement/name/) { get; set; } | 与表单一起提交时的表单控件或对象名称。请参阅 HTML 4.01. 中的名称 属性定义 |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | 此节点的名称空间 URI，如果未指定则为 null。 |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | 返回此元素的下一个兄弟元素节点。如果此元素在文档树中没有此元素之后的元素兄弟节点，则为 null. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | 紧接此节点之后的节点。如果没有这样的节点，则返回 null. |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | 此节点的名称，取决于其类型。 |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | 表示底层对象类型的代码。 |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | 这个节点的值，取决于它的类型。 |
| [Options](../../aspose.html/htmlselectelement/options/) { get; } | 的集合`选项`此 元素包含的元素。 @version DOM 级别 2 |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | 返回表示元素及其内容的 HTML 或 XML 片段。 可以设置，用从给定字符串解析的节点替换元素。 |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | 与此节点关联的文档对象。这也是用于创建新节点的文档对象。当此节点是尚未与任何文档一起使用的文档或文档类型时，这是 null. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | 获取父级[`Element`](../../aspose.html.dom/element/)这个节点的. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | 此节点的父节点。除了 Attr、Document、DocumentFragment、Entity 和 Notation 之外的所有节点都可以有一个父节点。但是，如果一个节点刚刚被创建，还没有添加到树中，或者它已经从树中移除，这就是 null. |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | 此节点的名称空间前缀，如果未指定则为 null。定义为null时，设置无效 |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | 返回该元素的前一个兄弟元素节点。如果此元素在文档树中没有出现在该元素之前的元素兄弟节点，则为 null. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | 紧接此节点之前的节点。如果没有这样的节点，则返回 null. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo/) { get; } | 与此元素关联的类型信息。 |
| [SelectedIndex](../../aspose.html/htmlselectelement/selectedindex/) { get; set; } | 所选选项的序号索引，从 0 开始。如果没有选择任何元素，则返回值 -1 。如果选择了多个选项 ，则返回第一个选择的选项的索引。 |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | 返回存储在此元素上的 shadowRoot，如果关闭则返回 null。 |
| [Size](../../aspose.html/htmlselectelement/size/) { get; set; } | 可见行数。请参阅 HTML 4.01. 中的大小属性定义 |
| [Style](../../aspose.html/htmlelement/style/) { get; } | 表示样式属性，允许作者将样式信息直接应用于特定元素。 |
| [TabIndex](../../aspose.html/htmlselectelement/tabindex/) { get; set; } | 表示元素在 Tab 键顺序中的位置的索引。请参阅 HTML 4.01. 中的 tabindex 属性定义 |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | 元素的名称。 |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | 该属性返回该节点及其后代的文本内容。当它被定义为空时，设置它是无效的。在设置时，此节点可能具有的任何可能的子节点都将被删除，如果新字符串不为空或为空，则替换为包含此属性设置为的字符串的单个文本节点。 |
| [Title](../../aspose.html/htmlelement/title/) { get; set; } | 元素的咨询标题。请参阅 HTML 4.01. 中的 title 属性定义 |
| [Type](../../aspose.html/htmlselectelement/type/) { get; } | 此表单控件的类型。这是 multiple 属性时的字符串“select-multiple”`真的`和字符串“选择一个”时`错误的`. |
| [Value](../../aspose.html/htmlselectelement/value/) { get; set; } | 当前表单控件值（即当前 所选选项的值），如果选择了多个选项，则这是第一个所选选项的值 。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | 将节点 newChild 添加到该节点的子节点列表的末尾。如果 newChild 已经在树中，则首先将其删除。 |
| [AttachShadow](../../aspose.html.dom/element/attachshadow/)(ShadowRootMode) | 创建阴影根并将其附加到当前元素。 |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空），也没有用户数据。 |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空），也没有用户数据。 |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | 此方法允许将事件分派到实现事件模型中。 |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | 执行与释放、释放或重置非托管资源相关的应用程序定义的任务。 |
| [GetAttribute](../../aspose.html.dom/element/getattribute/)(string) | 按名称检索属性值。 |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode/)(string) | 按名称检索属性节点。 |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens/)(string, string) | 通过本地名称和命名空间 URI 检索 Attr 节点。 |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens/)(string, string) | 通过本地名称和命名空间 URI 检索属性值。 |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | 返回一个实时 NodeList 对象，其中包含文档中所有元素，这些元素具有参数中指定的所有类。 http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | 按文档顺序返回具有给定标签名称的所有后代元素的节点列表。 |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | 以文档顺序返回具有给定本地名称和命名空间 URI 的所有后代元素的节点列表。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
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
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute/)(string, bool) | 如果参数isId为真，则此方法声明指定属性为用户确定的ID属性。 |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode/)(Attr, bool) | 如果参数isId为真，则此方法声明指定属性为用户确定的ID属性。 |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens/)(string, string, bool) | 如果参数isId为真，则此方法声明指定属性为用户确定的ID属性。 |
| override [ToString](../../aspose.html.dom/node/tostring/)() | 返回一个String代表这个实例. |

## 活动

| 姓名 | 描述 |
| --- | --- |
| event [OnAbort](../../aspose.html/htmlelement/onabort/) | 获取或设置 OnAbort 事件的事件处理程序。 |
| event [OnBlur](../../aspose.html/htmlelement/onblur/) | 获取或设置 OnBlur 事件的事件处理程序。 |
| event [OnCancel](../../aspose.html/htmlelement/oncancel/) | 获取或设置 OnCancel 事件的事件处理程序。 |
| event [OnCanplay](../../aspose.html/htmlelement/oncanplay/) | 获取或设置 OnCanplay 事件的事件处理程序。 |
| event [OnCanPlayThrough](../../aspose.html/htmlelement/oncanplaythrough/) | 获取或设置 OnCanPlayThrough 事件的事件处理程序。 |
| event [OnChange](../../aspose.html/htmlelement/onchange/) | 获取或设置 OnChange 事件的事件处理程序。 |
| event [OnClick](../../aspose.html/htmlelement/onclick/) | 获取或设置 OnClick 事件的事件处理程序。 |
| event [OnCueChange](../../aspose.html/htmlelement/oncuechange/) | 获取或设置 OnCueChange 事件的事件处理程序。 |
| event [OnDblClick](../../aspose.html/htmlelement/ondblclick/) | 获取或设置 OnDblClick 事件的事件处理程序。 |
| event [OnDurationChange](../../aspose.html/htmlelement/ondurationchange/) | 获取或设置 OnDurationChange 事件的事件处理程序。 |
| event [OnEmptied](../../aspose.html/htmlelement/onemptied/) | 获取或设置 OnEmptied 事件的事件处理程序。 |
| event [OnEnded](../../aspose.html/htmlelement/onended/) | 获取或设置 OnEnded 事件的事件处理程序。 |
| event [OnError](../../aspose.html/htmlelement/onerror/) | 获取或设置 OnError 事件的事件处理程序。 |
| event [OnFocus](../../aspose.html/htmlelement/onfocus/) | 获取或设置 OnFocus 事件的事件处理程序。 |
| event [OnInput](../../aspose.html/htmlelement/oninput/) | 获取或设置 OnInput 事件的事件处理程序。 |
| event [OnInvalid](../../aspose.html/htmlelement/oninvalid/) | 获取或设置 OnInvalid 事件的事件处理程序。 |
| event [OnKeyDown](../../aspose.html/htmlelement/onkeydown/) | 获取或设置 OnKeyDown 事件的事件处理程序。 |
| event [OnKeyPress](../../aspose.html/htmlelement/onkeypress/) | 获取或设置 OnKeyPress 事件的事件处理程序。 |
| event [OnKeyUp](../../aspose.html/htmlelement/onkeyup/) | 获取或设置 OnKeyUp 事件的事件处理程序。 |
| event [OnLoad](../../aspose.html/htmlelement/onload/) | 获取或设置 OnLoad 事件的事件处理程序。 |
| event [OnLoadedData](../../aspose.html/htmlelement/onloadeddata/) | 获取或设置 OnLoadedData 事件的事件处理程序。 |
| event [OnLoadedMetadata](../../aspose.html/htmlelement/onloadedmetadata/) | 获取或设置 OnLoadedMetadata 事件的事件处理程序。 |
| event [OnLoadStart](../../aspose.html/htmlelement/onloadstart/) | 获取或设置 OnLoadStart 事件的事件处理程序。 |
| event [OnMouseDown](../../aspose.html/htmlelement/onmousedown/) | 获取或设置 OnMouseDown 事件的事件处理程序。 |
| event [OnMouseEnter](../../aspose.html/htmlelement/onmouseenter/) | 获取或设置 OnMouseEnter 事件的事件处理程序。 |
| event [OnMouseLeave](../../aspose.html/htmlelement/onmouseleave/) | 获取或设置 OnMouseLeave 事件的事件处理程序。 |
| event [OnMouseMove](../../aspose.html/htmlelement/onmousemove/) | 获取或设置 OnMouseMove 事件的事件处理程序。 |
| event [OnMouseOut](../../aspose.html/htmlelement/onmouseout/) | 获取或设置 OnMouseOut 事件的事件处理程序。 |
| event [OnMouseOver](../../aspose.html/htmlelement/onmouseover/) | 获取或设置 OnMouseOver 事件的事件处理程序。 |
| event [OnMouseUp](../../aspose.html/htmlelement/onmouseup/) | 获取或设置 OnMouseUp 事件的事件处理程序。 |
| event [OnMouseWheel](../../aspose.html/htmlelement/onmousewheel/) | 获取或设置 OnMouseWheel 事件的事件处理程序。 |
| event [OnPause](../../aspose.html/htmlelement/onpause/) | 获取或设置 OnPause 事件的事件处理程序。 |
| event [OnPlay](../../aspose.html/htmlelement/onplay/) | 获取或设置 OnPlay 事件的事件处理程序。 |
| event [OnPlaying](../../aspose.html/htmlelement/onplaying/) | 获取或设置 OnPlaying 事件的事件处理程序。 |
| event [OnProgress](../../aspose.html/htmlelement/onprogress/) | 获取或设置 OnProgress 事件的事件处理程序。 |
| event [OnRateChange](../../aspose.html/htmlelement/onratechange/) | 获取或设置 OnRateChange 事件的事件处理程序。 |
| event [OnReset](../../aspose.html/htmlelement/onreset/) | 获取或设置 OnReset 事件的事件处理程序。 |
| event [OnResize](../../aspose.html/htmlelement/onresize/) | 获取或设置 OnResize 事件的事件处理程序。 |
| event [OnScroll](../../aspose.html/htmlelement/onscroll/) | 获取或设置 OnScroll 事件的事件处理程序。 |
| event [OnSeeked](../../aspose.html/htmlelement/onseeked/) | 获取或设置 OnSeeked 事件的事件处理程序。 |
| event [OnSeeking](../../aspose.html/htmlelement/onseeking/) | 获取或设置 OnSeeking 事件的事件处理程序。 |
| event [OnSelect](../../aspose.html/htmlelement/onselect/) | 获取或设置 OnSelect 事件的事件处理程序。 |
| event [OnShow](../../aspose.html/htmlelement/onshow/) | 获取或设置 OnShow 事件的事件处理程序。 |
| event [OnStalled](../../aspose.html/htmlelement/onstalled/) | 获取或设置 OnStalled 事件的事件处理程序。 |
| event [OnSubmit](../../aspose.html/htmlelement/onsubmit/) | 获取或设置 OnSubmit 事件的事件处理程序。 |
| event [OnSuspend](../../aspose.html/htmlelement/onsuspend/) | 获取或设置 OnSuspend 事件的事件处理程序。 |
| event [OnTimeUpdate](../../aspose.html/htmlelement/ontimeupdate/) | 获取或设置 OnTimeUpdate 事件的事件处理程序。 |
| event [OnToggle](../../aspose.html/htmlelement/ontoggle/) | 获取或设置 OnToggle 事件的事件处理程序。 |
| event [OnVolumeChange](../../aspose.html/htmlelement/onvolumechange/) | 获取或设置 OnVolumeChange 事件的事件处理程序。 |
| event [OnWaiting](../../aspose.html/htmlelement/onwaiting/) | 获取或设置 OnWaiting 事件的事件处理程序。 |

### 也可以看看

* class [HTMLElement](../htmlelement/)
* 命名空间 [Aspose.Html](../../aspose.html/)
* 部件 [Aspose.HTML](../../)


