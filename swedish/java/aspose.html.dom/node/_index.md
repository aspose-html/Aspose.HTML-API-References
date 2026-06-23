---
title: "Node-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.Node-klass. Node-gränssnittet är den primära datatypen för hela Document Object Model. Det representerar en enskild nod i dokumentträdet. Även om alla objekt som implementerar Node-gränssnittet exponerar metoder för att hantera barn, har inte alla objekt som implementerar Node-gränssnittet barn. Till exempel kan Text-noder sakna barn och att lägga till barn till sådana noder resulterar i att ett DOMException kastas."
type: docs

url: /sv/java/com.aspose.html.dom/node/
---
## Node class

The Node‑gränssnittet är den primära datatypen för hela Document Object Model. Det representerar en enskild nod i dokumentträdet. Medan alla objekt som implementerar Node‑gränssnittet exponerar metoder för att hantera barn, kan inte alla objekt som implementerar Node‑gränssnittet ha barn. Till exempel kan [`Text`](../text/)‑noder sakna barn, och att lägga till barn till sådana noder resulterar i att ett [`DOMException`](../domexception/)‑undantag kastas.

Attributen [`nodeName`](./nodename/), [`nodeValue`](./nodevalue/) och attribut inkluderas som en mekanism för att komma åt nodinformation utan att kasta ner till det specifika härledda gränssnittet. I fall där det inte finns någon uppenbar mappning av dessa attribut för en specifik [`nodeType`](./nodetype/) (t.ex. nodeValue för ett [`Element`](../element/) eller attribut för ett [`Comment`](../comment/)), returneras null. Observera att de specialiserade gränssnitten kan innehålla ytterligare och mer bekväma mekanismer för att hämta och sätta relevant information.

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Den skrivskyddade baseURI‑egenskapen i Node‑gränssnittet returnerar den absoluta bas‑URL:en för dokumentet som innehåller noden. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Den skrivskyddade childNodes‑egenskapen i Node‑gränssnittet returnerar en levande [`NodeList`](../../com.aspose.html.collections/nodelist/) av barnnoder för det angivna elementet där den första barnnoden får index 0. Barnnoder inkluderar element, text och kommentarer. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Den skrivskyddade firstChild‑egenskapen för `Node`‑gränssnittet returnerar nodens första barn i trädet, eller null om noden saknar barn. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Den skrivskyddade lastChild‑egenskapen för `Node`‑gränssnittet returnerar nodens sista barn. Om dess förälder är ett element är barnet vanligtvis ett elementnod, ett textnod eller ett kommentarsnod. Den returnerar null om det inte finns några barn‑element. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Returnerar den lokala delen av det kvalificerade namnet för denna nod. För noder av någon annan typ än [`ELEMENT_NODE`](./element_node/) och [`ATTRIBUTE_NODE`](./attribute_node/) samt noder skapade med en DOM Level 1‑metod, såsom [`Document.createElement()`](../document/createelement/), är detta alltid null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Den skrivskyddade egenskapen Element.packageURI returnerar paket‑URI:n för elementet, eller null om elementet inte är i ett paket. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Den skrivskyddade nextSibling‑egenskapen för `Node`‑gränssnittet returnerar noden som omedelbart följer den angivna i deras förälders [`childNodes`](./childnodes/), eller returnerar null om den angivna noden är det sista barnet i förälderelementet. |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) Den skrivskyddade nodeName‑egenskapen för Node returnerar namnet på den aktuella noden som en String. |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) En kod som representerar typen av det underliggande objektet. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | nodeValue‑egenskapen för `Node`‑gränssnittet returnerar eller sätter värdet för den aktuella noden. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Den skrivskyddade ownerDocument‑egenskapen i Node‑gränssnittet returnerar nodens översta dokumentobjekt. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Den skrivskyddade parentElement‑egenskapen för `Node`‑gränssnittet returnerar DOM‑nodens föräldra‑[`Element`](../element/), eller null om noden antingen saknar förälder, eller dess förälder inte är ett DOM‑element. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Den skrivskyddade parentNode‑egenskapen i Node‑gränssnittet returnerar den angivna nodens förälder i DOM‑trädet. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Den skrivskyddade egenskapen prefix returnerar paket‑prefixet för det angivna elementet, eller null om inget prefix har angetts. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Den skrivskyddade previousSibling‑egenskapen för `Node`‑gränssnittet returnerar noden som omedelbart föregår den angivna i dess förälders [`childNodes`](./firstchild/)‑lista, eller null om den angivna noden är den första i listan. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | textContent‑egenskapen för `Node`‑gränssnittet representerar nodens textinnehåll och dess underordnade. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | addEventListener()‑metoden i [`EventTarget `](../eventtarget/)‑gränssnittet ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild()-metoden i Node-gränssnittet lägger till en nod i slutet av listan med barn till en specificerad föräldranod. Om den angivna barnet är en referens till en befintlig nod i dokumentet, flyttar appendChild() den från sin nuvarande position till den nya positionen (det krävs inte att noden tas bort från sin föräldranod innan den läggs till i någon annan nod). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Skickar ett Event till den specificerade [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synkront) och anropar de påverkade EventListeners i rätt ordning. De vanliga händelsebehandlingsreglerna (inklusive fångst- och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes()‑metoden för Node‑gränssnittet returnerar ett booleskt värde som indikerar om den givna `Node` har barnnoder eller inte. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore()-metoden i Node-gränssnittet infogar en nod före en referensnod som ett barn till en specificerad föräldranod. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace()-metoden i Node-gränssnittet accepterar ett paket-URI som argument. Den returnerar ett booleskt värde som är true om paketet är standardpaketet på den givna noden och false om det inte är det. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | isEqualNode()‑metoden för `Node`‑gränssnittet testar om två noder är lika. Två noder är lika när de har samma typ, definierande egenskaper (för element skulle detta vara deras ID, antal barn, osv.), deras attribut matchar, och så vidare. Den specifika uppsättningen av datapunkter som måste matcha varierar beroende på nodernas typer. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode()-metoden i Node-gränssnittet är ett äldre alias för ===-operatorn för strikt likhet. Det vill säga, den testar om två noder är samma (med andra ord, om de refererar till samma objekt). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI()-metoden i Node-gränssnittet tar ett prefix som parameter och returnerar paket-URI:n som är associerad med det på den givna noden om den finns (och null annars). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix()-metoden i Node-gränssnittet returnerar en sträng som innehåller prefixet för ett givet paket-URI, om det finns, och null annars. När flera prefix är möjliga returneras det första prefixet. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Placera alla [`Text`](../text/)‑noder i hela djupet av delträdet under denna Node, inklusive attributnoder, i ett \"normalt\" format där endast struktur (t.ex. [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), och [`entity references`](../entityreference/)) separerar [`Text`](../text/)‑noder, d.v.s. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer (såsom XPointer‑uppslagningar) som beror på en viss dokumentträdstruktur ska användas. Om parametern \"normalize-characters\" för [`DOMConfiguration`](../../com.aspose.html/configuration/)‑objektet som är knutet till [`Node.ownerDocument`](./ownerdocument/) är sann, kommer denna metod också att fullständigt normalisera tecknen i Text‑noderna. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Metoden removeChild() i Node‑gränssnittet tar bort en barnnod från DOM och returnerar den borttagna noden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Ersätter barnnoden oldChild med newChild i listan av barn, och returnerar oldChild‑noden. Om newChild är ett [`DocumentFragment`](../documentfragment/)‑objekt ersätts oldChild av alla [`DocumentFragment`](../documentfragment/)‑barn, som infogas i samma ordning. Om newChild redan finns i trädet tas den först bort. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Returnerar en sträng som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | Ett [`Attribute`](../attr/) för ett [`Element`](../element/). |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | En [`CDATASection`](../cdatasection/), såsom &lt;!CDATA[[ … ]]&gt;. |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | En [`Comment`](../comment/)‑nod, såsom &lt;!-- … --&gt;. |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | En [`DocumentFragment`](../documentfragment/)‑nod. |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | En [`Document`](../document/)‑nod. |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | En [`DocumentType`](../documenttype/)‑nod, såsom &lt;!DOCTYPE html&gt;. |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | Ett [`Element`](../element/)‑nod som &lt;p&gt; eller &lt;div&gt;. |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | En [`Entity`](../entity/)‑nod. |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | En [`EntityReference`](../entityreference/)‑nod. |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | En [`Notation`](../notation/)‑nod |
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
