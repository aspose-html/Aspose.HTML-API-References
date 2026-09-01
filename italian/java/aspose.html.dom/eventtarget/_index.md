---
title: "Classe EventTarget"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.dom.EventTarget classe. L'interfaccia EventTarget è implementata da oggetti che possono ricevere eventi e possono avere ascoltatori per essi. In altre parole, qualsiasi destinazione di eventi implementa i tre metodi associati a questa interfaccia."
type: docs

url: /it/java/com.aspose.html.dom/eventtarget/
---
## EventTarget class

L'interfaccia EventTarget è implementata dagli oggetti che possono ricevere eventi e possono avere ascoltatori per essi. In altre parole, qualsiasi destinazione di eventi implementa i tre metodi associati a questa interfaccia.

[`Element`](../element/), and its children, as well as [`Document`](../document/) and Window, are the most common event targets, but other objects can be event targets, too.

```java
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EventTarget](eventtarget/)() | Inizializza una nuova istanza dell'oggetto EventTarget. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener) | Il metodo addEventListener() dell'interfaccia `EventTarget ` imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(String, DOMEventHandler, bool) | Il metodo addEventListener() dell'interfaccia [EventTarget ](T:com.aspose.html.dom.EventTarget) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(String, IEventListener, bool) | Il metodo addEventListener() dell'interfaccia [EventTarget ](T:com.aspose.html.dom.EventTarget) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Esegue il dispatch di un Event al [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) specificato, (sincronamente) invocando gli EventListeners interessati nell'ordine appropriato. Le regole normali di elaborazione degli eventi (inclusa la fase di cattura e quella di bubbling opzionale) si applicano anche agli eventi inviati manualmente con [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset di risorse non gestite. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso da un elemento mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(String, DOMEventHandler, bool) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso da un elemento mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(String, IEventListener, bool) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso da un elemento mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |

### Vedi anche

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
