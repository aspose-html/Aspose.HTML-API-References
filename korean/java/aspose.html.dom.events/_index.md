---
title: "com.aspose.html.dom.events"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.events 패키지는 DOM 업데이트와 관련된 모든 이벤트에 대한 객체를 제공합니다. 여기에는 이벤트와 연관된 특정 컨텍스트 정보 관찰에 대한 구독 및 사용자 정의 이벤트 구성 등이 포함됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.events/
---
The **com.aspose.html.dom.events** 패키지는 DOM 업데이트와 관련된 모든 이벤트에 대한 객체를 제공합니다. 여기에는 이벤트와 연관된 특정 컨텍스트 정보 관찰에 대한 구독 및 사용자 정의 이벤트 생성이 포함됩니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [CustomEvent](./customevent/) | CustomEvent 인터페이스를 사용하는 이벤트는 사용자 정의 데이터를 전달하는 데 사용할 수 있습니다. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | DocumentLoadErrorEvent는 요청된 리소스를 사용할 수 없을 때 발생합니다. |
| [DOMEventHandler](./domeventhandler/) | Document Object Model (DOM) 이벤트 처리를 위한 일반 콜백 대리자를 나타냅니다. |
| [ErrorEvent](./errorevent/) | ErrorEvent는 런타임 중에 발생한 오류에 대한 컨텍스트 정보를 제공합니다. |
| [Event](./event/) | 이는 이벤트를 처리하는 핸들러에게 이벤트에 대한 컨텍스트 정보를 제공하는 데 사용됩니다. |
| [FocusEvent](./focusevent/) | FocusEvent 인터페이스는 포커스 이벤트와 관련된 특정 컨텍스트 정보를 제공합니다. |
| [InputEvent](./inputevent/) | DOM이 업데이트될 때마다 입력 이벤트가 알림으로 전송됩니다. |
| [KeyboardEvent](./keyboardevent/) | KeyboardEvent 인터페이스는 키보드 장치와 관련된 특정 컨텍스트 정보를 제공합니다. 각 키보드 이벤트는 값을 사용하여 키를 참조합니다. 키보드 이벤트는 일반적으로 포커스를 가진 요소를 대상으로 합니다. |
| [MouseEvent](./mouseevent/) | MouseEvent 인터페이스는 마우스 이벤트와 관련된 특정 컨텍스트 정보를 제공합니다. |
| [UIEvent](./uievent/) | UIEvent 인터페이스는 사용자 인터페이스 이벤트와 관련된 특정 컨텍스트 정보를 제공합니다. |
| [WheelEvent](./wheelevent/) | WheelEvent 인터페이스는 휠 이벤트와 관련된 특정 컨텍스트 정보를 제공합니다. WheelEvent 인터페이스의 인스턴스를 만들려면 WheelEvent 생성자를 사용하고 선택적인 WheelEventInit 사전을 전달하십시오. |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | DocumentEvent 인터페이스는 사용자가 구현에서 지원하는 유형의 Event를 생성할 수 있는 메커니즘을 제공합니다. 구현이 Event 모델을 지원하는 경우 Document 인터페이스를 구현하는 동일한 객체에 DocumentEvent 인터페이스가 구현될 것으로 예상됩니다. |
| [IEventListener](./ieventlistener/) | 이 인터페이스는 이벤트를 처리하기 위한 기본 방법입니다. 사용자는 인터페이스를 구현하고 해당 메서드를 사용하여 리스너를 등록합니다. 사용자는 리스너 사용을 완료한 후 해당 리스너를 제거해야 합니다. |
| [IEventTarget](./ieventtarget/) | EventTarget 인터페이스는 DOM Event 모델을 지원하는 구현의 모든 노드에 의해 구현됩니다. 따라서 이 인터페이스는 Node 인터페이스의 인스턴스에 바인딩 전용 캐스팅 메서드를 사용하여 얻을 수 있습니다. 이 인터페이스는 이벤트 리스너의 등록 및 제거와 해당 객체에 대한 이벤트 디스패치를 허용합니다. |
