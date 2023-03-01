---
title: EventTarget.RemoveEventListener
second_title: Aspose.HTML per riferimento API .NET
description: EventTarget metodo. Questo metodo consente la rimozione dei listener di eventi dalla destinazione dellevento. Se unIEventListener viene rimosso da unEventTarget mentre sta elaborando un evento non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi.
type: docs
weight: 40
url: /it/net/aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) viene rimosso da un[`EventTarget`](../) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | String | Specifica il tipo di evento di[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) essere rimosso. |
| handler | DOMEventHandler | IL[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/) parametro indica il[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) essere rimosso. |
| useCapture | Boolean | Specifica se l'EventListener rimosso è stato registrato come listener di acquisizione o meno. Se un listener è stato registrato due volte, uno con acquisizione e uno senza, ognuno deve essere rimosso separatamente. La rimozione di un ascoltatore di acquisizione non influisce su una versione senza acquisizione dello stesso ascoltatore e viceversa. |

### Guarda anche

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* spazio dei nomi [Aspose.Html.Dom](../../eventtarget/)
* assemblea [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) viene rimosso da un[`EventTarget`](../) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | String | Specifica il tipo di evento di[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) essere rimosso. |
| listener | IEventListener | IL[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) parametro indica il[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) essere rimosso. |

### Guarda anche

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* spazio dei nomi [Aspose.Html.Dom](../../eventtarget/)
* assemblea [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) viene rimosso da un[`EventTarget`](../) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | String | Specifica il tipo di evento di[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) essere rimosso. |
| listener | IEventListener | IL[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) parametro indica il[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) essere rimosso. |
| useCapture | Boolean | Specifica se l'EventListener rimosso è stato registrato come listener di acquisizione o meno. Se un listener è stato registrato due volte, uno con acquisizione e uno senza, ognuno deve essere rimosso separatamente. La rimozione di un ascoltatore di acquisizione non influisce su una versione senza acquisizione dello stesso ascoltatore e viceversa. |

### Guarda anche

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* spazio dei nomi [Aspose.Html.Dom](../../eventtarget/)
* assemblea [Aspose.HTML](../../../)


