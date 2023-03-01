---
title: Class KeyboardEvent
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Events.KeyboardEvent classe. Linterfaccia KeyboardEvent fornisce informazioni contestuali specifiche associate ai dispositivi tastiera. Ogni evento della tastiera fa riferimento a un tasto utilizzando un valore. Gli eventi della tastiera sono comunemente diretti allelemento che ha il focus.
type: docs
weight: 830
url: /it/net/aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

L'interfaccia KeyboardEvent fornisce informazioni contestuali specifiche associate ai dispositivi tastiera. Ogni evento della tastiera fa riferimento a un tasto utilizzando un valore. Gli eventi della tastiera sono comunemente diretti all'elemento che ha il focus.

```csharp
public class KeyboardEvent : UIEvent
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(string) | Inizializza una nuova istanza di`KeyboardEvent` classe. |
| [KeyboardEvent](keyboardevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Inizializza una nuova istanza di`KeyboardEvent` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/keyboardevent/altkey/) { get; } | true se il tasto di modifica Alt (alternativa) (o "Opzione") era attivo. Il valore non inizializzato di questo attributo DEVE essere falso. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Utilizzato per indicare se un evento è un evento bubbling. Se l'evento può generare bolle, il valore è vero, altrimenti il valore è falso. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Usato per indicare se un evento può avere o meno la sua azione predefinita prevenuta. Se l'azione predefinita può essere impedita, il valore è true, altrimenti il valore è false. |
| [Code](../../aspose.html.dom.events/keyboardevent/code/) { get; } | Il codice contiene una stringa che identifica il tasto fisico premuto. Il valore non è influenzato dal layout di tastiera corrente o dallo stato del modificatore, quindi un particolare tasto restituirà sempre lo stesso valore. |
| [CtrlKey](../../aspose.html.dom.events/keyboardevent/ctrlkey/) { get; } | vero se il modificatore del tasto Control (controllo) era attivo. Il valore non inizializzato di questo attributo DEVE essere falso. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Usato per indicare il[`IEventTarget`](../ieventtarget/) di chi[`IEventListener`](../ieventlistener/) s sono attualmente in fase di elaborazione. Questo è particolarmente utile durante l'acquisizione e il bubbling. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Restituisce true se preventDefault() è stato invocato mentre il valore dell'attributo cancelable è true, false in caso contrario. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Specifica alcune informazioni dettagliate sull'evento, a seconda del tipo di evento. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Utilizzato per indicare quale fase del flusso di eventi è attualmente in fase di valutazione. |
| [IsComposing](../../aspose.html.dom.events/keyboardevent/iscomposing/) { get; } | true se l'evento chiave si verifica come parte di una sessione di composizione, ovvero dopo un evento di inizio composizione e prima del corrispondente evento di fine composizione. Il valore non inizializzato di questo attributo DEVE essere falso. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | L'attributo isTrusted deve restituire il valore a cui è stato inizializzato. Quando viene creato un evento, l'attributo deve essere inizializzato su false. |
| [Key](../../aspose.html.dom.events/keyboardevent/key/) { get; } | Il tasto contiene il valore del tasto premuto. Se il valore ha una rappresentazione stampata, DEVE essere una stringa di caratteri Unicode non vuota, conforme all'algoritmo per determinare il valore della chiave definito in questa specifica. Se il valore è una chiave di controllo che non ha una rappresentazione stampata, DEVE essere uno dei valori chiave definiti nel set di valori chiave, come determinato dall'algoritmo per determinare il valore della chiave. Le implementazioni che non sono in grado di identificare una chiave DEVONO utilizzare il valore della chiave Unidentified. |
| [Location](../../aspose.html.dom.events/keyboardevent/location/) { get; } | L'attributo location contiene un'indicazione della posizione logica della chiave sul dispositivo. |
| [MetaKey](../../aspose.html.dom.events/keyboardevent/metakey/) { get; } | vero se il modificatore di chiave meta (Meta) era attivo. |
| [Repeat](../../aspose.html.dom.events/keyboardevent/repeat/) { get; } | true se il tasto è stato premuto in modo prolungato. Tenere premuto un tasto DEVE comportare la ripetizione degli eventi keydown, beforeinput, input in questo ordine, a una velocità determinata dalla configurazione del sistema. Per i dispositivi mobili che hanno un comportamento di pressione prolungata del tasto, il primo evento chiave con un valore di attributo di ripetizione di true DEVE servire come indicazione di una pressione prolungata del tasto. Il periodo di tempo in cui il tasto DEVE essere premuto per iniziare a ripetere dipende dalla configurazione. |
| [ShiftKey](../../aspose.html.dom.events/keyboardevent/shiftkey/) { get; } | true se il modificatore del tasto Maiusc (Maiusc) era attivo. |
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
| const [DOM_KEY_LOCATION_LEFT](../../aspose.html.dom.events/keyboardevent/dom_key_location_left/) | La chiave attivata ha avuto origine dalla posizione della chiave sinistra (quando esiste più di una posizione possibile per questa chiave). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | L'attivazione del tasto ha avuto origine sul tastierino numerico o con un tasto virtuale corrispondente al tastierino numerico (quando esiste più di una posizione possibile per questo tasto). Tieni presente che il tasto NumLock deve essere sempre codificato con una posizione di DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.html.dom.events/keyboardevent/dom_key_location_right/) | L'attivazione della chiave ha avuto origine dalla posizione corretta della chiave (quando esiste più di una posizione possibile per questa chiave). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | L'attivazione della chiave NON DEVE essere distinta come versione sinistra o destra della chiave e (a parte il tasto NumLock) non ha avuto origine dal tastierino numerico (o non ha avuto origine con un tasto virtuale corrispondente al tastierino numerico). |

### Guarda anche

* class [UIEvent](../uievent/)
* spazio dei nomi [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* assemblea [Aspose.HTML](../../)


