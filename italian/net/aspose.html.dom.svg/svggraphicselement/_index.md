---
title: Class SVGGraphicsElement
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Svg.SVGGraphicsElement classe. Linterfaccia SVGGraphicsElement rappresenta gli elementi SVG il cui scopo principale è il rendering diretto della grafica in un gruppo.
type: docs
weight: 2110
url: /it/net/aspose.html.dom.svg/svggraphicselement/
---
## SVGGraphicsElement class

L'interfaccia SVGGraphicsElement rappresenta gli elementi SVG il cui scopo principale è il rendering diretto della grafica in un gruppo.

```csharp
public class SVGGraphicsElement : SVGElement, ISVGTests
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Attributes](../../aspose.html.dom/element/attributes/) { get; } | Una NamedNodeMap contenente gli attributi di questo nodo (se è un elemento) o null in caso contrario. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | L'URI di base assoluto di questo nodo o null se l'implementazione non è stata in grado di ottenere un URI assoluto. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount/) { get; } | Restituisce il numero corrente di nodi elemento che sono figli di questo elemento. 0 se questo elemento non ha nodi figli di nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Un NodeList che contiene tutti i figli di questo nodo. Se non ci sono figli, questo è un NodeList che non contiene nodi.. |
| [Children](../../aspose.html.dom/element/children/) { get; } | Restituisce gli elementi figli dell'elemento corrente. |
| [ClassList](../../aspose.html.dom/element/classlist/) { get; } | Restituisce un DOMTokenList live che contiene i token ricevuti dall'analisi dell'attributo "class". |
| [ClassName](../../aspose.html.dom.svg/svgelement/classname/) { get; } | Corrisponde all'attributo 'classe' sull'elemento dato. |
| [ClassName](../../aspose.html.dom/element/classname/) { get; set; } | L'attributo di classe dell'elemento. Questo attributo è stato rinominato a causa di conflitti con la parola chiave "class" esposta da molti linguaggi. Vedi la definizione dell'attributo di classe in HTML 4.01. |
| [FarthestViewportElement](../../aspose.html.dom.svg/svggraphicselement/farthestviewportelement/) { get; } | L'elemento 'svg' dell'antenato più lontano. Null se l'elemento corrente è l'elemento svg più esterno. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Il primo figlio di questo nodo. Se non esiste tale nodo, questo restituisce null. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | Restituisce il primo nodo dell'elemento figlio di questo elemento. null se questo elemento non ha elementi figlio. |
| [Id](../../aspose.html.dom.svg/svgelement/id/) { get; set; } | Il valore dell'attributo 'id' sull'elemento dato, o la stringa vuota se 'id' non è presente. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | Restituisce un frammento di HTML o XML che rappresenta il contenuto dell'elemento. Può essere impostato per sostituire il contenuto dell'elemento con i nodi analizzati dalla stringa data. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | L'ultimo figlio di questo nodo. Se non esiste tale nodo, questo restituisce null. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | Restituisce l'ultimo nodo dell'elemento figlio di questo elemento. null se questo elemento non ha elementi figlio. |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | Restituisce la parte locale del nome completo di questo nodo. Per i nodi di qualsiasi tipo diverso da ELEMENT_NODE e ATTRIBUTE_NODE e per i nodi creati con un metodo DOM di livello 1, come Document.createElement(), è sempre null. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | L'URI dello spazio dei nomi di questo nodo o null se non è specificato. |
| [NearestViewportElement](../../aspose.html.dom.svg/svggraphicselement/nearestviewportelement/) { get; } | L'elemento che ha stabilito la finestra corrente. Spesso, l'elemento 'svg' dell'antenato più vicino. Null se l'elemento corrente è l'elemento svg più esterno. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | Restituisce il successivo nodo dell'elemento di pari livello di questo elemento. null se questo elemento non ha nodi di pari livello che vengono dopo questo nell'albero del documento. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Il nodo immediatamente successivo a questo nodo. Se non esiste tale nodo, questo restituisce null. |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | Il nome di questo nodo, a seconda del suo tipo. |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | Un codice che rappresenta il tipo dell'oggetto sottostante. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Il valore di questo nodo, a seconda del suo tipo. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | Restituisce un frammento di HTML o XML che rappresenta l'elemento e il suo contenuto. Può essere impostato per sostituire l'elemento con i nodi analizzati dalla stringa data. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | L'oggetto Document associato a questo nodo. Questo è anche l'oggetto Document utilizzato per creare nuovi nodi. Quando questo nodo è un Documento o un DocumentType che non è ancora utilizzato con nessun Documento, questo è null. |
| [OwnerSVGElement](../../aspose.html.dom.svg/svgelement/ownersvgelement/) { get; } | L'elemento 'svg' dell'antenato più vicino. Null se l'elemento dato è l'elemento svg più esterno. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Ottiene il genitore[`Element`](../../aspose.html.dom/element/) di questo nodo. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Il padre di questo nodo. Tutti i nodi, eccetto Attr, Document, DocumentFragment, Entity e Notation possono avere un genitore. Tuttavia, se un nodo è stato appena creato e non ancora aggiunto all'albero, o se è stato rimosso dall'albero, questo è nullo. |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | Il prefisso dello spazio dei nomi di questo nodo o null se non è specificato. Quando è definito nullo, impostarlo non ha effetto |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | Restituisce il precedente nodo dell'elemento di pari livello di questo elemento. null se questo elemento non ha nodi di pari livello che precedono questo nell'albero del documento. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Il nodo immediatamente precedente a questo nodo. Se non esiste tale nodo, questo restituisce null. |
| [RequiredExtensions](../../aspose.html.dom.svg/svggraphicselement/requiredextensions/) { get; } | Corrisponde all'attributo 'requiredExtensions' sull'elemento dato. |
| [RequiredFeatures](../../aspose.html.dom.svg/svggraphicselement/requiredfeatures/) { get; } | Corrisponde all'attributo 'requiredFeatures' sull'elemento dato. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo/) { get; } | Le informazioni sul tipo associate a questo elemento. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | Restituisce shadowRoot memorizzato su questo elemento o null se è chiuso. |
| [Style](../../aspose.html.dom.svg/svgelement/style/) { get; } | Corrisponde all'attributo 'style' sull'elemento dato. Se l'agente utente non supporta lo stile con i CSS, questo attributo deve sempre avere il valore null. |
| [SystemLanguage](../../aspose.html.dom.svg/svggraphicselement/systemlanguage/) { get; } | Corrisponde all'attributo 'systemLanguage' sull'elemento dato. |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | Il nome dell'elemento. |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | Questo attributo restituisce il contenuto testuale di questo nodo e dei suoi discendenti. Quando è definito nullo, impostarlo non ha alcun effetto. Al momento dell'impostazione, tutti i possibili figli che questo nodo può avere vengono rimossi e, se la nuova stringa non è vuota o nulla, sostituita da un singolo nodo di testo contenente la stringa su cui è impostato questo attributo. |
| [Transform](../../aspose.html.dom.svg/svggraphicselement/transform/) { get; } | Corrisponde all'attributo 'transform' sull'elemento dato. |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement/) { get; } | L'elemento che ha stabilito la finestra corrente. Spesso, l'elemento 'svg' dell'antenato più vicino. Null se l'elemento dato è l'elemento svg più esterno. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Questo metodo consente la registrazione dei listener di eventi sul target dell'evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Questo metodo consente la registrazione dei listener di eventi sul target dell'evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Questo metodo consente la registrazione dei listener di eventi sul target dell'evento. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Aggiunge il nodo newChild alla fine dell'elenco dei figli di questo nodo. Se il newChild è già nell'albero, viene prima rimosso. |
| [AttachShadow](../../aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Crea radice ombra e la collega all'elemento corrente. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Restituisce un duplicato di questo nodo, ovvero funge da costruttore di copie generico per i nodi. Il nodo duplicato non ha un genitore (parentNode è nullo) e nessun dato utente. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Restituisce un duplicato di questo nodo, ovvero funge da costruttore di copie generico per i nodi. Il nodo duplicato non ha un genitore (parentNode è nullo) e nessun dato utente. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Questo metodo consente l'invio di eventi nel modello di eventi delle implementazioni. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Esegue attività definite dall'applicazione associate alla liberazione, al rilascio o al ripristino di risorse non gestite. |
| [GetAttribute](../../aspose.html.dom/element/getattribute/)(string) | Recupera un valore di attributo per nome. |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode/)(string) | Recupera un nodo attributo per nome. |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens/)(string, string) | Recupera un nodo Attr in base al nome locale e all'URI dello spazio dei nomi. |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens/)(string, string) | Recupera un valore di attributo in base al nome locale e all'URI dello spazio dei nomi. |
| [GetBBox](../../aspose.html.dom.svg/svggraphicselement/getbbox/)() | Restituisce il riquadro di delimitazione stretto nello spazio utente corrente (ovvero, dopo l'applicazione dell'attributo 'transform', se presente) sulla geometria di tutti gli elementi grafici contenuti, esclusi gli effetti di tratto, ritaglio, mascheramento e filtro). Si noti che getBBox deve restituire il riquadro di delimitazione effettivo nel momento in cui è stato chiamato il metodo, anche nel caso in cui l'elemento non sia stato ancora visualizzato. |
| [GetCTM](../../aspose.html.dom.svg/svggraphicselement/getctm/)() | Restituisce la matrice di trasformazione dalle unità utente correnti (ovvero, dopo l'applicazione dell'eventuale attributo 'transform') al sistema di coordinate del viewport per l'ElementoVista più vicino. |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | Restituisce un oggetto NodeList attivo contenente tutti gli elementi nel documento che hanno tutte le classi specificate nell'argomento. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | Restituisce una NodeList di tutti gli elementi discendenti con un dato nome di tag, nell'ordine del documento. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | Restituisce un NodeList di tutti gli elementi discendenti con un dato nome locale e URI dello spazio dei nomi nell'ordine del documento. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| [GetScreenCTM](../../aspose.html.dom.svg/svggraphicselement/getscreenctm/)() | Restituisce la matrice di trasformazione dalle unità dell'utente corrente (cioè, dopo l'applicazione dell'attributo 'transform', se presente) all'avviso dell'agente utente genitore di un "pixel". Per i dispositivi di visualizzazione, idealmente questo rappresenta un pixel dello schermo fisico. Per altri dispositivi o ambienti in cui le dimensioni fisiche dei pixel non sono note, è possibile utilizzare invece un algoritmo simile alla definizione CSS2 di "pixel". Si noti che viene restituito null se questo elemento non è collegato all'albero del documento. Questo metodo sarebbe stato chiamato più appropriatamente come getClientCTM, ma il nome getScreenCTM viene mantenuto per ragioni storiche. |
| [HasAttribute](../../aspose.html.dom/element/hasattribute/)(string) | Restituisce true quando un attributo con un determinato nome è specificato su questo elemento o ha un valore predefinito, false in caso contrario. |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens/)(string, string) | Restituisce true quando un attributo con un determinato nome locale e URI dello spazio dei nomi è specificato su questo elemento o ha un valore predefinito, false in caso contrario. |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes/)() | Restituisce se questo nodo (se è un elemento) ha attributi |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Restituisce se questo nodo ha figli. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Inserisce il nodo prima del nodo figlio esistente figlio. Se child è null, inserisci il nodo alla fine dell'elenco dei child. Se child è un oggetto DocumentFragment, tutti i suoi child vengono inseriti, nello stesso ordine, prima di child. Se il figlio è già nell'albero, viene prima rimosso. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Questo metodo verifica se il namespaceURI specificato è lo spazio dei nomi predefinito o meno. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Verifica se due nodi sono uguali. Questo metodo verifica l'uguaglianza dei nodi, non l'uguaglianza (ovvero, se i due nodi sono riferimenti allo stesso oggetto) che possono essere verificati con Node.isSameNode(). Anche tutti i nodi uguali saranno uguali, anche se il contrario potrebbe non essere vero. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Restituisce se questo nodo è lo stesso nodo di quello dato. Questo metodo fornisce un modo per determinare se due riferimenti Node restituiti dall'implementazione fanno riferimento allo stesso oggetto. Quando due riferimenti Node sono riferimenti allo stesso oggetto, anche se tramite un proxy, i riferimenti possono essere utilizzati in modo completamente intercambiabile, in modo tale che tutti gli attributi abbiano gli stessi valori e chiamare lo stesso metodo DOM su entrambi i riferimenti ha sempre esattamente lo stesso effetto. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Cerca l'URI dello spazio dei nomi associato al prefisso dato, a partire da questo nodo. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Cerca il prefisso associato all'URI del namespace dato, a partire da questo nodo. Le dichiarazioni predefinite dello spazio dei nomi vengono ignorate da questo metodo. Vedere Ricerca prefisso nello spazio dei nomi per i dettagli sull'algoritmo utilizzato da questo metodo. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Mette tutti i nodi di testo nell'intera profondità del sottoalbero sotto questo nodo, inclusi i nodi di attributo, in una forma "normale" in cui solo la struttura (ad es. elementi, commenti, istruzioni di elaborazione, sezioni CDATA e riferimenti di entità) separa il testo nodi, cioè non ci sono né nodi di testo adiacenti né nodi di testo vuoti. Questo può essere utilizzato per garantire che la vista DOM di un documento sia la stessa di se fosse stato salvato e ricaricato, ed è utile quando le operazioni (come le ricerche XPointer [XPointer]) che dipendono da una particolare struttura ad albero del documento devono essere usato. Se il parametro "normalize-characters" dell'oggetto DOMConfiguration allegato al Node.ownerDocument è vero, questo metodo normalizzerà completamente anche i caratteri dei nodi Text. |
| [QuerySelector](../../aspose.html.dom/element/queryselector/)(string) | Restituisce il primo elemento nel documento, che corrisponde a selector |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall/)(string) | Restituisce un NodeList di tutti gli elementi nel documento, che corrispondono a selector |
| [Remove](../../aspose.html.dom/element/remove/)() | Rimuove questa istanza. |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute/)(string) | Rimuove un attributo per nome. |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode/)(Attr) | Rimuove il nodo dell'attributo specificato. |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens/)(string, string) | Rimuove un attributo in base al nome locale e all'URI dello spazio dei nomi. |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Rimuove il nodo figlio indicato da oldChild dalla lista dei figli, e lo restituisce. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) viene rimosso da un[`EventTarget`](../../aspose.html.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) viene rimosso da un[`EventTarget`](../../aspose.html.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) viene rimosso da un[`EventTarget`](../../aspose.html.dom/eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Sostituisce il nodo figlio oldChild con newChild nell'elenco dei figli e restituisce il nodo oldChild. Se newChild è un oggetto DocumentFragment, oldChild viene sostituito da tutti i figli DocumentFragment, che vengono inseriti nello stesso ordine. Se il newChild è già nell'albero, viene prima rimosso. |
| [SetAttribute](../../aspose.html.dom/element/setattribute/)(string, string) | Aggiunge un nuovo attributo. Se un attributo con quel nome è già presente nell'elemento, il suo valore viene modificato in quello del valore parametro |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode/)(Attr) | Aggiunge un nuovo nodo attributo. Se un attributo con quel nome (nodeName) è già presente nell'elemento, viene sostituito da quello nuovo. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens/)(Attr) | Aggiunge un nuovo attributo. Se un attributo con quel nome locale e quell'URI dello spazio dei nomi è già presente nell'elemento, viene sostituito da quello nuovo. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens/)(string, string, string) | Aggiunge un nuovo attributo. Se un attributo con lo stesso nome locale e lo stesso URI dello spazio dei nomi è già presente sull'elemento, il suo prefisso viene modificato in modo che sia la parte del prefisso di QualifiedName e il suo valore viene modificato in Value Parameter. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute/)(string, bool) | Se il parametro isId è vero, questo metodo dichiara che l'attributo specificato è un attributo ID determinato dall'utente. |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode/)(Attr, bool) | Se il parametro isId è vero, questo metodo dichiara che l'attributo specificato è un attributo ID determinato dall'utente. |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens/)(string, string, bool) | Se il parametro isId è vero, questo metodo dichiara che l'attributo specificato è un attributo ID determinato dall'utente. |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Restituisce aString che rappresenta questa istanza. |

### Guarda anche

* class [SVGElement](../svgelement/)
* interface [ISVGTests](../isvgtests/)
* spazio dei nomi [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* assemblea [Aspose.HTML](../../)


