---
title: "Comment-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.Comment-klass. Ärver från CharacterData och representerar innehållet i en kommentar, d.v.s. alla tecken mellan startmarkeringen."
type: docs

url: /sv/java/com.aspose.html.dom/comment/
---
## Comment class

Arver från CharacterData och representerar innehållet i en kommentar, d.v.s. alla tecken mellan start- och slutcitattecknen ''.

```java
public class Comment : CharacterData
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Den skrivskyddade baseURI‑egenskapen i Node‑gränssnittet returnerar den absoluta bas‑URL:en för dokumentet som innehåller noden. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Den skrivskyddade childNodes‑egenskapen i Node‑gränssnittet returnerar en levande [`NodeList`](../../com.aspose.html.collections/nodelist/) av barnnoder för det angivna elementet där den första barnnoden får index 0. Barnnoder inkluderar element, text och kommentarer. |
| [data](../../com.aspose.html.dom/characterdata/data/) { get; set; } | Teckendatan för noden som implementerar detta gränssnitt. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Den skrivskyddade firstChild‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar nodens första barn i trädet, eller null om noden saknar barn. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Den skrivskyddade lastChild‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar nodens sista barn. Om dess förälder är ett element är barnet vanligtvis ett element‑nod, ett text‑nod eller ett kommentars‑nod. Den returnerar null om det inte finns några barn‑element. |
| [getLength](../../com.aspose.html.dom/characterdata/length/) Antalet 16‑bit‑enheter som är tillgängliga via data och metoden subStringData nedan. Detta kan ha värdet noll, d.v.s. CharacterData‑noder kan vara tomma. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Returnerar den lokala delen av det kvalificerade namnet för denna nod. För noder av någon annan typ än [`ELEMENT_NODE`](../node/element_node/) och [`ATTRIBUTE_NODE`](../node/attribute_node/) samt noder som skapats med en DOM Level 1‑metod, såsom [`Document.createElement()`](../document/createelement/), är detta alltid null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Den skrivskyddade egenskapen Element.packageURI returnerar paket‑URI:n för elementet, eller null om elementet inte är i ett paket. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Den skrivskyddade nextSibling‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar noden som omedelbart följer den angivna i deras förälders [`childNodes`](../node/childnodes/), eller returnerar null om den angivna noden är det sista barnet i förälderelementet. |
| [getNodeName](../../com.aspose.html.dom/comment/nodename/) Namnet på denna nod, beroende på dess typ. |
| [getNodeType](../../com.aspose.html.dom/comment/nodetype/) En kod som representerar typen av det underliggande objektet. |
| [nodeValue](../../com.aspose.html.dom/comment/nodevalue/) { get; set; } | Värdet på denna nod, beroende på dess typ. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Den skrivskyddade ownerDocument‑egenskapen i Node‑gränssnittet returnerar nodens översta dokumentobjekt. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Den skrivskyddade parentElement‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar DOM‑nodens föräldra‑[`Element`](../element/), eller null om noden saknar förälder eller om dess förälder inte är ett DOM‑Element. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Den skrivskyddade parentNode‑egenskapen i Node‑gränssnittet returnerar den angivna nodens förälder i DOM‑trädet. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Den skrivskyddade egenskapen prefix returnerar paket‑prefixet för det angivna elementet, eller null om inget prefix har angetts. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Den skrivskyddade previousSibling‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar noden som omedelbart föregår den angivna i dess förälders [`childNodes`](../node/firstchild/)‑lista, eller null om den angivna noden är den första i listan. |
| [textContent](../../com.aspose.html.dom/comment/textcontent/) { get; set; } | Detta attribut returnerar textinnehållet för denna nod och dess undernoder. När det är definierat som null har en eventuell ändring ingen effekt. Vid en ändring tas alla eventuella barn till noden bort och, om den nya strängen inte är tom eller null, ersätts den med en enda Text‑nod som innehåller den sträng som attributet sätts till. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | addEventListener()‑metoden i [`EventTarget `](../eventtarget/)‑gränssnittet ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild()-metoden i Node-gränssnittet lägger till en nod i slutet av listan med barn till en specificerad föräldranod. Om den angivna barnet är en referens till en befintlig nod i dokumentet, flyttar appendChild() den från sin nuvarande position till den nya positionen (det krävs inte att noden tas bort från sin föräldranod innan den läggs till i någon annan nod). |
| [appendData](../../com.aspose.html.dom/characterdata/appenddata/)(String) | Lägg till strängen i slutet av teckendatan för noden. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [deleteData](../../com.aspose.html.dom/characterdata/deletedata/)(int, int) | Ta bort ett intervall av 16‑bit‑enheter från noden. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Skickar ett Event till den specificerade [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synkront) och anropar de påverkade EventListeners i rätt ordning. De vanliga händelsebehandlingsreglerna (inklusive fångst- och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes()‑metoden i Node‑gränssnittet returnerar ett booleskt värde som indikerar om den givna [`Node`](../node/) har barnnoder eller inte. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore()-metoden i Node-gränssnittet infogar en nod före en referensnod som ett barn till en specificerad föräldranod. |
| [insertData](../../com.aspose.html.dom/characterdata/insertdata/)(int, String) | Infoga en sträng vid den angivna 16‑bit‑enhets‑offseten. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace()-metoden i Node-gränssnittet accepterar ett paket-URI som argument. Den returnerar ett booleskt värde som är true om paketet är standardpaketet på den givna noden och false om det inte är det. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | isEqualNode()‑metoden i [`Node`](../node/)‑gränssnittet testar om två noder är lika. Två noder är lika när de har samma typ, definierande egenskaper (för element skulle detta vara deras ID, antal barn osv.), deras attribut matchar, osv. Den specifika uppsättningen av datapunkter som måste matcha varierar beroende på nodernas typer. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode()-metoden i Node-gränssnittet är ett äldre alias för ===-operatorn för strikt likhet. Det vill säga, den testar om två noder är samma (med andra ord, om de refererar till samma objekt). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI()-metoden i Node-gränssnittet tar ett prefix som parameter och returnerar paket-URI:n som är associerad med det på den givna noden om den finns (och null annars). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix()-metoden i Node-gränssnittet returnerar en sträng som innehåller prefixet för ett givet paket-URI, om det finns, och null annars. När flera prefix är möjliga returneras det första prefixet. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Placera alla [`Text`](../text/) noder i hela djupet av delträdet under denna Nod, inklusive attributnoder, i ett "normal" format där endast struktur (t.ex. [`elements`](../element/), `comments`, [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), och [`entity references`](../entityreference/)) separerar [`Text`](../text/) noder, d.v.s. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer (såsom XPointer [XPointer] uppslag) som beror på en viss dokumentträdstruktur ska användas. Om parametern "normalize-characters" för [`DOMConfiguration`](../../com.aspose.html/configuration/) objektet som är knutet till [`Node.ownerDocument`](../node/ownerdocument/) är sann, kommer denna metod också att helt normalisera tecknen i Text‑noderna. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Metoden removeChild() i Node‑gränssnittet tar bort en barnnod från DOM och returnerar den borttagna noden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Ersätter barnnoden oldChild med newChild i listan av barn, och returnerar oldChild‑noden. Om newChild är ett [`DocumentFragment`](../documentfragment/)‑objekt ersätts oldChild av alla [`DocumentFragment`](../documentfragment/)‑barn, som infogas i samma ordning. Om newChild redan finns i trädet tas den först bort. |
| [replaceData](../../com.aspose.html.dom/characterdata/replacedata/)(int, int, String) | Ersätt tecknen som börjar vid den angivna 16‑bit‑enhets‑offseten med den angivna strängen. |
| [subStringData](../../com.aspose.html.dom/characterdata/subStringdata/)(int, int) | Extraherar ett intervall av data från noden. |
| [toString](../../com.aspose.html.dom/characterdata/toString/)() | Returnerar en sträng som representerar detta objekt. |

### Se även

* class [CharacterData](../characterdata/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
