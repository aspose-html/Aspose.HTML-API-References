---
title: "DocumentFragment-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.DocumentFragment-klass. DocumentFragment är ett lättviktigt eller minimalt Document-objekt. Det är mycket vanligt att vilja kunna extrahera en del av ett dokuments träd eller skapa ett nytt fragment av ett dokument."
type: docs

url: /sv/java/com.aspose.html.dom/documentfragment/
---
## DocumentFragment class

DocumentFragment är ett "lightweight" eller "minimal" Document-objekt. Det är mycket vanligt att vilja kunna extrahera en del av ett dokuments träd eller skapa ett nytt fragment av ett dokument.

```java
public class DocumentFragment : Node, IParentNode
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Den skrivskyddade baseURI‑egenskapen i Node‑gränssnittet returnerar den absoluta bas‑URL:en för dokumentet som innehåller noden. |
| [getChildElementCount](../../com.aspose.html.dom/documentfragment/childelementcount/) Returnerar det aktuella antalet elementnoder som är barn till detta element. 0 om detta element inte har några barnnoder av nodtyp 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Den skrivskyddade childNodes‑egenskapen i Node‑gränssnittet returnerar en levande [`NodeList`](../../com.aspose.html.collections/nodelist/) av barnnoder för det givna elementet där den första barnnoden får index 0. Barnnoder inkluderar element, text och kommentarer. |
| [getChildren](../../com.aspose.html.dom/documentfragment/children/) Returnerar barn elementen för det aktuella elementet. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Den skrivskyddade firstChild‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar nodens första barn i trädet, eller null om noden saknar barn. |
| [getFirstElementChild](../../com.aspose.html.dom/documentfragment/firstelementchild/) Returnerar den första barn-elementnoden för detta element. null om detta element inte har några barn-element. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Den skrivskyddade lastChild‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar nodens sista barn. Om dess förälder är ett element är barnet vanligtvis ett element‑nod, ett text‑nod eller ett kommentars‑nod. Den returnerar null om det inte finns några barn‑element. |
| [getLastElementChild](../../com.aspose.html.dom/documentfragment/lastelementchild/) Returnerar den sista barn-elementnoden för detta element. null om detta element inte har några barn-element. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Returnerar den lokala delen av det kvalificerade namnet för den här noden. För noder av någon annan typ än [`ELEMENT_NODE`](../node/element_node/) och [`ATTRIBUTE_NODE`](../node/attribute_node/) och noder skapade med en DOM Level 1-metod, såsom [`Document.createElement()`](../document/createelement/), är detta alltid null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI‑egenskapen som är skrivskyddad returnerar elementets paket‑URI, eller null om elementet inte är i ett paket. |
| [getNextElementSibling](../../com.aspose.html.dom/documentfragment/nextelementsibling/) Returnerar nästa syskon-elementnod för detta element. null om detta element inte har några element-syskon som kommer efter detta i dokumentträdet. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Den skrivskyddade nextSibling‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar noden som omedelbart följer den angivna i deras förälders [`childNodes`](../node/childnodes/), eller returnerar null om den angivna noden är det sista barnet i förälderelementet. |
| [getNodeName](../../com.aspose.html.dom/documentfragment/nodename/) Namnet på denna nod, beroende på dess typ. |
| [getNodeType](../../com.aspose.html.dom/documentfragment/nodetype/) En kod som representerar typen av det underliggande objektet. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | nodeValue‑egenskapen för [`Node `](../node/)‑gränssnittet returnerar eller sätter värdet för den aktuella noden. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Den skrivskyddade ownerDocument‑egenskapen i Node‑gränssnittet returnerar nodens översta dokumentobjekt. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Den skrivskyddade parentElement‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar DOM‑nodens föräldra‑[`Element`](../element/), eller null om noden saknar förälder eller om dess förälder inte är ett DOM‑Element. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Den skrivskyddade parentNode‑egenskapen i Node‑gränssnittet returnerar den angivna nodens förälder i DOM‑trädet. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix‑egenskapen som är skrivskyddad returnerar paket‑prefixet för det angivna elementet, eller null om inget prefix har angetts. |
| [getPreviousElementSibling](../../com.aspose.html.dom/documentfragment/previouselementsibling/) Returnerar föregående syskon-elementnod för detta element. null om detta element inte har några element-syskon som kommer före detta i dokumentträdet. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Den skrivskyddade previousSibling‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar noden som omedelbart föregår den angivna i dess förälders [`childNodes`](../node/firstchild/)‑lista, eller null om den angivna noden är den första i listan. |
| [textContent](../../com.aspose.html.dom/documentfragment/textcontent/) { get; set; } | Detta attribut returnerar textinnehållet för denna nod och dess undernoder. När det är definierat som null har en eventuell inställning ingen effekt. Vid inställning tas eventuella befintliga barn till noden bort och, om den nya strängen inte är tom eller null, ersätts den med ett enda Text‑nod som innehåller den sträng som attributet sätts till. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | addEventListener()‑metoden i [`EventTarget `](../eventtarget/)‑gränssnittet ställer in en funktion som kommer att anropas närhelst den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild()-metoden i Node-gränssnittet lägger till en nod i slutet av listan med barn till en angiven föräldranod. Om det givna barnet är en referens till en befintlig nod i dokumentet, flyttar appendChild() den från sin nuvarande position till den nya positionen (det krävs inte att noden tas bort från sin föräldranod innan den läggs till i någon annan nod). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Skickar en händelse till den specificerade [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synkront) och anropar de berörda EventListeners i rätt ordning. De vanliga reglerna för händelsebehandling (inklusive fångst- och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes()‑metoden i Node‑gränssnittet returnerar ett booleskt värde som indikerar om den angivna [`Node`](../node/) har barnnoder eller inte. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore()-metoden i Node-gränssnittet infogar en nod före en referensnod som ett barn till en specificerad föräldranod. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace()-metoden i Node-gränssnittet accepterar ett paket-URI som argument. Den returnerar ett booleskt värde som är true om paketet är standardpaketet på den givna noden och false om det inte är det. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | isEqualNode()‑metoden i [`Node`](../node/)‑gränssnittet testar om två noder är lika. Två noder är lika när de har samma typ, definierande egenskaper (för element skulle detta vara deras ID, antal barn osv.), deras attribut matchar, och så vidare. Den specifika uppsättningen av datapunkter som måste matcha varierar beroende på nodernas typer. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode()-metoden i Node-gränssnittet är ett äldre alias för ===-operatorn för strikt likhet. Den testar alltså om två noder är desamma (med andra ord, om de refererar till samma objekt). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI()-metoden i Node-gränssnittet tar ett prefix som parameter och returnerar paket-URI:n som är associerad med det på den givna noden om den hittas (annars null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix()-metoden i Node-gränssnittet returnerar en sträng som innehåller prefixet för ett givet paket-URI, om det finns, annars null. När flera prefix är möjliga returneras det första prefixet. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Sätter alla [`Text`](../text/)‑noder i hela djupet av delträdet under denna Node, inklusive attributnoder, i ett \"normalt\" format där endast strukturen (t.ex. [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), och [`entity references`](../entityreference/)) separerar [`Text`](../text/)‑noder, d.v.s. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer (såsom XPointer‑uppslag [XPointer]) som är beroende av en viss dokumentträdstruktur ska användas. Om parametern \"normalize-characters\" för [`DOMConfiguration`](../../com.aspose.html/configuration/)‑objektet som är knutet till [`Node.ownerDocument`](../node/ownerdocument/) är sann, kommer denna metod också att helt normalisera tecknen i Text‑noderna. |
| [querySelector](../../com.aspose.html.dom/documentfragment/queryselector/)(String) | Returnerar det första Element i dokumentet som matchar selektorn |
| [querySelectorAll](../../com.aspose.html.dom/documentfragment/queryselectorall/)(String) | Returnerar en NodeList med alla Element i dokumentet som matchar selektorn |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Metoden removeChild() i Node‑gränssnittet tar bort en barnnod från DOM och returnerar den borttagna noden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Ersätter barnnoden oldChild med newChild i listan av barn och returnerar oldChild-noden. Om newChild är ett `DocumentFragment`-objekt ersätts oldChild av alla `DocumentFragment`-barn, som sätts in i samma ordning. Om newChild redan finns i trädet tas den först bort. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Returnerar en sträng som representerar detta objekt. |

### Se även

* class [Node](../node/)
* interface [IParentNode](../iparentnode/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
