---
title: "CustomEvent.InitCustomEvent"
second_title: "Aspose.HTML för Java API-referens"
description: "CustomEvent-metoden. /// InitEvent-metoden används för att initiera värdet av ett Event som skapats via IDocumentEvent-gränssnittet"
type: docs

url: /sv/java/com.aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// [`InitEvent`](../../event/initevent/)‑metoden används för att initiera värdet av ett [`Event`](../../event/) som skapats genom [`IDocumentEvent`](../../idocumentevent/)‑gränssnittet.

```java
public void InitCustomEvent(String type, bool bubbles, bool cancelable, object detail)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | Händelsetypen. |
| bubblor | Boolean | om den är satt till `true` [bubblor]. |
| avbrytbar | Boolean | om den är satt till `true` [avbrytbar]. |
| detalj | Objekt | Den anpassade datan. |

## Anmärkningar

Denna metod får endast anropas innan Eventet har skickats via [`DispatchEvent`](../../ieventtarget/dispatchevent/)-metoden, men den kan anropas flera gånger under den fasen om så behövs. Om den anropas flera gånger har det sista anropet företräde. Om den anropas från en underklass till Event‑gränssnittet modifieras endast de värden som anges i initEvent‑metoden, alla andra attribut lämnas oförändrade.

### Se även

* class [CustomEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
