---
title: Class HTMLDocument
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.HTMLDocument klass. AnHTMLdokument är roten till HTMLhierarkin och innehåller hela innehållet. Förutom att ge åtkomst till hierarkin tillhandahåller den också några bekvämlighetsmetoder för att komma åt vissa uppsättningar av information från dokumentet.
type: docs
weight: 3190
url: /sv/net/aspose.html/htmldocument/
---
## HTMLDocument class

An`HTML-dokument` är roten till HTML-hierarkin och innehåller hela innehållet. Förutom att ge åtkomst till hierarkin, tillhandahåller den också några bekvämlighetsmetoder för att komma åt vissa uppsättningar av information från dokumentet.

Följande egenskaper har fasats ut till förmån för motsvarande för`KROPP` element. I DOM nivå 2, metoden`getElementById` ärvs från`Dokumentera` gränssnitt dit det flyttades till.

Se även[Dokumentobjektmodell (DOM) Nivå 2 HTML-specifikation](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109) .

```csharp
public class HTMLDocument : Document, IDocumentCSS
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [HTMLDocument](htmldocument/#constructor)() | Initierar en ny instans av`HTMLDocument` class. |
| [HTMLDocument](htmldocument/#constructor_1)(Configuration) | Initierar en ny instans av`HTMLDocument` class. |
| [HTMLDocument](htmldocument/#constructor_2)(RequestMessage) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_10)(string) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_4)(Url) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_3)(RequestMessage, Configuration) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_8)(Stream, string) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Dokumentladdning startar från den aktuella positionen i strömmen. |
| [HTMLDocument](htmldocument/#constructor_6)(Stream, Url) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Dokumentladdning startar från den aktuella positionen i strömmen. |
| [HTMLDocument](htmldocument/#constructor_11)(string, Configuration) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_14)(string, string) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_12)(string, Url) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_5)(Url, Configuration) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_9)(Stream, string, Configuration) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Dokumentladdning startar från den aktuella positionen i strömmen. |
| [HTMLDocument](htmldocument/#constructor_7)(Stream, Url, Configuration) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Dokumentladdning startar från den aktuella positionen i strömmen. |
| [HTMLDocument](htmldocument/#constructor_15)(string, string, Configuration) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_13)(string, Url, Configuration) | Initierar en ny instans av`HTMLDocument` klass. Constructor fungerar synkront, den väntar på att alla externa resurser laddas (bilder, skript, etc.). Använd metoden för att ladda dokument asynkront[`Navigate`](../../aspose.html.dom/document/navigate/) eller dess överbelastningar. Eller så kan du inaktivera laddning av vissa externa resurser genom att ställa in lämpliga flaggor i[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Anchors](../../aspose.html/htmldocument/anchors/) { get; } | En samling av alla ankare (`A` ) element i ett dokument med ett värde för`namn`attribut. På grund av bakåtkompatibilitet innehåller den returnerade uppsättningen ankare endast de ankare som skapats med`namn` attribut, inte de som skapats med`id` attribut. Observera att i [[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801) ], `namn` attribut (se avsnitt 4.10) har ingen semantik och finns endast för äldre användaragenter:`id` attributet används istället. Användare bör föredra iteratormekanismerna som tillhandahålls av [[DOM Level 2 Traversal](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113) ] istället. |
| [Applets](../../aspose.html/htmldocument/applets/) { get; } | En samling av alla`OBJEKT` element som inkluderar applets och`APPLET` (utfasade) element i ett dokument. |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | En NamedNodeMap som innehåller attributen för denna nod (om det är ett element) eller null på annat sätt. |
| override [BaseURI](../../aspose.html.dom/document/baseuri/) { get; } | Den absoluta bas-URI för denna nod eller noll om implementeringen inte kunde erhålla en absolut URI. |
| [Body](../../aspose.html/htmldocument/body/) { get; set; } | Elementet som innehåller innehållet för dokumentet. I dokument med`KROPP` innehållet, returnerar`KROPP` element. I ramuppsättningsdokument returnerar detta den yttersta `RAMSET` element. |
| [CharacterSet](../../aspose.html.dom/document/characterset/) { get; } | Hämtar dokumentets kodning. |
| [Charset](../../aspose.html.dom/document/charset/) { get; } | Hämtar dokumentets kodning. |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount/) { get; } | Returnerar det aktuella antalet elementnoder som är barn till detta element. 0 om detta element inte har några underordnade noder som är av nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | En nodlista som innehåller alla underordnade till denna nod. Om det inte finns några underordnade, är detta en nodlista som inte innehåller några noder.. |
| [Children](../../aspose.html.dom/document/children/) { get; } | Returnerar de underordnade elementen. |
| [ContentType](../../aspose.html.dom/document/contenttype/) { get; } | Hämtar dokumentinnehållstypen. |
| [Context](../../aspose.html.dom/document/context/) { get; } | Hämtar aktuellt webbläsarkontext. |
| [DefaultView](../../aspose.html.dom/document/defaultview/) { get; } | StandardView IDL-attributet för Document-gränssnittet, när hämtas, måste returnera detta dokuments webbläsarkontexts WindowProxy-objekt, om detta dokument har en associerad webbläsarkontext, eller null annars. |
| [Doctype](../../aspose.html.dom/document/doctype/) { get; } | Dokumenttypsdeklarationen som är kopplad till detta dokument. |
| [DocumentElement](../../aspose.html.dom/document/documentelement/) { get; } | Detta är ett bekvämlighetsattribut som tillåter direkt åtkomst till den underordnade noden som är dokumentelementet i dokumentet. |
| [DocumentURI](../../aspose.html.dom/document/documenturi/) { get; } | Platsen för dokumentet eller null om odefinierat eller om dokumentet skapades med DOMImplementation.createDocument. |
| [Domain](../../aspose.html/htmldocument/domain/) { get; } | Domännamnet för servern som serverade dokumentet, eller `null` om servern inte kan identifieras av ett domännamn . |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Det första barnet i denna nod. Om det inte finns någon sådan nod returnerar detta null. |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild/) { get; } | Returnerar den första underordnade elementnoden för detta element. null om detta element inte har några underordnade element. |
| [Forms](../../aspose.html/htmldocument/forms/) { get; } | En samling av alla former av ett dokument. |
| [Images](../../aspose.html/htmldocument/images/) { get; } | En samling av alla`IMG` element i ett dokument. Beteendet är begränsat till`IMG` element för bakåtkompatibilitet . Som föreslagits av [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)], för att inkludera bilder kan författare använda the`OBJEKT` element eller`IMG` element. Därför rekommenderas det att inte använda detta attribut för att hitta -bilderna i dokumentet, men`getElementsByTagName` med HTML 4.01 eller`getElementsByTagNameNS` med XHTML 1.0. |
| [Implementation](../../aspose.html.dom/document/implementation/) { get; } | DOMImplementation-objektet som hanterar detta dokument. |
| [InputEncoding](../../aspose.html.dom/document/inputencoding/) { get; } | Hämtar dokumentets kodning. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Det sista underordnade av denna nod. Om det inte finns någon sådan nod returnerar detta null. |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild/) { get; } | Returnerar den sista underordnade elementnoden för detta element. null om detta element inte har några underordnade element. |
| [Links](../../aspose.html/htmldocument/links/) { get; } | En samling av alla`OMRÅDE` element och ankare ( `A` ) element i ett dokument med ett värde för `href` attribut. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Returnerar den lokala delen av det kvalificerade namnet på denna nod. För noder av någon annan typ än ELEMENT_NODE och ATTRIBUTE_NODE och noder skapade med en DOM Level 1-metod, som Document.createElement(), är detta alltid null. |
| [Location](../../aspose.html.dom/document/location/) { get; } | Dokumentets plats. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | Namnutrymmets URI för denna nod, eller null om den är ospecificerad. |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling/) { get; } | Returnerar nästa syskonelementnod för detta element. null om detta element inte har några element syskonnoder som kommer efter detta i dokumentträdet. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Noden omedelbart efter denna nod. Om det inte finns någon sådan nod returnerar detta null. |
| override [NodeName](../../aspose.html.dom/document/nodename/) { get; } | Namnet på denna nod, beroende på dess typ. |
| override [NodeType](../../aspose.html.dom/document/nodetype/) { get; } | En kod som representerar typen av det underliggande objektet. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Värdet för denna nod, beroende på dess typ. |
| [Origin](../../aspose.html.dom/document/origin/) { get; } | Hämtar dokumentets ursprung. |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument/) { get; } | Hämtar ägardokumentet. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Hämtar föräldern[`Element`](../../aspose.html.dom/element/) av denna nod. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Föräldern till denna nod. Alla noder, utom Attr, Document, DocumentFragment, Entity och Notation kan ha en förälder. Men om en nod just har skapats och ännu inte lagts till i trädet, eller om den har tagits bort från trädet, är detta null. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | Namnutrymmesprefixet för denna nod, eller null om det är ospecificerat. När den är definierad som null har inställningen ingen effekt |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling/) { get; } | Returnerar föregående syskonelementnod för detta element. null om detta element inte har några element syskonnoder som kommer före detta i dokumentträdet. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Noden omedelbart före denna nod. Om det inte finns någon sådan nod returnerar detta null. |
| [ReadyState](../../aspose.html.dom/document/readystate/) { get; } | Returnerar dokumentets beredskap. "Ladda in" medan dokumentet laddas, "interaktivt" när det är färdigt att tolka men fortfarande laddar underresurser, och "komplett" när det har laddats. |
| [Referrer](../../aspose.html/htmldocument/referrer/) { get; } | Returnerar URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt) på sidan som länkade till denna sida. Värdet är en tom sträng om användaren navigerade till sidan direkt (inte genom en länk, utan till exempel via ett bokmärke). |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking/) { get; set; } | Ett attribut som anger om felkontroll tillämpas eller inte. När den är inställd på false är implementeringen fri att inte testa alla möjliga felfall som normalt definieras på DOM-operationer, och inte generera några DOMException på DOM-operationer eller rapportera fel när du använder Document.normalizeDocument(). Vid fel är beteendet odefinierat. Det här attributet är sant som standard. |
| [StyleSheets](../../aspose.html.dom/document/stylesheets/) { get; } | En lista som innehåller alla stilmallar som är explicit länkade till eller inbäddade i ett dokument. För HTML-dokument inkluderar detta externa stilmallar, inkluderade via HTML LINK-elementet, och inline STYLE-element. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent/) { get; set; } | Detta attribut returnerar textinnehållet för denna nod och dess avkomlingar. När den är definierad som null har inställningen ingen effekt. Vid inställning tas alla möjliga barn bort som denna nod kan ha och, om den nya strängen inte är tom eller null, ersätts den av en enda textnod som innehåller strängen som detta attribut är inställt på. |
| [Title](../../aspose.html/htmldocument/title/) { get; set; } | Titeln på ett dokument som specificeras av`TITEL` element i dokumentets huvud. |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone/) { get; set; } | Ett attribut som anger, som en del av XML-deklarationen, om detta dokument är fristående. Detta är falskt när det är ospecificerat. |
| [XmlVersion](../../aspose.html.dom/document/xmlversion/) { get; set; } | Ett attribut som anger, som en del av XML-deklarationen, versionsnumret för detta dokument. Om det inte finns någon deklaration och om detta dokument stöder "XML"-funktionen är värdet "1.0". Om det här dokumentet inte stöder "XML"-funktionen är värdet alltid null. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Denna metod tillåter registrering av händelseavlyssnare på händelsemålet. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Denna metod tillåter registrering av händelseavlyssnare på händelsemålet. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Denna metod tillåter registrering av händelseavlyssnare på händelsemålet. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Lägger till noden newChild i slutet av listan över underordnade till denna nod. Om det nya barnet redan finns i trädet tas det först bort. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Returnerar en dubblett av denna nod, dvs fungerar som en generisk kopiakonstruktor för noder. Dubblettnoden har ingen förälder (parentNode är null) och inga användardata. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Returnerar en dubblett av denna nod, dvs fungerar som en generisk kopiakonstruktor för noder. Dubblettnoden har ingen förälder (parentNode är null) och inga användardata. |
| [CreateAttribute](../../aspose.html.dom/document/createattribute/)(string) | Skapar en Attr för förnamnet. |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens/)(string, string) | Skapar ett attribut för det angivna kvalificerade namnet och namnutrymmets URI. |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection/)(string) | Skapar en CDATASection-nod vars värde är den angivna strängen. |
| [CreateComment](../../aspose.html.dom/document/createcomment/)(string) | Skapar en kommentarsnod med den angivna strängen. |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment/)() | Skapar ett tomt DocumentFragment-objekt. |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype/)(string, string, string, string) | Skapar en DocumentType-nod. |
| [CreateElement](../../aspose.html.dom/document/createelement/)(string) | Skapar ett element av angiven typ. Observera att den returnerade instansen implementerar Element-gränssnittet, så attribut kan specificeras direkt på det returnerade objektet. |
| [CreateElementNS](../../aspose.html.dom/document/createelementns/)(string, string) | Skapar ett element av det angivna kvalificerade namnet och namnutrymmets URI. |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference/)(string) | Skapar ett EntityReference-objekt. Dessutom, om den refererade enheten är känd, görs den underordnade listan för EntityReference-noden densamma som den för motsvarande Entity-nod. |
| [CreateEvent](../../aspose.html.dom/document/createevent/)(string) | Skapar en[`Event`](../../aspose.html.dom.events/event/) av en typ som stöds av implementeringen. |
| [CreateExpression](../../aspose.html.dom/document/createexpression/)(string, IXPathNSResolver) | Skapar ett tolkat XPath-uttryck med lösta namnutrymmen. Detta är användbart när ett uttryck ska återanvändas i en applikation eftersom det gör det möjligt att kompilera uttryckssträngen till en mer effektiv intern form och förlösa alla namnområdesprefix som förekommer i uttrycket. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node) | Skapa en ny NodeIterator över underträdet som är rotat på den specificerade noden. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long) | Skapa en ny NodeIterator över underträdet som är rotat på den specificerade noden. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Skapa en ny NodeIterator över underträdet som är rotat på den specificerade noden. |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver/)(Node) | Anpassar valfri DOM-nod för att lösa namnområden så att ett XPath-uttryck enkelt kan utvärderas i förhållande till nodens kontext där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3-metoden`lookupNamespaceURI` på noder för att lösa namnutrymmetURI från ett givet prefix med den aktuella informationen som är tillgänglig i nodens hierarki vid den tidpunkt lookupNamespaceURI anropas, vilket också korrekt löser det implicita xml-prefixet. |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction/)(string, string) | Skapar en ProcessingInstruction-nod med det angivna namnet och datasträngarna. |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode/)(string) | Skapar en textnod med den angivna strängen. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node) | Skapa en ny TreeWalker över underträdet som är rotat vid den specificerade noden. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long) | Skapa en ny TreeWalker över underträdet som är rotat vid den specificerade noden. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | Skapa en ny TreeWalker över underträdet som är rotat vid den specificerade noden. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Denna metod tillåter sändning av händelser till implementeringshändelsemodellen. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| [Evaluate](../../aspose.html.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Utvärderar en XPath-uttryckssträng och returnerar ett resultat av den angivna typen om möjligt. |
| [GetElementById](../../aspose.html.dom/document/getelementbyid/)(string) | Returnerar elementet som har ett ID-attribut med det angivna värdet. Om inget sådant element finns returnerar detta null. Om mer än ett element har ett ID-attribut med det värdet, är det som returneras odefinierat. |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname/)(string) | Returnerar ett levande NodeList-objekt som innehåller alla element i dokumentet som har alla klasser som anges i argument. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname/)(string) | Returnerar en nodlista över alla element i dokumentordning med ett givet taggnamn och som finns i dokumentet. |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens/)(string, string) | Returnerar en nodlista över alla element med ett givet lokalt namn och namnområdes-URI i dokumentordning. |
| [GetOverrideStyle](../../aspose.html/htmldocument/getoverridestyle/)(Element, string) | Denna metod används för att hämta åsidosättningsstilsdeklarationen för ett angivet element och ett specificerat pseudoelement. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | Returnerar om denna nod (om det är ett element) har några attribut |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Returnerar om denna nod har några barn. |
| [ImportNode](../../aspose.html.dom/document/importnode/)(Node, bool) | Importerar en nod från ett annat dokument till detta dokument, utan att ändra eller ta bort källnoden från originaldokumentet; denna metod skapar en ny kopia av källnoden. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Infogar noden före det befintliga underordnade nodbarnet. Om child är null, infoga nod i slutet av listan med barn. Om child är ett DocumentFragment-objekt, infogas alla dess underordnade, i samma ordning, före child. Om barnet redan finns i trädet tas det först bort. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Den här metoden kontrollerar om det angivna namnutrymmet-URI är standardnamnutrymmet eller inte. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Testar om två noder är lika. Denna metod testar likadana noder, inte likhet (dvs om de två noderna är referenser till samma objekt) som kan testas med Node.isSameNode(). Alla noder som är lika kommer också att vara lika, även om det omvända kanske inte är sant. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Returnerar om denna nod är samma nod som den givna. Den här metoden ger ett sätt att avgöra om två nodreferenser som returneras av implementeringen refererar till samma objekt. När två nodreferenser är referenser till samma objekt, även om genom en proxy, kan referenserna användas helt utbytbart, så att alla attribut har samma värden och att anropa samma DOM-metod på någon av referenserna har alltid exakt samma effekt. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Slå upp namnutrymmes-URI som är kopplat till det givna prefixet, med början från denna nod. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Slå upp prefixet som är associerat med den givna namnutrymmes-URI, med början från denna nod. Standardnamnområdesdeklarationerna ignoreras av den här metoden. Se Namnutrymmesprefixsökning för detaljer om algoritmen som används av denna metod. |
| [Navigate](../../aspose.html.dom/document/navigate/)(RequestMessage) | Laddar dokumentet baserat på angivet förfrågningsobjekt och ersätter det tidigare innehållet. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string) | Laddar dokumentet på den angivna URL-adressen (Uniform Resource Locator) till den aktuella instansen och ersätter det tidigare innehållet. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Url) | Laddar dokumentet på den angivna URL-adressen (Uniform Resource Locator) till den aktuella instansen och ersätter det tidigare innehållet. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, string) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, Url) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, string) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, ersätter det tidigare innehållet. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, Url) | Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, ersätter det tidigare innehållet. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Lägger alla textnoder i underträdets fulla djup under denna nod, inklusive attributnoder, i en "normal" form där endast struktur (t.ex. element, kommentarer, bearbetningsinstruktioner, CDATA-sektioner och entitetsreferenser) separerar text noder, dvs det finns varken intilliggande textnoder eller tomma textnoder. Detta kan användas för att säkerställa att DOM-vyn för ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer (som XPointer [XPointer]-uppslagningar) som beror på en viss dokumentträdstruktur ska användas. Om parametern "normalize-characters" för DOMConfiguration-objektet som är kopplat till Node.ownerDocument är sant, kommer denna metod också att helt normalisera tecknen i Textnoderna. |
| [QuerySelector](../../aspose.html.dom/document/queryselector/)(string) | Returnerar det första elementet i dokumentet, som matchar selector |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall/)(string) | Returnerar en nodlista över alla element i dokumentet, som matchar selector |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Tar bort den underordnade noden som indikeras av oldChild från listan över barn och returnerar den. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) tas bort från en[`EventTarget`](../../aspose.html.dom/eventtarget/) medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) tas bort från en[`EventTarget`](../../aspose.html.dom/eventtarget/) medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) tas bort från en[`EventTarget`](../../aspose.html.dom/eventtarget/) medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort. |
| override [RenderTo](../../aspose.html/htmldocument/renderto/)(IDevice) | Denna metod används för att skriva ut innehållet i det aktuella dokumentet till den angivna enheten. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Ersätter barnnoden oldChild med newChild i listan över barn och returnerar oldChild-noden. Om newChild är ett DocumentFragment-objekt ersätts oldChild av alla DocumentFragment-underordnade, som infogas i samma ordning. Om det nya barnet redan finns i trädet tas det först bort. |
| [Save](../../aspose.html/htmldocument/save/#save)(IOutputStorage) | Sparar dokumentinnehållet och resurserna till utdatalagringen. |
| [Save](../../aspose.html/htmldocument/save/#save_10)(string) | Sparar dokumentet till lokal fil specificerad av`väg` Alla resurser som används i detta dokument kommer att sparas i till intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_5)(Url) | Sparar dokumentet till lokal fil specificerad av`url` Alla resurser som används i detta dokument kommer att sparas i till intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_1)(IOutputStorage, HTMLSaveFormat) | Sparar dokumentinnehållet och resurserna till utdatalagringen. |
| [Save](../../aspose.html/htmldocument/save/#save_2)(IOutputStorage, HTMLSaveOptions) | Sparar dokumentinnehållet och resurserna till utdatalagringen. |
| [Save](../../aspose.html/htmldocument/save/#save_3)(IOutputStorage, MarkdownSaveOptions) | Sparar dokumentinnehållet och resurserna till utdatalagringen. |
| [Save](../../aspose.html/htmldocument/save/#save_4)(IOutputStorage, MHTMLSaveOptions) | Sparar dokumentinnehållet och resurserna till utdatalagringen. |
| [Save](../../aspose.html/htmldocument/save/#save_11)(string, HTMLSaveFormat) | Sparar dokumentet till lokal fil specificerad av`väg` Alla resurser som används i detta dokument kommer att sparas i till intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_12)(string, HTMLSaveOptions) | Sparar dokumentet till lokal fil specificerad av`väg` Alla resurser som används i detta dokument kommer att sparas i till intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_13)(string, MarkdownSaveOptions) | Sparar dokumentet till lokal fil specificerad av`väg` Alla resurser som används i detta dokument kommer att sparas i till intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_14)(string, MHTMLSaveOptions) | Sparar dokumentet till lokal fil specificerad av`väg` Alla resurser som används i detta dokument kommer att sparas i till intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_6)(Url, HTMLSaveFormat) | Sparar dokumentet till lokal fil specificerad av`url` Alla resurser som används i detta dokument kommer att sparas i till intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_7)(Url, HTMLSaveOptions) | Sparar dokumentet till lokal fil specificerad av`url` Alla resurser som används i detta dokument kommer att sparas i till intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_8)(Url, MarkdownSaveOptions) | Sparar dokumentet till lokal fil specificerad av`url` Alla resurser som används i detta dokument kommer att sparas i till intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_9)(Url, MHTMLSaveOptions) | Sparar dokumentet till lokal fil specificerad av`url` Alla resurser som används i detta dokument kommer att sparas i till intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files". |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Returnerar enString som representerar denna instans. |
| [Write](../../aspose.html.dom/document/write/)(params string[]) | Skriv en textsträng till en dokumentström som öppnas av open(). Observera att funktionen kommer att producera ett document som inte nödvändigtvis drivs av en DTD och därför kan producera ett ogiltigt resultat i dokumentets sammanhang. |
| [WriteLn](../../aspose.html.dom/document/writeln/)(params string[]) | Skriv en textsträng följt av ett nyradstecken till en document -ström som öppnas av open(). Observera att funktionen kommer att producera ett dokument som inte nödvändigtvis drivs av en DTD och därför kan ge ett ogiltigt resultat i sammanhanget av document |

## evenemang

| namn | Beskrivning |
| --- | --- |
| event [OnAbort](../../aspose.html.dom/document/onabort/) | Hämtar eller ställer in händelsehanterare för OnAbort-händelse. |
| event [OnBlur](../../aspose.html.dom/document/onblur/) | Hämtar eller ställer in händelsehanterare för OnBlur-händelse. |
| event [OnCancel](../../aspose.html.dom/document/oncancel/) | Hämtar eller ställer in händelsehanterare för OnCancel-händelse. |
| event [OnCanplay](../../aspose.html.dom/document/oncanplay/) | Hämtar eller ställer in händelsehanterare för OnCanplay-händelse. |
| event [OnCanPlayThrough](../../aspose.html.dom/document/oncanplaythrough/) | Hämtar eller ställer in händelsehanterare för OnCanPlayThrough-händelse. |
| event [OnChange](../../aspose.html.dom/document/onchange/) | Hämtar eller ställer in händelsehanterare för OnChange-händelse. |
| event [OnClick](../../aspose.html.dom/document/onclick/) | Hämtar eller ställer in händelsehanterare för OnClick-händelse. |
| event [OnCueChange](../../aspose.html.dom/document/oncuechange/) | Hämtar eller ställer in händelsehanterare för OnCueChange-händelse. |
| event [OnDblClick](../../aspose.html.dom/document/ondblclick/) | Hämtar eller ställer in händelsehanterare för OnDblClick-händelse. |
| event [OnDurationChange](../../aspose.html.dom/document/ondurationchange/) | Hämtar eller ställer in händelsehanterare för OnDurationChange-händelse. |
| event [OnEmptied](../../aspose.html.dom/document/onemptied/) | Hämtar eller ställer in händelsehanterare för OnEmptied-händelse. |
| event [OnEnded](../../aspose.html.dom/document/onended/) | Hämtar eller ställer in händelsehanterare för OnEnded-händelse. |
| event [OnError](../../aspose.html.dom/document/onerror/) | Hämtar eller ställer in händelsehanterare för OnError-händelse. |
| event [OnFocus](../../aspose.html.dom/document/onfocus/) | Hämtar eller ställer in händelsehanterare för OnFocus-händelse. |
| event [OnInput](../../aspose.html.dom/document/oninput/) | Hämtar eller ställer in händelsehanterare för OnInput-händelse. |
| event [OnInvalid](../../aspose.html.dom/document/oninvalid/) | Hämtar eller ställer in händelsehanterare för OnInvalid-händelse. |
| event [OnKeyDown](../../aspose.html.dom/document/onkeydown/) | Hämtar eller ställer in händelsehanterare för OnKeyDown-händelse. |
| event [OnKeyPress](../../aspose.html.dom/document/onkeypress/) | Hämtar eller ställer in händelsehanterare för OnKeyPress-händelse. |
| event [OnKeyUp](../../aspose.html.dom/document/onkeyup/) | Hämtar eller ställer in händelsehanterare för OnKeyUp-händelse. |
| event [OnLoad](../../aspose.html.dom/document/onload/) | Hämtar eller ställer in händelsehanterare för OnLoad-händelse. |
| event [OnLoadedData](../../aspose.html.dom/document/onloadeddata/) | Hämtar eller ställer in händelsehanterare för OnLoadedData-händelse. |
| event [OnLoadedMetadata](../../aspose.html.dom/document/onloadedmetadata/) | Hämtar eller ställer in händelsehanterare för OnLoadedMetadata-händelse. |
| event [OnLoadStart](../../aspose.html.dom/document/onloadstart/) | Hämtar eller ställer in händelsehanterare för OnLoadStart-händelse. |
| event [OnMouseDown](../../aspose.html.dom/document/onmousedown/) | Hämtar eller ställer in händelsehanterare för OnMouseDown-händelse. |
| event [OnMouseEnter](../../aspose.html.dom/document/onmouseenter/) | Hämtar eller ställer in händelsehanterare för OnMouseEnter-händelse. |
| event [OnMouseLeave](../../aspose.html.dom/document/onmouseleave/) | Hämtar eller ställer in händelsehanterare för OnMouseLeave-händelse. |
| event [OnMouseMove](../../aspose.html.dom/document/onmousemove/) | Hämtar eller ställer in händelsehanterare för OnMouseMove-händelse. |
| event [OnMouseOut](../../aspose.html.dom/document/onmouseout/) | Hämtar eller ställer in händelsehanterare för OnMouseOut-händelse. |
| event [OnMouseOver](../../aspose.html.dom/document/onmouseover/) | Hämtar eller ställer in händelsehanterare för OnMouseOver-händelse. |
| event [OnMouseUp](../../aspose.html.dom/document/onmouseup/) | Hämtar eller ställer in händelsehanterare för OnMouseUp-händelse. |
| event [OnMouseWheel](../../aspose.html.dom/document/onmousewheel/) | Hämtar eller ställer in händelsehanterare för OnMouseWheel-händelse. |
| event [OnPause](../../aspose.html.dom/document/onpause/) | Hämtar eller ställer in händelsehanterare för OnPause-händelse. |
| event [OnPlay](../../aspose.html.dom/document/onplay/) | Hämtar eller ställer in händelsehanterare för OnPlay-händelse. |
| event [OnPlaying](../../aspose.html.dom/document/onplaying/) | Hämtar eller ställer in händelsehanterare för OnPlaying-händelse. |
| event [OnProgress](../../aspose.html.dom/document/onprogress/) | Hämtar eller ställer in händelsehanterare för OnProgress-händelse. |
| event [OnRateChange](../../aspose.html.dom/document/onratechange/) | Hämtar eller ställer in händelsehanterare för OnRateChange-händelse. |
| event [OnReadyStateChange](../../aspose.html.dom/document/onreadystatechange/) | Hämtar eller ställer in händelsehanterare för OnReadyStateChange-händelse. |
| event [OnReset](../../aspose.html.dom/document/onreset/) | Hämtar eller ställer in händelsehanterare för OnReset-händelse. |
| event [OnResize](../../aspose.html.dom/document/onresize/) | Hämtar eller ställer in händelsehanterare för OnResize-händelse. |
| event [OnScroll](../../aspose.html.dom/document/onscroll/) | Hämtar eller ställer in händelsehanterare för OnScroll-händelse. |
| event [OnSeeked](../../aspose.html.dom/document/onseeked/) | Hämtar eller ställer in händelsehanterare för OnSeeked-händelse. |
| event [OnSeeking](../../aspose.html.dom/document/onseeking/) | Hämtar eller ställer in händelsehanterare för OnSeeking-händelse. |
| event [OnSelect](../../aspose.html.dom/document/onselect/) | Hämtar eller ställer in händelsehanterare för OnSelect-händelse. |
| event [OnShow](../../aspose.html.dom/document/onshow/) | Hämtar eller ställer in händelsehanterare för OnShow-händelse. |
| event [OnStalled](../../aspose.html.dom/document/onstalled/) | Hämtar eller ställer in händelsehanterare för OnStalled-händelse. |
| event [OnSubmit](../../aspose.html.dom/document/onsubmit/) | Hämtar eller ställer in händelsehanterare för OnSubmit-händelse. |
| event [OnSuspend](../../aspose.html.dom/document/onsuspend/) | Hämtar eller ställer in händelsehanterare för OnSuspend-händelse. |
| event [OnTimeUpdate](../../aspose.html.dom/document/ontimeupdate/) | Hämtar eller ställer in händelsehanterare för OnTimeUpdate-händelse. |
| event [OnToggle](../../aspose.html.dom/document/ontoggle/) | Hämtar eller ställer in händelsehanterare för OnToggle-händelse. |
| event [OnVolumeChange](../../aspose.html.dom/document/onvolumechange/) | Hämtar eller ställer in händelsehanterare för OnVolumeChange-händelse. |
| event [OnWaiting](../../aspose.html.dom/document/onwaiting/) | Hämtar eller ställer in händelsehanterare för OnWaiting-händelse. |

### Se även

* class [Document](../../aspose.html.dom/document/)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss/)
* namnutrymme [Aspose.Html](../../aspose.html/)
* hopsättning [Aspose.HTML](../../)


