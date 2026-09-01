---
title: "Classe SVGZoomEvent"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Classe com.aspose.html.dom.svg.events.SVGZoomEvent. L'evento di zoom si verifica quando l'utente avvia un'azione che provoca il ridimensionamento della vista corrente del frammento del documento SVG. I gestori di eventi sono riconosciuti solo sugli elementi svg."
type: docs

url: /it/java/com.aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

L'evento di zoom si verifica quando l'utente avvia un'azione che provoca il ridimensionamento della vista corrente del frammento del documento SVG. I gestori di eventi sono riconosciuti solo sugli elementi ‘svg’.

```java
public class SVGZoomEvent : Event
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Utilizzato per indicare se un evento è un evento di bubbling o meno. Se l'evento può propagarsi, il valore è true, altrimenti è false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Utilizzato per indicare se un evento può avere la sua azione predefinita annullata o meno. Se l'azione predefinita può essere annullata, il valore è true, altrimenti è false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Utilizzato per indicare il [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) il cui [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/) è attualmente in fase di elaborazione. Questo è particolarmente utile durante la cattura e il bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Restituisce true se preventDefault() è stato invocato mentre il valore dell'attributo cancelable è true, altrimenti false. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Utilizzato per indicare quale fase del flusso di eventi è attualmente in valutazione. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) L'attributo isTrusted deve restituire il valore a cui è stato inizializzato. Quando viene creato un evento, l'attributo deve essere inizializzato a false. |
| [getNewScale](../../com.aspose.html.dom.svg.events/svgzoomevent/newscale/) Il fattore di scala che sarà in vigore dopo che l'operazione di zoom è stata elaborata. |
| [getNewTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/newtranslate/) I valori di traslazione che saranno in vigore dopo che l'operazione di zoom è stata elaborata. L'oggetto SVGPoint è di sola lettura. |
| [getPreviousScale](../../com.aspose.html.dom.svg.events/svgzoomevent/previousscale/) Il fattore di scala delle operazioni di zoom precedenti che era in vigore prima che l'operazione di zoom si verificasse. |
| [getPreviousTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) I valori di traslazione delle operazioni di zoom precedenti che erano in vigore prima che l'operazione di zoom si verificasse. L'oggetto SVGPoint è di sola lettura. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Utilizzato per indicare il [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) a cui l'evento è stato originariamente inviato. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Utilizzato per specificare il tempo (in millisecondi relativi all'epoch) al quale l'evento è stato creato. Poiché alcuni sistemi potrebbero non fornire queste informazioni, il valore di timeStamp potrebbe non essere disponibile per tutti gli eventi. Quando non è disponibile, verrà restituito il valore 0. Esempi di tempo epoch sono il tempo di avvio del sistema o 0:0:0 UTC 1° gennaio 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Il nome dell'evento (non sensibile a maiuscole/minuscole). Il nome deve essere un nome XML. |
| [getZoomRectScreen](../../com.aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) Il rettangolo di zoom specificato in unità di schermo. L'oggetto SVGRect è di sola lettura. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Il metodo [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) è usato per inizializzare il valore di un [`Event`](../../com.aspose.html.dom.events/event/) creato tramite l'interfaccia [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Se un evento è annullabile, il metodo [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) è usato per indicare che l'evento deve essere annullato, il che significa che nessuna azione predefinita normalmente eseguita dall'implementazione come risultato dell'evento avverrà. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invocare questo metodo impedisce che l'evento raggiunga i listener registrati dopo quello corrente e, quando viene inviato in un albero, impedisce anche che l'evento raggiunga altri oggetti. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Il metodo [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) è usato per impedire ulteriori propagazioni di un evento durante il flusso degli eventi. |

### Vedi anche

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
