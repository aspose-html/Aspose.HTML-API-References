---
title: "SVGGraphicsElement Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.svg.SVGGraphicsElement class. De SVGGraphicsElement interface vertegenwoordigt SVG-elementen waarvan het primaire doel is om direct graphics te renderen in een groep."
type: docs

url: /nl/java/com.aspose.html.dom.svg/svggraphicselement/
---
## SVGGraphicsElement class

De SVGGraphicsElement interface vertegenwoordigt SVG‑elementen waarvan het primaire doel is om direct grafische elementen in een groep te renderen.

```java
public class SVGGraphicsElement : SVGElement, ISVGTests
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) Een NamedNodeMap die de attributen van dit knooppunt bevat (als het een Element is) of anders null. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) De alleen-lezen baseURI-eigenschap van de Node-interface geeft de absolute basis-URL van het document dat het knooppunt bevat. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) Geeft het huidige aantal elementknooppunten dat kinderen zijn van dit element. 0 als dit element geen kindknooppunten heeft van nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) De alleen-lezen childNodes-eigenschap van de Node-interface geeft een live [`NodeList`](../../com.aspose.html.collections/nodelist/) van kindknooppunten van het opgegeven element waarbij het eerste kindknooppunt index 0 krijgt. Kindknooppunten omvatten elementen, tekst en commentaren. |
| [getChildren](../../com.aspose.html.dom/element/children/) Geeft de kindelementen van het huidige element terug. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) Geeft een live DOMTokenList terug die tokens bevat die zijn verkregen uit het parseren van het "class"-attribuut. |
| [getClassName](../../com.aspose.html.dom.svg/svgelement/classname/) Komt overeen met het attribuut ‘class’ op het opgegeven element. |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [getFarthestViewportElement](../../com.aspose.html.dom.svg/svggraphicselement/farthestviewportelement/) Het verste voorouder‑‘svg’-element. Null als het huidige element het buitenste svg‑element is. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) De alleen-lezen firstChild-eigenschap van de [`Node`](../../com.aspose.html.dom/node/) interface geeft het eerste kind van het knooppunt in de boom, of null als het knooppunt geen kinderen heeft. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Geeft het eerste kind-elementknooppunt van dit element terug. null als dit element geen kindelementen heeft. |
[getId]
[setId] The value of the ‘id’ attribute on the given element, or the empty String if ‘id’ is not present. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) De alleen-lezen lastChild-eigenschap van de [`Node`](../../com.aspose.html.dom/node/) interface geeft het laatste kind van het knooppunt terug. Als de ouder een element is, is het kind doorgaans een elementknooppunt, een tekstknooppunt of een commentaarknooppunt. Het geeft null terug als er geen kindelementen zijn. |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Retourneert het laatste kindelementknooppunt van dit element. null als dit element geen kindelementen heeft. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Retourneert het lokale deel van de gekwalificeerde naam van dit knooppunt. Voor knooppunten van elk type anders dan ELEMENT_NODE en ATTRIBUTE_NODE en knooppunten die zijn gemaakt met een DOM Level 1-methode, zoals Document.createElement(), is dit altijd null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) De pakket-URI van dit knooppunt, of null als deze niet is gespecificeerd. |
| [getNearestViewportElement](../../com.aspose.html.dom.svg/svggraphicselement/nearestviewportelement/) Het element dat de huidige viewport heeft vastgesteld. Vaak het dichtstbijzijnde voorouder‑‘svg’-element. Null als het huidige element het buitenste svg‑element is. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Retourneert het volgende broertje-elementknooppunt van dit element. null als dit element geen elementbroerknopen heeft die na dit knooppunt in de documentboom komen. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) De alleen-lezen nextSibling-eigenschap van de [`Node`](../../com.aspose.html.dom/node/) interface retourneert het knooppunt dat direct volgt op het opgegeven knooppunt in de [`childNodes`](../../com.aspose.html.dom/node/childnodes/) van hun ouder, of retourneert null als het opgegeven knooppunt het laatste kind in het bovenliggende element is. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) De naam van dit knooppunt, afhankelijk van het type. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) Een code die het type van het onderliggende object vertegenwoordigt. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | De nodeValue-eigenschap van de [`Node `](../../com.aspose.html.dom/node/) interface retourneert of stelt de waarde van het huidige knooppunt in. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) De alleen-lezen ownerDocument-eigenschap van de Node-interface retourneert het bovenliggende documentobject van het knooppunt. |
| [getOwnerSVGElement](../../com.aspose.html.dom.svg/svgelement/ownersvgelement/) Het dichtstbijzijnde bovenliggende ‘svg’-element. Null als het opgegeven element het buitenste svg-element is. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) De alleen-lezen parentElement-eigenschap van de [`Node`](../../com.aspose.html.dom/node/) interface retourneert het bovenliggende [`Element`](../../com.aspose.html.dom/element/) van het DOM-knooppunt, of null als het knooppunt geen ouder heeft, of als de ouder geen DOM-element is. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) De alleen-lezen parentNode-eigenschap van de Node-interface retourneert de ouder van het opgegeven knooppunt in de DOM-boom. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) Het pakketprefix van dit knooppunt, of null als dit niet is gespecificeerd. Wanneer het is ingesteld op null, heeft het instellen geen effect. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Retourneert het vorige broertje-elementknooppunt van dit element. null als dit element geen elementbroerknopen heeft die vóór dit knooppunt in de documentboom komen. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) De alleen-lezen previousSibling-eigenschap van de [`Node`](../../com.aspose.html.dom/node/) interface retourneert het knooppunt dat direct voorafgaat aan het opgegeven knooppunt in de [`childNodes`](../../com.aspose.html.dom/node/firstchild/) lijst van de ouder, of null als het opgegeven knooppunt het eerste in die lijst is. |
| [getRequiredExtensions](../../com.aspose.html.dom.svg/svggraphicselement/requiredextensions/) Komt overeen met het attribuut ‘requiredExtensions’ op het opgegeven element. |
| [getRequiredFeatures](../../com.aspose.html.dom.svg/svggraphicselement/requiredfeatures/) Komt overeen met het attribuut ‘requiredFeatures’ op het opgegeven element. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Retourneert de shadowRoot die op dit element is opgeslagen of null als deze gesloten is. |
| [getStyle](../../com.aspose.html.dom.svg/svgelement/style/) Komt overeen met het attribuut ‘style’ op het opgegeven element. Als de user agent geen styling met CSS ondersteunt, moet dit attribuut altijd de waarde null hebben. |
| [getSystemLanguage](../../com.aspose.html.dom.svg/svggraphicselement/systemlanguage/) Komt overeen met het attribuut ‘systemLanguage’ op het opgegeven element. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) De naam van het element. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | Dit attribuut retourneert de tekstinhoud van dit knooppunt en zijn afstammelingen. Wanneer het is ingesteld op null, heeft het instellen geen effect. Bij het instellen worden eventuele kinderen die dit knooppunt kan hebben verwijderd en, als de nieuwe string niet leeg of null is, vervangen door een enkel Text-knooppunt dat de string bevat waar dit attribuut op is ingesteld. |
| [getTransform](../../com.aspose.html.dom.svg/svggraphicselement/transform/) Komt overeen met het attribuut ‘transform’ op het opgegeven element. |
| [getViewportElement](../../com.aspose.html.dom.svg/svgelement/viewportelement/) Het element dat de huidige viewport heeft vastgesteld. Vaak het dichtstbijzijnde bovenliggende ‘svg’-element. Null als het opgegeven element het buitenste svg-element is. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | De addEventListener()-methode van de [`EventTarget `](../../com.aspose.html.dom/eventtarget/) interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | De addEventListener()‑methode van de [EventTarget](T:com.aspose.html.dom.EventTarget)‑interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | De addEventListener()‑methode van de [EventTarget](T:com.aspose.html.dom.EventTarget)‑interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | De appendChild()‑methode van de Node‑interface voegt een knoop toe aan het einde van de lijst met kinderen van een opgegeven bovenliggende knoop. Als het opgegeven kind een verwijzing is naar een bestaande knoop in het document, verplaatst appendChild() deze van zijn huidige positie naar de nieuwe positie (er is geen vereiste om de knoop van zijn bovenliggende knoop te verwijderen voordat hij aan een andere knoop wordt toegevoegd). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Maakt een shadow‑root aan en koppelt deze aan het huidige element. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Verzendt een Event naar de opgegeven [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchroon) en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor gebeurtenisverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Voert toepassingsspecifieke taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet‑beheerde bronnen. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Haalt een attribuutwaarde op op basis van de naam. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Retourneert de attribuutnamen van het element als een array van strings. Als het element geen attributen heeft, wordt een lege array geretourneerd. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Haalt een attribuutknoop op op basis van de naam. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Haalt een Attr‑knoop op op basis van de lokale naam en pakket‑URI. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Haalt een attribuutwaarde op op basis van de lokale naam en pakket‑URI. |
| [getBBox](../../com.aspose.html.dom.svg/svggraphicselement/getbbox/)() | Retourneert de nauwsluitende begrenzingsdoos in de huidige gebruikersruimte (d.w.z. na toepassing van het ‘transform’-attribuut, indien aanwezig) op de geometrie van alle ingesloten grafische elementen, exclusief stroken, bijsnijden, maskeren en filtereffecten). Merk op dat getBBox de werkelijke begrenzingsdoos moet retourneren op het moment dat de methode wordt aangeroepen, zelfs als het element nog niet is gerenderd. |
| [getCTM](../../com.aspose.html.dom.svg/svggraphicselement/getctm/)() | Retourneert de transformatie‑matrix van de huidige gebruikers‑eenheden (d.w.z. na toepassing van het ‘transform’-attribuut, indien aanwezig) naar het viewport‑coördinatensysteem voor het nearestViewportElement. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Retourneert een [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/)‑object dat alle elementen binnen [`element`](../../com.aspose.html.dom/element/) bevat die alle in het argument opgegeven klassen hebben. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Retourneert een [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/)‑object dat alle [`elements`](../../com.aspose.html.dom/element/) met een opgegeven tagnaam bevat, in documentvolgorde. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Retourneert een [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/)‑object dat alle [`elements`](../../com.aspose.html.dom/element/) met een opgegeven lokale naam en pakket‑URI‑string bevat, in documentvolgorde. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [getScreenCTM](../../com.aspose.html.dom.svg/svggraphicselement/getscreenctm/)() | Retourneert de transformatie‑matrix van de huidige gebruikers‑eenheden (d.w.z. na toepassing van het ‘transform’-attribuut, indien aanwezig) naar de perceptie van een \"pixel\" door de bovenliggende user‑agent. Voor weergave‑apparaten vertegenwoordigt dit idealiter een fysiek scherm‑pixel. Voor andere apparaten of omgevingen waarin de fysieke pixelgrootte onbekend is, kan in plaats daarvan een algoritme worden gebruikt dat vergelijkbaar is met de CSS2‑definitie van een \"pixel\". Merk op dat null wordt geretourneerd als dit element niet is gekoppeld aan de documentboom. Deze methode zou beter getClientCTM genoemd kunnen worden, maar de naam getScreenCTM wordt om historische redenen behouden. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | Retourneert true wanneer een attribuut met de opgegeven naam op dit element is gespecificeerd of een standaardwaarde heeft, anders false. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | Retourneert true wanneer een attribuut met de opgegeven lokale naam en pakket‑URI op dit element is gespecificeerd of een standaardwaarde heeft, anders false. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | Retourneert of deze knoop (indien het een element is) attributen heeft |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | De hasChildNodes()‑methode van de Node‑interface retourneert een booleaanse waarde die aangeeft of de gegeven [`Node`](../../com.aspose.html.dom/node/) kindknopen heeft of niet. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | De insertBefore()‑methode van de Node‑interface voegt een knoop in vóór een referentieknoop als kind van een opgegeven bovenliggende knoop. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | De isDefaultNamespace()‑methode van de Node‑interface accepteert een pakket‑URI als argument. Ze retourneert een booleaanse waarde die true is als het pakket de standaardpakket is op de opgegeven knoop en false anders. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | De isEqualNode()‑methode van de [`Node`](../../com.aspose.html.dom/node/)‑interface test of twee knopen gelijk zijn. Twee knopen zijn gelijk wanneer ze hetzelfde type hebben, dezelfde bepalende kenmerken (voor elementen is dit hun ID, aantal kinderen, enzovoort), hun attributen overeenkomen, enzovoort. De specifieke set gegevens die moeten overeenkomen varieert afhankelijk van het type knopen. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | De isSameNode()‑methode van de Node‑interface is een legacy‑alias voor de === strikte gelijkheidsoperator. Dat wil zeggen, ze test of twee knopen identiek zijn (met andere woorden, of ze naar hetzelfde object verwijzen). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | De lookupNamespaceURI()‑methode van de Node‑interface neemt een prefix als parameter en retourneert de pakket‑URI die eraan gekoppeld is op de opgegeven knoop, indien gevonden (anders null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | De lookupPrefix()‑methode van de Node‑interface retourneert een String met de prefix voor een gegeven pakket‑URI, indien aanwezig, en null anders. Wanneer meerdere prefixes mogelijk zijn, wordt de eerste prefix geretourneerd. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Plaatst alle [`Text`](../../com.aspose.html.dom/text/) knopen in de volledige diepte van de subboom onder deze Node, inclusief attribuutknopen, in een \"normale\" vorm waarbij alleen de structuur (bijv. [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), en [`entity references`](../../com.aspose.html.dom/entityreference/)) [`Text`](../../com.aspose.html.dom/text/) knopen scheidt, d.w.z. er zijn geen aangrenzende Text‑knopen noch lege Text‑knopen. Dit kan worden gebruikt om te garanderen dat de DOM‑weergave van een document hetzelfde is als wanneer het zou worden opgeslagen en opnieuw geladen, en is nuttig wanneer bewerkingen (zoals XPointer [XPointer] opzoekingen) die afhankelijk zijn van een specifieke documentboomstructuur moeten worden gebruikt. Als de parameter \"normalize-characters\" van het [`DOMConfiguration`](../../com.aspose.html/configuration/) object dat is gekoppeld aan de [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) true is, zal deze methode ook de tekens van de Text‑knopen volledig normaliseren. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | Retourneert het eerste Element in het document, dat overeenkomt met de selector |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | Retourneert een NodeList van alle Elements in het document die overeenkomen met de selector |
| [remove](../../com.aspose.html.dom/element/remove/)() | Verwijdert deze instantie. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | Verwijdert een attribuut op naam. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | Verwijdert het opgegeven attribuutknooppunt. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | Verwijdert een attribuut op basis van lokale naam en pakket-URI. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | De removeChild()-methode van de Node-interface verwijdert een kindknooppunt uit de DOM en retourneert het verwijderde knooppunt. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Deze methode maakt het verwijderen van event listeners van het eventdoel mogelijk. Als een listener wordt verwijderd terwijl deze een gebeurtenis verwerkt, zal deze niet worden geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Vervangt het kindknooppunt oldChild door newChild in de lijst van kinderen, en retourneert het oldChild-knooppunt. Als newChild een [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) object is, wordt oldChild vervangen door alle [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) kinderen, die in dezelfde volgorde worden ingevoegd. Als newChild al in de boom aanwezig is, wordt deze eerst verwijderd. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | Voegt een nieuw attribuut toe. Als een attribuut met die naam al aanwezig is in het element, wordt de waarde aangepast naar de waarde van de parameter. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | Voegt een nieuw attribuutknooppunt toe. Als een attribuut met die naam (nodeName) al aanwezig is in het element, wordt het vervangen door het nieuwe. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | Voegt een nieuw attribuut toe. Als een attribuut met die lokale naam en die pakket-URI al aanwezig is in het element, wordt het vervangen door het nieuwe. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | Voegt een nieuw attribuut toe. Als een attribuut met dezelfde lokale naam en pakket-URI al aanwezig is op het element, wordt het voorvoegsel aangepast naar het voorvoegselgedeelte van de qualifiedName, en wordt de waarde aangepast naar de waardeparameter. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | Als force niet is opgegeven, \"schakelt\" qualifiedName, verwijdert het als het aanwezig is en voegt het toe als het niet aanwezig is. Als force true is, wordt qualifiedName toegevoegd. Als force false is, wordt qualifiedName verwijderd. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | Als force niet is opgegeven, \"schakelt\" qualifiedName, verwijdert het als het aanwezig is en voegt het toe als het niet aanwezig is. Als force true is, wordt qualifiedName toegevoegd. Als force false is, wordt qualifiedName verwijderd. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Retourneert een String die dit exemplaar vertegenwoordigt. |

### Zie ook

* class [SVGElement](../svgelement/)
* interface [ISVGTests](../isvgtests/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
