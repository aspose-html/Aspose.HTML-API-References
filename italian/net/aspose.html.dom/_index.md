---
title: Aspose.Html.Dom
second_title: Aspose.HTML per riferimento API .NET
description: Il Aspose.Html.Dom Document Object Model namespace fornisce API che rappresenta e interagisce con qualsiasi documento HTML XML o SVG. Il DOM è un modello di documento caricato nel browser e rappresenta il documento come un albero di nodi dove ogni nodo rappresenta una parte del documento ad es. un elemento testo stringa o commento.
type: docs
weight: 40
url: /it/net/aspose.html.dom/
---
Il **Aspose.Html.Dom (Document Object Model)** namespace fornisce API che rappresenta e interagisce con qualsiasi documento HTML, XML o SVG. Il DOM è un modello di documento caricato nel browser e rappresenta il documento come un albero di nodi, dove ogni nodo rappresenta una parte del documento (ad es. un elemento, testo stringa o commento).

## Classi

| Classe | Descrizione |
| --- | --- |
| [Attr](./attr/) | L'interfaccia Attr rappresenta un attributo in un oggetto Element. In genere i valori consentiti per l'attributo sono definiti in uno schema associato al documento. |
| [CDATASection](./cdatasection/) | Le sezioni CDATA vengono utilizzate per eseguire l'escape di blocchi di testo contenenti caratteri che altrimenti verrebbero considerati markup. |
| [CharacterData](./characterdata/) | CharacterData estende Node con un set di attributi e metodi per accedere ai dati dei personaggi nel DOM. |
| [Comment](./comment/) | Eredita da CharacterData e rappresenta il contenuto di un commento, ovvero tutti i caratteri compresi tra l'iniziale ' . |
| [Document](./document/) | Il documento rappresenta l'intero documento HTML, XML o SVG. Concettualmente, è la radice dell'albero del documento e fornisce l'accesso principale ai dati del documento. |
| [DocumentFragment](./documentfragment/) | DocumentFragment è un oggetto Document "leggero" o "minimo". È molto comune voler poter estrarre una porzione dell'albero di un documento o creare un nuovo frammento di un documento. |
| [DocumentType](./documenttype/) | DocumentType fornisce un'interfaccia all'elenco di entità definite per il documento |
| [DOMException](./domexception/) | L'interfaccia DOMException rappresenta un evento anomalo (chiamato eccezione) che si verifica in seguito alla chiamata di un metodo o all'accesso a una proprietà di un'API web. Questo è fondamentalmente il modo in cui le condizioni di errore sono descritte nelle API web. |
| [DOMObject](./domobject/) | Il tipo DOMObject viene utilizzato per rappresentare un oggetto di base per l'intero Document Object Model. Per Java ed ECMAScript, DOMObject è associato al tipo Object. |
| [Element](./element/) | L'interfaccia Element rappresenta un elemento in un documento HTML o XML. |
| [Entity](./entity/) | Rappresenta un'entità nota, analizzata o non analizzata, in un documento XML. |
| [EntityReference](./entityreference/) | I nodi EntityReference possono essere utilizzati per rappresentare un riferimento a un'entità nell'albero. |
| [EventTarget](./eventtarget/) | Il[`EventTarget`](../aspose.html.dom/eventtarget/) l'interfaccia è implementata da tutti i nodi in un'implementazione che supporta il modello di eventi DOM. Pertanto, questa interfaccia può essere ottenuta utilizzando metodi di cast specifici dell'associazione su un'istanza dell'interfaccia del nodo. L'interfaccia consente la registrazione e la rimozione di Event Listener su UN[`EventTarget`](../aspose.html.dom/eventtarget/) e l'invio di eventi a quello[`IEventTarget`](../aspose.html.dom.events/ieventtarget/) . |
| [Node](./node/) | L'interfaccia Node è il tipo di dati primario per l'intero Document object Model. Rappresenta un singolo nodo nell'albero del documento. |
| [Notation](./notation/) | Rappresenta una notazione dichiarata nel DTD. |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction rappresenta una "istruzione di elaborazione", utilizzata in XML come un modo per mantenere le informazioni specifiche del processore nel testo del documento. |
| [ShadowRoot](./shadowroot/) | ShadowRoot è un nodo radice dell'albero delle ombre. |
| [Text](./text/) | L'interfaccia Text eredita da CharacterData e rappresenta il contenuto testuale (chiamato dati carattere in XML) di un elemento o Attr. |
| [TypeInfo](./typeinfo/) | TypeInfo rappresenta un tipo referenziato dai nodi Element o Attr, specificato negli schemi associati al documento. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Un contesto di navigazione è un ambiente in cui[`Document`](../aspose.html.dom/document/) gli oggetti vengono presentati all'utente. |
| [IChildNode](./ichildnode/) | Definisce[`IChildNode`](../aspose.html.dom/ichildnode/) interfaccia che dovrebbe essere implementata da[`Node`](../aspose.html.dom/node/) che può avere un genitore. |
| [IDocumentInit](./idocumentinit/) | Questa interfaccia fornisce[`Document`](../aspose.html.dom/document/) informazioni di inizializzazione. |
| [IDOMImplementation](./idomimplementation/) | L'interfaccia DOMImplementation fornisce una serie di metodi per eseguire operazioni che sono indipendenti da qualsiasi istanza particolare del modello a oggetti del documento. |
| [IElementInit](./ielementinit/) | Questa interfaccia fornisce[`Element`](../aspose.html.dom/element/) informazioni di inizializzazione. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Rappresenta l'interfaccia che deve essere ereditata da tutti gli elementi supportati dalla gestione degli eventi di sistema |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | Definisce[`IChildNode`](../aspose.html.dom/ichildnode/) che non sono[`DOCUMENT_TYPE_NODE`](../aspose.html.dom/node/document_type_node/) . |
| [INonElementParentNode](./inonelementparentnode/) | Definisce[`IParentNode`](../aspose.html.dom/iparentnode/) che non sono di tipo Elemento. |
| [IParentNode](./iparentnode/) | Definisce il[`IParentNode`](../aspose.html.dom/iparentnode/) interfaccia implementata da tutti i possibili genitori. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Modalità in cui può operare ShadowRoot. |


