---
title: "Event.PreventDefault"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo dell'evento. Se un evento è annullabile, il metodo PreventDefault viene utilizzato per indicare che l'evento deve essere annullato, il che significa che qualsiasi azione predefinita normalmente eseguita dall'implementazione a seguito dell'evento non si verificherà"
type: docs

url: /it/java/com.aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Se un evento è annullabile, il metodo `PreventDefault` viene utilizzato per indicare che l'evento deve essere annullato, il che significa che qualsiasi azione predefinita normalmente eseguita dall'implementazione a seguito dell'evento non si verificherà.

```java
public void PreventDefault()
```

## Osservazioni

Se, durante qualsiasi fase del flusso di eventi, viene chiamato il metodo `PreventDefault`, l'evento viene annullato. Qualsiasi azione predefinita associata all'evento non si verificherà. L'invocazione di questo metodo per un evento non annullabile non ha alcun effetto. Una volta che `PreventDefault` è stato chiamato, rimarrà in vigore per il resto della propagazione dell'evento. Questo metodo può essere utilizzato durante qualsiasi fase del flusso di eventi.

### Vedi anche

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
