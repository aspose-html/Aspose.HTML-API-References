---
title: "CustomEvent.InitCustomEvent"
second_title: "Aspose.HTML för Java API-referens"
description: "CustomEvent-metod. /// InitEvent-metoden används för att initiera värdet av ett Event som skapats genom IDocumentEvent-gränssnittet."
type: docs

url: /sv/java/com.aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// [`InitEvent`](../../event/initevent/) metoden används för att initiera värdet av ett [`Event`](../../event/) skapat genom [`IDocumentEvent`](../../idocumentevent/) gränssnittet.

```java
public void InitCustomEvent(String type, bool bubbles, bool cancelable, object detail)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | Händelsetypen. |
| bubblor | Boolean | om satt till `true` [bubblor]. |
| avbrytbar | Boolean | om satt till `true` [avbrytbar]. |
| detalj | Objekt | Den anpassade datan. |

## Anmärkningar

Denna metod får endast anropas innan Event har dispatchats via [`DispatchEvent`](../../ieventtarget/dispatchevent/) metoden, även om den kan anropas flera gånger under den fasen om nödvändigt. Om den anropas flera gånger har det sista anropet företräde. Om den anropas från en subklass av Event‑gränssnittet modifieras endast de värden som anges i initEvent‑metoden, alla andra attribut lämnas oförändrade.

### Se även

* class [CustomEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
