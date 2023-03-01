---
title: Class WheelEvent
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Events.WheelEvent classe. Linterfaccia WheelEvent fornisce informazioni contestuali specifiche associate agli eventi ruota. Per creare unistanza dellinterfaccia WheelEvent utilizza il costruttore WheelEvent passando un dizionario WheelEventInit facoltativo.
type: docs
weight: 860
url: /it/net/aspose.html.dom.events/wheelevent/
---
## WheelEvent class

L'interfaccia WheelEvent fornisce informazioni contestuali specifiche associate agli eventi ruota. Per creare un'istanza dell'interfaccia WheelEvent, utilizza il costruttore WheelEvent, passando un dizionario WheelEventInit facoltativo.

```csharp
public class WheelEvent : MouseEvent
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(string) | Inizializza una nuova istanza di`WheelEvent` classe. |
| [WheelEvent](wheelevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Inizializza una nuova istanza di`WheelEvent` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/mouseevent/altkey/) { get; } | Fare riferimento all'attributo altKey. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Utilizzato per indicare se un evento è un evento bubbling. Se l'evento può generare bolle, il valore è vero, altrimenti il valore è falso. |
| [Button](../../aspose.html.dom.events/mouseevent/button/) { get; } | Durante gli eventi del mouse causati dalla pressione o dal rilascio di un pulsante del mouse, il pulsante DEVE essere utilizzato per indicare quale pulsante del dispositivo puntatore ha cambiato stato. |
| [Buttons](../../aspose.html.dom.events/mouseevent/buttons/) { get; } | Durante qualsiasi evento del mouse, i pulsanti DEVONO essere utilizzati per indicare quale combinazione di pulsanti del mouse è attualmente premuta, espressa come maschera di bit. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Usato per indicare se un evento può avere o meno la sua azione predefinita prevenuta. Se l'azione predefinita può essere impedita, il valore è true, altrimenti il valore è false. |
| [ClientX](../../aspose.html.dom.events/mouseevent/clientx/) { get; } | La coordinata orizzontale in cui si è verificato l'evento rispetto al viewport associato all'evento. |
| [ClientY](../../aspose.html.dom.events/mouseevent/clienty/) { get; } | La coordinata verticale in cui si è verificato l'evento rispetto al viewport associato all'evento. |
| [CtrlKey](../../aspose.html.dom.events/mouseevent/ctrlkey/) { get; } | Fare riferimento all'attributo ctrlKey. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Usato per indicare il[`IEventTarget`](../ieventtarget/) di chi[`IEventListener`](../ieventlistener/) s sono attualmente in fase di elaborazione. Questo è particolarmente utile durante l'acquisizione e il bubbling. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Restituisce true se preventDefault() è stato invocato mentre il valore dell'attributo cancelable è true, false in caso contrario. |
| [DeltaMode](../../aspose.html.dom.events/wheelevent/deltamode/) { get; } | L'attributo deltaMode contiene un'indicazione delle unità di misura per i valori delta. Il valore predefinito è DOM_DELTA_PIXEL (pixel). |
| [DeltaX](../../aspose.html.dom.events/wheelevent/deltax/) { get; } | Nei programmi utente in cui l'azione predefinita dell'evento ruota è lo scorrimento, il valore DEVE essere la misura lungo l'asse x (in pixel, linee o pagine) da scorrere nel caso in cui l'evento non venga annullato. In caso contrario, si tratta di una misurazione specifica dell'implementazione (in pixel, linee o pagine) del movimento di un dispositivo ruota attorno all'asse x. |
| [DeltaY](../../aspose.html.dom.events/wheelevent/deltay/) { get; } | Nei programmi utente in cui l'azione predefinita dell'evento ruota è lo scorrimento, il valore DEVE essere la misura lungo l'asse y (in pixel, linee o pagine) da scorrere nel caso in cui l'evento non venga annullato. In caso contrario, si tratta di una misurazione specifica dell'implementazione (in pixel, linee o pagine) del movimento di un dispositivo ruota attorno all'asse y. |
| [DeltaZ](../../aspose.html.dom.events/wheelevent/deltaz/) { get; } | Nei programmi utente in cui l'azione predefinita dell'evento ruota è lo scorrimento, il valore DEVE essere la misura lungo l'asse z (in pixel, linee o pagine) da scorrere nel caso in cui l'evento non venga annullato. In caso contrario, si tratta di una misurazione specifica dell'implementazione (in pixel, linee o pagine) del movimento di un dispositivo ruota attorno all'asse z. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Specifica alcune informazioni dettagliate sull'evento, a seconda del tipo di evento. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Utilizzato per indicare quale fase del flusso di eventi è attualmente in fase di valutazione. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | L'attributo isTrusted deve restituire il valore a cui è stato inizializzato. Quando viene creato un evento, l'attributo deve essere inizializzato su false. |
| [MetaKey](../../aspose.html.dom.events/mouseevent/metakey/) { get; } | Fare riferimento all'attributo metaKey. |
| [RelatedTarget](../../aspose.html.dom.events/mouseevent/relatedtarget/) { get; } | Utilizzato per identificare un EventTarget secondario correlato a un evento UI, a seconda del tipo di evento. |
| [ScreenX](../../aspose.html.dom.events/mouseevent/screenx/) { get; } | La coordinata orizzontale in cui si è verificato l'evento rispetto all'origine del sistema di coordinate dello schermo. |
| [ScreenY](../../aspose.html.dom.events/mouseevent/screeny/) { get; } | La coordinata verticale in cui si è verificato l'evento rispetto all'origine del sistema di coordinate dello schermo. |
| [ShiftKey](../../aspose.html.dom.events/mouseevent/shiftkey/) { get; } | Fare riferimento all'attributo shiftKey. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Usato per indicare il[`IEventTarget`](../ieventtarget/) a cui l'evento è stato originariamente inviato. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Utilizzato per specificare l'ora (in millisecondi rispetto all'epoca) in cui è stato creato l'evento. A causa del fatto che alcuni sistemi potrebbero non fornire queste informazioni, il valore di timeStamp potrebbe non essere disponibile per tutti gli eventi. Quando non disponibile , verrà restituito un valore pari a 0. Esempi di epoch time sono l'ora di avvio del sistema o 0:0:0 UTC 1 gennaio 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Il nome dell'evento (senza distinzione tra maiuscole e minuscole). Il nome deve essere un nome XML. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | L'attributo view identifica la finestra da cui è stato generato l'evento. Il valore non inizializzato di questo attributo DEVE essere nullo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | Il[`InitEvent`](../event/initevent/) Il metodo viene utilizzato per inizializzare il valore di an[`Event`](../event/) creato tramite the [`IDocumentEvent`](../idocumentevent/) interfaccia. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Se un evento è cancellabile, il[`PreventDefault`](../event/preventdefault/) Il metodo viene utilizzato per indicare che l'evento deve essere annullato, il che significa che qualsiasi azione predefinita normalmente intrapresa dall'implementazione come risultato dell'evento non si verificherà. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | L'invocazione di questo metodo impedisce all'evento di raggiungere qualsiasi ascoltatore di eventi registrato dopo quello corrente e quando inviato in un albero impedisce anche all'evento di raggiungere qualsiasi altro oggetto. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | Il[`StopPropagation`](../event/stoppropagation/) viene utilizzato il metodo per impedire l'ulteriore propagazione di un evento durante il flusso di eventi. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DOM_DELTA_LINE](../../aspose.html.dom.events/wheelevent/dom_delta_line/) | Le unità di misura per il delta DEVONO essere singole righe di testo. Questo è il caso di molti controlli del modulo. |
| const [DOM_DELTA_PAGE](../../aspose.html.dom.events/wheelevent/dom_delta_page/) | Le unità di misura per il delta DEVONO essere pagine, definite come singola schermata o come pagina delimitata. |
| const [DOM_DELTA_PIXEL](../../aspose.html.dom.events/wheelevent/dom_delta_pixel/) | Le unità di misura per il delta DEVONO essere pixel. Questo è il caso più tipico nella maggior parte dei sistemi operativi e delle configurazioni di implementazione. |

### Guarda anche

* class [MouseEvent](../mouseevent/)
* spazio dei nomi [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* assemblea [Aspose.HTML](../../)


