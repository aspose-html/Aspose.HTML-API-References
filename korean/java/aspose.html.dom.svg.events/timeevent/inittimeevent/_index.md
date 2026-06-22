---
title: "TimeEvent.InitTimeEvent"
second_title: "Java용 Aspose.HTML API 참조"
description: "TimeEvent 메서드. initTimeEvent 메서드는 DocumentEvent 인터페이스를 통해 생성된 TimeEvent의 값을 초기화하는 데 사용됩니다. 이 메서드는 TimeEvent가 dispatchEvent 메서드를 통해 디스패치되기 전에만 호출될 수 있지만, 필요에 따라 해당 단계에서 여러 번 호출될 수 있습니다. 여러 번 호출될 경우 마지막 호출이 우선합니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

initTimeEvent 메서드는 DocumentEvent 인터페이스를 통해 생성된 TimeEvent의 값을 초기화하는 데 사용됩니다. 이 메서드는 TimeEvent가 dispatchEvent 메서드로 전달되기 전에만 호출할 수 있지만, 필요에 따라 해당 단계에서 여러 번 호출될 수 있습니다. 여러 번 호출된 경우, 마지막 호출이 우선합니다.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| typeArg | String | 이벤트 유형을 지정합니다. |
| viewArg | IAbstractView | Event의 AbstractView를 지정합니다. |
| detailArg | Int64 | Event의 detail을 지정합니다. |

### 또 보기

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
