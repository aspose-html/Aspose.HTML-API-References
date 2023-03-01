---
title: Interface IEventTarget
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Events.IEventTarget interfaccia. IlEventTarget linterfaccia è implementata da tutti i nodi in unimplementazione che supporta il modello di eventi DOM. Pertanto questa interfaccia può essere ottenuta utilizzando metodi di cast specifici dellassociazione su unistanza dellinterfaccia del nodo. Linterfaccia consente la registrazione e la rimozione di Event Listener su UNEventTarget e linvio di eventi a quelloIEventTarget .
type: docs
weight: 810
url: /it/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

Il[`EventTarget`](../../aspose.html.dom/eventtarget/) l'interfaccia è implementata da tutti i nodi in un'implementazione che supporta il modello di eventi DOM. Pertanto, questa interfaccia può essere ottenuta utilizzando metodi di cast specifici dell'associazione su un'istanza dell'interfaccia del nodo. L'interfaccia consente la registrazione e la rimozione di Event Listener su UN[`EventTarget`](../../aspose.html.dom/eventtarget/) e l'invio di eventi a quello`IEventTarget` .

```csharp
public interface IEventTarget
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(string, IEventListener) | Questo metodo consente la registrazione dei listener di eventi sul target dell'evento. |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener, bool) | Questo metodo consente la registrazione dei listener di eventi sul target dell'evento. |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Questo metodo consente l'invio di eventi nel modello di eventi delle implementazioni. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(string, IEventListener) | Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../ieventlistener/) viene rimosso da un[`EventTarget`](../../aspose.html.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener, bool) | Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../ieventlistener/) viene rimosso da un[`EventTarget`](../../aspose.html.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi. |

### Guarda anche

* spazio dei nomi [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* assemblea [Aspose.HTML](../../)


