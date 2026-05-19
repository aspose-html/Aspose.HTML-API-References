---
title: "Classe MediaQueryList"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.window.MediaQueryList. Un oggetto MediaQueryList memorizza informazioni su una media query applicata a un documento con supporto sia per il matching immediato sia per quello basato su eventi rispetto allo stato del documento. Vedere la specifica del modulo CSSOM View https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /it/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

Un oggetto MediaQueryList memorizza informazioni su una query media applicata a un documento, con supporto sia per il matching immediato sia basato su eventi rispetto allo stato del documento. Vedi la specifica del modulo CSSOM View: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) Documento associato all'oggetto Context. |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) Un valore booleano che restituisce true se il documento corrisponde attualmente alla lista di media query, o false in caso contrario. |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) Una stringa che rappresenta una media query serializzata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Il metodo addEventListener() dell'interfaccia [`EventTarget `](../../com.aspose.html.dom/eventtarget/) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Il metodo addEventListener() dell'interfaccia [EventTarget ](T:com.aspose.html.dom.EventTarget) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Il metodo addEventListener() dell'interfaccia [EventTarget ](T:com.aspose.html.dom.EventTarget) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | Aggiungi listener per l'evento di cambiamento dello stato di corrispondenza di MediaQueryList. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Esegue la distribuzione di un Event al [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) specificato, (sincronamente) invocando gli EventListener interessati nell'ordine appropriato. Le regole normali di elaborazione degli eventi (inclusa la fase di cattura e quella di bubbling opzionale) si applicano anche agli eventi distribuiti manualmente con [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset di risorse non gestite. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | Rimuovi listener per l'evento di cambiamento dello stato di corrispondenza di MediaQueryList. |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | Evento generato sul MediaQueryList quando lo stato di corrispondenza cambia. |

### Vedi anche

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
