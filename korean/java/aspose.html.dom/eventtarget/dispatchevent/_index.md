---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.HTML for Java API 참조"
description: "EventTarget 메서드. 지정된 EventTarget에 이벤트를 동기적으로 디스패치하여 영향을 받는 EventListener를 적절한 순서대로 호출합니다. 캡처 및 선택적 버블링 단계가 포함된 일반적인 이벤트 처리 규칙은 dispatchEvent로 수동 디스패치된 이벤트에도 적용됩니다"
type: docs

url: /ko/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

지정된 [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/)에 이벤트를 디스패치하고(동기식으로) 영향을 받는 EventListener를 적절한 순서대로 호출합니다. 캡처 및 선택적 버블링 단계를 포함한 일반적인 이벤트 처리 규칙은 [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)로 수동 디스패치된 이벤트에도 적용됩니다.

```java
public bool DispatchEvent(Event @event)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이벤트 | 이벤트 | 이벤트를 처리하는 데 사용될 이벤트 유형, 동작 및 컨텍스트 정보를 지정합니다. |

### 반환 값

반환값은 이벤트를 처리한 리스너 중 하나가 호출되었는지 여부를 나타냅니다. 호출되었다면 값은 false이며, 그렇지 않으면 값은 true입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../domexception/) |  |

## 비고

이와 같이 디스패치된 이벤트는 구현에 의해 직접 디스패치된 이벤트와 동일한 캡처링 및 버블링 동작을 가집니다. 이벤트의 대상은 호출된 on 입니다.

### 또 보기

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
