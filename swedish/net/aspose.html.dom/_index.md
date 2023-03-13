---
title: Aspose.Html.Dom
second_title: Aspose.HTML för .NET API Referens
description: Den Aspose.Html.Dom dokumentobjektmodell namespace tillhandahåller API som representerar och interagerar med alla HTML XML eller SVGdokument. DOM är en dokumentmodell som laddas i webbläsaren och representerar dokumentet som ett nodträd där varje node representerar en del av dokumentet t.ex. ett element text sträng eller kommentar.
type: docs
weight: 40
url: /sv/net/aspose.html.dom/
---
Den **Aspose.Html.Dom (dokumentobjektmodell)** namespace tillhandahåller API som representerar och interagerar med alla HTML-, XML- eller SVG-dokument. DOM är en dokumentmodell som laddas i webbläsaren och representerar dokumentet som ett nodträd, där varje node representerar en del av dokumentet (t.ex. ett element, text) sträng eller kommentar).

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Attr](./attr/) | Attr-gränssnittet representerar ett attribut i ett Element-objekt. Vanligtvis definieras de tillåtna värdena för attributet i ett schema som är kopplat till dokumentet. |
| [CDATASection](./cdatasection/) | CDATA-sektioner används för att undvika textblock som innehåller tecken som annars skulle betraktas som uppmärkning. |
| [CharacterData](./characterdata/) | CharacterData utökar noden med en uppsättning attribut och metoder för att komma åt teckendata i DOM. |
| [Comment](./comment/) | Ärver från CharacterData och representerar innehållet i en kommentar, dvs alla tecken mellan början ' . |
| [Document](./document/) | Dokumentet representerar hela HTML-, XML- eller SVG-dokumentet. Begreppsmässigt är det roten till dokumentträdet och ger den primära åtkomsten till dokumentets data. |
| [DocumentFragment](./documentfragment/) | DocumentFragment är ett "lätt" eller "minimalt" dokumentobjekt. Det är mycket vanligt att man vill kunna extrahera en del av ett dokuments träd eller skapa ett nytt fragment av ett dokument. |
| [DocumentType](./documenttype/) | DocumentType tillhandahåller ett gränssnitt till listan över enheter som är definierade för document |
| [DOMException](./domexception/) | DOMException-gränssnittet representerar en onormal händelse (kallad ett undantag) som inträffar som ett resultat av anrop av en metod eller åtkomst till en egenskap hos ett webb-API. Det är i princip hur feltillstånd beskrivs i webb-API:er. |
| [DOMObject](./domobject/) | DOMObject-typen används för att representera ett basobjekt för hela dokumentobjektmodellen. För Java och ECMAScript är DOMObject bundet till objekttypen. |
| [Element](./element/) | Element-gränssnittet representerar ett element i ett HTML- eller XML-dokument. |
| [Entity](./entity/) | Representerar en känd enhet, antingen tolkad eller oparsad, i ett XML-dokument. |
| [EntityReference](./entityreference/) | EntityReference-noder kan användas för att representera en entitetsreferens i trädet. |
| [EventTarget](./eventtarget/) | Den[`EventTarget`](../aspose.html.dom/eventtarget/) gränssnitt implementeras av alla noder i en implementering som stöder DOM-händelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika castingmetoder på en instans av nodgränssnittet. Gränssnittet tillåter registrering och borttagning av händelseavlyssnare på en[`EventTarget`](../aspose.html.dom/eventtarget/) och sändning av händelser till det[`IEventTarget`](../aspose.html.dom.events/ieventtarget/) . |
| [Node](./node/) | Nodgränssnittet är den primära datatypen för hela dokumentobjektmodellen. Den representerar en enda nod i dokumentträdet. |
| [Notation](./notation/) | Representerar en notation som deklareras i DTD. |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction representerar en "bearbetningsinstruktion", som används i XML som ett sätt att behålla processorspecifik information i dokumentets text. |
| [ShadowRoot](./shadowroot/) | ShadowRoot är en rotnod till skuggträdet. |
| [Text](./text/) | Text-gränssnittet ärver från CharacterData och representerar textinnehållet (kallas teckendata i XML) för ett element eller Attr. |
| [TypeInfo](./typeinfo/) | TypeInfo representerar en typ som refereras från Element- eller Attr-noder, specificerad i scheman som är associerade med dokumentet. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | En webbläsarkontext är en miljö där[`Document`](../aspose.html.dom/document/) objekt presenteras för användaren. |
| [IChildNode](./ichildnode/) | Definierar[`IChildNode`](../aspose.html.dom/ichildnode/) gränssnitt som bör implementeras av[`Node`](../aspose.html.dom/node/) som kan ha en förälder. |
| [IDocumentInit](./idocumentinit/) | Detta gränssnitt tillhandahåller[`Document`](../aspose.html.dom/document/) initialiseringsinformation. |
| [IDOMImplementation](./idomimplementation/) | DOMImplementation-gränssnittet tillhandahåller ett antal metoder för att utföra operationer som är oberoende av en viss instans av dokumentobjektmodellen. |
| [IElementInit](./ielementinit/) | Detta gränssnitt tillhandahåller[`Element`](../aspose.html.dom/element/) initialiseringsinformation. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Representerar gränssnitt som måste ärvas av alla element som stöds systemhändelsehantering |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | Definierar[`IChildNode`](../aspose.html.dom/ichildnode/) som inte är det[`DOCUMENT_TYPE_NODE`](../aspose.html.dom/node/document_type_node/) . |
| [INonElementParentNode](./inonelementparentnode/) | Definierar[`IParentNode`](../aspose.html.dom/iparentnode/) som inte är elementtyp. |
| [IParentNode](./iparentnode/) | Definierar[`IParentNode`](../aspose.html.dom/iparentnode/) gränssnitt som implementeras av eventuella föräldrar. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Lägen där ShadowRoot kan fungera. |


