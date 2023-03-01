---
title: IEventTarget.RemoveEventListener
second_title: Aspose.HTML per riferimento API .NET
description: IEventTarget metodo. Questo metodo consente la rimozione dei listener di eventi dalla destinazione dellevento. Se unIEventListener viene rimosso da unEventTarget mentre sta elaborando un evento non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi.
type: docs
weight: 30
url: /it/net/aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../ieventlistener/) viene rimosso da un[`EventTarget`](../../../aspose.html.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | String | Specifica il tipo di evento di[`IEventListener`](../../ieventlistener/) essere rimosso. |
| listener | IEventListener | IL[`IEventListener`](../../ieventlistener/) parametro indica il[`IEventListener`](../../ieventlistener/) essere rimosso. |

### Guarda anche

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* spazio dei nomi [Aspose.Html.Dom.Events](../../ieventtarget/)
* assemblea [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../ieventlistener/) viene rimosso da un[`EventTarget`](../../../aspose.html.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | String | Specifica il tipo di evento di[`IEventListener`](../../ieventlistener/) essere rimosso. |
| listener | IEventListener | IL[`IEventListener`](../../ieventlistener/) parametro indica il[`IEventListener`](../../ieventlistener/) essere rimosso. |
| useCapture | Boolean | Specifica se l'EventListener rimosso è stato registrato come listener di acquisizione o meno. Se un listener è stato registrato due volte, uno con acquisizione e uno senza, ognuno deve essere rimosso separatamente. La rimozione di un ascoltatore di acquisizione non influisce su una versione senza acquisizione dello stesso ascoltatore e viceversa. |

### Guarda anche

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* spazio dei nomi [Aspose.Html.Dom.Events](../../ieventtarget/)
* assemblea [Aspose.HTML](../../../)


