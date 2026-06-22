---
title: "HTMLHtmlElement 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.HTMLHtmlElement 클래스. HTML 문서의 루트입니다. HTML 4.01의 HTML 요소 정의를 참조하십시오."
type: docs

url: /ko/java/com.aspose.html/htmlhtmlelement/
---
## HTMLHtmlElement class

HTML 문서의 루트. HTML 4.01의 HTML 요소 정의를 참조하십시오.

또한 [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109)을 참조하십시오.

```java
public class HTMLHtmlElement : HTMLElement
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) 이 노드(요소인 경우)의 속성을 포함하는 NamedNodeMap이며, 그렇지 않으면 null을 반환합니다. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node 인터페이스의 읽기 전용 baseURI 속성은 노드를 포함하는 문서의 절대 기본 URL을 반환합니다. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) 이 요소의 자식인 요소 노드 현재 개수를 반환합니다. nodeType 1인 자식 노드가 없으면 0을 반환합니다. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node 인터페이스의 읽기 전용 childNodes 속성은 주어진 요소의 자식 노드에 대한 실시간 [`NodeList`](../../com.aspose.html.collections/nodelist/)을 반환하며, 첫 번째 자식 노드의 인덱스는 0입니다. 자식 노드에는 요소, 텍스트 및 주석이 포함됩니다. |
| [getChildren](../../com.aspose.html.dom/element/children/) 현재 요소의 자식 요소들을 반환합니다. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) \"class\" 속성을 파싱하여 얻은 토큰을 포함하는 실시간 DOMTokenList를 반환합니다. |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) [`Node`](../../com.aspose.html.dom/node/) 인터페이스의 읽기 전용 firstChild 속성은 트리에서 노드의 첫 번째 자식을 반환하며, 자식이 없으면 null을 반환합니다. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) 이 요소의 첫 번째 자식 요소 노드를 반환합니다. 자식 요소가 없으면 null을 반환합니다. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) [`Node`](../../com.aspose.html.dom/node/) 인터페이스의 읽기 전용 lastChild 속성은 노드의 마지막 자식을 반환합니다. 부모가 요소인 경우, 해당 자식은 일반적으로 요소 노드, 텍스트 노드 또는 주석 노드입니다. 자식 요소가 없으면 null을 반환합니다. |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) 이 요소의 마지막 자식 요소 노드를 반환합니다. 이 요소에 자식 요소가 없으면 null을 반환합니다. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) 이 노드의 정규화된 이름 중 로컬 부분을 반환합니다. ELEMENT_NODE와 ATTRIBUTE_NODE가 아닌 모든 유형의 노드 및 Document.createElement()와 같은 DOM Level 1 메서드로 생성된 노드의 경우 항상 null을 반환합니다. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) 이 노드의 네임스페이스 URI이며, 지정되지 않은 경우 null을 반환합니다. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) 이 요소의 다음 형제 요소 노드를 반환합니다. 문서 트리에서 이 요소 뒤에 오는 형제 요소 노드가 없으면 null을 반환합니다. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) [`Node`](../../com.aspose.html.dom/node/) 인터페이스의 읽기 전용 nextSibling 속성은 지정된 노드 바로 뒤에 있는 부모의 [`childNodes`](../../com.aspose.html.dom/node/childnodes/)에 있는 노드를 반환하며, 지정된 노드가 부모 요소의 마지막 자식인 경우 null을 반환합니다. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) 이 노드의 유형에 따라 결정되는 이름을 반환합니다. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) 기본 객체의 유형을 나타내는 코드입니다. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | `[`Node `](../../com.aspose.html.dom/node/)` 인터페이스의 nodeValue 속성은 현재 노드의 값을 반환하거나 설정합니다. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Node 인터페이스의 읽기 전용 ownerDocument 속성은 해당 노드의 최상위 문서 객체를 반환합니다. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) [`Node`](../../com.aspose.html.dom/node/) 인터페이스의 읽기 전용 parentElement 속성은 DOM 노드의 상위 [`Element`](../../com.aspose.html.dom/element/)을 반환하며, 노드에 상위가 없거나 상위가 DOM Element가 아닌 경우 null을 반환합니다. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node 인터페이스의 읽기 전용 parentNode 속성은 지정된 노드의 DOM 트리 상위 노드를 반환합니다. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) 이 노드의 네임스페이스 접두사이며, 지정되지 않은 경우 null을 반환합니다. null로 정의된 경우, 값을 설정해도 효과가 없습니다. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) 이 요소의 이전 형제 요소 노드를 반환합니다. 문서 트리에서 이 요소 앞에 오는 형제 요소 노드가 없으면 null을 반환합니다. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) [`Node`](../../com.aspose.html.dom/node/) 인터페이스의 읽기 전용 previousSibling 속성은 지정된 노드 바로 앞에 있는 부모의 [`childNodes`](../../com.aspose.html.dom/node/firstchild/) 목록의 노드를 반환하며, 지정된 노드가 해당 목록의 첫 번째인 경우 null을 반환합니다. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) 이 요소에 저장된 shadowRoot를 반환하며, 닫혀 있는 경우 null을 반환합니다. |
| [getStyle](../../com.aspose.html/htmlelement/style/) 특정 요소에 스타일 정보를 직접 적용할 수 있게 하는 스타일 속성을 나타냅니다. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) 요소의 이름을 반환합니다. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | 이 속성은 이 노드와 그 하위 노드들의 텍스트 내용을 반환합니다. null로 정의된 경우, 값을 설정해도 효과가 없습니다. 값을 설정하면 해당 노드의 모든 자식이 제거되고, 새 문자열이 비어 있지 않거나 null이 아니면 해당 문자열을 포함하는 단일 Text 노드로 교체됩니다. |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |
[getVersion]
[setVersion] Version information about the document's DTD. See the version attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | `[`EventTarget `](../../com.aspose.html.dom/eventtarget/)` 인터페이스의 addEventListener() 메서드는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() 메서드([EventTarget ](T:com.aspose.html.dom.EventTarget) 인터페이스)는 지정된 이벤트가 대상에 전달될 때마다 호출될 함수를 설정합니다. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() 메서드([EventTarget ](T:com.aspose.html.dom.EventTarget) 인터페이스)는 지정된 이벤트가 대상에 전달될 때마다 호출될 함수를 설정합니다. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Node 인터페이스의 appendChild() 메서드는 지정된 부모 노드의 자식 목록 끝에 노드를 추가합니다. 주어진 자식이 문서에 이미 존재하는 노드에 대한 참조인 경우, appendChild()는 해당 노드를 현재 위치에서 새로운 위치로 이동시킵니다(다른 노드에 추가하기 전에 노드를 부모 노드에서 제거할 필요가 없습니다). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | 그림자 루트를 생성하고 현재 요소에 연결합니다. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Node 인터페이스의 cloneNode() 메서드는 이 메서드가 호출된 노드의 복제본을 반환합니다. 매개변수는 노드에 포함된 하위 트리를 복제할지 여부를 제어합니다. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Node 인터페이스의 cloneNode() 메서드는 이 메서드가 호출된 노드의 복제본을 반환합니다. 매개변수는 노드에 포함된 하위 트리를 복제할지 여부를 제어합니다. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 지정된 [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/)에 이벤트를 디스패치하고(동기식으로) 해당 EventListener들을 적절한 순서대로 호출합니다. 캡처 및 선택적 버블링 단계 등을 포함한 일반 이벤트 처리 규칙은 [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)를 사용해 수동으로 디스패치된 이벤트에도 적용됩니다. |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | 이름으로 속성 값을 검색합니다. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | 요소의 속성 이름을 문자열 배열로 반환합니다. 요소에 속성이 없으면 빈 배열을 반환합니다. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | 이름으로 속성 노드를 검색합니다. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | 로컬 이름과 패키지 URI로 Attr 노드를 검색합니다. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | 로컬 이름과 패키지 URI로 속성 값을 검색합니다. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | 인수에 지정된 모든 클래스를 가진 [`element`](../../com.aspose.html.dom/element/) 내부의 모든 요소를 포함하는 [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) 객체를 반환합니다. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | 지정된 태그 이름을 가진 모든 [`elements`](../../com.aspose.html.dom/element/)를 문서 순서대로 포함하는 [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) 객체를 반환합니다. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | 지정된 로컬 이름 및 패키지 URI 문자열을 가진 모든 [`elements`](../../com.aspose.html.dom/element/)를 문서 순서대로 포함하는 [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) 객체를 반환합니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | 주어진 이름의 속성이 이 요소에 지정되어 있거나 기본값을 가지고 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | 주어진 로컬 이름 및 패키지 URI를 가진 속성이 이 요소에 지정되어 있거나 기본값을 가지고 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | 이 노드(요소인 경우)가 속성을 가지고 있는지 여부를 반환합니다. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node 인터페이스의 hasChildNodes() 메서드는 주어진 [`Node`](../../com.aspose.html.dom/node/)에 자식 노드가 있는지 여부를 나타내는 부울 값을 반환합니다. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Node 인터페이스의 insertBefore() 메서드는 지정된 부모 노드의 자식으로서 기준 노드 앞에 노드를 삽입합니다. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Node 인터페이스의 isDefaultNamespace() 메서드는 패키지 URI를 인수로 받으며, 해당 패키지가 주어진 노드의 기본 패키지이면 true, 그렇지 않으면 false를 반환합니다. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `[`Node`](../../com.aspose.html.dom/node/)` 인터페이스의 isEqualNode() 메서드는 두 노드가 동일한지 테스트합니다. 두 노드는 동일한 유형, 정의 특성(요소의 경우 ID, 자식 수 등), 속성이 일치할 때 동일하다고 판단됩니다. 일치해야 하는 구체적인 데이터 포인트는 노드 유형에 따라 다릅니다. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Node 인터페이스의 isSameNode() 메서드는 === 엄격 동등 연산자의 레거시 별칭입니다. 즉, 두 노드가 동일한지(다시 말해, 같은 객체를 참조하는지) 테스트합니다. |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Node 인터페이스의 lookupNamespaceURI() 메서드는 접두사를 매개변수로 받아 주어진 노드에서 해당 접두사와 연결된 패키지 URI를 찾으면 반환하고, 찾지 못하면 null을 반환합니다. |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Node 인터페이스의 lookupPrefix() 메서드는 주어진 패키지 URI에 대한 접두사가 있으면 해당 접두사를 포함한 문자열을 반환하고, 없으면 null을 반환합니다. 여러 접두사가 가능한 경우 첫 번째 접두사가 반환됩니다. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | 전체 깊이의 하위 트리(속성 노드 포함)에서 모든 [`Text`](../../com.aspose.html.dom/text/) 노드를 "normal" 형태로 변환합니다. 이 형태에서는 구조(예: [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), [`entity references`](../../com.aspose.html.dom/entityreference/))만이 [`Text`](../../com.aspose.html.dom/text/) 노드와 구분되며, 인접한 Text 노드나 빈 Text 노드가 존재하지 않게 됩니다. 이는 문서의 DOM 뷰가 저장 후 다시 로드된 것과 동일하도록 보장하는 데 사용할 수 있으며, 특정 문서 트리 구조에 의존하는 작업(예: XPointer [XPointer] 조회)에도 유용합니다. [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/)에 연결된 [`DOMConfiguration`](../configuration/) 객체의 "normalize-characters" 매개변수가 true이면, 이 메서드는 Text 노드의 문자도 완전히 정규화합니다. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | 문서에서 선택자와 일치하는 첫 번째 Element를 반환합니다. |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | 문서에서 선택자와 일치하는 모든 Element의 NodeList를 반환합니다. |
| [remove](../../com.aspose.html.dom/element/remove/)() | 이 인스턴스를 제거합니다. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | 이름으로 속성을 제거합니다. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | 지정된 속성 노드를 제거합니다. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | 지역 이름과 패키지 URI로 속성을 제거합니다. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node 인터페이스의 removeChild() 메서드는 DOM에서 자식 노드를 제거하고 제거된 노드를 반환합니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 자식 노드 목록에서 child node oldChild를 newChild로 교체하고 oldChild 노드를 반환합니다. newChild가 [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) 객체인 경우, oldChild는 해당 [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/)의 모든 자식으로 교체되며, 동일한 순서로 삽입됩니다. newChild가 이미 트리에 존재하면 먼저 제거됩니다. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | 새 속성을 추가합니다. 해당 이름의 속성이 이미 요소에 존재하면, 그 값이 value 매개변수의 값으로 변경됩니다. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | 새 속성 노드를 추가합니다. 해당 이름(nodeName)의 속성이 이미 요소에 존재하면, 새 속성으로 교체됩니다. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | 새 속성을 추가합니다. 해당 로컬 이름과 패키지 URI를 가진 속성이 이미 요소에 존재하면, 새 속성으로 교체됩니다. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | 새 속성을 추가합니다. 동일한 로컬 이름과 패키지 URI를 가진 속성이 이미 요소에 존재하면, 그 접두사가 qualifiedName의 접두사 부분으로 변경되고, 값이 value 매개변수의 값으로 변경됩니다. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | force가 지정되지 않은 경우, qualifiedName을 "toggles"하여 존재하면 제거하고 존재하지 않으면 추가합니다. force가 true이면 qualifiedName을 추가하고, false이면 qualifiedName을 제거합니다. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | force가 지정되지 않은 경우, qualifiedName을 "toggles"하여 존재하면 제거하고 존재하지 않으면 추가합니다. force가 true이면 qualifiedName을 추가하고, false이면 qualifiedName을 제거합니다. |
| [toString](../../com.aspose.html.dom/node/toString/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 이벤트

| 이름 | 설명 |
| --- | --- |
| event [OnAbort](../../com.aspose.html/htmlelement/onabort/) | OnAbort 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnBlur](../../com.aspose.html/htmlelement/onblur/) | OnBlur 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnCancel](../../com.aspose.html/htmlelement/oncancel/) | OnCancel 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnCanplay](../../com.aspose.html/htmlelement/oncanplay/) | OnCanplay 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnCanPlayThrough](../../com.aspose.html/htmlelement/oncanplaythrough/) | OnCanPlayThrough 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnChange](../../com.aspose.html/htmlelement/onchange/) | OnChange 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnClick](../../com.aspose.html/htmlelement/onclick/) | OnClick 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnCueChange](../../com.aspose.html/htmlelement/oncuechange/) | OnCueChange 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnDblClick](../../com.aspose.html/htmlelement/ondblclick/) | OnDblClick 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnDurationChange](../../com.aspose.html/htmlelement/ondurationchange/) | OnDurationChange 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnEmptied](../../com.aspose.html/htmlelement/onemptied/) | OnEmptied 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnEnded](../../com.aspose.html/htmlelement/onended/) | OnEnded 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnError](../../com.aspose.html/htmlelement/onerror/) | OnError 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnFocus](../../com.aspose.html/htmlelement/onfocus/) | OnFocus 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnInput](../../com.aspose.html/htmlelement/oninput/) | OnInput 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnInvalid](../../com.aspose.html/htmlelement/oninvalid/) | OnInvalid 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnKeyDown](../../com.aspose.html/htmlelement/onkeydown/) | OnKeyDown 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnKeyPress](../../com.aspose.html/htmlelement/onkeypress/) | OnKeyPress 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnKeyUp](../../com.aspose.html/htmlelement/onkeyup/) | OnKeyUp 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnLoad](../../com.aspose.html/htmlelement/onload/) | OnLoad 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnLoadedData](../../com.aspose.html/htmlelement/onloadeddata/) | OnLoadedData 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnLoadedMetadata](../../com.aspose.html/htmlelement/onloadedmetadata/) | OnLoadedMetadata 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnLoadStart](../../com.aspose.html/htmlelement/onloadstart/) | OnLoadStart 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseDown](../../com.aspose.html/htmlelement/onmousedown/) | OnMouseDown 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseEnter](../../com.aspose.html/htmlelement/onmouseenter/) | OnMouseEnter 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseLeave](../../com.aspose.html/htmlelement/onmouseleave/) | OnMouseLeave 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseMove](../../com.aspose.html/htmlelement/onmousemove/) | OnMouseMove 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseOut](../../com.aspose.html/htmlelement/onmouseout/) | OnMouseOut 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseOver](../../com.aspose.html/htmlelement/onmouseover/) | OnMouseOver 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseUp](../../com.aspose.html/htmlelement/onmouseup/) | OnMouseUp 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseWheel](../../com.aspose.html/htmlelement/onmousewheel/) | OnMouseWheel 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnPause](../../com.aspose.html/htmlelement/onpause/) | OnPause 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnPlay](../../com.aspose.html/htmlelement/onplay/) | OnPlay 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnPlaying](../../com.aspose.html/htmlelement/onplaying/) | OnPlaying 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnProgress](../../com.aspose.html/htmlelement/onprogress/) | OnProgress 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnRateChange](../../com.aspose.html/htmlelement/onratechange/) | OnRateChange 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnReset](../../com.aspose.html/htmlelement/onreset/) | OnReset 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnResize](../../com.aspose.html/htmlelement/onresize/) | OnResize 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnScroll](../../com.aspose.html/htmlelement/onscroll/) | OnScroll 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnSeeked](../../com.aspose.html/htmlelement/onseeked/) | OnSeeked 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnSeeking](../../com.aspose.html/htmlelement/onseeking/) | OnSeeking 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnSelect](../../com.aspose.html/htmlelement/onselect/) | OnSelect 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnShow](../../com.aspose.html/htmlelement/onshow/) | OnShow 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnStalled](../../com.aspose.html/htmlelement/onstalled/) | OnStalled 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnSubmit](../../com.aspose.html/htmlelement/onsubmit/) | OnSubmit 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnSuspend](../../com.aspose.html/htmlelement/onsuspend/) | OnSuspend 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnTimeUpdate](../../com.aspose.html/htmlelement/ontimeupdate/) | OnTimeUpdate 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnToggle](../../com.aspose.html/htmlelement/ontoggle/) | OnToggle 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnVolumeChange](../../com.aspose.html/htmlelement/onvolumechange/) | OnVolumeChange 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnWaiting](../../com.aspose.html/htmlelement/onwaiting/) | OnWaiting 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |

### 또 보기

* class [HTMLElement](../htmlelement/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
