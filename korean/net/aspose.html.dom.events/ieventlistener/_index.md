---
title: Interface IEventListener
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Events.IEventListener 상호 작용. IEventListener인터페이스는 이벤트를 처리하는 기본 방법입니다. 사용자는IEventListener 인터페이스에 리스너를 등록합니다.EventTarget 를 사용하여AddEventListener method. 사용자는 자신의IEventListener 그것으로부터EventTarget listener. 사용을 완료한 후
type: docs
weight: 800
url: /ko/net/aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

`IEventListener`인터페이스는 이벤트를 처리하는 기본 방법입니다. 사용자는`IEventListener` 인터페이스에 리스너를 등록합니다.[`EventTarget`](../../aspose.html.dom/eventtarget/) 를 사용하여[`AddEventListener`](../../aspose.html.dom/eventtarget/addeventlistener/) method. 사용자는 자신의`IEventListener` 그것으로부터[`EventTarget`](../../aspose.html.dom/eventtarget/) listener. 사용을 완료한 후

```csharp
public interface IEventListener
```

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [HandleEvent](../../aspose.html.dom.events/ieventlistener/handleevent/)(Event) | 이 메서드는 해당 유형의 이벤트가 발생할 때마다 호출됩니다.`IEventListener` 인터페이스가 등록되었습니다. |

### 비고

cloneNode 메서드를 사용하여 노드를 복사할 때 소스 노드에 연결된 이벤트 리스너는 복사된 노드에 연결되지 않습니다. 사용자가 새로 만든 복사본에 동일한 이벤트 리스너를 추가하려면 사용자가 수동으로 추가해야 합니다.

### 또한보십시오

* 네임스페이스 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 집회 [Aspose.HTML](../../)


