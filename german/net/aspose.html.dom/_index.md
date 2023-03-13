---
title: Aspose.Html.Dom
second_title: Aspose.HTML für .NET-API-Referenz
description: Die Aspose.Html.Dom Dokumentobjektmodell Namespace bietet eine API die alle HTML XML oder SVGDokumente darstellt und mit ihnen interagiert. Das DOM ist ein Dokumentmodell das in den Browser geladen wird und das Dokument als Knotenbaum darstellt wobei jeder Knoten einen Teil des Dokuments darstellt z. B. ein Element Text Zeichenfolge oder Kommentar.
type: docs
weight: 40
url: /de/net/aspose.html.dom/
---
Die **Aspose.Html.Dom (Dokumentobjektmodell)** Namespace bietet eine API, die alle HTML-, XML- oder SVG-Dokumente darstellt und mit ihnen interagiert. Das DOM ist ein Dokumentmodell, das in den Browser geladen wird und das Dokument als Knotenbaum darstellt, wobei jeder Knoten einen Teil des Dokuments darstellt (z. B. ein Element, Text Zeichenfolge oder Kommentar).

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Attr](./attr/) | Die Attr-Schnittstelle repräsentiert ein Attribut in einem Element-Objekt. Typischerweise werden die zulässigen Werte für das Attribut in einem Schema definiert, das dem Dokument zugeordnet ist. |
| [CDATASection](./cdatasection/) | CDATA-Abschnitte werden verwendet, um Textblöcke zu maskieren, die Zeichen enthalten, die andernfalls als Markup betrachtet würden. |
| [CharacterData](./characterdata/) | Der CharacterData erweitert Node um eine Reihe von Attributen und Methoden für den Zugriff auf Zeichendaten im DOM. |
| [Comment](./comment/) | erbt von CharacterData und stellt den Inhalt eines Kommentars dar, dh alle Zeichen zwischen dem beginnenden ' . |
| [Document](./document/) | Das Dokument repräsentiert das gesamte HTML-, XML- oder SVG-Dokument. Konzeptionell ist es die Wurzel des Dokumentbaums und bietet den primären Zugriff auf die Daten des Dokuments. |
| [DocumentFragment](./documentfragment/) | DocumentFragment ist ein "leichtes" oder "minimales" Document-Objekt. Es ist sehr üblich, einen Teil des Baums eines Dokuments extrahieren oder ein neues Fragment eines Dokuments erstellen zu können. |
| [DocumentType](./documenttype/) | Der DocumentType stellt eine Schnittstelle zur Liste der Entitäten bereit, die für das Dokument definiert sind. |
| [DOMException](./domexception/) | Die DOMException-Schnittstelle stellt ein anormales Ereignis dar (das als Ausnahme bezeichnet wird), das als Ergebnis des Aufrufs einer Methode oder des Zugriffs auf eine Eigenschaft einer Web-API auftritt. So werden im Grunde Fehlerbedingungen in Web-APIs beschrieben. |
| [DOMObject](./domobject/) | Der Typ DOMObject wird verwendet, um ein Basisobjekt für das gesamte Document Object Model darzustellen. Für Java und ECMAScript ist DOMObject an den Typ Object gebunden. |
| [Element](./element/) | Die Element-Schnittstelle repräsentiert ein Element in einem HTML- oder XML-Dokument. |
| [Entity](./entity/) | Repräsentiert eine bekannte Entität, entweder geparst oder nicht geparst, in einem XML-Dokument. |
| [EntityReference](./entityreference/) | EntityReference-Knoten können verwendet werden, um eine Entitätsreferenz im Baum darzustellen. |
| [EventTarget](./eventtarget/) | Die[`EventTarget`](../aspose.html.dom/eventtarget/) -Schnittstelle wird von allen Knoten in einer Implementierung implementiert, die das DOM-Ereignismodell unterstützt. Daher kann diese Schnittstelle durch Verwendung bindungsspezifischer Casting-Methoden auf einer Instanz der Knotenschnittstelle erhalten werden. Die Schnittstelle ermöglicht die Registrierung und Entfernung von Ereignis-Listenern ein[`EventTarget`](../aspose.html.dom/eventtarget/) und Versand von Ereignissen dazu[`IEventTarget`](../aspose.html.dom.events/ieventtarget/) . |
| [Node](./node/) | Die Node-Schnittstelle ist der primäre Datentyp für das gesamte Dokumentobjektmodell. Es stellt einen einzelnen Knoten im Dokumentbaum dar. |
| [Notation](./notation/) | Repräsentiert eine in der DTD deklarierte Notation. |
| [ProcessingInstruction](./processinginstruction/) | Die ProcessingInstruction stellt eine "Verarbeitungsanweisung" dar, die in XML verwendet wird, um prozessorspezifische Informationen im Text des Dokuments beizubehalten. |
| [ShadowRoot](./shadowroot/) | ShadowRoot ist ein Wurzelknoten des Schattenbaums. |
| [Text](./text/) | Die Textschnittstelle erbt von CharacterData und repräsentiert den Textinhalt (in XML als Zeichendaten bezeichnet) eines Elements oder Attr. |
| [TypeInfo](./typeinfo/) | Die TypeInfo stellt einen Typ dar, auf den von Element- oder Attr-Knoten verwiesen wird, die in den mit dem Dokument verknüpften Schemas angegeben sind. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Ein Browsing-Kontext ist eine Umgebung, in der[`Document`](../aspose.html.dom/document/) Objekte werden dem Benutzer präsentiert. |
| [IChildNode](./ichildnode/) | definiert[`IChildNode`](../aspose.html.dom/ichildnode/) Schnittstelle, die implementiert werden soll[`Node`](../aspose.html.dom/node/) das kann einen Elternteil haben. |
| [IDocumentInit](./idocumentinit/) | Diese Schnittstelle bietet[`Document`](../aspose.html.dom/document/) Initialisierungsinfo. |
| [IDOMImplementation](./idomimplementation/) | Die DOMImplementation-Schnittstelle bietet eine Reihe von Methoden zum Ausführen von Operationen, die unabhängig von einer bestimmten Instanz des Dokumentobjektmodells sind. |
| [IElementInit](./ielementinit/) | Diese Schnittstelle bietet[`Element`](../aspose.html.dom/element/) Initialisierungsinfo. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Stellt eine Schnittstelle dar, die von allen Elementen geerbt werden muss, die von der Systemereignisbehandlung unterstützt werden |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | definiert[`IChildNode`](../aspose.html.dom/ichildnode/) das sind nicht[`DOCUMENT_TYPE_NODE`](../aspose.html.dom/node/document_type_node/) . |
| [INonElementParentNode](./inonelementparentnode/) | definiert[`IParentNode`](../aspose.html.dom/iparentnode/) die kein Elementtyp sind. |
| [IParentNode](./iparentnode/) | Definiert die[`IParentNode`](../aspose.html.dom/iparentnode/) Schnittstelle, die von allen möglichen Eltern implementiert wird. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Modi, in denen ShadowRoot arbeiten kann. |


