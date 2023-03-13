---
title: Class HTMLNoScriptElement
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.HTMLNoScriptElement klass. Skriptsatser. Se NOSCRIPTelementdefinitionen i HTML 4.01.
type: docs
weight: 3420
url: /sv/net/aspose.html/htmlnoscriptelement/
---
## HTMLNoScriptElement class

Skriptsatser. Se NOSCRIPT-elementdefinitionen i HTML 4.01.

Se även[Dokumentobjektmodell (DOM) Nivå 2 HTML-specifikation](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109) .

```csharp
public class HTMLNoScriptElement : HTMLElement
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
| [ClassName](../../aspose.html/htmlelement/classname/) { get; set; } | Klassattributet för elementet. Det här attributet har bytt namn på grund av på grund av konflikter med nyckelordet "class" som exponerats av många språk. Se klassattributdefinitionen i HTML 4.01. |
| [Dir](../../aspose.html/htmlelement/dir/) { get; set; } | Anger basriktningen för riktningsneutral text och riktningen för tabeller. Se dir-attributdefinitionen i HTML 4.01. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Det första barnet i denna nod. Om det inte finns någon sådan nod returnerar detta null. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | Returnerar den första underordnade elementnoden för detta element. null om detta element inte har några underordnade element. |
| [Id](../../aspose.html/htmlelement/id/) { get; set; } | Elementets identifierare. Se definitionen av id-attributet i HTML 4.01. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | Returnerar ett fragment av HTML eller XML som representerar elementets innehåll. Kan ställas in för att ersätta innehållet i elementet med noder tolkade från den givna strängen. |
| [Lang](../../aspose.html/htmlelement/lang/) { get; set; } | Språkkod definierad i RFC 1766. Se definitionen av langattributet i HTML 4.01. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Det sista underordnade av denna nod. Om det inte finns någon sådan nod returnerar detta null. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | Returnerar den sista underordnade elementnoden för detta element. null om detta element inte har några underordnade element. |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | Returnerar den lokala delen av det kvalificerade namnet på denna nod. För noder av någon annan typ än ELEMENT_NODE och ATTRIBUTE_NODE och noder skapade med en DOM Level 1-metod, som Document.createElement(), är detta alltid null. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | Namnutrymmets URI för denna nod, eller null om den är ospecificerad. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | Returnerar nästa syskonelementnod för detta element. null om detta element inte har några element syskonnoder som kommer efter detta i dokumentträdet. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Noden omedelbart efter denna nod. Om det inte finns någon sådan nod returnerar detta null. |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | Namnet på denna nod, beroende på dess typ. |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | En kod som representerar typen av det underliggande objektet. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Värdet för denna nod, beroende på dess typ. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | Returnerar ett fragment av HTML eller XML som representerar elementet och dess innehåll. Kan ställas in för att ersätta elementet med noder tolkade från den givna strängen. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | Dokumentobjektet som är associerat med denna nod. Detta är också dokumentobjektet som används för att skapa nya noder. När denna nod är ett dokument eller en DocumentType som inte används med något dokument ännu, är detta null. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Hämtar föräldern[`Element`](../../aspose.html.dom/element/) av denna nod. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Föräldern till denna nod. Alla noder, utom Attr, Document, DocumentFragment, Entity och Notation kan ha en förälder. Men om en nod just har skapats och ännu inte lagts till i trädet, eller om den har tagits bort från trädet, är detta null. |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | Namnutrymmesprefixet för denna nod, eller null om det är ospecificerat. När den är definierad som null har inställningen ingen effekt |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | Returnerar föregående syskonelementnod för detta element. null om detta element inte har några element syskonnoder som kommer före detta i dokumentträdet. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Noden omedelbart före denna nod. Om det inte finns någon sådan nod returnerar detta null. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo/) { get; } | Typinformationen som är associerad med detta element. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | Returnerar shadowRoot lagrad på detta element eller null om det är stängt. |
| [Style](../../aspose.html/htmlelement/style/) { get; } | Representerar ett stilattribut som gör att författaren kan tillämpa stilinformation direkt på ett specifikt element. |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | Namnet på elementet. |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | Detta attribut returnerar textinnehållet för denna nod och dess avkomlingar. När den är definierad som null har inställningen ingen effekt. Vid inställning tas alla möjliga barn bort som denna nod kan ha och, om den nya strängen inte är tom eller null, ersätts den av en enda textnod som innehåller strängen som detta attribut är inställt på. |
| [Title](../../aspose.html/htmlelement/title/) { get; set; } | Elementets rådgivande titel. Se titelattributdefinitionen i HTML 4.01. |

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
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | Returnerar ett levande NodeList-objekt som innehåller alla element i dokumentet som har alla klasser som anges i argument. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | Returnerar en nodlista över alla underordnade element med ett givet taggnamn, i dokumentordning. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | Returnerar en nodlista med alla underordnade element med ett givet lokalt namn och namnområdes-URI i dokumentordning. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
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

## evenemang

| namn | Beskrivning |
| --- | --- |
| event [OnAbort](../../aspose.html/htmlelement/onabort/) | Hämtar eller ställer in händelsehanterare för OnAbort-händelse. |
| event [OnBlur](../../aspose.html/htmlelement/onblur/) | Hämtar eller ställer in händelsehanterare för OnBlur-händelse. |
| event [OnCancel](../../aspose.html/htmlelement/oncancel/) | Hämtar eller ställer in händelsehanterare för OnCancel-händelse. |
| event [OnCanplay](../../aspose.html/htmlelement/oncanplay/) | Hämtar eller ställer in händelsehanterare för OnCanplay-händelse. |
| event [OnCanPlayThrough](../../aspose.html/htmlelement/oncanplaythrough/) | Hämtar eller ställer in händelsehanterare för OnCanPlayThrough-händelse. |
| event [OnChange](../../aspose.html/htmlelement/onchange/) | Hämtar eller ställer in händelsehanterare för OnChange-händelse. |
| event [OnClick](../../aspose.html/htmlelement/onclick/) | Hämtar eller ställer in händelsehanterare för OnClick-händelse. |
| event [OnCueChange](../../aspose.html/htmlelement/oncuechange/) | Hämtar eller ställer in händelsehanterare för OnCueChange-händelse. |
| event [OnDblClick](../../aspose.html/htmlelement/ondblclick/) | Hämtar eller ställer in händelsehanterare för OnDblClick-händelse. |
| event [OnDurationChange](../../aspose.html/htmlelement/ondurationchange/) | Hämtar eller ställer in händelsehanterare för OnDurationChange-händelse. |
| event [OnEmptied](../../aspose.html/htmlelement/onemptied/) | Hämtar eller ställer in händelsehanterare för OnEmptied-händelse. |
| event [OnEnded](../../aspose.html/htmlelement/onended/) | Hämtar eller ställer in händelsehanterare för OnEnded-händelse. |
| event [OnError](../../aspose.html/htmlelement/onerror/) | Hämtar eller ställer in händelsehanterare för OnError-händelse. |
| event [OnFocus](../../aspose.html/htmlelement/onfocus/) | Hämtar eller ställer in händelsehanterare för OnFocus-händelse. |
| event [OnInput](../../aspose.html/htmlelement/oninput/) | Hämtar eller ställer in händelsehanterare för OnInput-händelse. |
| event [OnInvalid](../../aspose.html/htmlelement/oninvalid/) | Hämtar eller ställer in händelsehanterare för OnInvalid-händelse. |
| event [OnKeyDown](../../aspose.html/htmlelement/onkeydown/) | Hämtar eller ställer in händelsehanterare för OnKeyDown-händelse. |
| event [OnKeyPress](../../aspose.html/htmlelement/onkeypress/) | Hämtar eller ställer in händelsehanterare för OnKeyPress-händelse. |
| event [OnKeyUp](../../aspose.html/htmlelement/onkeyup/) | Hämtar eller ställer in händelsehanterare för OnKeyUp-händelse. |
| event [OnLoad](../../aspose.html/htmlelement/onload/) | Hämtar eller ställer in händelsehanterare för OnLoad-händelse. |
| event [OnLoadedData](../../aspose.html/htmlelement/onloadeddata/) | Hämtar eller ställer in händelsehanterare för OnLoadedData-händelse. |
| event [OnLoadedMetadata](../../aspose.html/htmlelement/onloadedmetadata/) | Hämtar eller ställer in händelsehanterare för OnLoadedMetadata-händelse. |
| event [OnLoadStart](../../aspose.html/htmlelement/onloadstart/) | Hämtar eller ställer in händelsehanterare för OnLoadStart-händelse. |
| event [OnMouseDown](../../aspose.html/htmlelement/onmousedown/) | Hämtar eller ställer in händelsehanterare för OnMouseDown-händelse. |
| event [OnMouseEnter](../../aspose.html/htmlelement/onmouseenter/) | Hämtar eller ställer in händelsehanterare för OnMouseEnter-händelse. |
| event [OnMouseLeave](../../aspose.html/htmlelement/onmouseleave/) | Hämtar eller ställer in händelsehanterare för OnMouseLeave-händelse. |
| event [OnMouseMove](../../aspose.html/htmlelement/onmousemove/) | Hämtar eller ställer in händelsehanterare för OnMouseMove-händelse. |
| event [OnMouseOut](../../aspose.html/htmlelement/onmouseout/) | Hämtar eller ställer in händelsehanterare för OnMouseOut-händelse. |
| event [OnMouseOver](../../aspose.html/htmlelement/onmouseover/) | Hämtar eller ställer in händelsehanterare för OnMouseOver-händelse. |
| event [OnMouseUp](../../aspose.html/htmlelement/onmouseup/) | Hämtar eller ställer in händelsehanterare för OnMouseUp-händelse. |
| event [OnMouseWheel](../../aspose.html/htmlelement/onmousewheel/) | Hämtar eller ställer in händelsehanterare för OnMouseWheel-händelse. |
| event [OnPause](../../aspose.html/htmlelement/onpause/) | Hämtar eller ställer in händelsehanterare för OnPause-händelse. |
| event [OnPlay](../../aspose.html/htmlelement/onplay/) | Hämtar eller ställer in händelsehanterare för OnPlay-händelse. |
| event [OnPlaying](../../aspose.html/htmlelement/onplaying/) | Hämtar eller ställer in händelsehanterare för OnPlaying-händelse. |
| event [OnProgress](../../aspose.html/htmlelement/onprogress/) | Hämtar eller ställer in händelsehanterare för OnProgress-händelse. |
| event [OnRateChange](../../aspose.html/htmlelement/onratechange/) | Hämtar eller ställer in händelsehanterare för OnRateChange-händelse. |
| event [OnReset](../../aspose.html/htmlelement/onreset/) | Hämtar eller ställer in händelsehanterare för OnReset-händelse. |
| event [OnResize](../../aspose.html/htmlelement/onresize/) | Hämtar eller ställer in händelsehanterare för OnResize-händelse. |
| event [OnScroll](../../aspose.html/htmlelement/onscroll/) | Hämtar eller ställer in händelsehanterare för OnScroll-händelse. |
| event [OnSeeked](../../aspose.html/htmlelement/onseeked/) | Hämtar eller ställer in händelsehanterare för OnSeeked-händelse. |
| event [OnSeeking](../../aspose.html/htmlelement/onseeking/) | Hämtar eller ställer in händelsehanterare för OnSeeking-händelse. |
| event [OnSelect](../../aspose.html/htmlelement/onselect/) | Hämtar eller ställer in händelsehanterare för OnSelect-händelse. |
| event [OnShow](../../aspose.html/htmlelement/onshow/) | Hämtar eller ställer in händelsehanterare för OnShow-händelse. |
| event [OnStalled](../../aspose.html/htmlelement/onstalled/) | Hämtar eller ställer in händelsehanterare för OnStalled-händelse. |
| event [OnSubmit](../../aspose.html/htmlelement/onsubmit/) | Hämtar eller ställer in händelsehanterare för OnSubmit-händelse. |
| event [OnSuspend](../../aspose.html/htmlelement/onsuspend/) | Hämtar eller ställer in händelsehanterare för OnSuspend-händelse. |
| event [OnTimeUpdate](../../aspose.html/htmlelement/ontimeupdate/) | Hämtar eller ställer in händelsehanterare för OnTimeUpdate-händelse. |
| event [OnToggle](../../aspose.html/htmlelement/ontoggle/) | Hämtar eller ställer in händelsehanterare för OnToggle-händelse. |
| event [OnVolumeChange](../../aspose.html/htmlelement/onvolumechange/) | Hämtar eller ställer in händelsehanterare för OnVolumeChange-händelse. |
| event [OnWaiting](../../aspose.html/htmlelement/onwaiting/) | Hämtar eller ställer in händelsehanterare för OnWaiting-händelse. |

### Se även

* class [HTMLElement](../htmlelement/)
* namnutrymme [Aspose.Html](../../aspose.html/)
* hopsättning [Aspose.HTML](../../)


