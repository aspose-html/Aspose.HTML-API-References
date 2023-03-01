---
title: Class InputEvent
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Events.InputEvent classe. Gli eventi di input vengono inviati come notifiche ogni volta che il DOM viene aggiornato.
type: docs
weight: 820
url: /it/net/aspose.html.dom.events/inputevent/
---
## InputEvent class

Gli eventi di input vengono inviati come notifiche ogni volta che il DOM viene aggiornato.

```csharp
public class InputEvent : UIEvent
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [InputEvent](inputevent/#constructor)(string) | Inizializza una nuova istanza di`InputEvent` classe. |
| [InputEvent](inputevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Inizializza una nuova istanza di`InputEvent` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Utilizzato per indicare se un evento è un evento bubbling. Se l'evento può generare bolle, il valore è vero, altrimenti il valore è falso. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Usato per indicare se un evento può avere o meno la sua azione predefinita prevenuta. Se l'azione predefinita può essere impedita, il valore è true, altrimenti il valore è false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Usato per indicare il[`IEventTarget`](../ieventtarget/) di chi[`IEventListener`](../ieventlistener/) s sono attualmente in fase di elaborazione. Questo è particolarmente utile durante l'acquisizione e il bubbling. |
| [Data](../../aspose.html.dom.events/inputevent/data/) { get; } | I dati contengono il valore dei caratteri generati da un metodo di input. Questo POTREBBE essere un singolo carattere Unicode o una sequenza non vuota di caratteri Unicode [Unicode]. I caratteri DOVREBBERO essere normalizzati come definito dalla forma di normalizzazione Unicode NFC, definita in [UAX15]. Questo attributo PUÒ contenere la stringa vuota. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Restituisce true se preventDefault() è stato invocato mentre il valore dell'attributo cancelable è true, false in caso contrario. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Specifica alcune informazioni dettagliate sull'evento, a seconda del tipo di evento. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Utilizzato per indicare quale fase del flusso di eventi è attualmente in fase di valutazione. |
| [IsComposing](../../aspose.html.dom.events/inputevent/iscomposing/) { get; } | true se l'evento di input si verifica come parte di una sessione di composizione, ovvero dopo un evento di inizio composizione e prima del corrispondente evento di fine composizione. Il valore non inizializzato di questo attributo DEVE essere falso. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | L'attributo isTrusted deve restituire il valore a cui è stato inizializzato. Quando viene creato un evento, l'attributo deve essere inizializzato su false. |
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

### Guarda anche

* class [UIEvent](../uievent/)
* spazio dei nomi [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* assemblea [Aspose.HTML](../../)


