---
title: EventTarget.DispatchEvent
second_title: .NET API 참조용 Aspose.HTML
description: EventTarget 방법. 이 메서드를 사용하면 구현 이벤트 모델로 이벤트를 보낼 수 있습니다.
type: docs
weight: 20
url: /ko/net/aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

이 메서드를 사용하면 구현 이벤트 모델로 이벤트를 보낼 수 있습니다.

```csharp
public bool DispatchEvent(Event @event)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| event | Event | 이벤트 처리에 사용할 이벤트 유형, 동작 및 컨텍스트 정보를 지정합니다. |

### 반환 값

의 반환 값`DispatchEvent` 이벤트를 처리한 리스너가 호출되었는지 여부를 나타냅니다.[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) . 만약[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) 값이 false라고 불렀고 그렇지 않으면 값이 true입니다.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../domexception/) |  |

### 비고

이 방식으로 전달된 이벤트는 구현에서 직접 전달된 이벤트와 동일한 캡처 및 버블링 동작을 갖습니다. 이벤트의 대상은[`EventTarget`](../) 에`DispatchEvent` 라고 합니다.

### 또한보십시오

* class [Event](../../../aspose.html.dom.events/event/)
* class [EventTarget](../)
* 네임스페이스 [Aspose.Html.Dom](../../eventtarget/)
* 집회 [Aspose.HTML](../../../)


