---
title: "CustomEvent.InitCustomEvent"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo CustomEvent. /// Il metodo InitEvent è usato per inizializzare il valore di un Event creato tramite l'interfaccia IDocumentEvent"
type: docs

url: /it/java/com.aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Il metodo [`InitEvent`](../../event/initevent/) è usato per inizializzare il valore di un [`Event`](../../event/) creato tramite l'interfaccia [`IDocumentEvent`](../../idocumentevent/).

```java
public void InitCustomEvent(String type, bool bubbles, bool cancelable, object detail)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | String | Il tipo di evento. |
| bubbles | Boolean | se impostato a `true` [bubbles]. |
| cancelable | Boolean | se impostato a `true` [cancelable]. |
| detail | Oggetto | I dati personalizzati. |

## Osservazioni

Questo metodo può essere chiamato solo prima che l'Event sia stato inviato tramite il metodo [`DispatchEvent`](../../ieventtarget/dispatchevent/), anche se può essere chiamato più volte durante quella fase se necessario. Se chiamato più volte, l'ultima invocazione ha la precedenza. Se chiamato da una sottoclasse dell'interfaccia Event, solo i valori specificati nel metodo initEvent vengono modificati, tutti gli altri attributi rimangono invariati.

### Vedi anche

* class [CustomEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
