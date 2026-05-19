---
title: "TimeEvent.InitTimeEvent"
second_title: "Aspose.HTML for Java API 참조"
description: "TimeEvent method. The initTimeEvent method is used to initialize the value of a TimeEvent created through the DocumentEvent interface. This method may only be called before the TimeEvent has been dispatched via the dispatchEvent method though it may be called multiple times during that phase if necessary. If called multiple times the final invocation takes precedence"
type: docs

url: /ko/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

initTimeEvent 메서드는 DocumentEvent 인터페이스를 통해 생성된 TimeEvent의 값을 초기화하는 데 사용됩니다. 이 메서드는 TimeEvent가 dispatchEvent 메서드로 전달되기 전에만 호출할 수 있으며, 필요에 따라 해당 단계에서 여러 번 호출될 수 있습니다. 여러 번 호출된 경우, 마지막 호출이 우선합니다.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| typeArg | String | Specifies the event type. |
| viewArg | IAbstractView | Specifies the Event's AbstractView. |
| detailArg | Int64 | Specifies the Event's detail. |

### 또 보기

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
