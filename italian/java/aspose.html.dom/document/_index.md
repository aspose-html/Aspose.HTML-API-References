---
title: "Classe Document"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.dom.Document. Il Document rappresenta l'intero documento HTML, XML o SVG. Concettualmente è la radice dell'albero del documento e fornisce l'accesso principale ai dati del documento"
type: docs

url: /it/java/com.aspose.html.dom/document/
---
## Document class

Il Document rappresenta l'intero documento HTML, XML o SVG. Concettualmente, è la radice dell'albero del documento e fornisce l'accesso principale ai dati del documento.

```java
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) L'URI base assoluto di questo nodo o null se l'implementazione non è riuscita a ottenere un URI assoluto. |
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
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La proprietà di sola lettura firstChild dell'interfaccia [`Node`](../node/) restituisce il primo figlio del nodo nell'albero, o null se il nodo non ha figli. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) Restituisce il primo nodo elemento figlio di questo elemento. null se questo elemento non ha elementi figli. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) L'oggetto DOMImplementation che gestisce questo documento. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) Ottiene la codifica del documento. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La proprietà di sola lettura lastChild dell'interfaccia [`Node`](../node/) restituisce l'ultimo figlio del nodo. Se il suo genitore è un elemento, il figlio è generalmente un nodo elemento, un nodo di testo o un nodo commento. Restituisce null se non ci sono elementi figli. |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) Restituisce l'ultimo nodo elemento figlio di questo elemento. null se questo elemento non ha elementi figli. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Restituisce la parte locale del nome qualificato di questo nodo. Per i nodi di qualsiasi tipo diverso da [`ELEMENT_NODE`](../node/element_node/) e [`ATTRIBUTE_NODE`](../node/attribute_node/) e i nodi creati con un metodo DOM di livello 1, come [`Document.createElement()`](./createelement/), questo è sempre null. |
| [getLocation](../../com.aspose.html.dom/document/location/) La posizione del documento. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) La proprietà di sola lettura Element.packageURI restituisce l'URI del pacchetto dell'elemento, o null se l'elemento non è in un pacchetto. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) Restituisce il nodo elemento fratello successivo di questo elemento. null se questo elemento non ha nodi fratelli elemento che lo seguono nell'albero del documento. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La proprietà di sola lettura nextSibling dell'interfaccia [`Node`](../node/) restituisce il nodo immediatamente successivo a quello specificato nel [`childNodes`](../node/childnodes/) del genitore, o restituisce null se il nodo specificato è l'ultimo figlio nell'elemento genitore. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) Il nome di questo nodo, a seconda del suo tipo. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) Un codice che rappresenta il tipo dell'oggetto sottostante. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | La proprietà nodeValue dell'interfaccia [`Node `](../node/) restituisce o imposta il valore del nodo corrente. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) Ottiene l'origine del documento. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) Ottiene il documento proprietario. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La proprietà di sola lettura parentElement dell'interfaccia [`Node`](../node/) restituisce il [`Element`](../element/) genitore del nodo DOM, o null se il nodo non ha genitore o il suo genitore non è un Element DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La proprietà di sola lettura parentNode dell'interfaccia Node restituisce il genitore del nodo specificato nell'albero DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | La proprietà di sola lettura prefix restituisce il prefisso del pacchetto dell'elemento specificato, o null se non è specificato alcun prefisso. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) Restituisce il nodo elemento fratello precedente di questo elemento. null se questo elemento non ha nodi fratelli elemento che lo precedono nell'albero del documento. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La proprietà di sola lettura previousSibling dell'interfaccia [`Node`](../node/) restituisce il nodo immediatamente precedente a quello specificato nella lista dei [`childNodes`](../node/firstchild/) del genitore, o null se il nodo specificato è il primo nella lista. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) Restituisce lo stato di prontezza del documento. \"loading\" mentre il Document è in caricamento, \"interactive\" una volta terminata l'analisi ma ancora in caricamento delle sotto-risorse, e \"complete\" una volta completato il caricamento. |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) Un elenco contenente tutti i fogli di stile collegati esplicitamente o incorporati in un documento. Per i documenti HTML, ciò include i fogli di stile esterni, inclusi tramite l'elemento HTML LINK, e gli elementi STYLE inline. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | La proprietà textContent dell'interfaccia [`Node`](../node/) rappresenta il contenuto testuale del nodo e dei suoi discendenti. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Il metodo addEventListener() dell'interface [`EventTarget `](../eventtarget/) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Il metodo addEventListener() dell'interfaccia [EventTarget ](T:com.aspose.html.dom.EventTarget) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Il metodo addEventListener() dell'interfaccia [EventTarget ](T:com.aspose.html.dom.EventTarget) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Il metodo appendChild() dell'interfaccia Node aggiunge un nodo alla fine dell'elenco dei figli di un nodo genitore specificato. Se il figlio fornito è un riferimento a un nodo esistente nel documento, appendChild() lo sposta dalla sua posizione attuale a quella nuova (non è necessario rimuovere il nodo dal suo nodo genitore prima di aggiungerlo a un altro nodo). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Il metodo cloneNode() dell'interfaccia Node restituisce un duplicato del nodo su cui è stato chiamato questo metodo. Il suo parametro controlla se il sottoalbero contenuto in un nodo viene anche clonato o meno. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Il metodo cloneNode() dell'interfaccia Node restituisce un duplicato del nodo su cui è stato chiamato questo metodo. Il suo parametro controlla se il sottoalbero contenuto in un nodo viene anche clonato o meno. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Il metodo Document.createAttribute() crea un nuovo nodo attributo e lo restituisce. L'oggetto crea un nodo che implementa l'interfaccia [`Attr`](../attr/). Il DOM non impone quale tipo di attributi possa essere aggiunto a un particolare elemento in questo modo. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Il metodo Document.createAttribute() crea un nuovo nodo attributo e lo restituisce. L'oggetto crea un nodo che implementa l'interfaccia [Attr](T:com.aspose.html.dom.Attr). Il DOM non impone quale tipo di attributi possa essere aggiunto a un elemento particolare in questo modo. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | Crea un nodo [`CDATASection`](../cdatasection/) il cui valore è la Stringa specificata. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | Crea un nodo [`Comment`](../comment/) dato la Stringa specificata. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | Crea un nuovo [`DocumentFragment`](../documentfragment/) vuoto nel quale è possibile aggiungere nodi DOM per costruire un albero DOM fuori schermo. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | Il metodo restituisce un oggetto [`DocumentType`](../documenttype/) che può essere usato con DOMImplementation.createDocument durante la creazione del documento o può essere inserito nel documento tramite metodi come Node.insertBefore() o Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | In un documento HTML, il metodo document.createElement() crea l'elemento HTML specificato da tagName, o un [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/) se tagName non è riconosciuto. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | Crea un elemento con il nome qualificato e l'URI del pacchetto forniti. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | Crea un oggetto EntityReference. Inoltre, se l'entità referenziata è nota, l'elenco dei figli del nodo EntityReference viene reso identico a quello del corrispondente nodo Entity. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | Crea un [`Event`](../../com.aspose.html.dom.events/event/) di un tipo supportato dall'implementazione. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | Crea un'espressione XPath analizzata con i pacchetti risolti. Questo è utile quando un'espressione verrà riutilizzata in un'applicazione poiché consente di compilare la Stringa dell'espressione in una forma interna più efficiente e di pre-risolvere tutti i prefissi dei pacchetti presenti nell'espressione. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator)(Node) | Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_1)(Node, long) | Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | Adatta qualsiasi nodo DOM per risolvere i pacchetti in modo che un'espressione XPath possa essere valutata facilmente rispetto al contesto del nodo in cui è comparsa all'interno del documento. Questo adattatore funziona come il metodo DOM Level 3 `lookupNamespaceURI` sui nodi nella risoluzione del packageURI da un prefisso dato, utilizzando le informazioni correnti disponibili nella gerarchia del nodo al momento della chiamata a lookupNamespaceURI, risolvendo correttamente anche il prefisso xml implicito. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | Crea un nodo ProcessingInstruction dato il nome e le stringhe di dati specificati. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | Crea un nodo Text dato la Stringa specificata. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker)(Node) | Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_1)(Node, long) | Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Esegue la distribuzione di un Event al [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) specificato, (sincronamente) invocando gli EventListener interessati nell'ordine appropriato. Le regole normali di elaborazione degli eventi (inclusa la fase di cattura e quella di bubbling opzionale) si applicano anche agli eventi distribuiti manualmente con [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset di risorse non gestite. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Valuta una Stringa di espressione XPath e restituisce un risultato del tipo specificato, se possibile. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Il metodo Document getElementById() restituisce un oggetto [`Element`](../element/) che rappresenta l'elemento la cui proprietà id corrisponde alla Stringa specificata. Poiché gli ID degli elementi devono essere unici se specificati, sono un modo utile per accedere rapidamente a un elemento specifico. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | Il metodo getElementsByClassName dell'interfaccia `Document` restituisce un oggetto simile a un array di tutti gli elementi figli che possiedono tutti i nomi di classe forniti. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | Il metodo getElementsByTagName dell'interfaccia `Document` restituisce una [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) di elementi con il nome di tag fornito. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | Restituisce un elenco di elementi con il nome di tag fornito appartenenti al pacchetto specificato. Viene cercato l'intero documento, inclusa la radice. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Il metodo hasChildNodes() dell'interfaccia Node restituisce un valore booleano che indica se il dato [`Node`](../node/) ha nodi figli o meno. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | Importa un nodo da un altro documento a questo documento, senza modificare o rimuovere il nodo sorgente dal documento originale; questo metodo crea una nuova copia del nodo sorgente. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Il metodo insertBefore() dell'interfaccia Node inserisce un nodo prima di un nodo di riferimento come figlio di un nodo genitore specificato. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Il metodo isDefaultNamespace() dell'interfaccia Node accetta un URI del pacchetto come argomento. Restituisce un valore booleano che è true se il pacchetto è quello predefinito sul nodo dato e false altrimenti. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Il metodo isEqualNode() dell'interfaccia [`Node`](../node/) verifica se due nodi sono uguali. Due nodi sono uguali quando hanno lo stesso tipo, caratteristiche distintive (per gli elementi, ad esempio ID, numero di figli, ecc.), i loro attributi corrispondono, e così via. L'insieme specifico di dati che devono corrispondere varia a seconda dei tipi dei nodi. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Il metodo isSameNode() dell'interfaccia Node è un alias legacy per l'operatore di uguaglianza stretta ===. Cioè, verifica se due nodi sono gli stessi (in altre parole, se fanno riferimento allo stesso oggetto). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Il metodo lookupNamespaceURI() dell'interfaccia Node prende un prefisso come parametro e restituisce l'URI del pacchetto associato su quel nodo, se trovato (e null se non lo è). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Il metodo lookupPrefix() dell'interfaccia Node restituisce una String contenente il prefisso per un dato URI del pacchetto, se presente, e null se non lo è. Quando sono possibili più prefissi, viene restituito il primo prefisso. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate)(RequestMessage) | Carica il documento in base all'oggetto request specificato, sostituendo il contenuto precedente. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_4)(String) | Carica il documento all'Uniform Resource Locator (URL) specificato nell'istanza corrente, sostituendo il contenuto precedente. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_1)(Url) | Carica il documento all'Uniform Resource Locator (URL) specificato nell'istanza corrente, sostituendo il contenuto precedente. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_3)(Stream, String) | Carica il documento dal contenuto specificato utilizzando baseUri per risolvere le risorse relative, sostituendo il contenuto precedente. Il caricamento del documento inizia dalla posizione corrente nello stream. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_2)(Stream, Url) | Carica il documento dal contenuto specificato utilizzando baseUri per risolvere le risorse relative, sostituendo il contenuto precedente. Il caricamento del documento inizia dalla posizione corrente nello stream. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_6)(String, String) | Carica il documento dal contenuto specificato utilizzando baseUri per risolvere le risorse relative, sostituendo il contenuto precedente. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_5)(String, Url) | Carica il documento dal contenuto specificato utilizzando baseUri per risolvere le risorse relative, sostituendo il contenuto precedente. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Posiziona tutti i nodi [`Text`](../text/) nella profondità completa del sotto-albero sotto questo Node, inclusi i nodi attributo, in una forma "normal" in cui solo la struttura (ad esempio [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), e [`entity references`](../entityreference/)) separa i nodi [`Text`](../text/), cioè non ci sono né nodi Text adiacenti né nodi Text vuoti. Questo può essere usato per garantire che la vista DOM di un documento sia la stessa di quella che si otterrebbe salvando e ricaricando il documento, ed è utile quando operazioni (come le ricerche XPointer [XPointer]) che dipendono da una particolare struttura dell'albero del documento devono essere utilizzate. Se il parametro "normalize-characters" dell'oggetto [`DOMConfiguration`](../../com.aspose.html/configuration/) collegato al [`Node.ownerDocument`](../node/ownerdocument/) è true, questo metodo normalizzerà anche completamente i caratteri dei nodi Text. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | Restituisce il primo Element nel documento che corrisponde al selettore |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | Restituisce un NodeList di tutti gli Elements nel documento che corrispondono al selettore |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Il metodo removeChild() dell'interfaccia Node rimuove un nodo figlio dal DOM e restituisce il nodo rimosso. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [renderTo](../../com.aspose.html.dom/document/renderto/)(IDevice) | Questo metodo è usato per renderizzare il contenuto del documento corrente su un dispositivo grafico specificato. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Sostituisce il nodo figlio oldChild con newChild nell'elenco dei figli e restituisce il nodo oldChild. Se newChild è un oggetto [`DocumentFragment`](../documentfragment/), oldChild viene sostituito da tutti i figli del [`DocumentFragment`](../documentfragment/), inseriti nello stesso ordine. Se newChild è già nell'albero, viene prima rimosso. |
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

### Vedi anche

* class [Node](../node/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../com.aspose.html.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../com.aspose.html.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../com.aspose.html.dom.xpath/ixpathevaluator/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
