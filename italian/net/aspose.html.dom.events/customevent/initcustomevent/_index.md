---
title: CustomEvent.InitCustomEvent
second_title: Aspose.HTML per riferimento API .NET
description: CustomEvent metodo. /// IlInitEvent Il metodo viene utilizzato per inizializzare il valore di anEvent creato attraverso ilIDocumentEvent interfaccia.
type: docs
weight: 30
url: /it/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Il[`InitEvent`](../../event/initevent/) Il metodo viene utilizzato per inizializzare il valore di an[`Event`](../../event/) creato attraverso il[`IDocumentEvent`](../../idocumentevent/) interfaccia.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | String | Il tipo di evento. |
| bubbles | Boolean | se impostato su`VERO` [bolle]. |
| cancelable | Boolean | se impostato su`VERO` [annullabile]. |
| detail | Object | I dati personalizzati. |

### Osservazioni

Questo metodo può essere chiamato solo prima che l'evento sia stato inviato tramite il[`DispatchEvent`](../../ieventtarget/dispatchevent/) method, sebbene possa essere chiamato più volte durante quella fase, se necessario. Se chiamato più volte, l'invocazione finale ha la precedenza. Se chiamato da una sottoclasse dell'interfaccia Event, vengono modificati solo i valori specificati nel metodo initEvent, tutti gli altri attributi rimangono invariati.

### Guarda anche

* class [CustomEvent](../)
* spazio dei nomi [Aspose.Html.Dom.Events](../../customevent/)
* assemblea [Aspose.HTML](../../../)


