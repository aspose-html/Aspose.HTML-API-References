---
title: "Node 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.Node 클래스. Node 인터페이스는 전체 Document Object Model의 기본 데이터 유형이며, 문서 트리에서 단일 노드를 나타냅니다. Node 인터페이스를 구현하는 모든 객체가 자식 노드를 다루는 메서드를 제공하지만, 모든 객체가 자식을 가질 수 있는 것은 아닙니다. 예를 들어 Text 노드는 자식이 없으며, 이러한 노드에 자식을 추가하면 DOMException이 발생합니다."
type: docs

url: /ko/java/com.aspose.html.dom/node/
---
## Node class

Node 인터페이스는 전체 문서 객체 모델(DOM)의 기본 데이터 유형입니다. 이는 문서 트리에서 단일 노드를 나타냅니다. Node 인터페이스를 구현하는 모든 객체는 자식 처리를 위한 메서드를 제공하지만, 모든 객체가 자식을 가질 수 있는 것은 아닙니다. 예를 들어, [`Text`](../text/) 노드는 자식이 없을 수 있으며, 이러한 노드에 자식을 추가하면 [`DOMException`](../domexception/)이 발생합니다.

속성 [`nodeName`](./nodename/), [`nodeValue`](./nodevalue/) 및 속성들은 특정 파생 인터페이스로 캐스팅하지 않고도 노드 정보를 얻기 위한 메커니즘으로 포함됩니다. 특정 [`nodeType`](./nodetype/)에 대해 이러한 속성에 명확한 매핑이 없는 경우(예: [`Element`](../element/)의 nodeValue 또는 [`Comment`](../comment/)의 attributes), null을 반환합니다. 특수화된 인터페이스는 관련 정보를 가져오고 설정하기 위한 추가적이고 더 편리한 메커니즘을 포함할 수 있다는 점에 유의하십시오.

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node 인터페이스의 읽기 전용 baseURI 속성은 노드를 포함하는 문서의 절대 기본 URL을 반환합니다. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node 인터페이스의 읽기 전용 childNodes 속성은 주어진 요소의 자식 노드에 대한 실시간 [`NodeList`](../../com.aspose.html.collections/nodelist/)을 반환하며, 첫 번째 자식 노드의 인덱스는 0입니다. 자식 노드에는 요소, 텍스트 및 주석이 포함됩니다. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) `Node` 인터페이스의 읽기 전용 firstChild 속성은 트리에서 해당 노드의 첫 번째 자식을 반환하며, 자식이 없으면 null을 반환합니다. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) `Node` 인터페이스의 읽기 전용 lastChild 속성은 노드의 마지막 자식을 반환합니다. 부모가 요소인 경우, 자식은 일반적으로 요소 노드, 텍스트 노드 또는 주석 노드입니다. 자식 요소가 없으면 null을 반환합니다. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) 이 메서드는 이 노드의 한정된 이름 중 로컬 부분을 반환합니다. [`ELEMENT_NODE`](./element_node/) 및 [`ATTRIBUTE_NODE`](./attribute_node/)이 아닌 모든 유형의 노드와 DOM Level 1 메서드(예: [`Document.createElement()`](../document/createelement/))로 생성된 노드에 대해서는 항상 null을 반환합니다. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI 읽기 전용 속성은 요소의 패키지 URI를 반환하며, 요소가 패키지에 속하지 않은 경우 null을 반환합니다. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) `Node` 인터페이스의 읽기 전용 nextSibling 속성은 부모의 [`childNodes`](./childnodes/)에서 지정된 노드 바로 다음에 위치한 노드를 반환하며, 지정된 노드가 부모 요소의 마지막 자식인 경우 null을 반환합니다. |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) Node의 읽기 전용 nodeName 속성은 현재 노드의 이름을 문자열로 반환합니다. |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) 기본 객체의 유형을 나타내는 코드입니다. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | `Node` 인터페이스의 nodeValue 속성은 현재 노드의 값을 반환하거나 설정합니다. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Node 인터페이스의 읽기 전용 ownerDocument 속성은 해당 노드의 최상위 문서 객체를 반환합니다. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) `Node` 인터페이스의 읽기 전용 parentElement 속성은 DOM 노드의 부모 [`Element`](../element/)을 반환하며, 노드에 부모가 없거나 부모가 DOM Element가 아닌 경우 null을 반환합니다. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node 인터페이스의 읽기 전용 parentNode 속성은 DOM 트리에서 지정된 노드의 상위를 반환합니다. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix 읽기 전용 속성은 지정된 요소의 패키지 접두사를 반환하며, 접두사가 지정되지 않은 경우 null을 반환합니다. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) `Node` 인터페이스의 읽기 전용 previousSibling 속성은 부모의 [`childNodes`](./firstchild/) 목록에서 지정된 노드 바로 앞에 위치한 노드를 반환하며, 지정된 노드가 목록의 첫 번째인 경우 null을 반환합니다. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | `Node` 인터페이스의 textContent 속성은 노드와 그 하위 노드들의 텍스트 내용을 나타냅니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | [`EventTarget `](../eventtarget/) 인터페이스의 addEventListener() 메서드는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | The addEventListener() 메서드([EventTarget ](T:com.aspose.html.dom.EventTarget) 인터페이스)는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | The addEventListener() 메서드([EventTarget ](T:com.aspose.html.dom.EventTarget) 인터페이스)는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Node 인터페이스의 appendChild() 메서드는 지정된 부모 노드의 자식 목록 끝에 노드를 추가합니다. 주어진 자식이 문서에 이미 존재하는 노드에 대한 참조인 경우, appendChild()는 현재 위치에서 새로운 위치로 이동시킵니다(다른 노드에 추가하기 전에 노드를 부모 노드에서 제거할 필요가 없습니다). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | Node 인터페이스의 cloneNode() 메서드는 이 메서드가 호출된 노드의 복제본을 반환합니다. 매개변수는 노드에 포함된 하위 트리를 복제할지 여부를 제어합니다. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | Node 인터페이스의 cloneNode() 메서드는 이 메서드가 호출된 노드의 복제본을 반환합니다. 매개변수는 노드에 포함된 하위 트리를 복제할지 여부를 제어합니다. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 지정된 [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/)에 이벤트를 디스패치하고(동기적으로) 영향을 받은 EventListener들을 적절한 순서로 호출합니다. 일반적인 이벤트 처리 규칙(캡처 및 선택적 버블링 단계 포함)도 [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)로 수동 디스패치된 이벤트에 적용됩니다. |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node 인터페이스의 hasChildNodes() 메서드는 주어진 `Node`에 자식 노드가 있는지 여부를 나타내는 부울 값을 반환합니다. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Node 인터페이스의 insertBefore() 메서드는 지정된 부모 노드의 자식으로서 기준 노드 앞에 노드를 삽입합니다. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Node 인터페이스의 isDefaultNamespace() 메서드는 패키지 URI를 인수로 받습니다. 주어진 노드에서 해당 패키지가 기본 패키지이면 true, 그렇지 않으면 false를 반환합니다. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `Node` 인터페이스의 isEqualNode() 메서드는 두 노드가 같은지 테스트합니다. 두 노드는 동일한 유형, 정의 특성(요소의 경우 ID, 자식 수 등), 속성이 일치할 때 동일하다고 판단되며, 일치해야 하는 구체적인 데이터 포인트는 노드 유형에 따라 다릅니다. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Node 인터페이스의 isSameNode() 메서드는 === 엄격 동등 연산자에 대한 레거시 별칭입니다. 즉, 두 노드가 동일한지(다시 말해, 같은 객체를 참조하는지) 테스트합니다. |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Node 인터페이스의 lookupNamespaceURI() 메서드는 접두사를 매개변수로 받아 해당 노드에서 찾은 경우 연결된 패키지 URI를 반환하고(찾지 못하면 null을 반환합니다). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Node 인터페이스의 lookupPrefix() 메서드는 주어진 패키지 URI에 대한 접두사가 있으면 해당 접두사를 포함한 문자열을 반환하고, 없으면 null을 반환합니다. 여러 접두사가 가능한 경우 첫 번째 접두사가 반환됩니다. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | 이 메서드는 이 Node 아래의 하위 트리 전체 깊이에 있는 모든 [`Text`](../text/) 노드(속성 노드 포함)를 "정규" 형태로 변환합니다. 즉, 구조(예: [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), [`entity references`](../entityreference/))만이 [`Text`](../text/) 노드를 구분하도록 하여 인접한 Text 노드나 빈 Text 노드가 없게 합니다. 이는 문서가 저장되고 다시 로드된 경우와 동일한 DOM 뷰를 보장하고, 특정 문서 트리 구조에 의존하는 작업(예: XPointer [XPointer] 조회) 사용 시 유용합니다. [`DOMConfiguration`](../../com.aspose.html/configuration/) 객체에 연결된 [`Node.ownerDocument`](./ownerdocument/)의 "normalize-characters" 매개변수가 true이면 이 메서드는 Text 노드의 문자도 완전히 정규화합니다. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node 인터페이스의 removeChild() 메서드는 DOM에서 자식 노드를 제거하고 제거된 노드를 반환합니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안에 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안에 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안에 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 자식 노드 목록에서 oldChild를 newChild로 교체하고, oldChild 노드를 반환합니다. newChild가 [`DocumentFragment`](../documentfragment/) 객체인 경우, oldChild는 해당 [`DocumentFragment`](../documentfragment/)의 모든 자식으로 교체되며, 동일한 순서로 삽입됩니다. newChild가 이미 트리에 존재하면 먼저 제거됩니다. |
| [toString](../../com.aspose.html.dom/node/toString/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | [`Attribute`](../attr/)의 [`Element`](../element/) 속성입니다. |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | [`CDATASection`](../cdatasection/) 예: &lt;!CDATA[[ … ]]&gt;. |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | [`Comment`](../comment/) 노드 예: &lt;!-- … --&gt;. |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | [`DocumentFragment`](../documentfragment/) 노드. |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | [`Document`](../document/) 노드. |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | [`DocumentType`](../documenttype/) 노드 예: &lt;!DOCTYPE html&gt;. |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | [`Element`](../element/) 노드 예: &lt;p&gt; 또는 &lt;div&gt;. |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | [`Entity`](../entity/) 노드. |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | [`EntityReference`](../entityreference/) 노드. |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | [`Notation`](../notation/) 노드 |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | XML 문서의 [`ProcessingInstruction`](../processinginstruction/)이며, 예를 들어 &lt;?xml-stylesheet … ?&gt;. |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | 실제 [`Text`](../text/)는 [`Element`](../element/) 또는 [`Attr`](../attr/) 내부에 있습니다. |

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 또 보기

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
