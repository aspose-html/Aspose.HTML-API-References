---
title: IDocumentEvent.CreateEvent
second_title: .NET API 참조용 Aspose.HTML
description: IDocumentEvent 방법. 생성Event 구현에서 지원하는 유형입니다.
type: docs
weight: 10
url: /ko/net/aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

생성[`Event`](../../event/) 구현에서 지원하는 유형입니다.

```csharp
public Event CreateEvent(string eventType)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| eventType | String | eventType 매개변수는 다음 유형을 지정합니다.[`Event`](../../event/) 생성할 인터페이스.  만약[`Event`](../../event/)지정된 인터페이스는 구현에서 지원됩니다. 이 메서드는 new 를 반환합니다.[`Event`](../../event/) 요청된 인터페이스 유형의. [`Event`](../../event/)를 통해 발송됩니다.[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) method that [`InitEvent`](../../event/initevent/) 메서드를 초기화하려면 생성 후 메서드를 호출해야 합니다.[`Event`](../../event/) s 값. |

### 반환 값

새로 생성된[`Event`](../../event/)

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 구현이 다음 유형을 지원하지 않는 경우 발생합니다.[`Event`](../../event/) 요청된 인터페이스 |

### 또한보십시오

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* 네임스페이스 [Aspose.Html.Dom.Events](../../idocumentevent/)
* 집회 [Aspose.HTML](../../../)


