---
title: "EventTarget 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.EventTarget 클래스. EventTarget 인터페이스는 이벤트를 수신할 수 있고 리스너를 가질 수 있는 객체에 구현됩니다. 즉, 이벤트 대상은 이 인터페이스와 연관된 세 가지 메서드를 구현합니다."
type: docs

url: /ko/java/com.aspose.html.dom/eventtarget/
---
## EventTarget class

EventTarget 인터페이스는 이벤트를 수신하고 해당 이벤트에 대한 리스너를 가질 수 있는 객체에 구현됩니다. 다시 말해, 모든 이벤트 대상은 이 인터페이스와 연관된 세 가지 메서드를 구현합니다.

[`Element`](../element/), and its children, as well as [`Document`](../document/) and Window, are the most common event targets, but other objects can be event targets, too.

```java
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [EventTarget](eventtarget/)() | EventTarget 객체의 새 인스턴스를 초기화합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener) | `EventTarget ` 인터페이스의 addEventListener() 메서드는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(String, DOMEventHandler, bool) | addEventListener() 메서드([EventTarget ](T:com.aspose.html.dom.EventTarget) 인터페이스)는 지정된 이벤트가 대상에 전달될 때마다 호출될 함수를 설정합니다. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(String, IEventListener, bool) | addEventListener() 메서드([EventTarget ](T:com.aspose.html.dom.EventTarget) 인터페이스)는 지정된 이벤트가 대상에 전달될 때마다 호출될 함수를 설정합니다. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 지정된 [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/)에 이벤트를 디스패치하고(동기식으로) 해당 EventListener들을 적절한 순서대로 호출합니다. 캡처 및 선택적 버블링 단계 등을 포함한 일반 이벤트 처리 규칙은 [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)를 사용해 수동으로 디스패치된 이벤트에도 적용됩니다. |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(String, DOMEventHandler, bool) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(String, IEventListener, bool) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |

### 또 보기

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
