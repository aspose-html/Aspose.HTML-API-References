---
title: "Node Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.Node Klasse. Die Node‑Schnittstelle ist der primäre Datentyp für das gesamte Document Object Model. Sie repräsentiert einen einzelnen Knoten im Dokumentbaum. Während alle Objekte, die die Node‑Schnittstelle implementieren, Methoden zum Umgang mit Kindknoten bereitstellen, müssen nicht alle Objekte, die die Node‑Schnittstelle implementieren, Kindknoten besitzen. Beispielsweise können Text‑Knoten keine Kindknoten haben, und das Hinzufügen von Kindknoten zu solchen Knoten führt zu einer ausgelösten DOMException."
type: docs

url: /de/java/com.aspose.html.dom/node/
---
## Node class

Die Node-Schnittstelle ist der primäre Datentyp für das gesamte Document Object Model. Sie stellt einen einzelnen Knoten im Dokumentbaum dar. Während alle Objekte, die die Node-Schnittstelle implementieren, Methoden zum Umgang mit Kindknoten bereitstellen, müssen nicht alle Objekte, die die Node-Schnittstelle implementieren, Kindknoten besitzen. Zum Beispiel können [`Text`](../text/) Knoten keine Kindknoten haben, und das Hinzufügen von Kindknoten zu solchen Knoten führt dazu, dass eine [`DOMException`](../domexception/) ausgelöst wird.

