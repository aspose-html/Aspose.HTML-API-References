---
title: Aspose.Html.Dom
second_title: Aspose.HTML for .NET API 参考
description: 的 Aspose.Html.Dom文档对象模型 namespace 提供 API 表示任何 HTMLXML 或 SVG 文档并与之交互 DOM 是加载到浏览器中的文档模型 将文档表示为节点树其中每个 node 表示文档的一部分例如元素文本字符串或注释
type: docs
weight: 40
url: /zh/net/aspose.html.dom/
---
的 **Aspose.Html.Dom（文档对象模型）** namespace 提供 API， 表示任何 HTML、XML 或 SVG 文档并与之交互。 DOM 是加载到浏览器中的文档模型， 将文档表示为节点树，其中每个 node 表示文档的一部分（例如元素、文本字符串，或注释）。

## 课程

| 班级 | 描述 |
| --- | --- |
| [Attr](./attr/) | Attr 接口表示 Element 对象中的属性。通常，属性的允许值在与文档关联的模式中定义。 |
| [CDATASection](./cdatasection/) | CDATA 部分用于转义包含字符的文本块，否则这些字符将被视为标记。 |
| [CharacterData](./characterdata/) | CharacterData 使用一组属性和方法扩展 Node，用于访问 DOM 中的字符数据。 |
| [Comment](./comment/) | 继承自CharacterData，表示注释的内容，即开始'之间的所有字符. |
| [Document](./document/) | Document 表示整个 HTML、XML 或 SVG 文档。从概念上讲，它是文档树的根，并提供对文档数据的主要访问。 |
| [DocumentFragment](./documentfragment/) | DocumentFragment 是“轻量级”或“最小”文档对象。希望能够提取文档树的一部分或创建文档的新片段是很常见的。 |
| [DocumentType](./documenttype/) | DocumentType 为为文档 定义的实体列表提供接口 |
| [DOMException](./domexception/) | DOMException 接口表示异常事件（称为异常），它是由于调用方法或访问 Web API 的属性而发生的。这基本上是 Web API 中描述错误情况的方式。 |
| [DOMObject](./domobject/) | DOMObject 类型用于表示整个文档对象模型的基础对象。 对于 Java 和 ECMAScript，DOMObject 绑定到 Object 类型。 |
| [Element](./element/) | Element 接口表示 HTML 或 XML 文档中的元素。 |
| [Entity](./entity/) | 表示 XML 文档中已解析或未解析的已知实体。 |
| [EntityReference](./entityreference/) | EntityReference 节点可用于表示树中的实体引用。 |
| [EventTarget](./eventtarget/) | 的[`EventTarget`](../aspose.html.dom/eventtarget/)接口由支持 DOM 事件模型的实现中的所有节点实现。 因此，可以通过在 Node 接口的实例上使用特定于绑定的转换方法来获得此接口。 该接口允许注册和删除事件侦听器一个[`EventTarget`](../aspose.html.dom/eventtarget/)并向其发送事件[`IEventTarget`](../aspose.html.dom.events/ieventtarget/). |
| [Node](./node/) | Node 接口是整个文档对象模型的主要数据类型。它代表文档树中的单个节点。 |
| [Notation](./notation/) | 表示在 DTD 中声明的符号。 |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction 表示“处理指令”，在 XML 中用作在文档文本中保留处理器特定信息的方式。 |
| [ShadowRoot](./shadowroot/) | ShadowRoot 是影子树的根节点。 |
| [Text](./text/) | Text 接口继承自 CharacterData 并表示元素或属性的文本内容（在 XML 中称为字符数据）。 |
| [TypeInfo](./typeinfo/) | TypeInfo 表示从 Element 或 Attr 节点引用的类型，在与文档关联的模式中指定。 |
## 接口

| 界面 | 描述 |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | 浏览上下文是一个环境，其中[`Document`](../aspose.html.dom/document/)对象呈现给用户。 |
| [IChildNode](./ichildnode/) | 定义[`IChildNode`](../aspose.html.dom/ichildnode/)应该实现的接口[`Node`](../aspose.html.dom/node/)可以有父母. |
| [IDocumentInit](./idocumentinit/) | 这个接口提供[`Document`](../aspose.html.dom/document/)初始化信息. |
| [IDOMImplementation](./idomimplementation/) | DOMImplementation 接口提供了许多方法来执行独立于文档对象模型的任何特定实例的操作。 |
| [IElementInit](./ielementinit/) | 这个接口提供[`Element`](../aspose.html.dom/element/)初始化信息. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | 表示所有支持系统事件处理的元素必须继承的接口 |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | 定义[`IChildNode`](../aspose.html.dom/ichildnode/)那不是[`DOCUMENT_TYPE_NODE`](../aspose.html.dom/node/document_type_node/). |
| [INonElementParentNode](./inonelementparentnode/) | 定义[`IParentNode`](../aspose.html.dom/iparentnode/)不是元素类型. |
| [IParentNode](./iparentnode/) | 定义[`IParentNode`](../aspose.html.dom/iparentnode/)由任何可能的父母实现的接口。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | ShadowRoot 可以运行的模式。 |


