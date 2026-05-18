---
title: "HTMLTemplateElement 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.HTMLTemplateElement 类。模板元素"
type: docs

url: /zh/java/com.aspose.html/htmltemplateelement/
---
## HTMLTemplateElement class

template 元素

```java
public class HTMLTemplateElement : HTMLElement, IDocumentFragmentElement
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) 一个 NamedNodeMap，包含此节点的属性（如果它是 Element），否则为 null。 |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node 接口的只读 baseURI 属性返回包含该节点的文档的绝对基础 URL。 |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) 返回作为此元素子节点的元素节点的当前数量。如果此元素没有 nodeType 为 1 的子节点，则返回 0。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node 接口的只读 childNodes 属性返回给定元素的实时 [`NodeList`](../../com.aspose.html.collections/nodelist/)，其中第一个子节点的索引为 0。子节点包括元素、文本和注释。 |
| [getChildren](../../com.aspose.html.dom/element/children/) 返回当前元素的子元素。 |
| [getClassList](../../com.aspose.html.dom/element/classlist/) 返回一个实时的 DOMTokenList，其中包含从解析 "class" 属性获得的标记。 |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [getContent](../../com.aspose.html/htmltemplateelement/content/) 获取 [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) 的实例。 |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) [`Node`](../../com.aspose.html.dom/node/) 接口的只读 firstChild 属性返回节点在树中的第一个子节点，如果节点没有子节点则返回 null。 |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) 返回此元素的第一个子元素节点。如果此元素没有子元素，则返回 null。 |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) [`Node`](../../com.aspose.html.dom/node/) 接口的只读 lastChild 属性返回节点的最后一个子节点。如果其父节点是元素，则该子节点通常是元素节点、文本节点或注释节点。如果没有子元素，则返回 null。 |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) 返回此元素的最后一个子元素节点。如果此元素没有子元素，则为 null。 |
| [getLocalName](../../com.aspose.html.dom/element/localname/) 返回此节点的限定名称的本地部分。对于除 ELEMENT_NODE 和 ATTRIBUTE_NODE 之外的任何类型的节点以及使用 DOM Level 1 方法（如 Document.createElement()）创建的节点，此值始终为 null。 |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) 此节点的包 URI，若未指定则为 null。 |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) 返回此元素的下一个兄弟元素节点。如果此元素在文档树中没有后续的元素兄弟节点，则为 null。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) 只读的 `nextSibling` 属性（[`Node`](../../com.aspose.html.dom/node/) 接口）返回其父节点的 [`childNodes`](../../com.aspose.html.dom/node/childnodes/) 中紧随指定节点之后的节点；如果指定节点是父元素中的最后一个子节点，则返回 null。 |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) 此节点的名称，取决于其类型。 |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) 表示底层对象类型的代码。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | The `nodeValue` property of the [`Node`](../../com.aspose.html.dom/node/) interface returns or sets the value of the current node. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) 只读的 `ownerDocument` 属性（Node 接口）返回该节点的顶层文档对象。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) 只读的 `parentElement` 属性（[`Node`](../../com.aspose.html.dom/node/) 接口）返回 DOM 节点的父 [`Element`](../../com.aspose.html.dom/element/)，如果节点没有父节点或其父节点不是 DOM 元素，则返回 null。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) 只读的 `parentNode` 属性（Node 接口）返回 DOM 树中指定节点的父节点。 |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) 此节点的包前缀，若未指定则为 null。当其被定义为 null 时，设置它不会产生任何影响。 |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) 返回此元素的前一个兄弟元素节点。如果此元素在文档树中没有前面的元素兄弟节点，则为 null。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) 只读的 `previousSibling` 属性（[`Node`](../../com.aspose.html.dom/node/) 接口）返回其父节点的 [`childNodes`](../../com.aspose.html.dom/node/firstchild/) 列表中紧邻指定节点之前的节点；如果指定节点是该列表中的第一个，则返回 null。 |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) 返回存储在此元素上的 shadowRoot，如果它已关闭则为 null。 |
| [getStyle](../../com.aspose.html/htmlelement/style/) 表示一种样式属性，允许作者直接将样式信息应用于特定元素。 |
| [getTagName](../../com.aspose.html.dom/element/tagname/) 元素的名称。 |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new String is not empty or null, replaced by a single Text node containing the String this attribute is set to. |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |

## 方法

| 名称 | 描述 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() method of the [`EventTarget`](../../com.aspose.html.dom/eventtarget/) interface sets up a function that will be called whenever the specified event is delivered to the target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件被发送到目标时被调用。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件被发送到目标时被调用。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() 方法属于 Node 接口，用于将节点添加到指定父节点的子节点列表末尾。如果给定的子节点是文档中已存在的节点，appendChild() 会将其从当前位置移动到新位置（无需在将其追加到其他节点之前先从父节点中移除）。 |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | 创建 shadow root 并将其附加到当前元素。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() 方法属于 Node 接口，返回对调用该方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() 方法属于 Node 接口，返回对调用该方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 在指定的 [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) 上分派一个事件（同步），按适当顺序调用受影响的 EventListeners。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) 手动分派的事件。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | 执行由应用程序定义的任务，以释放、释放或重置非托管资源。 |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | 按名称检索属性值。 |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | 返回元素的属性名称，形式为字符串数组。如果元素没有属性，则返回空数组。 |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | 按名称检索属性节点。 |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | 按本地名称和包 URI 检索 Attr 节点。 |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | 按本地名称和包 URI 检索属性值。 |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | 返回包含所有位于 [`element`](../../com.aspose.html.dom/element/) 中且具有参数中指定的所有类的元素的 [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) 对象。 |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | 返回 [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) 对象，包含文档顺序中具有给定标签名的所有 [`elements`](../../com.aspose.html.dom/element/)。 |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | 返回 [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) 对象，包含文档顺序中具有给定本地名称和包 URI 字符串的所有 [`elements`](../../com.aspose.html.dom/element/)。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | 当此元素上指定了具有给定名称的属性或该属性具有默认值时返回 true，否则返回 false。 |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | 当此元素上指定了具有给定本地名称和包 URI 的属性或该属性具有默认值时返回 true，否则返回 false。 |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | 返回此节点（如果是元素）是否具有任何属性。 |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes() 方法属于 Node 接口，返回一个布尔值，指示给定的 [`Node`](../../com.aspose.html.dom/node/) 是否拥有子节点。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() 方法属于 Node 接口，将一个节点插入为指定父节点的子节点，位置在参考节点之前。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() 方法属于 Node 接口，接受一个包 URI 作为参数。如果该包是给定节点的默认包，则返回 true，否则返回 false。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | isEqualNode() 方法属于 [`Node`](../../com.aspose.html.dom/node/) 接口，用于测试两个节点是否相等。当两个节点具有相同的类型、定义特征（对于元素而言，包括其 ID、子节点数量等）、属性匹配等时，即视为相等。必须匹配的数据点集合取决于节点的类型。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() 方法属于 Node 接口，是 === 严格相等运算符的旧别名。即，它测试两个节点是否相同（换言之，它们是否引用同一对象）。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() 方法属于 Node 接口，接受前缀作为参数，并返回给定节点上与之关联的包 URI（若未找到则返回 null）。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() 方法属于 Node 接口，返回给定包 URI 的前缀字符串（如果存在），否则返回 null。当存在多个可能的前缀时，返回第一个前缀。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | 将此节点下子树全部深度的所有[`Text`](../../com.aspose.html.dom/text/)节点（包括属性节点）放入一种\"普通\"形式，其中仅有结构（例如[`elements`](../../com.aspose.html.dom/element/)、[`comments`](../../com.aspose.html.dom/comment/)、[`processing instructions`](../../com.aspose.html.dom/processinginstruction/)、[`CDATA sections`](../../com.aspose.html.dom/cdatasection/)、以及[`entity references`](../../com.aspose.html.dom/entityreference/)）将[`Text`](../../com.aspose.html.dom/text/)节点分隔开，即不存在相邻的 Text 节点或空的 Text 节点。此操作可用于确保文档的 DOM 视图与保存后重新加载时的视图相同，并且在需要依赖特定文档树结构的操作（例如 XPointer [XPointer] 查找）时非常有用。如果附加到[`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/)的[`DOMConfiguration`](../configuration/)对象的参数 \"normalize-characters\" 为 true，则此方法还会完全规范化 Text 节点的字符。 |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | 返回文档中匹配选择器的第一个元素 |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | 返回文档中匹配选择器的所有元素的 NodeList |
| [remove](../../com.aspose.html.dom/element/remove/)() | 移除此实例。 |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | 按名称移除属性。 |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | 移除指定的属性节点。 |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | 按本地名称和包 URI 移除属性。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node 接口的 removeChild() 方法从 DOM 中移除子节点并返回被移除的节点。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从中移除，它将不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从中移除，它将不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从中移除，它将不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 在子节点列表中用 newChild 替换子节点 oldChild，并返回 oldChild 节点。如果 newChild 是一个 [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) 对象，oldChild 将被所有 [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) 子节点替换，这些子节点按相同顺序插入。如果 newChild 已经在树中，则先将其移除。 |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | 添加新属性。如果元素中已经存在同名属性，则其值将更改为 value 参数的值。 |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | 添加新属性节点。如果元素中已经存在同名属性（nodeName），则它将被新属性替换。 |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | 添加新属性。如果元素中已经存在具有相同本地名称和包 URI 的属性，则它将被新属性替换。 |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | 添加新属性。如果元素上已经存在具有相同本地名称和包 URI 的属性，则其前缀将更改为 qualifiedName 的前缀部分，且其值将更改为 value 参数的值。 |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | 如果未提供 force，则"切换"qualifiedName：如果已存在则移除，未存在则添加。如果 force 为 true，则添加 qualifiedName；如果 force 为 false，则移除 qualifiedName。 |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | 如果未提供 force，则"切换"qualifiedName：如果已存在则移除，未存在则添加。如果 force 为 true，则添加 qualifiedName；如果 force 为 false，则移除 qualifiedName。 |
| [toString](../../com.aspose.html.dom/node/toString/)() | 返回表示此实例的字符串。 |

