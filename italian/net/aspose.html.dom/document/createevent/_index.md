---
title: Document.CreateEvent
second_title: Aspose.HTML per riferimento API .NET
description: Document metodo. Crea un fileEvent di un tipo supportato dallimplementazione.
type: docs
weight: 880
url: /it/net/aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Crea un file[`Event`](../../../aspose.html.dom.events/event/) di un tipo supportato dall'implementazione.

```csharp
public Event CreateEvent(string eventType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| eventType | String | Il parametro eventType specifica il tipo di[`Event`](../../../aspose.html.dom.events/event/) interfaccia da creare.  Se il[`Event`](../../../aspose.html.dom.events/event/) l'interfaccia specificata è supportata dall'implementazione questo metodo restituirà un nuovo[`Event`](../../../aspose.html.dom.events/event/) del tipo di interfaccia richiesto. Se il[`Event`](../../../aspose.html.dom.events/event/)deve essere spedito tramite il[`DispatchEvent`](../../../aspose.html.dom.events/ieventtarget/dispatchevent/) metodo appropriato[`InitEvent`](../../../aspose.html.dom.events/event/initevent/) Il metodo deve essere chiamato dopo la creazione per inizializzare il file[`Event`](../../../aspose.html.dom.events/event/) s valori. |

### Valore di ritorno

Il nuovo creato[`Event`](../../../aspose.html.dom.events/event/)

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: sollevato se l'implementazione non supporta il tipo di[`Event`](../../../aspose.html.dom.events/event/) interfaccia richiesta |

### Guarda anche

* class [Event](../../../aspose.html.dom.events/event/)
* class [Document](../)
* spazio dei nomi [Aspose.Html.Dom](../../document/)
* assemblea [Aspose.HTML](../../../)


