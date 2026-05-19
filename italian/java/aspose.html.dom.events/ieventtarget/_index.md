---
title: "Interfaccia IEventTarget"
second_title: "Riferimento API Aspose.HTML per Java"
description: "interfaccia com.aspose.html.dom.events.IEventTarget. L'interfaccia EventTarget è implementata da tutti i Node in un'implementazione che supporta il modello di eventi DOM. Pertanto questa interfaccia può essere ottenuta utilizzando metodi di casting specifici per il binding su un'istanza dell'interfaccia Node. L'interfaccia consente la registrazione e la rimozione di Event Listener e l'invio di eventi a essi."
type: docs

url: /it/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

L'interfaccia EventTarget è implementata da tutti i Node in un'implementazione che supporta il modello di eventi DOM. Pertanto, questa interfaccia può essere ottenuta utilizzando metodi di casting specifici per il binding su un'istanza dell'interfaccia Node. L'interfaccia consente la registrazione e la rimozione di Event Listener su un oggetto e la distribuzione degli eventi a esso.

```java
public interface IEventTarget
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | Il metodo addEventListener() di EventTarget imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | Il metodo addEventListener() di EventTarget imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Invia un Event al EventTarget specificato, (sincronamente) invocando gli EventListener interessati nell'ordine appropriato. Le regole normali di elaborazione degli eventi (inclusi la fase di cattura e quella di bubbling opzionale) si applicano anche agli eventi inviati manualmente con dispatchEvent(). |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |

### Vedi anche

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
