---
title: "IEventTarget.RemoveEventListener"
second_title: "Aspose.HTML för Java API-referens"
description: "IEventTarget‑metod. Denna metod möjliggör borttagning av händelselyssnare från händelse‑målet. Om en tas bort från ett medan den bearbetar en händelse kommer den inte att utlösas av de pågående åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort"
type: docs

url: /sv/java/com.aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(String, IEventListener) {#removeeventlistener}

Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | Anger händelsetypen för den som tas bort. |
| lyssnare | IEventListener | Parametern indikerar den som ska tas bort. |

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_1}

Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | Anger händelsetypen för den som tas bort. |
| lyssnare | IEventListener | Parametern indikerar den som ska tas bort. |
| useCapture | Boolean | Anger om den EventListener som tas bort var registrerad som en capture‑lyssnare eller inte. Om en lyssnare registrerades två gånger, en med capture och en utan, måste varje tas bort separat. Borttagning av en capture‑lyssnare påverkar inte en icke‑capture‑version av samma lyssnare, och vice versa. |

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
