---
title: "Node 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.Node 类。`Node` 接口是整个 Document Object Model 的主要数据类型。它表示文档树中的单个节点。虽然所有实现 `Node` 接口的对象都公开处理子节点的方法，但并非所有实现 `Node` 接口的对象都可能拥有子节点。例如，文本节点可能没有子节点，向此类节点添加子节点会导致抛出 `DOMException`。"
type: docs

url: /zh/java/com.aspose.html.dom/node/
---
## Node class

Node 接口是整个文档对象模型的主要数据类型。它表示文档树中的单个节点。虽然所有实现 Node 接口的对象都公开用于处理子节点的方法，但并非所有实现 Node 接口的对象都可能拥有子节点。例如，[`Text`](../text/) 节点可能没有子节点，向此类节点添加子节点会导致抛出 [`DOMException`](../domexception/)。

属性 [`nodeName`](./nodename/)、[`nodeValue`](./nodevalue/) 以及属性集合被包含作为一种机制，以在不向下转型到特定派生接口的情况下获取节点信息。如果对特定 [`nodeType`](./nodetype/) 没有明显的映射（例如，对 [`Element`](../element/) 的 nodeValue，或对 [`Comment`](../comment/) 的 attributes），则返回 null。请注意，专门的接口可能包含额外且更方便的机制来获取和设置相关信息。

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node 接口的只读 baseURI 属性返回包含该节点的文档的绝对基础 URL。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node 接口的只读 childNodes 属性返回给定元素的实时 [`NodeList`](../../com.aspose.html.collections/nodelist/)，其中第一个子节点的索引为 0。子节点包括元素、文本和注释。 |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) 只读的 firstChild 属性（`Node` 接口）返回树中节点的第一个子节点，如果节点没有子节点则返回 null。 |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) 只读的 lastChild 属性（`Node` 接口）返回节点的最后一个子节点。如果其父节点是元素，则子节点通常是元素节点、文本节点或注释节点。如果没有子元素则返回 null。 |
| [getLocalName](../../com.aspose.html.dom/node/localname/) 返回此节点的限定名称的本地部分。对于除 [`ELEMENT_NODE`](./element_node/) 和 [`ATTRIBUTE_NODE`](./attribute_node/) 之外的任何类型的节点，以及使用 DOM Level 1 方法（如 [`Document.createElement()`](../document/createelement/)）创建的节点，此值始终为 null。 |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI 只读属性返回元素的包 URI，如果元素不在包中，则为 null。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) 只读的 nextSibling 属性（`Node` 接口）返回其父节点的 [`childNodes`](./childnodes/) 中紧随指定节点之后的节点，如果指定节点是父元素中的最后一个子节点则返回 null。 |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) 只读的 nodeName 属性（Node）返回当前节点的名称，类型为 String。 |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) 表示底层对象类型的代码。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Node 接口的 nodeValue 属性返回或设置当前节点的值。 |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) 只读的 `ownerDocument` 属性（Node 接口）返回该节点的顶层文档对象。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) 只读的 parentElement 属性（`Node` 接口）返回 DOM 节点的父级 [`Element`](../element/)，如果节点没有父节点或其父节点不是 DOM 元素，则返回 null。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) 只读的 `parentNode` 属性（Node 接口）返回 DOM 树中指定节点的父节点。 |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix 只读属性返回指定元素的包前缀，如果未指定前缀，则为 null。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) 只读的 previousSibling 属性（`Node` 接口）返回其父节点的 [`childNodes`](./firstchild/) 列表中紧邻指定节点之前的节点，如果指定节点是列表中的第一个则返回 null。 |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | Node 接口的 textContent 属性表示节点及其后代的文本内容。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | `addEventListener()` 方法（属于 [`EventTarget `](../eventtarget/) 接口）设置一个函数，当指定事件传递到目标时将被调用。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件被发送到目标时被调用。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件被发送到目标时被调用。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() 方法属于 Node 接口，用于将节点添加到指定父节点的子节点列表末尾。如果给定的子节点是文档中已存在的节点，appendChild() 会将其从当前位置移动到新位置（无需在将其追加到其他节点之前先从父节点中移除）。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | cloneNode() 方法属于 Node 接口，返回对调用该方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | cloneNode() 方法属于 Node 接口，返回对调用该方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 在指定的 [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) 上分派一个事件（同步），按适当顺序调用受影响的 EventListeners。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) 手动分派的事件。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | 执行由应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node 接口的 hasChildNodes() 方法返回一个布尔值，指示给定的 `Node` 是否拥有子节点。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() 方法属于 Node 接口，将一个节点插入为指定父节点的子节点，位置在参考节点之前。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() 方法属于 Node 接口，接受一个包 URI 作为参数。如果该包是给定节点的默认包，则返回 true，否则返回 false。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Node 接口的 isEqualNode() 方法测试两个节点是否相等。当两个节点具有相同的类型、定义特征（对于元素来说，包括其 ID、子节点数量等）、属性匹配等时，即认为它们相等。必须匹配的具体数据点集合取决于节点的类型。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() 方法属于 Node 接口，是 === 严格相等运算符的旧别名。即，它测试两个节点是否相同（换言之，它们是否引用同一对象）。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() 方法属于 Node 接口，接受前缀作为参数，并返回给定节点上与之关联的包 URI（若未找到则返回 null）。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() 方法属于 Node 接口，返回给定包 URI 的前缀字符串（如果存在），否则返回 null。当存在多个可能的前缀时，返回第一个前缀。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | 将此节点下子树的全部深度中的所有 [`Text`](../text/) 节点（包括属性节点）转换为“正常”形式，即只有结构（例如 [`elements`](../element/)、[`comments`](../comment/)、[`processing instructions`](../processinginstruction/)、[`CDATA sections`](../cdatasection/)、[`entity references`](../entityreference/)）分隔 [`Text`](../text/) 节点，换句话说，不会出现相邻的 Text 节点或空的 Text 节点。这可用于确保文档的 DOM 视图与保存后重新加载时的视图相同，并在需要依赖特定文档树结构的操作（如 XPointer [XPointer] 查找）时非常有用。如果附加到 [`Node.ownerDocument`](./ownerdocument/) 的 [`DOMConfiguration`](../../com.aspose.html/configuration/) 对象的参数 "normalize-characters" 为 true，则此方法还会完全规范化 Text 节点的字符。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node 接口的 removeChild() 方法从 DOM 中移除子节点并返回被移除的节点。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从中移除，它将不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从中移除，它将不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从中移除，它将不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 在子节点列表中用 newChild 替换子节点 oldChild，并返回 oldChild 节点。如果 newChild 是一个 [`DocumentFragment`](../documentfragment/) 对象，则 oldChild 将被该 [`DocumentFragment`](../documentfragment/) 的所有子节点所替代，这些子节点按相同顺序插入。如果 newChild 已经在树中，则会先将其移除。 |
| [toString](../../com.aspose.html.dom/node/toString/)() | 返回表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | 一个 [`Attribute`](../attr/)，属于一个 [`Element`](../element/)。 |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | 一个 [`CDATASection`](../cdatasection/)，例如 &lt;!CDATA[[ … ]]&gt;。 |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | 一个 [`Comment`](../comment/) 节点，例如 &lt;!-- … --&gt;。 |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | 一个 [`DocumentFragment`](../documentfragment/) 节点。 |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | 一个 [`Document`](../document/) 节点。 |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | 一个 [`DocumentType`](../documenttype/) 节点，例如 &lt;!DOCTYPE html&gt;。 |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | 一个 [`Element`](../element/) 节点，如 &lt;p&gt; 或 &lt;div&gt;。 |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | 一个 [`Entity`](../entity/) 节点。 |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | 一个 [`EntityReference`](../entityreference/) 节点。 |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | 一个 [`Notation`](../notation/) 节点 |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | XML 文档的一个 [`ProcessingInstruction`](../processinginstruction/)，例如 &lt;?xml-stylesheet … ?&gt;。 |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | 实际位于 [`Element`](../element/) 或 [`Attr`](../attr/) 中的 [`Text`](../text/)。 |

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 另请参阅

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
