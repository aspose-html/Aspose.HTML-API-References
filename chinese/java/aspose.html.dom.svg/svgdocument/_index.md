---
title: "SVGDocument 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.svg.SVGDocument 类。SVGDocument 是 SVG 层次结构的根节点，包含全部内容。除了提供对层次结构的访问外，它还提供一些便利方法，用于从文档中获取特定信息集合。当 svg 元素作为另一个包的文档（例如在 XHTML 文档中）内联嵌入时，不会存在 SVGDocument 对象，而文档对象层次结构的根对象将是其他类型的 Document 对象，如 HTMLDocument。然而，当 XML 文档层次结构的根元素是 svg 元素时（例如查看独立的 SVG 文件，即 MIME 类型为 image/svgxml 的文件），SVGDocument 对象确实存在，并且它将是文档对象模型层次结构的根对象。"
type: docs

url: /zh/java/com.aspose.html.dom.svg/svgdocument/
---
## SVGDocument class

`SVGDocument` 是 SVG 层次结构的根，保存整个内容。除了提供对层次结构的访问外，它还提供了一些便利方法，用于从文档中获取特定信息集。当 ‘svg’ 元素以内联方式作为来自其他包的文档的组件嵌入时，例如当 ‘svg’ 元素以内联方式嵌入 XHTML 文档 [XHTML] 中时，将不存在 SVGDocument 对象；相反，文档对象层次结构中的根对象将是其他类型的 Document 对象，例如 HTMLDocument 对象。然而，当 XML 文档层次结构的根元素是 ‘svg’ 元素时（例如查看独立的 SVG 文件，即 MIME 类型为 \"image/svg+xml\" 的文件），SVGDocument 对象确实会存在。在这种情况下，SVGDocument 对象将是文档对象模型层次结构的根对象。