## 事件

| 名称 | 描述 |
| --- | --- |
| event [OnAbort](../../com.aspose.html/htmlelement/onabort/) | 获取或设置 OnAbort 事件的事件处理程序。 |
| event [OnBlur](../../com.aspose.html/htmlelement/onblur/) | 获取或设置 OnBlur 事件的事件处理程序。 |
| event [OnCancel](../../com.aspose.html/htmlelement/oncancel/) | 获取或设置 OnCancel 事件的事件处理程序。 |
| event [OnCanplay](../../com.aspose.html/htmlelement/oncanplay/) | 获取或设置 OnCanplay 事件的事件处理程序。 |
| event [OnCanPlayThrough](../../com.aspose.html/htmlelement/oncanplaythrough/) | 获取或设置 OnCanPlayThrough 事件的事件处理程序。 |
| event [OnChange](../../com.aspose.html/htmlelement/onchange/) | 获取或设置 OnChange 事件的事件处理程序。 |
| event [OnClick](../../com.aspose.html/htmlelement/onclick/) | 获取或设置 OnClick 事件的事件处理程序。 |
| event [OnCueChange](../../com.aspose.html/htmlelement/oncuechange/) | 获取或设置 OnCueChange 事件的事件处理程序。 |
| event [OnDblClick](../../com.aspose.html/htmlelement/ondblclick/) | 获取或设置 OnDblClick 事件的事件处理程序。 |
| event [OnDurationChange](../../com.aspose.html/htmlelement/ondurationchange/) | 获取或设置 OnDurationChange 事件的事件处理程序。 |
| event [OnEmptied](../../com.aspose.html/htmlelement/onemptied/) | 获取或设置 OnEmptied 事件的事件处理程序。 |
| event [OnEnded](../../com.aspose.html/htmlelement/onended/) | 获取或设置 OnEnded 事件的事件处理程序。 |
| event [OnError](../../com.aspose.html/htmlelement/onerror/) | 获取或设置 OnError 事件的事件处理程序。 |
| event [OnFocus](../../com.aspose.html/htmlelement/onfocus/) | 获取或设置 OnFocus 事件的事件处理程序。 |
| event [OnInput](../../com.aspose.html/htmlelement/oninput/) | 获取或设置 OnInput 事件的事件处理程序。 |
| event [OnInvalid](../../com.aspose.html/htmlelement/oninvalid/) | 获取或设置 OnInvalid 事件的事件处理程序。 |
| event [OnKeyDown](../../com.aspose.html/htmlelement/onkeydown/) | 获取或设置 OnKeyDown 事件的事件处理程序。 |
| event [OnKeyPress](../../com.aspose.html/htmlelement/onkeypress/) | 获取或设置 OnKeyPress 事件的事件处理程序。 |
| event [OnKeyUp](../../com.aspose.html/htmlelement/onkeyup/) | 获取或设置 OnKeyUp 事件的事件处理程序。 |
| event [OnLoad](../../com.aspose.html/htmlelement/onload/) | 获取或设置 OnLoad 事件的事件处理程序。 |
| event [OnLoadedData](../../com.aspose.html/htmlelement/onloadeddata/) | 获取或设置 OnLoadedData 事件的事件处理程序。 |
| event [OnLoadedMetadata](../../com.aspose.html/htmlelement/onloadedmetadata/) | 获取或设置 OnLoadedMetadata 事件的事件处理程序。 |
| event [OnLoadStart](../../com.aspose.html/htmlelement/onloadstart/) | 获取或设置 OnLoadStart 事件的事件处理程序。 |
| event [OnMouseDown](../../com.aspose.html/htmlelement/onmousedown/) | 获取或设置 OnMouseDown 事件的事件处理程序。 |
| event [OnMouseEnter](../../com.aspose.html/htmlelement/onmouseenter/) | 获取或设置 OnMouseEnter 事件的事件处理程序。 |
| event [OnMouseLeave](../../com.aspose.html/htmlelement/onmouseleave/) | 获取或设置 OnMouseLeave 事件的事件处理程序。 |
| event [OnMouseMove](../../com.aspose.html/htmlelement/onmousemove/) | 获取或设置 OnMouseMove 事件的事件处理程序。 |
| event [OnMouseOut](../../com.aspose.html/htmlelement/onmouseout/) | 获取或设置 OnMouseOut 事件的事件处理程序。 |
| event [OnMouseOver](../../com.aspose.html/htmlelement/onmouseover/) | 获取或设置 OnMouseOver 事件的事件处理程序。 |
| event [OnMouseUp](../../com.aspose.html/htmlelement/onmouseup/) | 获取或设置 OnMouseUp 事件的事件处理程序。 |
| event [OnMouseWheel](../../com.aspose.html/htmlelement/onmousewheel/) | 获取或设置 OnMouseWheel 事件的事件处理程序。 |
| event [OnPause](../../com.aspose.html/htmlelement/onpause/) | 获取或设置 OnPause 事件的事件处理程序。 |
| event [OnPlay](../../com.aspose.html/htmlelement/onplay/) | 获取或设置 OnPlay 事件的事件处理程序。 |
| event [OnPlaying](../../com.aspose.html/htmlelement/onplaying/) | 获取或设置 OnPlaying 事件的事件处理程序。 |
| event [OnProgress](../../com.aspose.html/htmlelement/onprogress/) | 获取或设置 OnProgress 事件的事件处理程序。 |
| event [OnRateChange](../../com.aspose.html/htmlelement/onratechange/) | 获取或设置 OnRateChange 事件的事件处理程序。 |
| event [OnReset](../../com.aspose.html/htmlelement/onreset/) | 获取或设置 OnReset 事件的事件处理程序。 |
| event [OnResize](../../com.aspose.html/htmlelement/onresize/) | 获取或设置 OnResize 事件的事件处理程序。 |
| event [OnScroll](../../com.aspose.html/htmlelement/onscroll/) | 获取或设置 OnScroll 事件的事件处理程序。 |
| event [OnSeeked](../../com.aspose.html/htmlelement/onseeked/) | 获取或设置 OnSeeked 事件的事件处理程序。 |
| event [OnSeeking](../../com.aspose.html/htmlelement/onseeking/) | 获取或设置 OnSeeking 事件的事件处理程序。 |
| event [OnSelect](../../com.aspose.html/htmlelement/onselect/) | 获取或设置 OnSelect 事件的事件处理程序。 |
| event [OnShow](../../com.aspose.html/htmlelement/onshow/) | 获取或设置 OnShow 事件的事件处理程序。 |
| event [OnStalled](../../com.aspose.html/htmlelement/onstalled/) | 获取或设置 OnStalled 事件的事件处理程序。 |
| event [OnSubmit](../../com.aspose.html/htmlelement/onsubmit/) | 获取或设置 OnSubmit 事件的事件处理程序。 |
| event [OnSuspend](../../com.aspose.html/htmlelement/onsuspend/) | 获取或设置 OnSuspend 事件的事件处理程序。 |
| event [OnTimeUpdate](../../com.aspose.html/htmlelement/ontimeupdate/) | 获取或设置 OnTimeUpdate 事件的事件处理程序。 |
| event [OnToggle](../../com.aspose.html/htmlelement/ontoggle/) | 获取或设置 OnToggle 事件的事件处理程序。 |
| event [OnVolumeChange](../../com.aspose.html/htmlelement/onvolumechange/) | 获取或设置 OnVolumeChange 事件的事件处理程序。 |
| event [OnWaiting](../../com.aspose.html/htmlelement/onwaiting/) | 获取或设置 OnWaiting 事件的事件处理程序。 |

### 另请参阅

* class [HTMLElement](../htmlelement/)
* interface [IDocumentFragmentElement](../idocumentfragmentelement/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
