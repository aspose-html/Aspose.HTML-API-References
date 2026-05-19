---
title: "com.aspose.html.dom"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Il pacchetto com.aspose.html.dom Document Object Model fornisce API che rappresentano e interagiscono con qualsiasi documento HTML, XML o SVG. Il DOM è un modello di documento caricato nel browser e rappresenta il documento come un albero di nodi dove ogni nodo rappresenta una parte del documento, ad esempio un elemento, una stringa di testo o un commento."
type: docs

url: /it/java/com.aspose.html.dom/
---
Il pacchetto **com.aspose.html.dom (Document Object Model)** fornisce un'API che rappresenta e interagisce con qualsiasi documento HTML, XML o SVG. Il DOM è un modello di documento caricato nel browser e rappresenta il documento come un albero di nodi, dove ogni nodo rappresenta una parte del documento (ad es. un elemento, una stringa di testo o un commento).

## Classi

| Classe | Descrizione |
| --- | --- |
| [Attr](./attr/) | L'interfaccia Attr rappresenta un attributo in un oggetto Element. Tipicamente i valori consentiti per l'attributo sono definiti in uno schema associato al documento. |
| [CDATASection](./cdatasection/) | Le sezioni CDATA sono utilizzate per eseguire l'escape di blocchi di testo contenenti caratteri che altrimenti verrebbero considerati markup. |
| [CharacterData](./characterdata/) | CharacterData estende Node con un insieme di attributi e metodi per accedere ai dati di carattere nel DOM. |
| [Comment](./comment/) | Eredita da CharacterData e rappresenta il contenuto di un commento, cioè tutti i caratteri compresi tra le virgolette iniziali ''. |
| [Document](./document/) | Il Document rappresenta l'intero documento HTML, XML o SVG. Concettualmente, è la radice dell'albero del documento e fornisce l'accesso principale ai dati del documento. |
| [DocumentFragment](./documentfragment/) | DocumentFragment è un oggetto Document "leggero" o "minimalista". È molto comune voler estrarre una porzione dell'albero di un documento o creare un nuovo frammento di un documento. |
| [DocumentType](./documenttype/) | Il DocumentType fornisce un'interfaccia all'elenco delle entità definite per il documento |
| [DOMException](./domexception/) | L'interfaccia DOMException rappresenta un evento anomalo (chiamato eccezione) che si verifica a seguito della chiamata a un metodo o dell'accesso a una proprietà di una web API. Questo è fondamentalmente il modo in cui le condizioni di errore sono descritte nelle web API. |
| [DOMObject](./domobject/) | Il tipo DOMObject è usato per rappresentare un oggetto base per l'intero Document Object Model. Per Java ed ECMAScript, DOMObject è legato al tipo Object. |
| [Element](./element/) | L'interfaccia Element rappresenta un elemento in un documento HTML o XML. |
| [Entity](./entity/) | Rappresenta un'entità nota, sia analizzata che non analizzata, in un documento XML. |
| [EntityReference](./entityreference/) | I nodi EntityReference possono essere usati per rappresentare un riferimento a un'entità nell'albero. |
| [EventTarget](./eventtarget/) | L'interfaccia EventTarget è implementata da oggetti che possono ricevere eventi e possono avere ascoltatori per essi. In altre parole, qualsiasi destinazione di eventi implementa i tre metodi associati a questa interfaccia. |
| [Node](./node/) | L'interfaccia Node è il tipo di dato principale per l'intero Document Object Model. Rappresenta un singolo nodo nell'albero del documento. Sebbene tutti gli oggetti che implementano l'interfaccia Node espongano metodi per gestire i figli, non tutti gli oggetti che implementano l'interfaccia Node possono avere figli. Per esempio, i nodi [`Text`](../com.aspose.html.dom/text/) potrebbero non avere figli, e l'aggiunta di figli a tali nodi genera un [`DOMException`](../com.aspose.html.dom/domexception/) sollevato. |
| [Notation](./notation/) | Rappresenta una notazione dichiarata nel DTD. |
| [ProcessingInstruction](./processinginstruction/) | Il ProcessingInstruction rappresenta una "istruzione di elaborazione", usata in XML come modo per mantenere informazioni specifiche del processore nel testo del documento. |
| [QualifiedName](./qualifiedname/) | Rappresenta un nome qualificato HTML. |
| [ShadowRoot](./shadowroot/) | ShadowRoot è un nodo radice dell'albero shadow. |
| [Text](./text/) | L'interfaccia Text eredita da CharacterData e rappresenta il contenuto testuale (definito dati di carattere in XML) di un Element o Attr. |
| [TypeInfo](./typeinfo/) | Il TypeInfo rappresenta un tipo referenziato da nodi Element o Attr, specificato negli schemi associati al documento. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Un contesto di navigazione è un ambiente in cui gli oggetti [`Document`](../com.aspose.html.dom/document/) sono presentati all'utente. |
| [IChildNode](./ichildnode/) | Definisce l'interfaccia [`IChildNode`](../com.aspose.html.dom/ichildnode/) che dovrebbe essere implementata da [`Node`](../com.aspose.html.dom/node/) che può avere un genitore. |
| [IDOMImplementation](./idomimplementation/) | L'interfaccia DOMImplementation fornisce numerosi metodi per eseguire operazioni indipendenti da qualsiasi istanza particolare del modello di oggetto documento. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Rappresenta un'interfaccia che deve essere ereditata da tutti gli elementi che supportano la gestione degli eventi di sistema. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | Definisce [`IChildNode`](../com.aspose.html.dom/ichildnode/) che non sono [`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/). |
| [INonElementParentNode](./inonelementparentnode/) | Definisce [`IParentNode`](../com.aspose.html.dom/iparentnode/) che non sono di tipo Element. |
| [IParentNode](./iparentnode/) | Definisce l'interfaccia [`IParentNode`](../com.aspose.html.dom/iparentnode/) che è implementata da tutti i possibili genitori. |
| [IStorage](./istorage/) | Questa interfaccia della Web Storage API fornisce l'accesso alla sessione o allo storage locale di un dominio specifico. Vedi la specifica Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Modalità in cui ShadowRoot può operare. |
