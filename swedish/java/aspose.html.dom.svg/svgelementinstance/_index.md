---
title: "SVGElementInstance klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.svg.SVGElementInstance klass. Rotobjektet för varje use-element skuggträd implementerar SVGUseElementShadowRoot-gränssnittet. Detta gränssnitt definierar för närvarande inga utökningar av egenskaperna och metoderna som definieras för ShadowRoot-gränssnittet och DocumentOrShadowRoot-mixin. Trädet som är rotat vid denna nod är dock helt skrivskyddat ur författarskriptens perspektiv."
type: docs

url: /sv/java/com.aspose.html.dom.svg/svgelementinstance/
---
## SVGElementInstance class

Rotobjektet för varje use‑element‑skuggträd implementerar SVGUseElementShadowRoot‑gränssnittet. Detta gränssnitt definierar för närvarande inga utökningar av egenskaperna och metoderna som definieras för ShadowRoot‑gränssnittet och DocumentOrShadowRoot‑mixinen. Trädet som är rotat vid denna nod är dock helt skrivskyddat ur skriptförfattarens perspektiv.

```java
public class SVGElementInstance : ShadowRoot
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Den skrivskyddade baseURI‑egenskapen i Node‑gränssnittet returnerar den absoluta bas‑URL:en för dokumentet som innehåller noden. |
| [getChildElementCount](../../com.aspose.html.dom/documentfragment/childelementcount/) Returnerar det aktuella antalet elementnoder som är barn till detta element. 0 om detta element inte har några barnnoder av nodtyp 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Den skrivskyddade childNodes‑egenskapen i Node‑gränssnittet returnerar en levande [`NodeList`](../../com.aspose.html.collections/nodelist/) av barnnoder för det angivna elementet där den första barnnoden får index 0. Barnnoder inkluderar element, text och kommentarer. |
| [getChildren](../../com.aspose.html.dom/documentfragment/children/) Returnerar barn elementen för det aktuella elementet. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Den skrivskyddade firstChild‑egenskapen i [`Node`](../../com.aspose.html.dom/node/)‑gränssnittet returnerar nodens första barn i trädet, eller null om noden saknar barn. |
| [getFirstElementChild](../../com.aspose.html.dom/documentfragment/firstelementchild/) Returnerar den första barn-elementnoden för detta element. null om detta element inte har några barn-element. |
| [getHost](../../com.aspose.html.dom/shadowroot/host/) Host är ett element som innehåller detta ShadowRoot. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Den skrivskyddade lastChild‑egenskapen i [`Node`](../../com.aspose.html.dom/node/)‑gränssnittet returnerar nodens sista barn. Om dess förälder är ett element är barnet vanligtvis ett elementnod, ett textnod eller ett kommentarnod. Den returnerar null om det inte finns några barn‑element. |
| [getLastElementChild](../../com.aspose.html.dom/documentfragment/lastelementchild/) Returnerar den sista barn-elementnoden för detta element. null om detta element inte har några barn-element. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Returnerar den lokala delen av det kvalificerade namnet för denna nod. För noder av någon annan typ än [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) och [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) och noder skapade med en DOM Level 1‑metod, såsom [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/), är detta alltid null. |
| [getMode](../../com.aspose.html.dom/shadowroot/mode/) Läge i vilket detta ShadowRoot opererar. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Den skrivskyddade egenskapen Element.packageURI returnerar paket‑URI:n för elementet, eller null om elementet inte är i ett paket. |
| [getNextElementSibling](../../com.aspose.html.dom/documentfragment/nextelementsibling/) Returnerar nästa syskon-elementnod för detta element. null om detta element inte har några element-syskonnoder som kommer efter detta i dokumentträdet. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Den skrivskyddade nextSibling‑egenskapen i [`Node`](../../com.aspose.html.dom/node/)‑gränssnittet returnerar noden som omedelbart följer den angivna i dess förälders [`childNodes`](../../com.aspose.html.dom/node/childnodes/), eller returnerar null om den angivna noden är det sista barnet i förälderelementet. |
| [getNodeName](../../com.aspose.html.dom/documentfragment/nodename/) Namnet på denna nod, beroende på dess typ. |
| [getNodeType](../../com.aspose.html.dom/documentfragment/nodetype/) En kod som representerar typen av det underliggande objektet. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | nodeValue‑egenskapen i [`Node `](../../com.aspose.html.dom/node/)gränssnittet returnerar eller sätter värdet för den aktuella noden. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Den skrivskyddade ownerDocument‑egenskapen i Node‑gränssnittet returnerar nodens översta dokumentobjekt. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Den skrivskyddade parentElement‑egenskapen i [`Node`](../../com.aspose.html.dom/node/)‑gränssnittet returnerar DOM‑nodens föräldra‑[`Element`](../../com.aspose.html.dom/element/), eller null om noden saknar förälder, eller om dess förälder inte är ett DOM‑Element. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Den skrivskyddade parentNode‑egenskapen i Node‑gränssnittet returnerar den angivna nodens förälder i DOM‑trädet. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Den skrivskyddade egenskapen prefix returnerar paket‑prefixet för det angivna elementet, eller null om inget prefix har angetts. |
| [getPreviousElementSibling](../../com.aspose.html.dom/documentfragment/previouselementsibling/) Returnerar föregående syskon-elementnod för detta element. null om detta element inte har några element-syskonnoder som kommer före detta i dokumentträdet. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Den skrivskyddade previousSibling‑egenskapen i [`Node`](../../com.aspose.html.dom/node/)‑gränssnittet returnerar noden som omedelbart föregår den angivna i dess förälders [`childNodes`](../../com.aspose.html.dom/node/firstchild/)‑lista, eller null om den angivna noden är den första i listan. |
| [textContent](../../com.aspose.html.dom/documentfragment/textcontent/) { get; set; } | Detta attribut returnerar textinnehållet för denna nod och dess undernoder. När det är definierat som null har en eventuell ändring ingen effekt. Vid en ändring tas alla eventuella barn till noden bort och, om den nya strängen inte är tom eller null, ersätts den med en enda Text‑nod som innehåller den sträng som attributet sätts till. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | addEventListener()-metoden i [`EventTarget `](../../com.aspose.html.dom/eventtarget/)‑gränssnittet konfigurerar en funktion som kommer att anropas närhelst den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild()-metoden i Node-gränssnittet lägger till en nod i slutet av listan med barn till en specificerad föräldranod. Om den angivna barnet är en referens till en befintlig nod i dokumentet, flyttar appendChild() den från sin nuvarande position till den nya positionen (det krävs inte att noden tas bort från sin föräldranod innan den läggs till i någon annan nod). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Skickar ett Event till den specificerade [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synkront) och anropar de påverkade EventListeners i rätt ordning. De vanliga händelsebehandlingsreglerna (inklusive fångst- och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes()-metoden i Node-gränssnittet returnerar ett booleskt värde som indikerar om den angivna [`Node`](../../com.aspose.html.dom/node/) har barnnoder eller inte. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore()-metoden i Node-gränssnittet infogar en nod före en referensnod som ett barn till en specificerad föräldranod. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace()-metoden i Node-gränssnittet accepterar ett paket-URI som argument. Den returnerar ett booleskt värde som är true om paketet är standardpaketet på den givna noden och false om det inte är det. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | isEqualNode()-metoden i [`Node`](../../com.aspose.html.dom/node/)-gränssnittet testar om två noder är lika. Två noder är lika när de har samma typ, definierande egenskaper (för element skulle detta vara deras ID, antal barn osv.), deras attribut matchar, och så vidare. Den specifika uppsättningen av datapunkter som måste matcha varierar beroende på nodernas typer. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode()-metoden i Node-gränssnittet är ett äldre alias för ===-operatorn för strikt likhet. Det vill säga, den testar om två noder är samma (med andra ord, om de refererar till samma objekt). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI()-metoden i Node-gränssnittet tar ett prefix som parameter och returnerar paket-URI:n som är associerad med det på den givna noden om den finns (och null annars). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix()-metoden i Node-gränssnittet returnerar en sträng som innehåller prefixet för ett givet paket-URI, om det finns, och null annars. När flera prefix är möjliga returneras det första prefixet. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Placera alla [`Text`](../../com.aspose.html.dom/text/)-noder i hela djupet av underträdet under denna Node, inklusive attributnoder, i ett "normalt" format där endast strukturen (t.ex. [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), och [`entity references`](../../com.aspose.html.dom/entityreference/)) separerar [`Text`](../../com.aspose.html.dom/text/)-noder, dvs. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer (såsom XPointer‑uppslagningar) som beror på en viss dokumentträdstruktur ska användas. Om parametern "normalize-characters" för [`DOMConfiguration`](../../com.aspose.html/configuration/)-objektet som är kopplat till [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) är true, kommer denna metod också att helt normalisera tecknen i Text‑noderna. |
| [querySelector](../../com.aspose.html.dom/documentfragment/queryselector/)(String) | Returnerar det första Elementet i dokumentet som matchar selektorn |
| [querySelectorAll](../../com.aspose.html.dom/documentfragment/queryselectorall/)(String) | Returnerar en NodeList med alla Element i dokumentet som matchar selektorn |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Metoden removeChild() i Node‑gränssnittet tar bort en barnnod från DOM och returnerar den borttagna noden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Ersätter barnnoden oldChild med newChild i listan av barn och returnerar oldChild‑noden. Om newChild är ett [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/)‑objekt, ersätts oldChild av alla [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/)‑barn, som infogas i samma ordning. Om newChild redan finns i trädet tas den först bort. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Returnerar en sträng som representerar detta objekt. |

### Se även

* class [ShadowRoot](../../com.aspose.html.dom/shadowroot/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
