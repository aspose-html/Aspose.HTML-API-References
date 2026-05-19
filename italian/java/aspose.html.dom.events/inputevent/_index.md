---
title: "Classe InputEvent"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.dom.events.InputEvent. Gli eventi di input vengono inviati come notifiche ogni volta che il DOM viene aggiornato"
type: docs

url: /it/java/com.aspose.html.dom.events/inputevent/
---
## InputEvent class

Gli eventi di input vengono inviati come notifiche ogni volta che il DOM viene aggiornato.

```java
public class InputEvent : UIEvent
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [InputEvent](inputevent/#constructor)(String) | Inizializza una nuova istanza della classe `InputEvent`. |
| [InputEvent](inputevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Utilizzato per indicare se un evento è un evento di bubbling o meno. Se l'evento può propagarsi, il valore è true, altrimenti il valore è false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Utilizzato per indicare se un evento può avere la sua azione predefinita annullata. Se l'azione predefinita può essere annullata, il valore è true, altrimenti il valore è false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Utilizzato per indicare il [`IEventTarget`](../ieventtarget/) i cui [`IEventListener`](../ieventlistener/) sono attualmente in fase di elaborazione. Questo è particolarmente utile durante il capturing e il bubbling. |
| [getData](../../com.aspose.html.dom.events/inputevent/data/) I dati contengono il valore dei caratteri generati da un metodo di input. Questo PUÒ essere un singolo carattere Unicode o una sequenza non vuota di caratteri Unicode [Unicode]. I caratteri DEVONO essere normalizzati come definito dalla forma di normalizzazione Unicode NFC, definita in [UAX15]. Questo attributo PUÒ contenere la stringa vuota. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Restituisce true se preventDefault() è stato invocato mentre il valore dell'attributo cancelable è true, altrimenti false. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Specifica alcune informazioni di dettaglio sull'Event, a seconda del tipo di evento. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Utilizzato per indicare quale fase del flusso di eventi è attualmente in valutazione. |
| [getIsComposing](../../com.aspose.html.dom.events/inputevent/iscomposing/) true se l'evento di input si verifica come parte di una sessione di composizione, cioè dopo un evento compositionstart e prima del corrispondente evento compositionend. Il valore non inizializzato di questo attributo DEVE essere false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) L'attributo isTrusted deve restituire il valore a cui è stato inizializzato. Quando un evento viene creato, l'attributo deve essere inizializzato a false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Utilizzato per indicare il [`IEventTarget`](../ieventtarget/) a cui l'evento è stato originariamente inviato. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Utilizzato per specificare il tempo (in millisecondi relativi all'epoca) al quale l'evento è stato creato. Poiché alcuni sistemi potrebbero non fornire queste informazioni, il valore di timeStamp potrebbe non essere disponibile per tutti gli eventi. Quando non disponibile, verrà restituito il valore 0. Esempi di tempo epoch sono il tempo di avvio del sistema o 0:0:0 UTC 1° gennaio 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Il nome dell'evento (non sensibile a maiuscole/minuscole). Il nome deve essere un nome XML. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) L'attributo view identifica la Window da cui è stato generato l'evento. Il valore non inizializzato di questo attributo DEVE essere null. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Il metodo [`InitEvent`](../event/initevent/) è usato per inizializzare il valore di un [`Event`](../event/) creato tramite l'interfaccia [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Se un evento è annullabile, il metodo [`PreventDefault`](../event/preventdefault/) è usato per indicare che l'evento deve essere annullato, il che significa che qualsiasi azione predefinita normalmente eseguita dall'implementazione a seguito dell'evento non avverrà. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invocare questo metodo impedisce che l'evento raggiunga qualsiasi listener registrato dopo quello corrente e, quando inviato in un albero, impedisce anche che l'evento raggiunga altri oggetti. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Il metodo [`StopPropagation`](../event/stoppropagation/) è usato per impedire ulteriori propagazioni di un evento durante il flusso dell'evento. |

### Vedi anche

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
