---
title: "com.aspose.html.dom"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Het com.aspose.html.dom Document Object Model-pakket biedt een API die elk HTML-, XML- of SVG-document weergeeft en ermee interacteert. De DOM is een documentmodel dat in de browser wordt geladen en het document weergeeft als een knooppuntboom waarbij elk knooppunt een deel van het document vertegenwoordigt, bijv. een element, tekst, tekenreeks of commentaar."
type: docs

url: /nl/java/com.aspose.html.dom/
---
Het **com.aspose.html.dom (Document Object Model)**-pakket biedt een API die elk HTML-, XML- of SVG‑document weergeeft en ermee interageert. De DOM is een documentmodel dat in de browser wordt geladen en het document weergeeft als een knooppuntboom, waarbij elk knooppunt een deel van het document vertegenwoordigt (bijv. een element, tekst‑string of commentaar).

## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [Attr](./attr/) | De Attr-interface vertegenwoordigt een attribuut in een Element-object. Typisch worden de toegestane waarden voor het attribuut gedefinieerd in een schema dat aan het document is gekoppeld. |
| [CDATASection](./cdatasection/) | CDATA-secties worden gebruikt om tekstblokken te escapen die tekens bevatten die anders als markup zouden worden beschouwd. |
| [CharacterData](./characterdata/) | De CharacterData breidt Node uit met een reeks attributen en methoden voor het benaderen van tekengegevens in de DOM. |
| [Comment](./comment/) | Erft van CharacterData en vertegenwoordigt de inhoud van een commentaar, d.w.z. alle tekens tussen de startende ''. |
| [Document](./document/) | Het Document vertegenwoordigt het volledige HTML-, XML- of SVG-document. Conceptueel is het de wortel van de documentboom en biedt het primaire toegang tot de gegevens van het document. |
| [DocumentFragment](./documentfragment/) | DocumentFragment is een "lichte" of "minimale" Document-object. Het is heel gebruikelijk om een deel van de documentboom te willen extraheren of een nieuw fragment van een document te maken. |
| [DocumentType](./documenttype/) | De DocumentType biedt een interface naar de lijst van entiteiten die voor het document zijn gedefinieerd. |
| [DOMException](./domexception/) | De DOMException-interface vertegenwoordigt een abnormale gebeurtenis (een uitzondering genoemd) die optreedt als gevolg van het aanroepen van een methode of het benaderen van een eigenschap van een web-API. Dit is in feite hoe foutcondities worden beschreven in web-API's. |
| [DOMObject](./domobject/) | Het DOMObject-type wordt gebruikt om een basisobject voor het volledige Document Object Model te vertegenwoordigen. Voor Java en ECMAScript is DOMObject gekoppeld aan het Object-type. |
| [Element](./element/) | De Element-interface vertegenwoordigt een element in een HTML- of XML-document. |
| [Entity](./entity/) | Stelt een bekende entiteit voor, ofwel geparseerd of niet-geparseerd, in een XML-document. |
| [EntityReference](./entityreference/) | EntityReference nodes kunnen worden gebruikt om een entiteitsreferentie in de boom weer te geven. |
| [EventTarget](./eventtarget/) | De EventTarget‑interface wordt geïmplementeerd door objecten die gebeurtenissen kunnen ontvangen en er mogelijk luisteraars voor hebben. Met andere woorden, elk doelwit van gebeurtenissen implementeert de drie methoden die bij deze interface horen. |
| [Node](./node/) | De Node‑interface is het primaire datatype voor het volledige Document Object Model. Het vertegenwoordigt een enkel knooppunt in de documentboom. Terwijl alle objecten die de Node‑interface implementeren methoden blootstellen voor het omgaan met kinderen, mogen niet alle objecten die de Node‑interface implementeren kinderen hebben. Bijvoorbeeld, [`Text`](../com.aspose.html.dom/text/) knooppunten mogen geen kinderen hebben, en het toevoegen van kinderen aan dergelijke knooppunten leidt tot een [`DOMException`](../com.aspose.html.dom/domexception/) die wordt opgegooid. |
| [Notation](./notation/) | Stelt een notatie voor die in de DTD is gedeclareerd. |
| [ProcessingInstruction](./processinginstruction/) | De ProcessingInstruction vertegenwoordigt een "verwerkingsinstructie", die in XML wordt gebruikt om processor‑specifieke informatie in de tekst van het document te behouden. |
| [QualifiedName](./qualifiedname/) | Stelt een HTML‑gekwalificeerde naam voor. |
| [ShadowRoot](./shadowroot/) | ShadowRoot is een wortelknooppunt van de shadow‑boom. |
| [Text](./text/) | De Text‑interface erft van CharacterData en vertegenwoordigt de tekstuele inhoud (in XML aangeduid als character data) van een Element of Attr. |
| [TypeInfo](./typeinfo/) | De TypeInfo vertegenwoordigt een type dat wordt gerefereerd vanuit Element‑ of Attr‑knooppunten, gespecificeerd in de schema's die bij het document horen. |
## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Een browse‑context is een omgeving waarin [`Document`](../com.aspose.html.dom/document/) objecten aan de gebruiker worden gepresenteerd. |
| [IChildNode](./ichildnode/) | Definieert de [`IChildNode`](../com.aspose.html.dom/ichildnode/) interface die geïmplementeerd moet worden door [`Node`](../com.aspose.html.dom/node/) die een ouder kan hebben. |
| [IDOMImplementation](./idomimplementation/) | De DOMImplementation‑interface biedt een aantal methoden voor het uitvoeren van bewerkingen die onafhankelijk zijn van een specifieke instantie van het documentobjectmodel. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Stelt een interface voor die moet worden geërfd door elk element dat systeem‑gebeurtenisafhandeling ondersteunt. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | Definieert [`IChildNode`](../com.aspose.html.dom/ichildnode/) die geen [`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/) zijn. |
| [INonElementParentNode](./inonelementparentnode/) | Definieert [`IParentNode`](../com.aspose.html.dom/iparentnode/) die geen Element‑type zijn. |
| [IParentNode](./iparentnode/) | Definieert de [`IParentNode`](../com.aspose.html.dom/iparentnode/) interface die door alle mogelijke ouders wordt geïmplementeerd. |
| [IStorage](./istorage/) | Deze interface van de Web Storage‑API biedt toegang tot de sessie‑ of lokale opslag van een bepaald domein. Zie de Web Storage‑specificatie: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## Enumeratie

| Enumeratie | Beschrijving |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Modi waarin ShadowRoot kan opereren. |
