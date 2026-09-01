---
title: "Classe ErrorEvent"
second_title: "Aspose.HTML per Java Riferimento API"
description: "classe com.aspose.html.dom.events.ErrorEvent. L'ErrorEvent fornisce informazioni contestuali su errori verificatisi durante l'esecuzione"
type: docs

url: /it/java/com.aspose.html.dom.events/errorevent/
---
## ErrorEvent class

L'ErrorEvent fornisce informazioni contestuali su errori verificatisi durante l'esecuzione.

```java
public class ErrorEvent : Event
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(Exception) | Inizializza una nuova istanza della classe `ErrorEvent`. |
| [ErrorEvent](errorevent/#constructor)(IDictionary&lt;String, object&gt;) |  |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Utilizzato per indicare se un evento è un evento di bubbling o meno. Se l'evento può propagarsi, il valore è true, altrimenti è false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Utilizzato per indicare se un evento può avere la sua azione predefinita annullata o meno. Se l'azione predefinita può essere annullata, il valore è true, altrimenti è false. |
| [getColNo](../../com.aspose.html.dom.events/errorevent/colno/) L'attributo colno deve restituire il valore con cui è stato inizializzato. Quando l'oggetto è creato, questo attributo deve essere inizializzato a zero. Rappresenta il numero di colonna in cui si è verificato l'errore nello script. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Utilizzato per indicare il [`IEventTarget`](../ieventtarget/) i cui [`IEventListener`](../ieventlistener/) sono attualmente in fase di elaborazione. Questo è particolarmente utile durante il capturing e il bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Restituisce true se preventDefault() è stato invocato mentre il valore dell'attributo cancelable è true, altrimenti false. |
| [getError](../../com.aspose.html.dom.events/errorevent/error/) L'attributo error deve restituire il valore con cui è stato inizializzato. Quando l'oggetto è creato, questo attributo deve essere inizializzato a null. Quando appropriato, viene impostato sull'oggetto che rappresenta l'errore (ad esempio l'oggetto eccezione nel caso di un'eccezione DOM non catturata). |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Utilizzato per indicare quale fase del flusso di eventi è attualmente in valutazione. |
| [getFileName](../../com.aspose.html.dom.events/errorevent/filename/) L'attributo filename deve restituire il valore con cui è stato inizializzato. Quando l'oggetto è creato, questo attributo deve essere inizializzato a una Stringa vuota. Rappresenta l'URL assoluto dello script in cui l'errore si è verificato originariamente. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) L'attributo isTrusted deve restituire il valore a cui è stato inizializzato. Quando viene creato un evento, l'attributo deve essere inizializzato a false. |
| [getLineNo](../../com.aspose.html.dom.events/errorevent/lineno/) L'attributo lineno deve restituire il valore a cui è stato inizializzato. Quando l'oggetto viene creato, questo attributo deve essere inizializzato a zero. Rappresenta il numero di riga in cui si è verificato l'errore nello script. |
| [getMessage](../../com.aspose.html.dom.events/errorevent/message/) L'attributo message deve restituire il valore a cui è stato inizializzato. Quando l'oggetto viene creato, questo attributo deve essere inizializzato alla stringa vuota. Rappresenta il messaggio di errore. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Utilizzato per indicare il [`IEventTarget`](../ieventtarget/) a cui l'evento è stato originariamente inviato. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Utilizzato per specificare il tempo (in millisecondi relativi all'epoch) al quale l'evento è stato creato. Poiché alcuni sistemi potrebbero non fornire queste informazioni, il valore di timeStamp potrebbe non essere disponibile per tutti gli eventi. Quando non è disponibile, verrà restituito il valore 0. Esempi di tempo epoch sono il tempo di avvio del sistema o 0:0:0 UTC 1° gennaio 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Il nome dell'evento (non sensibile a maiuscole/minuscole). Il nome deve essere un nome XML. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Il metodo [`InitEvent`](../event/initevent/) è usato per inizializzare il valore di un [`Event`](../event/) creato tramite l'interfaccia[`IDocumentEvent`](../idocumentevent/) . |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Se un evento è annullabile, il metodo [`PreventDefault`](../event/preventdefault/) è usato per indicare che l'evento deve essere annullato, il che significa che nessuna azione predefinita normalmente eseguita dall'implementazione a seguito dell'evento avverrà. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invocare questo metodo impedisce che l'evento raggiunga i listener registrati dopo quello corrente e, quando viene inviato in un albero, impedisce anche che l'evento raggiunga altri oggetti. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Il metodo [`StopPropagation`](../event/stoppropagation/) è usato per impedire ulteriori propagazioni di un evento durante il flusso dell'evento. |

### Vedi anche

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
