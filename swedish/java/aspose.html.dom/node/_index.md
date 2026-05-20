---
title: "Node klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.Node klass. Node‑gränssnittet är den primära datatypen för hela Document Object Model. Det representerar en enskild nod i dokumentträdet. Även om alla objekt som implementerar Node‑gränssnittet exponerar metoder för att hantera barn, har inte alla objekt som implementerar Node‑gränssnittet barn. Till exempel kan Text‑noder sakna barn och att lägga till barn till sådana noder resulterar i att ett DOMException kastas."
type: docs

url: /sv/java/com.aspose.html.dom/node/
---
## Node class

The Node‑gränssnittet är den primära datatypen för hela Document Object Model. Det representerar en enskild nod i dokumentträdet. Medan alla objekt som implementerar Node‑gränssnittet exponerar metoder för att hantera barn, har inte alla objekt som implementerar Node‑gränssnittet barn. Till exempel kan [`Text`](../text/) noder sakna barn, och att lägga till barn till sådana noder resulterar i att ett [`DOMException`](../domexception/) undantag kastas.

Attributen [`nodeName`](./nodename/), [`nodeValue`](./nodevalue/) och attribut inkluderas som en mekanism för att få åtkomst till nodinformation utan att kasta ner till det specifika härledda gränssnittet. I fall där det inte finns någon uppenbar mappning av dessa attribut för en specifik [`nodeType`](./nodetype/) (t.ex. nodeValue för ett [`Element`](../element/) eller attribut för ett [`Comment`](../comment/)), returneras null. Observera att de specialiserade gränssnitten kan innehålla ytterligare och mer praktiska mekanismer för att hämta och sätta relevant information.

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Den skrivskyddade baseURI‑egenskapen i Node‑gränssnittet returnerar den absoluta bas‑URL:en för dokumentet som innehåller noden. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Den skrivskyddade childNodes‑egenskapen i Node‑gränssnittet returnerar en levande [`NodeList`](../../com.aspose.html.collections/nodelist/) av barnnoder för det givna elementet där den första barnnoden får index 0. Barnnoder inkluderar element, text och kommentarer. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Den skrivskyddade firstChild‑egenskapen för `Node`‑gränssnittet returnerar nodens första barn i trädet, eller null om noden saknar barn. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Den skrivskyddade lastChild‑egenskapen för `Node`‑gränssnittet returnerar nodens sista barn. Om dess förälder är ett element är barnet vanligtvis ett elementnod, ett textnod eller ett kommentarsnod. Den returnerar null om det inte finns några barn‑element. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Returnerar den lokala delen av det kvalificerade namnet för denna nod. För noder av någon annan typ än [`ELEMENT_NODE`](./element_node/) och [`ATTRIBUTE_NODE`](./attribute_node/) samt noder skapade med en DOM Level 1‑metod, såsom [`Document.createElement()`](../document/createelement/), är detta alltid null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI‑egenskapen som är skrivskyddad returnerar elementets paket‑URI, eller null om elementet inte är i ett paket. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Den skrivskyddade nextSibling‑egenskapen för `Node`‑gränssnittet returnerar noden som omedelbart följer den angivna i dess förälders [`childNodes`](./childnodes/), eller null om den angivna noden är det sista barnet i förälderelementet. |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) Den skrivskyddade nodeName‑egenskapen för Node returnerar namnet på den aktuella noden som en String. |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) En kod som representerar typen av det underliggande objektet. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | The nodeValue property of `Node `interface returns or sets the value of the current node. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Den skrivskyddade ownerDocument‑egenskapen i Node‑gränssnittet returnerar nodens översta dokumentobjekt. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Den skrivskyddade parentElement‑egenskapen för `Node`‑gränssnittet returnerar DOM‑nodens föräldra‑[`Element`](../element/), eller null om noden antingen saknar förälder, eller dess förälder inte är ett DOM‑element. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Den skrivskyddade parentNode‑egenskapen i Node‑gränssnittet returnerar den angivna nodens förälder i DOM‑trädet. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix‑egenskapen som är skrivskyddad returnerar paket‑prefixet för det angivna elementet, eller null om inget prefix har angetts. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Den skrivskyddade previousSibling‑egenskapen för `Node`‑gränssnittet returnerar noden som omedelbart föregår den angivna i dess förälders [`childNodes`](./firstchild/)‑lista, eller null om den angivna noden är den första i listan. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | The textContent property of the `Node` interface represents the text content of the node and its descendants. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | addEventListener()‑metoden i [`EventTarget `](../eventtarget/)‑gränssnittet ställer in en funktion som kommer att anropas närhelst den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild()-metoden i Node-gränssnittet lägger till en nod i slutet av listan med barn till en angiven föräldranod. Om det givna barnet är en referens till en befintlig nod i dokumentet, flyttar appendChild() den från sin nuvarande position till den nya positionen (det krävs inte att noden tas bort från sin föräldranod innan den läggs till i någon annan nod). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Skickar en händelse till den specificerade [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synkront) och anropar de berörda EventListeners i rätt ordning. De vanliga reglerna för händelsebehandling (inklusive fångst- och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | The hasChildNodes() method of the Node interface returns a boolean value indicating whether the given `Node` has child nodes or not. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore()-metoden i Node-gränssnittet infogar en nod före en referensnod som ett barn till en specificerad föräldranod. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace()-metoden i Node-gränssnittet accepterar ett paket-URI som argument. Den returnerar ett booleskt värde som är true om paketet är standardpaketet på den givna noden och false om det inte är det. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | The isEqualNode() method of the `Node` interface tests whether two nodes are equal. Two nodes are equal when they have the same type, defining characteristics (for elements, this would be their ID, number of children, and so forth), its attributes match, and so on. The specific set of data points that must match varies depending on the types of the nodes. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode()-metoden i Node-gränssnittet är ett äldre alias för ===-operatorn för strikt likhet. Den testar alltså om två noder är desamma (med andra ord, om de refererar till samma objekt). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI()-metoden i Node-gränssnittet tar ett prefix som parameter och returnerar paket-URI:n som är associerad med det på den givna noden om den hittas (annars null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix()-metoden i Node-gränssnittet returnerar en sträng som innehåller prefixet för ett givet paket-URI, om det finns, annars null. När flera prefix är möjliga returneras det första prefixet. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Puts all [`Text`](../text/) nodes in the full depth of the sub-tree underneath this Node, including attribute nodes, into a "normal" form where only structure (e.g., [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), and [`entity references`](../entityreference/)) separates [`Text`](../text/) nodes, i.e., there are neither adjacent Text nodes nor empty Text nodes. This can be used to ensure that the DOM view of a document is the same as if it were saved and re-loaded, and is useful when operations (such as XPointer [XPointer] lookups) that depend on a particular document tree structure are to be used. If the parameter "normalize-characters" of the [`DOMConfiguration`](../../com.aspose.html/configuration/) object attached to the [`Node.ownerDocument`](./ownerdocument/) is true, this method will also fully normalize the characters of the Text nodes. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Metoden removeChild() i Node‑gränssnittet tar bort en barnnod från DOM och returnerar den borttagna noden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Ersätter barnnoden oldChild med newChild i listan av barn, och returnerar oldChild‑noden. Om newChild är ett [`DocumentFragment`](../documentfragment/)‑objekt ersätts oldChild av alla [`DocumentFragment`](../documentfragment/)‑barn, som infogas i samma ordning. Om newChild redan finns i trädet tas den först bort. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Returnerar en sträng som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | An [`Attribute`](../attr/) of an [`Element`](../element/). |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | A [`CDATASection`](../cdatasection/), such as &lt;!CDATA[[ … ]]&gt;. |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | A [`Comment`](../comment/) node, such as &lt;!-- … --&gt;. |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | A [`DocumentFragment`](../documentfragment/) node. |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | A [`Document`](../document/) node. |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | A [`DocumentType`](../documenttype/) node, such as &lt;!DOCTYPE html&gt;. |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | An [`Element`](../element/) node like &lt;p&gt; or &lt;div&gt;. |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | An [`Entity`](../entity/) node. |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | An [`EntityReference`](../entityreference/) node. |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | A [`Notation`](../notation/) node |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | En [`ProcessingInstruction`](../processinginstruction/) i ett XML-dokument, såsom &lt;?xml-stylesheet … ?&gt;. |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | Den faktiska [`Text`](../text/) inuti ett [`Element`](../element/) eller [`Attr`](../attr/). |

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Se även

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
