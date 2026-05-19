---
title: "SVGDocument 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.svg.SVGDocument 클래스. SVGDocument는 SVG 계층 구조의 루트이며 전체 콘텐츠를 보유합니다. 계층 구조에 대한 접근성을 제공할 뿐만 아니라 문서에서 특정 정보 집합에 접근하기 위한 편리한 메서드도 제공합니다. SVG 요소가 다른 패키지의 문서(예: XHTML 문서) 내에 인라인으로 포함될 경우 SVGDocument 객체는 존재하지 않고, 문서 객체 계층의 루트 객체는 HTMLDocument와 같은 다른 유형의 Document 객체가 됩니다. 그러나 XML 문서 계층의 루트 요소가 SVG 요소인 경우(예: MIME 타입이 image/svg+xml인 독립형 SVG 파일을 볼 때) SVGDocument 객체가 실제로 존재하며, 이 경우 SVGDocument 객체가 문서 객체 모델 계층의 루트 객체가 됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg/svgdocument/
---
## SVGDocument class

`SVGDocument`는 SVG 계층 구조의 루트이며 전체 콘텐츠를 보유합니다. 계층 구조에 대한 접근을 제공할 뿐만 아니라 문서에서 특정 정보 집합에 접근하기 위한 편리한 메서드도 제공합니다. ‘svg’ 요소가 다른 패키지의 문서 구성 요소로 인라인 삽입될 때, 예를 들어 ‘svg’ 요소가 XHTML 문서 [XHTML] 내에 인라인 삽입될 경우, `SVGDocument` 객체는 존재하지 않습니다; 대신 문서 객체 계층 구조의 루트 객체는 HTMLDocument와 같은 다른 유형의 Document 객체가 됩니다. 그러나 XML 문서 계층 구조의 루트 요소가 ‘svg’ 요소인 경우, 예를 들어 독립 실행형 SVG 파일(즉, MIME 타입 "image/svg+xml"인 파일)을 볼 때는 `SVGDocument` 객체가 실제로 존재합니다. 이 경우 `SVGDocument` 객체가 문서 객체 모델 계층 구조의 루트 객체가 됩니다.

