---
title: IEventTarget.AddEventListener
second_title: Aspose.HTML per riferimento API .NET
description: IEventTarget metodo. Questo metodo consente la registrazione dei listener di eventi sul target dellevento.
type: docs
weight: 10
url: /it/net/aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(string, IEventListener) {#addeventlistener}

Questo metodo consente la registrazione dei listener di eventi sul target dell'evento.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | String | Il tipo di evento per il quale l'utente si sta registrando |
| listener | IEventListener | Prende un'interfaccia implementata dall'utente che contiene i metodi da chiamare quando si verifica l'evento. |

### Osservazioni

Se an[`IEventListener`](../../ieventlistener/) viene aggiunto ad un[`EventTarget`](../../../aspose.html.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti ma potrebbe essere attivato durante una fase successiva del flusso di eventi, come la fase di bubbling.

Se sullo stesso sono registrati più Event Listener identici[`EventTarget`](../../../aspose.html.dom/eventtarget/)con gli stessi parametri le istanze duplicate vengono scartate. Non provocano il[`IEventListener`](../../ieventlistener/) essere chiamati due volte e poiché vengono scartati non è necessario rimuoverli con the [`RemoveEventListener`](../removeeventlistener/) metodo.

### Guarda anche

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* spazio dei nomi [Aspose.Html.Dom.Events](../../ieventtarget/)
* assemblea [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_1}

Questo metodo consente la registrazione dei listener di eventi sul target dell'evento.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | String | Il tipo di evento per il quale l'utente si sta registrando |
| listener | IEventListener | Prende un'interfaccia implementata dall'utente che contiene i metodi da chiamare quando si verifica l'evento. |
| useCapture | Boolean | Se true, useCapture indica che l'utente desidera avviare l'acquisizione. Dopo l'avvio dell'acquisizione, tutti gli eventi del tipo specificato verranno inviati all'oggetto Registered [`IEventListener`](../../ieventlistener/) prima di essere inviato a qualsiasi Event Target sotto di loro nell'albero. Gli eventi che stanno ribollendo verso l'alto attraverso l'albero non attiveranno un[`IEventListener`](../../ieventlistener/) designato per utilizzare la cattura. |

### Osservazioni

Se an[`IEventListener`](../../ieventlistener/) viene aggiunto ad un[`EventTarget`](../../../aspose.html.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti ma potrebbe essere attivato durante una fase successiva del flusso di eventi, come la fase di bubbling.

Se sullo stesso sono registrati più Event Listener identici[`EventTarget`](../../../aspose.html.dom/eventtarget/)con gli stessi parametri le istanze duplicate vengono scartate. Non provocano il[`IEventListener`](../../ieventlistener/) essere chiamati due volte e poiché vengono scartati non è necessario rimuoverli con the [`RemoveEventListener`](../removeeventlistener/) metodo.

### Guarda anche

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* spazio dei nomi [Aspose.Html.Dom.Events](../../ieventtarget/)
* assemblea [Aspose.HTML](../../../)


