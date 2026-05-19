---
title: "Classe HTMLDocument"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.HTMLDocument. Rappresenta un documento HTML. Tutti gli oggetti HTML di livello superiore sono aggiunti a questo oggetto. Questa classe rappresenta la pagina HTML così come la vediamo nel browser. Tutti i form, le tabelle, gli script ... sono aggiunti alla pagina HTML tramite le interfacce di questa classe. HTMLDocument è l'implementazione HTML dell'interfaccia Document più generale e entrambi costituiscono il punto centrale o radice del DOM - Document Object Model. Questi concetti sono pienamente conformi alle basi o agli standard ufficiali dello sviluppo web. Per gli scopi dello sviluppo web, si può generalmente pensare a HTMLDocument come a un alias di Document su cui si basa HTMLDocument."
type: docs

url: /it/java/com.aspose.html/htmldocument/
---
## HTMLDocument class

Rappresenta un documento HTML. Tutti gli oggetti HTML di livello superiore sono aggiunti a questo oggetto. Questa classe rappresenta la pagina HTML così come la vediamo nel browser. Tutti i form, le tabelle, gli script, ... sono aggiunti alla pagina HTML tramite le interfacce di questa classe. [HTMLDocument](https://dom.spec.whatwg.org/#ref-for-dom-domimplementation-createhtmldocument) è l'implementazione HTML dell'interfaccia [Document](https://dom.spec.whatwg.org/#document) più generale e entrambi costituiscono il punto centrale o radice del [DOM](https://dom.spec.whatwg.org/) - Document Object Model. questi concetti sono pienamente conformi alle basi o agli standard ufficiali dello sviluppo web. Ai fini dello sviluppo web, si può generalmente considerare HTMLDocument come un alias di Document, su cui si basa HTMLDocument.

```java
public class HTMLDocument : Document, IDocumentCSS
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [HTMLDocument](htmldocument/#constructor)() | Il costruttore HTMLDocument crea un nuovo oggetto HTML Document che è una pagina web caricata nel browser e funge da punto di ingresso al contenuto della pagina. |
| [HTMLDocument](htmldocument/#constructor_1)(Configuration) | Il costruttore HTMLDocument crea un nuovo oggetto HTML Document che è una pagina web caricata nel browser e funge da punto di ingresso al contenuto della pagina. |
| [HTMLDocument](htmldocument/#constructor_2)(RequestMessage) | Crea un documento HTML dall'oggetto [`RequestMessage`](../../com.aspose.html.net/requestmessage/). |
| [HTMLDocument](htmldocument/#constructor_10)(String) | Carica il documento HTML da un indirizzo. |
| [HTMLDocument](htmldocument/#constructor_4)(Url) | Carica il documento HTML da un URL. |
| [HTMLDocument](htmldocument/#constructor_3)(RequestMessage, Configuration) | Crea un documento HTML da un oggetto [RequestMessage](T:com.aspose.html.net.RequestMessage). |
| [HTMLDocument](htmldocument/#constructor_8)(Stream, String) | Crea un documento HTML da un contenuto [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con base-uri specificato, utilizzato per risolvere il percorso delle risorse relative. |
| [HTMLDocument](htmldocument/#constructor_6)(Stream, Url) | Crea un documento HTML da un contenuto [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con base-uri specificato, utilizzato per risolvere il percorso delle risorse relative. |
| [HTMLDocument](htmldocument/#constructor_11)(String, Configuration) | Carica il documento HTML da un indirizzo con le impostazioni di configurazione dell'ambiente specificate. |
| [HTMLDocument](htmldocument/#constructor_14)(String, String) | Crea un documento HTML da un contenuto String con base-uri specificato. |
| [HTMLDocument](htmldocument/#constructor_12)(String, Url) | Crea un documento HTML da un contenuto String con base-uri specificato. |
| [HTMLDocument](htmldocument/#constructor_5)(Url, Configuration) | Carica il documento HTML da un URL con le impostazioni di configurazione dell'ambiente specificate. |
| [HTMLDocument](htmldocument/#constructor_9)(Stream, String, Configuration) | Crea un documento HTML da un contenuto [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con base-uri e impostazioni di configurazione dell'ambiente specificate. |
| [HTMLDocument](htmldocument/#constructor_7)(Stream, Url, Configuration) | Crea un documento HTML da un contenuto [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con base-uri e impostazioni di configurazione dell'ambiente specificate. |
| [HTMLDocument](htmldocument/#constructor_15)(String, String, Configuration) | Crea un documento HTML da un contenuto String con base-uri e impostazioni di configurazione dell'ambiente specificate. |
| [HTMLDocument](htmldocument/#constructor_13)(String, Url, Configuration) | Crea un documento HTML da un contenuto String con base-uri e impostazioni di configurazione dell'ambiente specificate. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getAnchors](../../com.aspose.html/htmldocument/anchors/) Una raccolta di tutti gli elementi anchor (`A`) in un documento con un valore per l'attributo `name`. Per motivi di retrocompatibilità, il set restituito di anchor contiene solo quelli creati con l'attributo `name`, non quelli creati con l'attributo `id`. Nota che in [[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801)], l'attributo `name` (vedi sezione 4.10) non ha semantica ed è presente solo per agenti utente legacy: l'attributo `id` è usato al suo posto. Gli utenti dovrebbero preferire i meccanismi iteratore forniti da [[DOM Level 2 Traversal](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)]. |
| [getApplets](../../com.aspose.html/htmldocument/applets/) Una raccolta di tutti gli elementi `OBJECT` che includono applet e elementi `APPLET` (deprecati) in un documento. |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) L'URI base assoluto di questo nodo o null se l'implementazione non è riuscita a ottenere un URI assoluto. |
[getBody]
[setBody] The element that contains the content for the document. In documents with `BODY` contents, returns the `BODY`element. In frameset documents, this returns the outermost `FRAMESET` element. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) Restituisce la codifica del documento. |
| [getCharset](../../com.aspose.html.dom/document/charset/) Restituisce la codifica del documento. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) Restituisce il numero corrente di nodi elemento che sono figli di questo elemento. 0 se questo elemento non ha nodi figli di tipo nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) La proprietà read-only childNodes dell'interfaccia Node restituisce una [`NodeList`](../../com.aspose.html.collections/nodelist/) live dei nodi figlio dell'elemento specificato, dove il primo nodo figlio ha indice 0. I nodi figlio includono elementi, testo e commenti. |
| [getChildren](../../com.aspose.html.dom/document/children/) Restituisce gli elementi figlio. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) Ottiene il tipo di contenuto del documento. |
| [getContext](../../com.aspose.html.dom/document/context/) Ottiene il contesto di navigazione corrente. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) L'attributo IDL defaultView dell'interfaccia Document, al momento del recupero, deve restituire l'oggetto WindowProxy del contesto di navigazione di questo Document, se questo Document ha un contesto di navigazione associato, altrimenti null. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) La dichiarazione del tipo di documento associata a questo documento. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) Questo è un attributo di comodità che consente l'accesso diretto al nodo figlio che è l'elemento documento del documento. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) La posizione del documento o null se non definita o se il Document è stato creato usando DOMImplementation.createDocument. |
| [getDomain](../../com.aspose.html/htmldocument/domain/) Il nome di dominio del server che ha fornito il documento, o `null` se il server non può essere identificato da un nome di dominio. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La proprietà read-only firstChild dell'interfaccia [`Node`](../../com.aspose.html.dom/node/) restituisce il primo figlio del nodo nell'albero, o null se il nodo non ha figli. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) Restituisce il primo nodo elemento figlio di questo elemento. null se questo elemento non ha elementi figli. |
| [getForms](../../com.aspose.html/htmldocument/forms/) Una raccolta di tutti i form di un documento. |
| [getImages](../../com.aspose.html/htmldocument/images/) Una raccolta di tutti gli elementi `IMG` in un documento. Il comportamento è limitato agli elementi `IMG` per retrocompatibilità. Come suggerito da [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)], per includere immagini gli autori possono usare l'elemento `OBJECT` o l'elemento `IMG`. Pertanto, si raccomanda di non usare questo attributo per trovare le immagini nel documento, ma di utilizzare `getElementsByTagName` con HTML 4.01 o `getElementsByTagNameNS` con XHTML 1.0. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) L'oggetto DOMImplementation che gestisce questo documento. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) Ottiene la codifica del documento. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La proprietà read-only lastChild dell'interfaccia [`Node`](../../com.aspose.html.dom/node/) restituisce l'ultimo figlio del nodo. Se il suo genitore è un elemento, il figlio è generalmente un nodo elemento, un nodo di testo o un nodo commento. Restituisce null se non ci sono elementi figli |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) Restituisce l'ultimo nodo elemento figlio di questo elemento. null se questo elemento non ha elementi figli. |
| [getLinks](../../com.aspose.html/htmldocument/links/) Una raccolta di tutti gli elementi `AREA` e gli anchor (`A`) in un documento con un valore per l'attributo `href`. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Restituisce la parte locale del nome qualificato di questo nodo. Per i nodi di qualsiasi tipo diverso da [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) e [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) e per i nodi creati con un metodo DOM Level 1, come [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/), questo è sempre null. |
| [getLocation](../../com.aspose.html.dom/document/location/) La posizione del documento. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) La proprietà di sola lettura Element.packageURI restituisce l'URI del pacchetto dell'elemento, o null se l'elemento non è in un pacchetto. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) Restituisce il nodo elemento fratello successivo di questo elemento. null se questo elemento non ha nodi fratelli elemento che lo seguono nell'albero del documento. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La proprietà di sola lettura nextSibling dell'interfaccia [`Node`](../../com.aspose.html.dom/node/) restituisce il nodo immediatamente successivo a quello specificato nel [`childNodes`](../../com.aspose.html.dom/node/childnodes/) del genitore, oppure restituisce null se il nodo specificato è l'ultimo figlio nell'elemento genitore. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) Il nome di questo nodo, a seconda del suo tipo. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) Un codice che rappresenta il tipo dell'oggetto sottostante. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | La proprietà nodeValue dell'interfaccia [`Node `](../../com.aspose.html.dom/node/) restituisce o imposta il valore del nodo corrente. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) Ottiene l'origine del documento. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) Ottiene il documento proprietario. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La proprietà di sola lettura parentElement dell'interfaccia [`Node`](../../com.aspose.html.dom/node/) restituisce il genitore DOM del nodo, ovvero [`Element`](../../com.aspose.html.dom/element/), o null se il nodo non ha genitore o se il suo genitore non è un Element DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La proprietà di sola lettura parentNode dell'interfaccia Node restituisce il genitore del nodo specificato nell'albero DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | La proprietà di sola lettura prefix restituisce il prefisso del pacchetto dell'elemento specificato, o null se non è specificato alcun prefisso. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) Restituisce il nodo elemento fratello precedente di questo elemento. null se questo elemento non ha nodi fratelli elemento che lo precedono nell'albero del documento. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La proprietà di sola lettura previousSibling dell'interfaccia [`Node`](../../com.aspose.html.dom/node/) restituisce il nodo immediatamente precedente a quello specificato nella lista [`childNodes`](../../com.aspose.html.dom/node/firstchild/) del genitore, oppure null se il nodo specificato è il primo in quella lista. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) Restituisce lo stato di prontezza del documento. \"loading\" mentre il Document è in caricamento, \"interactive\" una volta terminata l'analisi ma ancora in caricamento delle sotto-risorse, e \"complete\" una volta completato il caricamento. |
| [getReferrer](../../com.aspose.html/htmldocument/referrer/) Restituisce l'URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)] della pagina che ha collegato a questa pagina. Il valore è una stringa vuota se l'utente ha navigato direttamente alla pagina (non tramite un link, ma, ad esempio, tramite un segnalibro). |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) Un elenco contenente tutti i fogli di stile collegati esplicitamente o incorporati in un documento. Per i documenti HTML, ciò include i fogli di stile esterni, inclusi tramite l'elemento HTML LINK, e gli elementi STYLE inline. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | La proprietà textContent dell'interfaccia [`Node`](../../com.aspose.html.dom/node/) rappresenta il contenuto testuale del nodo e dei suoi discendenti. |
[getTitle]
[setTitle] The title of a document as specified by the `TITLE` element in the head of the document. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Il metodo addEventListener() dell'interfaccia [`EventTarget `](../../com.aspose.html.dom/eventtarget/) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Il metodo addEventListener() dell'interfaccia [EventTarget ](T:com.aspose.html.dom.EventTarget) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Il metodo addEventListener() dell'interfaccia [EventTarget ](T:com.aspose.html.dom.EventTarget) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Il metodo appendChild() dell'interfaccia Node aggiunge un nodo alla fine dell'elenco dei figli di un nodo genitore specificato. Se il figlio fornito è un riferimento a un nodo esistente nel documento, appendChild() lo sposta dalla sua posizione attuale a quella nuova (non è necessario rimuovere il nodo dal suo nodo genitore prima di aggiungerlo a un altro nodo). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Il metodo cloneNode() dell'interfaccia Node restituisce un duplicato del nodo su cui è stato chiamato questo metodo. Il suo parametro controlla se il sottoalbero contenuto in un nodo viene anche clonato o meno. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Il metodo cloneNode() dell'interfaccia Node restituisce un duplicato del nodo su cui è stato chiamato questo metodo. Il suo parametro controlla se il sottoalbero contenuto in un nodo viene anche clonato o meno. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Il metodo Document.createAttribute() crea un nuovo nodo attributo e lo restituisce. L'oggetto crea un nodo che implementa l'interfaccia [`Attr`](../../com.aspose.html.dom/attr/). Il DOM non impone quale tipo di attributi possa essere aggiunto a un elemento particolare in questo modo. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Il metodo Document.createAttribute() crea un nuovo nodo attributo e lo restituisce. L'oggetto crea un nodo che implementa l'interfaccia [Attr](T:com.aspose.html.dom.Attr). Il DOM non impone quale tipo di attributi possa essere aggiunto a un elemento particolare in questo modo. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | Crea un nodo [`CDATASection`](../../com.aspose.html.dom/cdatasection/) il cui valore è la Stringa specificata. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | Crea un nodo [`Comment`](../../com.aspose.html.dom/comment/) dato la Stringa specificata. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | Crea un nuovo [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) vuoto nel quale è possibile aggiungere nodi DOM per costruire un albero DOM offscreen. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | Il metodo restituisce un oggetto [`DocumentType`](../../com.aspose.html.dom/documenttype/) che può essere usato con DOMImplementation.createDocument durante la creazione del documento o inserito nel documento tramite metodi come Node.insertBefore() o Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | In un documento HTML, il metodo document.createElement() crea l'elemento HTML specificato da tagName, oppure un [`HTMLUnknownElement`](../htmlunknownelement/) se tagName non è riconosciuto. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | Crea un elemento con il nome qualificato e l'URI del pacchetto forniti. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | Crea un oggetto EntityReference. Inoltre, se l'entità referenziata è nota, l'elenco dei figli del nodo EntityReference viene reso identico a quello del corrispondente nodo Entity. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | Crea un [`Event`](../../com.aspose.html.dom.events/event/) di un tipo supportato dall'implementazione. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | Crea un'espressione XPath analizzata con i pacchetti risolti. Questo è utile quando un'espressione verrà riutilizzata in un'applicazione poiché consente di compilare la Stringa dell'espressione in una forma interna più efficiente e di pre-risolvere tutti i prefissi dei pacchetti presenti nell'espressione. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node) | Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long) | Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | Adatta qualsiasi nodo DOM per risolvere i pacchetti in modo che un'espressione XPath possa essere valutata facilmente rispetto al contesto del nodo in cui è comparsa all'interno del documento. Questo adattatore funziona come il metodo DOM Level 3 `lookupNamespaceURI` sui nodi nella risoluzione del packageURI da un prefisso dato, utilizzando le informazioni correnti disponibili nella gerarchia del nodo al momento della chiamata a lookupNamespaceURI, risolvendo correttamente anche il prefisso xml implicito. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | Crea un nodo ProcessingInstruction dato il nome e le stringhe di dati specificati. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | Crea un nodo Text dato la Stringa specificata. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node) | Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long) | Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Esegue la distribuzione di un Event al [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) specificato, (sincronamente) invocando gli EventListener interessati nell'ordine appropriato. Le regole normali di elaborazione degli eventi (inclusa la fase di cattura e quella di bubbling opzionale) si applicano anche agli eventi distribuiti manualmente con [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset di risorse non gestite. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Valuta una Stringa di espressione XPath e restituisce un risultato del tipo specificato, se possibile. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Il metodo Document getElementById() restituisce un oggetto [`Element`](../../com.aspose.html.dom/element/) che rappresenta l'elemento il cui attributo id corrisponde alla Stringa specificata. Poiché gli ID degli elementi devono essere unici se specificati, sono un modo utile per accedere rapidamente a un elemento specifico. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | Il metodo getElementsByClassName dell'interfaccia [`Document`](../../com.aspose.html.dom/document/) restituisce un oggetto simile a un array di tutti gli elementi figli che possiedono tutti i nomi di classe forniti. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | Il metodo getElementsByTagName dell'interfaccia [`Document`](../../com.aspose.html.dom/document/) restituisce una [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) di elementi con il nome di tag fornito. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | Restituisce un elenco di elementi con il nome di tag fornito appartenenti al pacchetto specificato. Viene cercato l'intero documento, inclusa la radice. |
| [getOverrideStyle](../../com.aspose.html/htmldocument/getoverridestyle/)(Element, String) | Questo metodo è usato per recuperare la dichiarazione di stile di override per un elemento specificato e un pseudo-elemento specificato. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Il metodo hasChildNodes() dell'interfaccia Node restituisce un valore booleano che indica se il dato [`Node`](../../com.aspose.html.dom/node/) ha nodi figli o meno. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | Importa un nodo da un altro documento a questo documento, senza modificare o rimuovere il nodo sorgente dal documento originale; questo metodo crea una nuova copia del nodo sorgente. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Il metodo insertBefore() dell'interfaccia Node inserisce un nodo prima di un nodo di riferimento come figlio di un nodo genitore specificato. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Il metodo isDefaultNamespace() dell'interfaccia Node accetta un URI del pacchetto come argomento. Restituisce un valore booleano che è true se il pacchetto è quello predefinito sul nodo dato e false altrimenti. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Il metodo isEqualNode() dell'interfaccia [`Node`](../../com.aspose.html.dom/node/) verifica se due nodi sono uguali. Due nodi sono uguali quando hanno lo stesso tipo, caratteristiche distintive (per gli elementi, ad esempio ID, numero di figli, ecc.), i loro attributi corrispondono, e così via. L'insieme specifico di dati che devono corrispondere varia a seconda dei tipi dei nodi. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Il metodo isSameNode() dell'interfaccia Node è un alias legacy per l'operatore di uguaglianza stretta ===. Cioè, verifica se due nodi sono gli stessi (in altre parole, se fanno riferimento allo stesso oggetto). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Il metodo lookupNamespaceURI() dell'interfaccia Node prende un prefisso come parametro e restituisce l'URI del pacchetto associato su quel nodo, se trovato (e null se non lo è). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Il metodo lookupPrefix() dell'interfaccia Node restituisce una String contenente il prefisso per un dato URI del pacchetto, se presente, e null se non lo è. Quando sono possibili più prefissi, viene restituito il primo prefisso. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(RequestMessage) | Carica il documento in base all'oggetto request specificato, sostituendo il contenuto precedente. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String) | Carica il documento all'Uniform Resource Locator (URL) specificato nell'istanza corrente, sostituendo il contenuto precedente. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Url) | Carica il documento all'Uniform Resource Locator (URL) specificato nell'istanza corrente, sostituendo il contenuto precedente. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, String) | Carica il documento dal contenuto specificato utilizzando baseUri per risolvere le risorse relative, sostituendo il contenuto precedente. Il caricamento del documento inizia dalla posizione corrente nello stream. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, Url) | Carica il documento dal contenuto specificato utilizzando baseUri per risolvere le risorse relative, sostituendo il contenuto precedente. Il caricamento del documento inizia dalla posizione corrente nello stream. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, String) | Carica il documento dal contenuto specificato utilizzando baseUri per risolvere le risorse relative, sostituendo il contenuto precedente. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, Url) | Carica il documento dal contenuto specificato utilizzando baseUri per risolvere le risorse relative, sostituendo il contenuto precedente. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Mette tutti i nodi [`Text`](../../com.aspose.html.dom/text/) nella massima profondità del sotto-albero sotto questo Nodo, inclusi i nodi attributo, in una forma "normale" in cui solo la struttura (ad es., [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), e [`entity references`](../../com.aspose.html.dom/entityreference/)) separa i nodi [`Text`](../../com.aspose.html.dom/text/), cioè non ci sono nodi Text adiacenti né nodi Text vuoti. Questo può essere usato per garantire che la vista DOM di un documento sia la stessa di quella che si otterrebbe salvandolo e ricaricandolo, ed è utile quando operazioni (come le ricerche XPointer [XPointer]) che dipendono da una particolare struttura dell'albero del documento devono essere utilizzate. Se il parametro "normalize-characters" dell'oggetto [`DOMConfiguration`](../configuration/) collegato al [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) è true, questo metodo normalizzerà anche completamente i caratteri dei nodi Text. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | Restituisce il primo Element nel documento che corrisponde al selettore |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | Restituisce un NodeList di tutti gli Elements nel documento che corrispondono al selettore |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Il metodo removeChild() dell'interfaccia Node rimuove un nodo figlio dal DOM e restituisce il nodo rimosso. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [renderTo](../../com.aspose.html/htmldocument/renderto/)(IDevice) | Questo metodo è usato per stampare il contenuto del documento corrente sul dispositivo specificato. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Sostituisce il nodo figlio oldChild con newChild nell'elenco dei figli e restituisce il nodo oldChild. Se newChild è un oggetto [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), oldChild viene sostituito da tutti i figli del [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) che vengono inseriti nello stesso ordine. Se newChild è già nell'albero, viene prima rimosso. |
| [save](../../com.aspose.html/htmldocument/save/#save)(ResourceHandler) | Salva il contenuto del documento e le risorse utilizzando il [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_10)(String) | Salva il documento in un file locale specificato dal percorso. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_5)(Url) | Salva il documento in un file locale specificato dall'url. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_1)(ResourceHandler, HTMLSaveFormat) | Salva il contenuto del documento e le risorse utilizzando il [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_2)(ResourceHandler, HTMLSaveOptions) | Salva il contenuto del documento e le risorse utilizzando il [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_3)(ResourceHandler, MarkdownSaveOptions) | Salva il contenuto del documento e le risorse utilizzando il [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_4)(ResourceHandler, MHTMLSaveOptions) | Salva il contenuto del documento e le risorse utilizzando il [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_11)(String, HTMLSaveFormat) | Salva il documento in un file locale specificato dal percorso. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_12)(String, HTMLSaveOptions) | Salva il documento in un file locale specificato dal percorso. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_13)(String, MarkdownSaveOptions) | Salva il documento in un file locale specificato dal percorso. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_14)(String, MHTMLSaveOptions) | Salva il documento in un file locale specificato dal percorso. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_6)(Url, HTMLSaveFormat) | Salva il documento in un file locale specificato dall'url. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_7)(Url, HTMLSaveOptions) | Salva il documento in un file locale specificato dall'url. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_8)(Url, MarkdownSaveOptions) | Salva il documento in un file locale specificato dall'url. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_9)(Url, MHTMLSaveOptions) | Salva il documento in un file locale specificato dall'url. Tutte le risorse utilizzate in questo documento saranno salvate in una cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [toString](../../com.aspose.html.dom/node/toString/)() | Restituisce una String che rappresenta questa istanza. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | Scrivi una stringa di testo in un flusso di documento aperto da open(). Nota che la funzione produrrà un documento che non è necessariamente guidato da un DTD e quindi potrebbe generare un risultato non valido nel contesto del documento. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | Scrivi una stringa di testo seguita da un carattere di nuova riga in un flusso di documento aperto da open(). Nota che la funzione produrrà un documento che non è necessariamente guidato da un DTD e quindi potrebbe generare un risultato non valido nel contesto del documento. |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | Ottiene o imposta il gestore dell'evento OnAbort. |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | Ottiene o imposta il gestore dell'evento OnBlur. |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | Ottiene o imposta il gestore dell'evento OnCancel. |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | Ottiene o imposta il gestore dell'evento OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | Ottiene o imposta il gestore dell'evento OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | Ottiene o imposta il gestore dell'evento OnChange. |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | Ottiene o imposta il gestore dell'evento OnClick. |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | Ottiene o imposta il gestore dell'evento OnCueChange. |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | Ottiene o imposta il gestore dell'evento OnDblClick. |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | Ottiene o imposta il gestore dell'evento OnDurationChange. |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | Ottiene o imposta il gestore dell'evento OnEmptied. |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | Ottiene o imposta il gestore dell'evento OnEnded. |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | Ottiene o imposta il gestore dell'evento OnError. |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | Ottiene o imposta il gestore dell'evento OnFocus. |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | Ottiene o imposta il gestore dell'evento OnInput. |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | Ottiene o imposta il gestore dell'evento per l'evento OnInvalid. |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | Ottiene o imposta il gestore dell'evento per l'evento OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | Ottiene o imposta il gestore dell'evento per l'evento OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | Ottiene o imposta il gestore dell'evento per l'evento OnKeyUp. |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | Ottiene o imposta il gestore dell'evento per l'evento OnLoad. |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | Ottiene o imposta il gestore dell'evento per l'evento OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | Ottiene o imposta il gestore dell'evento per l'evento OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | Ottiene o imposta il gestore dell'evento per l'evento OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | Ottiene o imposta il gestore dell'evento per l'evento OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | Ottiene o imposta il gestore dell'evento per l'evento OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | Ottiene o imposta il gestore dell'evento per l'evento OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | Ottiene o imposta il gestore dell'evento per l'evento OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | Ottiene o imposta il gestore dell'evento per l'evento OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | Ottiene o imposta il gestore dell'evento per l'evento OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | Ottiene o imposta il gestore dell'evento per l'evento OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | Ottiene o imposta il gestore dell'evento per l'evento OnMouseWheel. |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | Ottiene o imposta il gestore dell'evento per l'evento OnPause. |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | Ottiene o imposta il gestore dell'evento per l'evento OnPlay. |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | Ottiene o imposta il gestore dell'evento per l'evento OnPlaying. |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | Ottiene o imposta il gestore dell'evento per l'evento OnProgress. |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | Ottiene o imposta il gestore dell'evento per l'evento OnRateChange. |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | Ottiene o imposta il gestore dell'evento per l'evento OnReadyStateChange. |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | Ottiene o imposta il gestore dell'evento per l'evento OnReset. |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | Ottiene o imposta il gestore dell'evento per l'evento OnResize. |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | Ottiene o imposta il gestore dell'evento per l'evento OnScroll. |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | Ottiene o imposta il gestore dell'evento OnSeeked. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | Ottiene o imposta il gestore dell'evento OnSeeking. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | Ottiene o imposta il gestore dell'evento OnSelect. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | Ottiene o imposta il gestore dell'evento OnShow. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | Ottiene o imposta il gestore dell'evento OnStalled. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | Ottiene o imposta il gestore dell'evento OnSubmit. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | Ottiene o imposta il gestore dell'evento OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | Ottiene o imposta il gestore dell'evento OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | Ottiene o imposta il gestore dell'evento OnToggle. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | Ottiene o imposta il gestore dell'evento OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | Ottiene o imposta il gestore dell'evento OnWaiting. |

## Osservazioni

Maggiori informazioni su HTMLDocument, Document e DOM possono essere ottenute nelle risorse popolari di sviluppo web:

[General Document interface](https://developer.mozilla.org/en-US/docs/Web/API/Document).[Html specific HTMLDocument interface](https://developer.mozilla.org/en-US/docs/Web/API/HTMLDocument).[What is the HTML DOM](https://www.w3schools.com/js/js_htmldom.asp).

Riferimento agli standard:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Esempi

```java
    // Crea un'istanza di un documento HTML
	using (var document = new HTMLDocument())
      {
        // Crea un elemento style e assegna il colore verde a tutti gli elementi il cui nome di classe è 'gr'.
        var style = document.CreateElement("style");
        style.TextContent = ".gr { color: green }";

        // Trova l'elemento header del documento e aggiungi l'elemento style all'header
        var head = document.GetElementsByTagName("head").First();
        head.AppendChild(style);

        // Crea un elemento paragraph con nome di classe 'gr'.
        var p = (HTMLParagraphElement)document.CreateElement("p");
        p.ClassName = "gr";

        // Crea un nodo di testo
        var text = document.CreateTextNode("Hello World!!");

        // Aggiungi il nodo di testo al paragrafo
        p.AppendChild(text);

        // Aggiungi il paragrafo all'elemento body del documento
        document.Body.AppendChild(p);

        // Salva il documento HTML in un file 
        document.Save(Path.Combine(OutputDir, "using-dom.html"));

        // Crea un'istanza del dispositivo di output PDF e renderizza il documento in questo dispositivo
        using (var device = new PdfDevice(Path.Combine(OutputDir, "using-dom.pdf")))
        {
          // Renderizza HTML in PDF
          document.RenderTo(device);
        }
      }       
```

### Vedi anche

* class [Document](../../com.aspose.html.dom/document/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
