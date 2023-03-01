---
title: Class HTMLDocument
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.HTMLDocument klas. EenHTMLDocument is de root van de HTMLhiërarchie en bevat de volledige inhoud. Naast het bieden van toegang tot de hiërarchie biedt ook enkele gemaksmethoden voor toegang tot bepaalde sets van informatie uit het document.
type: docs
weight: 3190
url: /nl/net/aspose.html/htmldocument/
---
## HTMLDocument class

Een`HTMLDocument` is de root van de HTML-hiërarchie en bevat de volledige inhoud. Naast het bieden van toegang tot de hiërarchie, biedt ook enkele gemaksmethoden voor toegang tot bepaalde sets van -informatie uit het document.

De volgende eigenschappen zijn gedeprecieerd ten gunste van de overeenkomstige voor de`LICHAAM` element. In DOM Level 2, de methode`getElementById` is geërfd van de`Document` interface waar het naartoe is verplaatst.

Zie ook de[Documentobjectmodel (DOM) Niveau 2 HTML-specificatie](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109) .

```csharp
public class HTMLDocument : Document, IDocumentCSS
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [HTMLDocument](htmldocument/#constructor)() | Initialiseert een nieuw exemplaar van het`HTMLDocument` klasse. |
| [HTMLDocument](htmldocument/#constructor_1)(Configuration) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klasse. |
| [HTMLDocument](htmldocument/#constructor_2)(RequestMessage) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_10)(string) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_4)(Url) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_3)(RequestMessage, Configuration) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_8)(Stream, string) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Het laden van documenten begint vanaf de huidige positie in de stream. |
| [HTMLDocument](htmldocument/#constructor_6)(Stream, Url) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Het laden van documenten begint vanaf de huidige positie in de stream. |
| [HTMLDocument](htmldocument/#constructor_11)(string, Configuration) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_14)(string, string) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_12)(string, Url) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_5)(Url, Configuration) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_9)(Stream, string, Configuration) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Het laden van documenten begint vanaf de huidige positie in de stream. |
| [HTMLDocument](htmldocument/#constructor_7)(Stream, Url, Configuration) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Het laden van documenten begint vanaf de huidige positie in de stream. |
| [HTMLDocument](htmldocument/#constructor_15)(string, string, Configuration) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_13)(string, Url, Configuration) | Initialiseert een nieuw exemplaar van het`HTMLDocument` klas. Constructor werkt synchroon, het wacht op het laden van alle externe bronnen (afbeeldingen, scripts, enz.). Gebruik de methode om het document asynchroon te laden[`Navigate`](../../aspose.html.dom/document/navigate/) of de overbelasting ervan. Of u kunt het laden van sommige externe bronnen uitschakelen door de juiste vlaggen in te stellen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Anchors](../../aspose.html/htmldocument/anchors/) { get; } | Een verzameling van alle anker (`A` ) elementen in een document met een waarde voor de`naam`attribuut. Vanwege achterwaartse compatibiliteit bevat de geretourneerde set ankers alleen die ankers die zijn gemaakt met de`naam` attribuut, niet die gemaakt met de`ID kaart` attribuut. Merk op dat in [[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801) ], de `naam` attribuut (zie paragraaf 4.10) heeft geen semantiek en is alleen aanwezig voor legacy user agents: de`ID kaart` attribuut wordt in plaats daarvan gebruikt. Gebruikers zouden de voorkeur moeten geven aan de herhalingsmechanismen die door [[DOM Niveau 2 Traversal](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113) ] in plaats van. |
| [Applets](../../aspose.html/htmldocument/applets/) { get; } | Een verzameling van alle`VOORWERP` elementen die applets en`APPLET` (verouderde) elementen in een document. |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | Een NamedNodeMap met de attributen van dit knooppunt (als het een Element is) of anders nul. |
| override [BaseURI](../../aspose.html.dom/document/baseuri/) { get; } | De absolute basis-URI van dit knooppunt of null als de implementatie geen absolute URI kon verkrijgen. |
| [Body](../../aspose.html/htmldocument/body/) { get; set; } | Het element dat de inhoud van het document bevat. In documenten met`LICHAAM` inhoud, retourneert de`LICHAAM` element. In frameset-documenten retourneert dit de buitenste `FRAMESET` element. |
| [CharacterSet](../../aspose.html.dom/document/characterset/) { get; } | Haalt de codering van het document op. |
| [Charset](../../aspose.html.dom/document/charset/) { get; } | Haalt de codering van het document op. |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount/) { get; } | Retourneert het huidige aantal elementknooppunten dat kinderen zijn van dit element. 0 als dit element geen onderliggende knooppunten heeft die van nodeType 1. zijn |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Een NodeList die alle kinderen van deze node bevat. Als er geen kinderen zijn, is dit een NodeList die geen nodes bevat.. |
| [Children](../../aspose.html.dom/document/children/) { get; } | Geeft de onderliggende elementen terug. |
| [ContentType](../../aspose.html.dom/document/contenttype/) { get; } | Haalt het inhoudstype van het document op. |
| [Context](../../aspose.html.dom/document/context/) { get; } | Haalt de huidige browsercontext op. |
| [DefaultView](../../aspose.html.dom/document/defaultview/) { get; } | Het defaultView IDL-attribuut van de documentinterface, bij ophalen, moet het WindowProxy-object van de browsercontext van dit document retourneren, als dit document een bijbehorende browsecontext heeft, of anders null. |
| [Doctype](../../aspose.html.dom/document/doctype/) { get; } | De documenttypeverklaring die aan dit document is gekoppeld. |
| [DocumentElement](../../aspose.html.dom/document/documentelement/) { get; } | Dit is een handig attribuut dat directe toegang geeft tot het onderliggende knooppunt dat het documentelement van het document is. |
| [DocumentURI](../../aspose.html.dom/document/documenturi/) { get; } | De locatie van het document of null indien niet gedefinieerd of als het document is gemaakt met DOMImplementation.createDocument. |
| [Domain](../../aspose.html/htmldocument/domain/) { get; } | De domeinnaam van de server die het document aanleverde, of `nul` als de server niet kan worden geïdentificeerd met een domeinnaam . |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Het eerste kind van dit knooppunt. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild/) { get; } | Retourneert het eerste onderliggende elementknooppunt van dit element. null als dit element geen onderliggende elementen heeft. |
| [Forms](../../aspose.html/htmldocument/forms/) { get; } | Een verzameling van alle vormen van een document. |
| [Images](../../aspose.html/htmldocument/images/) { get; } | Een verzameling van alle`IMG` elementen in een document. Het gedrag is beperkt tot`IMG` elementen voor achterwaartse compatibiliteit. Zoals voorgesteld door [[HTML4.01](http://www.w3.org/TR/1999/REC-html401-19991224)], om afbeeldingen op te nemen, mogen auteurs de`VOORWERP` element of de`IMG` element. Het wordt daarom aanbevolen om dit attribuut niet te gebruiken om de afbeeldingen in het document te vinden, maar`getElementsByTagName` met HTML 4.01 of`getElementsByTagNameNS` met XHTML 1.0. |
| [Implementation](../../aspose.html.dom/document/implementation/) { get; } | Het DOMImplementatieobject dat dit document afhandelt. |
| [InputEncoding](../../aspose.html.dom/document/inputencoding/) { get; } | Haalt de codering van het document op. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Het laatste kind van dit knooppunt. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild/) { get; } | Geeft het laatste onderliggende elementknooppunt van dit element terug. null als dit element geen onderliggende elementen heeft. |
| [Links](../../aspose.html/htmldocument/links/) { get; } | Een verzameling van alles`GEBIED` elementen en anker ( `A` ) elementen in een document met een waarde voor de `href` attribuut. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Retourneert het lokale deel van de gekwalificeerde naam van dit knooppunt. Voor knooppunten van een ander type dan ELEMENT_NODE en ATTRIBUTE_NODE en knooppunten gemaakt met een DOM Level 1-methode, zoals Document.createElement(), is dit altijd null. |
| [Location](../../aspose.html.dom/document/location/) { get; } | De locatie van het document. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | De naamruimte-URI van dit knooppunt, of null als deze niet is gespecificeerd. |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling/) { get; } | Retourneert het volgende elementknooppunt van dit element. null als dit element geen element-zusterknooppunten heeft die na dit element in de documentstructuur komen. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Het knooppunt dat onmiddellijk volgt op dit knooppunt. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| override [NodeName](../../aspose.html.dom/document/nodename/) { get; } | De naam van dit knooppunt, afhankelijk van het type. |
| override [NodeType](../../aspose.html.dom/document/nodetype/) { get; } | Een code die het type van het onderliggende object vertegenwoordigt. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | De waarde van dit knooppunt, afhankelijk van het type. |
| [Origin](../../aspose.html.dom/document/origin/) { get; } | Haalt de oorsprong van het document op. |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument/) { get; } | Haalt het eigenaarsdocument op. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Haalt de ouder op[`Element`](../../aspose.html.dom/element/) van dit knooppunt. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | De ouder van dit knooppunt. Alle knooppunten, behalve Attr, Document, DocumentFragment, Entity en Notation kunnen een ouder hebben. Als een knooppunt echter net is gemaakt en nog niet aan de boom is toegevoegd, of als het uit de boom is verwijderd, is dit null. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | Het naamruimtevoorvoegsel van dit knooppunt, of null als het niet is gespecificeerd. Als het is gedefinieerd als null, heeft het instellen ervan geen effect |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling/) { get; } | Retourneert het vorige elementknooppunt van dit element. null als dit element geen element-zusterknooppunten heeft die vóór dit element in de documentstructuur komen. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Het knooppunt dat onmiddellijk aan dit knooppunt voorafgaat. Als zo'n knooppunt niet bestaat, retourneert dit null. |
| [ReadyState](../../aspose.html.dom/document/readystate/) { get; } | Retourneert de gereedheid van het document. Het "laden" terwijl het document wordt geladen, "interactief" zodra het klaar is met parseren maar nog steeds subbronnen laadt, en "voltooid" zodra het is geladen. |
| [Referrer](../../aspose.html/htmldocument/referrer/) { get; } | Retourneert de URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt) van de pagina die naar deze pagina linkte. De waarde is een lege string als de gebruiker rechtstreeks naar de pagina is genavigeerd (niet via een link, maar bijvoorbeeld via een bladwijzer). |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking/) { get; set; } | Een attribuut dat specificeert of foutcontrole wordt afgedwongen of niet. Indien ingesteld op false, is de implementatie vrij om niet elk mogelijk foutgeval te testen dat normaal is gedefinieerd voor DOM-bewerkingen, en geen DOMException op te roepen voor DOM-bewerkingen of fouten te rapporteren tijdens het gebruik van Document.normalizeDocument(). In geval van een fout is het gedrag ongedefinieerd. Dit kenmerk is standaard waar. |
| [StyleSheets](../../aspose.html.dom/document/stylesheets/) { get; } | Een lijst met alle stijlbladen die expliciet zijn gekoppeld aan of ingebed in een document. Voor HTML-documenten omvat dit externe stijlbladen, opgenomen via het HTML LINK-element, en inline STYLE-elementen. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent/) { get; set; } | Dit attribuut retourneert de tekstinhoud van dit knooppunt en zijn afstammelingen. Als het is gedefinieerd als null, heeft het instellen ervan geen effect. Bij het instellen worden alle mogelijke kinderen die dit knooppunt heeft verwijderd en, als de nieuwe tekenreeks niet leeg of null is, vervangen door een enkel tekstknooppunt dat de tekenreeks bevat waarop dit kenmerk is ingesteld. |
| [Title](../../aspose.html/htmldocument/title/) { get; set; } | De titel van een document zoals opgegeven door de`TITEL` element in de kop van het document. |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone/) { get; set; } | Een attribuut dat specificeert, als onderdeel van de XML-declaratie, of dit document op zichzelf staat. Dit is niet waar wanneer niet gespecificeerd. |
| [XmlVersion](../../aspose.html.dom/document/xmlversion/) { get; set; } | Een attribuut dat, als onderdeel van de XML-declaratie, het versienummer van dit document specificeert. Als er geen declaratie is en als dit document de functie "XML" ondersteunt, is de waarde "1.0". Als dit document de "XML"-functie niet ondersteunt, is de waarde altijd null. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Voegt het knooppunt newChild toe aan het einde van de lijst met kinderen van dit knooppunt. Als de newChild al in de stamboom staat, wordt deze eerst verwijderd. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Retourneert een duplicaat van dit knooppunt, dwz dient als generieke kopieerconstructor voor knooppunten. Het gedupliceerde knooppunt heeft geen ouder (parentNode is null) en geen gebruikersgegevens. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Retourneert een duplicaat van dit knooppunt, dwz dient als generieke kopieerconstructor voor knooppunten. Het gedupliceerde knooppunt heeft geen ouder (parentNode is null) en geen gebruikersgegevens. |
| [CreateAttribute](../../aspose.html.dom/document/createattribute/)(string) | Creëert een Attr van de opgegeven naam. |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens/)(string, string) | Maakt een kenmerk van de gegeven gekwalificeerde naam en naamruimte-URI. |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection/)(string) | Maakt een CDATASection-knooppunt waarvan de waarde de opgegeven tekenreeks is. |
| [CreateComment](../../aspose.html.dom/document/createcomment/)(string) | Creëert een commentaarknooppunt op basis van de opgegeven tekenreeks. |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment/)() | Maakt een leeg DocumentFragment-object aan. |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype/)(string, string, string, string) | Creëert een DocumentType-knooppunt. |
| [CreateElement](../../aspose.html.dom/document/createelement/)(string) | Creëert een element van het gespecificeerde type. Merk op dat de geretourneerde instantie de Element-interface implementeert, dus attributen kunnen rechtstreeks op het geretourneerde object worden gespecificeerd. |
| [CreateElementNS](../../aspose.html.dom/document/createelementns/)(string, string) | Maakt een element van de opgegeven gekwalificeerde naam en naamruimte-URI. |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference/)(string) | Maakt een EntityReference-object. Bovendien, als de entiteit waarnaar wordt verwezen bekend is, wordt de onderliggende lijst van het EntityReference-knooppunt hetzelfde gemaakt als die van het corresponderende Entity-knooppunt. |
| [CreateEvent](../../aspose.html.dom/document/createevent/)(string) | Creëert een[`Event`](../../aspose.html.dom.events/event/) van een type dat wordt ondersteund door de implementatie. |
| [CreateExpression](../../aspose.html.dom/document/createexpression/)(string, IXPathNSResolver) | Maakt een geparseerde XPath-expressie met opgeloste naamruimten. Dit is handig wanneer een expressie opnieuw wordt gebruikt in een toepassing, aangezien het mogelijk maakt om de uitdrukkingsreeks in een efficiëntere interne vorm te compileren en alle naamruimtevoorvoegsels die binnen de uitdrukking voorkomen vooraf op te lossen. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node) | Maak een nieuwe NodeIterator over de substructuur die is geworteld in het gespecificeerde knooppunt. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long) | Maak een nieuwe NodeIterator over de substructuur die is geworteld in het gespecificeerde knooppunt. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Maak een nieuwe NodeIterator over de substructuur die is geworteld in het gespecificeerde knooppunt. |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver/)(Node) | Past elk DOM-knooppunt aan om naamruimten op te lossen, zodat een XPath-expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waar het in het document verscheen. Deze adapter werkt zoals de DOM Level 3-methode`opzoekenNaamruimteURI` op knooppunten bij het oplossen van de namespaceURI van een bepaald voorvoegsel met behulp van de huidige informatie die beschikbaar is in de hiërarchie van het knooppunt op het moment dat lookupNamespaceURI wordt aangeroepen, waarbij ook het impliciete xml-voorvoegsel correct wordt opgelost. |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction/)(string, string) | Maakt een ProcessingInstruction-knooppunt met de opgegeven naam en gegevensreeksen. |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode/)(string) | Maakt een tekstknooppunt op basis van de opgegeven tekenreeks. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node) | Maak een nieuwe TreeWalker over de subboom die is geroot op het gespecificeerde knooppunt. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long) | Maak een nieuwe TreeWalker over de subboom die is geroot op het gespecificeerde knooppunt. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | Maak een nieuwe TreeWalker over de subboom die is geroot op het gespecificeerde knooppunt. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Met deze methode kunnen gebeurtenissen worden verzonden naar het gebeurtenismodel van de implementatie. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijmaken, vrijgeven of resetten van onbeheerde bronnen. |
| [Evaluate](../../aspose.html.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Evalueert een XPath-expressietekenreeks en retourneert indien mogelijk een resultaat van het opgegeven type. |
| [GetElementById](../../aspose.html.dom/document/getelementbyid/)(string) | Geeft het element terug dat een ID-attribuut heeft met de gegeven waarde. Als een dergelijk element niet bestaat, wordt null geretourneerd. Als meer dan één element een ID-attribuut met die waarde heeft, is wat wordt geretourneerd ongedefinieerd. |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname/)(string) | Retourneert een live NodeList-object met alle elementen in het document waarvan alle klassen zijn opgegeven in argument. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname/)(string) | Retourneert een NodeList van alle Elementen in documentvolgorde met een gegeven tagnaam en zijn opgenomen in het document. |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens/)(string, string) | Retourneert een NodeList van alle elementen met een gegeven lokale naam en naamruimte-URI in documentvolgorde. |
| [GetOverrideStyle](../../aspose.html/htmldocument/getoverridestyle/)(Element, string) | Deze methode wordt gebruikt om de override-stijldeclaratie op te halen voor een gespecificeerd element en een gespecificeerd pseudo-element. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | Geeft terug of dit knooppunt (als het een element is) attributen heeft |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Geeft terug of dit knooppunt kinderen heeft. |
| [ImportNode](../../aspose.html.dom/document/importnode/)(Node, bool) | Importeert een knooppunt uit een ander document naar dit document, zonder het bronknooppunt uit het originele document te wijzigen of te verwijderen; deze methode maakt een nieuwe kopie van het bronknooppunt. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Voegt het knooppunt in vóór het bestaande onderliggende knooppunt. Als kind null is, voegt u een knooppunt in aan het einde van de lijst met kinderen. Als kind een DocumentFragment-object is, worden alle kinderen in dezelfde volgorde ingevoegd vóór kind. Als het kind al in de boom zit, wordt het eerst verwijderd. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Deze methode controleert of de opgegeven naamruimte-URI de standaard naamruimte is of niet. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Test of twee knooppunten gelijk zijn. Deze methode test op gelijkheid van knooppunten, niet gelijkheid (dwz of de twee knooppunten verwijzingen naar hetzelfde object zijn), wat kan worden getest met Node.isSameNode(). Alle knooppunten die hetzelfde zijn, zullen ook gelijk zijn, hoewel het omgekeerde misschien niet waar is. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Geeft terug of dit knooppunt hetzelfde knooppunt is als het opgegeven knooppunt. Deze methode biedt een manier om te bepalen of twee Node-referenties die door de implementatie worden geretourneerd, naar hetzelfde object verwijzen. Wanneer twee Node-referenties verwijzingen zijn naar hetzelfde object, zelfs via een proxy, kunnen de referenties volledig onderling uitwisselbaar worden gebruikt, zodat alle attributen dezelfde waarden hebben en het aanroepen van dezelfde DOM-methode voor beide referenties altijd exact hetzelfde effect heeft. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Zoek de naamruimte-URI op die is gekoppeld aan het opgegeven voorvoegsel, beginnend vanaf dit knooppunt. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Zoek het voorvoegsel op dat is gekoppeld aan de opgegeven naamruimte-URI, beginnend bij dit knooppunt. De standaard naamruimtedeclaraties worden door deze methode genegeerd. Zie Namespace Prefix Lookup voor meer informatie over het algoritme dat door deze methode wordt gebruikt. |
| [Navigate](../../aspose.html.dom/document/navigate/)(RequestMessage) | Laadt het document op basis van het opgegeven verzoekobject en vervangt de vorige inhoud. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string) | Laadt het document op de gespecificeerde Uniform Resource Locator (URL) in de huidige instantie en vervangt de vorige inhoud. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Url) | Laadt het document op de gespecificeerde Uniform Resource Locator (URL) in de huidige instantie en vervangt de vorige inhoud. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, string) | Laadt het document vanuit gespecificeerde inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van documenten begint vanaf de huidige positie in de stroom. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, Url) | Laadt het document vanuit gespecificeerde inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van documenten begint vanaf de huidige positie in de stroom. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, string) | Laadt het document vanuit gespecificeerde inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, Url) | Laadt het document vanuit gespecificeerde inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Zet alle tekstknooppunten in de volledige diepte van de subboom onder dit knooppunt, inclusief attribuutknooppunten, in een "normale" vorm waar alleen structuur (bijv. elementen, opmerkingen, verwerkingsinstructies, CDATA-secties en entiteitsreferenties) tekst scheidt knooppunten, dwz er zijn geen aangrenzende tekstknooppunten of lege tekstknooppunten. Dit kan worden gebruikt om ervoor te zorgen dat de DOM-weergave van een document hetzelfde is alsof het is opgeslagen en opnieuw geladen, en is handig wanneer bewerkingen (zoals XPointer [XPointer]-lookups) die afhankelijk zijn van een bepaalde documentboomstructuur, moeten worden uitgevoerd. worden gebruikt. Als de parameter "normalize-characters" van het DOMConfiguration-object dat aan het Node.ownerDocument is gekoppeld, waar is, zal deze methode ook de tekens van de tekstknooppunten volledig normaliseren. |
| [QuerySelector](../../aspose.html.dom/document/queryselector/)(string) | Retourneert het eerste element in het document dat overeenkomt met selector |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall/)(string) | Retourneert een NodeList van alle elementen in het document, die overeenkomen met selector |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Verwijdert het onderliggende knooppunt aangegeven door oldChild uit de lijst met onderliggende items en retourneert het. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../../aspose.html.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../../aspose.html.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../../aspose.html.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| override [RenderTo](../../aspose.html/htmldocument/renderto/)(IDevice) | Deze methode wordt gebruikt om de inhoud van het huidige document naar het opgegeven apparaat af te drukken. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Vervangt het onderliggende knooppunt oldChild door newChild in de lijst met onderliggende items en retourneert het oldChild-knooppunt. Als newChild een DocumentFragment-object is, wordt oldChild vervangen door alle DocumentFragment-kinderen, die in dezelfde volgorde worden ingevoegd. Als de newChild al in de stamboom staat, wordt deze eerst verwijderd. |
| [Save](../../aspose.html/htmldocument/save/#save)(IOutputStorage) | Slaat de documentinhoud en bronnen op in de uitvoeropslag. |
| [Save](../../aspose.html/htmldocument/save/#save_10)(string) | Slaat het document op in een lokaal bestand gespecificeerd door`pad` Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_5)(Url) | Slaat het document op in een lokaal bestand gespecificeerd door`url` Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_1)(IOutputStorage, HTMLSaveFormat) | Slaat de documentinhoud en bronnen op in de uitvoeropslag. |
| [Save](../../aspose.html/htmldocument/save/#save_2)(IOutputStorage, HTMLSaveOptions) | Slaat de documentinhoud en bronnen op in de uitvoeropslag. |
| [Save](../../aspose.html/htmldocument/save/#save_3)(IOutputStorage, MarkdownSaveOptions) | Slaat de documentinhoud en bronnen op in de uitvoeropslag. |
| [Save](../../aspose.html/htmldocument/save/#save_4)(IOutputStorage, MHTMLSaveOptions) | Slaat de documentinhoud en bronnen op in de uitvoeropslag. |
| [Save](../../aspose.html/htmldocument/save/#save_11)(string, HTMLSaveFormat) | Slaat het document op in een lokaal bestand gespecificeerd door`pad` Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_12)(string, HTMLSaveOptions) | Slaat het document op in een lokaal bestand gespecificeerd door`pad` Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_13)(string, MarkdownSaveOptions) | Slaat het document op in een lokaal bestand gespecificeerd door`pad` Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_14)(string, MHTMLSaveOptions) | Slaat het document op in een lokaal bestand gespecificeerd door`pad` Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_6)(Url, HTMLSaveFormat) | Slaat het document op in een lokaal bestand gespecificeerd door`url` Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_7)(Url, HTMLSaveOptions) | Slaat het document op in een lokaal bestand gespecificeerd door`url` Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_8)(Url, MarkdownSaveOptions) | Slaat het document op in een lokaal bestand gespecificeerd door`url` Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_9)(Url, MHTMLSaveOptions) | Slaat het document op in een lokaal bestand gespecificeerd door`url` Alle bronnen die in dit document worden gebruikt, worden opgeslagen in in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files". |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |
| [Write](../../aspose.html.dom/document/write/)(params string[]) | Schrijf een tekstreeks naar een documentstroom geopend door open(). Merk op dat de functie een document zal produceren dat niet noodzakelijkerwijs wordt aangestuurd door een DTD en daarom kan zijn een ongeldig resultaat opleveren in de context van het document. |
| [WriteLn](../../aspose.html.dom/document/writeln/)(params string[]) | Schrijf een tekstreeks gevolgd door een teken voor een nieuwe regel naar een document stroom geopend door open(). Merk op dat de functie will een document produceert dat niet noodzakelijkerwijs wordt aangestuurd door een DTD en kan daarom een ongeldig resultaat opleveren in de context van the document |

## Evenementen

| Naam | Beschrijving |
| --- | --- |
| event [OnAbort](../../aspose.html.dom/document/onabort/) | Haalt of stelt gebeurtenishandler in voor OnAbort-gebeurtenis. |
| event [OnBlur](../../aspose.html.dom/document/onblur/) | Haalt of stelt gebeurtenishandler in voor OnBlur-gebeurtenis. |
| event [OnCancel](../../aspose.html.dom/document/oncancel/) | Haalt of stelt gebeurtenishandler in voor OnCancel-gebeurtenis. |
| event [OnCanplay](../../aspose.html.dom/document/oncanplay/) | Haalt of stelt gebeurtenishandler in voor OnCanplay-gebeurtenis. |
| event [OnCanPlayThrough](../../aspose.html.dom/document/oncanplaythrough/) | Haalt of stelt gebeurtenishandler in voor OnCanPlayThrough-gebeurtenis. |
| event [OnChange](../../aspose.html.dom/document/onchange/) | Haalt of stelt gebeurtenishandler in voor OnChange-gebeurtenis. |
| event [OnClick](../../aspose.html.dom/document/onclick/) | Haalt of stelt gebeurtenishandler in voor OnClick-gebeurtenis. |
| event [OnCueChange](../../aspose.html.dom/document/oncuechange/) | Haalt of stelt gebeurtenishandler in voor OnCueChange-gebeurtenis. |
| event [OnDblClick](../../aspose.html.dom/document/ondblclick/) | Haalt of stelt gebeurtenishandler in voor OnDblClick-gebeurtenis. |
| event [OnDurationChange](../../aspose.html.dom/document/ondurationchange/) | Haalt of stelt gebeurtenishandler in voor OnDurationChange-gebeurtenis. |
| event [OnEmptied](../../aspose.html.dom/document/onemptied/) | Haalt of stelt gebeurtenishandler in voor OnEmptied-gebeurtenis. |
| event [OnEnded](../../aspose.html.dom/document/onended/) | Haalt of stelt gebeurtenishandler in voor OnEnded-gebeurtenis. |
| event [OnError](../../aspose.html.dom/document/onerror/) | Haalt of stelt gebeurtenishandler in voor OnError-gebeurtenis. |
| event [OnFocus](../../aspose.html.dom/document/onfocus/) | Krijgt of stelt gebeurtenishandler in voor OnFocus-gebeurtenis. |
| event [OnInput](../../aspose.html.dom/document/oninput/) | Haalt of stelt gebeurtenishandler in voor OnInput-gebeurtenis. |
| event [OnInvalid](../../aspose.html.dom/document/oninvalid/) | Haalt of stelt gebeurtenishandler in voor OnInvalid-gebeurtenis. |
| event [OnKeyDown](../../aspose.html.dom/document/onkeydown/) | Haalt of stelt gebeurtenishandler in voor OnKeyDown-gebeurtenis. |
| event [OnKeyPress](../../aspose.html.dom/document/onkeypress/) | Krijgt of stelt gebeurtenishandler in voor OnKeyPress-gebeurtenis. |
| event [OnKeyUp](../../aspose.html.dom/document/onkeyup/) | Haalt of stelt gebeurtenishandler in voor OnKeyUp-gebeurtenis. |
| event [OnLoad](../../aspose.html.dom/document/onload/) | Haalt of stelt gebeurtenishandler in voor OnLoad-gebeurtenis. |
| event [OnLoadedData](../../aspose.html.dom/document/onloadeddata/) | Haalt of stelt gebeurtenishandler in voor OnLoadedData-gebeurtenis. |
| event [OnLoadedMetadata](../../aspose.html.dom/document/onloadedmetadata/) | Haalt of stelt gebeurtenishandler in voor OnLoadedMetadata-gebeurtenis. |
| event [OnLoadStart](../../aspose.html.dom/document/onloadstart/) | Haalt of stelt gebeurtenishandler in voor OnLoadStart-gebeurtenis. |
| event [OnMouseDown](../../aspose.html.dom/document/onmousedown/) | Haalt of stelt gebeurtenishandler in voor OnMouseDown-gebeurtenis. |
| event [OnMouseEnter](../../aspose.html.dom/document/onmouseenter/) | Haalt gebeurtenishandler op of stelt deze in voor OnMouseEnter-gebeurtenis. |
| event [OnMouseLeave](../../aspose.html.dom/document/onmouseleave/) | Haalt of stelt gebeurtenishandler in voor OnMouseLeave-gebeurtenis. |
| event [OnMouseMove](../../aspose.html.dom/document/onmousemove/) | Haalt of stelt gebeurtenishandler in voor OnMouseMove-gebeurtenis. |
| event [OnMouseOut](../../aspose.html.dom/document/onmouseout/) | Haalt of stelt gebeurtenishandler in voor OnMouseOut-gebeurtenis. |
| event [OnMouseOver](../../aspose.html.dom/document/onmouseover/) | Haalt of stelt gebeurtenishandler in voor OnMouseOver-gebeurtenis. |
| event [OnMouseUp](../../aspose.html.dom/document/onmouseup/) | Haalt of stelt gebeurtenishandler in voor OnMouseUp-gebeurtenis. |
| event [OnMouseWheel](../../aspose.html.dom/document/onmousewheel/) | Haalt of stelt gebeurtenishandler in voor OnMouseWheel-gebeurtenis. |
| event [OnPause](../../aspose.html.dom/document/onpause/) | Haalt of stelt gebeurtenishandler in voor OnPause-gebeurtenis. |
| event [OnPlay](../../aspose.html.dom/document/onplay/) | Krijgt of stelt gebeurtenishandler in voor OnPlay-gebeurtenis. |
| event [OnPlaying](../../aspose.html.dom/document/onplaying/) | Haalt of stelt gebeurtenishandler in voor OnPlaying-gebeurtenis. |
| event [OnProgress](../../aspose.html.dom/document/onprogress/) | Haalt of stelt gebeurtenishandler in voor OnProgress-gebeurtenis. |
| event [OnRateChange](../../aspose.html.dom/document/onratechange/) | Haalt of stelt gebeurtenishandler in voor OnRateChange-gebeurtenis. |
| event [OnReadyStateChange](../../aspose.html.dom/document/onreadystatechange/) | Haalt of stelt gebeurtenishandler in voor OnReadyStateChange-gebeurtenis. |
| event [OnReset](../../aspose.html.dom/document/onreset/) | Haalt of stelt gebeurtenishandler in voor OnReset-gebeurtenis. |
| event [OnResize](../../aspose.html.dom/document/onresize/) | Haalt of stelt gebeurtenishandler in voor OnResize-gebeurtenis. |
| event [OnScroll](../../aspose.html.dom/document/onscroll/) | Haalt of stelt gebeurtenishandler in voor OnScroll-gebeurtenis. |
| event [OnSeeked](../../aspose.html.dom/document/onseeked/) | Haalt of stelt gebeurtenishandler in voor OnSeeked-gebeurtenis. |
| event [OnSeeking](../../aspose.html.dom/document/onseeking/) | Haalt of stelt gebeurtenishandler in voor OnSeeking-gebeurtenis. |
| event [OnSelect](../../aspose.html.dom/document/onselect/) | Haalt of stelt gebeurtenishandler in voor OnSelect-gebeurtenis. |
| event [OnShow](../../aspose.html.dom/document/onshow/) | Haalt of stelt gebeurtenishandler in voor OnShow-gebeurtenis. |
| event [OnStalled](../../aspose.html.dom/document/onstalled/) | Krijgt of stelt gebeurtenishandler in voor OnStalled-gebeurtenis. |
| event [OnSubmit](../../aspose.html.dom/document/onsubmit/) | Haalt of stelt gebeurtenishandler in voor OnSubmit-gebeurtenis. |
| event [OnSuspend](../../aspose.html.dom/document/onsuspend/) | Haalt gebeurtenishandler op of stelt deze in voor OnSuspend-gebeurtenis. |
| event [OnTimeUpdate](../../aspose.html.dom/document/ontimeupdate/) | Haalt of stelt gebeurtenishandler in voor OnTimeUpdate-gebeurtenis. |
| event [OnToggle](../../aspose.html.dom/document/ontoggle/) | Haalt of stelt gebeurtenishandler in voor OnToggle-gebeurtenis. |
| event [OnVolumeChange](../../aspose.html.dom/document/onvolumechange/) | Haalt of stelt gebeurtenishandler in voor OnVolumeChange-gebeurtenis. |
| event [OnWaiting](../../aspose.html.dom/document/onwaiting/) | Haalt of stelt gebeurtenishandler in voor OnWaiting-gebeurtenis. |

### Zie ook

* class [Document](../../aspose.html.dom/document/)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss/)
* naamruimte [Aspose.Html](../../aspose.html/)
* montage [Aspose.HTML](../../)


