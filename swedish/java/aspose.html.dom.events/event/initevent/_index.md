---
title: "Event.InitEvent"
second_title: "Aspose.HTML för Java API-referens"
description: "Event-metod. InitEvent-metoden används för att initiera värdet av en Event som skapats genom theIDocumentEvent-gränssnittet."
type: docs

url: /sv/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

Metoden `InitEvent` används för att initiera värdet av en [`Event`](../) som skapats genom [`IDocumentEvent`](../../idocumentevent/)‑gränssnittet.

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | Händelsetypen. |
| bubblor | Boolean | om den är satt till `true` [bubblor]. |
| avbrytbar | Boolean | om den är satt till `true` [avbrytbar]. |

## Anmärkningar

Denna metod får endast anropas innan Eventet har skickats via [`DispatchEvent`](../../ieventtarget/dispatchevent/)-metoden, men den kan anropas flera gånger under den fasen om så behövs. Om den anropas flera gånger har det sista anropet företräde. Om den anropas från en underklass till Event‑gränssnittet modifieras endast de värden som anges i initEvent‑metoden, alla andra attribut lämnas oförändrade.

### Se även

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
