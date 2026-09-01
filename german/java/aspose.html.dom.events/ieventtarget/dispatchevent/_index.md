---
title: "IEventTarget.DispatchEvent"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IEventTarget-Methode. Sendet ein Event an das angegebene EventTarget synchron und ruft die betroffenen EventListeners in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln, einschließlich der Capturing- und optionalen Bubbling-Phase, gelten auch für manuell mit dispatchEvent gesendete Events."
type: docs

url: /de/java/com.aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Sendet ein Ereignis an das angegebene EventTarget (synchron) und ruft die betroffenen EventListener in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Erfassungs‑ und optionalen Bubbling‑Phase) gelten ebenfalls für Ereignisse, die manuell mit dispatchEvent() gesendet werden.

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
| [dOMException](../../../com.aspose.html.dom/domexception/) | Von Event-Handlern ausgelöste Ausnahmen werden als nicht abgefangene Ausnahmen gemeldet. Die Event-Handler laufen auf einem verschachtelten Aufrufstapel; sie blockieren den Aufrufer, bis sie abgeschlossen sind, aber Ausnahmen werden nicht zum Aufrufer propagiert. |

## Hinweise

Auf diese Weise gesendete Events haben dasselbe Capturing- und Bubbling-Verhalten wie Events, die direkt von der Implementierung gesendet werden. Das Ziel des Events ist das on, auf dem es aufgerufen wird.

### Siehe auch

* class [Event](../../event/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
