---
title: "IEventTarget‑Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.events.IEventTarget‑Schnittstelle. Die EventTarget‑Schnittstelle wird von allen Nodes in einer Implementierung, die das DOM‑Ereignismodell unterstützt, implementiert. Daher kann diese Schnittstelle durch bindungsspezifische Cast‑Methoden auf einer Instanz der Node‑Schnittstelle erhalten werden. Die Schnittstelle ermöglicht die Registrierung und Entfernung von Event‑Listenern sowie das Senden von Ereignissen an diese."
type: docs

url: /de/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

Das EventTarget-Interface wird von allen Nodes in einer Implementierung, die das DOM-Ereignismodell unterstützt, implementiert. Daher kann dieses Interface durch bindungsspezifische Cast-Methoden auf einer Instanz des Node-Interfaces erhalten werden. Das Interface ermöglicht die Registrierung und Entfernung von Event-Listenern sowie das Dispatchen von Ereignissen an diese.

```java
public interface IEventTarget
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | Die EventTarget‑Methode addEventListener() richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel geliefert wird. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | Die EventTarget‑Methode addEventListener() richtet eine Funktion ein, die immer dann aufgerufen wird, wenn das angegebene Ereignis an das Ziel geliefert wird. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Sendet ein Ereignis an das angegebene EventTarget (synchron) und ruft die betroffenen EventListener in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Erfassungs‑ und optionalen Bubbling‑Phase) gelten ebenfalls für Ereignisse, die manuell mit dispatchEvent() gesendet werden. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein Listener während der Verarbeitung eines Ereignisses entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein Listener während der Verarbeitung eines Ereignisses entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach dem Entfernen niemals mehr aufgerufen werden. |

### Siehe auch

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
