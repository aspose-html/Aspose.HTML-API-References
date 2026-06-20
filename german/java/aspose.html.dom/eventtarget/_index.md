---
title: "EventTarget Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.EventTarget Klasse. Das EventTarget-Interface wird von Objekten implementiert, die Ereignisse empfangen können und möglicherweise Listener dafür haben. Mit anderen Worten implementiert jedes Ereignisziel die drei mit diesem Interface verbundenen Methoden."
type: docs

url: /de/java/com.aspose.html.dom/eventtarget/
---
## EventTarget class

Das EventTarget‑Interface wird von Objekten implementiert, die Ereignisse empfangen können und möglicherweise Listener dafür besitzen. Mit anderen Worten, jedes Ereignisziel implementiert die drei mit diesem Interface verbundenen Methoden.

[`Element`](../element/), and its children, as well as [`Document`](../document/) and Window, are the most common event targets, but other objects can be event targets, too.

```java
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [EventTarget](eventtarget/)() | Initialisiert eine neue Instanz des EventTarget-Objekts. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener) | Die addEventListener()-Methode des `EventTarget `-Interfaces richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(String, DOMEventHandler, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(String, IEventListener, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Sendet ein Event an das angegebene [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListeners in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Erfassungs‑ und optionalen Bubbling‑Phase) gelten ebenfalls für manuell mit [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) gesendete Events. |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein Listener während der Verarbeitung eines Ereignisses entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(String, DOMEventHandler, bool) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein Listener während der Verarbeitung eines Ereignisses entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(String, IEventListener, bool) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein Listener während der Verarbeitung eines Ereignisses entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach dem Entfernen niemals mehr aufgerufen werden. |

### Siehe auch

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
