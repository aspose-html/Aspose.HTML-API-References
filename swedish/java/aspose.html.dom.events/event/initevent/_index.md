---
title: "Event.InitEvent"
second_title: "Aspose.HTML för Java API-referens"
description: "Event‑metod. InitEvent‑metoden används för att initiera värdet på ett Event som skapats via gränssnittet theIDocumentEvent."
type: docs

url: /sv/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

Metoden `InitEvent` används för att initiera värdet på ett [`Event`](../) som skapats via [`IDocumentEvent`](../../idocumentevent/)‑gränssnittet.

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | Händelsetypen. |
| bubblor | Boolean | om satt till `true` [bubblor]. |
| avbrytbar | Boolean | om satt till `true` [avbrytbar]. |

## Anmärkningar

Denna metod får endast anropas innan Event har dispatchats via [`DispatchEvent`](../../ieventtarget/dispatchevent/) metoden, även om den kan anropas flera gånger under den fasen om nödvändigt. Om den anropas flera gånger har det sista anropet företräde. Om den anropas från en subklass av Event‑gränssnittet modifieras endast de värden som anges i initEvent‑metoden, alla andra attribut lämnas oförändrade.

### Se även

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
