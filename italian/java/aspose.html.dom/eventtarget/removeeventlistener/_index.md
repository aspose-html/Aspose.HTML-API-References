---
title: "EventTarget.RemoveEventListener"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo EventTarget. Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso da un target mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi."
type: docs

url: /it/java/com.aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(String, DOMEventHandler, bool) {#removeeventlistener}

Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso da un elemento mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi.

```java
public void RemoveEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | String | Specifica il tipo di evento dell'elemento da rimuovere. |
| gestore | DOMEventHandler | Il parametro indica l'elemento da rimuovere. |
| useCapture | Boolean | Specifica se l'EventListener rimosso era registrato come listener di cattura o meno. Se un listener è stato registrato due volte, una con cattura e una senza, ciascuno deve essere rimosso separatamente. La rimozione di un listener di cattura non influisce su una versione non di cattura dello stesso listener, e viceversa. |

### Vedi anche

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener) {#removeeventlistener_1}

Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso da un elemento mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | String | Specifica il tipo di evento dell'elemento da rimuovere. |
| ascoltatore | IEventListener | Il parametro indica l'elemento da rimuovere. |

### Vedi anche

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_2}

Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso da un elemento mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | String | Specifica il tipo di evento dell'elemento da rimuovere. |
| ascoltatore | IEventListener | Il parametro indica l'elemento da rimuovere. |
| useCapture | Boolean | Specifica se l'EventListener rimosso era registrato come listener di cattura o meno. Se un listener è stato registrato due volte, una con cattura e una senza, ciascuno deve essere rimosso separatamente. La rimozione di un listener di cattura non influisce su una versione non di cattura dello stesso listener, e viceversa. |

### Vedi anche

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
