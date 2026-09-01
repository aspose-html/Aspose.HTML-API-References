---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.HTML für Java API-Referenz"
description: "EventTarget-Methode. Sendet ein Ereignis an das angegebene EventTarget synchron und ruft die betroffenen EventListener in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln, einschließlich der Erfassungs- und optionalen Bubbling-Phase, gelten auch für manuell mit dispatchEvent gesendete Ereignisse."
type: docs

url: /de/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Sendet ein Ereignis an das angegebene [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListener in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Erfassungs- und optionalen Bubbling-Phase) gelten auch für manuell mit [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) gesendete Ereignisse.

```java
public bool DispatchEvent(Event @event)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ereignis | Ereignis | Gibt den Ereignistyp, das Verhalten und die Kontextinformationen an, die bei der Verarbeitung des Ereignisses verwendet werden sollen. |

### Rückgabewert

Der Rückgabewert von gibt an, ob einer der Listener, die das Ereignis verarbeitet haben, aufgerufen wurde. Wenn aufgerufen wurde, ist der Wert false, sonst ist der Wert true.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../domexception/) |  |

## Hinweise

Auf diese Weise gesendete Events haben dasselbe Capturing- und Bubbling-Verhalten wie Events, die direkt von der Implementierung gesendet werden. Das Ziel des Events ist das on, auf dem es aufgerufen wird.

### Siehe auch

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
