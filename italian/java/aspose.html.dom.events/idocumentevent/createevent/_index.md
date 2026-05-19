---
title: "IDocumentEvent.CreateEvent"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo IDocumentEvent. Il metodo createEvent è usato per creare Event quando è scomodo o non necessario per l'utente creare un Event da solo."
type: docs

url: /it/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Il metodo createEvent è utilizzato per creare Event quando è scomodo o non necessario che l'utente crei un Event da solo.

```java
public Event CreateEvent(String eventType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| eventType | String | Il parametro eventType specifica il tipo di interfaccia da creare. Se l'interfaccia specificata è supportata dall'implementazione, questo metodo restituirà una nuova dell'interfaccia richiesta. Se il è da dispatciare tramite il metodo, il metodo appropriato deve essere chiamato dopo la creazione per inizializzare i valori. Il metodo è usato per creare s quando è scomodo o non necessario per l'utente crearli da soli. Nei casi in cui l'implementazione fornita è insufficiente, gli utenti possono fornire le proprie implementazioni da usare con il metodo. |

### Valore di ritorno

Restituisce il nuovo evento creato del tipo di evento specificato.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Sollevato se l'implementazione non supporta il tipo di interfaccia richiesto |

### Vedi anche

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
