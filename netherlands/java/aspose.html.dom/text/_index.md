---
title: "Tekstklasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.Text‑klasse. De Text‑interface erft van CharacterData en vertegenwoordigt de tekstuele inhoud, aangeduid als character data, in XML van een Element of Attr"
type: docs

url: /nl/java/com.aspose.html.dom/text/
---
## Text class

De Text-interface erft van CharacterData en vertegenwoordigt de tekstuele inhoud (in XML karaktergegevens genoemd) van een Element of Attr.

```java
public class Text : CharacterData
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) De alleen-lezen baseURI-eigenschap van de Node-interface retourneert de absolute basis-URL van het document dat het knooppunt bevat. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) De alleen-lezen childNodes-eigenschap van de Node-interface retourneert een live [`NodeList`](../../com.aspose.html.collections/nodelist/) van kindknooppunten van het opgegeven element waarbij het eerste kindknooppunt index 0 krijgt. Kindknooppunten omvatten elementen, tekst en commentaren. |
| [data](../../com.aspose.html.dom/characterdata/data/) { get; set; } | De character data van het knooppunt dat deze interface implementeert. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) De alleen-lezen firstChild-eigenschap van de [`Node`](../node/) interface retourneert het eerste kind van de node in de boom, of null als de node geen kinderen heeft. |
| [getIsElementContentWhitespace](../../com.aspose.html.dom/text/iselementcontentwhitespace/) Retourneert of dit tekstknooppunt element‑content whitespace bevat, vaak abusievelijk "negeerbare whitespace" genoemd. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) De alleen-lezen lastChild-eigenschap van de [`Node`](../node/) interface retourneert het laatste kind van de node. Als de ouder een element is, is het kind doorgaans een elementnode, een tekstnode of een commentaarnode. Het retourneert null als er geen kindelementen zijn |
| [getLength](../../com.aspose.html.dom/characterdata/length/) Het aantal 16‑bit eenheden dat beschikbaar is via data en de subStringData‑methode hieronder. Dit kan de waarde nul hebben, d.w.z. CharacterData‑knooppunten kunnen leeg zijn. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Retourneert het lokale deel van de gekwalificeerde naam van dit knooppunt. Voor knooppunten van elk type behalve [`ELEMENT_NODE`](../node/element_node/) en [`ATTRIBUTE_NODE`](../node/attribute_node/) en knooppunten die zijn gemaakt met een DOM‑Level‑1‑methode, zoals [`Document.createElement()`](../document/createelement/), is dit altijd null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) De alleen‑lezen‑eigenschap Element.packageURI retourneert de pakket‑URI van het element, of null als het element zich niet in een pakket bevindt. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) De alleen-lezen nextSibling-eigenschap van de [`Node`](../node/) interface retourneert de node die direct volgt op de opgegeven node in de [`childNodes`](../node/childnodes/) van hun ouder, of retourneert null als de opgegeven node het laatste kind in het bovenliggende element is. |
| [getNodeName](../../com.aspose.html.dom/text/nodename/) De naam van dit knooppunt, afhankelijk van het type. |
| [getNodeType](../../com.aspose.html.dom/text/nodetype/) Een code die het type van het onderliggende object vertegenwoordigt. |
| [nodeValue](../../com.aspose.html.dom/text/nodevalue/) { get; set; } | De waarde van deze node, afhankelijk van het type. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) De alleen‑lezen ownerDocument‑eigenschap van de Node‑interface retourneert het bovenliggende documentobject van het knooppunt. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) De alleen-lezen parentElement-eigenschap van [`Node`](../node/) interface retourneert de ouder-`[`Element`](../element/)` van de DOM-node, of null als de node geen ouder heeft, of als de ouder geen DOM Element is. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) De alleen‑lezen parentNode‑eigenschap van de Node‑interface retourneert de ouder van het opgegeven knooppunt in de DOM‑boom. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | De alleen‑lezen‑eigenschap prefix retourneert het pakket‑prefix van het opgegeven element, of null als er geen prefix is opgegeven. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) De alleen-lezen previousSibling-eigenschap van de [`Node`](../node/) interface retourneert de node die direct voorafgaat aan de opgegeven node in de [`childNodes`](../node/firstchild/) lijst van zijn ouder, of null als de opgegeven node de eerste in die lijst is. |
| [textContent](../../com.aspose.html.dom/text/textcontent/) { get; set; } | Dit attribuut retourneert de tekstinhoud van dit knooppunt en zijn afstammelingen. Wanneer het op null is ingesteld, heeft het instellen geen effect. Bij het instellen worden eventuele kinderen die dit knooppunt kan hebben verwijderd en, als de nieuwe string niet leeg of null is, vervangen door één Text‑knooppunt dat de string bevat waar dit attribuut op wordt gezet. |
| [getWholeText](../../com.aspose.html.dom/text/wholetext/) Retourneert alle tekst van Text‑knooppunten die logisch aangrenzend zijn aan dit knooppunt, samengevoegd in documentvolgorde. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | De addEventListener() methode van de [`EventTarget `](../eventtarget/) interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | De addEventListener()‑methode van de [EventTarget ](T:com.aspose.html.dom.EventTarget)interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | De addEventListener()‑methode van de [EventTarget ](T:com.aspose.html.dom.EventTarget)interface stelt een functie in die wordt aangeroepen telkens wanneer het opgegeven evenement aan het doel wordt geleverd. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | De appendChild()‑methode van de Node‑interface voegt een knoop toe aan het einde van de lijst met kinderen van een opgegeven bovenliggende knoop. Als het opgegeven kind een verwijzing is naar een bestaande knoop in het document, verplaatst appendChild() deze van zijn huidige positie naar de nieuwe positie (er is geen vereiste om de knoop uit zijn bovenliggende knoop te verwijderen voordat hij aan een andere knoop wordt toegevoegd). |
| [appendData](../../com.aspose.html.dom/characterdata/appenddata/)(String) | Voeg de String toe aan het einde van de character data van het knooppunt. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | De cloneNode()‑methode van de Node‑interface retourneert een duplicaat van de knoop waarop deze methode is aangeroepen. De parameter bepaalt of de in een knoop aanwezige subboom ook wordt gekloond al dan niet. |
| [deleteData](../../com.aspose.html.dom/characterdata/deletedata/)(int, int) | Verwijder een bereik van 16‑bit eenheden uit het knooppunt. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Zend een Event naar het opgegeven [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchroon) en roep de betrokken EventListeners in de juiste volgorde aan. De normale regels voor gebeurtenisverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig verzonden events met [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet‑beheerde bronnen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | De hasChildNodes() methode van de Node-interface retourneert een booleaanse waarde die aangeeft of de opgegeven [`Node`](../node/) kindnodes heeft of niet. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | De insertBefore()‑methode van de Node‑interface voegt een knoop in vóór een referentieknoop als kind van een opgegeven bovenliggende knoop. |
| [insertData](../../com.aspose.html.dom/characterdata/insertdata/)(int, String) | Voeg een String in op de opgegeven 16‑bit eenheids‑offset. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | De isDefaultNamespace()‑methode van de Node‑interface accepteert een package‑URI als argument. Ze retourneert een booleaanse waarde die true is als het package het standaardpackage is op de gegeven knoop en false anders. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | De isEqualNode() methode van de [`Node`](../node/) interface test of twee nodes gelijk zijn. Twee nodes zijn gelijk wanneer ze hetzelfde type hebben, dezelfde kenmerkende eigenschappen (voor elementen, hun ID, aantal kinderen, enzovoort), hun attributen overeenkomen, enzovoort. De specifieke set gegevenspunten die moeten overeenkomen varieert afhankelijk van de typen van de nodes. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | De isSameNode()‑methode van de Node‑interface is een legacy‑alias voor de === strikte gelijkheidsoperator. Met andere woorden, ze test of twee knopen identiek zijn (ofwel of ze naar hetzelfde object verwijzen). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | De lookupNamespaceURI()‑methode van de Node‑interface neemt een prefix als parameter en retourneert de package‑URI die eraan gekoppeld is op de gegeven knoop, indien gevonden (anders null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | De lookupPrefix()‑methode van de Node‑interface retourneert een string die de prefix voor een gegeven package‑URI bevat, indien aanwezig, en anders null. Wanneer meerdere prefixes mogelijk zijn, wordt de eerste prefix geretourneerd. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Plaatst alle `Text`‑knooppunten op de volledige diepte van de subboom onder deze Node, inclusief attribuutknooppunten, in een "normale" vorm waarbij alleen de structuur (bijv. [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), en [`entity references`](../entityreference/)) de `Text`‑knooppunten scheidt, d.w.z. er zijn geen aangrenzende Text‑knooppunten noch lege Text‑knooppunten. Dit kan worden gebruikt om te verzekeren dat de DOM‑weergave van een document hetzelfde is als wanneer het is opgeslagen en opnieuw geladen, en is nuttig wanneer bewerkingen (zoals XPointer‑[XPointer] opzoekingen) die afhankelijk zijn van een specifieke documentboomstructuur moeten worden gebruikt. Als de parameter "normalize-characters" van het [`DOMConfiguration`](../../com.aspose.html/configuration/) object dat is gekoppeld aan de [`Node.ownerDocument`](../node/ownerdocument/) waar is, zal deze methode ook de tekens van de Text‑knooppunten volledig normaliseren. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | De removeChild()-methode van de Node-interface verwijdert een kindknooppunt uit de DOM en retourneert het verwijderde knooppunt. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Deze methode maakt het verwijderen van event listeners van het event target mogelijk. Als een listener wordt verwijderd terwijl er een event wordt verwerkt, wordt deze niet geactiveerd door de huidige acties. Event Listeners kunnen nooit meer worden aangeroepen nadat ze zijn verwijderd. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Vervangt de kindnode oldChild door newChild in de lijst van kinderen, en retourneert de oldChild-node. Als newChild een [`DocumentFragment`](../documentfragment/) object is, wordt oldChild vervangen door alle [`DocumentFragment`](../documentfragment/) kinderen, die in dezelfde volgorde worden ingevoegd. Als newChild al in de boom aanwezig is, wordt deze eerst verwijderd. |
| [replaceData](../../com.aspose.html.dom/characterdata/replacedata/)(int, int, String) | Vervang de tekens beginnend bij de opgegeven 16‑bit eenheids‑offset door de opgegeven String. |
| [replaceWholeText](../../com.aspose.html.dom/text/replacewholetext/)(String) | Vervangt de tekst van het huidige node en alle logisch-aangrenzende tekstnodes met de opgegeven tekst. Alle logisch-aangrenzende tekstnodes worden verwijderd, inclusief het huidige node, tenzij het de ontvanger van de vervangende tekst was. |
| [splitText](../../com.aspose.html.dom/text/splittext/)(int) | Splitst dit node op in twee nodes op de opgegeven offset, waarbij beide als broers in de boom behouden blijven. |
| [subStringData](../../com.aspose.html.dom/characterdata/subStringdata/)(int, int) | Haalt een bereik aan gegevens uit het node. |
| [toString](../../com.aspose.html.dom/characterdata/toString/)() | Retourneert een String die deze instantie vertegenwoordigt. |

### Zie ook

* class [CharacterData](../characterdata/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
