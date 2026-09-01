---
title: "Classe TimeEvent"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Classe com.aspose.html.dom.svg.events.TimeEvent. L'interfaccia TimeEvent fornisce informazioni contestuali specifiche associate agli eventi Time. I diversi tipi di eventi che possono verificarsi sono beginEvent, endEvent e repeatEvent."
type: docs

url: /it/java/com.aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

L'interfaccia TimeEvent fornisce informazioni contestuali specifiche associate agli eventi temporali. I diversi tipi di eventi che possono verificarsi sono: beginEvent, endEvent e repeatEvent.

```java
public class TimeEvent : Event
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Utilizzato per indicare se un evento è un evento di bubbling o meno. Se l'evento può propagarsi, il valore è true, altrimenti è false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Utilizzato per indicare se un evento può avere la sua azione predefinita annullata o meno. Se l'azione predefinita può essere annullata, il valore è true, altrimenti è false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Utilizzato per indicare il [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) il cui [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/) è attualmente in fase di elaborazione. Questo è particolarmente utile durante la cattura e il bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Restituisce true se preventDefault() è stato invocato mentre il valore dell'attributo cancelable è true, altrimenti false. |
| [getDetail](../../com.aspose.html.dom.svg.events/timeevent/detail/) Specifica alcune informazioni di dettaglio sull'Event, a seconda del tipo di evento. Per questo tipo di evento, indica il numero di ripetizione per l'animazione. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Utilizzato per indicare quale fase del flusso di eventi è attualmente in valutazione. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) L'attributo isTrusted deve restituire il valore a cui è stato inizializzato. Quando viene creato un evento, l'attributo deve essere inizializzato a false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Utilizzato per indicare il [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) a cui l'evento è stato originariamente inviato. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Utilizzato per specificare il tempo (in millisecondi relativi all'epoch) al quale l'evento è stato creato. Poiché alcuni sistemi potrebbero non fornire queste informazioni, il valore di timeStamp potrebbe non essere disponibile per tutti gli eventi. Quando non è disponibile, verrà restituito il valore 0. Esempi di tempo epoch sono il tempo di avvio del sistema o 0:0:0 UTC 1° gennaio 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Il nome dell'evento (non sensibile a maiuscole/minuscole). Il nome deve essere un nome XML. |
| [getView](../../com.aspose.html.dom.svg.events/timeevent/view/) L'attributo view identifica l'AbstractView [DOM2VIEWS] da cui è stato generato l'evento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Il metodo [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) è usato per inizializzare il valore di un [`Event`](../../com.aspose.html.dom.events/event/) creato tramite l'interfaccia [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/). |
| [initTimeEvent](../../com.aspose.html.dom.svg.events/timeevent/inittimeevent/)(String, IAbstractView, long) | Il metodo initTimeEvent è usato per inizializzare il valore di un TimeEvent creato tramite l'interfaccia DocumentEvent. Questo metodo può essere chiamato solo prima che il TimeEvent sia stato inviato tramite il metodo dispatchEvent, anche se può essere chiamato più volte durante quella fase se necessario. Se chiamato più volte, l'ultima invocazione ha la precedenza. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Se un evento è annullabile, il metodo [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) è usato per indicare che l'evento deve essere annullato, il che significa che nessuna azione predefinita normalmente eseguita dall'implementazione come risultato dell'evento avverrà. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invocare questo metodo impedisce che l'evento raggiunga i listener registrati dopo quello corrente e, quando viene inviato in un albero, impedisce anche che l'evento raggiunga altri oggetti. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Il metodo [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) è usato per impedire ulteriori propagazioni di un evento durante il flusso degli eventi. |

### Vedi anche

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
