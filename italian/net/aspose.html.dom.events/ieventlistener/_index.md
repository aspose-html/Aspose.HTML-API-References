---
title: Interface IEventListener
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Events.IEventListener interfaccia. IlIEventListenerlinterfaccia è il metodo principale per la gestione degli eventi. Gli utenti implementano ilIEventListener interfaccia e registrare il loro ascoltatore su unEventTarget usando ilAddEventListener method. Gli utenti dovrebbero anche rimuovere il loroIEventListener dal suoEventTarget dopo aver completato lutilizzo dellascoltatore.
type: docs
weight: 800
url: /it/net/aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

Il`IEventListener`l'interfaccia è il metodo principale per la gestione degli eventi. Gli utenti implementano il`IEventListener` interfaccia e registrare il loro ascoltatore su un[`EventTarget`](../../aspose.html.dom/eventtarget/) usando il[`AddEventListener`](../../aspose.html.dom/eventtarget/addeventlistener/) method. Gli utenti dovrebbero anche rimuovere il loro`IEventListener` dal suo[`EventTarget`](../../aspose.html.dom/eventtarget/) dopo aver completato l'utilizzo dell'ascoltatore.

```csharp
public interface IEventListener
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [HandleEvent](../../aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Questo metodo viene chiamato ogni volta che si verifica un evento del tipo per il quale il`IEventListener` l'interfaccia è stata registrata. |

### Osservazioni

Quando un Nodo viene copiato utilizzando il metodo cloneNode, gli Event Listener collegati al Nodo sorgente non sono collegati al Nodo copiato. Se l'utente desidera che gli stessi Event Listener vengano aggiunti alla copia appena creata, l'utente deve aggiungerli manualmente.

### Guarda anche

* spazio dei nomi [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* assemblea [Aspose.HTML](../../)


