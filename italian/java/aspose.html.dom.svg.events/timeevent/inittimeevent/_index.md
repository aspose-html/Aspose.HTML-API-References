---
title: "TimeEvent.InitTimeEvent"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo TimeEvent. Il metodo initTimeEvent è usato per inizializzare il valore di un TimeEvent creato tramite l'interfaccia DocumentEvent. Questo metodo può essere chiamato solo prima che il TimeEvent sia stato inviato tramite il metodo dispatchEvent, anche se può essere chiamato più volte durante quella fase, se necessario. Se chiamato più volte, l'ultima invocazione ha la precedenza."
type: docs

url: /it/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

Il metodo initTimeEvent è usato per inizializzare il valore di un TimeEvent creato tramite l'interfaccia DocumentEvent. Questo metodo può essere chiamato solo prima che il TimeEvent sia stato inviato tramite il metodo dispatchEvent, anche se può essere chiamato più volte durante quella fase se necessario. Se chiamato più volte, l'ultima invocazione ha la precedenza.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeArg | String | Specifica il tipo di evento. |
| viewArg | IAbstractView | Specifica l'AbstractView dell'evento. |
| detailArg | Int64 | Specifica il dettaglio dell'evento. |

### Vedi anche

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
