---
title: Class SVGTextContentElement
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Svg.SVGTextContentElement klass. SVGTextContentElement ärvs av olika textrelaterade gränssnitt såsom SVGTextElement SVGTSpanElement SVGTrefElement SVGAltGlyphElement och SVGTextPathElement. För metoderna i det här gränssnittet som refererar till dessa ett indexnummer till ett tecken till ett indexnummer till ett tecken tolkas som ett index till en UTF16kodenhet respektive ett antal UTF16kodenheter. Detta är för överensstämmelse med DOM Level 2 Core där metoder på CharacterDatagränssnittet använder UTF16kodenheter som index och räknas i teckendatan. Om textinnehållet i ett textelement till exempel är ett enda icke BMPtecken såsom U10000 och sedan anropande av getNumberOfChars på det elementet returnerar 2 eftersom det finns två UTF16kodenheter surrogatparet som används för att representera det ena tecknet.
type: docs
weight: 2340
url: /sv/net/aspose.html.dom.svg/svgtextcontentelement/
---
## SVGTextContentElement class

SVGTextContentElement ärvs av olika textrelaterade gränssnitt, såsom SVGTextElement, SVGTSpanElement, SVGTrefElement, SVGAltGlyphElement och SVGTextPathElement. För metoderna i det här gränssnittet som refererar till dessa ett indexnummer till ett tecken till ett indexnummer till ett tecken tolkas som ett index till en UTF-16-kodenhet respektive ett antal UTF-16-kodenheter. Detta är för överensstämmelse med DOM Level 2 Core, där metoder på CharacterData-gränssnittet använder UTF-16-kodenheter som index och räknas i teckendatan. Om textinnehållet i ett "text"-element till exempel är ett enda icke- BMP-tecken, såsom U+10000, och sedan anropande av getNumberOfChars på det elementet returnerar 2 eftersom det finns två UTF-16-kodenheter (surrogatparet) som används för att representera det ena tecknet.

