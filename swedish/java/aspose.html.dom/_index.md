---
title: "com.aspose.html.dom"
second_title: "Aspose.HTML för Java API-referens"
description: "Paketet com.aspose.html.dom Document Object Model tillhandahåller ett API som representerar och interagerar med alla HTML-, XML- eller SVG-dokument. DOM är en dokumentmodell som laddas i webbläsaren och representerar dokumentet som ett nodträd där varje nod motsvarar en del av dokumentet, t.ex. ett element, text, sträng eller kommentar."
type: docs

url: /sv/java/com.aspose.html.dom/
---
Paketet **com.aspose.html.dom (Document Object Model)** tillhandahåller ett API som representerar och interagerar med alla HTML-, XML- eller SVG-dokument. DOM är en dokumentmodell som laddas i webbläsaren och representerar dokumentet som ett nodträd, där varje nod motsvarar en del av dokumentet (t.ex. ett element, en textsträng eller en kommentar).

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Attr](./attr/) | Attr-gränssnittet representerar ett attribut i ett Element-objekt. Vanligtvis definieras de tillåtna värdena för attributet i ett schema som är kopplat till dokumentet. |
| [CDATASection](./cdatasection/) | CDATA-sektioner används för att undkomma textblock som innehåller tecken som annars skulle betraktas som markup. |
| [CharacterData](./characterdata/) | CharacterData utökar Node med en uppsättning attribut och metoder för åtkomst till teckendata i DOM. |
| [Comment](./comment/) | Arver från CharacterData och representerar innehållet i en kommentar, d.v.s. alla tecken mellan start- och slutcitattecknen ''. |
| [Document](./document/) | Document representerar hela HTML-, XML- eller SVG-dokumentet. Konceptuellt är det roten i dokumentträdet och ger primär åtkomst till dokumentets data. |
| [DocumentFragment](./documentfragment/) | DocumentFragment är ett "lättvikt" eller "minimal" dokumentobjekt. Det är mycket vanligt att vilja kunna extrahera en del av ett dokuments träd eller skapa ett nytt fragment av ett dokument. |
| [DocumentType](./documenttype/) | DocumentType tillhandahåller ett gränssnitt till listan över enheter som är definierade för dokumentet. |
| [DOMException](./domexception/) | DOMException-gränssnittet representerar en onormal händelse (kallad ett undantag) som uppstår som resultat av att anropa en metod eller komma åt en egenskap i ett webb‑API. Detta är i princip hur felvillkor beskrivs i webb‑API:er. |
| [DOMObject](./domobject/) | DOMObject-typen används för att representera ett basobjekt för hela Document Object Model. För Java och ECMAScript är DOMObject bunden till Object-typen. |
| [Element](./element/) | Element-gränssnittet representerar ett element i ett HTML- eller XML-dokument. |
| [Entity](./entity/) | Representerar en känd entitet, antingen parsad eller oparsad, i ett XML-dokument. |
| [EntityReference](./entityreference/) | EntityReference‑noder kan användas för att representera en entitetsreferens i trädet. |
| [EventTarget](./eventtarget/) | EventTarget‑gränssnittet implementeras av objekt som kan ta emot händelser och kan ha lyssnare för dem. Med andra ord implementerar alla händelse‑mål de tre metoderna som är associerade med detta gränssnitt. |
| [Node](./node/) | Node‑gränssnittet är den primära datatypen för hela Document Object Model. Det representerar en enskild nod i dokumentträdet. Även om alla objekt som implementerar Node‑gränssnittet exponerar metoder för att hantera barn, kan inte alla objekt som implementerar Node‑gränssnittet ha barn. Till exempel kan [`Text`](../com.aspose.html.dom/text/)‑noder sakna barn, och att lägga till barn i sådana noder resulterar i att en [`DOMException`](../com.aspose.html.dom/domexception/) kastas. |
| [Notation](./notation/) | Representerar en notation som deklarerats i DTD:n. |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction representerar en "processinstruktion", som används i XML för att behålla processor‑specifik information i dokumentets text. |
| [QualifiedName](./qualifiedname/) | Representerar ett HTML‑kvalificerat namn. |
| [ShadowRoot](./shadowroot/) | ShadowRoot är en rot‑nod i ett skuggträd. |
| [Text](./text/) | Text‑gränssnittet ärver från CharacterData och representerar det textuella innehållet (benämnt teckendata i XML) för ett Element eller Attr. |
| [TypeInfo](./typeinfo/) | TypeInfo representerar en typ som refereras från Element‑ eller Attr‑noder, specificerad i de scheman som är associerade med dokumentet. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | En webbläsarkontext är en miljö där [`Document`](../com.aspose.html.dom/document/)‑objekt presenteras för användaren. |
| [IChildNode](./ichildnode/) | Definierar [`IChildNode`](../com.aspose.html.dom/ichildnode/)‑gränssnittet som bör implementeras av [`Node`](../com.aspose.html.dom/node/) som kan ha en förälder. |
| [IDOMImplementation](./idomimplementation/) | DOMImplementation‑gränssnittet tillhandahåller ett antal metoder för att utföra operationer som är oberoende av någon specifik instans av dokumentobjektmodellen. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Representerar ett gränssnitt som måste ärvas av alla element som stöder systemhändelsehantering. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | Definierar [`IChildNode`](../com.aspose.html.dom/ichildnode/) som inte är [`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/). |
| [INonElementParentNode](./inonelementparentnode/) | Definierar [`IParentNode`](../com.aspose.html.dom/iparentnode/) som inte är av Element‑typ. |
| [IParentNode](./iparentnode/) | Definierar [`IParentNode`](../com.aspose.html.dom/iparentnode/)‑gränssnittet som implementeras av alla möjliga föräldrar. |
| [IStorage](./istorage/) | Detta gränssnitt i Web Storage‑API:et ger åtkomst till en specifik domäns session‑ eller lokala lagring. Se Web Storage‑specifikationen: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Lägen där ShadowRoot kan fungera. |
