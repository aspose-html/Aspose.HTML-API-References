---
title: "Classe WheelEvent"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.dom.events.WheelEvent. L'interfaccia WheelEvent fornisce informazioni contestuali specifiche associate agli eventi della rotella. Per creare un'istanza dell'interfaccia WheelEvent, utilizzare il costruttore WheelEvent passando un dizionario opzionale WheelEventInit."
type: docs

url: /it/java/com.aspose.html.dom.events/wheelevent/
---
## WheelEvent class

L'interfaccia WheelEvent fornisce informazioni contestuali specifiche associate agli eventi della rotella. Per creare un'istanza dell'interfaccia WheelEvent, utilizzare il costruttore WheelEvent, passando un dizionario opzionale WheelEventInit.

```java
public class WheelEvent : MouseEvent
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(String) | Inizializza una nuova istanza della classe `WheelEvent`. |
| [WheelEvent](wheelevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/mouseevent/altkey/) Fare riferimento all'attributo altKey. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Utilizzato per indicare se un evento è un evento di bubbling o meno. Se l'evento può propagarsi, il valore è true, altrimenti il valore è false. |
| [getButton](../../com.aspose.html.dom.events/mouseevent/button/) Durante gli eventi del mouse causati dalla pressione o rilascio di un pulsante del mouse, button DEVE essere usato per indicare quale pulsante del dispositivo di puntamento ha cambiato stato. |
| [getButtons](../../com.aspose.html.dom.events/mouseevent/buttons/) Durante qualsiasi evento del mouse, buttons DEVE essere usato per indicare quale combinazione di pulsanti del mouse è attualmente premuta, espressa come bitmask. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Utilizzato per indicare se un evento può avere la sua azione predefinita annullata. Se l'azione predefinita può essere annullata, il valore è true, altrimenti il valore è false. |
| [getClientX](../../com.aspose.html.dom.events/mouseevent/clientx/) La coordinata orizzontale in cui si è verificato l'evento rispetto al viewport associato all'evento. |
| [getClientY](../../com.aspose.html.dom.events/mouseevent/clienty/) La coordinata verticale in cui si è verificato l'evento rispetto al viewport associato all'evento. |
| [getCtrlKey](../../com.aspose.html.dom.events/mouseevent/ctrlkey/) Fare riferimento all'attributo ctrlKey. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Utilizzato per indicare il [`IEventTarget`](../ieventtarget/) i cui [`IEventListener`](../ieventlistener/) sono attualmente in fase di elaborazione. Questo è particolarmente utile durante il capturing e il bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Restituisce true se preventDefault() è stato invocato mentre il valore dell'attributo cancelable è true, altrimenti false. |
| [getDeltaMode](../../com.aspose.html.dom.events/wheelevent/deltamode/) L'attributo deltaMode contiene un'indicazione delle unità di misura per i valori delta. Il valore predefinito è DOM_DELTA_PIXEL (pixel). |
| [getDeltaX](../../com.aspose.html.dom.events/wheelevent/deltax/) Nei user agent in cui l'azione predefinita dell'evento wheel è lo scorrimento, il valore DEVE essere la misura lungo l'asse x (in pixel, linee o pagine) da scorrere nel caso in cui l'evento non sia annullato. Altrimenti, si tratta di una misura specifica dell'implementazione (in pixel, linee o pagine) del movimento del dispositivo wheel attorno all'asse x. |
| [getDeltaY](../../com.aspose.html.dom.events/wheelevent/deltay/) Nei user agent in cui l'azione predefinita dell'evento wheel è lo scorrimento, il valore DEVE essere la misura lungo l'asse y (in pixel, linee o pagine) da scorrere nel caso in cui l'evento non sia annullato. Altrimenti, si tratta di una misura specifica dell'implementazione (in pixel, linee o pagine) del movimento del dispositivo wheel attorno all'asse y. |
| [getDeltaZ](../../com.aspose.html.dom.events/wheelevent/deltaz/) Nei user agent in cui l'azione predefinita dell'evento wheel è lo scorrimento, il valore DEVE essere la misura lungo l'asse z (in pixel, linee o pagine) da scorrere nel caso in cui l'evento non sia annullato. Altrimenti, si tratta di una misura specifica dell'implementazione (in pixel, linee o pagine) del movimento del dispositivo wheel attorno all'asse z. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Specifica alcune informazioni di dettaglio sull'Event, a seconda del tipo di evento. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Utilizzato per indicare quale fase del flusso di eventi è attualmente in valutazione. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) L'attributo isTrusted deve restituire il valore a cui è stato inizializzato. Quando un evento viene creato, l'attributo deve essere inizializzato a false. |
| [getMetaKey](../../com.aspose.html.dom.events/mouseevent/metakey/) Fare riferimento all'attributo metaKey. |
| [getRelatedTarget](../../com.aspose.html.dom.events/mouseevent/relatedtarget/) Utilizzato per identificare un EventTarget secondario correlato a un evento UI, a seconda del tipo di evento. |
| [getScreenX](../../com.aspose.html.dom.events/mouseevent/screenx/) La coordinata orizzontale in cui si è verificato l'evento rispetto all'origine del sistema di coordinate dello schermo. |
| [getScreenY](../../com.aspose.html.dom.events/mouseevent/screeny/) La coordinata verticale in cui si è verificato l'evento rispetto all'origine del sistema di coordinate dello schermo. |
| [getShiftKey](../../com.aspose.html.dom.events/mouseevent/shiftkey/) Fare riferimento all'attributo shiftKey. |
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
| const [DOM_DELTA_LINE](../../com.aspose.html.dom.events/wheelevent/dom_delta_line/) | Le unità di misura per il delta DEVONO essere linee di testo individuali. Questo è il caso per molti controlli di modulo. |
| const [DOM_DELTA_PAGE](../../com.aspose.html.dom.events/wheelevent/dom_delta_page/) | Le unità di misura per il delta DEVONO essere pagine, definite come uno schermo unico o come una pagina delimitata. |
| const [DOM_DELTA_PIXEL](../../com.aspose.html.dom.events/wheelevent/dom_delta_pixel/) | Le unità di misura per il delta DEVONO essere pixel. Questo è il caso più tipico nella maggior parte dei sistemi operativi e delle configurazioni di implementazione. |

### Vedi anche

* class [MouseEvent](../mouseevent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
