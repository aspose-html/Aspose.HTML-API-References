---
title: Event.InitEvent
second_title: Aspose.HTML per riferimento API .NET
description: Event metodo. IlInitEvent Il metodo viene utilizzato per inizializzare il valore di anEvent creato tramite the IDocumentEvent interfaccia.
type: docs
weight: 110
url: /it/net/aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

Il`InitEvent` Il metodo viene utilizzato per inizializzare il valore di an[`Event`](../) creato tramite the [`IDocumentEvent`](../../idocumentevent/) interfaccia.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | String | Il tipo di evento. |
| bubbles | Boolean | se impostato su`VERO` [bolle]. |
| cancelable | Boolean | se impostato su`VERO` [annullabile]. |

### Osservazioni

Questo metodo può essere chiamato solo prima che l'evento sia stato inviato tramite il[`DispatchEvent`](../../ieventtarget/dispatchevent/) method, sebbene possa essere chiamato più volte durante quella fase, se necessario. Se chiamato più volte, l'invocazione finale ha la precedenza. Se chiamato da una sottoclasse dell'interfaccia Event, vengono modificati solo i valori specificati nel metodo initEvent, tutti gli altri attributi rimangono invariati.

### Guarda anche

* class [Event](../)
* spazio dei nomi [Aspose.Html.Dom.Events](../../event/)
* assemblea [Aspose.HTML](../../../)


