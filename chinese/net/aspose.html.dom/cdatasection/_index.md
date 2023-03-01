---
title: Class CDATASection
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.CDATASection 班级. CDATA 部分用于转义包含字符的文本块否则这些字符将被视为标记
type: docs
weight: 200
url: /zh/net/aspose.html.dom/cdatasection/
---
## CDATASection class

CDATA 部分用于转义包含字符的文本块，否则这些字符将被视为标记。

```csharp
public class CDATASection : Text
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | 包含此节点属性的 NamedNodeMap（如果它是一个元素）或 null 否则。 |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | 此节点的绝对基础 URI，如果实现无法获得绝对 URI，则为 null。 |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | 包含此节点的所有子节点的 NodeList。如果没有孩子，这是一个不包含节点的 NodeList.. |
| virtual [Data](../../aspose.html.dom/characterdata/data/) { get; set; } | 实现该接口的节点的字符数据。 |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | 此节点的第一个子节点。如果没有这样的节点，则返回 null. |
| [IsElementContentWhitespace](../../aspose.html.dom/text/iselementcontentwhitespace/) { get; } | 返回此文本节点是否包含元素内容空白，通常被滥用为“可忽略的空白”。 |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | 此节点的最后一个子节点。如果没有这样的节点，则返回 null. |
| [Length](../../aspose.html.dom/characterdata/length/) { get; } | 可通过数据和下面的 substringData 方法获得的 16 位单元的数量。这可能具有零值，即 CharacterData 节点可能为空。 |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | 返回此节点限定名称的本地部分。 对于除 ELEMENT_NODE 和 ATTRIBUTE_NODE 以外的任何类型的节点以及使用 DOM Level 1 方法创建的节点，例如 Document.createElement()，这始终为空。 |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | 此节点的名称空间 URI，如果未指定则为 null。 |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | 紧接此节点之后的节点。如果没有这样的节点，则返回 null. |
| override [NodeName](../../aspose.html.dom/cdatasection/nodename/) { get; } | 此节点的名称，取决于其类型。 |
| override [NodeType](../../aspose.html.dom/cdatasection/nodetype/) { get; } | 表示底层对象类型的代码。 |
| override [NodeValue](../../aspose.html.dom/text/nodevalue/) { get; set; } | 这个节点的值，取决于它的类型。 |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | 与此节点关联的文档对象。这也是用于创建新节点的文档对象。当此节点是尚未与任何文档一起使用的文档或文档类型时，这是 null. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | 获取父级[`Element`](../element/)这个节点的. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | 此节点的父节点。除了 Attr、Document、DocumentFragment、Entity 和 Notation 之外的所有节点都可以有一个父节点。但是，如果一个节点刚刚被创建，还没有添加到树中，或者它已经从树中移除，这就是 null. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | 此节点的名称空间前缀，如果未指定则为 null。定义为null时，设置无效 |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | 紧接此节点之前的节点。如果没有这样的节点，则返回 null. |
| override [TextContent](../../aspose.html.dom/text/textcontent/) { get; set; } | 该属性返回该节点及其后代的文本内容。当它被定义为空时，设置它是无效的。在设置时，此节点可能具有的任何可能的子节点都将被删除，如果新字符串不为空或为空，则替换为包含此属性设置为的字符串的单个文本节点。 |
| [WholeText](../../aspose.html.dom/text/wholetext/) { get; } | 返回逻辑上与该节点相邻的文本节点的文本节点的所有文本，按文档顺序连接。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | 此方法允许在事件目标上注册事件侦听器。 |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | 将节点 newChild 添加到该节点的子节点列表的末尾。如果 newChild 已经在树中，则首先将其删除。 |
| virtual [AppendData](../../aspose.html.dom/characterdata/appenddata/)(string) | 将字符串附加到节点的字符数据的末尾。 |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空），也没有用户数据。 |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | 返回此节点的副本，即用作节点的通用复制构造函数。重复节点没有父节点（parentNode 为空），也没有用户数据。 |
| virtual [DeleteData](../../aspose.html.dom/characterdata/deletedata/)(int, int) | 从节点中删除一系列 16 位单元。 |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | 此方法允许将事件分派到实现事件模型中。 |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | 执行与释放、释放或重置非托管资源相关的应用程序定义的任务。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | 返回这个节点（如果它是一个元素）是否有任何属性 |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | 返回此节点是否有任何子节点。 |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | 在现有子节点 child 之前插入节点。如果 child 为 null，则在子节点列表的末尾插入节点。 如果 child 是 DocumentFragment 对象，则其所有子节点均按相同顺序插入到 child 之前。如果孩子已经在树中，则首先将其删除。 |
| virtual [InsertData](../../aspose.html.dom/characterdata/insertdata/)(int, string) | 在指定的 16 位单元偏移处插入一个字符串。 |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | 此方法检查指定的命名空间 URI 是否为默认命名空间。 |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | 测试两个节点是否相等。 此方法测试节点的相等性，而不是相同性（即两个节点是否是对同一对象的引用），可以使用 Node.isSameNode() 进行测试。所有相同的节点也将相等，但反过来可能不正确。 |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | 返回此节点是否与给定节点相同。 此方法提供了一种方法来确定实现返回的两个 Node 引用是否引用同一对象。当两个 Node 引用是对同一对象的引用时，即使通过代理，引用也可以完全互换使用，这样所有属性都具有相同的值，并且在任一引用上调用相同的 DOM 方法始终具有完全相同的效果。 |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | 查找与给定前缀关联的名称空间 URI，从该节点开始。 |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | 从该节点开始查找与给定名称空间 URI 关联的前缀。此方法忽略默认名称空间声明。 有关此方法使用的算法的详细信息，请参阅命名空间前缀查找。 |
| [Normalize](../../aspose.html.dom/node/normalize/)() | 将所有文本节点在此节点下的子树的完整深度（包括属性节点）放入“正常”形式，其中只有结构（例如，元素、注释、处理指令、CDATA 部分和实体引用）将文本分隔开节点，即既没有相邻的文本节点，也没有空文本节点。这可用于确保文档的 DOM 视图与保存和重新加载时相同，并且在依赖于特定文档树结构的操作（例如 XPointer [XPointer] 查找）要执行时很有用使用。如果附加到 Node.ownerDocument 的 DOMConfiguration 对象的参数“normalize-characters”为 true，则此方法也会完全规范化 Text 节点的字符。 |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | 从子列表中移除 oldChild 指示的子节点，并返回它。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)从中删除[`EventTarget`](../eventtarget/)当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)从中删除[`EventTarget`](../eventtarget/)当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | 此方法允许从事件目标中删除事件侦听器。 如果一个[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)从中删除[`EventTarget`](../eventtarget/)当它正在处理一个事件时，它不会被当前的动作触发。 事件监听器在被移除后永远不会被调用。 |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | 将子节点列表中的子节点oldChild替换为newChild，并返回oldChild节点。 如果 newChild 是一个 DocumentFragment 对象，则 oldChild 将替换为所有 DocumentFragment 子对象，它们以相同的顺序插入。如果 newChild 已经在树中，则首先将其删除。 |
| virtual [ReplaceData](../../aspose.html.dom/characterdata/replacedata/)(int, int, string) | 用指定的字符串替换从指定的 16 位单元偏移量开始的字符。 |
| [ReplaceWholeText](../../aspose.html.dom/text/replacewholetext/)(string) | 用指定文本替换当前节点和所有逻辑上相邻的文本节点的文本。删除所有逻辑上相邻的文本节点，包括当前节点，除非它是替换文本的接收者。 |
| [SplitText](../../aspose.html.dom/text/splittext/)(int) | 将此节点分成指定偏移处的两个节点，将它们作为兄弟节点保留在树中。 |
| virtual [SubstringData](../../aspose.html.dom/characterdata/substringdata/)(int, int) | 从节点中提取一系列数据。 |
| override [ToString](../../aspose.html.dom/characterdata/tostring/)() | 返回一个String代表这个实例. |

### 也可以看看

* class [Text](../text/)
* 命名空间 [Aspose.Html.Dom](../../aspose.html.dom/)
* 部件 [Aspose.HTML](../../)


