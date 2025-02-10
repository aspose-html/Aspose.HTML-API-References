---
title: TimeEvent.InitTimeEvent
second_title: Aspose.HTML for Java API Reference
description: TimeEvent method. The initTimeEvent method is used to initialize the value of a TimeEvent created through the DocumentEvent interface. This method may only be called before the TimeEvent has been dispatched via the dispatchEvent method though it may be called multiple times during that phase if necessary. If called multiple times the final invocation takes precedence
type: docs
weight: 30
url: /java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

The initTimeEvent method is used to initialize the value of a TimeEvent created through the DocumentEvent interface. This method may only be called before the TimeEvent has been dispatched via the dispatchEvent method, though it may be called multiple times during that phase if necessary. If called multiple times, the final invocation takes precedence.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| Parameter | Type | Description |
| --- | --- | --- |
| typeArg | String | Specifies the event type. |
| viewArg | IAbstractView | Specifies the Event's AbstractView. |
| detailArg | Int64 | Specifies the Event's detail. |

### See Also

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
