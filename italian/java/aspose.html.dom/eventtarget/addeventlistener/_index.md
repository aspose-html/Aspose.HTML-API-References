---
title: "EventTarget.AddEventListener"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo EventTarget. Il metodo addEventListener dell'interfaccia EventTarget imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target."
type: docs

url: /it/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

Il metodo addEventListener() dell'interfaccia [EventTarget ](T:com.aspose.html.dom.EventTarget) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target.

Funziona aggiungendo una funzione o un oggetto che implementa [EventListener](T:com.aspose.html.dom.events.IEventListener) all'elenco dei listener di eventi per il tipo di evento specificato sull'EventTarget su cui viene chiamato. Se la funzione o l'oggetto è già presente nell'elenco dei listener di eventi per questo target, non viene aggiunto una seconda volta.

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | String | Il tipo di evento per cui l'utente si sta registrando |
| gestore | DOMEventHandler | Accetta un gestore da chiamare quando l'evento si verifica. |
| useCapture | Boolean | Se true, `useCapture` indica che l'utente desidera avviare la cattura. Dopo aver avviato la cattura, tutti gli eventi del tipo specificato verranno dispatciati ai listener registrati prima di essere dispatciati a qualsiasi Event Target sottostante nell'albero. Gli eventi che fanno bubbling verso l'alto nell'albero non attiveranno un listener designato per usare la cattura. |

## Osservazioni

Se un listener viene aggiunto a un target mentre sta elaborando un evento, non verrà attivato dalle azioni correnti ma potrà essere attivato in una fase successiva del flusso di eventi, come la fase di bubbling. Se più Event Listeners identici sono registrati sullo stesso target con gli stessi parametri, le istanze duplicate vengono scartate. Non causano la chiamata doppia del listener e, poiché vengono scartate, non è necessario rimuoverle con il metodo.

### Vedi anche

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

Il metodo addEventListener() dell'interfaccia [`EventTarget `](../) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target.

Funziona aggiungendo una funzione o un oggetto che implementa [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) all'elenco dei listener di eventi per il tipo di evento specificato sull'EventTarget su cui viene chiamato. Se la funzione o l'oggetto è già presente nell'elenco dei listener di eventi per questo target, non viene aggiunto una seconda volta.

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | String | Il tipo di evento per cui l'utente si sta registrando |
| ascoltatore | IEventListener | Accetta un'interfaccia implementata dall'utente che contiene i metodi da chiamare quando si verifica l'evento. |

## Osservazioni

Se un listener viene aggiunto a un target mentre sta elaborando un evento, non verrà attivato dalle azioni correnti ma potrà essere attivato in una fase successiva del flusso di eventi, come la fase di bubbling. Se più Event Listeners identici sono registrati sullo stesso target con gli stessi parametri, le istanze duplicate vengono scartate. Non causano la chiamata doppia del listener e, poiché vengono scartate, non è necessario rimuoverle con il metodo.

### Vedi anche

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

Il metodo addEventListener() dell'interfaccia [EventTarget ](T:com.aspose.html.dom.EventTarget) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target.

Funziona aggiungendo una funzione o un oggetto che implementa [EventListener](T:com.aspose.html.dom.events.IEventListener) all'elenco dei listener di eventi per il tipo di evento specificato sull'EventTarget su cui viene chiamato. Se la funzione o l'oggetto è già presente nell'elenco dei listener di eventi per questo target, non viene aggiunto una seconda volta.

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | String | Il tipo di evento per cui l'utente si sta registrando |
| ascoltatore | IEventListener | Accetta un'interfaccia implementata dall'utente che contiene i metodi da chiamare quando si verifica l'evento. |
| useCapture | Boolean | Se true, `useCapture` indica che l'utente desidera avviare la cattura. Dopo aver avviato la cattura, tutti gli eventi del tipo specificato verranno dispatciati ai listener registrati prima di essere dispatciati a qualsiasi Event Target sottostante nell'albero. Gli eventi che fanno bubbling verso l'alto nell'albero non attiveranno un listener designato per usare la cattura. |

## Osservazioni

Se un listener viene aggiunto a un target mentre sta elaborando un evento, non verrà attivato dalle azioni correnti ma potrà essere attivato in una fase successiva del flusso di eventi, come la fase di bubbling. Se più Event Listeners identici sono registrati sullo stesso target con gli stessi parametri, le istanze duplicate vengono scartate. Non causano la chiamata doppia del listener e, poiché vengono scartate, non è necessario rimuoverle con il metodo.

### Vedi anche

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
