---
title: "com.aspose.html.dom"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom Document Object Model 패키지는 모든 HTML, XML 또는 SVG 문서를 표현하고 상호 작용할 수 있는 API를 제공합니다. DOM은 브라우저에 로드되는 문서 모델로, 문서를 노드 트리로 표현하며 각 노드는 문서의 일부(예: 요소, 텍스트, 문자열 또는 주석)를 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.dom/
---
The **com.aspose.html.dom (Document Object Model)** 패키지는 모든 HTML, XML 또는 SVG 문서를 표현하고 상호 작용할 수 있는 API를 제공합니다. DOM은 브라우저에 로드되는 문서 모델로, 문서를 노드 트리 형태로 나타내며 각 노드는 문서의 일부(예: 요소, 텍스트 문자열 또는 주석)를 나타냅니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [Attr](./attr/) | Attr 인터페이스는 Element 객체의 속성을 나타냅니다. 일반적으로 해당 속성의 허용 값은 문서와 연관된 스키마에 정의됩니다. |
| [CDATASection](./cdatasection/) | CDATA 섹션은 마크업으로 간주될 수 있는 문자를 포함하는 텍스트 블록을 이스케이프하는 데 사용됩니다. |
| [CharacterData](./characterdata/) | CharacterData는 DOM에서 문자 데이터를 접근하기 위한 속성과 메서드 집합을 갖는 Node를 확장합니다. |
| [Comment](./comment/) | CharacterData를 상속하며, 주석의 내용, 즉 시작 '' 사이의 모든 문자를 나타냅니다. |
| [Document](./document/) | Document는 전체 HTML, XML 또는 SVG 문서를 나타냅니다. 개념적으로 이는 문서 트리의 루트이며, 문서 데이터에 대한 주요 접근을 제공합니다. |
| [DocumentFragment](./documentfragment/) | DocumentFragment는 "lightweight" 또는 "minimal" 문서 객체입니다. 문서 트리의 일부를 추출하거나 새로운 문서 조각을 만들고자 하는 경우가 매우 흔합니다. |
| [DocumentType](./documenttype/) | DocumentType은 문서에 정의된 엔터티 목록에 대한 인터페이스를 제공합니다. |
| [DOMException](./domexception/) | DOMException 인터페이스는 웹 API의 메서드를 호출하거나 속성에 접근할 때 발생하는 비정상적인 이벤트(예외)를 나타냅니다. 이는 웹 API에서 오류 상황을 설명하는 기본 방식입니다. |
| [DOMObject](./domobject/) | DOMObject 타입은 전체 Document Object Model의 기본 객체를 나타내는 데 사용됩니다. Java와 ECMAScript에서는 DOMObject가 Object 타입에 바인딩됩니다. |
| [Element](./element/) | Element 인터페이스는 HTML 또는 XML 문서의 요소를 나타냅니다. |
| [Entity](./entity/) | XML 문서에서 파싱되었든 파싱되지 않았든 알려진 엔터티를 나타냅니다. |
| [EntityReference](./entityreference/) | EntityReference 노드는 트리에서 엔터티 참조를 나타내는 데 사용할 수 있습니다. |
| [EventTarget](./eventtarget/) | EventTarget 인터페이스는 이벤트를 수신할 수 있고 해당 이벤트에 대한 리스너를 가질 수 있는 객체에 구현됩니다. 다시 말해, 모든 이벤트 대상은 이 인터페이스와 연관된 세 가지 메서드를 구현합니다. |
| [Node](./node/) | Node 인터페이스는 전체 Document Object Model의 기본 데이터 유형입니다. 이는 문서 트리에서 단일 노드를 나타냅니다. Node 인터페이스를 구현하는 모든 객체가 자식 처리 메서드를 제공하지만, 모든 객체가 자식을 가질 수 있는 것은 아닙니다. 예를 들어, [`Text`](../com.aspose.html.dom/text/) 노드는 자식을 가질 수 없으며, 이러한 노드에 자식을 추가하면 [`DOMException`](../com.aspose.html.dom/domexception/)이 발생합니다. |
| [Notation](./notation/) | DTD에 선언된 표기법을 나타냅니다. |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction은 "processing instruction"을 나타내며, XML에서 문서 텍스트에 프로세서별 정보를 유지하는 방법으로 사용됩니다. |
| [QualifiedName](./qualifiedname/) | HTML 한정 이름을 나타냅니다. |
| [ShadowRoot](./shadowroot/) | ShadowRoot는 섀도우 트리의 루트 노드입니다. |
| [Text](./text/) | Text 인터페이스는 CharacterData를 상속하며 Element 또는 Attr의 텍스트 콘텐츠(XML에서는 문자 데이터라고 함)를 나타냅니다. |
| [TypeInfo](./typeinfo/) | TypeInfo는 문서와 연관된 스키마에 지정된대로 Element 또는 Attr 노드에서 참조되는 타입을 나타냅니다. |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | 브라우징 컨텍스트는 [`Document`](../com.aspose.html.dom/document/) 객체가 사용자에게 표시되는 환경입니다. |
| [IChildNode](./ichildnode/) | `[`IChildNode`](../com.aspose.html.dom/ichildnode/)` 인터페이스를 정의하며, 이는 부모를 가질 수 있는 [`Node`](../com.aspose.html.dom/node/)에 의해 구현되어야 합니다. |
| [IDOMImplementation](./idomimplementation/) | DOMImplementation 인터페이스는 특정 문서 객체 모델 인스턴스와 무관하게 작업을 수행하기 위한 다양한 메서드를 제공합니다. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | 시스템 이벤트 처리를 지원하는 모든 요소가 상속해야 하는 인터페이스를 나타냅니다. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | `[`IChildNode`](../com.aspose.html.dom/ichildnode/)`를 정의하며, 이는 [`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/)가 아닙니다. |
| [INonElementParentNode](./inonelementparentnode/) | `[`IParentNode`](../com.aspose.html.dom/iparentnode/)`를 정의하며, 이는 Element 타입이 아닙니다. |
| [IParentNode](./iparentnode/) | `[`IParentNode`](../com.aspose.html.dom/iparentnode/)` 인터페이스를 정의하며, 이는 가능한 모든 부모에 의해 구현됩니다. |
| [IStorage](./istorage/) | Web Storage API의 이 인터페이스는 특정 도메인의 세션 또는 로컬 스토리지에 대한 접근을 제공합니다. Web Storage 사양을 참조하십시오: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | ShadowRoot가 작동할 수 있는 모드. |
