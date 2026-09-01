---
title: "IEventTarget.DispatchEvent"
second_title: "Java용 Aspose.HTML API 참조"
description: "IEventTarget 메서드. 지정된 EventTarget에서 이벤트를 동기적으로 디스패치하여 영향을 받은 EventListeners들을 적절한 순서대로 호출합니다. 캡처 및 선택적 버블링 단계가 포함된 일반 이벤트 처리 규칙이 dispatchEvent로 수동 디스패치된 이벤트에도 적용됩니다."
type: docs

url: /ko/java/com.aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

지정된 EventTarget에 이벤트를 디스패치하고(동기적으로) 영향을 받는 EventListener를 적절한 순서대로 호출합니다. 일반적인 이벤트 처리 규칙(캡처 단계 및 선택적 버블링 단계 포함)도 dispatchEvent()로 수동 디스패치된 이벤트에 적용됩니다.

```java
public bool DispatchEvent(Event @event)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 이벤트 | 이벤트 | 이벤트를 처리하는 데 사용될 이벤트 유형, 동작 및 컨텍스트 정보를 지정합니다. |

### 반환 값

반환값은 이벤트를 처리한 리스너 중 하나가 호출되었는지 여부를 나타냅니다. 호출되었다면 값은 false이고, 그렇지 않으면 값은 true입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 이벤트 핸들러에서 발생한 예외는 잡히지 않은 예외로 보고됩니다. 이벤트 핸들러는 중첩 호출 스택에서 실행되며, 완료될 때까지 호출자를 차단하지만 예외는 호출자에게 전파되지 않습니다. |

## 비고

이와 같이 디스패치된 이벤트는 구현에 의해 직접 디스패치된 이벤트와 동일한 캡처 및 버블링 동작을 가집니다. 이벤트의 대상은 호출된 대상입니다.

### 또 보기

* class [Event](../../event/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
