---
title: "EventTarget.RemoveEventListener"
second_title: "Aspose.HTML för Java API-referens"
description: "EventTarget-metod. Denna metod möjliggör borttagning av händelselyssnare från målobjektet. Om en tas bort från ett medan det bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de har tagits bort."
type: docs

url: /sv/java/com.aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(String, DOMEventHandler, bool) {#removeeventlistener}

Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort.

```java
public void RemoveEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | Anger händelsetypen för den som tas bort. |
| hanterare | DOMEventHandler | Parametern anger den som ska tas bort. |
| useCapture | Boolean | Anger om EventListener som tas bort var registrerad som en fångstlyssnare eller inte. Om en lyssnare registrerades två gånger, en med capture och en utan, måste varje tas bort separat. Borttagning av en fångstlyssnare påverkar inte en icke‑fångstversion av samma lyssnare, och vice versa. |

### Se även

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener) {#removeeventlistener_1}

Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | Anger händelsetypen för den som tas bort. |
| lyssnare | IEventListener | Parametern anger den som ska tas bort. |

### Se även

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_2}

Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | Anger händelsetypen för den som tas bort. |
| lyssnare | IEventListener | Parametern anger den som ska tas bort. |
| useCapture | Boolean | Anger om EventListener som tas bort var registrerad som en fångstlyssnare eller inte. Om en lyssnare registrerades två gånger, en med capture och en utan, måste varje tas bort separat. Borttagning av en fångstlyssnare påverkar inte en icke‑fångstversion av samma lyssnare, och vice versa. |

### Se även

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
