---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo IEventTarget. Il metodo `addEventListener` di EventTarget imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target."
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
| tipo | String | Una Stringa sensibile al maiuscolo/minuscolo che rappresenta il tipo di evento da ascoltare. |
| ascoltatore | IEventListener | Accetta un'interfaccia implementata dall'utente che contiene i metodi da chiamare quando si verifica l'evento. |

## Osservazioni

Se un listener viene aggiunto a un target mentre sta elaborando un evento, non verrà attivato dalle azioni correnti ma potrà essere attivato in una fase successiva del flusso di eventi, come la fase di bubbling. Se più Event Listeners identici sono registrati sullo stesso target con gli stessi parametri, le istanze duplicate vengono scartate. Non causano la chiamata doppia del listener e, poiché vengono scartate, non è necessario rimuoverle con il metodo.

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
| tipo | String | Una Stringa sensibile al maiuscolo/minuscolo che rappresenta il tipo di evento da ascoltare. |
| ascoltatore | IEventListener | Accetta un'interfaccia implementata dall'utente che contiene i metodi da chiamare quando si verifica l'evento. |
| useCapture | Boolean | Se true, `useCapture` indica che l'utente desidera avviare la cattura. Dopo aver avviato la cattura, tutti gli eventi del tipo specificato verranno dispatciati ai listener registrati prima di essere dispatciati a qualsiasi Event Target sottostante nell'albero. Gli eventi che fanno bubbling verso l'alto nell'albero non attiveranno un listener designato per usare la cattura. |

## Osservazioni

Se un listener viene aggiunto a un target mentre sta elaborando un evento, non verrà attivato dalle azioni correnti ma potrà essere attivato in una fase successiva del flusso di eventi, come la fase di bubbling. Se più Event Listeners identici sono registrati sullo stesso target con gli stessi parametri, le istanze duplicate vengono scartate. Non causano la chiamata doppia del listener e, poiché vengono scartate, non è necessario rimuoverle con il metodo.

### Vedi anche

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
