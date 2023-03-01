---
title: Class HTMLDocument
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.HTMLDocument classe. AnDocumento HTML è la radice della gerarchia HTML e contiene lintero contenuto. Oltre a fornire laccesso alla gerarchia fornisce anche alcuni metodi utili per accedere a determinate serie di informazioni dal documento.
type: docs
weight: 3190
url: /it/net/aspose.html/htmldocument/
---
## HTMLDocument class

An`Documento HTML` è la radice della gerarchia HTML e contiene l'intero contenuto. Oltre a fornire l'accesso alla gerarchia, fornisce anche alcuni metodi utili per accedere a determinate serie di informazioni dal documento.

Le seguenti proprietà sono state deprecate a favore delle corrispondenti per the`CORPO` element. In DOM Livello 2, il metodo`getElementById` è ereditato dal`Documento` interfaccia in cui è stato spostato.

Vedi anche il[Document object Model (DOM) Specifica HTML di livello 2](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109) .

```csharp
public class HTMLDocument : Document, IDocumentCSS
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [HTMLDocument](htmldocument/#constructor)() | Inizializza una nuova istanza di`HTMLDocument` classe. |
| [HTMLDocument](htmldocument/#constructor_1)(Configuration) | Inizializza una nuova istanza di`HTMLDocument` classe. |
| [HTMLDocument](htmldocument/#constructor_2)(RequestMessage) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_10)(string) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_4)(Url) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_3)(RequestMessage, Configuration) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_8)(Stream, string) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Il caricamento del documento inizia dalla posizione corrente nello stream. |
| [HTMLDocument](htmldocument/#constructor_6)(Stream, Url) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Il caricamento del documento inizia dalla posizione corrente nello stream. |
| [HTMLDocument](htmldocument/#constructor_11)(string, Configuration) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_14)(string, string) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_12)(string, Url) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_5)(Url, Configuration) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_9)(Stream, string, Configuration) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Il caricamento del documento inizia dalla posizione corrente nello stream. |
| [HTMLDocument](htmldocument/#constructor_7)(Stream, Url, Configuration) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Il caricamento del documento inizia dalla posizione corrente nello stream. |
| [HTMLDocument](htmldocument/#constructor_15)(string, string, Configuration) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_13)(string, Url, Configuration) | Inizializza una nuova istanza di`HTMLDocument` classe. Il costruttore funziona in modo sincrono, attende il caricamento di tutte le risorse esterne (immagini, script, ecc.). Per caricare il documento in modo asincrono utilizzare il metodo[`Navigate`](../../aspose.html.dom/document/navigate/) o i suoi sovraccarichi. Oppure puoi disabilitare il caricamento di alcune risorse esterne impostando i flag appropriati in[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Anchors](../../aspose.html/htmldocument/anchors/) { get; } | Una raccolta di tutte le ancore (`UN` ) elementi in un documento con un valore per the`nome`attributo. Per motivi di compatibilità con le versioni precedenti, il set di ancore restituito contiene solo quelle ancore create con il`nome` attributo, non quelli creati con l'attributo`id` attributo. Si noti che in [[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801) ], il `nome` attributo (vedere la sezione 4.10) non ha semantica e è presente solo per i programmi utente legacy: il`id` viene invece utilizzato l'attributo . Gli utenti dovrebbero preferire i meccanismi iteratori forniti da [[DOM Livello 2 Attraversamento](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113) ] Invece. |
| [Applets](../../aspose.html/htmldocument/applets/) { get; } | Una raccolta di tutti i file`OGGETTO` elementi che includono applet e`APPLET` elementi (deprecati) in un documento. |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | Una NamedNodeMap contenente gli attributi di questo nodo (se è un elemento) o null in caso contrario. |
| override [BaseURI](../../aspose.html.dom/document/baseuri/) { get; } | L'URI di base assoluto di questo nodo o null se l'implementazione non è stata in grado di ottenere un URI assoluto. |
| [Body](../../aspose.html/htmldocument/body/) { get; set; } | L'elemento che contiene il contenuto del documento. Nei documenti con`CORPO` contenuto, restituisce il`CORPO` elemento. Nei documenti frameset, questo restituisce il più esterno`CORNICE` elemento. |
| [CharacterSet](../../aspose.html.dom/document/characterset/) { get; } | Ottiene la codifica del documento. |
| [Charset](../../aspose.html.dom/document/charset/) { get; } | Ottiene la codifica del documento. |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount/) { get; } | Restituisce il numero corrente di nodi elemento che sono figli di questo elemento. 0 se questo elemento non ha nodi figli di nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Un NodeList che contiene tutti i figli di questo nodo. Se non ci sono figli, questo è un NodeList che non contiene nodi.. |
| [Children](../../aspose.html.dom/document/children/) { get; } | Restituisce gli elementi figli. |
| [ContentType](../../aspose.html.dom/document/contenttype/) { get; } | Ottiene il tipo di contenuto del documento. |
| [Context](../../aspose.html.dom/document/context/) { get; } | Ottiene il contesto di navigazione corrente. |
| [DefaultView](../../aspose.html.dom/document/defaultview/) { get; } | L'attributo defaultView IDL dell'interfaccia del documento, quando viene ottenuto, deve restituire l'oggetto WindowProxy del contesto di esplorazione di questo documento, se questo documento ha un contesto di esplorazione associato o null in caso contrario. |
| [Doctype](../../aspose.html.dom/document/doctype/) { get; } | La dichiarazione del tipo di documento associata a questo documento. |
| [DocumentElement](../../aspose.html.dom/document/documentelement/) { get; } | Questo è un attributo di convenienza che consente l'accesso diretto al nodo figlio che è l'elemento documento del documento. |
| [DocumentURI](../../aspose.html.dom/document/documenturi/) { get; } | La posizione del documento o null se non definito o se il documento è stato creato utilizzando DOMImplementation.createDocument. |
| [Domain](../../aspose.html/htmldocument/domain/) { get; } | Il nome di dominio del server che ha servito il documento, o `nullo` se il server non può essere identificato da un nome di dominio . |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Il primo figlio di questo nodo. Se non esiste tale nodo, questo restituisce null. |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild/) { get; } | Restituisce il primo nodo dell'elemento figlio di questo elemento. null se questo elemento non ha elementi figlio. |
| [Forms](../../aspose.html/htmldocument/forms/) { get; } | Una raccolta di tutte le forme di un documento. |
| [Images](../../aspose.html/htmldocument/images/) { get; } | Una raccolta di tutti i file`IMG` elementi in un documento. Il comportamento di è limitato a`IMG` elementi per la retrocompatibilità . Come suggerito da [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)], per includere immagini, gli autori possono utilizzare the`OGGETTO` elemento o il`IMG` elemento. Pertanto, si consiglia di non utilizzare questo attributo per trovare le immagini nel documento ma`getElementsByTagName` con HTML 4.01 o`getElementsByTagNameNS` con XHTML 1.0. |
| [Implementation](../../aspose.html.dom/document/implementation/) { get; } | L'oggetto DOMImplementation che gestisce questo documento. |
| [InputEncoding](../../aspose.html.dom/document/inputencoding/) { get; } | Ottiene la codifica del documento. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | L'ultimo figlio di questo nodo. Se non esiste tale nodo, questo restituisce null. |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild/) { get; } | Restituisce l'ultimo nodo dell'elemento figlio di questo elemento. null se questo elemento non ha elementi figlio. |
| [Links](../../aspose.html/htmldocument/links/) { get; } | Una raccolta di tutti`LA ZONA` elementi e ancoraggio ( `UN` ) elementi in un documento con un valore per `href` attributo. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Restituisce la parte locale del nome completo di questo nodo. Per i nodi di qualsiasi tipo diverso da ELEMENT_NODE e ATTRIBUTE_NODE e per i nodi creati con un metodo DOM di livello 1, come Document.createElement(), è sempre null. |
| [Location](../../aspose.html.dom/document/location/) { get; } | La posizione del documento. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | L'URI dello spazio dei nomi di questo nodo o null se non è specificato. |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling/) { get; } | Restituisce il successivo nodo dell'elemento di pari livello di questo elemento. null se questo elemento non ha nodi di pari livello che vengono dopo questo nell'albero del documento. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Il nodo immediatamente successivo a questo nodo. Se non esiste tale nodo, questo restituisce null. |
| override [NodeName](../../aspose.html.dom/document/nodename/) { get; } | Il nome di questo nodo, a seconda del suo tipo. |
| override [NodeType](../../aspose.html.dom/document/nodetype/) { get; } | Un codice che rappresenta il tipo dell'oggetto sottostante. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Il valore di questo nodo, a seconda del suo tipo. |
| [Origin](../../aspose.html.dom/document/origin/) { get; } | Ottiene l'origine del documento. |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument/) { get; } | Ottiene il documento proprietario. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Ottiene il genitore[`Element`](../../aspose.html.dom/element/) di questo nodo. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Il padre di questo nodo. Tutti i nodi, eccetto Attr, Document, DocumentFragment, Entity e Notation possono avere un genitore. Tuttavia, se un nodo è stato appena creato e non ancora aggiunto all'albero, o se è stato rimosso dall'albero, questo è nullo. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | Il prefisso dello spazio dei nomi di questo nodo o null se non è specificato. Quando è definito nullo, impostarlo non ha effetto |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling/) { get; } | Restituisce il precedente nodo dell'elemento di pari livello di questo elemento. null se questo elemento non ha nodi di pari livello che precedono questo nell'albero del documento. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Il nodo immediatamente precedente a questo nodo. Se non esiste tale nodo, questo restituisce null. |
| [ReadyState](../../aspose.html.dom/document/readystate/) { get; } | Restituisce la disponibilità del documento. Il "caricamento" durante il caricamento del documento, "interattivo" una volta terminata l'analisi ma ancora il caricamento delle risorse secondarie e "completo" una volta caricato. |
| [Referrer](../../aspose.html/htmldocument/referrer/) { get; } | Restituisce l'URI [[RFC 2396 dell'IETF](http://www.ietf.org/rfc/rfc2396.txt) della pagina collegata a questa pagina. Il valore è una stringa vuota se l'utente è passato direttamente alla pagina (non tramite un collegamento, ma, ad esempio, tramite un segnalibro). |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking/) { get; set; } | Un attributo che specifica se il controllo degli errori è applicato o meno. Quando è impostata su false, l'implementazione è libera di non testare ogni possibile caso di errore normalmente definito sulle operazioni DOM e di non generare alcuna DOMException sulle operazioni DOM o di segnalare errori durante l'utilizzo di Document.normalizeDocument(). In caso di errore, il comportamento è indefinito. Questo attributo è true per impostazione predefinita. |
| [StyleSheets](../../aspose.html.dom/document/stylesheets/) { get; } | Un elenco contenente tutti i fogli di stile esplicitamente collegati o incorporati in un documento. Per i documenti HTML, questo include i fogli di stile esterni, inclusi tramite l'elemento HTML LINK, e gli elementi STYLE incorporati. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent/) { get; set; } | Questo attributo restituisce il contenuto testuale di questo nodo e dei suoi discendenti. Quando è definito nullo, impostarlo non ha alcun effetto. Al momento dell'impostazione, tutti i possibili figli che questo nodo può avere vengono rimossi e, se la nuova stringa non è vuota o nulla, sostituita da un singolo nodo di testo contenente la stringa su cui è impostato questo attributo. |
| [Title](../../aspose.html/htmldocument/title/) { get; set; } | Il titolo di un documento come specificato dal`TITOLO` elemento nell'intestazione del documento. |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone/) { get; set; } | Un attributo che specifica, come parte della dichiarazione XML, se questo documento è autonomo. Questo è falso quando non specificato. |
| [XmlVersion](../../aspose.html.dom/document/xmlversion/) { get; set; } | Un attributo che specifica, come parte della dichiarazione XML, il numero di versione di questo documento. Se non c'è alcuna dichiarazione e se questo documento supporta la funzione "XML", il valore è "1.0". Se questo documento non supporta la funzionalità "XML", il valore è sempre null. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Questo metodo consente la registrazione dei listener di eventi sul target dell'evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Questo metodo consente la registrazione dei listener di eventi sul target dell'evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Questo metodo consente la registrazione dei listener di eventi sul target dell'evento. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Aggiunge il nodo newChild alla fine dell'elenco dei figli di questo nodo. Se il newChild è già nell'albero, viene prima rimosso. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Restituisce un duplicato di questo nodo, ovvero funge da costruttore di copie generico per i nodi. Il nodo duplicato non ha un genitore (parentNode è nullo) e nessun dato utente. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Restituisce un duplicato di questo nodo, ovvero funge da costruttore di copie generico per i nodi. Il nodo duplicato non ha un genitore (parentNode è nullo) e nessun dato utente. |
| [CreateAttribute](../../aspose.html.dom/document/createattribute/)(string) | Crea un Attr con il nome dato. |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens/)(string, string) | Crea un attributo del nome completo e dell'URI dello spazio dei nomi forniti. |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection/)(string) | Crea un nodo CDATASection il cui valore è la stringa specificata. |
| [CreateComment](../../aspose.html.dom/document/createcomment/)(string) | Crea un nodo Comment data la stringa specificata. |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment/)() | Crea un oggetto DocumentFragment vuoto. |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype/)(string, string, string, string) | Crea un nodo DocumentType. |
| [CreateElement](../../aspose.html.dom/document/createelement/)(string) | Crea un elemento del tipo specificato. Si noti che l'istanza restituita implementa l'interfaccia Element, quindi gli attributi possono essere specificati direttamente sull'oggetto restituito. |
| [CreateElementNS](../../aspose.html.dom/document/createelementns/)(string, string) | Crea un elemento del nome completo e dell'URI dello spazio dei nomi forniti. |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference/)(string) | Crea un oggetto EntityReference. Inoltre, se l'entità referenziata è nota, l'elenco figlio del nodo EntityReference viene reso uguale a quello del nodo Entity corrispondente. |
| [CreateEvent](../../aspose.html.dom/document/createevent/)(string) | Crea un file[`Event`](../../aspose.html.dom.events/event/) di un tipo supportato dall'implementazione. |
| [CreateExpression](../../aspose.html.dom/document/createexpression/)(string, IXPathNSResolver) | Crea un'espressione XPath analizzata con spazi dei nomi risolti. Questo è utile quando un'espressione verrà riutilizzata in un'applicazione poiché rende possibile compilare la stringa dell'espressione in un formato interno più efficiente e pre-risolvere tutti i prefissi dello spazio dei nomi che ricorrono all'interno dell'espressione. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node) | Crea un nuovo NodeIterator sulla sottostruttura radicata nel nodo specificato. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long) | Crea un nuovo NodeIterator sulla sottostruttura radicata nel nodo specificato. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Crea un nuovo NodeIterator sulla sottostruttura radicata nel nodo specificato. |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver/)(Node) | Adatta qualsiasi nodo DOM per risolvere gli spazi dei nomi in modo che un'espressione XPath possa essere facilmente valutata rispetto al contesto del nodo in cui è apparsa all'interno del documento. Questo adattatore funziona come il metodo DOM Level 3`lookupNamespaceURI` sui nodi nel risolvere il namespaceURI da un dato prefisso utilizzando le informazioni correnti disponibili nella gerarchia del nodo al momento viene chiamato lookupNamespaceURI, risolvendo anche correttamente il prefisso xml implicito. |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction/)(string, string) | Crea un nodo ProcessingInstruction con il nome e le stringhe di dati specificati. |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode/)(string) | Crea un nodo di testo data la stringa specificata. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node) | Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long) | Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Questo metodo consente l'invio di eventi nel modello di eventi delle implementazioni. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Esegue attività definite dall'applicazione associate alla liberazione, al rilascio o al ripristino di risorse non gestite. |
| [Evaluate](../../aspose.html.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Valuta una stringa di espressione XPath e, se possibile, restituisce un risultato del tipo specificato. |
| [GetElementById](../../aspose.html.dom/document/getelementbyid/)(string) | Restituisce l'elemento che ha un attributo ID con il valore specificato. Se tale elemento non esiste, questo restituisce null. Se più di un elemento ha un attributo ID con quel valore, ciò che viene restituito è indefinito. |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname/)(string) | Restituisce un oggetto NodeList attivo contenente tutti gli elementi nel documento che hanno tutte le classi specificate nell'argomento. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname/)(string) | Restituisce una NodeList di tutti gli elementi in ordine di documento con un dato nome di tag e sono contenuti nel documento. |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens/)(string, string) | Restituisce un NodeList di tutti gli elementi con un dato nome locale e URI dello spazio dei nomi nell'ordine del documento. |
| [GetOverrideStyle](../../aspose.html/htmldocument/getoverridestyle/)(Element, string) | Questo metodo viene utilizzato per recuperare la dichiarazione di stile override per un elemento specificato e uno pseudo-elemento specificato. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | Restituisce se questo nodo (se è un elemento) ha attributi |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Restituisce se questo nodo ha figli. |
| [ImportNode](../../aspose.html.dom/document/importnode/)(Node, bool) | Importa un nodo da un altro documento in questo documento, senza alterare o rimuovere il nodo sorgente dal documento originale; questo metodo crea una nuova copia del nodo sorgente. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Inserisce il nodo prima del nodo figlio esistente figlio. Se child è null, inserisci il nodo alla fine dell'elenco dei child. Se child è un oggetto DocumentFragment, tutti i suoi child vengono inseriti, nello stesso ordine, prima di child. Se il figlio è già nell'albero, viene prima rimosso. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Questo metodo verifica se il namespaceURI specificato è lo spazio dei nomi predefinito o meno. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Verifica se due nodi sono uguali. Questo metodo verifica l'uguaglianza dei nodi, non l'uguaglianza (ovvero, se i due nodi sono riferimenti allo stesso oggetto) che possono essere verificati con Node.isSameNode(). Anche tutti i nodi uguali saranno uguali, anche se il contrario potrebbe non essere vero. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Restituisce se questo nodo è lo stesso nodo di quello dato. Questo metodo fornisce un modo per determinare se due riferimenti Node restituiti dall'implementazione fanno riferimento allo stesso oggetto. Quando due riferimenti Node sono riferimenti allo stesso oggetto, anche se tramite un proxy, i riferimenti possono essere utilizzati in modo completamente intercambiabile, in modo tale che tutti gli attributi abbiano gli stessi valori e chiamare lo stesso metodo DOM su entrambi i riferimenti ha sempre esattamente lo stesso effetto. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Cerca l'URI dello spazio dei nomi associato al prefisso dato, a partire da questo nodo. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Cerca il prefisso associato all'URI del namespace dato, a partire da questo nodo. Le dichiarazioni predefinite dello spazio dei nomi vengono ignorate da questo metodo. Vedere Ricerca prefisso nello spazio dei nomi per i dettagli sull'algoritmo utilizzato da questo metodo. |
| [Navigate](../../aspose.html.dom/document/navigate/)(RequestMessage) | Carica il documento in base all'oggetto di richiesta specificato, sostituendo il contenuto precedente. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string) | Carica il documento all'URL (Uniform Resource Locator) specificato nell'istanza corrente, sostituendo il contenuto precedente. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Url) | Carica il documento all'URL (Uniform Resource Locator) specificato nell'istanza corrente, sostituendo il contenuto precedente. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, string) | Carica il documento dal contenuto specificato e utilizza baseUri per risolvere le risorse relative, sostituendo il contenuto precedente. Il caricamento del documento inizia dalla posizione corrente nello stream. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, Url) | Carica il documento dal contenuto specificato e utilizza baseUri per risolvere le risorse relative, sostituendo il contenuto precedente. Il caricamento del documento inizia dalla posizione corrente nello stream. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, string) | Carica il documento dal contenuto specificato e utilizza baseUri per risolvere le relative risorse, sostituendo il contenuto precedente. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, Url) | Carica il documento dal contenuto specificato e utilizza baseUri per risolvere le relative risorse, sostituendo il contenuto precedente. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Mette tutti i nodi di testo nell'intera profondità del sottoalbero sotto questo nodo, inclusi i nodi di attributo, in una forma "normale" in cui solo la struttura (ad es. elementi, commenti, istruzioni di elaborazione, sezioni CDATA e riferimenti di entità) separa il testo nodi, cioè non ci sono né nodi di testo adiacenti né nodi di testo vuoti. Questo può essere utilizzato per garantire che la vista DOM di un documento sia la stessa di se fosse stato salvato e ricaricato, ed è utile quando le operazioni (come le ricerche XPointer [XPointer]) che dipendono da una particolare struttura ad albero del documento devono essere usato. Se il parametro "normalize-characters" dell'oggetto DOMConfiguration allegato al Node.ownerDocument è vero, questo metodo normalizzerà completamente anche i caratteri dei nodi Text. |
| [QuerySelector](../../aspose.html.dom/document/queryselector/)(string) | Restituisce il primo elemento nel documento, che corrisponde a selector |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall/)(string) | Restituisce un NodeList di tutti gli elementi nel documento, che corrispondono a selector |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Rimuove il nodo figlio indicato da oldChild dalla lista dei figli, e lo restituisce. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) viene rimosso da un[`EventTarget`](../../aspose.html.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) viene rimosso da un[`EventTarget`](../../aspose.html.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) viene rimosso da un[`EventTarget`](../../aspose.html.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi. |
| override [RenderTo](../../aspose.html/htmldocument/renderto/)(IDevice) | Questo metodo viene utilizzato per stampare il contenuto del documento corrente sul dispositivo specificato. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Sostituisce il nodo figlio oldChild con newChild nell'elenco dei figli e restituisce il nodo oldChild. Se newChild è un oggetto DocumentFragment, oldChild viene sostituito da tutti i figli DocumentFragment, che vengono inseriti nello stesso ordine. Se il newChild è già nell'albero, viene prima rimosso. |
| [Save](../../aspose.html/htmldocument/save/#save)(IOutputStorage) | Salva il contenuto del documento e le risorse nell'archivio di output. |
| [Save](../../aspose.html/htmldocument/save/#save_10)(string) | Salva il documento nel file locale specificato da`sentiero` Tutte le risorse utilizzate in questo documento verranno salvate in nella cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_5)(Url) | Salva il documento nel file locale specificato da`URL` Tutte le risorse utilizzate in questo documento verranno salvate in nella cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_1)(IOutputStorage, HTMLSaveFormat) | Salva il contenuto del documento e le risorse nell'archivio di output. |
| [Save](../../aspose.html/htmldocument/save/#save_2)(IOutputStorage, HTMLSaveOptions) | Salva il contenuto del documento e le risorse nell'archivio di output. |
| [Save](../../aspose.html/htmldocument/save/#save_3)(IOutputStorage, MarkdownSaveOptions) | Salva il contenuto del documento e le risorse nell'archivio di output. |
| [Save](../../aspose.html/htmldocument/save/#save_4)(IOutputStorage, MHTMLSaveOptions) | Salva il contenuto del documento e le risorse nell'archivio di output. |
| [Save](../../aspose.html/htmldocument/save/#save_11)(string, HTMLSaveFormat) | Salva il documento nel file locale specificato da`sentiero` Tutte le risorse utilizzate in questo documento verranno salvate in nella cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_12)(string, HTMLSaveOptions) | Salva il documento nel file locale specificato da`sentiero` Tutte le risorse utilizzate in questo documento verranno salvate in nella cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_13)(string, MarkdownSaveOptions) | Salva il documento nel file locale specificato da`sentiero` Tutte le risorse utilizzate in questo documento verranno salvate in nella cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_14)(string, MHTMLSaveOptions) | Salva il documento nel file locale specificato da`sentiero` Tutte le risorse utilizzate in questo documento verranno salvate in nella cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_6)(Url, HTMLSaveFormat) | Salva il documento nel file locale specificato da`URL` Tutte le risorse utilizzate in questo documento verranno salvate in nella cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_7)(Url, HTMLSaveOptions) | Salva il documento nel file locale specificato da`URL` Tutte le risorse utilizzate in questo documento verranno salvate in nella cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_8)(Url, MarkdownSaveOptions) | Salva il documento nel file locale specificato da`URL` Tutte le risorse utilizzate in questo documento verranno salvate in nella cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_9)(Url, MHTMLSaveOptions) | Salva il documento nel file locale specificato da`URL` Tutte le risorse utilizzate in questo documento verranno salvate in nella cartella adiacente, il cui nome sarà costruito come: output_file_name + "_files". |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Restituisce aString che rappresenta questa istanza. |
| [Write](../../aspose.html.dom/document/write/)(params string[]) | Scrive una stringa di testo in un flusso di documenti aperto da open(). Si noti che la funzione produrrà un documento che non è necessariamente guidato da un DTD e pertanto potrebbe produrre un risultato non valido nel contesto del documento. |
| [WriteLn](../../aspose.html.dom/document/writeln/)(params string[]) | Scrive una stringa di testo seguita da un carattere di nuova riga in un flusso document aperto da open(). Si noti che la funzione produrrà un documento che non è necessariamente guidato da un DTD e pertanto potrebbe produrre un risultato non valido nel contesto del document |

## Eventi

| Nome | Descrizione |
| --- | --- |
| event [OnAbort](../../aspose.html.dom/document/onabort/) | Ottiene o imposta il gestore eventi per l'evento OnAbort. |
| event [OnBlur](../../aspose.html.dom/document/onblur/) | Ottiene o imposta il gestore eventi per l'evento OnBlur. |
| event [OnCancel](../../aspose.html.dom/document/oncancel/) | Ottiene o imposta il gestore eventi per l'evento OnCancel. |
| event [OnCanplay](../../aspose.html.dom/document/oncanplay/) | Ottiene o imposta il gestore eventi per l'evento OnCanplay. |
| event [OnCanPlayThrough](../../aspose.html.dom/document/oncanplaythrough/) | Ottiene o imposta il gestore eventi per l'evento OnCanPlayThrough. |
| event [OnChange](../../aspose.html.dom/document/onchange/) | Ottiene o imposta il gestore eventi per l'evento OnChange. |
| event [OnClick](../../aspose.html.dom/document/onclick/) | Ottiene o imposta il gestore eventi per l'evento OnClick. |
| event [OnCueChange](../../aspose.html.dom/document/oncuechange/) | Ottiene o imposta il gestore eventi per l'evento OnCueChange. |
| event [OnDblClick](../../aspose.html.dom/document/ondblclick/) | Ottiene o imposta il gestore eventi per l'evento OnDblClick. |
| event [OnDurationChange](../../aspose.html.dom/document/ondurationchange/) | Ottiene o imposta il gestore eventi per l'evento OnDurationChange. |
| event [OnEmptied](../../aspose.html.dom/document/onemptied/) | Ottiene o imposta il gestore eventi per l'evento OnEmptied. |
| event [OnEnded](../../aspose.html.dom/document/onended/) | Ottiene o imposta il gestore eventi per l'evento OnEnded. |
| event [OnError](../../aspose.html.dom/document/onerror/) | Ottiene o imposta il gestore eventi per l'evento OnError. |
| event [OnFocus](../../aspose.html.dom/document/onfocus/) | Ottiene o imposta il gestore eventi per l'evento OnFocus. |
| event [OnInput](../../aspose.html.dom/document/oninput/) | Ottiene o imposta il gestore eventi per l'evento OnInput. |
| event [OnInvalid](../../aspose.html.dom/document/oninvalid/) | Ottiene o imposta il gestore eventi per l'evento OnInvalid. |
| event [OnKeyDown](../../aspose.html.dom/document/onkeydown/) | Ottiene o imposta il gestore eventi per l'evento OnKeyDown. |
| event [OnKeyPress](../../aspose.html.dom/document/onkeypress/) | Ottiene o imposta il gestore eventi per l'evento OnKeyPress. |
| event [OnKeyUp](../../aspose.html.dom/document/onkeyup/) | Ottiene o imposta il gestore eventi per l'evento OnKeyUp. |
| event [OnLoad](../../aspose.html.dom/document/onload/) | Ottiene o imposta il gestore eventi per l'evento OnLoad. |
| event [OnLoadedData](../../aspose.html.dom/document/onloadeddata/) | Ottiene o imposta il gestore eventi per l'evento OnLoadedData. |
| event [OnLoadedMetadata](../../aspose.html.dom/document/onloadedmetadata/) | Ottiene o imposta il gestore eventi per l'evento OnLoadedMetadata. |
| event [OnLoadStart](../../aspose.html.dom/document/onloadstart/) | Ottiene o imposta il gestore eventi per l'evento OnLoadStart. |
| event [OnMouseDown](../../aspose.html.dom/document/onmousedown/) | Ottiene o imposta il gestore eventi per l'evento OnMouseDown. |
| event [OnMouseEnter](../../aspose.html.dom/document/onmouseenter/) | Ottiene o imposta il gestore eventi per l'evento OnMouseEnter. |
| event [OnMouseLeave](../../aspose.html.dom/document/onmouseleave/) | Ottiene o imposta il gestore eventi per l'evento OnMouseLeave. |
| event [OnMouseMove](../../aspose.html.dom/document/onmousemove/) | Ottiene o imposta il gestore eventi per l'evento OnMouseMove. |
| event [OnMouseOut](../../aspose.html.dom/document/onmouseout/) | Ottiene o imposta il gestore eventi per l'evento OnMouseOut. |
| event [OnMouseOver](../../aspose.html.dom/document/onmouseover/) | Ottiene o imposta il gestore eventi per l'evento OnMouseOver. |
| event [OnMouseUp](../../aspose.html.dom/document/onmouseup/) | Ottiene o imposta il gestore eventi per l'evento OnMouseUp. |
| event [OnMouseWheel](../../aspose.html.dom/document/onmousewheel/) | Ottiene o imposta il gestore eventi per l'evento OnMouseWheel. |
| event [OnPause](../../aspose.html.dom/document/onpause/) | Ottiene o imposta il gestore eventi per l'evento OnPause. |
| event [OnPlay](../../aspose.html.dom/document/onplay/) | Ottiene o imposta il gestore eventi per l'evento OnPlay. |
| event [OnPlaying](../../aspose.html.dom/document/onplaying/) | Ottiene o imposta il gestore eventi per l'evento OnPlaying. |
| event [OnProgress](../../aspose.html.dom/document/onprogress/) | Ottiene o imposta il gestore eventi per l'evento OnProgress. |
| event [OnRateChange](../../aspose.html.dom/document/onratechange/) | Ottiene o imposta il gestore eventi per l'evento OnRateChange. |
| event [OnReadyStateChange](../../aspose.html.dom/document/onreadystatechange/) | Ottiene o imposta il gestore eventi per l'evento OnReadyStateChange. |
| event [OnReset](../../aspose.html.dom/document/onreset/) | Ottiene o imposta il gestore eventi per l'evento OnReset. |
| event [OnResize](../../aspose.html.dom/document/onresize/) | Ottiene o imposta il gestore eventi per l'evento OnResize. |
| event [OnScroll](../../aspose.html.dom/document/onscroll/) | Ottiene o imposta il gestore eventi per l'evento OnScroll. |
| event [OnSeeked](../../aspose.html.dom/document/onseeked/) | Ottiene o imposta il gestore eventi per l'evento OnSeeked. |
| event [OnSeeking](../../aspose.html.dom/document/onseeking/) | Ottiene o imposta il gestore eventi per l'evento OnSeeking. |
| event [OnSelect](../../aspose.html.dom/document/onselect/) | Ottiene o imposta il gestore eventi per l'evento OnSelect. |
| event [OnShow](../../aspose.html.dom/document/onshow/) | Ottiene o imposta il gestore eventi per l'evento OnShow. |
| event [OnStalled](../../aspose.html.dom/document/onstalled/) | Ottiene o imposta il gestore eventi per l'evento OnStalled. |
| event [OnSubmit](../../aspose.html.dom/document/onsubmit/) | Ottiene o imposta il gestore eventi per l'evento OnSubmit. |
| event [OnSuspend](../../aspose.html.dom/document/onsuspend/) | Ottiene o imposta il gestore eventi per l'evento OnSuspend. |
| event [OnTimeUpdate](../../aspose.html.dom/document/ontimeupdate/) | Ottiene o imposta il gestore eventi per l'evento OnTimeUpdate. |
| event [OnToggle](../../aspose.html.dom/document/ontoggle/) | Ottiene o imposta il gestore eventi per l'evento OnToggle. |
| event [OnVolumeChange](../../aspose.html.dom/document/onvolumechange/) | Ottiene o imposta il gestore eventi per l'evento OnVolumeChange. |
| event [OnWaiting](../../aspose.html.dom/document/onwaiting/) | Ottiene o imposta il gestore eventi per l'evento OnWaiting. |

### Guarda anche

* class [Document](../../aspose.html.dom/document/)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss/)
* spazio dei nomi [Aspose.Html](../../aspose.html/)
* assemblea [Aspose.HTML](../../)


