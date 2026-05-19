---
title: "EventTarget.AddEventListener"
second_title: "Aspose.HTML for Java API 참조"
description: "EventTarget 메서드. EventTarget 인터페이스의 addEventListener 메서드는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다"
type: docs

url: /ko/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

The addEventListener() 메서드([EventTarget ](T:com.aspose.html.dom.EventTarget) 인터페이스)는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다.

이는 호출된 EventTarget의 지정된 이벤트 유형에 대한 이벤트 리스너 목록에 함수를 추가하거나 [EventListener](T:com.aspose.html.dom.events.IEventListener)를 구현하는 객체를 추가함으로써 작동합니다. 해당 함수나 객체가 이미 해당 대상의 이벤트 리스너 목록에 존재하면 두 번째로 추가되지 않습니다.

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | String | 사용자가 등록하는 이벤트 유형 |
| 핸들러 | DOMEventHandler | 이벤트가 발생할 때 호출될 것을 받습니다. |
| useCapture | Boolean | true인 경우, useCapture는 사용자가 캡처를 시작하려는 의도를 나타냅니다. 캡처가 시작된 후, 지정된 유형의 모든 이벤트는 트리에서 그들 아래의 Event Targets에 디스패치되기 전에 등록된 대상에게 디스패치됩니다. 트리를 따라 위로 버블링되는 이벤트는 캡처를 사용하도록 지정된 대상에 의해 트리거되지 않습니다. |

## 비고

만약 an이 이벤트를 처리하는 동안 an에 추가되면, 현재 동작에 의해 트리거되지 않지만 버블링 단계와 같은 이후 이벤트 흐름 단계에서 트리거될 수 있습니다. 동일한 매개변수로 동일한 대상에 여러 개의 동일한 Event Listener가 등록된 경우 중복 인스턴스는 폐기됩니다. 이는 해당 리스너가 두 번 호출되는 것을 방지하며, 폐기되었으므로 그 메서드로 제거할 필요가 없습니다.

### 또 보기

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

[`EventTarget `](../) 인터페이스의 addEventListener() 메서드는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다.

이는 호출된 EventTarget의 지정된 이벤트 유형에 대한 이벤트 리스너 목록에 함수를 추가하거나 [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/)를 구현하는 객체를 추가함으로써 작동합니다. 해당 함수나 객체가 이미 해당 대상의 이벤트 리스너 목록에 존재하면 두 번째로 추가되지 않습니다.

```java
public void AddEventListener(String type, IEventListener listener)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | String | 사용자가 등록하는 이벤트 유형 |
| 리스너 | IEventListener | 사용자가 구현한 인터페이스를 받아 이벤트 발생 시 호출될 메서드들을 포함합니다. |

## 비고

만약 an이 이벤트를 처리하는 동안 an에 추가되면, 현재 동작에 의해 트리거되지 않지만 버블링 단계와 같은 이후 이벤트 흐름 단계에서 트리거될 수 있습니다. 동일한 매개변수로 동일한 대상에 여러 개의 동일한 Event Listener가 등록된 경우 중복 인스턴스는 폐기됩니다. 이는 해당 리스너가 두 번 호출되는 것을 방지하며, 폐기되었으므로 그 메서드로 제거할 필요가 없습니다.

### 또 보기

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

The addEventListener() 메서드([EventTarget ](T:com.aspose.html.dom.EventTarget) 인터페이스)는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다.

이는 호출된 EventTarget의 지정된 이벤트 유형에 대한 이벤트 리스너 목록에 함수를 추가하거나 [EventListener](T:com.aspose.html.dom.events.IEventListener)를 구현하는 객체를 추가함으로써 작동합니다. 해당 함수나 객체가 이미 해당 대상의 이벤트 리스너 목록에 존재하면 두 번째로 추가되지 않습니다.

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | String | 사용자가 등록하는 이벤트 유형 |
| 리스너 | IEventListener | 사용자가 구현한 인터페이스를 받아 이벤트 발생 시 호출될 메서드들을 포함합니다. |
| useCapture | Boolean | true인 경우, useCapture는 사용자가 캡처를 시작하려는 의도를 나타냅니다. 캡처가 시작된 후, 지정된 유형의 모든 이벤트는 트리에서 그들 아래의 Event Targets에 디스패치되기 전에 등록된 대상에게 디스패치됩니다. 트리를 따라 위로 버블링되는 이벤트는 캡처를 사용하도록 지정된 대상에 의해 트리거되지 않습니다. |

## 비고

만약 an이 이벤트를 처리하는 동안 an에 추가되면, 현재 동작에 의해 트리거되지 않지만 버블링 단계와 같은 이후 이벤트 흐름 단계에서 트리거될 수 있습니다. 동일한 매개변수로 동일한 대상에 여러 개의 동일한 Event Listener가 등록된 경우 중복 인스턴스는 폐기됩니다. 이는 해당 리스너가 두 번 호출되는 것을 방지하며, 폐기되었으므로 그 메서드로 제거할 필요가 없습니다.

### 또 보기

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
