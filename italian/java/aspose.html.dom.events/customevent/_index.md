---
title: "CustomEvent Classe"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.dom.events.CustomEvent classe. Gli eventi che utilizzano l'interfaccia CustomEvent possono essere usati per trasportare dati personalizzati."
type: docs

url: /it/java/com.aspose.html.dom.events/customevent/
---
## CustomEvent class

Gli eventi che utilizzano l'interfaccia CustomEvent possono essere usati per trasportare dati personalizzati.

```java
public class CustomEvent : Event
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CustomEvent](customevent/#constructor)(String) | Inizializza una nuova istanza della classe `CustomEvent`. |
| [CustomEvent](customevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Utilizzato per indicare se un evento è un evento di bubbling o meno. Se l'evento può propagarsi, il valore è true, altrimenti è false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Utilizzato per indicare se un evento può avere la sua azione predefinita annullata o meno. Se l'azione predefinita può essere annullata, il valore è true, altrimenti è false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Utilizzato per indicare il [`IEventTarget`](../ieventtarget/) i cui [`IEventListener`](../ieventlistener/) sono attualmente in fase di elaborazione. Questo è particolarmente utile durante il capturing e il bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Restituisce true se preventDefault() è stato invocato mentre il valore dell'attributo cancelable è true, altrimenti false. |
| [getDetail](../../com.aspose.html.dom.events/customevent/detail/) Ottiene i dati personalizzati. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Utilizzato per indicare quale fase del flusso di eventi è attualmente in valutazione. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) L'attributo isTrusted deve restituire il valore a cui è stato inizializzato. Quando viene creato un evento, l'attributo deve essere inizializzato a false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Utilizzato per indicare il [`IEventTarget`](../ieventtarget/) a cui l'evento è stato originariamente inviato. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Utilizzato per specificare il tempo (in millisecondi relativi all'epoch) al quale l'evento è stato creato. Poiché alcuni sistemi potrebbero non fornire queste informazioni, il valore di timeStamp potrebbe non essere disponibile per tutti gli eventi. Quando non è disponibile, verrà restituito il valore 0. Esempi di tempo epoch sono il tempo di avvio del sistema o 0:0:0 UTC 1° gennaio 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Il nome dell'evento (non sensibile a maiuscole/minuscole). Il nome deve essere un nome XML. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [initCustomEvent](../../com.aspose.html.dom.events/customevent/initcustomevent/)(String, bool, bool, object) | /// Il metodo [`InitEvent`](../event/initevent/) è usato per inizializzare il valore di un [`Event`](../event/) creato tramite l'interfaccia [`IDocumentEvent`](../idocumentevent/). |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Il metodo [`InitEvent`](../event/initevent/) è usato per inizializzare il valore di un [`Event`](../event/) creato tramite l'interfaccia[`IDocumentEvent`](../idocumentevent/) . |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Se un evento è annullabile, il metodo [`PreventDefault`](../event/preventdefault/) è usato per indicare che l'evento deve essere annullato, il che significa che nessuna azione predefinita normalmente eseguita dall'implementazione a seguito dell'evento avverrà. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invocare questo metodo impedisce che l'evento raggiunga i listener registrati dopo quello corrente e, quando viene inviato in un albero, impedisce anche che l'evento raggiunga altri oggetti. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Il metodo [`StopPropagation`](../event/stoppropagation/) è usato per impedire ulteriori propagazioni di un evento durante il flusso dell'evento. |

### Vedi anche

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
