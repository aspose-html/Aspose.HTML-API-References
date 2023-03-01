---
title: Aspose.Html.Dom.Events
second_title: Aspose.HTML per riferimento API .NET
description: Il Aspose.Html.Dom.Events namespace fornisce oggetti per qualsiasi evento relativo allaggiornamento del DOM. Include labbonamento a osservazioni specifiche di informazioni contestuali associate allevento e la costruzione di eventi personalizzati.
type: docs
weight: 80
url: /it/net/aspose.html.dom.events/
---
Il **Aspose.Html.Dom.Events** namespace fornisce oggetti per qualsiasi evento relativo all'aggiornamento del DOM. Include l'abbonamento a osservazioni specifiche di informazioni contestuali associate all'evento e la costruzione di eventi personalizzati.

## Classi

| Classe | Descrizione |
| --- | --- |
| [CustomEvent](./customevent/) | Gli eventi che utilizzano l'interfaccia CustomEvent possono essere utilizzati per trasportare dati personalizzati. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | Il[`DocumentLoadErrorEvent`](../aspose.html.dom.events/documentloaderrorevent/) si verifica quando la risorsa richiesta non è disponibile. |
| [DOMEventHandler](./domeventhandler/) | Rappresenta la richiamata per la gestione degli eventi. |
| [ErrorEvent](./errorevent/) | Il[`ErrorEvent`](../aspose.html.dom.events/errorevent/) fornisce informazioni contestuali su un errore che si è verificato durante il runtime. |
| [Event](./event/) | Il[`Event`](../aspose.html.dom.events/event/) viene utilizzato per fornire informazioni contestuali su un evento al gestore che elabora l'evento. |
| [FocusEvent](./focusevent/) | L'interfaccia FocusEvent fornisce informazioni contestuali specifiche associate agli eventi Focus. |
| [InputEvent](./inputevent/) | Gli eventi di input vengono inviati come notifiche ogni volta che il DOM viene aggiornato. |
| [KeyboardEvent](./keyboardevent/) | L'interfaccia KeyboardEvent fornisce informazioni contestuali specifiche associate ai dispositivi tastiera. Ogni evento della tastiera fa riferimento a un tasto utilizzando un valore. Gli eventi della tastiera sono comunemente diretti all'elemento che ha il focus. |
| [MouseEvent](./mouseevent/) | L'interfaccia MouseEvent fornisce informazioni contestuali specifiche associate agli eventi del mouse. |
| [UIEvent](./uievent/) | L'interfaccia UIEvent fornisce informazioni contestuali specifiche associate agli eventi dell'interfaccia utente. |
| [WheelEvent](./wheelevent/) | L'interfaccia WheelEvent fornisce informazioni contestuali specifiche associate agli eventi ruota. Per creare un'istanza dell'interfaccia WheelEvent, utilizza il costruttore WheelEvent, passando un dizionario WheelEventInit facoltativo. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | Il[`IDocumentEvent`](../aspose.html.dom.events/idocumentevent/) L'interfaccia fornisce un meccanismo mediante il quale l'utente può creare un file[`Event`](../aspose.html.dom.events/event/) di un tipo supportato dall'implementazione. |
| [IEventListener](./ieventlistener/) | Il[`IEventListener`](../aspose.html.dom.events/ieventlistener/)l'interfaccia è il metodo principale per la gestione degli eventi. Gli utenti implementano il[`IEventListener`](../aspose.html.dom.events/ieventlistener/) interfaccia e registrare il loro ascoltatore su un[`EventTarget`](../aspose.html.dom/eventtarget/) usando il[`AddEventListener`](../aspose.html.dom/eventtarget/addeventlistener/) method. Gli utenti dovrebbero anche rimuovere il loro[`IEventListener`](../aspose.html.dom.events/ieventlistener/) dal suo[`EventTarget`](../aspose.html.dom/eventtarget/) dopo aver completato l'utilizzo dell'ascoltatore. |
| [IEventTarget](./ieventtarget/) | Il[`EventTarget`](../aspose.html.dom/eventtarget/) l'interfaccia è implementata da tutti i nodi in un'implementazione che supporta il modello di eventi DOM. Pertanto, questa interfaccia può essere ottenuta utilizzando metodi di cast specifici dell'associazione su un'istanza dell'interfaccia del nodo. L'interfaccia consente la registrazione e la rimozione di Event Listener su UN[`EventTarget`](../aspose.html.dom/eventtarget/) e l'invio di eventi a quello[`IEventTarget`](../aspose.html.dom.events/ieventtarget/) . |


