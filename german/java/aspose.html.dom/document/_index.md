---
title: "Document Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.Document Klasse. Das Document stellt das gesamte HTML‑, XML‑ oder SVG‑Dokument dar. Konzeptionell ist es die Wurzel des Dokumentbaums und bietet den primären Zugriff auf die Daten des Dokuments."
type: docs

url: /de/java/com.aspose.html.dom/document/
---
## Document class

Das Document repräsentiert das gesamte HTML‑, XML‑ oder SVG‑Dokument. Konzeptionell ist es die Wurzel des Dokumentbaums und bietet den primären Zugriff auf die Dokumentdaten.

```java
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) Die absolute Basis‑URI dieses Knotens oder null, wenn die Implementierung keine absolute URI ermitteln konnte. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) Ermittelt die Kodierung des Dokuments. |
| [getCharset](../../com.aspose.html.dom/document/charset/) Ermittelt die Kodierung des Dokuments. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) Gibt die aktuelle Anzahl von Elementknoten zurück, die Kinder dieses Elements sind. 0, wenn dieses Element keine Kindknoten vom Typ nodeType 1 hat. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Die schreibgeschützte childNodes‑Eigenschaft des Node‑Interfaces gibt eine Live‑[`NodeList`](../../com.aspose.html.collections/nodelist/) von Kindknoten des angegebenen Elements zurück, wobei dem ersten Kindknoten der Index 0 zugewiesen wird. Kindknoten umfassen Elemente, Text und Kommentare. |
| [getChildren](../../com.aspose.html.dom/document/children/) Gibt die Kind-Elemente zurück. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) Ermittelt den Dokument‑Inhaltstyp. |
| [getContext](../../com.aspose.html.dom/document/context/) Ermittelt den aktuellen Browsing‑Kontext. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) Das defaultView IDL‑Attribut des Document‑Interfaces muss beim Abrufen das WindowProxy‑Objekt des Browsing‑Kontexts dieses Dokuments zurückgeben, falls dieses Dokument einen zugehörigen Browsing‑Kontext hat, sonst null. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) Die Document Type Declaration, die mit diesem Dokument verknüpft ist. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) Dies ist ein Komfort‑Attribut, das direkten Zugriff auf das Kind‑Knoten‑Element des Dokuments ermöglicht. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) Der Speicherort des Dokuments oder null, falls undefiniert oder das Dokument mit DOMImplementation.createDocument erstellt wurde. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Die schreibgeschützte firstChild‑Eigenschaft des [`Node`](../node/) Interfaces gibt das erste Kind des Knotens im Baum zurück, oder null, wenn der Knoten keine Kinder hat. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) Gibt den ersten Kind‑Element‑Knoten dieses Elements zurück. null, falls dieses Element keine Kind‑Elemente hat. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) Das DOMImplementation‑Objekt, das dieses Dokument verarbeitet. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) Ermittelt die Kodierung des Dokuments. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Die schreibgeschützte lastChild‑Eigenschaft des [`Node`](../node/) Interfaces gibt das letzte Kind des Knotens zurück. Wenn dessen Elternteil ein Element ist, ist das Kind in der Regel ein Element‑Knoten, ein Text‑Knoten oder ein Kommentar‑Knoten. Sie gibt null zurück, wenn keine Kind‑Elemente vorhanden sind. |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) Gibt den letzten Kind‑Element‑Knoten dieses Elements zurück. null, falls dieses Element keine Kind‑Elemente hat. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Gibt den lokalen Teil des qualifizierten Namens dieses Knotens zurück. Für Knoten jeglichen Typs außer [`ELEMENT_NODE`](../node/element_node/) und [`ATTRIBUTE_NODE`](../node/attribute_node/) sowie für mit einer DOM Level‑1‑Methode erstellte Knoten, wie z. B. [`Document.createElement()`](./createelement/), ist dieser immer null. |
| [getLocation](../../com.aspose.html.dom/document/location/) Der Speicherort des Dokuments. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Die schreibgeschützte Eigenschaft Element.packageURI gibt die Paket‑URI des Elements zurück, oder null, falls das Element nicht in einem Paket ist. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) Gibt den nächsten Geschwister‑Element‑Knoten dieses Elements zurück. null, falls dieses Element keine nachfolgenden Element‑Geschwisterknoten im Dokumentbaum hat. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Die schreibgeschützte nextSibling‑Eigenschaft des [`Node`](../node/) Interfaces gibt den Knoten zurück, der dem angegebenen Knoten im `childNodes`‑Array des Elternteils unmittelbar folgt, oder null, wenn der angegebene Knoten das letzte Kind im Elternelement ist. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) Der Name dieses Knotens, abhängig von seinem Typ. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) Ein Code, der den Typ des zugrunde liegenden Objekts darstellt. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Die nodeValue‑Eigenschaft der [`Node `](../node/)‑Schnittstelle gibt den Wert des aktuellen Knotens zurück oder setzt ihn. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) Ermittelt die Herkunft des Dokuments. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) Ermittelt das Eigentümer‑Dokument. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Die schreibgeschützte parentElement‑Eigenschaft des [`Node`](../node/) Interfaces gibt das übergeordnete [`Element`](../element/) des DOM‑Knotens zurück, oder null, wenn der Knoten keinen Elternteil hat oder sein Elternteil kein DOM‑Element ist. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Die schreibgeschützte parentNode‑Eigenschaft des Node‑Interfaces gibt den Elternknoten des angegebenen Knotens im DOM‑Baum zurück. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Die schreibgeschützte Eigenschaft prefix gibt das Paket‑Präfix des angegebenen Elements zurück, oder null, falls kein Präfix angegeben ist. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) Gibt den vorherigen Geschwister‑Element‑Knoten dieses Elements zurück. null, falls dieses Element keine vorherigen Element‑Geschwisterknoten im Dokumentbaum hat. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Die schreibgeschützte previousSibling‑Eigenschaft des [`Node`](../node/) Interfaces gibt den Knoten zurück, der dem angegebenen Knoten im `childNodes`‑Array des Elternteils unmittelbar vorausgeht, oder null, wenn der angegebene Knoten der erste in dieser Liste ist. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) Gibt den Ladezustand des Dokuments zurück. "loading" während das Dokument lädt, "interactive" sobald das Parsen abgeschlossen ist, aber noch Unterressourcen geladen werden, und "complete" sobald es vollständig geladen ist. |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) Eine Liste, die alle Stylesheets enthält, die explizit in ein Dokument verlinkt oder eingebettet sind. Für HTML-Dokumente umfasst dies externe Stylesheets, die über das HTML‑LINK‑Element eingebunden werden, sowie Inline‑STYLE‑Elemente. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | Die textContent‑Eigenschaft der [`Node`](../node/)‑Schnittstelle stellt den Textinhalt des Knotens und seiner Nachkommen dar. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Die addEventListener()-Methode des [`EventTarget `](../eventtarget/) Interfaces richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Die appendChild()-Methode des Node-Interface fügt einen Knoten am Ende der Kindliste eines angegebenen Elternknotens hinzu. Wenn das angegebene Kind eine Referenz zu einem bereits im Dokument vorhandenen Knoten ist, verschiebt appendChild() ihn von seiner aktuellen Position zur neuen Position (es ist nicht erforderlich, den Knoten vor dem Anhängen an einen anderen Knoten aus seinem Elternknoten zu entfernen). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Die cloneNode()-Methode des Node-Interface gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Ihr Parameter bestimmt, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Die cloneNode()-Methode des Node-Interface gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Ihr Parameter bestimmt, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Die Methode Document.createAttribute() erstellt einen neuen Attributknoten und gibt ihn zurück. Das erzeugte Objekt ist ein Knoten, der die [`Attr`](../attr/)‑Schnittstelle implementiert. Das DOM erzwingt nicht, welche Art von Attributen auf diese Weise zu einem bestimmten Element hinzugefügt werden können. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Die Methode Document.createAttribute() erstellt einen neuen Attributknoten und gibt ihn zurück. Das erstellte Objekt ist ein Knoten, der das [Attr](T:com.aspose.html.dom.Attr)‑Interface implementiert. Das DOM erzwingt nicht, welche Art von Attributen auf diese Weise zu einem bestimmten Element hinzugefügt werden können. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | Erstellt einen [`CDATASection`](../cdatasection/)‑Knoten, dessen Wert die angegebene Zeichenkette ist. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | Erstellt einen [`Comment`](../comment/)‑Knoten mit der angegebenen Zeichenkette. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | Erstellt ein neues leeres [`DocumentFragment`](../documentfragment/), in das DOM‑Knoten eingefügt werden können, um einen Offscreen‑DOM‑Baum aufzubauen. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | Die Methode gibt ein [`DocumentType`](../documenttype/)‑Objekt zurück, das entweder bei der Dokumenterstellung mit DOMImplementation.createDocument verwendet werden kann oder über Methoden wie Node.insertBefore() oder Node.replaceChild() in das Dokument eingefügt werden kann. |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | In einem HTML‑Dokument erstellt die Methode document.createElement() das HTML‑Element, das durch tagName angegeben ist, oder ein [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/), falls tagName nicht erkannt wird. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | Erstellt ein Element mit dem angegebenen qualifizierten Namen und der Paket‑URI. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | Erstellt ein EntityReference‑Objekt. Zusätzlich wird, falls die referenzierte Entität bekannt ist, die Kindliste des EntityReference‑Knotens mit der der entsprechenden Entity‑Knoten identisch gemacht. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | Erstellt ein [`Event`](../../com.aspose.html.dom.events/event/) eines von der Implementierung unterstützten Typs. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | Erstellt einen geparsten XPath‑Ausdruck mit aufgelösten Paketen. Dies ist nützlich, wenn ein Ausdruck in einer Anwendung wiederverwendet werden soll, da er es ermöglicht, die Ausdruckszeichenkette in eine effizientere interne Form zu kompilieren und alle im Ausdruck vorkommenden Paket‑Präfixe vorab aufzulösen. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator)(Node) | Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten verwurzelt ist. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_1)(Node, long) | Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten verwurzelt ist. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten verwurzelt ist. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | Passt jeden DOM‑Knoten an, um Pakete aufzulösen, sodass ein XPath‑Ausdruck leicht relativ zum Kontext des Knotens, in dem er im Dokument erschien, ausgewertet werden kann. Dieser Adapter funktioniert wie die DOM‑Level‑3‑Methode `lookupNamespaceURI` auf Knoten, indem er die packageURI aus einem gegebenen Präfix mithilfe der zum Zeitpunkt des Aufrufs von lookupNamespaceURI verfügbaren Informationen in der Knotenhierarchie auflöst und dabei auch das implizite xml‑Präfix korrekt behandelt. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | Erstellt einen ProcessingInstruction‑Knoten mit dem angegebenen Namen und den Daten‑Zeichenketten. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | Erstellt einen Text‑Knoten mit der angegebenen Zeichenkette. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker)(Node) | Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten verwurzelt ist. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_1)(Node, long) | Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten verwurzelt ist. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten verwurzelt ist. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Sendet ein Event an das angegebene [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListener in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Erfassungs‑ und optionalen Bubbling‑Phase) gelten auch für manuell mit [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) gesendete Events. |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Evaluert eine XPath‑Ausdruck‑Zeichenkette und gibt, falls möglich, ein Ergebnis des angegebenen Typs zurück. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Die Document‑Methode getElementById() gibt ein [`Element`](../element/)‑Objekt zurück, das das Element darstellt, dessen id‑Eigenschaft mit der angegebenen Zeichenkette übereinstimmt. Da Element‑IDs, falls angegeben, eindeutig sein müssen, ist dies ein nützlicher Weg, um schnell auf ein bestimmtes Element zuzugreifen. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | Die Methode getElementsByClassName der `Document`‑Schnittstelle gibt ein array‑ähnliches Objekt aller Kind‑Elemente zurück, die alle angegebenen Klassennamen besitzen. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | Die Methode getElementsByTagName der `Document`‑Schnittstelle gibt eine [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) von Elementen mit dem angegebenen Tag‑Namen zurück. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | Gibt eine Liste von Elementen mit dem angegebenen Tag‑Namen zurück, die zum angegebenen Paket gehören. Das gesamte Dokument wird durchsucht, einschließlich des Wurzelknotens. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript‑Objekt abzurufen. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Die hasChildNodes()-Methode des Node‑Interfaces gibt einen booleschen Wert zurück, der angibt, ob der angegebene [`Node`](../node/) Kindknoten hat oder nicht. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | Importiert einen Knoten aus einem anderen Dokument in dieses Dokument, ohne den Quellknoten im Originaldokument zu verändern oder zu entfernen; diese Methode erstellt eine neue Kopie des Quellknotens. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Die insertBefore()-Methode des Node-Interface fügt einen Knoten vor einem Referenzknoten als Kind eines angegebenen Elternknotens ein. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Die isDefaultNamespace()-Methode des Node-Interface akzeptiert eine Namespace‑URI als Argument. Sie gibt einen booleschen Wert zurück, der true ist, wenn die Namespace‑URI das Standard‑Namespace des angegebenen Knotens ist, andernfalls false. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Die isEqualNode()-Methode des [`Node`](../node/) Interfaces prüft, ob zwei Knoten gleich sind. Zwei Knoten sind gleich, wenn sie denselben Typ, dieselben charakteristischen Merkmale (für Elemente wären das ihre ID, die Anzahl der Kinder usw.), ihre Attribute übereinstimmen usw. Der genaue Satz von Datenpunkten, die übereinstimmen müssen, variiert je nach Knotentyp. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Die isSameNode()-Methode des Node-Interface ist ein veraltetes Alias für den strikten Gleichheitsoperator ===. Sie prüft, ob zwei Knoten identisch sind (mit anderen Worten, ob sie auf dasselbe Objekt verweisen). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Die lookupNamespaceURI()-Methode des Node-Interface nimmt ein Präfix als Parameter und gibt die zugehörige Namespace‑URI des angegebenen Knotens zurück, falls gefunden (andernfalls null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Die lookupPrefix()-Methode des Node-Interface gibt eine Zeichenkette zurück, die das Präfix für eine gegebene Namespace‑URI enthält, falls vorhanden, andernfalls null. Wenn mehrere Präfixe möglich sind, wird das erste Präfix zurückgegeben. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate)(RequestMessage) | Lädt das Dokument basierend auf dem angegebenen Anforderungsobjekt und ersetzt den vorherigen Inhalt. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_4)(String) | Lädt das Dokument unter der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz und ersetzt den vorherigen Inhalt. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_1)(Url) | Lädt das Dokument unter der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz und ersetzt den vorherigen Inhalt. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_3)(Stream, String) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_2)(Stream, Url) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_6)(String, String) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_5)(String, Url) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Setzt alle [`Text`](../text/) Knoten in der vollen Tiefe des Unterbaums unterhalb dieses Knotens, einschließlich Attributknoten, in eine \"normale\" Form, bei der nur die Struktur (z. B. [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), und [`entity references`](../entityreference/)) die [`Text`](../text/) Knoten trennt, d. h. es gibt weder benachbarte Text‑Knoten noch leere Text‑Knoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM‑Ansicht eines Dokuments dieselbe ist, als wäre sie gespeichert und erneut geladen worden, und ist nützlich, wenn Operationen (wie XPointer‑[XPointer]‑Nachschlagen), die von einer bestimmten Dokumentbaumstruktur abhängen, verwendet werden sollen. Wenn der Parameter \"normalize-characters\" des [`DOMConfiguration`](../../com.aspose.html/configuration/) Objekts, das an das [`Node.ownerDocument`](../node/ownerdocument/) angehängt ist, true ist, normalisiert diese Methode außerdem vollständig die Zeichen der Text‑Knoten. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | Gibt das erste Element im Dokument zurück, das dem Selektor entspricht |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | Gibt eine NodeList aller Elemente im Dokument zurück, die dem Selektor entsprechen |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Die Methode `removeChild()` des Node-Interfaces entfernt einen Kindknoten aus dem DOM und gibt den entfernten Knoten zurück. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Diese Methode ermöglicht das Entfernen von Event-Listenern vom Event-Ziel. Wenn ein Listener während der Verarbeitung eines Events entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Event-Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Diese Methode ermöglicht das Entfernen von Event-Listenern vom Event-Ziel. Wenn ein Listener während der Verarbeitung eines Events entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Event-Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Diese Methode ermöglicht das Entfernen von Event-Listenern vom Event-Ziel. Wenn ein Listener während der Verarbeitung eines Events entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Event-Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [renderTo](../../com.aspose.html.dom/document/renderto/)(IDevice) | Diese Methode wird verwendet, um den Inhalt des aktuellen Dokuments auf ein angegebenes grafisches Gerät zu rendern. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Ersetzt den Kindknoten oldChild durch newChild in der Kindliste und gibt den alten oldChild‑Knoten zurück. Ist newChild ein [`DocumentFragment`](../documentfragment/)‑Objekt, wird oldChild durch alle Kinder des [`DocumentFragment`](../documentfragment/) ersetzt, die in derselben Reihenfolge eingefügt werden. Befindet sich newChild bereits im Baum, wird es zuerst entfernt. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Gibt einen String zurück, der diese Instanz darstellt. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | Schreibt eine Zeichenkette Text in einen Dokumenten-Stream, der mit open() geöffnet wurde. Beachten Sie, dass die Funktion ein Dokument erzeugt, das nicht unbedingt von einer DTD gesteuert wird und daher im Kontext des Dokuments ein ungültiges Ergebnis erzeugen kann. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | Schreibt eine Zeichenkette Text, gefolgt von einem Zeilenumbruchzeichen, in einen Dokumenten-Stream, der mit open() geöffnet wurde. Beachten Sie, dass die Funktion ein Dokument erzeugt, das nicht unbedingt von einer DTD gesteuert wird und daher im Kontext des Dokuments ein ungültiges Ergebnis erzeugen kann. |

## Ereignisse

| Name | Beschreibung |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | Liest oder setzt den Ereignishandler für das OnAbort-Ereignis. |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | Liest oder setzt den Ereignishandler für das OnBlur-Ereignis. |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | Liest oder setzt den Ereignishandler für das OnCancel-Ereignis. |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | Liest oder setzt den Ereignishandler für das OnCanplay-Ereignis. |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | Liest oder setzt den Ereignishandler für das OnCanPlayThrough-Ereignis. |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | Liest oder setzt den Ereignishandler für das OnChange-Ereignis. |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | Liest oder setzt den Ereignishandler für das OnClick-Ereignis. |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | Liest oder setzt den Ereignishandler für das OnCueChange-Ereignis. |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | Liest oder setzt den Ereignishandler für das OnDblClick-Ereignis. |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | Liest oder setzt den Ereignishandler für das OnDurationChange-Ereignis. |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | Liest oder setzt den Ereignishandler für das OnEmptied-Ereignis. |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | Liest oder setzt den Ereignishandler für das OnEnded-Ereignis. |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | Liest oder setzt den Ereignishandler für das OnError-Ereignis. |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | Liest oder setzt den Ereignishandler für das OnFocus-Ereignis. |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | Liest oder setzt den Ereignishandler für das OnInput-Ereignis. |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | Liest oder legt den Ereignis-Handler für das OnInvalid-Ereignis fest. |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | Liest oder legt den Ereignis-Handler für das OnKeyDown-Ereignis fest. |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | Liest oder legt den Ereignis-Handler für das OnKeyPress-Ereignis fest. |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | Liest oder legt den Ereignis-Handler für das OnKeyUp-Ereignis fest. |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | Liest oder legt den Ereignis-Handler für das OnLoad-Ereignis fest. |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | Liest oder legt den Ereignis-Handler für das OnLoadedData-Ereignis fest. |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | Liest oder legt den Ereignis-Handler für das OnLoadedMetadata-Ereignis fest. |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | Liest oder legt den Ereignis-Handler für das OnLoadStart-Ereignis fest. |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | Liest oder legt den Ereignis-Handler für das OnMouseDown-Ereignis fest. |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | Liest oder legt den Ereignis-Handler für das OnMouseEnter-Ereignis fest. |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | Liest oder legt den Ereignis-Handler für das OnMouseLeave-Ereignis fest. |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | Liest oder legt den Ereignis-Handler für das OnMouseMove-Ereignis fest. |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | Liest oder legt den Ereignis-Handler für das OnMouseOut-Ereignis fest. |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | Liest oder legt den Ereignis-Handler für das OnMouseOver-Ereignis fest. |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | Liest oder legt den Ereignis-Handler für das OnMouseUp-Ereignis fest. |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | Liest oder legt den Ereignis-Handler für das OnMouseWheel-Ereignis fest. |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | Liest oder legt den Ereignis-Handler für das OnPause-Ereignis fest. |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | Liest oder legt den Ereignis-Handler für das OnPlay-Ereignis fest. |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | Liest oder legt den Ereignis-Handler für das OnPlaying-Ereignis fest. |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | Liest oder legt den Ereignis-Handler für das OnProgress-Ereignis fest. |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | Liest oder legt den Ereignis-Handler für das OnRateChange-Ereignis fest. |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | Liest oder legt den Ereignis-Handler für das OnReadyStateChange-Ereignis fest. |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | Liest oder legt den Ereignis-Handler für das OnReset-Ereignis fest. |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | Liest oder legt den Ereignis-Handler für das OnResize-Ereignis fest. |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | Liest oder legt den Ereignis-Handler für das OnScroll-Ereignis fest. |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | Liest oder setzt den Ereignishandler für das OnSeeked-Ereignis. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | Liest oder setzt den Ereignishandler für das OnSeeking-Ereignis. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | Liest oder setzt den Ereignishandler für das OnSelect-Ereignis. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | Liest oder setzt den Ereignishandler für das OnShow-Ereignis. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | Liest oder setzt den Ereignishandler für das OnStalled-Ereignis. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | Liest oder setzt den Ereignishandler für das OnSubmit-Ereignis. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | Liest oder setzt den Ereignishandler für das OnSuspend-Ereignis. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | Liest oder setzt den Ereignishandler für das OnTimeUpdate-Ereignis. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | Liest oder setzt den Ereignishandler für das OnToggle-Ereignis. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | Liest oder setzt den Ereignishandler für das OnVolumeChange-Ereignis. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | Liest oder setzt den Ereignishandler für das OnWaiting-Ereignis. |

### Siehe auch

* class [Node](../node/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../com.aspose.html.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../com.aspose.html.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../com.aspose.html.dom.xpath/ixpathevaluator/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
