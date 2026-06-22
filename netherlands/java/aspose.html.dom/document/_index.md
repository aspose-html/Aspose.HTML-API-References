---
title: "Document‑klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.Document class. Het Document vertegenwoordigt het volledige HTML‑, XML‑ of SVG‑document. Conceptueel is het de wortel van de documentboom en biedt het primaire toegang tot de gegevens van het document."
type: docs

url: /nl/java/com.aspose.html.dom/document/
---
## Document class

Het Document vertegenwoordigt het volledige HTML-, XML- of SVG-document. Conceptueel is het de wortel van de documentboom en biedt het primaire toegang tot de gegevens van het document.

```java
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) De absolute basis‑URI van dit knooppunt of null als de implementatie geen absolute URI kon verkrijgen. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) Haalt de codering van het document op. |
| [getCharset](../../com.aspose.html.dom/document/charset/) Haalt de codering van het document op. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) Retourneert het huidige aantal element‑knooppunten dat kinderen zijn van dit element. 0 als dit element geen kind‑knooppunten heeft van nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) De alleen-lezen childNodes-eigenschap van de Node-interface geeft een live [`NodeList`](../../com.aspose.html.collections/nodelist/) van kindknooppunten van het opgegeven element waarbij het eerste kindknooppunt index 0 krijgt. Kindknooppunten omvatten elementen, tekst en commentaren. |
| [getChildren](../../com.aspose.html.dom/document/children/) Retourneert de kindelementen. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) Haalt het documentinhoudtype op. |
| [getContext](../../com.aspose.html.dom/document/context/) Haalt de huidige browse-context op. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) Het defaultView IDL-attribuut van de Document-interface moet bij opvragen dit Document's browsing context's WindowProxy-object retourneren, als dit Document een gekoppelde browsing context heeft, of anders null. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) De Document Type Declaration die aan dit document is gekoppeld. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) Dit is een gemakattribuut dat directe toegang biedt tot het kindknooppunt dat het documentelement van het document is. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) De locatie van het document of null als ongedefinieerd of als het Document is gemaakt met DOMImplementation.createDocument. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) De alleen-lezen firstChild eigenschap van de [`Node`](../node/) interface retourneert het eerste kind van de node in de boom, of null als de node geen kinderen heeft. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) Retourneert het eerste kindelementknooppunt van dit element. null als dit element geen kindelementen heeft. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) Het DOMImplementation-object dat dit document verwerkt. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) Haalt de codering van het document op. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) De alleen-lezen lastChild eigenschap van de [`Node`](../node/) interface retourneert het laatste kind van de node. Als de ouder een element is, dan is het kind doorgaans een elementnode, een tekstnode of een commentaarnode. Het retourneert null als er geen kindelementen zijn. |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) Retourneert het laatste kindelementknooppunt van dit element. null als dit element geen kindelementen heeft. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Retourneert het lokale deel van de gekwalificeerde naam van dit knooppunt. Voor knooppunten van elk type anders dan [`ELEMENT_NODE`](../node/element_node/) en [`ATTRIBUTE_NODE`](../node/attribute_node/) en knooppunten die zijn gemaakt met een DOM Level 1‑methode, zoals [`Document.createElement()`](./createelement/), is dit altijd null. |
| [getLocation](../../com.aspose.html.dom/document/location/) De locatie van het document. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) De alleen-lezen eigenschap Element.packageURI retourneert de pakket-URI van het element, of null als het element zich niet in een pakket bevindt. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) Retourneert het volgende broerelementknooppunt van dit element. null als dit element geen elementbroer‑knooppunten heeft die na dit knooppunt in de documentboom komen. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) De alleen-lezen nextSibling eigenschap van de [`Node`](../node/) interface retourneert de node die direct volgt op de opgegeven node in de [`childNodes`](../node/childnodes/) van hun ouder, of retourneert null als de opgegeven node het laatste kind in het bovenliggende element is. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) De naam van dit knooppunt, afhankelijk van het type. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) Een code die het type van het onderliggende object vertegenwoordigt. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | De nodeValue‑eigenschap van de [`Node `](../node/)interface geeft de waarde van het huidige knooppunt terug of stelt deze in. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) Haalt de oorsprong van het document op. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) Haalt het eigendocument op. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) De alleen-lezen parentElement eigenschap van de [`Node`](../node/) interface retourneert de bovenliggende [`Element`](../element/) van de DOM-node, of null als de node geen ouder heeft, of als de ouder geen DOM Element is. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) De alleen-lezen parentNode-eigenschap van de Node-interface retourneert de ouder van het opgegeven knooppunt in de DOM-boom. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | De alleen-lezen eigenschap prefix retourneert het pakket‑prefix van het opgegeven element, of null als er geen prefix is opgegeven. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) Retourneert het vorige broerelementknooppunt van dit element. null als dit element geen elementbroer‑knooppunten heeft die vóór dit knooppunt in de documentboom komen. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) De alleen-lezen previousSibling eigenschap van de [`Node`](../node/) interface retourneert de node die direct voorafgaat aan de opgegeven node in de [`childNodes`](../node/firstchild/) lijst van de ouder, of null als de opgegeven node de eerste in die lijst is. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) Retourneert de gereedheid van het document. De "loading" terwijl het Document wordt geladen, "interactive" zodra het klaar is met parseren maar nog sub‑resources laadt, en "complete" zodra het volledig is geladen. |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) Een lijst met alle stijlbladen die expliciet zijn gekoppeld aan of ingebed in een document. Voor HTML-documenten omvat dit externe stijlbladen, opgenomen via het HTML LINK-element, en inline STYLE-elementen. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | De textContent‑eigenschap van de [`Node`](../node/) interface vertegenwoordigt de tekstinhoud van het knooppunt en zijn afstammelingen. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | De addEventListener() methode van de [`EventTarget `](../eventtarget/) interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | De addEventListener()‑methode van de [EventTarget](T:com.aspose.html.dom.EventTarget)‑interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | De addEventListener()‑methode van de [EventTarget](T:com.aspose.html.dom.EventTarget)‑interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | De appendChild()‑methode van de Node‑interface voegt een knoop toe aan het einde van de lijst met kinderen van een opgegeven bovenliggende knoop. Als het opgegeven kind een verwijzing is naar een bestaande knoop in het document, verplaatst appendChild() deze van zijn huidige positie naar de nieuwe positie (er is geen vereiste om de knoop van zijn bovenliggende knoop te verwijderen voordat hij aan een andere knoop wordt toegevoegd). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | De Document.createAttribute()‑methode maakt een nieuw attribuutknooppunt aan en retourneert dit. Het object creëert een knooppunt dat de [`Attr`](../attr/) interface implementeert. De DOM dwingt niet af welk type attributen op deze manier aan een bepaald element kan worden toegevoegd. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | De Document.createAttribute()‑methode maakt een nieuw attribuutknooppunt aan en retourneert dit. Het object creëert een knooppunt dat de [Attr](T:com.aspose.html.dom.Attr) interface implementeert. De DOM dwingt niet af welk type attributen op deze manier aan een bepaald element kan worden toegevoegd. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | Maakt een [`CDATASection`](../cdatasection/) knooppunt aan waarvan de waarde de opgegeven String is. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | Maakt een [`Comment`](../comment/) knooppunt aan met de opgegeven String. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | Maakt een nieuw leeg [`DocumentFragment`](../documentfragment/) aan waarin DOM‑knooppunten kunnen worden toegevoegd om een off‑screen DOM‑boom te bouwen. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | De methode retourneert een [`DocumentType`](../documenttype/) object dat kan worden gebruikt met DOMImplementation.createDocument bij het aanmaken van een document of dat in het document kan worden geplaatst via methoden zoals Node.insertBefore() of Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | In een HTML-document maakt de document.createElement()‑methode het HTML‑element aan dat door tagName wordt gespecificeerd, of een [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/) als tagName niet wordt herkend. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | Maakt een element aan met de opgegeven gekwalificeerde naam en pakket‑URI. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | Maakt een EntityReference‑object aan. Bovendien, als de gerefereerde entiteit bekend is, wordt de kindlijst van het EntityReference‑knooppunt gelijk gemaakt aan die van het overeenkomstige Entity‑knooppunt. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | Maakt een [`Event`](../../com.aspose.html.dom.events/event/) van een type dat door de implementatie wordt ondersteund. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | Maakt een geparseerde XPath‑expressie met opgeloste pakketten. Dit is nuttig wanneer een expressie opnieuw wordt gebruikt in een toepassing, omdat het mogelijk maakt de expressie‑String te compileren naar een efficiëntere interne vorm en alle pakket‑prefixen die in de expressie voorkomen vooraf op te lossen. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator)(Node) | Maak een nieuwe NodeIterator over de subboom die is geworteld bij het opgegeven knooppunt. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_1)(Node, long) | Maak een nieuwe NodeIterator over de subboom die is geworteld bij het opgegeven knooppunt. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Maak een nieuwe NodeIterator over de subboom die is geworteld bij het opgegeven knooppunt. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | Past elk DOM‑knooppunt aan om pakketten op te lossen zodat een XPath‑expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waarin het in het document verscheen. Deze adapter werkt zoals de DOM Level 3‑methode `lookupNamespaceURI` op knooppunten bij het oplossen van de packageURI vanuit een gegeven prefix met behulp van de huidige informatie die beschikbaar is in de hiërarchie van het knooppunt op het moment dat lookupNamespaceURI wordt aangeroepen, en lost ook de impliciete xml‑prefix correct op. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | Maakt een ProcessingInstruction‑knooppunt aan met de opgegeven naam‑ en data‑Strings. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | Maakt een Text‑knooppunt aan met de opgegeven String. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker)(Node) | Maak een nieuwe TreeWalker over de subboom die is geworteld bij het opgegeven knooppunt. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_1)(Node, long) | Maak een nieuwe TreeWalker over de subboom die is geworteld bij het opgegeven knooppunt. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Maak een nieuwe TreeWalker over de subboom die is geworteld bij het opgegeven knooppunt. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Verzendt een Event naar de opgegeven [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchroon) en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor gebeurtenisverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Voert toepassingsspecifieke taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet‑beheerde bronnen. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Evalueert een XPath‑expressie‑String en retourneert een resultaat van het opgegeven type indien mogelijk. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | De Document‑methode getElementById() retourneert een [`Element`](../element/) object dat het element vertegenwoordigt waarvan de id‑eigenschap overeenkomt met de opgegeven String. Aangezien element‑ID’s uniek moeten zijn indien opgegeven, is dit een handige manier om snel toegang te krijgen tot een specifiek element. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | De getElementsByClassName‑methode van de `Document`‑interface retourneert een array‑achtig object van alle kindelementen die alle opgegeven klasse‑naam(en) hebben. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | De getElementsByTagName‑methode van de `Document`‑interface retourneert een [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) van elementen met de opgegeven tag‑naam. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | Retourneert een lijst van elementen met de opgegeven tag‑naam die tot het opgegeven pakket behoren. Het volledige document wordt doorzocht, inclusief het root‑knooppunt. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | De hasChildNodes() methode van de Node interface retourneert een booleaanse waarde die aangeeft of de gegeven [`Node`](../node/) kindnodes heeft of niet. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | Importeert een knooppunt van een ander document naar dit document, zonder het bronknooppunt in het oorspronkelijke document te wijzigen of te verwijderen; deze methode maakt een nieuwe kopie van het bronknooppunt. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | De insertBefore()‑methode van de Node‑interface voegt een knoop in vóór een referentieknoop als kind van een opgegeven bovenliggende knoop. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | De isDefaultNamespace()‑methode van de Node‑interface accepteert een pakket‑URI als argument. Ze retourneert een booleaanse waarde die true is als het pakket de standaardpakket is op de opgegeven knoop en false anders. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | De isEqualNode() methode van de [`Node`](../node/) interface test of twee nodes gelijk zijn. Twee nodes zijn gelijk wanneer ze hetzelfde type hebben, bepalende kenmerken (voor elementen zou dit hun ID, aantal kinderen, enzovoort zijn), hun attributen overeenkomen, enzovoort. De specifieke set gegevenspunten die moeten overeenkomen varieert afhankelijk van de types van de nodes. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | De isSameNode()‑methode van de Node‑interface is een legacy‑alias voor de === strikte gelijkheidsoperator. Dat wil zeggen, ze test of twee knopen identiek zijn (met andere woorden, of ze naar hetzelfde object verwijzen). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | De lookupNamespaceURI()‑methode van de Node‑interface neemt een prefix als parameter en retourneert de pakket‑URI die eraan gekoppeld is op de opgegeven knoop, indien gevonden (anders null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | De lookupPrefix()‑methode van de Node‑interface retourneert een String met de prefix voor een gegeven pakket‑URI, indien aanwezig, en null anders. Wanneer meerdere prefixes mogelijk zijn, wordt de eerste prefix geretourneerd. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate)(RequestMessage) | Laadt het document op basis van het opgegeven request‑object, waarbij de vorige inhoud wordt vervangen. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_4)(String) | Laadt het document op de opgegeven Uniform Resource Locator (URL) in de huidige instantie, waarbij de vorige inhoud wordt vervangen. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_1)(Url) | Laadt het document op de opgegeven Uniform Resource Locator (URL) in de huidige instantie, waarbij de vorige inhoud wordt vervangen. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_3)(Stream, String) | Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van het document begint vanaf de huidige positie in de stream. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_2)(Stream, Url) | Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van het document begint vanaf de huidige positie in de stream. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_6)(String, String) | Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_5)(String, Url) | Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Plaatst alle [`Text`](../text/) nodes op de volledige diepte van de subboom onder deze Node, inclusief attribuutnodes, in een "normale" vorm waarbij alleen de structuur (bijv. [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), en [`entity references`](../entityreference/)) [`Text`](../text/) nodes scheidt, d.w.z. er zijn geen aangrenzende Text-nodes of lege Text-nodes. Dit kan worden gebruikt om te verzekeren dat de DOM-weergave van een document hetzelfde is als wanneer het is opgeslagen en opnieuw geladen, en is nuttig wanneer bewerkingen (zoals XPointer [XPointer] opzoekingen) die afhankelijk zijn van een specifieke documentboomstructuur moeten worden gebruikt. Als de parameter "normalize-characters" van het [`DOMConfiguration`](../../com.aspose.html/configuration/) object dat is gekoppeld aan de [`Node.ownerDocument`](../node/ownerdocument/) waar is, zal deze methode ook de tekens van de Text-nodes volledig normaliseren. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | Retourneert het eerste Element in het document, dat overeenkomt met de selector |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | Retourneert een NodeList van alle Elements in het document die overeenkomen met de selector |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | De removeChild()-methode van de Node-interface verwijdert een kindknooppunt uit de DOM en retourneert het verwijderde knooppunt. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [renderTo](../../com.aspose.html.dom/document/renderto/)(IDevice) | Deze methode wordt gebruikt om de inhoud van het huidige document weer te geven op een opgegeven grafisch apparaat. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Vervangt de kindnode oldChild door newChild in de lijst van kinderen, en retourneert de oldChild node. Als newChild een [`DocumentFragment`](../documentfragment/) object is, wordt oldChild vervangen door alle [`DocumentFragment`](../documentfragment/) kinderen, die in dezelfde volgorde worden ingevoegd. Als de newChild al in de boom aanwezig is, wordt deze eerst verwijderd. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Retourneert een String die dit exemplaar vertegenwoordigt. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | Schrijf een tekenreeks tekst naar een documentstroom geopend door open(). Merk op dat de functie een document kan produceren dat niet noodzakelijkerwijs wordt aangestuurd door een DTD en daarom een ongeldig resultaat kan opleveren in de context van het document. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | Schrijf een tekenreeks tekst gevolgd door een regeleinde‑teken naar een documentstroom geopend door open(). Merk op dat de functie een document kan produceren dat niet noodzakelijkerwijs wordt aangestuurd door een DTD en daarom een ongeldig resultaat kan opleveren in de context van het document. |

## Gebeurtenissen

| Naam | Beschrijving |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | Haalt op of stelt de gebeurtenishandler in voor het OnAbort‑event. |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | Haalt op of stelt de gebeurtenishandler in voor het OnBlur‑event. |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | Haalt op of stelt de gebeurtenishandler in voor het OnCancel‑event. |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | Haalt op of stelt de gebeurtenishandler in voor het OnCanplay‑event. |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | Haalt op of stelt de gebeurtenishandler in voor het OnCanPlayThrough‑event. |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | Haalt op of stelt de gebeurtenishandler in voor het OnChange‑event. |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | Haalt op of stelt de gebeurtenishandler in voor het OnClick‑event. |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | Haalt op of stelt de gebeurtenishandler in voor het OnCueChange‑event. |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | Haalt op of stelt de gebeurtenishandler in voor het OnDblClick‑event. |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | Haalt op of stelt de gebeurtenishandler in voor het OnDurationChange‑event. |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | Haalt op of stelt de gebeurtenishandler in voor het OnEmptied‑event. |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | Haalt op of stelt de gebeurtenishandler in voor het OnEnded‑event. |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | Haalt op of stelt de gebeurtenishandler in voor het OnError‑event. |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | Haalt op of stelt de gebeurtenishandler in voor het OnFocus‑event. |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | Haalt op of stelt de gebeurtenishandler in voor het OnInput‑event. |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | Haalt op of stelt de eventhandler in voor de OnInvalid-gebeurtenis. |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | Haalt op of stelt de eventhandler in voor de OnKeyDown-gebeurtenis. |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | Haalt op of stelt de eventhandler in voor de OnKeyPress-gebeurtenis. |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | Haalt op of stelt de eventhandler in voor de OnKeyUp-gebeurtenis. |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | Haalt op of stelt de eventhandler in voor de OnLoad-gebeurtenis. |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | Haalt op of stelt de eventhandler in voor de OnLoadedData-gebeurtenis. |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | Haalt op of stelt de eventhandler in voor de OnLoadedMetadata-gebeurtenis. |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | Haalt op of stelt de eventhandler in voor de OnLoadStart-gebeurtenis. |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | Haalt op of stelt de eventhandler in voor de OnMouseDown-gebeurtenis. |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | Haalt op of stelt de eventhandler in voor de OnMouseEnter-gebeurtenis. |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | Haalt op of stelt de eventhandler in voor de OnMouseLeave-gebeurtenis. |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | Haalt op of stelt de eventhandler in voor de OnMouseMove-gebeurtenis. |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | Haalt op of stelt de eventhandler in voor de OnMouseOut-gebeurtenis. |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | Haalt op of stelt de eventhandler in voor de OnMouseOver-gebeurtenis. |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | Haalt op of stelt de eventhandler in voor de OnMouseUp-gebeurtenis. |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | Haalt op of stelt de eventhandler in voor de OnMouseWheel-gebeurtenis. |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | Haalt op of stelt de eventhandler in voor de OnPause-gebeurtenis. |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | Haalt op of stelt de eventhandler in voor de OnPlay-gebeurtenis. |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | Haalt op of stelt de eventhandler in voor de OnPlaying-gebeurtenis. |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | Haalt op of stelt de eventhandler in voor de OnProgress-gebeurtenis. |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | Haalt op of stelt de eventhandler in voor de OnRateChange-gebeurtenis. |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | Haalt op of stelt de eventhandler in voor de OnReadyStateChange-gebeurtenis. |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | Haalt op of stelt de eventhandler in voor de OnReset-gebeurtenis. |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | Haalt op of stelt de eventhandler in voor de OnResize-gebeurtenis. |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | Haalt op of stelt de eventhandler in voor de OnScroll-gebeurtenis. |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | Haalt op of stelt de event handler in voor het OnSeeked‑evenement. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | Haalt op of stelt de event handler in voor het OnSeeking‑evenement. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | Haalt op of stelt de event handler in voor het OnSelect‑evenement. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | Haalt op of stelt de event handler in voor het OnShow‑evenement. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | Haalt op of stelt de event handler in voor het OnStalled‑evenement. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | Haalt op of stelt de event handler in voor het OnSubmit‑evenement. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | Haalt op of stelt de event handler in voor het OnSuspend‑evenement. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | Haalt op of stelt de event handler in voor het OnTimeUpdate‑evenement. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | Haalt op of stelt de event handler in voor het OnToggle‑evenement. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | Haalt op of stelt de event handler in voor het OnVolumeChange‑evenement. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | Haalt op of stelt de event handler in voor het OnWaiting‑evenement. |

### Zie ook

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
