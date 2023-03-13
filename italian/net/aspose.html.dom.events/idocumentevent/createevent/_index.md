---
title: IDocumentEvent.CreateEvent
second_title: Aspose.HTML per riferimento API .NET
description: IDocumentEvent metodo. Crea un fileEvent di un tipo supportato dallimplementazione.
type: docs
weight: 10
url: /it/net/aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Crea un file[`Event`](../../event/) di un tipo supportato dall'implementazione.

```csharp
public Event CreateEvent(string eventType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| eventType | String | Il parametro eventType specifica il tipo di[`Event`](../../event/) interfaccia da creare.  Se il[`Event`](../../event/)l'interfaccia specificata è supportata dall'implementazione questo metodo restituirà un new [`Event`](../../event/) del tipo di interfaccia richiesto. Se il[`Event`](../../event/)deve essere spedito tramite il[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) metodo appropriato [`InitEvent`](../../event/initevent/) Il metodo deve essere chiamato dopo la creazione per inizializzare il[`Event`](../../event/) s valori. |

### Valore di ritorno

Il nuovo creato[`Event`](../../event/)

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: sollevato se l'implementazione non supporta il tipo di[`Event`](../../event/) interfaccia richiesta |

### Guarda anche

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* spazio dei nomi [Aspose.Html.Dom.Events](../../idocumentevent/)
* assemblea [Aspose.HTML](../../../)


