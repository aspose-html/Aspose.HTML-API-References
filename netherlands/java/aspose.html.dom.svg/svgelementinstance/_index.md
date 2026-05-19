---
title: "SVGElementInstance Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.svg.SVGElementInstance class. Het rootobject van elke use-element shadow tree implementeert de SVGUseElementShadowRoot interface. Deze interface definieert momenteel geen uitbreidingen op de eigenschappen en methoden die zijn gedefinieerd voor de ShadowRoot interface en DocumentOrShadowRoot mixin. Echter is de boom die bij dit knooppunt is geworteld volledig alleen-lezen vanuit het perspectief van auteurscripts."
type: docs

url: /nl/java/com.aspose.html.dom.svg/svgelementinstance/
---
## SVGElementInstance class

Het root‑object van elke use‑element‑schaduwbomen implementeert de SVGUseElementShadowRoot‑interface. Deze interface definieert momenteel geen extensies op de eigenschappen en methoden die zijn gedefinieerd voor de ShadowRoot‑interface en de DocumentOrShadowRoot‑mixin. Echter, de boom die op dit knooppunt is geworteld is volledig alleen‑lezen vanuit het perspectief van scripts van de auteur.

```java
public class SVGElementInstance : ShadowRoot
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) De alleen-lezen baseURI-eigenschap van de Node-interface retourneert de absolute basis-URL van het document dat het knooppunt bevat. |
| [getChildElementCount](../../com.aspose.html.dom/documentfragment/childelementcount/) Geeft het huidige aantal elementknooppunten dat kinderen zijn van dit element. 0 als dit element geen kindknooppunten heeft die van nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) De alleen-lezen childNodes-eigenschap van de Node-interface retourneert een live [`NodeList`](../../com.aspose.html.collections/nodelist/) van kindknooppunten van het opgegeven element waarbij het eerste kindknooppunt index 0 krijgt. Kindknooppunten omvatten elementen, tekst en commentaren. |
| [getChildren](../../com.aspose.html.dom/documentfragment/children/) Geeft de kindelementen van het huidige element. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) De alleen-lezen firstChild-eigenschap van de [`Node`](../../com.aspose.html.dom/node/) interface retourneert het eerste kind van het knooppunt in de boom, of null als het knooppunt geen kinderen heeft. |
| [getFirstElementChild](../../com.aspose.html.dom/documentfragment/firstelementchild/) Geeft het eerste kindelementknooppunt van dit element. null als dit element geen kindelementen heeft. |
| [getHost](../../com.aspose.html.dom/shadowroot/host/) Host is een element dat deze ShadowRoot bevat. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) De alleen-lezen lastChild-eigenschap van de [`Node`](../../com.aspose.html.dom/node/) interface retourneert het laatste kind van het knooppunt. Als de ouder een element is, is het kind doorgaans een elementknooppunt, een tekstknooppunt of een commentaarknooppunt. Het retourneert null als er geen kindelementen zijn. |
| [getLastElementChild](../../com.aspose.html.dom/documentfragment/lastelementchild/) Geeft het laatste kindelementknooppunt van dit element. null als dit element geen kindelementen heeft. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Retourneert het lokale deel van de gekwalificeerde naam van dit knooppunt. Voor knooppunten van elk type anders dan [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) en [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) en knooppunten gemaakt met een DOM Level 1‑methode, zoals [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/), is dit altijd null. |
| [getMode](../../com.aspose.html.dom/shadowroot/mode/) Modus waarin deze ShadowRoot opereert. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) De alleen‑lezen‑eigenschap Element.packageURI retourneert de pakket‑URI van het element, of null als het element zich niet in een pakket bevindt. |
| [getNextElementSibling](../../com.aspose.html.dom/documentfragment/nextelementsibling/) Geeft het volgende sibling-elementknooppunt van dit element. null als dit element geen element-siblingknooppunten heeft die na dit knooppunt komen in de documentboom. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) De alleen‑lezen nextSibling‑eigenschap van de [`Node`](../../com.aspose.html.dom/node/) interface retourneert het knooppunt dat direct volgt op het opgegeven knooppunt in de `childNodes` van hun ouder, of retourneert null als het opgegeven knooppunt het laatste kind in het bovenliggende element is. |
| [getNodeName](../../com.aspose.html.dom/documentfragment/nodename/) De naam van dit knooppunt, afhankelijk van het type. |
| [getNodeType](../../com.aspose.html.dom/documentfragment/nodetype/) Een code die het type van het onderliggende object vertegenwoordigt. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | De nodeValue‑eigenschap van de [`Node `](../../com.aspose.html.dom/node/)interface retourneert of stelt de waarde van het huidige knooppunt in. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) De alleen‑lezen ownerDocument‑eigenschap van de Node‑interface retourneert het bovenliggende documentobject van het knooppunt. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) De alleen‑lezen parentElement‑eigenschap van de [`Node`](../../com.aspose.html.dom/node/) interface retourneert de bovenliggende [`Element`](../../com.aspose.html.dom/element/) van het DOM‑knooppunt, of null als het knooppunt geen ouder heeft, of als de ouder geen DOM‑Element is. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) De alleen‑lezen parentNode‑eigenschap van de Node‑interface retourneert de ouder van het opgegeven knooppunt in de DOM‑boom. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | De alleen‑lezen‑eigenschap prefix retourneert het pakket‑prefix van het opgegeven element, of null als er geen prefix is opgegeven. |
| [getPreviousElementSibling](../../com.aspose.html.dom/documentfragment/previouselementsibling/) Geeft het vorige sibling-elementknooppunt van dit element. null als dit element geen element-siblingknooppunten heeft die vóór dit knooppunt komen in de documentboom. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) De alleen‑lezen previousSibling‑eigenschap van de [`Node`](../../com.aspose.html.dom/node/) interface retourneert het knooppunt dat direct voorafgaat aan het opgegeven knooppunt in de `childNodes`‑lijst van zijn ouder, of null als het opgegeven knooppunt het eerste in die lijst is. |
| [textContent](../../com.aspose.html.dom/documentfragment/textcontent/) { get; set; } | Dit attribuut retourneert de tekstinhoud van dit knooppunt en zijn afstammelingen. Wanneer het op null is ingesteld, heeft het instellen geen effect. Bij het instellen worden eventuele kinderen die dit knooppunt kan hebben verwijderd en, als de nieuwe string niet leeg of null is, vervangen door één Text‑knooppunt dat de string bevat waar dit attribuut op wordt gezet. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | De addEventListener()-methode van de [`EventTarget `](../../com.aspose.html.dom/eventtarget/)interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | De addEventListener()‑methode van de [EventTarget ](T:com.aspose.html.dom.EventTarget)interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | De addEventListener()‑methode van de [EventTarget ](T:com.aspose.html.dom.EventTarget)interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | De appendChild()‑methode van de Node‑interface voegt een knoop toe aan het einde van de lijst met kinderen van een opgegeven bovenliggende knoop. Als het opgegeven kind een verwijzing is naar een bestaande knoop in het document, verplaatst appendChild() deze van zijn huidige positie naar de nieuwe positie (er is geen vereiste om de knoop uit zijn bovenliggende knoop te verwijderen voordat hij aan een andere knoop wordt toegevoegd). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Zend een Event naar het opgegeven [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchroon) en roep de betrokken EventListeners in de juiste volgorde aan. De normale regels voor gebeurtenisverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet‑beheerde bronnen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | De hasChildNodes()‑methode van de Node‑interface retourneert een booleaanse waarde die aangeeft of de gegeven [`Node`](../../com.aspose.html.dom/node/) kindknooppunten heeft of niet. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | De insertBefore()‑methode van de Node‑interface voegt een knoop in vóór een referentieknoop als kind van een opgegeven bovenliggende knoop. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | De isDefaultNamespace()‑methode van de Node‑interface accepteert een package‑URI als argument. Ze retourneert een booleaanse waarde die true is als het package het standaardpackage is op de gegeven knoop en false anders. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | De isEqualNode()‑methode van de [`Node`](../../com.aspose.html.dom/node/)‑interface test of twee knopen gelijk zijn. Twee knopen zijn gelijk wanneer ze hetzelfde type hebben, dezelfde bepalende kenmerken (voor elementen bijvoorbeeld hun ID, aantal kinderen, enzovoort), hun attributen overeenkomen, enzovoort. De specifieke set gegevenspunten die moeten overeenkomen varieert afhankelijk van de typen knopen. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | De isSameNode()‑methode van de Node‑interface is een legacy‑alias voor de === strikte gelijkheidsoperator. Met andere woorden, ze test of twee knopen identiek zijn (ofwel of ze naar hetzelfde object verwijzen). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | De lookupNamespaceURI()‑methode van de Node‑interface neemt een prefix als parameter en retourneert de package‑URI die eraan gekoppeld is op de gegeven knoop, indien gevonden (anders null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | De lookupPrefix()‑methode van de Node‑interface retourneert een string die de prefix voor een gegeven package‑URI bevat, indien aanwezig, en anders null. Wanneer meerdere prefixes mogelijk zijn, wordt de eerste prefix geretourneerd. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Plaatst alle [`Text`](../../com.aspose.html.dom/text/) knopen in de volledige diepte van de subboom onder deze Node, inclusief attribuutknooppunten, in een \"normale\" vorm waarbij alleen de structuur (bijv. [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), en [`entity references`](../../com.aspose.html.dom/entityreference/)) de [`Text`](../../com.aspose.html.dom/text/) knopen scheidt, d.w.z. er zijn geen aangrenzende Text‑knooppunten of lege Text‑knooppunten. Dit kan worden gebruikt om te garanderen dat de DOM‑weergave van een document hetzelfde is als wanneer het zou worden opgeslagen en opnieuw geladen, en is nuttig wanneer bewerkingen (zoals XPointer [XPointer] opzoekingen) die afhankelijk zijn van een bepaalde documentboomstructuur moeten worden gebruikt. Als de parameter \"normalize-characters\" van het [`DOMConfiguration`](../../com.aspose.html/configuration/) object dat is gekoppeld aan de [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) true is, zal deze methode ook de tekens van de Text‑knooppunten volledig normaliseren. |
| [querySelector](../../com.aspose.html.dom/documentfragment/queryselector/)(String) | Retourneert het eerste Element in het document dat aan de selector voldoet |
| [querySelectorAll](../../com.aspose.html.dom/documentfragment/queryselectorall/)(String) | Retourneert een NodeList van alle Elements in het document die aan de selector voldoen |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | De removeChild()-methode van de Node-interface verwijdert een kindknooppunt uit de DOM en retourneert het verwijderde knooppunt. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Vervangt het kindknooppunt oldChild door newChild in de lijst van kinderen, en retourneert het oldChild-knooppunt. Als newChild een [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) object is, wordt oldChild vervangen door alle [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) kinderen, die in dezelfde volgorde worden ingevoegd. Als newChild al in de boom aanwezig is, wordt het eerst verwijderd. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Retourneert een String die deze instantie vertegenwoordigt. |

### Zie ook

* class [ShadowRoot](../../com.aspose.html.dom/shadowroot/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
