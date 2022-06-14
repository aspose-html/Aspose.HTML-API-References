---
title: CharacterData
second_title: Aspose.HTML for .NET API 参考
description: CharacterData 使用一组属性和方法扩展了 Node用于访问 DOM 中的字符数据
type: docs
weight: 410
url: /zh/net/aspose.html.dom/characterdata/
---
## CharacterData class

CharacterData 使用一组属性和方法扩展了 Node，用于访问 DOM 中的字符数据。

```csharp
public abstract class CharacterData : Node
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes) { get; } | NamedNodeMap 包含此节点的属性（如果它是一个元素），否则为 null。 |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | 此节点的绝对基本 URI 或 null 如果实现无法获得绝对 URI。 |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | 一个包含该节点所有子节点的 NodeList。如果没有子节点，这是一个不包含节点的 NodeList.. |
| virtual [Data](../../aspose.html.dom/characterdata/data) { get; set; } | 实现该接口的节点的字符数据。 |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | 此节点的第一个子节点。如果没有这样的节点，则返回 null。 |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | 该节点的最后一个子节点。如果没有这样的节点，则返回 null。 |
| [Length](../../aspose.html.dom/characterdata/length) { get; } | 通过 data 和下面的 substringData 方法可用的 16 位单元的数量。这可能具有零值，即 CharacterData 节点可能为空。 |
| virtual [LocalName](../../aspose.html.dom/node/localname) { get; } | 返回此节点的限定名称的本地部分。 对于除 ELEMENT_NODE 和 ATTRIBUTE_NODE 之外的任何类型的节点以及使用 DOM 级别 1 方法（例如 Document.createElement()）创建的节点，这始终为 null。 |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri) { get; } | 此节点的命名空间 URI，如果未指定，则为 null。 |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | 紧跟该节点的节点。如果没有这样的节点，则返回 null。 |
| abstract [NodeName](../../aspose.html.dom/node/nodename) { get; } | 此节点的名称，取决于其类型。 |
| abstract [NodeType](../../aspose.html.dom/node/nodetype) { get; } | 表示底层对象类型的代码。 |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | 此节点的值，取决于其类型。 |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | 与此节点关联的 Document 对象。这也是用于创建新节点的 Document 对象。当此节点是尚未与任何 Document 一起使用的 Document 或 DocumentType 时，此节点为 null。 |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | 获取此节点的父[`Element`](../element)。 |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | 该节点的父节点。除 Attr、Document、DocumentFragment、Entity 和 Notation 之外的所有节点都可以有父节点。但是，如果一个节点刚刚创建但尚未添加到树中，或者它已从树中删除，则为 null。 |
| virtual [Prefix](../../aspose.html.dom/node/prefix) { get; set; } | 此节点的命名空间前缀，如果未指定，则为 null。当定义为null时，设置没有效果 |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | 紧接在此节点之前的节点。如果没有这样的节点，则返回 null。 |
| virtual [TextContent](../../aspose.html.dom/node/textcontent) { get; set; } | 此属性返回此节点及其后代的文本内容。定义为null时，设置无效。设置时，此节点可能具有的任何可能的子节点都将被删除，如果新字符串不为空或 null，则替换为包含此属性设置为的字符串的单个 Text 节点。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | 将节点 newChild 添加到该节点的子节点列表的末尾。如果 newChild 已经在树中，则首先将其移除。 |
| virtual [AppendData](../../aspose.html.dom/characterdata/appenddata)(string) | 将字符串追加到节点字符数据的末尾。 |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空）并且没有用户数据。 |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空）并且没有用户数据。 |
| virtual [DeleteData](../../aspose.html.dom/characterdata/deletedata)(int, int) | 从节点中删除一系列 16 位单元。 |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | 此方法允许将事件分派到实现事件模型中。 |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | 此方法用于检索 ECMAScript 对象Type。 |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes)() | 返回此节点（如果是元素）是否有任何属性 |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | 返回此节点是否有任何子节点。 |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | 在现有子节点 child 之前插入节点。如果 child 为 null，则在子列表的末尾插入节点。 如果 child 是 DocumentFragment 对象，则它的所有孩子都以相同的顺序插入到 child 之前。如果孩子已经在树中，则首先将其移除。 |
| virtual [InsertData](../../aspose.html.dom/characterdata/insertdata)(int, string) | 在指定的 16 位单元偏移处插入一个字符串。 |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | 此方法检查指定的 namespaceURI 是否为默认命名空间。 |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | 测试两个节点是否相等。 此方法测试节点的相等性，而不是相同性（即两个节点是否是对同一对象的引用），可以使用 Node.isSameNode() 测试。所有相同的节点也将相等，尽管反过来可能不正确。 |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | 返回此节点是否与给定节点相同。 该方法提供了一种方法来确定实现返回的两个 Node 引用是否引用同一个对象。当两个 Node 引用是对同一个对象的引用时，即使通过代理，这些引用也可以完全互换使用，这样所有属性都具有相同的值，并且在任一引用上调用相同的 DOM 方法总是具有完全相同的效果。 |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | 从该节点开始查找与给定前缀关联的命名空间 URI。 |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | 从该节点开始查找与给定命名空间 URI 关联的前缀。此方法忽略默认命名空间声明。 有关此方法使用的算法的详细信息，请参阅命名空间前缀查找。 |
| [Normalize](../../aspose.html.dom/node/normalize)() | 将所有位于该节点下的子树全深度的文本节点，包括属性节点，放入“正常”形式，其中只有结构（例如，元素，注释、处理指令、CDATA 部分和实体引用）分隔 Text 节点，即既没有相邻的 Text 节点，也没有空的 Text 节点。这可用于确保文档的 DOM 视图与保存和重新加载时相同，并且在依赖于特定文档树结构的操作（例如 XPointer [XPointer] 查找）时很有用使用。如果附加到 Node.ownerDocument 的 DOMConfiguration 对象的参数“normalize-characters”为 true，则此方法还将完全规范化 Text 节点的字符。 |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | 从子节点列表中移除 oldChild 指示的子节点，并返回它。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | 此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../../aspose.html.dom.events/ieventlistener)从[`EventTarget`](../eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | 此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../../aspose.html.dom.events/ieventlistener)从[`EventTarget`](../eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | 此方法允许从事件目标中删除事件侦听器。 如果[`IEventListener`](../../aspose.html.dom.events/ieventlistener)从[`EventTarget`](../eventtarget)中删除，而它正在处理一个事件，它不会被当前操作触发。 事件监听器在被移除后永远不能被调用。 |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | 将子节点列表中的子节点 oldChild 替换为 newChild，并返回 oldChild 节点。 如果 newChild 是 DocumentFragment 对象，则 oldChild 将替换为所有 DocumentFragment 子代，它们以相同的顺序插入。如果 newChild 已经在树中，则首先将其移除。 |
| virtual [ReplaceData](../../aspose.html.dom/characterdata/replacedata)(int, int, string) | 用指定的字符串替换从指定的 16 位单位偏移量开始的字符。 |
| virtual [SubstringData](../../aspose.html.dom/characterdata/substringdata)(int, int) | 从节点中提取数据范围。 |
| override [ToString](../../aspose.html.dom/characterdata/tostring)() | 返回代表此实例的String。 |

### 也可以看看

* class [Node](../node)
* 命名空间 [Aspose.Html.Dom](../../aspose.html.dom)
* 部件 [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
