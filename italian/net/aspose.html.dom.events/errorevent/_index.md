---
title: Class ErrorEvent
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Events.ErrorEvent classe. IlErrorEvent fornisce informazioni contestuali su un errore che si è verificato durante il runtime.
type: docs
weight: 760
url: /it/net/aspose.html.dom.events/errorevent/
---
## ErrorEvent class

Il`ErrorEvent` fornisce informazioni contestuali su un errore che si è verificato durante il runtime.

```csharp
public class ErrorEvent : Event
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(Exception) | Inizializza una nuova istanza di`ErrorEvent` classe. |
| [ErrorEvent](errorevent/#constructor)(IDictionary&lt;string, object&gt;) | Inizializza una nuova istanza di`ErrorEvent` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Utilizzato per indicare se un evento è un evento bubbling. Se l'evento può generare bolle, il valore è vero, altrimenti il valore è falso. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Usato per indicare se un evento può avere o meno la sua azione predefinita prevenuta. Se l'azione predefinita può essere impedita, il valore è true, altrimenti il valore è false. |
| [ColNo](../../aspose.html.dom.events/errorevent/colno/) { get; } | L'attributo colno deve restituire il valore a cui è stato inizializzato. Quando l'oggetto viene creato, questo attributo deve essere inizializzato a zero. Rappresenta il numero di colonna in cui si è verificato l'errore nello script. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Usato per indicare il[`IEventTarget`](../ieventtarget/) di chi[`IEventListener`](../ieventlistener/) s sono attualmente in fase di elaborazione. Questo è particolarmente utile durante l'acquisizione e il bubbling. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Restituisce true se preventDefault() è stato invocato mentre il valore dell'attributo cancelable è true, false in caso contrario. |
| [Error](../../aspose.html.dom.events/errorevent/error/) { get; } | L'attributo error deve restituire il valore a cui è stato inizializzato. Quando l'oggetto viene creato, questo attributo deve essere inizializzato su null. Ove appropriato, viene impostato sull'oggetto che rappresenta l'errore (ad es. l'oggetto eccezione nel caso di un'eccezione DOM non rilevata). |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Utilizzato per indicare quale fase del flusso di eventi è attualmente in fase di valutazione. |
| [FileName](../../aspose.html.dom.events/errorevent/filename/) { get; } | L'attributo filename deve restituire il valore con cui è stato inizializzato. Quando l'oggetto viene creato, questo attributo deve essere inizializzato sulla stringa vuota. Rappresenta l'URL assoluto dello script in cui si è verificato originariamente l'errore. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | L'attributo isTrusted deve restituire il valore a cui è stato inizializzato. Quando viene creato un evento, l'attributo deve essere inizializzato su false. |
| [LineNo](../../aspose.html.dom.events/errorevent/lineno/) { get; } | L'attributo lineno deve restituire il valore a cui è stato inizializzato. Quando l'oggetto viene creato, questo attributo deve essere inizializzato a zero. Rappresenta il numero di riga in cui si è verificato l'errore nello script. |
| [Message](../../aspose.html.dom.events/errorevent/message/) { get; } | L'attributo del messaggio deve restituire il valore a cui è stato inizializzato. Quando l'oggetto viene creato, questo attributo deve essere inizializzato sulla stringa vuota. Rappresenta il messaggio di errore. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Usato per indicare il[`IEventTarget`](../ieventtarget/) a cui l'evento è stato originariamente inviato. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Utilizzato per specificare l'ora (in millisecondi rispetto all'epoca) in cui è stato creato l'evento. A causa del fatto che alcuni sistemi potrebbero non fornire queste informazioni, il valore di timeStamp potrebbe non essere disponibile per tutti gli eventi. Quando non disponibile , verrà restituito un valore pari a 0. Esempi di epoch time sono l'ora di avvio del sistema o 0:0:0 UTC 1 gennaio 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Il nome dell'evento (senza distinzione tra maiuscole e minuscole). Il nome deve essere un nome XML. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | Il[`InitEvent`](../event/initevent/) Il metodo viene utilizzato per inizializzare il valore di an[`Event`](../event/) creato tramite the [`IDocumentEvent`](../idocumentevent/) interfaccia. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Se un evento è cancellabile, il[`PreventDefault`](../event/preventdefault/) Il metodo viene utilizzato per indicare che l'evento deve essere annullato, il che significa che qualsiasi azione predefinita normalmente intrapresa dall'implementazione come risultato dell'evento non si verificherà. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | L'invocazione di questo metodo impedisce all'evento di raggiungere qualsiasi ascoltatore di eventi registrato dopo quello corrente e quando inviato in un albero impedisce anche all'evento di raggiungere qualsiasi altro oggetto. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | Il[`StopPropagation`](../event/stoppropagation/) viene utilizzato il metodo per impedire l'ulteriore propagazione di un evento durante il flusso di eventi. |

### Guarda anche

* class [Event](../event/)
* spazio dei nomi [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* assemblea [Aspose.HTML](../../)


