---
title: "ProcessingInstruction 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.ProcessingInstruction 类。ProcessingInstruction 表示在 XML 中使用的处理指令，用于在文档文本中保留特定处理器的信息"
type: docs

url: /zh/java/com.aspose.html.dom/processinginstruction/
---
## ProcessingInstruction class

ProcessingInstruction 表示“处理指令”，在 XML 中用于在文档文本中保留特定处理器的信息。

```java
public class ProcessingInstruction : CharacterData
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node 接口的只读 baseURI 属性返回包含该节点的文档的绝对基础 URL。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node 接口的只读 childNodes 属性返回给定元素的实时 [`NodeList`](../../com.aspose.html.collections/nodelist/)，其中第一个子节点的索引为 0。子节点包括元素、文本和注释。 |
| [data](../../com.aspose.html.dom/characterdata/data/) { get; set; } | 实现此接口的节点的字符数据。 |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) 只读的 firstChild 属性（属于 [`Node`](../node/) 接口）返回树中节点的第一个子节点，如果节点没有子节点则返回 null。 |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) 只读的 lastChild 属性（属于 [`Node`](../node/) 接口）返回节点的最后一个子节点。如果其父节点是元素，则子节点通常是元素节点、文本节点或注释节点。如果没有子元素则返回 null。 |
| [getLength](../../com.aspose.html.dom/characterdata/length/) 通过 data 和下面的 subStringData 方法可用的 16 位单元的数量。该值可能为零，即 CharacterData 节点可能为空。 |
| [getLocalName](../../com.aspose.html.dom/node/localname/) 返回此节点的限定名称的本地部分。对于除 [`ELEMENT_NODE`](../node/element_node/) 和 [`ATTRIBUTE_NODE`](../node/attribute_node/) 之外的任何类型的节点，以及使用 DOM Level 1 方法（如 [`Document.createElement()`](../document/createelement/)）创建的节点，此值始终为 null。 |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI 只读属性返回元素的包 URI；如果元素不在任何包中，则为 null。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) 只读的 nextSibling 属性（属于 [`Node`](../node/) 接口）返回其父节点的 [`childNodes`](../node/childnodes/) 中紧随指定节点之后的节点，如果指定节点是父元素的最后一个子节点则返回 null。 |
| [getNodeName](../../com.aspose.html.dom/processinginstruction/nodename/) 根据其类型，此节点的名称。 |
| [getNodeType](../../com.aspose.html.dom/processinginstruction/nodetype/) 表示底层对象类型的代码。 |
| [nodeValue](../../com.aspose.html.dom/processinginstruction/nodevalue/) { get; set; } | 此节点的值，取决于其类型。 |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) 只读的 ownerDocument 属性（Node 接口）返回该节点的顶层文档对象。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) 只读的 parentElement 属性（属于 [`Node`](../node/) 接口）返回 DOM 节点的父级 [`Element`](../element/)，如果节点没有父节点或其父节点不是 DOM Element，则返回 null。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) 只读的 parentNode 属性（Node 接口）返回 DOM 树中指定节点的父节点。 |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix 只读属性返回指定元素的包前缀；如果未指定前缀，则为 null。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) 只读的 previousSibling 属性（属于 [`Node`](../node/) 接口）返回其父节点的 [`childNodes`](../node/firstchild/) 列表中紧前于指定节点的节点，如果指定节点是列表中的第一个则返回 null。 |
| [getTarget](../../com.aspose.html.dom/processinginstruction/target/) 此处理指令的目标。 |
| [textContent](../../com.aspose.html.dom/processinginstruction/textcontent/) { get; set; } | 此属性返回该节点及其后代的文本内容。当其被定义为 null 时，设置该属性没有任何效果。设置时，节点可能拥有的所有子节点将被移除，如果新的字符串既不为空也不为 null，则会被一个包含该字符串的单一 Text 节点所取代。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | [`EventTarget `](../eventtarget/) 接口的 addEventListener() 方法设置一个函数，该函数将在指定事件传递给目标时被调用。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件传递到目标时被调用。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件传递到目标时被调用。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() 方法属于 Node 接口，用于将节点添加到指定父节点的子节点列表末尾。如果给定的子节点是文档中已有节点的引用，appendChild() 会将其从当前位置移动到新位置（在将节点追加到其他节点之前，无需先从其父节点中移除）。 |
| [appendData](../../com.aspose.html.dom/characterdata/appenddata/)(String) | 将字符串追加到节点字符数据的末尾。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() 方法属于 Node 接口，返回调用该方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() 方法属于 Node 接口，返回调用该方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。 |
| [deleteData](../../com.aspose.html.dom/characterdata/deletedata/)(int, int) | 从节点中移除一段 16 位单元。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 在指定的 [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) 上分派 Event（同步），按适当顺序调用受影响的 EventListeners。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) 手动分派的事件。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | 执行由应用程序定义的任务，以释放、解除占用或重置非托管资源。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node 接口的 hasChildNodes() 方法返回一个布尔值，指示给定的 [`Node`](../node/) 是否具有子节点。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() 方法属于 Node 接口，在指定的父节点中，将一个节点插入到参考节点之前作为子节点。 |
| [insertData](../../com.aspose.html.dom/characterdata/insertdata/)(int, String) | 在指定的 16 位单元偏移处插入字符串。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() 方法属于 Node 接口，接受一个包 URI 作为参数。如果该包是给定节点的默认包，则返回 true，否则返回 false。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | [`Node`](../node/) 接口的 isEqualNode() 方法测试两个节点是否相等。当两个节点具有相同的类型、定义特征（对于元素来说，包括其 ID、子节点数量等）、属性匹配等时，即视为相等。必须匹配的数据点集合会根据节点的类型而有所不同。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Node 接口的 isSameNode() 方法是 === 严格相等运算符的旧别名。即，它测试两个节点是否相同（换句话说，它们是否引用同一个对象）。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Node 接口的 lookupNamespaceURI() 方法接受前缀作为参数，并在给定节点上返回与之关联的包 URI（如果找到），否则返回 null。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Node 接口的 lookupPrefix() 方法返回包含给定包 URI 前缀的字符串（如果存在），否则返回 null。当存在多个前缀时，返回第一个前缀。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | 将此节点下子树的全部深度中的所有[`Text`](../text/)节点（包括属性节点）放入“普通”形式，其中仅有结构（例如[`elements`](../element/)、[`comments`](../comment/)、`processing instructions`、[`CDATA sections`](../cdatasection/)和[`entity references`](../entityreference/)）将[`Text`](../text/)节点分隔，即不存在相邻的 Text 节点或空的 Text 节点。此操作可用于确保文档的 DOM 视图与保存后重新加载时相同，并在需要依赖特定文档树结构的操作（如 XPointer [XPointer] 查找）时非常有用。如果附加到[`Node.ownerDocument`](../node/ownerdocument/)的[`DOMConfiguration`](../../com.aspose.html/configuration/)对象的参数 "normalize-characters" 为 true，则此方法还会完全规范化 Text 节点的字符。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node 接口的 removeChild() 方法从 DOM 中移除子节点并返回被移除的节点。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | 此方法允许从事件目标中移除 event listeners。如果在处理事件时将其从中移除，则不会被当前操作触发。event listeners 在被移除后永远不会被调用。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | 此方法允许从事件目标中移除 event listeners。如果在处理事件时将其从中移除，则不会被当前操作触发。event listeners 在被移除后永远不会被调用。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | 此方法允许从事件目标中移除 event listeners。如果在处理事件时将其从中移除，则不会被当前操作触发。event listeners 在被移除后永远不会被调用。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 在子节点列表中用 newChild 替换子节点 oldChild，并返回 oldChild 节点。如果 newChild 是一个 [`DocumentFragment`](../documentfragment/) 对象，则 oldChild 将被该 [`DocumentFragment`](../documentfragment/) 的所有子节点所替代，这些子节点按相同顺序插入。如果 newChild 已经在树中，则先将其移除。 |
| [replaceData](../../com.aspose.html.dom/characterdata/replacedata/)(int, int, String) | 用指定的字符串替换从指定的 16 位单元偏移开始的字符。 |
| [subStringData](../../com.aspose.html.dom/characterdata/subStringdata/)(int, int) | 从节点中提取一段数据。 |
| [toString](../../com.aspose.html.dom/characterdata/toString/)() | 返回表示此实例的字符串。 |

### 另请参见

* class [CharacterData](../characterdata/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
