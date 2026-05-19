---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.HTML for Java API 참조"
description: "IEventTarget 메서드. EventTarget 메서드 addEventListener는 지정된 이벤트가 대상에 전달될 때마다 호출될 함수를 설정합니다."
type: docs

url: /ko/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

EventTarget 메서드 addEventListener()는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다.

일반적인 대상은 Element, Document, Window이지만, 대상은 이벤트를 지원하는 모든 객체(예: XMLHttpRequest)일 수 있습니다.

```java
public void AddEventListener(String type, IEventListener listener)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | String | 청취하려는 이벤트 유형을 나타내는 대소문자를 구분하는 문자열입니다. |
| 리스너 | IEventListener | 사용자가 구현한 인터페이스를 받아 이벤트 발생 시 호출될 메서드들을 포함합니다. |

## 비고

만약 an이 이벤트를 처리하는 동안 an에 추가되면, 현재 동작에 의해 트리거되지 않지만 버블링 단계와 같은 이후 이벤트 흐름 단계에서 트리거될 수 있습니다. 동일한 매개변수로 동일한 대상에 여러 개의 동일한 Event Listener가 등록된 경우 중복 인스턴스는 폐기됩니다. 이는 해당 리스너가 두 번 호출되는 것을 방지하며, 폐기되었으므로 그 메서드로 제거할 필요가 없습니다.

### 또 보기

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

EventTarget 메서드 addEventListener()는 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다.

일반적인 대상은 Element, Document, Window이지만, 대상은 이벤트를 지원하는 모든 객체(예: XMLHttpRequest)일 수 있습니다.

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | String | 청취하려는 이벤트 유형을 나타내는 대소문자를 구분하는 문자열입니다. |
| 리스너 | IEventListener | 사용자가 구현한 인터페이스를 받아 이벤트 발생 시 호출될 메서드들을 포함합니다. |
| useCapture | Boolean | true인 경우, useCapture는 사용자가 캡처를 시작하려는 의도를 나타냅니다. 캡처가 시작된 후, 지정된 유형의 모든 이벤트는 트리에서 그들 아래의 Event Targets에 디스패치되기 전에 등록된 대상에게 디스패치됩니다. 트리를 따라 위로 버블링되는 이벤트는 캡처를 사용하도록 지정된 대상에 의해 트리거되지 않습니다. |

## 비고

만약 an이 이벤트를 처리하는 동안 an에 추가되면, 현재 동작에 의해 트리거되지 않지만 버블링 단계와 같은 이후 이벤트 흐름 단계에서 트리거될 수 있습니다. 동일한 매개변수로 동일한 대상에 여러 개의 동일한 Event Listener가 등록된 경우 중복 인스턴스는 폐기됩니다. 이는 해당 리스너가 두 번 호출되는 것을 방지하며, 폐기되었으므로 그 메서드로 제거할 필요가 없습니다.

### 또 보기

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