```csharp
public class SVGTextContentElement : SVGGraphicsElement
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Attributes](../../aspose.html.dom/element/attributes/) { get; } | En NamedNodeMap som innehåller attributen för denna nod (om det är ett element) eller null på annat sätt. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | Den absoluta bas-URI för denna nod eller noll om implementeringen inte kunde erhålla en absolut URI. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount/) { get; } | Returnerar det aktuella antalet elementnoder som är barn till detta element. 0 om detta element inte har några underordnade noder som är av nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | En nodlista som innehåller alla underordnade till denna nod. Om det inte finns några underordnade, är detta en nodlista som inte innehåller några noder.. |
| [Children](../../aspose.html.dom/element/children/) { get; } | Returnerar de underordnade elementen för det aktuella elementet. |
| [ClassList](../../aspose.html.dom/element/classlist/) { get; } | Returnerar en levande DOMTokenList som innehåller tokens som tagits emot från att analysera "class"-attributet. |
| [ClassName](../../aspose.html.dom.svg/svgelement/classname/) { get; } | Motsvarar attributet 'class' på det givna elementet. |
| [ClassName](../../aspose.html.dom/element/classname/) { get; set; } | Klassattributet för elementet. Det här attributet har bytt namn till due till konflikter med nyckelordet "class" som exponeras av många språk. Se klassattributdefinitionen i HTML 4.01. |
| [FarthestViewportElement](../../aspose.html.dom.svg/svggraphicselement/farthestviewportelement/) { get; } | Det mest avlägsna förfaderns "svg"-element. Null om det aktuella elementet är det yttersta svg-elementet. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Det första barnet i denna nod. Om det inte finns någon sådan nod returnerar detta null. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | Returnerar den första underordnade elementnoden för detta element. null om detta element inte har några underordnade element. |
| [Id](../../aspose.html.dom.svg/svgelement/id/) { get; set; } | Värdet för 'id'-attributet på det givna elementet, eller den tomma strängen om 'id' inte finns. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | Returnerar ett fragment av HTML eller XML som representerar elementets innehåll. Kan ställas in för att ersätta innehållet i elementet med noder tolkade från den givna strängen. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Det sista underordnade av denna nod. Om det inte finns någon sådan nod returnerar detta null. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | Returnerar den sista underordnade elementnoden för detta element. null om detta element inte har några underordnade element. |
| [LengthAdjust](../../aspose.html.dom.svg/svgtextcontentelement/lengthadjust/) { get; } | Motsvarar attributet 'lengthAdjust' på det givna elementet. Värdet måste vara en av längdjusteringskonstanterna som definieras i detta gränssnitt. |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | Returnerar den lokala delen av det kvalificerade namnet på denna nod. För noder av någon annan typ än ELEMENT_NODE och ATTRIBUTE_NODE och noder skapade med en DOM Level 1-metod, som Document.createElement(), är detta alltid null. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | Namnutrymmets URI för denna nod, eller null om den är ospecificerad. |
| [NearestViewportElement](../../aspose.html.dom.svg/svggraphicselement/nearestviewportelement/) { get; } | Elementet som etablerade den aktuella visningsporten. Ofta är det närmaste förfaderns "svg"-element. Null om det aktuella elementet är det yttersta svg-elementet. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | Returnerar nästa syskonelementnod för detta element. null om detta element inte har några element syskonnoder som kommer efter detta i dokumentträdet. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Noden omedelbart efter denna nod. Om det inte finns någon sådan nod returnerar detta null. |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | Namnet på denna nod, beroende på dess typ. |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | En kod som representerar typen av det underliggande objektet. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Värdet för denna nod, beroende på dess typ. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | Returnerar ett fragment av HTML eller XML som representerar elementet och dess innehåll. Kan ställas in för att ersätta elementet med noder tolkade från den givna strängen. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | Dokumentobjektet som är associerat med denna nod. Detta är också dokumentobjektet som används för att skapa nya noder. När denna nod är ett dokument eller en DocumentType som inte används med något dokument ännu, är detta null. |
| [OwnerSVGElement](../../aspose.html.dom.svg/svgelement/ownersvgelement/) { get; } | Det närmaste förfaderns "svg"-element. Null om det givna elementet är det yttersta svg-elementet. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Hämtar föräldern[`Element`](../../aspose.html.dom/element/) av denna nod. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Föräldern till denna nod. Alla noder, utom Attr, Document, DocumentFragment, Entity och Notation kan ha en förälder. Men om en nod just har skapats och ännu inte lagts till i trädet, eller om den har tagits bort från trädet, är detta null. |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | Namnutrymmesprefixet för denna nod, eller null om det är ospecificerat. När den är definierad som null har inställningen ingen effekt |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | Returnerar föregående syskonelementnod för detta element. null om detta element inte har några element syskonnoder som kommer före detta i dokumentträdet. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Noden omedelbart före denna nod. Om det inte finns någon sådan nod returnerar detta null. |
| [RequiredExtensions](../../aspose.html.dom.svg/svggraphicselement/requiredextensions/) { get; } | Motsvarar attributet 'requiredExtensions' på det givna elementet. |
| [RequiredFeatures](../../aspose.html.dom.svg/svggraphicselement/requiredfeatures/) { get; } | Motsvarar attributet 'requiredFeatures' på det givna elementet. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo/) { get; } | Typinformationen som är associerad med detta element. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | Returnerar shadowRoot lagrad på detta element eller null om det är stängt. |
| [Style](../../aspose.html.dom.svg/svgelement/style/) { get; } | Motsvarar attributet 'stil' på det givna elementet. Om användaragenten inte stöder styling med CSS måste detta attribut alltid ha värdet null. |
| [SystemLanguage](../../aspose.html.dom.svg/svggraphicselement/systemlanguage/) { get; } | Motsvarar attributet 'systemLanguage' på det givna elementet. |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | Namnet på elementet. |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | Detta attribut returnerar textinnehållet för denna nod och dess avkomlingar. När den är definierad som null har inställningen ingen effekt. Vid inställning tas alla möjliga barn bort som denna nod kan ha och, om den nya strängen inte är tom eller null, ersätts den av en enda textnod som innehåller strängen som detta attribut är inställt på. |
| [TextLength](../../aspose.html.dom.svg/svgtextcontentelement/textlength/) { get; } | Motsvarar attributet 'textLength' på det givna elementet. |
| [Transform](../../aspose.html.dom.svg/svggraphicselement/transform/) { get; } | Motsvarar attributet 'transform' på det givna elementet. |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement/) { get; } | Elementet som etablerade den aktuella visningsporten. Ofta är det närmaste förfaderns "svg"-element. Null om det givna elementet är det yttersta svg-elementet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Denna metod tillåter registrering av händelseavlyssnare på händelsemålet. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Denna metod tillåter registrering av händelseavlyssnare på händelsemålet. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Denna metod tillåter registrering av händelseavlyssnare på händelsemålet. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Lägger till noden newChild i slutet av listan över underordnade till denna nod. Om det nya barnet redan finns i trädet tas det först bort. |
| [AttachShadow](../../aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Skapar skuggrot och fäster den till aktuellt element. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Returnerar en dubblett av denna nod, dvs fungerar som en generisk kopiakonstruktor för noder. Dubblettnoden har ingen förälder (parentNode är null) och inga användardata. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Returnerar en dubblett av denna nod, dvs fungerar som en generisk kopiakonstruktor för noder. Dubblettnoden har ingen förälder (parentNode är null) och inga användardata. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Denna metod tillåter sändning av händelser till implementeringshändelsemodellen. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| [GetAttribute](../../aspose.html.dom/element/getattribute/)(string) | Hämtar ett attributvärde efter namn. |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode/)(string) | Hämtar en attributnod efter namn. |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens/)(string, string) | Hämtar en Attr-nod efter lokalt namn och namnutrymmes-URI. |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens/)(string, string) | Hämtar ett attributvärde efter lokalt namn och namnutrymmes-URI. |
| [GetBBox](../../aspose.html.dom.svg/svggraphicselement/getbbox/)() | Returnerar den snäva begränsningsrutan i det aktuella användarutrymmet (dvs. efter applicering av 'transform'-attributet, om det finns) på geometrin för alla ingående grafiska element, exklusive sträckning, klippning, maskering och filtereffekter). Observera att getBBox måste returnera den faktiska begränsningsrutan vid den tidpunkt då metoden anropades, även om elementet ännu inte har renderats. |
| [GetComputedTextLength](../../aspose.html.dom.svg/svgtextcontentelement/getcomputedtextlength/)() | Den totala summan av alla förskottsvärden från att rendera alla tecken i detta element, inklusive förskottsvärdet på glyferna (horisontellt eller vertikalt), effekten av egenskaperna "kerning", "bokstavsmellanrum" och "ord- mellanrum" och justeringar på grund av attributen "dx" och "dy" på "tspan"-element. För icke-renderande miljöer ska användaragenten göra rimliga antaganden om glyfmetrik. |
| [GetCTM](../../aspose.html.dom.svg/svggraphicselement/getctm/)() | Returnerar transformationsmatrisen från nuvarande användarenheter (dvs. efter applicering av "transform"-attributet, om det finns) till viewport-koordinatsystemet för närmasteViewportElement. |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | Returnerar ett levande NodeList-objekt som innehåller alla element i dokumentet som har alla klasser som anges i argument. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | Returnerar en nodlista över alla underordnade element med ett givet taggnamn, i dokumentordning. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | Returnerar en nodlista med alla underordnade element med ett givet lokalt namn och namnområdes-URI i dokumentordning. |
| [GetNumberOfChars](../../aspose.html.dom.svg/svgtextcontentelement/getnumberofchars/)() | Returnerar det totala antalet tecken som är tillgängliga för rendering inom det aktuella elementet, vilket inkluderar refererade tecken från 'tref'-referens, oavsett om de kommer att renderas. Detta är i praktiken ekvivalent med längden på Node::textContent-attributet från DOM Level 3 Core ([DOM3], avsnitt 1.4), om det attributet också utökade 'tref'-element. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| [GetScreenCTM](../../aspose.html.dom.svg/svggraphicselement/getscreenctm/)() | Returnerar transformationsmatrisen från nuvarande användarenheter (dvs. efter applicering av "transform"-attributet, om det finns) till den överordnade användaragentens meddelande om en "pixel". För visningsenheter representerar detta idealiskt en fysisk skärmpixel. För andra enheter eller miljöer där fysiska pixelstorlekar inte är kända, kan en algoritm som liknar CSS2-definitionen av en "pixel" istället användas. Observera att null returneras om detta element inte är kopplat till dokumentträdet. Denna metod skulle ha fått ett mer passande namn som getClientCTM, men namnet getScreenCTM behålls av historiska skäl. |
| [HasAttribute](../../aspose.html.dom/element/hasattribute/)(string) | Returnerar sant när ett attribut med ett givet namn anges på detta element eller har ett standardvärde, annars falskt. |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens/)(string, string) | Returnerar sant när ett attribut med ett givet lokalt namn och namnområdes-URI anges på detta element eller har ett standardvärde, annars falskt. |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes/)() | Returnerar om denna nod (om det är ett element) har några attribut |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Returnerar om denna nod har några barn. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Infogar noden före det befintliga underordnade nodbarnet. Om child är null, infoga nod i slutet av listan med barn. Om child är ett DocumentFragment-objekt, infogas alla dess underordnade, i samma ordning, före child. Om barnet redan finns i trädet tas det först bort. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Den här metoden kontrollerar om det angivna namnutrymmet-URI är standardnamnutrymmet eller inte. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Testar om två noder är lika. Denna metod testar likadana noder, inte likhet (dvs om de två noderna är referenser till samma objekt) som kan testas med Node.isSameNode(). Alla noder som är lika kommer också att vara lika, även om det omvända kanske inte är sant. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Returnerar om denna nod är samma nod som den givna. Den här metoden ger ett sätt att avgöra om två nodreferenser som returneras av implementeringen refererar till samma objekt. När två nodreferenser är referenser till samma objekt, även om genom en proxy, kan referenserna användas helt utbytbart, så att alla attribut har samma värden och att anropa samma DOM-metod på någon av referenserna har alltid exakt samma effekt. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Slå upp namnutrymmes-URI som är kopplat till det givna prefixet, med början från denna nod. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Slå upp prefixet som är associerat med den givna namnutrymmes-URI, med början från denna nod. Standardnamnområdesdeklarationerna ignoreras av den här metoden. Se Namnutrymmesprefixsökning för detaljer om algoritmen som används av denna metod. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Lägger alla textnoder i underträdets fulla djup under denna nod, inklusive attributnoder, i en "normal" form där endast struktur (t.ex. element, kommentarer, bearbetningsinstruktioner, CDATA-sektioner och entitetsreferenser) separerar text noder, dvs det finns varken intilliggande textnoder eller tomma textnoder. Detta kan användas för att säkerställa att DOM-vyn för ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer (som XPointer [XPointer]-uppslagningar) som beror på en viss dokumentträdstruktur ska användas. Om parametern "normalize-characters" för DOMConfiguration-objektet som är kopplat till Node.ownerDocument är sant, kommer denna metod också att helt normalisera tecknen i Textnoderna. |
| [QuerySelector](../../aspose.html.dom/element/queryselector/)(string) | Returnerar det första elementet i dokumentet, som matchar selector |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall/)(string) | Returnerar en nodlista över alla element i dokumentet, som matchar selector |
| [Remove](../../aspose.html.dom/element/remove/)() | Tar bort den här instansen. |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute/)(string) | Tar bort ett attribut efter namn. |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode/)(Attr) | Tar bort den angivna attributnoden. |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens/)(string, string) | Tar bort ett attribut efter lokalt namn och namnutrymmes-URI. |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Tar bort den underordnade noden som indikeras av oldChild från listan över barn och returnerar den. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) tas bort från en[`EventTarget`](../../aspose.html.dom/eventtarget/) medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) tas bort från en[`EventTarget`](../../aspose.html.dom/eventtarget/) medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) tas bort från en[`EventTarget`](../../aspose.html.dom/eventtarget/) medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Ersätter barnnoden oldChild med newChild i listan över barn och returnerar oldChild-noden. Om newChild är ett DocumentFragment-objekt ersätts oldChild av alla DocumentFragment-underordnade, som infogas i samma ordning. Om det nya barnet redan finns i trädet tas det först bort. |
| [SetAttribute](../../aspose.html.dom/element/setattribute/)(string, string) | Lägger till ett nytt attribut. Om ett attribut med det namnet redan finns i elementet ändras dess värde till att vara värdet parameter |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode/)(Attr) | Lägger till en ny attributnod. Om ett attribut med det namnet (nodeName) redan finns i elementet ersätts det med det nya. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens/)(Attr) | Lägger till ett nytt attribut. Om ett attribut med det lokala namnet och den namnutrymmets URI redan finns i elementet ersätts det av det nya. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens/)(string, string, string) | Lägger till ett nytt attribut. Om ett attribut med samma lokala namn och namnområdes-URI redan finns på elementet, ändras dess prefix till att vara prefixdelen av qualifiedName och dess värde ändras till värdeparametern. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute/)(string, bool) | Om parametern isId är sant, deklarerar den här metoden att det angivna attributet är ett användarbestämt ID-attribut. |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode/)(Attr, bool) | Om parametern isId är sant, deklarerar den här metoden att det angivna attributet är ett användarbestämt ID-attribut. |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens/)(string, string, bool) | Om parametern isId är sant, deklarerar den här metoden att det angivna attributet är ett användarbestämt ID-attribut. |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [LENGTHADJUST_SPACING](../../aspose.html.dom.svg/svgtextcontentelement/lengthadjust_spacing/) | Motsvarar värdet 'mellanrum'. |
| const [LENGTHADJUST_SPACINGANDGLYPHS](../../aspose.html.dom.svg/svgtextcontentelement/lengthadjust_spacingandglyphs/) | Motsvarar värdet 'spacingAndGlyphs'. |
| const [LENGTHADJUST_UNKNOWN](../../aspose.html.dom.svg/svgtextcontentelement/lengthadjust_unknown/) | Uppräkningen sattes till ett värde som inte är en av fördefinierade typer. Det är ogiltigt att försöka definiera ett nytt värde av denna typ eller att försöka ändra ett befintligt värde till denna typ. |

### Se även

* class [SVGElement](../svgelement/)
* class [SVGGraphicsElement](../svggraphicselement/)
* namnutrymme [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* hopsättning [Aspose.HTML](../../)

