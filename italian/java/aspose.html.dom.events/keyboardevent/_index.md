---
title: "Classe KeyboardEvent"
second_title: "Riferimento API Aspose.HTML per Java"
description: "com.aspose.html.dom.events.KeyboardEvent class. L'interfaccia KeyboardEvent fornisce informazioni contestuali specifiche associate ai dispositivi di tastiera. Ogni evento di tastiera fa riferimento a un tasto mediante un valore. Gli eventi di tastiera sono comunemente indirizzati all'elemento che ha il focus."
type: docs

url: /it/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

L'interfaccia KeyboardEvent fornisce informazioni contestuali specifiche associate ai dispositivi di tastiera. Ogni evento di tastiera fa riferimento a un tasto mediante un valore. Gli eventi di tastiera sono comunemente indirizzati all'elemento che ha il focus.

```java
public class KeyboardEvent : UIEvent
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | Inizializza una nuova istanza della classe `KeyboardEvent`. |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) true se il modificatore del tasto Alt (alternativo) (o "Option") era attivo. Il valore non inizializzato di questo attributo DEVE essere false. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Utilizzato per indicare se un evento è un evento di bubbling o meno. Se l'evento può propagarsi, il valore è true, altrimenti il valore è false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Utilizzato per indicare se un evento può avere la sua azione predefinita annullata. Se l'azione predefinita può essere annullata, il valore è true, altrimenti il valore è false. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) Il codice contiene una Stringa che identifica il tasto fisico premuto. Il valore non è influenzato dal layout della tastiera corrente o dallo stato dei modificatori, quindi un determinato tasto restituirà sempre lo stesso valore. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) true se il modificatore del tasto Control (controllo) era attivo. Il valore non inizializzato di questo attributo DEVE essere false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Utilizzato per indicare il [`IEventTarget`](../ieventtarget/) i cui [`IEventListener`](../ieventlistener/) sono attualmente in fase di elaborazione. Questo è particolarmente utile durante il capturing e il bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Restituisce true se preventDefault() è stato invocato mentre il valore dell'attributo cancelable è true, altrimenti false. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Specifica alcune informazioni di dettaglio sull'Event, a seconda del tipo di evento. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Utilizzato per indicare quale fase del flusso di eventi è attualmente in valutazione. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) true se l'evento di tasto si verifica come parte di una sessione di composizione, cioè dopo un evento compositionstart e prima dell'evento compositionend corrispondente. Il valore non inizializzato di questo attributo DEVE essere false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) L'attributo isTrusted deve restituire il valore a cui è stato inizializzato. Quando un evento viene creato, l'attributo deve essere inizializzato a false. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) La chiave contiene il valore del tasto premuto. Se il valore ha una rappresentazione stampata, DEVE essere una Stringa di caratteri Unicode non vuota, conforme all'algoritmo per determinare il valore del tasto definito in questa specifica. Se il valore è un tasto di controllo privo di rappresentazione stampata, DEVE essere uno dei valori di tasto definiti nel set di valori di tasto, come determinato dall'algoritmo per determinare il valore del tasto. Le implementazioni che non sono in grado di identificare un tasto DEVONO usare il valore di tasto Unidentified. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) L'attributo location contiene un'indicazione della posizione logica del tasto sul dispositivo. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) true se il modificatore del tasto meta (Meta) era attivo. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) true se il tasto è stato premuto in modo prolungato. Tenere premuto un tasto DEVE far ripetere gli eventi keydown, beforeinput, input in quest'ordine, a una velocità determinata dalla configurazione del sistema. Per i dispositivi mobili che hanno un comportamento di pressione prolungata, il primo evento di tasto con valore dell'attributo repeat true DEVE fungere da indicazione di una pressione prolungata. Il tempo necessario affinché il tasto DEVA essere premuto per iniziare a ripetersi dipende dalla configurazione. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) true se il modificatore del tasto shift (Shift) era attivo. |
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

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | Il tasto attivato proviene dalla posizione sinistra del tasto (quando esistono più posizioni possibili per questo tasto). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | L'attivazione del tasto ha avuto origine sul tastierino numerico o con un tasto virtuale corrispondente al tastierino numerico (quando esiste più di una possibile posizione per questo tasto). Nota che il tasto NumLock dovrebbe sempre essere codificato con una posizione di DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | L'attivazione del tasto ha avuto origine dalla posizione destra del tasto (quando esiste più di una possibile posizione per questo tasto). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | L'attivazione del tasto NON DEVE essere distinta come la versione sinistra o destra del tasto e (ad eccezione del tasto NumLock) non ha avuto origine dal tastierino numerico (o non ha avuto origine con un tasto virtuale corrispondente al tastierino numerico). |

### Vedi anche

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
