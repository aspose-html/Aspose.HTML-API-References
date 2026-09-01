---
title: "TimeEvent.InitTimeEvent"
second_title: "Aspose.HTML för Java API-referens"
description: "TimeEvent-metod. initTimeEvent-metoden används för att initiera värdet för ett TimeEvent som skapats via DocumentEvent‑gränssnittet. Denna metod får endast anropas innan TimeEvent har skickats via dispatchEvent‑metoden, men den kan anropas flera gånger under den fasen om det behövs. Om den anropas flera gånger har det sista anropet företräde"
type: docs

url: /sv/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

Metoden initTimeEvent används för att initiera värdet för ett TimeEvent skapat via DocumentEvent‑gränssnittet. Denna metod får endast anropas innan TimeEvent har skickats via dispatchEvent‑metoden, men den kan anropas flera gånger under den fasen om så behövs. Om den anropas flera gånger har det sista anropet företräde.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeArg | String | Anger händelsetypen. |
| viewArg | IAbstractView | Anger händelsens AbstractView. |
| detailArg | Int64 | Anger händelsens detalj. |

### Se även

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
