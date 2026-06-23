---
title: "Document‑klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.Document‑klass. Document representerar hela HTML‑, XML‑ eller SVG‑dokumentet. Konceptuellt är det roten i dokumentträdet och ger primär åtkomst till dokumentets data."
type: docs

url: /sv/java/com.aspose.html.dom/document/
---
## Document class

Document representerar hela HTML-, XML- eller SVG-dokumentet. Konceptuellt är det roten i dokumentträdet och ger primär åtkomst till dokumentets data.

```java
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) Den absoluta bas‑URI:n för denna nod eller null om implementationen inte kunde erhålla en absolut URI. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) Hämtar dokumentets kodning. |
| [getCharset](../../com.aspose.html.dom/document/charset/) Hämtar dokumentets kodning. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) Returnerar det aktuella antalet elementnoder som är barn till detta element. 0 om detta element inte har några barnnoder av nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Den skrivskyddade childNodes‑egenskapen i Node‑gränssnittet returnerar en levande [`NodeList`](../../com.aspose.html.collections/nodelist/) av barnnoder för det angivna elementet där den första barnnoden får index 0. Barnnoder inkluderar element, text och kommentarer. |
| [getChildren](../../com.aspose.html.dom/document/children/) Returnerar de underordnade elementen. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) Hämtar dokumentets innehållstyp. |
| [getContext](../../com.aspose.html.dom/document/context/) Hämtar det aktuella webbläsningssammanhanget. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) defaultView‑IDL‑attributet för Document‑gränssnittet, vid hämtning, måste returnera detta dokuments webbläsningssammanhangs WindowProxy‑objekt, om detta dokument har ett associerat webbläsningssammanhang, annars null. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) Dokumenttypdeklarationen som är associerad med detta dokument. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) Detta är ett bekvämlighetsattribut som möjliggör direkt åtkomst till barnnoden som är dokumentelementet i dokumentet. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) Platsen för dokumentet eller null om den är odefinierad eller om dokumentet skapades med DOMImplementation.createDocument. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Den skrivskyddade firstChild‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar nodens första barn i trädet, eller null om noden saknar barn. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) Returnerar den första barn‑elementnoden för detta element. null om detta element saknar barn‑element. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) DOMImplementation‑objektet som hanterar detta dokument. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) Hämtar dokumentets kodning. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Den skrivskyddade lastChild‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar nodens sista barn. Om dess förälder är ett element är barnet vanligtvis ett element‑nod, ett text‑nod eller ett kommentars‑nod. Den returnerar null om det inte finns några barn‑element. |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) Returnerar den sista barn‑elementnoden för detta element. null om detta element saknar barn‑element. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Returnerar den lokala delen av det kvalificerade namnet för denna nod. För noder av någon annan typ än [`ELEMENT_NODE`](../node/element_node/) och [`ATTRIBUTE_NODE`](../node/attribute_node/) samt noder som skapats med en DOM Level 1‑metod, såsom [`Document.createElement()`](./createelement/), är detta alltid null. |
| [getLocation](../../com.aspose.html.dom/document/location/) Platsen för dokumentet. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Den skrivskyddade egenskapen Element.packageURI returnerar paket‑URI:n för elementet, eller null om elementet inte är i ett paket. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) Returnerar nästa syskon‑elementnod för detta element. null om detta element saknar element‑syskonnoder som kommer efter detta i dokumentträdet. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Den skrivskyddade nextSibling‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar noden som omedelbart följer den angivna i deras förälders [`childNodes`](../node/childnodes/), eller returnerar null om den angivna noden är det sista barnet i förälderelementet. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) Namnet på denna nod, beroende på dess typ. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) En kod som representerar typen av det underliggande objektet. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | nodeValue‑egenskapen för [`Node `](../node/)‑gränssnittet returnerar eller sätter värdet på den aktuella noden. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) Hämtar dokumentets ursprung. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) Hämtar ägardokumentet. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Den skrivskyddade parentElement‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar DOM‑nodens föräldra‑[`Element`](../element/), eller null om noden saknar förälder eller om dess förälder inte är ett DOM‑Element. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Den skrivskyddade parentNode‑egenskapen i Node‑gränssnittet returnerar den angivna nodens förälder i DOM‑trädet. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Den skrivskyddade egenskapen prefix returnerar paket‑prefixet för det angivna elementet, eller null om inget prefix har angetts. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) Returnerar föregående syskon‑elementnod för detta element. null om detta element saknar element‑syskonnoder som kommer före detta i dokumentträdet. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Den skrivskyddade previousSibling‑egenskapen i [`Node`](../node/)‑gränssnittet returnerar noden som omedelbart föregår den angivna i dess förälders [`childNodes`](../node/firstchild/)‑lista, eller null om den angivna noden är den första i listan. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) Returnerar dokumentets läge. "loading" medan dokumentet laddas, "interactive" när det har slutfört parsning men fortfarande laddar resurser, och "complete" när det är helt laddat. |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) En lista som innehåller alla stilmallar som explicit länkas in eller bäddas in i ett dokument. För HTML-dokument inkluderar detta externa stilmallar, inkluderade via HTML LINK‑elementet, och inbäddade STYLE‑element. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | textContent‑egenskapen för [`Node`](../node/)‑gränssnittet representerar textinnehållet i noden och dess underordnade. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | addEventListener()‑metoden i [`EventTarget `](../eventtarget/)‑gränssnittet ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild()-metoden i Node-gränssnittet lägger till en nod i slutet av listan med barn till en specificerad föräldranod. Om den angivna barnet är en referens till en befintlig nod i dokumentet, flyttar appendChild() den från sin nuvarande position till den nya positionen (det krävs inte att noden tas bort från sin föräldranod innan den läggs till i någon annan nod). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Metoden Document.createAttribute() skapar en ny attributnod och returnerar den. Objektet skapar en nod som implementerar [`Attr`](../attr/)‑gränssnittet. DOM‑en påtvingar inte vilken typ av attribut som kan läggas till ett specifikt element på detta sätt. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Metoden Document.createAttribute() skapar en ny attributnod och returnerar den. Objektet skapar en nod som implementerar [Attr](T:com.aspose.html.dom.Attr)‑gränssnittet. DOM‑implementeringen påtvingar inte vilken typ av attribut som kan läggas till ett specifikt element på detta sätt. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | Skapar en [`CDATASection`](../cdatasection/)‑nod vars värde är den angivna strängen. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | Skapar en [`Comment`](../comment/)‑nod med den angivna strängen. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | Skapar ett nytt tomt [`DocumentFragment`](../documentfragment/) där DOM‑noder kan läggas till för att bygga ett off‑screen DOM‑träd. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | Metoden returnerar ett [`DocumentType`](../documenttype/)‑objekt som antingen kan användas med DOMImplementation.createDocument vid dokumentskapande eller kan placeras i dokumentet via metoder som Node.insertBefore() eller Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | I ett HTML‑dokument skapar metoden document.createElement() HTML‑elementet som anges av tagName, eller ett [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/) om tagName inte känns igen. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | Skapar ett element med det angivna kvalificerade namnet och paket‑URI:n. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | Skapar ett EntityReference‑objekt. Dessutom, om den refererade entiteten är känd, görs barnlistan för EntityReference‑noden identisk med den för motsvarande Entity‑nod. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | Skapar ett [`Event`](../../com.aspose.html.dom.events/event/) av en typ som stöds av implementationen. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | Skapar ett parsat XPath‑uttryck med upplösta paket. Detta är användbart när ett uttryck ska återanvändas i en applikation eftersom det möjliggör att kompilera uttrycksssträngen till en mer effektiv intern form och förupplösa alla paketprefix som förekommer i uttrycket. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator)(Node) | Skapa en ny NodeIterator över delträdet som är rotat vid den angivna noden. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_1)(Node, long) | Skapa en ny NodeIterator över delträdet som är rotat vid den angivna noden. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Skapa en ny NodeIterator över delträdet som är rotat vid den angivna noden. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | Anpassar vilken DOM‑nod som helst för att lösa paket så att ett XPath‑uttryck enkelt kan utvärderas relativt till nodens kontext där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3‑metoden `lookupNamespaceURI` på noder för att lösa paket‑URI från ett givet prefix med den information som finns i nodens hierarki när lookupNamespaceURI anropas, och löser även korrekt det implicita xml‑prefixet. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | Skapar en ProcessingInstruction‑nod med det angivna namn‑ och data‑strängarna. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | Skapar en Text‑nod med den angivna strängen. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker)(Node) | Skapa en ny TreeWalker över delträdet som är rotat vid den angivna noden. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_1)(Node, long) | Skapa en ny TreeWalker över delträdet som är rotat vid den angivna noden. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Skapa en ny TreeWalker över delträdet som är rotat vid den angivna noden. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Skickar ett Event till den specificerade [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synkront) och anropar de påverkade EventListeners i rätt ordning. De vanliga händelsebehandlingsreglerna (inklusive fångst- och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Utvärderar en XPath‑uttryck‑String och returnerar ett resultat av den angivna typen om möjligt. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Document‑metoden getElementById() returnerar ett [`Element`](../element/)‑objekt som representerar det element vars id‑egenskap matchar den angivna strängen. Eftersom element‑ID:n måste vara unika om de anges, är de ett praktiskt sätt att snabbt få åtkomst till ett specifikt element. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | Metoden getElementsByClassName i `Document`‑gränssnittet returnerar ett array‑likt objekt med alla underordnade element som har alla angivna klassnamn. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | Metoden getElementsByTagName i `Document`‑gränssnittet returnerar en [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) med element som har det angivna taggnamnet. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | Returnerar en lista med element med det angivna taggnamnet som tillhör det angivna paketet. Hela dokumentet söks, inklusive rotnoden. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes()‑metoden i Node‑gränssnittet returnerar ett booleskt värde som indikerar om den givna [`Node`](../node/) har barnnoder eller inte. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | Importerar en nod från ett annat dokument till detta dokument, utan att ändra eller ta bort källnoden från originaldokumentet; denna metod skapar en ny kopia av källnoden. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore()-metoden i Node-gränssnittet infogar en nod före en referensnod som ett barn till en specificerad föräldranod. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace()-metoden i Node-gränssnittet accepterar ett paket-URI som argument. Den returnerar ett booleskt värde som är true om paketet är standardpaketet på den givna noden och false om det inte är det. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | isEqualNode()‑metoden i [`Node`](../node/)‑gränssnittet testar om två noder är lika. Två noder är lika när de har samma typ, definierande egenskaper (för element skulle detta vara deras ID, antal barn osv.), deras attribut matchar, osv. Den specifika uppsättningen av datapunkter som måste matcha varierar beroende på nodernas typer. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode()-metoden i Node-gränssnittet är ett äldre alias för ===-operatorn för strikt likhet. Det vill säga, den testar om två noder är samma (med andra ord, om de refererar till samma objekt). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI()-metoden i Node-gränssnittet tar ett prefix som parameter och returnerar paket-URI:n som är associerad med det på den givna noden om den finns (och null annars). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix()-metoden i Node-gränssnittet returnerar en sträng som innehåller prefixet för ett givet paket-URI, om det finns, och null annars. När flera prefix är möjliga returneras det första prefixet. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate)(RequestMessage) | Laddar dokumentet baserat på det angivna begäran‑objektet och ersätter det tidigare innehållet. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_4)(String) | Laddar dokumentet från den angivna Uniform Resource Locator (URL) till den aktuella instansen och ersätter det tidigare innehållet. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_1)(Url) | Laddar dokumentet från den angivna Uniform Resource Locator (URL) till den aktuella instansen och ersätter det tidigare innehållet. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_3)(Stream, String) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_2)(Stream, Url) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_6)(String, String) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_5)(String, Url) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Sätter alla [`Text`](../text/)‑noder i hela djupet av delträdet under denna Node, inklusive attributnoder, i ett "normalt" format där endast strukturen (t.ex. [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), och [`entity references`](../entityreference/)) separerar [`Text`](../text/)‑noder, d.v.s. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer (såsom XPointer‑uppslagningar [XPointer]) som beror på en viss dokumentträdstruktur ska användas. Om parametern "normalize-characters" för [`DOMConfiguration`](../../com.aspose.html/configuration/)‑objektet som är kopplat till [`Node.ownerDocument`](../node/ownerdocument/) är true, kommer denna metod även att fullständigt normalisera tecknen i Text‑noderna. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | Returnerar det första Elementet i dokumentet som matchar selektorn |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | Returnerar en NodeList med alla Element i dokumentet som matchar selektorn |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Metoden removeChild() i Node‑gränssnittet tar bort en barnnod från DOM och returnerar den borttagna noden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [renderTo](../../com.aspose.html.dom/document/renderto/)(IDevice) | Denna metod används för att rendera innehållet i det aktuella dokumentet till en specificerad grafisk enhet. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Ersätter barnnoden oldChild med newChild i listan av barn, och returnerar oldChild‑noden. Om newChild är ett [`DocumentFragment`](../documentfragment/)‑objekt ersätts oldChild av alla [`DocumentFragment`](../documentfragment/)‑barn, som infogas i samma ordning. Om newChild redan finns i trädet tas den först bort. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Returnerar en sträng som representerar detta objekt. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | Skriv en textsträng till ett dokumentflöde som öppnats med open(). Observera att funktionen kommer att skapa ett dokument som inte nödvändigtvis styrs av en DTD och därför kan producera ett ogiltigt resultat i dokumentets sammanhang. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | Skriv en textsträng följt av ett radbrytningstecken till ett dokumentflöde som öppnats med open(). Observera att funktionen kommer att skapa ett dokument som inte nödvändigtvis styrs av en DTD och därför kan producera ett ogiltigt resultat i dokumentets sammanhang. |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | Hämtar eller anger händelsehanterare för OnAbort‑händelsen. |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | Hämtar eller anger händelsehanterare för OnBlur‑händelsen. |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | Hämtar eller anger händelsehanterare för OnCancel‑händelsen. |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | Hämtar eller anger händelsehanterare för OnCanplay‑händelsen. |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | Hämtar eller anger händelsehanterare för OnCanPlayThrough‑händelsen. |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | Hämtar eller anger händelsehanterare för OnChange‑händelsen. |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | Hämtar eller anger händelsehanterare för OnClick‑händelsen. |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | Hämtar eller anger händelsehanterare för OnCueChange‑händelsen. |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | Hämtar eller anger händelsehanterare för OnDblClick‑händelsen. |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | Hämtar eller anger händelsehanterare för OnDurationChange‑händelsen. |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | Hämtar eller anger händelsehanterare för OnEmptied‑händelsen. |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | Hämtar eller anger händelsehanterare för OnEnded‑händelsen. |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | Hämtar eller anger händelsehanterare för OnError‑händelsen. |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | Hämtar eller anger händelsehanterare för OnFocus‑händelsen. |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | Hämtar eller anger händelsehanterare för OnInput‑händelsen. |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | Hämtar eller anger händelsehanterare för OnInvalid‑händelse. |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | Hämtar eller anger händelsehanterare för OnKeyDown‑händelse. |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | Hämtar eller anger händelsehanterare för OnKeyPress‑händelse. |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | Hämtar eller anger händelsehanterare för OnKeyUp‑händelse. |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | Hämtar eller anger händelsehanterare för OnLoad‑händelse. |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | Hämtar eller anger händelsehanterare för OnLoadedData‑händelse. |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | Hämtar eller anger händelsehanterare för OnLoadedMetadata‑händelse. |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | Hämtar eller anger händelsehanterare för OnLoadStart‑händelse. |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | Hämtar eller anger händelsehanterare för OnMouseDown‑händelse. |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | Hämtar eller anger händelsehanterare för OnMouseEnter‑händelse. |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | Hämtar eller anger händelsehanterare för OnMouseLeave‑händelse. |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | Hämtar eller anger händelsehanterare för OnMouseMove‑händelse. |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | Hämtar eller anger händelsehanterare för OnMouseOut‑händelse. |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | Hämtar eller anger händelsehanterare för OnMouseOver‑händelse. |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | Hämtar eller anger händelsehanterare för OnMouseUp‑händelse. |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | Hämtar eller anger händelsehanterare för OnMouseWheel‑händelse. |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | Hämtar eller anger händelsehanterare för OnPause‑händelse. |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | Hämtar eller anger händelsehanterare för OnPlay‑händelse. |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | Hämtar eller anger händelsehanterare för OnPlaying‑händelse. |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | Hämtar eller anger händelsehanterare för OnProgress‑händelse. |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | Hämtar eller anger händelsehanterare för OnRateChange‑händelse. |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | Hämtar eller anger händelsehanterare för OnReadyStateChange‑händelse. |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | Hämtar eller anger händelsehanterare för OnReset‑händelse. |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | Hämtar eller anger händelsehanterare för OnResize‑händelse. |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | Hämtar eller anger händelsehanterare för OnScroll‑händelse. |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | Hämtar eller anger händelsehanterare för OnSeeked‑händelsen. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | Hämtar eller anger händelsehanterare för OnSeeking‑händelsen. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | Hämtar eller anger händelsehanterare för OnSelect‑händelsen. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | Hämtar eller anger händelsehanterare för OnShow‑händelsen. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | Hämtar eller anger händelsehanterare för OnStalled‑händelsen. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | Hämtar eller anger händelsehanterare för OnSubmit‑händelsen. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | Hämtar eller anger händelsehanterare för OnSuspend‑händelsen. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | Hämtar eller anger händelsehanterare för OnTimeUpdate‑händelsen. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | Hämtar eller anger händelsehanterare för OnToggle‑händelsen. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | Hämtar eller anger händelsehanterare för OnVolumeChange‑händelsen. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | Hämtar eller anger händelsehanterare för OnWaiting‑händelsen. |

### Se även

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
