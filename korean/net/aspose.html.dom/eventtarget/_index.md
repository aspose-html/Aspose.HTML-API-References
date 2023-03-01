---
title: Class EventTarget
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.EventTarget 수업. EventTarget 인터페이스는 DOM 이벤트 모델을 지원하는 구현에서 모든 노드에 의해 구현됩니다. 따라서 이 인터페이스는 노드 인터페이스의 인스턴스에서 바인딩 특정 캐스팅 방법을 사용하여 얻을 수 있습니다. 인터페이스를 통해 이벤트 리스너를 등록 및 제거할 수 있습니다. 한EventTarget 그리고 이벤트를 디스패치IEventTarget .
type: docs
weight: 720
url: /ko/net/aspose.html.dom/eventtarget/
---
## EventTarget class

`EventTarget` 인터페이스는 DOM 이벤트 모델을 지원하는 구현에서 모든 노드에 의해 구현됩니다. 따라서 이 인터페이스는 노드 인터페이스의 인스턴스에서 바인딩 특정 캐스팅 방법을 사용하여 얻을 수 있습니다. 인터페이스를 통해 이벤트 리스너를 등록 및 제거할 수 있습니다. 한`EventTarget` 그리고 이벤트를 디스패치[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) .

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(string, DOMEventHandler, bool) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(string, IEventListener, bool) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | 이 메서드를 사용하면 구현 이벤트 모델로 이벤트를 보낼 수 있습니다. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | 관리되지 않는 리소스 해제, 해제 또는 재설정과 관련된 응용 프로그램 정의 작업을 수행합니다. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../aspose.html.dom.events/ieventlistener/) 에서 제거됩니다.`EventTarget` 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(string, DOMEventHandler, bool) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../aspose.html.dom.events/ieventlistener/) 에서 제거됩니다.`EventTarget` 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(string, IEventListener, bool) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../aspose.html.dom.events/ieventlistener/) 에서 제거됩니다.`EventTarget` 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |

### 또한보십시오

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* 네임스페이스 [Aspose.Html.Dom](../../aspose.html.dom/)
* 집회 [Aspose.HTML](../../)


