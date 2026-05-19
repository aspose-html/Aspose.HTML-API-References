---
title: "IEventTarget.AddEventListener"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo IEventTarget. Il metodo EventTarget addEventListener imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target."
type: docs

url: /it/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

Il metodo addEventListener() di EventTarget imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target.

I target comuni sono Element, Document e Window, ma il target può essere qualsiasi oggetto che supporta gli eventi (come XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | String | Una String sensibile alle maiuscole/minuscole che rappresenta il tipo di evento da ascoltare. |
| listener | IEventListener | Accetta un'interfaccia implementata dall'utente che contiene i metodi da chiamare quando si verifica l'evento. |

## Osservazioni

Se un è aggiunto a un mentre sta elaborando un evento, non verrà attivato dalle azioni correnti ma potrebbe essere attivato in una fase successiva del flusso di eventi, come la fase di bubbling. Se più Event Listeners identici sono registrati sullo stesso con gli stessi parametri, le istanze duplicate vengono scartate. Non causano la chiamata doppia e, poiché vengono scartate, non è necessario rimuoverle con il metodo.

### Vedi anche

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

Il metodo addEventListener() di EventTarget imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target.

I target comuni sono Element, Document e Window, ma il target può essere qualsiasi oggetto che supporta gli eventi (come XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | String | Una String sensibile alle maiuscole/minuscole che rappresenta il tipo di evento da ascoltare. |
| listener | IEventListener | Accetta un'interfaccia implementata dall'utente che contiene i metodi da chiamare quando si verifica l'evento. |
| useCapture | Boolean | Se true, useCapture indica che l'utente desidera avviare la cattura. Dopo aver avviato la cattura, tutti gli eventi del tipo specificato verranno dispatciati ai registrati prima di essere dispatciati a qualsiasi Event Target sottostante nell'albero. Gli eventi che stanno facendo bubbling verso l'alto attraverso l'albero non attiveranno un designato per usare la cattura. |

## Osservazioni

Se un è aggiunto a un mentre sta elaborando un evento, non verrà attivato dalle azioni correnti ma potrebbe essere attivato in una fase successiva del flusso di eventi, come la fase di bubbling. Se più Event Listeners identici sono registrati sullo stesso con gli stessi parametri, le istanze duplicate vengono scartate. Non causano la chiamata doppia e, poiché vengono scartate, non è necessario rimuoverle con il metodo.

### Vedi anche

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
