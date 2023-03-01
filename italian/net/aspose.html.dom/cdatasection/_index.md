---
title: Class CDATASection
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.CDATASection classe. Le sezioni CDATA vengono utilizzate per eseguire lescape di blocchi di testo contenenti caratteri che altrimenti verrebbero considerati markup.
type: docs
weight: 200
url: /it/net/aspose.html.dom/cdatasection/
---
## CDATASection class

Le sezioni CDATA vengono utilizzate per eseguire l'escape di blocchi di testo contenenti caratteri che altrimenti verrebbero considerati markup.

```csharp
public class CDATASection : Text
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | Una NamedNodeMap contenente gli attributi di questo nodo (se è un elemento) o null in caso contrario. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | L'URI di base assoluto di questo nodo o null se l'implementazione non è stata in grado di ottenere un URI assoluto. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Un NodeList che contiene tutti i figli di questo nodo. Se non ci sono figli, questo è un NodeList che non contiene nodi.. |
| virtual [Data](../../aspose.html.dom/characterdata/data/) { get; set; } | I dati carattere del nodo che implementa questa interfaccia. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Il primo figlio di questo nodo. Se non esiste tale nodo, questo restituisce null. |
| [IsElementContentWhitespace](../../aspose.html.dom/text/iselementcontentwhitespace/) { get; } | Restituisce se questo nodo di testo contiene spazi bianchi nel contenuto dell'elemento, spesso impropriamente chiamati "spazi bianchi ignorabili". |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | L'ultimo figlio di questo nodo. Se non esiste tale nodo, questo restituisce null. |
| [Length](../../aspose.html.dom/characterdata/length/) { get; } | Il numero di unità a 16 bit disponibili tramite i dati e il metodo substringData riportato di seguito. Questo può avere il valore zero, cioè i nodi CharacterData possono essere vuoti. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Restituisce la parte locale del nome completo di questo nodo. Per i nodi di qualsiasi tipo diverso da ELEMENT_NODE e ATTRIBUTE_NODE e per i nodi creati con un metodo DOM di livello 1, come Document.createElement(), è sempre null. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | L'URI dello spazio dei nomi di questo nodo o null se non è specificato. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Il nodo immediatamente successivo a questo nodo. Se non esiste tale nodo, questo restituisce null. |
| override [NodeName](../../aspose.html.dom/cdatasection/nodename/) { get; } | Il nome di questo nodo, a seconda del suo tipo. |
| override [NodeType](../../aspose.html.dom/cdatasection/nodetype/) { get; } | Un codice che rappresenta il tipo dell'oggetto sottostante. |
| override [NodeValue](../../aspose.html.dom/text/nodevalue/) { get; set; } | Il valore di questo nodo, a seconda del suo tipo. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | L'oggetto Document associato a questo nodo. Questo è anche l'oggetto Document utilizzato per creare nuovi nodi. Quando questo nodo è un Documento o un DocumentType che non è ancora utilizzato con nessun Documento, questo è null. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Ottiene il genitore[`Element`](../element/) di questo nodo. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Il padre di questo nodo. Tutti i nodi, eccetto Attr, Document, DocumentFragment, Entity e Notation possono avere un genitore. Tuttavia, se un nodo è stato appena creato e non ancora aggiunto all'albero, o se è stato rimosso dall'albero, questo è nullo. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | Il prefisso dello spazio dei nomi di questo nodo o null se non è specificato. Quando è definito nullo, impostarlo non ha effetto |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Il nodo immediatamente precedente a questo nodo. Se non esiste tale nodo, questo restituisce null. |
| override [TextContent](../../aspose.html.dom/text/textcontent/) { get; set; } | Questo attributo restituisce il contenuto testuale di questo nodo e dei suoi discendenti. Quando è definito nullo, impostarlo non ha alcun effetto. Al momento dell'impostazione, tutti i possibili figli che questo nodo può avere vengono rimossi e, se la nuova stringa non è vuota o nulla, sostituita da un singolo nodo di testo contenente la stringa su cui è impostato questo attributo. |
| [WholeText](../../aspose.html.dom/text/wholetext/) { get; } | Restituisce tutto il testo dei nodi di testo logicamente adiacenti a questo nodo, concatenati nell'ordine del documento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Questo metodo consente la registrazione dei listener di eventi sul target dell'evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Questo metodo consente la registrazione dei listener di eventi sul target dell'evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Questo metodo consente la registrazione dei listener di eventi sul target dell'evento. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Aggiunge il nodo newChild alla fine dell'elenco dei figli di questo nodo. Se il newChild è già nell'albero, viene prima rimosso. |
| virtual [AppendData](../../aspose.html.dom/characterdata/appenddata/)(string) | Aggiungi la stringa alla fine dei dati carattere del nodo. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Restituisce un duplicato di questo nodo, ovvero funge da costruttore di copie generico per i nodi. Il nodo duplicato non ha un genitore (parentNode è nullo) e nessun dato utente. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Restituisce un duplicato di questo nodo, ovvero funge da costruttore di copie generico per i nodi. Il nodo duplicato non ha un genitore (parentNode è nullo) e nessun dato utente. |
| virtual [DeleteData](../../aspose.html.dom/characterdata/deletedata/)(int, int) | Rimuove un intervallo di unità a 16 bit dal nodo. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Questo metodo consente l'invio di eventi nel modello di eventi delle implementazioni. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Esegue attività definite dall'applicazione associate alla liberazione, al rilascio o al ripristino di risorse non gestite. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | Restituisce se questo nodo (se è un elemento) ha attributi |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Restituisce se questo nodo ha figli. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Inserisce il nodo prima del nodo figlio esistente figlio. Se child è null, inserisci il nodo alla fine dell'elenco dei child. Se child è un oggetto DocumentFragment, tutti i suoi child vengono inseriti, nello stesso ordine, prima di child. Se il figlio è già nell'albero, viene prima rimosso. |
| virtual [InsertData](../../aspose.html.dom/characterdata/insertdata/)(int, string) | Inserisce una stringa all'offset dell'unità a 16 bit specificato. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Questo metodo verifica se il namespaceURI specificato è lo spazio dei nomi predefinito o meno. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Verifica se due nodi sono uguali. Questo metodo verifica l'uguaglianza dei nodi, non l'uguaglianza (ovvero, se i due nodi sono riferimenti allo stesso oggetto) che possono essere verificati con Node.isSameNode(). Anche tutti i nodi uguali saranno uguali, anche se il contrario potrebbe non essere vero. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Restituisce se questo nodo è lo stesso nodo di quello dato. Questo metodo fornisce un modo per determinare se due riferimenti Node restituiti dall'implementazione fanno riferimento allo stesso oggetto. Quando due riferimenti Node sono riferimenti allo stesso oggetto, anche se tramite un proxy, i riferimenti possono essere utilizzati in modo completamente intercambiabile, in modo tale che tutti gli attributi abbiano gli stessi valori e chiamare lo stesso metodo DOM su entrambi i riferimenti ha sempre esattamente lo stesso effetto. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Cerca l'URI dello spazio dei nomi associato al prefisso dato, a partire da questo nodo. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Cerca il prefisso associato all'URI del namespace dato, a partire da questo nodo. Le dichiarazioni predefinite dello spazio dei nomi vengono ignorate da questo metodo. Vedere Ricerca prefisso nello spazio dei nomi per i dettagli sull'algoritmo utilizzato da questo metodo. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Mette tutti i nodi di testo nell'intera profondità del sottoalbero sotto questo nodo, inclusi i nodi di attributo, in una forma "normale" in cui solo la struttura (ad es. elementi, commenti, istruzioni di elaborazione, sezioni CDATA e riferimenti di entità) separa il testo nodi, cioè non ci sono né nodi di testo adiacenti né nodi di testo vuoti. Questo può essere utilizzato per garantire che la vista DOM di un documento sia la stessa di se fosse stato salvato e ricaricato, ed è utile quando le operazioni (come le ricerche XPointer [XPointer]) che dipendono da una particolare struttura ad albero del documento devono essere usato. Se il parametro "normalize-characters" dell'oggetto DOMConfiguration allegato al Node.ownerDocument è vero, questo metodo normalizzerà completamente anche i caratteri dei nodi Text. |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Rimuove il nodo figlio indicato da oldChild dalla lista dei figli, e lo restituisce. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) viene rimosso da un[`EventTarget`](../eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) viene rimosso da un[`EventTarget`](../eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Questo metodo consente la rimozione dei listener di eventi dalla destinazione dell'evento. Se un[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) viene rimosso da un[`EventTarget`](../eventtarget/) mentre sta elaborando un evento, non verrà attivato dalle azioni correnti. I listener di eventi non possono mai essere richiamati dopo essere stati rimossi. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Sostituisce il nodo figlio oldChild con newChild nell'elenco dei figli e restituisce il nodo oldChild. Se newChild è un oggetto DocumentFragment, oldChild viene sostituito da tutti i figli DocumentFragment, che vengono inseriti nello stesso ordine. Se il newChild è già nell'albero, viene prima rimosso. |
| virtual [ReplaceData](../../aspose.html.dom/characterdata/replacedata/)(int, int, string) | Sostituisce i caratteri a partire dall'offset dell'unità a 16 bit specificato con la stringa specificata. |
| [ReplaceWholeText](../../aspose.html.dom/text/replacewholetext/)(string) | Sostituisce il testo del nodo corrente e tutti i nodi di testo logicamente adiacenti con il testo specificato. Tutti i nodi di testo logicamente adiacenti vengono rimossi, compreso il nodo corrente, a meno che non fosse il destinatario del testo sostitutivo. |
| [SplitText](../../aspose.html.dom/text/splittext/)(int) | Spezza questo nodo in due nodi all'offset specificato, mantenendo entrambi nell'albero come fratelli. |
| virtual [SubstringData](../../aspose.html.dom/characterdata/substringdata/)(int, int) | Estrae un intervallo di dati dal nodo. |
| override [ToString](../../aspose.html.dom/characterdata/tostring/)() | Restituisce aString che rappresenta questa istanza. |

### Guarda anche

* class [Text](../text/)
* spazio dei nomi [Aspose.Html.Dom](../../aspose.html.dom/)
* assemblea [Aspose.HTML](../../)