```java
public class SVGDocument : Document, IDocumentCSS
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGDocument](svgdocument/#constructor)() | 初始化 `SVGDocument` 类的新实例。 |
| [SVGDocument](svgdocument/#constructor_1)(Configuration) | 初始化 `SVGDocument` 类的新实例。 |
| [SVGDocument](svgdocument/#constructor_2)(RequestMessage) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_10)(String) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_4)(Url) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_3)(RequestMessage, Configuration) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_8)(Stream, String) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。文档加载从流的当前位置开始。 |
| [SVGDocument](svgdocument/#constructor_6)(Stream, Url) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。文档加载从流的当前位置开始。 |
| [SVGDocument](svgdocument/#constructor_11)(String, Configuration) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_14)(String, String) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_12)(String, Url) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_5)(Url, Configuration) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_9)(Stream, String, Configuration) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。文档加载从流的当前位置开始。 |
| [SVGDocument](svgdocument/#constructor_7)(Stream, Url, Configuration) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。文档加载从流的当前位置开始。 |
| [SVGDocument](svgdocument/#constructor_15)(String, String, Configuration) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_13)(String, Url, Configuration) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。要异步加载文档，请使用方法 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 或其重载。或者通过在 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) 此节点的绝对基础 URI，如果实现无法获取绝对 URI，则为 null。 |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) 获取文档的编码。 |
| [getCharset](../../com.aspose.html.dom/document/charset/) 获取文档的编码。 |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) 返回作为此元素子节点的元素节点当前数量。如果此元素没有 nodeType 为 1 的子节点，则返回 0。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node 接口的只读 childNodes 属性返回给定元素的实时 [`NodeList`](../../com.aspose.html.collections/nodelist/)，其中第一个子节点的索引为 0。子节点包括元素、文本和注释。 |
| [getChildren](../../com.aspose.html.dom/document/children/) 返回子元素。 |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) 获取文档内容类型。 |
| [getContext](../../com.aspose.html.dom/document/context/) 获取当前浏览上下文。 |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) Document 接口的 defaultView IDL 属性，在获取时，必须返回此文档的浏览上下文的 WindowProxy 对象（如果该文档关联了浏览上下文），否则返回 null。 |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) 与此文档关联的文档类型声明（DOCTYPE）。 |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) 这是一个便利属性，允许直接访问作为文档元素的子节点。 |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) 文档的位置；如果未定义或文档是使用 DOMImplementation.createDocument 创建的，则为 null。 |
| [getDomain](../../com.aspose.html.dom.svg/svgdocument/domain/) 提供文档的服务器的域名；如果无法通过域名识别服务器，则为 null 字符串。 |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) [`Node`](../../com.aspose.html.dom/node/) 接口的只读 firstChild 属性返回节点在树中的第一个子节点，如果节点没有子节点则返回 null。 |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) 返回此元素的第一个子元素节点；如果此元素没有子元素，则为 null。 |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) 处理此文档的 DOMImplementation 对象。 |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) 获取文档的编码。 |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) [`Node`](../../com.aspose.html.dom/node/) 接口的只读 lastChild 属性返回节点的最后一个子节点。如果其父节点是元素，则子节点通常是元素节点、文本节点或注释节点。如果没有子元素，则返回 null。 |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) 返回此元素的最后一个子元素节点；如果此元素没有子元素，则为 null。 |
| [getLocalName](../../com.aspose.html.dom/node/localname/) 返回此节点的合格名称的本地部分。对于除 [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) 和 [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) 之外的任何类型的节点，以及使用 DOM Level 1 方法创建的节点，例如 [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/)，此值始终为 null。 |
| [getLocation](../../com.aspose.html.dom/document/location/) 文档的位置。 |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI 只读属性返回元素的包 URI；如果元素不在任何包中，则为 null。 |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) 返回此元素的下一个兄弟元素节点；如果在文档树中此元素后没有元素兄弟节点，则为 null。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) 只读的 nextSibling 属性（[`Node`](../../com.aspose.html.dom/node/) 接口）返回紧随指定节点之后的节点，位于其父节点的 [`childNodes`](../../com.aspose.html.dom/node/childnodes/) 中；如果指定节点是父元素的最后一个子节点，则返回 null。 |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) 根据节点类型，此节点的名称。 |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) 表示底层对象类型的代码。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | [`Node `](../../com.aspose.html.dom/node/) 接口的 nodeValue 属性返回或设置当前节点的值。 |
| [getOrigin](../../com.aspose.html.dom/document/origin/) 获取文档的来源。 |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) 获取所有者文档。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) 只读的 parentElement 属性（[`Node`](../../com.aspose.html.dom/node/) 接口）返回 DOM 节点的父 [`Element`](../../com.aspose.html.dom/element/)，如果节点没有父节点或其父节点不是 DOM Element，则为 null。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) 只读的 parentNode 属性（Node 接口）返回 DOM 树中指定节点的父节点。 |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix 只读属性返回指定元素的包前缀；如果未指定前缀，则为 null。 |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) 返回此元素的上一个兄弟元素节点；如果在文档树中此元素前没有元素兄弟节点，则为 null。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) 只读的 previousSibling 属性（[`Node`](../../com.aspose.html.dom/node/) 接口）返回其父节点的 [`childNodes`](../../com.aspose.html.dom/node/firstchild/) 列表中紧挨在指定节点之前的节点，如果指定节点是列表中的第一个，则返回 null。 |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) 返回文档的就绪状态。当文档正在加载时为 "loading"，解析完成但子资源仍在加载时为 "interactive"，加载完成后为 "complete"。 |
| [getReferrer](../../com.aspose.html.dom.svg/svgdocument/referrer/) 返回链接到此页面的页面的 URI。如果用户直接导航到该页面（未通过链接，例如通过书签），则该值为空字符串。 |
| [getRootElement](../../com.aspose.html.dom.svg/svgdocument/rootelement/) 文档层次结构中的根 ‘svg’ 元素。 |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) 包含文档中所有显式链接或嵌入的样式表的列表。对于 HTML 文档，这包括通过 HTML LINK 元素包含的外部样式表以及内联 STYLE 元素。 |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | 接口 [`Node`](../../com.aspose.html.dom/node/) 的 textContent 属性表示节点及其后代的文本内容。 |
| [getTitle](../../com.aspose.html.dom.svg/svgdocument/title/) 文档的标题，由 ‘svg’ 根元素的 ‘title’ 子元素指定（例如，这里是标题……） |
| [getURL](../../com.aspose.html.dom.svg/svgdocument/url/) 文档的完整 URI。 |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## 方法

| 名称 | 描述 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | `EventTarget ` 接口的 addEventListener() 方法设置一个函数，该函数将在指定事件被分发到目标时被调用。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件传递到目标时被调用。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() 方法属于 [EventTarget ](T:com.aspose.html.dom.EventTarget) 接口，用于设置一个函数，该函数将在指定事件传递到目标时被调用。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() 方法属于 Node 接口，用于将节点添加到指定父节点的子节点列表末尾。如果给定的子节点是文档中已有节点的引用，appendChild() 会将其从当前位置移动到新位置（在将节点追加到其他节点之前，无需先从其父节点中移除）。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() 方法属于 Node 接口，返回调用该方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() 方法属于 Node 接口，返回调用该方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。 |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Document.createAttribute() 方法创建一个新的属性节点并返回它。该对象创建了一个实现了 [`Attr`](../../com.aspose.html.dom/attr/) 接口的节点。DOM 不强制规定可以以这种方式添加到特定元素的属性类型。 |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Document.createAttribute() 方法创建一个新的属性节点并返回它。该对象创建了一个实现了 [Attr](T:com.aspose.html.dom.Attr) 接口的节点。DOM 不强制规定可以以这种方式添加到特定元素的属性类型。 |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | 创建一个值为指定字符串的 [`CDATASection`](../../com.aspose.html.dom/cdatasection/) 节点。 |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | 根据指定的字符串创建一个 [`Comment`](../../com.aspose.html.dom/comment/) 节点。 |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | 创建一个新的空 [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/)，可以向其中添加 DOM 节点以构建离屏 DOM 树。 |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | 该方法返回一个 [`DocumentType`](../../com.aspose.html.dom/documenttype/) 对象，可在文档创建时与 DOMImplementation.createDocument 一起使用，或通过 Node.insertBefore()、Node.replaceChild() 等方法放入文档中。 |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | 在 HTML 文档中，document.createElement() 方法创建由 tagName 指定的 HTML 元素；如果 tagName 未被识别，则创建一个 [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/)。 |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | 创建具有给定限定名称和包 URI 的元素。 |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | 创建一个 EntityReference 对象。此外，如果已知被引用的实体，则 EntityReference 节点的子列表将与相应的 Entity 节点相同。 |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | 创建一个实现支持的类型的 [`Event`](../../com.aspose.html.dom.events/event/)。 |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | 创建一个已解析包的 XPath 表达式。此功能在表达式将在应用程序中重复使用时很有用，因为它可以将表达式字符串编译为更高效的内部形式，并预先解析表达式中出现的所有包前缀。 |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node) | 在以指定节点为根的子树上创建一个新的 NodeIterator。 |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long) | 在以指定节点为根的子树上创建一个新的 NodeIterator。 |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | 在以指定节点为根的子树上创建一个新的 NodeIterator。 |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | 适配任意 DOM 节点以解析包，使得 XPath 表达式可以相对于其在文档中出现的节点上下文轻松求值。此适配器的工作方式类似于 DOM Level 3 方法 `lookupNamespaceURI`，在解析给定前缀的 packageURI 时使用节点层次结构中当前可用的信息，并且还能正确解析隐式的 xml 前缀。 |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | 根据指定的名称和数据字符串创建一个 ProcessingInstruction 节点。 |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | 根据指定的字符串创建一个 Text 节点。 |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node) | 在以指定节点为根的子树上创建一个新的 TreeWalker。 |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long) | 在以指定节点为根的子树上创建一个新的 TreeWalker。 |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | 在以指定节点为根的子树上创建一个新的 TreeWalker。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 在指定的 [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) 上分派 Event（同步），按适当顺序调用受影响的 EventListeners。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) 手动分派的事件。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | 执行由应用程序定义的任务，以释放、解除占用或重置非托管资源。 |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | 求值一个 XPath 表达式字符串，并在可能的情况下返回指定类型的结果。 |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Document 方法 getElementById() 返回一个 [`Element`](../../com.aspose.html.dom/element/) 对象，表示其 id 属性与指定字符串匹配的元素。由于元素 ID（如果指定）必须唯一，它们是快速访问特定元素的有用方式。 |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | [`Document`](../../com.aspose.html.dom/document/) 接口的 getElementsByClassName 方法返回一个类似数组的对象，包含所有具有给定类名的子元素。 |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | [`Document`](../../com.aspose.html.dom/document/) 接口的 getElementsByTagName 方法返回一个 [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/)，其中包含具有给定标签名的元素。 |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | 返回属于给定包的、具有指定标签名的元素列表。搜索范围包括整个文档，包括根节点。 |
| [getOverrideStyle](../../com.aspose.html.dom.svg/svgdocument/getoverridestyle/)(Element, String) | 此方法用于检索指定元素和指定伪元素的覆盖样式声明。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes() 方法属于 Node 接口，返回一个布尔值，指示给定的 [`Node`](../../com.aspose.html.dom/node/) 是否具有子节点。 |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | 从另一个文档导入节点到此文档，而不更改或删除原始文档中的源节点；此方法会创建源节点的新副本。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() 方法属于 Node 接口，在指定的父节点中，将一个节点插入到参考节点之前作为子节点。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() 方法属于 Node 接口，接受一个包 URI 作为参数。如果该包是给定节点的默认包，则返回 true，否则返回 false。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | [`Node`](../../com.aspose.html.dom/node/) 接口的 isEqualNode() 方法测试两个节点是否相等。当两个节点具有相同的类型、定义特征（对于元素而言，包括其 ID、子节点数量等）、属性匹配等时，它们被视为相等。必须匹配的数据点集合取决于节点的类型。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Node 接口的 isSameNode() 方法是 === 严格相等运算符的旧别名。即，它测试两个节点是否相同（换句话说，它们是否引用同一个对象）。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Node 接口的 lookupNamespaceURI() 方法接受前缀作为参数，并在给定节点上返回与之关联的包 URI（如果找到），否则返回 null。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Node 接口的 lookupPrefix() 方法返回包含给定包 URI 前缀的字符串（如果存在），否则返回 null。当存在多个前缀时，返回第一个前缀。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(RequestMessage) | 根据指定的请求对象加载文档，替换之前的内容。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String) | 将位于指定统一资源定位符（URL）的文档加载到当前实例中，替换先前的内容。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Url) | 将位于指定统一资源定位符（URL）的文档加载到当前实例中，替换先前的内容。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, String) | 从指定内容加载文档，并使用 baseUri 解析相对资源，替换先前的内容。文档加载从流中的当前位置开始。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, Url) | 从指定内容加载文档，并使用 baseUri 解析相对资源，替换先前的内容。文档加载从流中的当前位置开始。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, String) | 从指定内容加载文档，并使用 baseUri 解析相对资源，替换先前的内容。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, Url) | 从指定内容加载文档，并使用 baseUri 解析相对资源，替换先前的内容。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | 将此 Node 下子树的全部深度中的所有 [`Text`](../../com.aspose.html.dom/text/) 节点（包括属性节点）转换为“正常”形式，使只有结构（例如 [`elements`](../../com.aspose.html.dom/element/)、[`comments`](../../com.aspose.html.dom/comment/)、[`processing instructions`](../../com.aspose.html.dom/processinginstruction/)、[`CDATA sections`](../../com.aspose.html.dom/cdatasection/)、[`entity references`](../../com.aspose.html.dom/entityreference/)）将 [`Text`](../../com.aspose.html.dom/text/) 节点分隔，即不存在相邻的 Text 节点或空的 Text 节点。这可用于确保文档的 DOM 视图与保存后重新加载时相同，并在依赖特定文档树结构的操作（如 XPointer [XPointer] 查找）时非常有用。如果附加到 [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) 的 [`DOMConfiguration`](../../com.aspose.html/configuration/) 对象的参数 "normalize-characters" 为 true，则此方法还会完全规范化 Text 节点的字符。 |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | 返回文档中匹配选择器的第一个 Element。 |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | 返回文档中匹配选择器的所有 Elements 的 NodeList。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node 接口的 removeChild() 方法从 DOM 中移除子节点并返回被移除的节点。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | 此方法允许从事件目标中移除 event listeners。如果在处理事件时将其从中移除，则不会被当前操作触发。event listeners 在被移除后永远不会被调用。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | 此方法允许从事件目标中移除 event listeners。如果在处理事件时将其从中移除，则不会被当前操作触发。event listeners 在被移除后永远不会被调用。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | 此方法允许从事件目标中移除 event listeners。如果在处理事件时将其从中移除，则不会被当前操作触发。event listeners 在被移除后永远不会被调用。 |
| [renderTo](../../com.aspose.html.dom.svg/svgdocument/renderto/)(IDevice) | 此方法用于将当前文档的内容打印到指定设备。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 在子节点列表中用 newChild 替换子节点 oldChild，并返回 oldChild 节点。如果 newChild 是一个 [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) 对象，则 oldChild 将被该 [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) 的所有子节点替换，这些子节点按相同顺序插入。如果 newChild 已经在树中，则会先将其移除。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save)(ResourceHandler) | 使用 [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_6)(String) | 将文档保存到由 `path` 指定的本地文件。文档中使用的所有资源将保存到相邻文件夹中，文件夹名称将构建为：output_file_name + "_files"。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_3)(Url) | 将文档保存到由 `url` 指定的本地文件。文档中使用的所有资源将保存到相邻文件夹中，文件夹名称将构建为：output_file_name + "_files"。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_1)(ResourceHandler, SVGSaveFormat) | 使用 [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_2)(ResourceHandler, SVGSaveOptions) | 使用 [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_7)(String, SVGSaveFormat) | 将文档保存到由 `path` 指定的本地文件。文档中使用的所有资源将保存到相邻文件夹中，文件夹名称将构建为：output_file_name + "_files"。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_8)(String, SVGSaveOptions) | 将文档保存到由 `path` 指定的本地文件。文档中使用的所有资源将保存到相邻文件夹中，文件夹名称将构建为：output_file_name + "_files"。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_4)(Url, SVGSaveFormat) | 将文档保存到由 `url` 指定的本地文件。文档中使用的所有资源将保存到相邻文件夹中，文件夹名称将构建为：output_file_name + "_files"。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_5)(Url, SVGSaveOptions) | 将文档保存到由 `url` 指定的本地文件。文档中使用的所有资源将保存到相邻文件夹中，文件夹名称将构建为：output_file_name + "_files"。 |
| [toString](../../com.aspose.html.dom/node/toString/)() | 返回表示此实例的字符串。 |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | 将一段文本字符串写入由 open() 打开的文档流。请注意，该函数生成的文档不一定受 DTD 驱动，因此在文档上下文中可能产生无效结果。 |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | 将一段文本字符串后跟换行符写入由 open() 打开的文档流。请注意，该函数生成的文档不一定受 DTD 驱动，因此在文档上下文中可能产生无效结果。 |

## 事件

| 名称 | 描述 |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | 获取或设置 OnAbort 事件的事件处理程序。 |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | 获取或设置 OnBlur 事件的事件处理程序。 |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | 获取或设置 OnCancel 事件的事件处理程序。 |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | 获取或设置 OnCanplay 事件的事件处理程序。 |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | 获取或设置 OnCanPlayThrough 事件的事件处理程序。 |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | 获取或设置 OnChange 事件的事件处理程序。 |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | 获取或设置 OnClick 事件的事件处理程序。 |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | 获取或设置 OnCueChange 事件的事件处理程序。 |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | 获取或设置 OnDblClick 事件的事件处理程序。 |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | 获取或设置 OnDurationChange 事件的事件处理程序。 |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | 获取或设置 OnEmptied 事件的事件处理程序。 |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | 获取或设置 OnEnded 事件的事件处理程序。 |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | 获取或设置 OnError 事件的事件处理程序。 |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | 获取或设置 OnFocus 事件的事件处理程序。 |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | 获取或设置 OnInput 事件的事件处理程序。 |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | 获取或设置 OnInvalid 事件的事件处理程序。 |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | 获取或设置 OnKeyDown 事件的事件处理程序。 |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | 获取或设置 OnKeyPress 事件的事件处理程序。 |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | 获取或设置 OnKeyUp 事件的事件处理程序。 |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | 获取或设置 OnLoad 事件的事件处理程序。 |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | 获取或设置 OnLoadedData 事件的事件处理程序。 |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | 获取或设置 OnLoadedMetadata 事件的事件处理程序。 |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | 获取或设置 OnLoadStart 事件的事件处理程序。 |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | 获取或设置 OnMouseDown 事件的事件处理程序。 |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | 获取或设置 OnMouseEnter 事件的事件处理程序。 |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | 获取或设置 OnMouseLeave 事件的事件处理程序。 |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | 获取或设置 OnMouseMove 事件的事件处理程序。 |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | 获取或设置 OnMouseOut 事件的事件处理程序。 |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | 获取或设置 OnMouseOver 事件的事件处理程序。 |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | 获取或设置 OnMouseUp 事件的事件处理程序。 |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | 获取或设置 OnMouseWheel 事件的事件处理程序。 |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | 获取或设置 OnPause 事件的事件处理程序。 |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | 获取或设置 OnPlay 事件的事件处理程序。 |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | 获取或设置 OnPlaying 事件的事件处理程序。 |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | 获取或设置 OnProgress 事件的事件处理程序。 |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | 获取或设置 OnRateChange 事件的事件处理程序。 |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | 获取或设置 OnReadyStateChange 事件的事件处理程序。 |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | 获取或设置 OnReset 事件的事件处理程序。 |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | 获取或设置 OnResize 事件的事件处理程序。 |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | 获取或设置 OnScroll 事件的事件处理程序。 |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | 获取或设置 OnSeeked 事件的事件处理程序。 |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | 获取或设置 OnSeeking 事件的事件处理程序。 |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | 获取或设置 OnSelect 事件的事件处理程序。 |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | 获取或设置 OnShow 事件的事件处理程序。 |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | 获取或设置 OnStalled 事件的事件处理程序。 |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | 获取或设置 OnSubmit 事件的事件处理程序。 |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | 获取或设置 OnSuspend 事件的事件处理程序。 |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | 获取或设置 OnTimeUpdate 事件的事件处理程序。 |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | 获取或设置 OnToggle 事件的事件处理程序。 |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | 获取或设置 OnVolumeChange 事件的事件处理程序。 |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | 获取或设置 OnWaiting 事件的事件处理程序。 |

### 另请参见

* class [Document](../../com.aspose.html.dom/document/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