```java
public class SVGDocument : Document, IDocumentCSS
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SVGDocument](svgdocument/#constructor)() | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. |
| [SVGDocument](svgdocument/#constructor_1)(Configuration) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. |
| [SVGDocument](svgdocument/#constructor_2)(RequestMessage) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. |
| [SVGDocument](svgdocument/#constructor_10)(String) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. |
| [SVGDocument](svgdocument/#constructor_4)(Url) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. |
| [SVGDocument](svgdocument/#constructor_3)(RequestMessage, Configuration) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. |
| [SVGDocument](svgdocument/#constructor_8)(Stream, String) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. 문서 로드는 스트림의 현재 위치에서 시작됩니다. |
| [SVGDocument](svgdocument/#constructor_6)(Stream, Url) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. 문서 로드는 스트림의 현재 위치에서 시작됩니다. |
| [SVGDocument](svgdocument/#constructor_11)(String, Configuration) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. |
| [SVGDocument](svgdocument/#constructor_14)(String, String) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. |
| [SVGDocument](svgdocument/#constructor_12)(String, Url) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. |
| [SVGDocument](svgdocument/#constructor_5)(Url, Configuration) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. |
| [SVGDocument](svgdocument/#constructor_9)(Stream, String, Configuration) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. 문서 로드는 스트림의 현재 위치에서 시작됩니다. |
| [SVGDocument](svgdocument/#constructor_7)(Stream, Url, Configuration) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. 문서 로드는 스트림의 현재 위치에서 시작됩니다. |
| [SVGDocument](svgdocument/#constructor_15)(String, String, Configuration) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. |
| [SVGDocument](svgdocument/#constructor_13)(String, Url, Configuration) | `SVGDocument` 클래스의 새 인스턴스를 초기화합니다. 생성자는 동기적으로 작동하며 모든 외부 리소스(이미지, 스크립트 등)의 로딩이 완료될 때까지 기다립니다. 문서를 비동기적으로 로드하려면 [`Navigate`](../../com.aspose.html.dom/document/navigate/) 메서드 또는 그 오버로드를 사용하십시오. 또는 [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/)에서 적절한 플래그를 설정하여 일부 외부 리소스 로드를 비활성화할 수 있습니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) 이 노드의 절대 기본 URI이며, 구현이 절대 URI를 얻지 못한 경우 null입니다. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) 문서의 인코딩을 가져옵니다. |
| [getCharset](../../com.aspose.html.dom/document/charset/) 문서의 인코딩을 가져옵니다. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) 이 요소의 자식인 요소 노드 현재 개수를 반환합니다. nodeType이 1인 자식 노드가 없으면 0을 반환합니다. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node 인터페이스의 읽기 전용 childNodes 속성은 주어진 요소의 자식 노드에 대한 실시간 [`NodeList`](../../com.aspose.html.collections/nodelist/)을 반환하며, 첫 번째 자식 노드의 인덱스는 0입니다. 자식 노드에는 요소, 텍스트 및 주석이 포함됩니다. |
| [getChildren](../../com.aspose.html.dom/document/children/) 자식 요소를 반환합니다. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) 문서 콘텐츠 유형을 가져옵니다. |
| [getContext](../../com.aspose.html.dom/document/context/) 현재 브라우징 컨텍스트를 가져옵니다. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) Document 인터페이스의 defaultView IDL 속성은, 가져올 때 이 Document에 연결된 브라우징 컨텍스트가 있는 경우 해당 Document의 브라우징 컨텍스트의 WindowProxy 객체를 반환하고, 그렇지 않으면 null을 반환해야 합니다. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) 이 문서와 연결된 Document Type Declaration입니다. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) 이는 문서의 문서 요소인 자식 노드에 직접 접근할 수 있게 해 주는 편리한 속성입니다. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) 문서의 위치이며, 정의되지 않았거나 Document가 DOMImplementation.createDocument를 사용하여 생성된 경우 null을 반환합니다. |
| [getDomain](../../com.aspose.html.dom.svg/svgdocument/domain/) 문서를 제공한 서버의 도메인 이름이며, 서버를 도메인 이름으로 식별할 수 없는 경우 null 문자열을 반환합니다. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) [`Node`](../../com.aspose.html.dom/node/) 인터페이스의 읽기 전용 firstChild 속성은 트리에서 노드의 첫 번째 자식을 반환하며, 자식이 없으면 null을 반환합니다. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) 이 요소의 첫 번째 자식 요소 노드를 반환합니다. 자식 요소가 없으면 null을 반환합니다. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) 이 문서를 처리하는 DOMImplementation 객체입니다. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) 문서의 인코딩을 가져옵니다. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) [`Node`](../../com.aspose.html.dom/node/) 인터페이스의 읽기 전용 lastChild 속성은 노드의 마지막 자식을 반환합니다. 부모가 요소인 경우, 해당 자식은 일반적으로 요소 노드, 텍스트 노드 또는 주석 노드입니다. 자식 요소가 없으면 null을 반환합니다. |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) 이 요소의 마지막 자식 요소 노드를 반환합니다. 자식 요소가 없으면 null을 반환합니다. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) 이 노드의 정규화된 이름의 로컬 부분을 반환합니다. [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/)와 [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/)가 아닌 모든 유형의 노드 및 DOM Level 1 메서드(예: [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/))로 생성된 노드의 경우 항상 null입니다. |
| [getLocation](../../com.aspose.html.dom/document/location/) 문서의 위치입니다. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI 읽기 전용 속성은 요소의 패키지 URI를 반환하며, 요소가 패키지에 속하지 않은 경우 null을 반환합니다. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) 이 요소의 다음 형제 요소 노드를 반환합니다. 문서 트리에서 이 요소 뒤에 오는 형제 요소 노드가 없으면 null을 반환합니다. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) [`Node`](../../com.aspose.html.dom/node/) 인터페이스의 읽기 전용 nextSibling 속성은 지정된 노드 바로 뒤에 있는 부모의 [`childNodes`](../../com.aspose.html.dom/node/childnodes/)에서 노드를 반환하며, 지정된 노드가 부모 요소의 마지막 자식인 경우 null을 반환합니다. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) 이 노드의 이름이며, 유형에 따라 다릅니다. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) 기본 객체의 유형을 나타내는 코드입니다. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | `[`Node `](../../com.aspose.html.dom/node/) 인터페이스의 nodeValue 속성은 현재 노드의 값을 반환하거나 설정합니다. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) 문서의 출처를 가져옵니다. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) 소유 문서를 가져옵니다. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) [`Node`](../../com.aspose.html.dom/node/) 인터페이스의 읽기 전용 parentElement 속성은 DOM 노드의 상위 [`Element`](../../com.aspose.html.dom/element/)을 반환하며, 노드에 상위가 없거나 상위가 DOM Element가 아닌 경우 null을 반환합니다. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node 인터페이스의 읽기 전용 parentNode 속성은 DOM 트리에서 지정된 노드의 상위를 반환합니다. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix 읽기 전용 속성은 지정된 요소의 패키지 접두사를 반환하며, 접두사가 지정되지 않은 경우 null을 반환합니다. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) 이 요소의 이전 형제 요소 노드를 반환합니다. 문서 트리에서 이 요소 앞에 오는 형제 요소 노드가 없으면 null을 반환합니다. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) [`Node`](../../com.aspose.html.dom/node/) 인터페이스의 읽기 전용 previousSibling 속성은 부모의 [`childNodes`](../../com.aspose.html.dom/node/firstchild/) 목록에서 지정된 노드 바로 앞에 있는 노드를 반환하며, 지정된 노드가 해당 목록의 첫 번째인 경우 null을 반환합니다. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) 문서 준비 상태를 반환합니다. Document가 로드 중일 때는 "loading", 파싱은 끝났지만 서브 리소스가 아직 로드 중일 때는 "interactive", 모두 로드되면 "complete"를 반환합니다. |
| [getReferrer](../../com.aspose.html.dom.svg/svgdocument/referrer/) 이 페이지에 링크된 페이지의 URI를 반환합니다. 사용자가 직접(링크를 통해서가 아니라 예를 들어 북마크 등으로) 페이지에 이동한 경우 값은 빈 문자열입니다. |
| [getRootElement](../../com.aspose.html.dom.svg/svgdocument/rootelement/) 문서 계층 구조에서 루트 ‘svg’입니다. |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) 문서에 명시적으로 연결되거나 포함된 모든 스타일시트의 목록입니다. HTML 문서의 경우, HTML LINK 요소를 통해 포함된 외부 스타일시트와 인라인 STYLE 요소를 포함합니다. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | `[`Node`](../../com.aspose.html.dom/node/)` 인터페이스의 `textContent` 속성은 노드와 그 하위 노드들의 텍스트 내용을 나타냅니다. |
| [getTitle](../../com.aspose.html.dom.svg/svgdocument/title/) ‘svg’ 루트 요소의 ‘title’ 하위 요소에 의해 지정된 문서의 제목입니다 (예: Here is the title...). |
| [getURL](../../com.aspose.html.dom.svg/svgdocument/url/) 문서의 전체 URI입니다. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | `[`EventTarget `](../../com.aspose.html.dom/eventtarget/) 인터페이스의 addEventListener() 메서드는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | The addEventListener() 메서드([EventTarget ](T:com.aspose.html.dom.EventTarget) 인터페이스)는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | The addEventListener() 메서드([EventTarget ](T:com.aspose.html.dom.EventTarget) 인터페이스)는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Node 인터페이스의 appendChild() 메서드는 지정된 부모 노드의 자식 목록 끝에 노드를 추가합니다. 주어진 자식이 문서에 이미 존재하는 노드에 대한 참조인 경우, appendChild()는 현재 위치에서 새로운 위치로 이동시킵니다(다른 노드에 추가하기 전에 노드를 부모 노드에서 제거할 필요가 없습니다). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Node 인터페이스의 cloneNode() 메서드는 이 메서드가 호출된 노드의 복제본을 반환합니다. 매개변수는 노드에 포함된 하위 트리를 복제할지 여부를 제어합니다. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Node 인터페이스의 cloneNode() 메서드는 이 메서드가 호출된 노드의 복제본을 반환합니다. 매개변수는 노드에 포함된 하위 트리를 복제할지 여부를 제어합니다. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Document.createAttribute() 메서드는 새로운 속성 노드를 생성하고 반환합니다. 생성된 객체는 [`Attr`](../../com.aspose.html.dom/attr/) 인터페이스를 구현하는 노드입니다. DOM은 이러한 방식으로 특정 요소에 추가할 수 있는 속성 종류를 강제하지 않습니다. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Document.createAttribute() 메서드는 새로운 속성 노드를 생성하고 반환합니다. 생성된 객체는 [Attr](T:com.aspose.html.dom.Attr) 인터페이스를 구현하는 노드입니다. DOM은 이러한 방식으로 특정 요소에 추가할 수 있는 속성 종류를 강제하지 않습니다. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | 지정된 문자열 값을 갖는 [`CDATASection`](../../com.aspose.html.dom/cdatasection/) 노드를 생성합니다. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | 지정된 문자열을 사용하여 [`Comment`](../../com.aspose.html.dom/comment/) 노드를 생성합니다. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | DOM 노드를 추가하여 오프스크린 DOM 트리를 구축할 수 있는 새로운 빈 [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/)을 생성합니다. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | 이 메서드는 [`DocumentType`](../../com.aspose.html.dom/documenttype/) 객체를 반환하며, 이는 문서 생성 시 DOMImplementation.createDocument와 함께 사용하거나 Node.insertBefore() 또는 Node.replaceChild()와 같은 메서드로 문서에 삽입할 수 있습니다. |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | HTML 문서에서 document.createElement() 메서드는 tagName으로 지정된 HTML 요소를 생성하거나, tagName을 인식하지 못하면 [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/)을 생성합니다. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | 주어진 정규화된 이름과 패키지 URI를 가진 요소를 생성합니다. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | EntityReference 객체를 생성합니다. 또한, 참조된 엔터티가 알려져 있는 경우 EntityReference 노드의 자식 목록은 해당 엔터티 노드와 동일하게 설정됩니다. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | `[`Event`](../../com.aspose.html.dom.events/event/)`을 구현에서 지원하는 유형으로 생성합니다. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | 해결된 패키지를 포함한 파싱된 XPath 표현식을 생성합니다. 이는 표현식 문자열을 보다 효율적인 내부 형태로 컴파일하고 표현식 내에 나타나는 모든 패키지 접두사를 미리 해결할 수 있어, 애플리케이션에서 표현식을 재사용할 때 유용합니다. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node) | 지정된 노드를 루트로 하는 서브트리에서 새로운 NodeIterator를 생성합니다. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long) | 지정된 노드를 루트로 하는 서브트리에서 새로운 NodeIterator를 생성합니다. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | 지정된 노드를 루트로 하는 서브트리에서 새로운 NodeIterator를 생성합니다. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | 문서 내에서 나타난 노드의 컨텍스트를 기준으로 XPath 표현식을 쉽게 평가할 수 있도록 모든 DOM 노드를 패키지 해결에 맞게 변환합니다. 이 어댑터는 `lookupNamespaceURI` 메서드와 유사하게 동작하여, 호출 시점에 노드 계층 구조에 존재하는 현재 정보를 사용해 주어진 접두사로부터 packageURI를 해결하고, 암시적인 xml 접두사도 올바르게 해결합니다. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | 지정된 이름과 데이터 문자열을 사용하여 ProcessingInstruction 노드를 생성합니다. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | 지정된 문자열을 사용하여 Text 노드를 생성합니다. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node) | 지정된 노드를 루트로 하는 서브트리에서 새로운 TreeWalker를 생성합니다. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long) | 지정된 노드를 루트로 하는 서브트리에서 새로운 TreeWalker를 생성합니다. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | 지정된 노드를 루트로 하는 서브트리에서 새로운 TreeWalker를 생성합니다. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 지정된 [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/)에 이벤트를 디스패치하고(동기적으로) 영향을 받은 EventListener들을 적절한 순서로 호출합니다. 일반적인 이벤트 처리 규칙(캡처 및 선택적 버블링 단계 포함)도 [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)로 수동 디스패치된 이벤트에 적용됩니다. |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | XPath 표현식 문자열을 평가하고 가능한 경우 지정된 유형의 결과를 반환합니다. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Document 메서드 getElementById()는 지정된 문자열과 일치하는 id 속성을 가진 요소를 나타내는 [`Element`](../../com.aspose.html.dom/element/) 객체를 반환합니다. 요소 ID는 지정된 경우 고유해야 하므로 특정 요소에 빠르게 접근하는 유용한 방법입니다. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | [`Document`](../../com.aspose.html.dom/document/) 인터페이스의 getElementsByClassName 메서드는 주어진 클래스 이름을 모두 가진 모든 자식 요소들의 배열과 유사한 객체를 반환합니다. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | [`Document`](../../com.aspose.html.dom/document/) 인터페이스의 getElementsByTagName 메서드는 주어진 태그 이름을 가진 요소들의 [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/)을 반환합니다. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | 주어진 패키지에 속한 지정된 태그 이름을 가진 요소들의 목록을 반환합니다. 루트 노드를 포함한 전체 문서를 검색합니다. |
| [getOverrideStyle](../../com.aspose.html.dom.svg/svgdocument/getoverridestyle/)(Element, String) | 이 메서드는 지정된 요소와 지정된 의사 요소에 대한 override 스타일 선언을 검색하는 데 사용됩니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node 인터페이스의 hasChildNodes() 메서드는 주어진 [`Node`](../../com.aspose.html.dom/node/)에 자식 노드가 있는지 여부를 나타내는 부울 값을 반환합니다. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | 다른 문서에서 이 문서로 노드를 가져오며, 원본 문서의 소스 노드를 변경하거나 제거하지 않습니다; 이 메서드는 소스 노드의 새 복사본을 생성합니다. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Node 인터페이스의 insertBefore() 메서드는 지정된 부모 노드의 자식으로서 기준 노드 앞에 노드를 삽입합니다. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Node 인터페이스의 isDefaultNamespace() 메서드는 패키지 URI를 인수로 받습니다. 주어진 노드에서 해당 패키지가 기본 패키지이면 true, 그렇지 않으면 false를 반환합니다. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `[`Node`](../../com.aspose.html.dom/node/)` 인터페이스의 isEqualNode() 메서드는 두 노드가 동일한지 테스트합니다. 두 노드는 동일한 유형, 정의 특성(요소의 경우 ID, 자식 수 등), 속성이 일치할 때 동일하다고 판단됩니다. 일치해야 하는 구체적인 데이터 포인트는 노드 유형에 따라 다릅니다. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Node 인터페이스의 isSameNode() 메서드는 === 엄격 동등 연산자에 대한 레거시 별칭입니다. 즉, 두 노드가 동일한지(다시 말해, 같은 객체를 참조하는지) 테스트합니다. |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Node 인터페이스의 lookupNamespaceURI() 메서드는 접두사를 매개변수로 받아 해당 노드에서 찾은 경우 연결된 패키지 URI를 반환하고(찾지 못하면 null을 반환합니다). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Node 인터페이스의 lookupPrefix() 메서드는 주어진 패키지 URI에 대한 접두사가 있으면 해당 접두사를 포함한 문자열을 반환하고, 없으면 null을 반환합니다. 여러 접두사가 가능한 경우 첫 번째 접두사가 반환됩니다. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(RequestMessage) | 지정된 요청 객체를 기반으로 문서를 로드하고 이전 내용을 교체합니다. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String) | 지정된 통합 자원 위치(URL)에서 문서를 현재 인스턴스로 로드하여 이전 내용을 교체합니다. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Url) | 지정된 통합 자원 위치(URL)에서 문서를 현재 인스턴스로 로드하여 이전 내용을 교체합니다. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, String) | 지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 상대 리소스를 해결하여 이전 내용을 교체합니다. 문서 로드는 스트림의 현재 위치에서 시작됩니다. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, Url) | 지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 상대 리소스를 해결하여 이전 내용을 교체합니다. 문서 로드는 스트림의 현재 위치에서 시작됩니다. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, String) | 지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 상대 리소스를 해결하여 이전 내용을 교체합니다. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, Url) | 지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 상대 리소스를 해결하여 이전 내용을 교체합니다. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | `[`Text`](../../com.aspose.html.dom/text/)` 노드들을 이 Node 아래 서브트리 전체 깊이(속성 노드 포함)로 이동시켜, 구조만 남고(`[`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), [`entity references`](../../com.aspose.html.dom/entityreference/))가 `[`Text`](../../com.aspose.html.dom/text/)` 노드를 구분하는 ‘정규’ 형태로 만듭니다. 즉, 인접한 Text 노드나 빈 Text 노드가 존재하지 않게 됩니다. 이는 문서의 DOM 뷰가 저장 후 다시 로드된 것과 동일하도록 보장하는 데 사용할 수 있으며, 특정 문서 트리 구조에 의존하는 작업(예: XPointer [XPointer] 조회)에도 유용합니다. [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/)에 연결된 [`DOMConfiguration`](../../com.aspose.html/configuration/) 객체의 ‘normalize-characters’ 매개변수가 true이면, 이 메서드는 Text 노드의 문자도 완전히 정규화합니다. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | 문서에서 선택자와 일치하는 첫 번째 요소를 반환합니다. |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | 문서에서 선택자와 일치하는 모든 요소의 NodeList를 반환합니다. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node 인터페이스의 removeChild() 메서드는 DOM에서 자식 노드를 제거하고 제거된 노드를 반환합니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안에 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안에 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안에 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [renderTo](../../com.aspose.html.dom.svg/svgdocument/renderto/)(IDevice) | 이 메서드는 현재 문서의 내용을 지정된 장치에 출력하는 데 사용됩니다. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 자식 목록에서 자식 노드 oldChild를 newChild로 교체하고 oldChild 노드를 반환합니다. newChild가 [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) 객체인 경우, oldChild는 모든 [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) 자식으로 교체되며, 동일한 순서로 삽입됩니다. newChild가 이미 트리에 존재하면 먼저 제거됩니다. |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save)(ResourceHandler) | 문서 내용 및 리소스를 [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/)를 사용하여 저장합니다. |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_6)(String) | `path`로 지정된 로컬 파일에 문서를 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 생성됩니다. |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_3)(Url) | `url`로 지정된 로컬 파일에 문서를 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 생성됩니다. |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_1)(ResourceHandler, SVGSaveFormat) | 문서 내용 및 리소스를 [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/)를 사용하여 저장합니다. |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_2)(ResourceHandler, SVGSaveOptions) | 문서 내용 및 리소스를 [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/)를 사용하여 저장합니다. |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_7)(String, SVGSaveFormat) | `path`로 지정된 로컬 파일에 문서를 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 생성됩니다. |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_8)(String, SVGSaveOptions) | `path`로 지정된 로컬 파일에 문서를 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 생성됩니다. |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_4)(Url, SVGSaveFormat) | `url`로 지정된 로컬 파일에 문서를 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 생성됩니다. |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_5)(Url, SVGSaveOptions) | `url`로 지정된 로컬 파일에 문서를 저장합니다. 이 문서에서 사용된 모든 리소스는 인접 폴더에 저장되며, 폴더 이름은 output_file_name + "_files" 형태로 생성됩니다. |
| [toString](../../com.aspose.html.dom/node/toString/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | open()으로 연 문서 스트림에 텍스트 문자열을 씁니다. 이 함수는 반드시 DTD에 의해 구동되는 문서를 생성하지 않을 수 있으므로 문서 컨텍스트에서 잘못된 결과를 생성할 수 있습니다. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | open()으로 연 문서 스트림에 텍스트 문자열을 쓰고 줄바꿈 문자를 추가합니다. 이 함수는 반드시 DTD에 의해 구동되는 문서를 생성하지 않을 수 있으므로 문서 컨텍스트에서 잘못된 결과를 생성할 수 있습니다. |

## 이벤트

| 이름 | 설명 |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | OnAbort 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | OnBlur 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | OnCancel 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | OnCanplay 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | OnCanPlayThrough 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | OnChange 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | OnClick 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | OnCueChange 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | OnDblClick 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | OnDurationChange 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | OnEmptied 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | OnEnded 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | OnError 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | OnFocus 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | OnInput 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | OnInvalid 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | OnKeyDown 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | OnKeyPress 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | OnKeyUp 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | OnLoad 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | OnLoadedData 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | OnLoadedMetadata 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | OnLoadStart 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | OnMouseDown 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | OnMouseEnter 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | OnMouseLeave 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | OnMouseMove 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | OnMouseOut 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | OnMouseOver 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | OnMouseUp 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | OnMouseWheel 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | OnPause 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | OnPlay 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | OnPlaying 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | OnProgress 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | OnRateChange 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | OnReadyStateChange 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | OnReset 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | OnResize 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | OnScroll 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | OnSeeked 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | OnSeeking 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | OnSelect 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | OnShow 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | OnStalled 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | OnSubmit 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | OnSuspend 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | OnTimeUpdate 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | OnToggle 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | OnVolumeChange 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | OnWaiting 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |

### 또 보기

* class [Document](../../com.aspose.html.dom/document/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
