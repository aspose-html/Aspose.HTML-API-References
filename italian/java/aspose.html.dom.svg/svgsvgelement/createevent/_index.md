---
title: "SVGSVGElement.CreateEvent"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo SVGSVGElement. Crea un Event di un tipo supportato dall’implementazione."
type: docs

url: /it/java/com.aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Creare un [`Event`](../../../com.aspose.html.dom.events/event/) di un tipo supportato dall’implementazione.

```java
public Event CreateEvent(String eventType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| eventType | String | Il parametro eventType specifica il tipo di interfaccia [`Event`](../../../com.aspose.html.dom.events/event/) da creare.Se l'interfaccia [`Event`](../../../com.aspose.html.dom.events/event/) specificata è supportata dall'implementazione, questo metodo restituirà un nuovo[`Event`](../../../com.aspose.html.dom.events/event/) del tipo di interfaccia richiesto. Se il [`Event`](../../../com.aspose.html.dom.events/event/) deve essere inviato tramite il metodo [`DispatchEvent`](../../../com.aspose.html.dom/eventtarget/dispatchevent/) il metodo appropriato[`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) deve essere chiamato dopo la creazione per inizializzare i valori del [`Event`](../../../com.aspose.html.dom.events/event/). |

### Valore di ritorno

Il nuovo [`Event`](../../../com.aspose.html.dom.events/event/) creato

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Sollevato se l'implementazione non supporta il tipo di interfaccia [`Event`](../../../com.aspose.html.dom.events/event/) richiesto |

### Vedi anche

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
