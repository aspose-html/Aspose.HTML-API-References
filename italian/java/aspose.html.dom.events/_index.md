---
title: "com.aspose.html.dom.events"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Il pacchetto com.aspose.html.dom.events fornisce oggetti per qualsiasi evento relativo all'aggiornamento del DOM. Include l'iscrizione all'osservazione di informazioni contestuali specifiche associate all'evento, nonché la costruzione di eventi personalizzati."
type: docs

url: /it/java/com.aspose.html.dom.events/
---
Il pacchetto **com.aspose.html.dom.events** fornisce oggetti per tutti gli eventi relativi all'aggiornamento del DOM. Include l'iscrizione all'osservazione di informazioni contestuali specifiche associate all'evento, nonché la costruzione di eventi personalizzati.

## Classi

| Classe | Descrizione |
| --- | --- |
| [CustomEvent](./customevent/) | Gli eventi che utilizzano l'interfaccia CustomEvent possono essere usati per trasportare dati personalizzati. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | L'evento DocumentLoadErrorEvent si verifica quando la risorsa richiesta non è disponibile. |
| [DOMEventHandler](./domeventhandler/) | Rappresenta un delegato di callback generico per la gestione degli eventi del Document Object Model (DOM). |
| [ErrorEvent](./errorevent/) | L'ErrorEvent fornisce informazioni contestuali su errori verificatisi durante l'esecuzione. |
| [Event](./event/) | Il sistema è usato per fornire informazioni contestuali su un evento al gestore che elabora l'evento. |
| [FocusEvent](./focusevent/) | L'interfaccia FocusEvent fornisce informazioni contestuali specifiche associate agli eventi di Focus. |
| [InputEvent](./inputevent/) | Gli eventi di input vengono inviati come notifiche ogni volta che il DOM viene aggiornato. |
| [KeyboardEvent](./keyboardevent/) | L'interfaccia KeyboardEvent fornisce informazioni contestuali specifiche associate ai dispositivi di tastiera. Ogni evento di tastiera fa riferimento a un tasto tramite un valore. Gli eventi di tastiera sono comunemente indirizzati all'elemento che ha il focus. |
| [MouseEvent](./mouseevent/) | L'interfaccia MouseEvent fornisce informazioni contestuali specifiche associate agli eventi del mouse. |
| [UIEvent](./uievent/) | L'interfaccia UIEvent fornisce informazioni contestuali specifiche associate agli eventi dell'interfaccia utente. |
| [WheelEvent](./wheelevent/) | L'interfaccia WheelEvent fornisce informazioni contestuali specifiche associate agli eventi della rotella. Per creare un'istanza dell'interfaccia WheelEvent, utilizzare il costruttore WheelEvent, passando un dizionario opzionale WheelEventInit. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | L'interfaccia DocumentEvent fornisce un meccanismo mediante il quale l'utente può creare un Event di un tipo supportato dall'implementazione. Si prevede che l'interfaccia DocumentEvent sarà implementata sullo stesso oggetto che implementa l'interfaccia Document in un'implementazione che supporta il modello Event. |
| [IEventListener](./ieventlistener/) | L'interfaccia è il metodo principale per gestire gli eventi. Gli utenti implementano l'interfaccia e registrano il loro listener su un oggetto usando il metodo. Gli utenti dovrebbero anche rimuovere il loro listener dopo aver terminato l'uso. |
| [IEventTarget](./ieventtarget/) | L'interfaccia EventTarget è implementata da tutti i Node in un'implementazione che supporta il modello di eventi DOM. Pertanto, questa interfaccia può essere ottenuta utilizzando metodi di casting specifici per il binding su un'istanza dell'interfaccia Node. L'interfaccia consente la registrazione e la rimozione di Event Listener su un oggetto e la distribuzione degli eventi a esso. |
