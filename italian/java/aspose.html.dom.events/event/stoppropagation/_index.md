---
title: "Event.StopPropagation"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Event. Il metodo StopPropagation è usato per impedire ulteriore propagazione di un evento durante il flusso dell'evento"
type: docs

url: /it/java/com.aspose.html.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

Il metodo `StopPropagation` è usato per impedire ulteriore propagazione di un evento durante il flusso dell'evento.

```java
public void StopPropagation()
```

## Osservazioni

Se questo metodo è chiamato da qualsiasi [`IEventListener`](../../ieventlistener/), l'evento cesserà di propagarsi attraverso l'albero. L'evento completerà l'invio a tutti i listener sull'attuale [`IEventTarget`](../../ieventtarget/) prima che il flusso dell'evento si fermi. Questo metodo può essere usato in qualsiasi fase del flusso dell'evento.

### Vedi anche

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
