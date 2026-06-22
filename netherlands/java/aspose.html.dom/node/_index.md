---
title: "Node Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.Node class. De Node‑interface is het primaire datatype voor het volledige Document Object Model. Het vertegenwoordigt een enkel knooppunt in de documentboom. Hoewel alle objecten die de Node‑interface implementeren methoden blootleggen voor het omgaan met kinderen, hebben niet alle objecten die de Node‑interface implementeren kinderen. Bijvoorbeeld Text‑knooppunten kunnen geen kinderen hebben en het toevoegen van kinderen aan dergelijke knooppunten leidt tot een DOMException."
type: docs

url: /nl/java/com.aspose.html.dom/node/
---
## Node class

De Node-interface is het primaire gegevenstype voor het volledige Document Object Model. Het vertegenwoordigt een enkel knooppunt in de documentboom. Terwijl alle objecten die de Node-interface implementeren methoden blootleggen voor het omgaan met kinderen, mogen niet alle objecten die de Node-interface implementeren kinderen hebben. Bijvoorbeeld, [`Text`](../text/) knooppunten kunnen geen kinderen hebben, en het toevoegen van kinderen aan dergelijke knooppunten resulteert in een [`DOMException`](../domexception/) die wordt opgegooid.

De attributen [`nodeName`](./nodename/), [`nodeValue`](./nodevalue/) en attributen zijn opgenomen als een mechanisme om knoopinformatie te verkrijgen zonder te casten naar de specifieke afgeleide interface. In gevallen waarin er geen duidelijke mapping van deze attributen bestaat voor een specifiek [`nodeType`](./nodetype/) (bijv. nodeValue voor een [`Element`](../element/) of attributen voor een [`Comment`](../comment/)), retourneert dit null. Merk op dat de gespecialiseerde interfaces aanvullende en handigere mechanismen kunnen bevatten om de relevante informatie op te halen en in te stellen.

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) De alleen-lezen baseURI-eigenschap van de Node-interface geeft de absolute basis-URL van het document dat het knooppunt bevat. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) De alleen-lezen childNodes-eigenschap van de Node-interface geeft een live [`NodeList`](../../com.aspose.html.collections/nodelist/) van kindknooppunten van het opgegeven element waarbij het eerste kindknooppunt index 0 krijgt. Kindknooppunten omvatten elementen, tekst en commentaren. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) De alleen-lezen firstChild-eigenschap van de `Node`-interface retourneert het eerste kind van de knoop in de boom, of null als de knoop geen kinderen heeft. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) De alleen-lezen lastChild-eigenschap van de `Node`-interface retourneert het laatste kind van de knoop. Als de ouder een element is, dan is het kind doorgaans een elementknoop, een tekstknoop of een commentaarknoop. Het retourneert null als er geen kindelementen zijn. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Retourneert het lokale deel van de gekwalificeerde naam van deze knoop. Voor knopen van elk type behalve [`ELEMENT_NODE`](./element_node/) en [`ATTRIBUTE_NODE`](./attribute_node/) en knopen die zijn gemaakt met een DOM Level 1-methode, zoals [`Document.createElement()`](../document/createelement/), is dit altijd null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) De alleen-lezen eigenschap Element.packageURI retourneert de pakket-URI van het element, of null als het element zich niet in een pakket bevindt. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) De alleen-lezen nextSibling-eigenschap van de `Node`-interface retourneert de knoop die direct volgt op de opgegeven knoop in de [`childNodes`](./childnodes/) van hun ouder, of retourneert null als de opgegeven knoop het laatste kind in het bovenliggende element is. |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) De alleen-lezen nodeName-eigenschap van Node retourneert de naam van de huidige knoop als een String. |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) Een code die het type van het onderliggende object vertegenwoordigt. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | De nodeValue-eigenschap van de `Node `-interface retourneert of stelt de waarde van de huidige knoop in. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) De alleen-lezen ownerDocument-eigenschap van de Node-interface retourneert het bovenliggende documentobject van het knooppunt. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) De alleen-lezen parentElement-eigenschap van de `Node`-interface retourneert de ouder van het DOM-knooppunt [`Element`](../element/), of null als de knoop geen ouder heeft, of als de ouder geen DOM-element is. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) De alleen-lezen parentNode-eigenschap van de Node-interface retourneert de ouder van het opgegeven knooppunt in de DOM-boom. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | De alleen-lezen eigenschap prefix retourneert het pakket‑prefix van het opgegeven element, of null als er geen prefix is opgegeven. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) De alleen-lezen previousSibling-eigenschap van de `Node`-interface retourneert de knoop die direct voorafgaat aan de opgegeven knoop in de [`childNodes`](./firstchild/) lijst van zijn ouder, of null als de opgegeven knoop de eerste in die lijst is. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | De textContent-eigenschap van de `Node`-interface vertegenwoordigt de tekstinhoud van de knoop en zijn afstammelingen. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | De addEventListener() methode van de [`EventTarget `](../eventtarget/) interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | De addEventListener()‑methode van de [EventTarget](T:com.aspose.html.dom.EventTarget)‑interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | De addEventListener()‑methode van de [EventTarget](T:com.aspose.html.dom.EventTarget)‑interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | De appendChild()‑methode van de Node‑interface voegt een knoop toe aan het einde van de lijst met kinderen van een opgegeven bovenliggende knoop. Als het opgegeven kind een verwijzing is naar een bestaande knoop in het document, verplaatst appendChild() deze van zijn huidige positie naar de nieuwe positie (er is geen vereiste om de knoop van zijn bovenliggende knoop te verwijderen voordat hij aan een andere knoop wordt toegevoegd). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Verzendt een Event naar de opgegeven [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchroon) en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor gebeurtenisverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Voert toepassingsspecifieke taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet‑beheerde bronnen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | De hasChildNodes()-methode van de Node-interface retourneert een booleaanse waarde die aangeeft of de opgegeven `Node` kindknooppunten heeft of niet. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | De insertBefore()‑methode van de Node‑interface voegt een knoop in vóór een referentieknoop als kind van een opgegeven bovenliggende knoop. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | De isDefaultNamespace()‑methode van de Node‑interface accepteert een pakket‑URI als argument. Ze retourneert een booleaanse waarde die true is als het pakket de standaardpakket is op de opgegeven knoop en false anders. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | De isEqualNode()-methode van de `Node`-interface test of twee knopen gelijk zijn. Twee knopen zijn gelijk wanneer ze hetzelfde type hebben, dezelfde bepalende kenmerken (voor elementen zou dit hun ID, aantal kinderen, enzovoort zijn), hun attributen overeenkomen, enzovoort. De specifieke set gegevenspunten die moeten overeenkomen varieert afhankelijk van de typen van de knopen. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | De isSameNode()‑methode van de Node‑interface is een legacy‑alias voor de === strikte gelijkheidsoperator. Dat wil zeggen, ze test of twee knopen identiek zijn (met andere woorden, of ze naar hetzelfde object verwijzen). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | De lookupNamespaceURI()‑methode van de Node‑interface neemt een prefix als parameter en retourneert de pakket‑URI die eraan gekoppeld is op de opgegeven knoop, indien gevonden (anders null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | De lookupPrefix()‑methode van de Node‑interface retourneert een String met de prefix voor een gegeven pakket‑URI, indien aanwezig, en null anders. Wanneer meerdere prefixes mogelijk zijn, wordt de eerste prefix geretourneerd. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Plaatst alle [`Text`](../text/) knopen in de volledige diepte van de subboom onder deze Node, inclusief attribuutknopen, in een "normale" vorm waarbij alleen de structuur (bijv. [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), en [`entity references`](../entityreference/)) [`Text`](../text/) knopen scheidt, d.w.z. er zijn geen aangrenzende Text‑knopen noch lege Text‑knopen. Dit kan worden gebruikt om te garanderen dat de DOM-weergave van een document hetzelfde is als wanneer het zou worden opgeslagen en opnieuw geladen, en is nuttig wanneer bewerkingen (zoals XPointer‑[XPointer]-opzoekingen) die afhankelijk zijn van een specifieke documentboomstructuur moeten worden gebruikt. Als de parameter "normalize-characters" van het [`DOMConfiguration`](../../com.aspose.html/configuration/) object dat is gekoppeld aan de [`Node.ownerDocument`](./ownerdocument/) waar is, zal deze methode ook de tekens van de Text‑knopen volledig normaliseren. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | De removeChild()-methode van de Node-interface verwijdert een kindknooppunt uit de DOM en retourneert het verwijderde knooppunt. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Vervangt de kindnode oldChild door newChild in de lijst van kinderen, en retourneert de oldChild node. Als newChild een [`DocumentFragment`](../documentfragment/) object is, wordt oldChild vervangen door alle [`DocumentFragment`](../documentfragment/) kinderen, die in dezelfde volgorde worden ingevoegd. Als de newChild al in de boom aanwezig is, wordt deze eerst verwijderd. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Retourneert een String die dit exemplaar vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | Een [`Attribute`](../attr/) van een [`Element`](../element/). |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | Een [`CDATASection`](../cdatasection/), zoals &lt;!CDATA[[ … ]]&gt;. |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | Een [`Comment`](../comment/) knoop, zoals &lt;!-- … --&gt;. |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | Een [`DocumentFragment`](../documentfragment/) knoop. |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | Een [`Document`](../document/) knoop. |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | Een [`DocumentType`](../documenttype/) knoop, zoals &lt;!DOCTYPE html&gt;. |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | Een [`Element`](../element/) knoop zoals &lt;p&gt; of &lt;div&gt;. |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | Een [`Entity`](../entity/) knoop. |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | Een [`EntityReference`](../entityreference/) knoop. |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | Een [`Notation`](../notation/) knoop |
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
