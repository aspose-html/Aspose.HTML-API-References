---
title: "HTMLDocument klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.HTMLDocument klass. Representerar ett HTML‑dokument. Alla HTML‑objekt på toppnivå läggs till i detta objekt. Denna klass representerar HTML‑sidan som vi ser i webbläsaren. Alla formulär, tabeller, skript … läggs till HTML‑sidan via klassens gränssnitt. HTMLDocument är en HTML‑implementation av det mest generella Document‑gränssnittet och båda är kärnan eller rotpunkten i DOM – Document Object Model. Dessa koncept är i full överensstämmelse med officiella webb­utvecklingsprinciper eller standarder. För webb­utveckling kan du generellt betrakta HTMLDocument som ett alias för Document som HTMLDocument är baserat på."
type: docs

url: /sv/java/com.aspose.html/htmldocument/
---
## HTMLDocument class

Representerar ett HTML‑dokument. Alla HTML‑objekt på toppnivå läggs till i detta objekt. Denna klass representerar HTML‑sidan som vi ser i webbläsaren. Alla formulär, tabeller, skript, … läggs till på HTML‑sidan via klassens gränssnitt. [HTMLDocument](https://dom.spec.whatwg.org/#ref-for-dom-domimplementation-createhtmldocument) är HTML‑implementeringen av det mest generella [Document](https://dom.spec.whatwg.org/#document)‑gränssnittet och båda är kärnan eller rotpunkten för [DOM](https://dom.spec.whatwg.org/) – Document Object Model. Dessa begrepp är i full överensstämmelse med officiella webb‑utvecklingsgrunder eller standarder. För webb‑utveckling kan du i allmänhet betrakta HTMLDocument som ett alias för Document, på vilket HTMLDocument är baserat.

```java
public class HTMLDocument : Document, IDocumentCSS
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HTMLDocument](htmldocument/#constructor)() | HTMLDocument‑konstruktorn skapar ett nytt HTML‑dokumentobjekt som är en webbsida laddad i webbläsaren och fungerar som en ingångspunkt till sidans innehåll. |
| [HTMLDocument](htmldocument/#constructor_1)(Configuration) | HTMLDocument‑konstruktorn skapar ett nytt HTML‑dokumentobjekt som är en webbsida laddad i webbläsaren och fungerar som en ingångspunkt till sidans innehåll. |
| [HTMLDocument](htmldocument/#constructor_2)(RequestMessage) | Skapar ett HTML‑dokument från [`RequestMessage`](../../com.aspose.html.net/requestmessage/)‑objektet. |
| [HTMLDocument](htmldocument/#constructor_10)(String) | Läser in HTML‑dokumentet från en adress. |
| [HTMLDocument](htmldocument/#constructor_4)(Url) | Läser in HTML‑dokumentet från en URL. |
| [HTMLDocument](htmldocument/#constructor_3)(RequestMessage, Configuration) | Skapar ett HTML‑dokument från [RequestMessage](T:com.aspose.html.net.RequestMessage)‑objektet. |
| [HTMLDocument](htmldocument/#constructor_8)(Stream, String) | Skapar ett HTML‑dokument från ett [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-innehåll med angiven bas‑uri som används för att lösa relativa resurssökvägar. |
| [HTMLDocument](htmldocument/#constructor_6)(Stream, Url) | Skapar ett HTML‑dokument från ett [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-innehåll med angiven bas‑uri som används för att lösa relativa resurssökvägar. |
| [HTMLDocument](htmldocument/#constructor_11)(String, Configuration) | Läser in HTML‑dokumentet från en adress med angivna miljökonfigurationsinställningar. |
| [HTMLDocument](htmldocument/#constructor_14)(String, String) | Skapar ett HTML‑dokument från ett String‑innehåll med angiven bas‑uri. |
| [HTMLDocument](htmldocument/#constructor_12)(String, Url) | Skapar ett HTML‑dokument från ett String‑innehåll med angiven bas‑uri. |
| [HTMLDocument](htmldocument/#constructor_5)(Url, Configuration) | Läser in HTML‑dokumentet från en URL med angivna miljökonfigurationsinställningar. |
| [HTMLDocument](htmldocument/#constructor_9)(Stream, String, Configuration) | Skapar ett HTML‑dokument från ett [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-innehåll med angiven bas‑uri och miljökonfigurationsinställningar. |
| [HTMLDocument](htmldocument/#constructor_7)(Stream, Url, Configuration) | Skapar ett HTML‑dokument från ett [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream)-innehåll med angiven bas‑uri och miljökonfigurationsinställningar. |
| [HTMLDocument](htmldocument/#constructor_15)(String, String, Configuration) | Skapar ett HTML‑dokument från ett String‑innehåll med angiven bas‑uri och miljökonfigurationsinställningar. |
| [HTMLDocument](htmldocument/#constructor_13)(String, Url, Configuration) | Skapar ett HTML‑dokument från ett String‑innehåll med angiven bas‑uri och miljökonfigurationsinställningar. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getAnchors](../../com.aspose.html/htmldocument/anchors/) En samling av alla ankare (`A`)‑element i ett dokument med ett värde för `name`‑attributet. Av bakåtkompatibilitetsskäl innehåller den returnerade mängden ankare endast de ankare som skapats med `name`‑attributet, inte de som skapats med `id`‑attributet. Observera att i [[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801)] har `name`‑attributet (se avsnitt 4.10) ingen semantik och endast finns för äldre användaragenter: `id`‑attributet används istället. Användare bör föredra iterator‑mekanismerna som tillhandahålls av [[DOM Level 2 Traversal](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)] istället. |
| [getApplets](../../com.aspose.html/htmldocument/applets/) En samling av alla `OBJECT`‑element som innehåller applets och `APPLET`‑element (föråldrade) i ett dokument. |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) Den absoluta bas‑URI:n för denna nod eller null om implementationen inte kunde erhålla en absolut URI. |
[getBody]
[setBody] The element that contains the content for the document. In documents with `BODY` contents, returns the `BODY`element. In frameset documents, this returns the outermost `FRAMESET` element. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) Hämtar dokumentets kodning. |
| [getCharset](../../com.aspose.html.dom/document/charset/) Hämtar dokumentets kodning. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) Returnerar det aktuella antalet elementnoder som är barn till detta element. 0 om detta element inte har några barnnoder av nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Den skrivskyddade childNodes‑egenskapen i Node‑gränssnittet returnerar en levande [`NodeList`](../../com.aspose.html.collections/nodelist/) av barnnoder för det givna elementet där den första barnnoden får index 0. Barnnoder inkluderar element, text och kommentarer. |
| [getChildren](../../com.aspose.html.dom/document/children/) Returnerar de underordnade elementen. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) Hämtar dokumentets innehållstyp. |
| [getContext](../../com.aspose.html.dom/document/context/) Hämtar det aktuella bläddringssammanhanget. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) defaultView IDL-attributet för Document‑gränssnittet ska, vid hämtning, returnera detta dokuments bläddringssammanhangs WindowProxy‑objekt, om detta dokument har ett associerat bläddringssammanhang, annars null. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) Den Document Type Declaration som är associerad med detta dokument. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) Detta är ett bekvämt attribut som tillåter direkt åtkomst till den undernod som är dokumentets dokumentelement. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) Platsen för dokumentet eller null om den är odefinierad eller om dokumentet skapades med DOMImplementation.createDocument. |
| [getDomain](../../com.aspose.html/htmldocument/domain/) Domännamnet för servern som levererade dokumentet, eller `null` om servern inte kan identifieras med ett domännamn. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Den skrivskyddade firstChild‑egenskapen i [`Node`](../../com.aspose.html.dom/node/)‑gränssnittet returnerar nodens första barn i trädet, eller null om noden saknar barn. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) Returnerar det första underordnade elementnodet för detta element. null om detta element inte har några underordnade element. |
| [getForms](../../com.aspose.html/htmldocument/forms/) En samling av alla formulär i ett dokument. |
| [getImages](../../com.aspose.html/htmldocument/images/) En samling av alla `IMG`‑element i ett dokument. Beteendet är begränsat till `IMG`‑element för bakåtkompatibilitet. Enligt [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)] kan författare använda `OBJECT`‑elementet eller `IMG`‑elementet för att inkludera bilder. Därför rekommenderas det att inte använda detta attribut för att hitta bilder i dokumentet utan att använda `getElementsByTagName` med HTML 4.01 eller `getElementsByTagNameNS` med XHTML 1.0. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) DOMImplementation‑objektet som hanterar detta dokument. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) Hämtar dokumentets kodning. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Den skrivskyddade lastChild‑egenskapen i [`Node`](../../com.aspose.html.dom/node/)‑gränssnittet returnerar den sista barnet till noden. Om dess förälder är ett element är barnet vanligtvis ett element, en textnod eller en kommentarnod. Den returnerar null om det inte finns några barn‑element. |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) Returnerar det sista underordnade elementnodet för detta element. null om detta element inte har några underordnade element. |
| [getLinks](../../com.aspose.html/htmldocument/links/) En samling av alla `AREA`‑element och ankare (`A`)‑element i ett dokument med ett värde för `href`‑attributet. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Returnerar den lokala delen av det kvalificerade namnet för denna nod. För noder av någon annan typ än [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) och [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) samt noder skapade med en DOM Level 1‑metod, såsom [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/), är detta alltid null. |
| [getLocation](../../com.aspose.html.dom/document/location/) Platsen för dokumentet. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI‑egenskapen som är skrivskyddad returnerar elementets paket‑URI, eller null om elementet inte är i ett paket. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) Returnerar nästa syskon‑elementnod för detta element. null om detta element inte har några element‑syskonnoder som kommer efter detta i dokumentträdet. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Den skrivskyddade nextSibling‑egenskapen i [`Node`](../../com.aspose.html.dom/node/)‑gränssnittet returnerar noden som omedelbart följer den angivna i dess förälders [`childNodes`](../../com.aspose.html.dom/node/childnodes/), eller returnerar null om den angivna noden är det sista barnet i förälderelementet. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) Namnet på denna nod, beroende på dess typ. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) En kod som representerar typen av det underliggande objektet. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | nodeValue‑egenskapen i [`Node `](../../com.aspose.html.dom/node/)‑gränssnittet returnerar eller sätter värdet för den aktuella noden. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) Hämtar dokumentets ursprung. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) Hämtar ägardokumentet. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Den skrivskyddade parentElement‑egenskapen i [`Node`](../../com.aspose.html.dom/node/)‑gränssnittet returnerar DOM‑nodens föräldra‑[`Element`](../../com.aspose.html.dom/element/), eller null om noden antingen saknar förälder eller dess förälder inte är ett DOM‑Element. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Den skrivskyddade parentNode‑egenskapen i Node‑gränssnittet returnerar den angivna nodens förälder i DOM‑trädet. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix‑egenskapen som är skrivskyddad returnerar paket‑prefixet för det angivna elementet, eller null om inget prefix har angetts. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) Returnerar föregående syskon‑elementnod för detta element. null om detta element inte har några element‑syskonnoder som kommer före detta i dokumentträdet. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Den skrivskyddade previousSibling‑egenskapen i [`Node`](../../com.aspose.html.dom/node/)‑gränssnittet returnerar noden som omedelbart föregår den angivna i dess förälders [`childNodes`](../../com.aspose.html.dom/node/firstchild/)‑lista, eller null om den angivna noden är den första i listan. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) Returnerar dokumentets lässtatus. "loading" medan dokumentet laddas, "interactive" när det har slutfört parsning men fortfarande laddar resurser, och "complete" när det är helt inläst. |
| [getReferrer](../../com.aspose.html/htmldocument/referrer/) Returnerar URI‑en [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)] för sidan som länkat till denna sida. Värdet är en tom String om användaren navigerade till sidan direkt (inte via en länk, utan till exempel via ett bokmärke). |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) En lista som innehåller alla stilmallar som uttryckligen länkas in i eller bäddas in i ett dokument. För HTML-dokument inkluderar detta externa stilmallar, inkluderade via HTML LINK-elementet, och inbäddade STYLE-element. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | textContent‑egenskapen för [`Node`](../../com.aspose.html.dom/node/)‑gränssnittet representerar nodens textinnehåll och dess underordnade. |
[getTitle]
[setTitle] The title of a document as specified by the `TITLE` element in the head of the document. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | addEventListener()-metoden i [`EventTarget `](../../com.aspose.html.dom/eventtarget/)‑gränssnittet ställer in en funktion som kommer att anropas närhelst det specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild()-metoden i Node-gränssnittet lägger till en nod i slutet av listan med barn till en angiven föräldranod. Om det givna barnet är en referens till en befintlig nod i dokumentet, flyttar appendChild() den från sin nuvarande position till den nya positionen (det krävs inte att noden tas bort från sin föräldranod innan den läggs till i någon annan nod). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode()-metoden i Node-gränssnittet returnerar en duplikat av den nod som metoden anropades på. Dess parameter styr om underträdet som finns i en nod också klonas eller inte. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Metoden Document.createAttribute() skapar en ny attributnod och returnerar den. Det skapade objektet är en nod som implementerar [`Attr`](../../com.aspose.html.dom/attr/)‑gränssnittet. DOM‑implementeringen påtvingar inte vilken typ av attribut som kan läggas till ett specifikt element på detta sätt. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Metoden Document.createAttribute() skapar en ny attributnod och returnerar den. Det skapade objektet är en nod som implementerar [Attr](T:com.aspose.html.dom.Attr)‑gränssnittet. DOM‑implementeringen påtvingar inte vilken typ av attribut som kan läggas till ett specifikt element på detta sätt. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | Skapar en [`CDATASection`](../../com.aspose.html.dom/cdatasection/)‑nod vars värde är den angivna strängen. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | Skapar en [`Comment`](../../com.aspose.html.dom/comment/)‑nod med den angivna strängen. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | Skapar ett nytt tomt [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) där DOM‑noder kan läggas till för att bygga ett offscreen‑DOM‑träd. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | Metoden returnerar ett [`DocumentType`](../../com.aspose.html.dom/documenttype/)‑objekt som antingen kan användas med DOMImplementation.createDocument vid dokumentets skapande eller kan placeras i dokumentet via metoder som Node.insertBefore() eller Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | I ett HTML‑dokument skapar metoden document.createElement() HTML‑elementet som anges av tagName, eller ett [`HTMLUnknownElement`](../htmlunknownelement/) om tagName inte känns igen. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | Skapar ett element med det angivna kvalificerade namnet och paket‑URI:n. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | Skapar ett EntityReference‑objekt. Dessutom, om den refererade enheten är känd, görs barnlistan för EntityReference‑noden identisk med den för motsvarande Entity‑nod. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | Skapar ett [`Event`](../../com.aspose.html.dom.events/event/) av en typ som stöds av implementationen. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | Skapar ett analyserat XPath‑uttryck med upplösta paket. Detta är användbart när ett uttryck ska återanvändas i en applikation eftersom det möjliggör att kompilera uttryckets sträng till en mer effektiv intern form och förhandslösa alla paketprefix som förekommer i uttrycket. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node) | Skapa en ny NodeIterator över delträdet som har den angivna noden som rot. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long) | Skapa en ny NodeIterator över delträdet som har den angivna noden som rot. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Skapa en ny NodeIterator över delträdet som har den angivna noden som rot. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | Anpassar vilken DOM‑nod som helst för att lösa paket så att ett XPath‑uttryck enkelt kan utvärderas relativt till nodens kontext där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3‑metoden `lookupNamespaceURI` på noder för att lösa paket‑URI från ett givet prefix med den aktuella informationen som finns i nodens hierarki när lookupNamespaceURI anropas, och löser även korrekt det implicita xml‑prefixet. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | Skapar en ProcessingInstruction‑nod med det angivna namn‑ och datatsträngarna. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | Skapar en Text‑nod med den angivna strängen. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node) | Skapa en ny TreeWalker över delträdet som har den angivna noden som rot. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long) | Skapa en ny TreeWalker över delträdet som har den angivna noden som rot. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | Skapa en ny TreeWalker över delträdet som har den angivna noden som rot. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Skickar en händelse till den specificerade [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synkront) och anropar de berörda EventListeners i rätt ordning. De vanliga reglerna för händelsebehandling (inklusive fångst- och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Utvärderar en XPath‑uttryck‑sträng och returnerar ett resultat av den angivna typen om möjligt. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Document‑metoden getElementById() returnerar ett [`Element`](../../com.aspose.html.dom/element/)‑objekt som representerar elementet vars id‑egenskap matchar den angivna strängen. Eftersom element‑ID:n måste vara unika om de anges, är de ett praktiskt sätt att snabbt få åtkomst till ett specifikt element. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | Metoden getElementsByClassName i [`Document`](../../com.aspose.html.dom/document/)‑gränssnittet returnerar ett array‑likt objekt med alla underordnade element som har alla de angivna klassnamnen. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | Metoden getElementsByTagName i [`Document`](../../com.aspose.html.dom/document/)‑gränssnittet returnerar en [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) med element som har det angivna taggnamnet. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | Returnerar en lista med element med det angivna taggnamnet som tillhör det angivna paketet. Hela dokumentet genomsöks, inklusive rotnoden. |
| [getOverrideStyle](../../com.aspose.html/htmldocument/getoverridestyle/)(Element, String) | Denna metod används för att hämta override‑stildeklarationen för ett specificerat element och ett specificerat pseudo‑element. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes()-metoden i Node-gränssnittet returnerar ett booleskt värde som indikerar om den givna [`Node`](../../com.aspose.html.dom/node/) har barnnoder eller inte. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | Importerar en nod från ett annat dokument till detta dokument, utan att ändra eller ta bort källnoden från originaldokumentet; denna metod skapar en ny kopia av källnoden. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore()-metoden i Node-gränssnittet infogar en nod före en referensnod som ett barn till en specificerad föräldranod. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace()-metoden i Node-gränssnittet accepterar ett paket-URI som argument. Den returnerar ett booleskt värde som är true om paketet är standardpaketet på den givna noden och false om det inte är det. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | isEqualNode()-metoden i [`Node`](../../com.aspose.html.dom/node/)-gränssnittet testar om två noder är lika. Två noder är lika när de har samma typ, definierande egenskaper (för element skulle detta vara deras ID, antal barn osv.), deras attribut matchar och så vidare. Den specifika uppsättningen av datapunkter som måste matcha varierar beroende på nodernas typer. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode()-metoden i Node-gränssnittet är ett äldre alias för ===-operatorn för strikt likhet. Den testar alltså om två noder är desamma (med andra ord, om de refererar till samma objekt). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI()-metoden i Node-gränssnittet tar ett prefix som parameter och returnerar paket-URI:n som är associerad med det på den givna noden om den hittas (annars null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix()-metoden i Node-gränssnittet returnerar en sträng som innehåller prefixet för ett givet paket-URI, om det finns, annars null. När flera prefix är möjliga returneras det första prefixet. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(RequestMessage) | Laddar dokumentet baserat på det angivna begärande objektet och ersätter det tidigare innehållet. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String) | Läser in dokumentet på den angivna Uniform Resource Locator (URL) i den aktuella instansen och ersätter det tidigare innehållet. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Url) | Läser in dokumentet på den angivna Uniform Resource Locator (URL) i den aktuella instansen och ersätter det tidigare innehållet. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, String) | Läser in dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, och ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, Url) | Läser in dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, och ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, String) | Läser in dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, och ersätter det tidigare innehållet. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, Url) | Läser in dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, och ersätter det tidigare innehållet. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Sätter alla [`Text`](../../com.aspose.html.dom/text/) noder i hela djupet av delträdet under denna Node, inklusive attributnoder, i ett "normalt" format där endast strukturen (t.ex. [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), och [`entity references`](../../com.aspose.html.dom/entityreference/)) separerar [`Text`](../../com.aspose.html.dom/text/) noder, d.v.s. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer (såsom XPointer‑uppslagningar [XPointer]) som beror på en viss dokumentträdstruktur ska användas. Om parametern "normalize-characters" för [`DOMConfiguration`](../configuration/)‑objektet som är bifogat till [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) är sann, kommer denna metod även att helt normalisera tecknen i Text‑noderna. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | Returnerar det första Element i dokumentet som matchar selektorn |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | Returnerar en NodeList med alla Element i dokumentet som matchar selektorn |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Metoden removeChild() i Node‑gränssnittet tar bort en barnnod från DOM och returnerar den borttagna noden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [renderTo](../../com.aspose.html/htmldocument/renderto/)(IDevice) | Denna metod används för att skriva ut innehållet i det aktuella dokumentet till den angivna enheten. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Ersätter barnnoden oldChild med newChild i listan över barn och returnerar oldChild‑noden. Om newChild är ett [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/)‑objekt, ersätts oldChild med alla [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/)‑barn, som infogas i samma ordning. Om newChild redan finns i trädet tas den först bort. |
| [save](../../com.aspose.html/htmldocument/save/#save)(ResourceHandler) | Sparar dokumentets innehåll och resurser med hjälp av [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_10)(String) | Sparar dokumentet till en lokal fil som anges av sökvägen. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn konstrueras som: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_5)(Url) | Sparar dokumentet till en lokal fil som anges av url. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp, vars namn kommer att konstrueras som output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_1)(ResourceHandler, HTMLSaveFormat) | Sparar dokumentets innehåll och resurser med hjälp av [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_2)(ResourceHandler, HTMLSaveOptions) | Sparar dokumentets innehåll och resurser med hjälp av [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_3)(ResourceHandler, MarkdownSaveOptions) | Sparar dokumentets innehåll och resurser med hjälp av [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_4)(ResourceHandler, MHTMLSaveOptions) | Sparar dokumentets innehåll och resurser med hjälp av [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_11)(String, HTMLSaveFormat) | Sparar dokumentet till en lokal fil som anges av sökväg. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp, vars namn kommer att konstrueras som output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_12)(String, HTMLSaveOptions) | Sparar dokumentet till en lokal fil som anges av sökvägen. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn konstrueras som: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_13)(String, MarkdownSaveOptions) | Sparar dokumentet till en lokal fil som anges av sökvägen. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn konstrueras som: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_14)(String, MHTMLSaveOptions) | Sparar dokumentet till en lokal fil som anges av sökvägen. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn konstrueras som: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_6)(Url, HTMLSaveFormat) | Sparar dokumentet till en lokal fil som anges av url. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp, vars namn kommer att konstrueras som output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_7)(Url, HTMLSaveOptions) | Sparar dokumentet till en lokal fil som anges av url. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_8)(Url, MarkdownSaveOptions) | Sparar dokumentet till en lokal fil som anges av url. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_9)(Url, MHTMLSaveOptions) | Sparar dokumentet till en lokal fil som anges av url. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files". |
| [toString](../../com.aspose.html.dom/node/toString/)() | Returnerar en sträng som representerar detta objekt. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | Skriv en textsträng till ett dokumentflöde som öppnats med open(). Observera att funktionen kan skapa ett dokument som inte nödvändigtvis styrs av en DTD och därför kan ge ett ogiltigt resultat i dokumentets sammanhang. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | Skriv en textsträng följd av ett radbrytningstecken till ett dokumentflöde som öppnats med open(). Observera att funktionen kan skapa ett dokument som inte nödvändigtvis styrs av en DTD och därför kan ge ett ogiltigt resultat i dokumentets sammanhang. |

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

## Anmärkningar

Mer information om HTMLDocument, Document och DOM kan erhållas i populära resurser för webbutveckling:

[General Document interface](https://developer.mozilla.org/en-US/docs/Web/API/Document).[Html specific HTMLDocument interface](https://developer.mozilla.org/en-US/docs/Web/API/HTMLDocument).[What is the HTML DOM](https://www.w3schools.com/js/js_htmldom.asp).

Standardreferens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exempel

```java
    // Skapa en instans av ett HTML-dokument
	using (var document = new HTMLDocument())
      {
        // Skapa ett style-element och tilldela den gröna färgen för alla element med klassnamn lika med 'gr'.
        var style = document.CreateElement("style");
        style.TextContent = ".gr { color: green }";

        // Hitta dokumentets header-element och lägg till style-elementet i headern
        var head = document.GetElementsByTagName("head").First();
        head.AppendChild(style);

        // Skapa ett paragraf-element med klassnamn 'gr'.
        var p = (HTMLParagraphElement)document.CreateElement("p");
        p.ClassName = "gr";

        // Skapa en textnod
        var text = document.CreateTextNode("Hello World!!");

        // Lägg till textnoden i paragrafen
        p.AppendChild(text);

        // Lägg till paragrafen i dokumentets body-element
        document.Body.AppendChild(p);

        // Spara HTML-dokumentet till en fil 
        document.Save(Path.Combine(OutputDir, "using-dom.html"));

        // Skapa en instans av PDF-utdataenheten och rendera dokumentet till denna enhet
        using (var device = new PdfDevice(Path.Combine(OutputDir, "using-dom.pdf")))
        {
          // Rendera HTML till PDF
          document.RenderTo(device);
        }
      }       
```

### Se även

* class [Document](../../com.aspose.html.dom/document/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
