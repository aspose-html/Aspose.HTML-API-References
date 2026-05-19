---
title: "Classe Notation"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.dom.Notation. Rappresenta una notazione dichiarata nel DTD"
type: docs

url: /it/java/com.aspose.html.dom/notation/
---
## Notation class

Rappresenta una notazione dichiarata nel DTD.

```java
public class Notation : Node
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) La proprietà read-only baseURI dell'interfaccia Node restituisce l'URL base assoluto del documento che contiene il nodo. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) La proprietà read-only childNodes dell'interfaccia Node restituisce una [`NodeList`](../../com.aspose.html.collections/nodelist/) live dei nodi figlio dell'elemento specificato, dove il primo nodo figlio ha indice 0. I nodi figlio includono elementi, testo e commenti. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) La proprietà di sola lettura firstChild dell'interfaccia [`Node`](../node/) restituisce il primo figlio del nodo nell'albero, o null se il nodo non ha figli. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) La proprietà di sola lettura lastChild dell'interfaccia [`Node`](../node/) restituisce l'ultimo figlio del nodo. Se il suo genitore è un elemento, il figlio è generalmente un nodo elemento, un nodo di testo o un nodo commento. Restituisce null se non ci sono elementi figli. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Restituisce la parte locale del nome qualificato di questo nodo. Per i nodi di qualsiasi tipo diverso da [`ELEMENT_NODE`](../node/element_node/) e [`ATTRIBUTE_NODE`](../node/attribute_node/) e i nodi creati con un metodo DOM di livello 1, come [`Document.createElement()`](../document/createelement/), questo è sempre null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) La proprietà di sola lettura Element.packageURI restituisce l'URI del pacchetto dell'elemento, o null se l'elemento non è in un pacchetto. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) La proprietà di sola lettura nextSibling dell'interfaccia [`Node`](../node/) restituisce il nodo immediatamente successivo a quello specificato nel [`childNodes`](../node/childnodes/) del genitore, o restituisce null se il nodo specificato è l'ultimo figlio nell'elemento genitore. |
| [getNodeName](../../com.aspose.html.dom/notation/nodename/) Il nome di questo nodo, a seconda del suo tipo. |
| [getNodeType](../../com.aspose.html.dom/notation/nodetype/) Un codice che rappresenta il tipo dell'oggetto sottostante. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | La proprietà nodeValue dell'interfaccia [`Node `](../node/) restituisce o imposta il valore del nodo corrente. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) La proprietà di sola lettura ownerDocument dell'interfaccia Node restituisce l'oggetto documento di livello superiore del nodo. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) La proprietà di sola lettura parentElement dell'interfaccia [`Node`](../node/) restituisce il [`Element`](../element/) genitore del nodo DOM, o null se il nodo non ha genitore o il suo genitore non è un Element DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) La proprietà di sola lettura parentNode dell'interfaccia Node restituisce il genitore del nodo specificato nell'albero DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | La proprietà di sola lettura prefix restituisce il prefisso del pacchetto dell'elemento specificato, o null se non è specificato alcun prefisso. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) La proprietà di sola lettura previousSibling dell'interfaccia [`Node`](../node/) restituisce il nodo immediatamente precedente a quello specificato nella lista dei [`childNodes`](../node/firstchild/) del genitore, o null se il nodo specificato è il primo nella lista. |
| [getPublicId](../../com.aspose.html.dom/notation/publicid/) L'identificatore pubblico di questa notazione. Se l'identificatore pubblico non è stato specificato, è null. |
| [getSystemId](../../com.aspose.html.dom/notation/systemid/) L'identificatore di sistema di questa notazione. Se l'identificatore di sistema non è stato specificato, è null. Può essere un URI assoluto o meno. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | La proprietà textContent dell'interfaccia [`Node`](../node/) rappresenta il contenuto testuale del nodo e dei suoi discendenti. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Il metodo addEventListener() dell'interface [`EventTarget `](../eventtarget/) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Il metodo addEventListener() dell'interfaccia [EventTarget ](T:com.aspose.html.dom.EventTarget) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Il metodo addEventListener() dell'interfaccia [EventTarget ](T:com.aspose.html.dom.EventTarget) imposta una funzione che verrà chiamata ogni volta che l'evento specificato viene consegnato al target. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Il metodo appendChild() dell'interfaccia Node aggiunge un nodo alla fine dell'elenco dei figli di un nodo genitore specificato. Se il figlio fornito è un riferimento a un nodo esistente nel documento, appendChild() lo sposta dalla sua posizione attuale a quella nuova (non è necessario rimuovere il nodo dal suo nodo genitore prima di aggiungerlo a un altro nodo). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Il metodo cloneNode() dell'interfaccia Node restituisce un duplicato del nodo su cui è stato chiamato questo metodo. Il suo parametro controlla se il sottoalbero contenuto in un nodo viene anche clonato o meno. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Il metodo cloneNode() dell'interfaccia Node restituisce un duplicato del nodo su cui è stato chiamato questo metodo. Il suo parametro controlla se il sottoalbero contenuto in un nodo viene anche clonato o meno. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Esegue la distribuzione di un Event al [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) specificato, (sincronamente) invocando gli EventListener interessati nell'ordine appropriato. Le regole normali di elaborazione degli eventi (inclusa la fase di cattura e quella di bubbling opzionale) si applicano anche agli eventi distribuiti manualmente con [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset di risorse non gestite. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Il metodo hasChildNodes() dell'interfaccia Node restituisce un valore booleano che indica se il dato [`Node`](../node/) ha nodi figli o meno. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Il metodo insertBefore() dell'interfaccia Node inserisce un nodo prima di un nodo di riferimento come figlio di un nodo genitore specificato. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Il metodo isDefaultNamespace() dell'interfaccia Node accetta un URI del pacchetto come argomento. Restituisce un valore booleano che è true se il pacchetto è quello predefinito sul nodo dato e false altrimenti. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Il metodo isEqualNode() dell'interfaccia [`Node`](../node/) verifica se due nodi sono uguali. Due nodi sono uguali quando hanno lo stesso tipo, caratteristiche distintive (per gli elementi, ad esempio ID, numero di figli, ecc.), i loro attributi corrispondono, e così via. L'insieme specifico di dati che devono corrispondere varia a seconda dei tipi dei nodi. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Il metodo isSameNode() dell'interfaccia Node è un alias legacy per l'operatore di uguaglianza stretta ===. Cioè, verifica se due nodi sono gli stessi (in altre parole, se fanno riferimento allo stesso oggetto). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Il metodo lookupNamespaceURI() dell'interfaccia Node prende un prefisso come parametro e restituisce l'URI del pacchetto associato su quel nodo, se trovato (e null se non lo è). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Il metodo lookupPrefix() dell'interfaccia Node restituisce una String contenente il prefisso per un dato URI del pacchetto, se presente, e null se non lo è. Quando sono possibili più prefissi, viene restituito il primo prefisso. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Posiziona tutti i nodi [`Text`](../text/) nella profondità completa del sotto-albero sotto questo Node, inclusi i nodi attributo, in una forma "normal" in cui solo la struttura (ad esempio [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), e [`entity references`](../entityreference/)) separa i nodi [`Text`](../text/), cioè non ci sono né nodi Text adiacenti né nodi Text vuoti. Questo può essere usato per garantire che la vista DOM di un documento sia la stessa di quella che si otterrebbe salvando e ricaricando il documento, ed è utile quando operazioni (come le ricerche XPointer [XPointer]) che dipendono da una particolare struttura dell'albero del documento devono essere utilizzate. Se il parametro "normalize-characters" dell'oggetto [`DOMConfiguration`](../../com.aspose.html/configuration/) collegato al [`Node.ownerDocument`](../node/ownerdocument/) è true, questo metodo normalizzerà anche completamente i caratteri dei nodi Text. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Il metodo removeChild() dell'interfaccia Node rimuove un nodo figlio dal DOM e restituisce il nodo rimosso. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Questo metodo consente la rimozione dei listener di eventi dal target dell'evento. Se un listener viene rimosso mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere invocati dopo essere stati rimossi. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Sostituisce il nodo figlio oldChild con newChild nell'elenco dei figli e restituisce il nodo oldChild. Se newChild è un oggetto [`DocumentFragment`](../documentfragment/), oldChild viene sostituito da tutti i figli del [`DocumentFragment`](../documentfragment/), inseriti nello stesso ordine. Se newChild è già nell'albero, viene prima rimosso. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Restituisce una String che rappresenta questa istanza. |

### Vedi anche

* class [Node](../node/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
