---
title: "Event.InitEvent"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Event. Il metodo InitEvent è usato per inizializzare il valore di un Event creato tramite l'interfaccia IDocumentEvent"
type: docs

url: /it/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

Il metodo `InitEvent` è usato per inizializzare il valore di un [`Event`](../) creato tramite l'[`IDocumentEvent`](../../idocumentevent/) interfaccia.

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | String | Il tipo di evento. |
| bubbles | Boolean | se impostato su `true` [bubbles]. |
| cancelable | Boolean | se impostato su `true` [cancelable]. |

## Osservazioni

Questo metodo può essere chiamato solo prima che l'Event sia stato inviato tramite il metodo [`DispatchEvent`](../../ieventtarget/dispatchevent/), anche se può essere chiamato più volte durante quella fase se necessario. Se chiamato più volte, l'ultima invocazione ha la precedenza. Se chiamato da una sottoclasse dell'interfaccia Event, solo i valori specificati nel metodo initEvent vengono modificati, tutti gli altri attributi rimangono invariati.

### Vedi anche

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
