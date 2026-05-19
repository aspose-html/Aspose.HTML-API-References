---
title: "EventTarget.RemoveEventListener"
second_title: "Aspose.HTML for Java API 참조"
description: "EventTarget 메서드. 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안에 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 제거된 이벤트 리스너는 다시 호출될 수 없습니다"
type: docs

url: /ko/java/com.aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(String, DOMEventHandler, bool) {#removeeventlistener}

이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안에 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다.

```java
public void RemoveEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | String | 제거되는 대상의 이벤트 유형을 지정합니다. |
| 핸들러 | DOMEventHandler | 해당 매개변수는 제거될 대상을 나타냅니다. |
| useCapture | Boolean | 제거되는 EventListener가 캡처링 리스너로 등록되었는지 여부를 지정합니다. 리스너가 두 번 등록된 경우, 하나는 캡처와 함께, 하나는 없이 등록되었다면 각각 별도로 제거해야 합니다. 캡처링 리스너를 제거해도 동일한 리스너의 비캡처링 버전에 영향을 주지 않으며, 그 반대도 마찬가지입니다. |

### 또 보기

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener) {#removeeventlistener_1}

이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안에 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | String | 제거되는 대상의 이벤트 유형을 지정합니다. |
| 리스너 | IEventListener | 해당 매개변수는 제거될 대상을 나타냅니다. |

### 또 보기

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_2}

이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 동안에 리스너가 제거되면 현재 동작에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 절대 호출될 수 없습니다.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | String | 제거되는 대상의 이벤트 유형을 지정합니다. |
| 리스너 | IEventListener | 해당 매개변수는 제거될 대상을 나타냅니다. |
| useCapture | Boolean | 제거되는 EventListener가 캡처링 리스너로 등록되었는지 여부를 지정합니다. 리스너가 두 번 등록된 경우, 하나는 캡처와 함께, 하나는 없이 등록되었다면 각각 별도로 제거해야 합니다. 캡처링 리스너를 제거해도 동일한 리스너의 비캡처링 버전에 영향을 주지 않으며, 그 반대도 마찬가지입니다. |

### 또 보기

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
