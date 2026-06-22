---
title: "IEventTarget 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.events.IEventTarget 인터페이스. EventTarget 인터페이스는 DOM 이벤트 모델을 지원하는 구현에서 모든 Node에 의해 구현됩니다. 따라서 이 인터페이스는 Node 인터페이스 인스턴스에 대한 바인딩 전용 캐스팅 메서드를 사용하여 얻을 수 있습니다. 이 인터페이스는 Event Listener의 등록 및 제거와 해당 대상에 대한 이벤트 디스패치를 허용합니다."
type: docs

url: /ko/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

EventTarget 인터페이스는 DOM 이벤트 모델을 지원하는 구현에서 모든 노드에 구현됩니다. 따라서 이 인터페이스는 Node 인터페이스의 인스턴스에 바인딩 전용 캐스팅 메서드를 사용하여 얻을 수 있습니다. 이 인터페이스는 이벤트 리스너의 등록 및 제거와 해당 객체에 대한 이벤트 디스패치를 허용합니다.

```java
public interface IEventTarget
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | EventTarget 메서드 addEventListener()는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | EventTarget 메서드 addEventListener()는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | 지정된 EventTarget에 이벤트를 디스패치하고(동기적으로) 영향을 받는 EventListener를 적절한 순서대로 호출합니다. 일반적인 이벤트 처리 규칙(캡처 단계 및 선택적 버블링 단계 포함)도 dispatchEvent()로 수동 디스패치된 이벤트에 적용됩니다. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다. |

### 또 보기

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
