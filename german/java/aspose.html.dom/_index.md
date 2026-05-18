---
title: "com.aspose.html.dom"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Das Paket com.aspose.html.dom Document Object Model stellt eine API bereit, die beliebige HTML‑, XML‑ oder SVG‑Dokumente repräsentiert und mit ihnen interagiert. Das DOM ist ein im Browser geladenes Dokumentenmodell, das das Dokument als Knotbaum darstellt, wobei jeder Knoten einen Teil des Dokuments repräsentiert, z. B. ein Element, Text, eine Zeichenkette oder einen Kommentar."
type: docs

url: /de/java/com.aspose.html.dom/
---
Das **com.aspose.html.dom (Document Object Model)**-Paket stellt eine API bereit, die beliebige HTML‑, XML‑ oder SVG‑Dokumente repräsentiert und mit ihnen interagiert. Das DOM ist ein im Browser geladenes Dokumentenmodell, das das Dokument als Knotbaum darstellt, wobei jeder Knoten einen Teil des Dokuments (z. B. ein Element, einen Text‑String oder einen Kommentar) repräsentiert.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Attr](./attr/) | Die Attr‑Schnittstelle repräsentiert ein Attribut in einem Element‑Objekt. Typischerweise werden die zulässigen Werte für das Attribut in einem dem Dokument zugeordneten Schema definiert. |
| [CDATASection](./cdatasection/) | CDATA‑Abschnitte werden verwendet, um Textblöcke zu escapen, die Zeichen enthalten, die sonst als Markup betrachtet würden. |
| [CharacterData](./characterdata/) | CharacterData erweitert Node um eine Reihe von Attributen und Methoden zum Zugriff auf Zeichendaten im DOM. |
| [Comment](./comment/) | Erbt von CharacterData und repräsentiert den Inhalt eines Kommentars, d. h. alle Zeichen zwischen dem startenden ''. |
| [Document](./document/) | Das Document repräsentiert das gesamte HTML‑, XML‑ oder SVG‑Dokument. Konzeptionell ist es die Wurzel des Dokumentbaums und bietet den primären Zugriff auf die Dokumentdaten. |
| [DocumentFragment](./documentfragment/) | DocumentFragment ist ein "lightweight" oder "minimalistisches" Document‑Objekt. Es ist sehr üblich, einen Teil des Dokumentbaums extrahieren oder ein neues Fragment eines Dokuments erstellen zu wollen. |
| [DocumentType](./documenttype/) | Der DocumentType bietet eine Schnittstelle zur Liste der Entitäten, die für das Dokument definiert sind. |
| [DOMException](./domexception/) | Die DOMException‑Schnittstelle repräsentiert ein abnormalen Ereignis (eine Ausnahme), das als Ergebnis des Aufrufs einer Methode oder des Zugriffs auf eine Eigenschaft einer Web‑API auftritt. So werden Fehlersituationen im Wesentlichen in Web‑APIs beschrieben. |
| [DOMObject](./domobject/) | Der Typ DOMObject wird verwendet, um ein Basiselement für das gesamte Document Object Model zu repräsentieren. Für Java und ECMAScript ist DOMObject an den Typ Object gebunden. |
| [Element](./element/) | Die Element‑Schnittstelle repräsentiert ein Element in einem HTML‑ oder XML‑Dokument. |
| [Entity](./entity/) | Stellt eine bekannte Entität dar, entweder geparst oder ungeparst, in einem XML-Dokument. |
| [EntityReference](./entityreference/) | EntityReference‑Knoten können verwendet werden, um eine Entity‑Referenz im Baum darzustellen. |
| [EventTarget](./eventtarget/) | Das EventTarget‑Interface wird von Objekten implementiert, die Ereignisse empfangen können und möglicherweise Listener dafür haben. Mit anderen Worten implementiert jedes Ereignis‑Ziel die drei mit diesem Interface verbundenen Methoden. |
| [Node](./node/) | Das Node‑Interface ist der primäre Datentyp für das gesamte Document Object Model. Es stellt einen einzelnen Knoten im Dokumentbaum dar. Während alle Objekte, die das Node‑Interface implementieren, Methoden zum Umgang mit Kindknoten bereitstellen, dürfen nicht alle Objekte, die das Node‑Interface implementieren, Kindknoten besitzen. Zum Beispiel können [`Text`](../com.aspose.html.dom/text/)‑Knoten keine Kindknoten haben, und das Hinzufügen von Kindknoten zu solchen Knoten führt zu einer [`DOMException`](../com.aspose.html.dom/domexception/), die ausgelöst wird. |
| [Notation](./notation/) | Stellt eine im DTD deklarierte Notation dar. |
| [ProcessingInstruction](./processinginstruction/) | Die ProcessingInstruction stellt eine „Verarbeitungsanweisung“ dar, die in XML verwendet wird, um prozessor-spezifische Informationen im Text des Dokuments zu speichern. |
| [QualifiedName](./qualifiedname/) | Stellt einen qualifizierten HTML‑Namen dar. |
| [ShadowRoot](./shadowroot/) | ShadowRoot ist ein Wurzelknoten des Shadow‑Baums. |
| [Text](./text/) | Das Text‑Interface erbt von CharacterData und stellt den Textinhalt (in XML als Character Data bezeichnet) eines Elements oder Attributs dar. |
| [TypeInfo](./typeinfo/) | Die TypeInfo stellt einen Typ dar, der von Element‑ oder Attr‑Knoten referenziert wird und in den mit dem Dokument verbundenen Schemata angegeben ist. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Ein Browsing‑Kontext ist eine Umgebung, in der [`Document`](../com.aspose.html.dom/document/)‑Objekte dem Benutzer präsentiert werden. |
| [IChildNode](./ichildnode/) | Definiert das [`IChildNode`](../com.aspose.html.dom/ichildnode/)‑Interface, das von einem [`Node`](../com.aspose.html.dom/node/) implementiert werden sollte, das einen Elternteil haben kann. |
| [IDOMImplementation](./idomimplementation/) | Das DOMImplementation‑Interface bietet eine Reihe von Methoden zum Ausführen von Operationen, die von keiner bestimmten Instanz des Document Object Model abhängen. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Stellt ein Interface dar, das von allen Elementen, die die systemseitige Ereignisbehandlung unterstützen, geerbt werden muss. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | Definiert [`IChildNode`](../com.aspose.html.dom/ichildnode/), die nicht [`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/) sind. |
| [INonElementParentNode](./inonelementparentnode/) | Definiert [`IParentNode`](../com.aspose.html.dom/iparentnode/), die kein Elementtyp sind. |
| [IParentNode](./iparentnode/) | Definiert das [`IParentNode`](../com.aspose.html.dom/iparentnode/)‑Interface, das von allen möglichen Eltern implementiert wird. |
| [IStorage](./istorage/) | Dieses Interface der Web‑Storage‑API bietet Zugriff auf den Sitzungs‑ oder lokalen Speicher einer bestimmten Domain. Siehe die Web‑Storage‑Spezifikation: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Modi, in denen ShadowRoot operieren kann. |
