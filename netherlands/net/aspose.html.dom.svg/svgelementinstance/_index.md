---
title: Class SVGElementInstance
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Svg.SVGElementInstance klas. Het hoofdobject van elke schaduwboom met gebruikselementen implementeert de SVGUseElementShadowRootinterface. Deze interface definieert momenteel geen uitbreidingen op de eigenschappen en methoden die zijn gedefinieerd voor de ShadowRootinterface en DocumentOrShadowRootmix. De boom die op dit knooppunt is geworteld is echter volledig alleenlezen vanuit het perspectief van auteursscripts.
type: docs
weight: 2030
url: /nl/net/aspose.html.dom.svg/svgelementinstance/
---
## SVGElementInstance class

Het hoofdobject van elke schaduwboom met gebruikselementen implementeert de SVGUseElementShadowRoot-interface. Deze interface definieert momenteel geen uitbreidingen op de eigenschappen en methoden die zijn gedefinieerd voor de ShadowRoot-interface en DocumentOrShadowRoot-mix. De boom die op dit knooppunt is geworteld, is echter volledig alleen-lezen vanuit het perspectief van auteursscripts.

```csharp
public class SVGElementInstance : ShadowRoot
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | Een NamedNodeMap met de attributen van dit knooppunt (als het een Element is) of anders nul. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | De absolute basis-URI van dit knooppunt of null als de implementatie geen absolute URI kon verkrijgen. |
| [ChildElementCount](../../aspose.html.dom/documentfragment/childelementcount/) { get; } | Retourneert het huidige aantal elementknooppunten dat kinderen zijn van dit element. 0 als dit element geen onderliggende knooppunten heeft die van nodeType 1. zijn |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Een NodeList die alle kinderen van deze node bevat. Als er geen kinderen zijn, is dit een NodeList die geen nodes bevat.. |
| [Children](../../aspose.html.dom/documentfragment/children/) { get; } | Retourneert de onderliggende elementen van het huidige element. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Het eerste kind van dit knooppunt. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| [FirstElementChild](../../aspose.html.dom/documentfragment/firstelementchild/) { get; } | Retourneert het eerste onderliggende elementknooppunt van dit element. null als dit element geen onderliggende elementen heeft. |
| [Host](../../aspose.html.dom/shadowroot/host/) { get; } | Host is een element dat deze ShadowRoot bevat. |
| [InnerHTML](../../aspose.html.dom/documentfragment/innerhtml/) { get; set; } | Retourneert een HTML- of XML-fragment dat de inhoud van het element vertegenwoordigt. Kan worden ingesteld om de inhoud van het element te vervangen door knooppunten die zijn geparseerd uit de opgegeven tekenreeks. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Het laatste kind van dit knooppunt. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| [LastElementChild](../../aspose.html.dom/documentfragment/lastelementchild/) { get; } | Geeft het laatste onderliggende elementknooppunt van dit element terug. null als dit element geen onderliggende elementen heeft. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Retourneert het lokale deel van de gekwalificeerde naam van dit knooppunt. Voor knooppunten van een ander type dan ELEMENT_NODE en ATTRIBUTE_NODE en knooppunten gemaakt met een DOM Level 1-methode, zoals Document.createElement(), is dit altijd null. |
| [Mode](../../aspose.html.dom/shadowroot/mode/) { get; } | Modus waarin deze ShadowRoot werkt. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | De naamruimte-URI van dit knooppunt, of null als deze niet is gespecificeerd. |
| [NextElementSibling](../../aspose.html.dom/documentfragment/nextelementsibling/) { get; } | Retourneert het volgende elementknooppunt van dit element. null als dit element geen element-zusterknooppunten heeft die na dit element in de documentstructuur komen. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Het knooppunt dat onmiddellijk volgt op dit knooppunt. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| override [NodeName](../../aspose.html.dom/documentfragment/nodename/) { get; } | De naam van dit knooppunt, afhankelijk van het type. |
| override [NodeType](../../aspose.html.dom/documentfragment/nodetype/) { get; } | Een code die het type van het onderliggende object vertegenwoordigt. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | De waarde van dit knooppunt, afhankelijk van het type. |
| [OuterHTML](../../aspose.html.dom/documentfragment/outerhtml/) { get; set; } | Retourneert een HTML- of XML-fragment dat het element en zijn inhoud vertegenwoordigt. Kan worden ingesteld om het element te vervangen door knooppunten die zijn geparseerd uit de opgegeven tekenreeks. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | Het documentobject dat aan dit knooppunt is gekoppeld. Dit is ook het documentobject dat wordt gebruikt om nieuwe knooppunten te maken. Als dit knooppunt een document is of een documenttype dat nog niet met een document wordt gebruikt, is dit null. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Haalt de ouder op[`Element`](../../aspose.html.dom/element/) van dit knooppunt. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | De ouder van dit knooppunt. Alle knooppunten, behalve Attr, Document, DocumentFragment, Entity en Notation kunnen een ouder hebben. Als een knooppunt echter net is gemaakt en nog niet aan de boom is toegevoegd, of als het uit de boom is verwijderd, is dit null. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | Het naamruimtevoorvoegsel van dit knooppunt, of null als het niet is gespecificeerd. Als het is gedefinieerd als null, heeft het instellen ervan geen effect |
| [PreviousElementSibling](../../aspose.html.dom/documentfragment/previouselementsibling/) { get; } | Retourneert het vorige elementknooppunt van dit element. null als dit element geen element-zusterknooppunten heeft die vóór dit element in de documentstructuur komen. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Het knooppunt dat onmiddellijk aan dit knooppunt voorafgaat. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| override [TextContent](../../aspose.html.dom/documentfragment/textcontent/) { get; set; } | Dit attribuut retourneert de tekstinhoud van dit knooppunt en zijn afstammelingen. Als het is gedefinieerd als null, heeft het instellen ervan geen effect. Bij het instellen worden alle mogelijke kinderen die dit knooppunt heeft verwijderd en, als de nieuwe tekenreeks niet leeg of null is, vervangen door een enkel tekstknooppunt dat de tekenreeks bevat waarop dit kenmerk is ingesteld. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Voegt het knooppunt newChild toe aan het einde van de lijst met kinderen van dit knooppunt. Als de newChild al in de stamboom staat, wordt deze eerst verwijderd. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Retourneert een duplicaat van dit knooppunt, dwz dient als generieke kopieerconstructor voor knooppunten. Het gedupliceerde knooppunt heeft geen ouder (parentNode is null) en geen gebruikersgegevens. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Retourneert een duplicaat van dit knooppunt, dwz dient als generieke kopieerconstructor voor knooppunten. Het gedupliceerde knooppunt heeft geen ouder (parentNode is null) en geen gebruikersgegevens. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Met deze methode kunnen gebeurtenissen worden verzonden naar het gebeurtenismodel van de implementatie. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijmaken, vrijgeven of resetten van onbeheerde bronnen. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | Geeft terug of dit knooppunt (als het een element is) attributen heeft |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Geeft terug of dit knooppunt kinderen heeft. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Voegt het knooppunt in vóór het bestaande onderliggende knooppunt. Als kind null is, voegt u een knooppunt in aan het einde van de lijst met kinderen. Als kind een DocumentFragment-object is, worden alle kinderen in dezelfde volgorde ingevoegd vóór kind. Als het kind al in de boom zit, wordt het eerst verwijderd. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Deze methode controleert of de opgegeven naamruimte-URI de standaard naamruimte is of niet. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Test of twee knooppunten gelijk zijn. Deze methode test op gelijkheid van knooppunten, niet gelijkheid (dwz of de twee knooppunten verwijzingen naar hetzelfde object zijn), wat kan worden getest met Node.isSameNode(). Alle knooppunten die hetzelfde zijn, zullen ook gelijk zijn, hoewel het omgekeerde misschien niet waar is. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Geeft terug of dit knooppunt hetzelfde knooppunt is als het opgegeven knooppunt. Deze methode biedt een manier om te bepalen of twee Node-referenties die door de implementatie worden geretourneerd, naar hetzelfde object verwijzen. Wanneer twee Node-referenties verwijzingen zijn naar hetzelfde object, zelfs via een proxy, kunnen de referenties volledig onderling uitwisselbaar worden gebruikt, zodat alle attributen dezelfde waarden hebben en het aanroepen van dezelfde DOM-methode voor beide referenties altijd exact hetzelfde effect heeft. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Zoek de naamruimte-URI op die is gekoppeld aan het opgegeven voorvoegsel, beginnend vanaf dit knooppunt. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Zoek het voorvoegsel op dat is gekoppeld aan de opgegeven naamruimte-URI, beginnend bij dit knooppunt. De standaard naamruimtedeclaraties worden door deze methode genegeerd. Zie Namespace Prefix Lookup voor meer informatie over het algoritme dat door deze methode wordt gebruikt. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Zet alle tekstknooppunten in de volledige diepte van de subboom onder dit knooppunt, inclusief attribuutknooppunten, in een "normale" vorm waar alleen structuur (bijv. elementen, opmerkingen, verwerkingsinstructies, CDATA-secties en entiteitsreferenties) tekst scheidt knooppunten, dwz er zijn geen aangrenzende tekstknooppunten of lege tekstknooppunten. Dit kan worden gebruikt om ervoor te zorgen dat de DOM-weergave van een document hetzelfde is alsof het is opgeslagen en opnieuw geladen, en is handig wanneer bewerkingen (zoals XPointer [XPointer]-lookups) die afhankelijk zijn van een bepaalde documentboomstructuur, moeten worden uitgevoerd. worden gebruikt. Als de parameter "normalize-characters" van het DOMConfiguration-object dat aan het Node.ownerDocument is gekoppeld, waar is, zal deze methode ook de tekens van de tekstknooppunten volledig normaliseren. |
| [QuerySelector](../../aspose.html.dom/documentfragment/queryselector/)(string) | Retourneert het eerste element in het document dat overeenkomt met selector |
| [QuerySelectorAll](../../aspose.html.dom/documentfragment/queryselectorall/)(string) | Retourneert een NodeList van alle elementen in het document, die overeenkomen met selector |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Verwijdert het onderliggende knooppunt aangegeven door oldChild uit de lijst met onderliggende items en retourneert het. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../../aspose.html.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../../aspose.html.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../../aspose.html.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Vervangt het onderliggende knooppunt oldChild door newChild in de lijst met onderliggende items en retourneert het oldChild-knooppunt. Als newChild een DocumentFragment-object is, wordt oldChild vervangen door alle DocumentFragment-kinderen, die in dezelfde volgorde worden ingevoegd. Als de newChild al in de stamboom staat, wordt deze eerst verwijderd. |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

### Zie ook

* class [ShadowRoot](../../aspose.html.dom/shadowroot/)
* naamruimte [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* montage [Aspose.HTML](../../)