Die Attribute [`nodeName`](./nodename/), [`nodeValue`](./nodevalue/) und Attribute sind als Mechanismus enthalten, um auf Knoteninformationen zuzugreifen, ohne auf das spezifische abgeleitete Interface zu casten. In Fällen, in denen es keine offensichtliche Zuordnung dieser Attribute für einen bestimmten [`nodeType`](./nodetype/) gibt (z. B. nodeValue für ein [`Element`](../element/) oder Attribute für einen [`Comment`](../comment/)), gibt dies null zurück. Beachten Sie, dass die spezialisierten Interfaces zusätzliche und bequemere Mechanismen zum Abrufen und Setzen der relevanten Informationen enthalten können.

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Die schreibgeschützte baseURI‑Eigenschaft des Node‑Interfaces gibt die absolute Basis‑URL des Dokuments zurück, das den Knoten enthält. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Die schreibgeschützte childNodes‑Eigenschaft des Node‑Interfaces gibt eine Live‑[`NodeList`](../../com.aspose.html.collections/nodelist/) von Kindknoten des angegebenen Elements zurück, wobei dem ersten Kindknoten der Index 0 zugewiesen wird. Kindknoten umfassen Elemente, Text und Kommentare. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Die schreibgeschützte firstChild-Eigenschaft der `Node`-Schnittstelle gibt das erste Kind des Knotens im Baum zurück oder null, wenn der Knoten keine Kinder hat. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Die schreibgeschützte lastChild-Eigenschaft der `Node`-Schnittstelle gibt das letzte Kind des Knotens zurück. Wenn sein übergeordnetes Element ein Element ist, ist das Kind in der Regel ein Elementknoten, ein Textknoten oder ein Kommentarknoten. Sie gibt null zurück, wenn keine Kind-Elemente vorhanden sind. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Gibt den lokalen Teil des qualifizierten Namens dieses Knotens zurück. Für Knoten jeglichen Typs, die nicht [`ELEMENT_NODE`](./element_node/) oder [`ATTRIBUTE_NODE`](./attribute_node/) sind und für Knoten, die mit einer DOM Level 1-Methode erstellt wurden, wie [`Document.createElement()`](../document/createelement/), ist dies stets null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Die schreibgeschützte Eigenschaft Element.packageURI gibt die Paket‑URI des Elements zurück, oder null, falls das Element nicht in einem Paket ist. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Die schreibgeschützte nextSibling-Eigenschaft der `Node`-Schnittstelle gibt den Knoten zurück, der dem angegebenen Knoten im [`childNodes`](./childnodes/)‑Array seines Elternteils unmittelbar folgt, oder gibt null zurück, wenn der angegebene Knoten das letzte Kind im übergeordneten Element ist. |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) Die schreibgeschützte nodeName-Eigenschaft von Node gibt den Namen des aktuellen Knotens als String zurück. |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) Ein Code, der den Typ des zugrunde liegenden Objekts darstellt. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Die nodeValue-Eigenschaft der `Node`-Schnittstelle gibt den Wert des aktuellen Knotens zurück oder setzt ihn. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Die schreibgeschützte ownerDocument‑Eigenschaft des Node‑Interfaces gibt das oberste Dokumentobjekt des Knotens zurück. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Die schreibgeschützte parentElement-Eigenschaft der `Node`-Schnittstelle gibt das übergeordnete [`Element`](../element/) des DOM-Knotens zurück oder null, wenn der Knoten keinen Elternteil hat oder sein Elternteil kein DOM-Element ist. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Die schreibgeschützte parentNode‑Eigenschaft des Node‑Interfaces gibt den Elternknoten des angegebenen Knotens im DOM‑Baum zurück. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Die schreibgeschützte Eigenschaft prefix gibt das Paket‑Präfix des angegebenen Elements zurück, oder null, falls kein Präfix angegeben ist. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Die schreibgeschützte previousSibling-Eigenschaft der `Node`-Schnittstelle gibt den Knoten zurück, der dem angegebenen Knoten im [`childNodes`](./firstchild/)‑Array seines Elternteils unmittelbar vorausgeht, oder null, wenn der angegebene Knoten das erste in dieser Liste ist. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | Die textContent-Eigenschaft der `Node`-Schnittstelle stellt den Textinhalt des Knotens und seiner Nachkommen dar. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Die addEventListener()-Methode des [`EventTarget `](../eventtarget/) Interfaces richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Die appendChild()-Methode des Node-Interface fügt einen Knoten am Ende der Kindliste eines angegebenen Elternknotens hinzu. Wenn das angegebene Kind eine Referenz zu einem bereits im Dokument vorhandenen Knoten ist, verschiebt appendChild() ihn von seiner aktuellen Position zur neuen Position (es ist nicht erforderlich, den Knoten vor dem Anhängen an einen anderen Knoten aus seinem Elternknoten zu entfernen). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | Die cloneNode()-Methode des Node-Interface gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Ihr Parameter bestimmt, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | Die cloneNode()-Methode des Node-Interface gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Ihr Parameter bestimmt, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Sendet ein Event an das angegebene [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListener in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Erfassungs‑ und optionalen Bubbling‑Phase) gelten auch für manuell mit [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) gesendete Events. |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript‑Objekt abzurufen. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Die hasChildNodes()-Methode der Node-Schnittstelle gibt einen booleschen Wert zurück, der angibt, ob der gegebene `Node` Kindknoten hat oder nicht. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Die insertBefore()-Methode des Node-Interface fügt einen Knoten vor einem Referenzknoten als Kind eines angegebenen Elternknotens ein. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Die isDefaultNamespace()-Methode des Node-Interface akzeptiert eine Namespace‑URI als Argument. Sie gibt einen booleschen Wert zurück, der true ist, wenn die Namespace‑URI das Standard‑Namespace des angegebenen Knotens ist, andernfalls false. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Die isEqualNode()-Methode der `Node`-Schnittstelle prüft, ob zwei Knoten gleich sind. Zwei Knoten sind gleich, wenn sie denselben Typ und dieselben definierenden Merkmale besitzen (für Elemente wären das ihre ID, die Anzahl der Kinder usw.), ihre Attribute übereinstimmen und so weiter. Der spezifische Satz von Datenpunkten, die übereinstimmen müssen, variiert je nach Knotentyp. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Die isSameNode()-Methode des Node-Interface ist ein veraltetes Alias für den strikten Gleichheitsoperator ===. Sie prüft, ob zwei Knoten identisch sind (mit anderen Worten, ob sie auf dasselbe Objekt verweisen). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Die lookupNamespaceURI()-Methode des Node-Interface nimmt ein Präfix als Parameter und gibt die zugehörige Namespace‑URI des angegebenen Knotens zurück, falls gefunden (andernfalls null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Die lookupPrefix()-Methode des Node-Interface gibt eine Zeichenkette zurück, die das Präfix für eine gegebene Namespace‑URI enthält, falls vorhanden, andernfalls null. Wenn mehrere Präfixe möglich sind, wird das erste Präfix zurückgegeben. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Setzt alle [`Text`](../text/) Knoten in der vollen Tiefe des Unterbaums unterhalb dieses Knotens, einschließlich Attributknoten, in eine „normale“ Form, bei der nur die Struktur (z. B. [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/) und [`entity references`](../entityreference/)) die [`Text`](../text/) Knoten trennt, d. h. es gibt weder benachbarte Textknoten noch leere Textknoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM-Ansicht eines Dokuments dieselbe ist, als wäre sie gespeichert und erneut geladen worden, und ist nützlich, wenn Operationen (wie XPointer‑[XPointer]‑Nachschlagen), die von einer bestimmten Dokumentbaumstruktur abhängen, verwendet werden sollen. Ist der Parameter "normalize-characters" des [`DOMConfiguration`](../../com.aspose.html/configuration/)‑Objekts, das an das [`Node.ownerDocument`](./ownerdocument/) angehängt ist, wahr, normalisiert diese Methode außerdem vollständig die Zeichen der Textknoten. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Die Methode `removeChild()` des Node-Interfaces entfernt einen Kindknoten aus dem DOM und gibt den entfernten Knoten zurück. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Diese Methode ermöglicht das Entfernen von Event-Listenern vom Event-Ziel. Wenn ein Listener während der Verarbeitung eines Events entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Event-Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Diese Methode ermöglicht das Entfernen von Event-Listenern vom Event-Ziel. Wenn ein Listener während der Verarbeitung eines Events entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Event-Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Diese Methode ermöglicht das Entfernen von Event-Listenern vom Event-Ziel. Wenn ein Listener während der Verarbeitung eines Events entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Event-Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Ersetzt den Kindknoten oldChild durch newChild in der Kindliste und gibt den alten oldChild‑Knoten zurück. Ist newChild ein [`DocumentFragment`](../documentfragment/)‑Objekt, wird oldChild durch alle Kinder des [`DocumentFragment`](../documentfragment/) ersetzt, die in derselben Reihenfolge eingefügt werden. Befindet sich newChild bereits im Baum, wird es zuerst entfernt. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | Ein [`Attribute`](../attr/) eines [`Element`](../element/). |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | Eine [`CDATASection`](../cdatasection/), wie &lt;!CDATA[[ … ]]&gt;. |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | Ein [`Comment`](../comment/) Knoten, wie &lt;!-- … --&gt;. |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | Ein [`DocumentFragment`](../documentfragment/) Knoten. |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | Ein [`Document`](../document/) Knoten. |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | Ein [`DocumentType`](../documenttype/) Knoten, wie &lt;!DOCTYPE html&gt;. |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | Ein [`Element`](../element/) Knoten wie &lt;p&gt; oder &lt;div&gt;. |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | Ein [`Entity`](../entity/) Knoten. |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | Ein [`EntityReference`](../entityreference/) Knoten. |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | Ein [`Notation`](../notation/) Knoten. |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | Eine [`ProcessingInstruction`](../processinginstruction/) eines XML-Dokuments, wie &lt;?xml-stylesheet … ?&gt;. |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | Der eigentliche [`Text`](../text/) innerhalb eines [`Element`](../element/) oder [`Attr`](../attr/). |

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Siehe auch

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
