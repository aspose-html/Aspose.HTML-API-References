---
title: "Node Class"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.Node class. De Node‑interface is het primaire datatype voor het volledige Document Object Model. Het vertegenwoordigt een enkel knooppunt in de documentboom. Terwijl alle objecten die de Node‑interface implementeren methoden blootstellen voor het omgaan met kinderen, hebben niet alle objecten die de Node‑interface implementeren kinderen. Bijvoorbeeld Text‑knooppunten kunnen geen kinderen hebben en het toevoegen van kinderen aan dergelijke knooppunten leidt tot een DOMException."
type: docs

url: /nl/java/com.aspose.html.dom/node/
---
## Node class

De Node-interface is het primaire datatype voor het volledige Document Object Model. Het vertegenwoordigt een enkele node in de documentboom. Terwijl alle objecten die de Node-interface implementeren methoden blootstellen voor het omgaan met kinderen, mogen niet alle objecten die de Node-interface implementeren kinderen hebben. Bijvoorbeeld, [`Text`](../text/) nodes kunnen geen kinderen hebben, en het toevoegen van kinderen aan dergelijke nodes resulteert in een [`DOMException`](../domexception/) die wordt opgegooid.

De attributen [`nodeName`](./nodename/), [`nodeValue`](./nodevalue/) en attributen zijn opgenomen als een mechanisme om node-informatie te verkrijgen zonder te casten naar de specifieke afgeleide interface. In gevallen waarin er geen duidelijke mapping van deze attributen bestaat voor een specifiek [`nodeType`](./nodetype/) (bijv. nodeValue voor een [`Element`](../element/) of attributen voor een [`Comment`](../comment/)), retourneert dit null. Merk op dat de gespecialiseerde interfaces extra en meer handige mechanismen kunnen bevatten om de relevante informatie te krijgen en in te stellen.

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) De alleen-lezen baseURI-eigenschap van de Node-interface retourneert de absolute basis-URL van het document dat het knooppunt bevat. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) De alleen-lezen childNodes-eigenschap van de Node-interface retourneert een live [`NodeList`](../../com.aspose.html.collections/nodelist/) van kindknooppunten van het opgegeven element waarbij het eerste kindknooppunt index 0 krijgt. Kindknooppunten omvatten elementen, tekst en commentaren. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) De alleen-lezen firstChild‑eigenschap van de `Node`‑interface retourneert de eerste child van de node in de boom, of null als de node geen kinderen heeft. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) De alleen-lezen lastChild‑eigenschap van de `Node`‑interface retourneert de laatste child van de node. Als de ouder een element is, is de child doorgaans een elementnode, een textnode of een commentnode. Het retourneert null als er geen kindelementen zijn. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Retourneert het lokale deel van de gekwalificeerde naam van deze node. Voor nodes van elk type behalve [`ELEMENT_NODE`](./element_node/) en [`ATTRIBUTE_NODE`](./attribute_node/) en nodes die zijn aangemaakt met een DOM Level 1‑methode, zoals [`Document.createElement()`](../document/createelement/), is dit altijd null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) De alleen‑lezen‑eigenschap Element.packageURI retourneert de pakket‑URI van het element, of null als het element zich niet in een pakket bevindt. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) De alleen-lezen nextSibling‑eigenschap van de `Node`‑interface retourneert de node die direct volgt op de opgegeven node in de [`childNodes`](./childnodes/) van hun ouder, of retourneert null als de opgegeven node de laatste child in het bovenliggende element is. |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) De alleen-lezen nodeName‑eigenschap van Node retourneert de naam van de huidige node als een String. |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) Een code die het type van het onderliggende object vertegenwoordigt. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | De nodeValue‑eigenschap van de `Node`‑interface retourneert of stelt de waarde van de huidige node in. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) De alleen‑lezen ownerDocument‑eigenschap van de Node‑interface retourneert het bovenliggende documentobject van het knooppunt. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) De alleen-lezen parentElement‑eigenschap van de `Node`‑interface retourneert de ouder‑[`Element`](../element/) van de DOM‑node, of null als de node geen ouder heeft, of als de ouder geen DOM‑Element is. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) De alleen‑lezen parentNode‑eigenschap van de Node‑interface retourneert de ouder van het opgegeven knooppunt in de DOM‑boom. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | De alleen‑lezen‑eigenschap prefix retourneert het pakket‑prefix van het opgegeven element, of null als er geen prefix is opgegeven. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) De alleen-lezen previousSibling‑eigenschap van de `Node`‑interface retourneert de node die direct voorafgaat aan de opgegeven node in de [`childNodes`](./firstchild/) van zijn ouder, of null als de opgegeven node de eerste in die lijst is. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | De textContent‑eigenschap van de `Node`‑interface vertegenwoordigt de tekstinhoud van de node en haar afstammelingen. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | De addEventListener() methode van de [`EventTarget `](../eventtarget/) interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | De addEventListener()‑methode van de [EventTarget ](T:com.aspose.html.dom.EventTarget)interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | De addEventListener()‑methode van de [EventTarget ](T:com.aspose.html.dom.EventTarget)interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | De appendChild()‑methode van de Node‑interface voegt een knoop toe aan het einde van de lijst met kinderen van een opgegeven bovenliggende knoop. Als het opgegeven kind een verwijzing is naar een bestaande knoop in het document, verplaatst appendChild() deze van zijn huidige positie naar de nieuwe positie (er is geen vereiste om de knoop uit zijn bovenliggende knoop te verwijderen voordat hij aan een andere knoop wordt toegevoegd). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Zend een Event naar het opgegeven [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchroon) en roep de betrokken EventListeners in de juiste volgorde aan. De normale regels voor gebeurtenisverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet‑beheerde bronnen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | De hasChildNodes()‑methode van de Node‑interface retourneert een booleaanse waarde die aangeeft of de gegeven `Node` al dan niet child‑nodes heeft. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | De insertBefore()‑methode van de Node‑interface voegt een knoop in vóór een referentieknoop als kind van een opgegeven bovenliggende knoop. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | De isDefaultNamespace()‑methode van de Node‑interface accepteert een package‑URI als argument. Ze retourneert een booleaanse waarde die true is als het package het standaardpackage is op de gegeven knoop en false anders. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | De isEqualNode()‑methode van de `Node`‑interface test of twee nodes gelijk zijn. Twee nodes zijn gelijk wanneer ze hetzelfde type hebben, dezelfde bepalende kenmerken (voor elementen zou dit hun ID, aantal kinderen, enzovoort zijn), hun attributen overeenkomen, enzovoort. De specifieke set gegevenspunten die moeten overeenkomen varieert afhankelijk van de typen van de nodes. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | De isSameNode()‑methode van de Node‑interface is een legacy‑alias voor de === strikte gelijkheidsoperator. Met andere woorden, ze test of twee knopen identiek zijn (ofwel of ze naar hetzelfde object verwijzen). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | De lookupNamespaceURI()‑methode van de Node‑interface neemt een prefix als parameter en retourneert de package‑URI die eraan gekoppeld is op de gegeven knoop, indien gevonden (anders null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | De lookupPrefix()‑methode van de Node‑interface retourneert een string die de prefix voor een gegeven package‑URI bevat, indien aanwezig, en anders null. Wanneer meerdere prefixes mogelijk zijn, wordt de eerste prefix geretourneerd. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Plaatst alle [`Text`](../text/) nodes in de volledige diepte van de sub‑boom onder deze Node, inclusief attribuut‑nodes, in een "normale" vorm waarbij alleen structuur (bijv. [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), en [`entity references`](../entityreference/)) [`Text`](../text/) nodes scheidt, d.w.z. er zijn geen aangrenzende Text‑nodes of lege Text‑nodes. Dit kan worden gebruikt om te garanderen dat de DOM‑weergave van een document hetzelfde is als wanneer het zou worden opgeslagen en opnieuw geladen, en is nuttig wanneer bewerkingen (zoals XPointer‑[XPointer]‑opzoekingen) die afhankelijk zijn van een specifieke documentboomstructuur moeten worden gebruikt. Als de parameter "normalize-characters" van het [`DOMConfiguration`](../../com.aspose.html/configuration/)‑object dat is gekoppeld aan de [`Node.ownerDocument`](./ownerdocument/) true is, zal deze methode ook de tekens van de Text‑nodes volledig normaliseren. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | De removeChild()-methode van de Node-interface verwijdert een kindknooppunt uit de DOM en retourneert het verwijderde knooppunt. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Vervangt de kindnode oldChild door newChild in de lijst van kinderen, en retourneert de oldChild-node. Als newChild een [`DocumentFragment`](../documentfragment/) object is, wordt oldChild vervangen door alle [`DocumentFragment`](../documentfragment/) kinderen, die in dezelfde volgorde worden ingevoegd. Als newChild al in de boom aanwezig is, wordt deze eerst verwijderd. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | Een [`Attribute`](../attr/) van een [`Element`](../element/). |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | Een [`CDATASection`](../cdatasection/), zoals &lt;!CDATA[[ … ]]&gt;. |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | Een [`Comment`](../comment/) node, zoals &lt;!-- … --&gt;. |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | Een [`DocumentFragment`](../documentfragment/) node. |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | Een [`Document`](../document/) node. |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | Een [`DocumentType`](../documenttype/) node, zoals &lt;!DOCTYPE html&gt;. |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | Een [`Element`](../element/) node zoals &lt;p&gt; of &lt;div&gt;. |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | Een [`Entity`](../entity/) node. |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | Een [`EntityReference`](../entityreference/) node. |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | Een [`Notation`](../notation/) node |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | Een [`ProcessingInstruction`](../processinginstruction/) van een XML-document, zoals &lt;?xml-stylesheet … ?&gt;. |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | De daadwerkelijke [`Text`](../text/) binnen een [`Element`](../element/) of [`Attr`](../attr/). |

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Zie ook

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
