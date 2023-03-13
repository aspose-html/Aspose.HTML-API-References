---
title: EventTarget.DispatchEvent
second_title: Aspose.HTML per riferimento API .NET
description: EventTarget metodo. Questo metodo consente linvio di eventi nel modello di eventi delle implementazioni.
type: docs
weight: 20
url: /it/net/aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Questo metodo consente l'invio di eventi nel modello di eventi delle implementazioni.

```csharp
public bool DispatchEvent(Event @event)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| event | Event | Specifica il tipo di evento, il comportamento e le informazioni contestuali da utilizzare nell'elaborazione dell'evento. |

### Valore di ritorno

Il valore restituito di`DispatchEvent` indica se qualcuno dei listener che ha gestito l'evento ha chiamato[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) . Se[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) è stato chiamato il valore è falso, altrimenti il valore è vero.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../domexception/) |  |

### Osservazioni

Gli eventi inviati in questo modo avranno lo stesso comportamento di acquisizione e bubbling degli eventi inviati direttamente dall'implementazione. L'obiettivo dell'evento è il[`EventTarget`](../) in cui`DispatchEvent` si chiama.

### Guarda anche

* class [Event](../../../aspose.html.dom.events/event/)
* class [EventTarget](../)
* spazio dei nomi [Aspose.Html.Dom](../../eventtarget/)
* assemblea [Aspose.HTML](../../../)


