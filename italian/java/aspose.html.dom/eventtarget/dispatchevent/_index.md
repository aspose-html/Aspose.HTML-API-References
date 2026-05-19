---
title: "EventTarget.DispatchEvent"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo EventTarget. Invia un evento al EventTarget specificato in modo sincrono, invocando i EventListener interessati nell'ordine appropriato. Le regole normali di elaborazione degli eventi, inclusa la fase di cattura e quella di bubbling opzionale, si applicano anche agli eventi inviati manualmente con dispatchEvent"
type: docs

url: /it/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Invia un evento al [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/), (sincronamente) invocando i EventListener interessati nell'ordine appropriato. Le regole normali di elaborazione degli eventi (inclusa la fase di cattura e quella di bubbling opzionale) si applicano anche agli eventi inviati manualmente con [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/).

```java
public bool DispatchEvent(Event @event)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| evento | Evento | Specifica il tipo di evento, il comportamento e le informazioni contestuali da utilizzare nell'elaborazione dell'evento. |

### Valore di ritorno

Il valore di ritorno indica se uno dei listener che hanno gestito l'evento è stato chiamato. Se è stato chiamato, il valore è false, altrimenti il valore è true.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../domexception/) |  |

## Osservazioni

Gli eventi dispatciati in questo modo avranno lo stesso comportamento di cattura e bubbling degli eventi dispatciati direttamente dall'implementazione. Il target dell'evento è il on su cui viene chiamato.

### Vedi anche

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
