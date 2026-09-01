---
title: "com.aspose.html.dom"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom Document Object Model 包提供用于表示和交互任何 HTML、XML 或 SVG 文档的 API。DOM 是在浏览器中加载的文档模型，以节点树的形式表示文档，其中每个节点代表文档的一部分，例如元素、文本、字符串或注释。"
type: docs

url: /zh/java/com.aspose.html.dom/
---
该 **com.aspose.html.dom (Document Object Model)** 包提供用于表示和交互任何 HTML、XML 或 SVG 文档的 API。DOM 是在浏览器中加载的文档模型，将文档表示为节点树，其中每个节点代表文档的一部分（例如元素、文本字符串或注释）。

## 类

| 类 | 描述 |
| --- | --- |
| [Attr](./attr/) | Attr 接口表示 Element 对象中的属性。通常，属性的允许值在与文档关联的模式中定义。 |
| [CDATASection](./cdatasection/) | CDATA 区段用于转义包含本应被视为标记的字符的文本块。 |
| [CharacterData](./characterdata/) | CharacterData 扩展 Node，提供一组属性和方法用于访问 DOM 中的字符数据。 |
| [Comment](./comment/) | 继承自 CharacterData，表示注释的内容，即起始 '' 之间的所有字符。 |
| [Document](./document/) | Document 表示整个 HTML、XML 或 SVG 文档。从概念上讲，它是文档树的根，并提供对文档数据的主要访问。 |
| [DocumentFragment](./documentfragment/) | DocumentFragment 是一个 "lightweight" 或 "minimal" 的 Document 对象。通常需要提取文档树的一部分或创建文档的新片段。 |
| [DocumentType](./documenttype/) | DocumentType 提供用于访问文档中已定义实体列表的接口。 |
| [DOMException](./domexception/) | DOMException 接口表示因调用方法或访问 Web API 的属性而产生的异常事件（称为异常）。这基本上是 Web API 中错误情况的描述方式。 |
| [DOMObject](./domobject/) | DOMObject 类型用于表示整个 Document Object Model 的基础对象。对于 Java 和 ECMAScript，DOMObject 绑定到 Object 类型。 |
| [Element](./element/) | Element 接口表示 HTML 或 XML 文档中的元素。 |
| [Entity](./entity/) | 表示 XML 文档中已知的实体，可以是已解析的或未解析的。 |
| [EntityReference](./entityreference/) | EntityReference 节点可用于在树中表示实体引用。 |
| [EventTarget](./eventtarget/) | EventTarget 接口由能够接收事件并可能拥有监听器的对象实现。换句话说，任何事件目标都实现了该接口关联的三个方法。 |
| [Node](./node/) | Node 接口是整个文档对象模型的主要数据类型。它表示文档树中的单个节点。虽然所有实现 Node 接口的对象都公开处理子节点的方法，但并非所有实现 Node 接口的对象都可能拥有子节点。例如，[`Text`](../com.aspose.html.dom/text/) 节点可能没有子节点，向此类节点添加子节点会导致抛出 [`DOMException`](../com.aspose.html.dom/domexception/)。 |
| [Notation](./notation/) | 表示在 DTD 中声明的符号（notation）。 |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction 表示“处理指令”，在 XML 中用于在文档文本中保留特定处理器的信息。 |
| [QualifiedName](./qualifiedname/) | 表示 HTML 合格名称。 |
| [ShadowRoot](./shadowroot/) | ShadowRoot 是影子树的根节点。 |
| [Text](./text/) | Text 接口继承自 CharacterData，并表示 Element 或 Attr 的文本内容（在 XML 中称为字符数据）。 |
| [TypeInfo](./typeinfo/) | TypeInfo 表示从 Element 或 Attr 节点引用的类型，该类型在与文档关联的模式中指定。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | 浏览上下文是呈现 [`Document`](../com.aspose.html.dom/document/) 对象给用户的环境。 |
| [IChildNode](./ichildnode/) | 定义了应由能够拥有父节点的 [`Node`](../com.aspose.html.dom/node/) 实现的 [`IChildNode`](../com.aspose.html.dom/ichildnode/) 接口。 |
| [IDOMImplementation](./idomimplementation/) | DOMImplementation 接口提供了多种方法，用于执行独立于文档对象模型任何特定实例的操作。 |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | 表示必须被所有支持系统事件处理的元素继承的接口。 |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | 定义了不是 [`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/) 的 [`IChildNode`](../com.aspose.html.dom/ichildnode/)。 |
| [INonElementParentNode](./inonelementparentnode/) | 定义了不是 Element 类型的 [`IParentNode`](../com.aspose.html.dom/iparentnode/)。 |
| [IParentNode](./iparentnode/) | 定义了由任何可能的父节点实现的 [`IParentNode`](../com.aspose.html.dom/iparentnode/) 接口。 |
| [IStorage](./istorage/) | Web Storage API 的此接口提供对特定域的会话或本地存储的访问。参见 Web Storage 规范: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | ShadowRoot 可以运行的模式。 |
