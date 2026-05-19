---
title: "IEventTarget.DispatchEvent"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo IEventTarget. Dispatcia un Event al EventTarget specificato invocando sincronicamente gli EventListeners interessati nell'ordine appropriato. Le regole normali di elaborazione degli eventi, inclusa la fase di cattura e quella opzionale di bubbling, si applicano anche agli eventi dispatciati manualmente con dispatchEvent."
type: docs

url: /it/java/com.aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Invia un Event al EventTarget specificato, (sincronamente) invocando gli EventListener interessati nell'ordine appropriato. Le regole normali di elaborazione degli eventi (inclusi la fase di cattura e quella di bubbling opzionale) si applicano anche agli eventi inviati manualmente con dispatchEvent().

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
| [dOMException](../../../com.aspose.html.dom/domexception/) | Le eccezioni generate dai gestori di eventi sono segnalate come eccezioni non catturate. I gestori di eventi vengono eseguiti su una pila di chiamate annidata; bloccano il chiamante finché non terminano, ma le eccezioni non si propagano al chiamante. |

## Osservazioni

Gli eventi dispatciati in questo modo avranno lo stesso comportamento di cattura e bubbling degli eventi dispatciati direttamente dall'implementazione. Il target dell'evento è il on su cui viene chiamato.

### Vedi anche

* class [Event](../../event/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
