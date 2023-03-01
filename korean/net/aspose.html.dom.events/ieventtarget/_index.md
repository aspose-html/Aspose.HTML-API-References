---
title: Interface IEventTarget
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Events.IEventTarget 상호 작용. EventTarget 인터페이스는 DOM 이벤트 모델을 지원하는 구현에서 모든 노드에 의해 구현됩니다. 따라서 이 인터페이스는 노드 인터페이스의 인스턴스에서 바인딩 특정 캐스팅 방법을 사용하여 얻을 수 있습니다. 인터페이스를 통해 이벤트 리스너를 등록 및 제거할 수 있습니다. 한EventTarget 그리고 이벤트를 디스패치IEventTarget .
type: docs
weight: 810
url: /ko/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

[`EventTarget`](../../aspose.html.dom/eventtarget/) 인터페이스는 DOM 이벤트 모델을 지원하는 구현에서 모든 노드에 의해 구현됩니다. 따라서 이 인터페이스는 노드 인터페이스의 인스턴스에서 바인딩 특정 캐스팅 방법을 사용하여 얻을 수 있습니다. 인터페이스를 통해 이벤트 리스너를 등록 및 제거할 수 있습니다. 한[`EventTarget`](../../aspose.html.dom/eventtarget/) 그리고 이벤트를 디스패치`IEventTarget` .

```csharp
public interface IEventTarget
```

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(string, IEventListener) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener, bool) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | 이 메서드를 사용하면 구현 이벤트 모델로 이벤트를 보낼 수 있습니다. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(string, IEventListener) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../ieventlistener/) 에서 제거됩니다.[`EventTarget`](../../aspose.html.dom/eventtarget/) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener, bool) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../ieventlistener/) 에서 제거됩니다.[`EventTarget`](../../aspose.html.dom/eventtarget/) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 집회 [Aspose.HTML](../../)


