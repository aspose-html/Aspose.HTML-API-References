---
title: "Entity-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.Entity class. Stellt eine bekannte Entität dar, die entweder geparst oder ungeparst in einem XML-Dokument ist."
type: docs

url: /de/java/com.aspose.html.dom/entity/
---
## Entity class

Stellt eine bekannte Entität dar, entweder geparst oder ungeparst, in einem XML-Dokument.

```java
public class Entity : Node
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Die schreibgeschützte baseURI‑Eigenschaft des Node‑Interfaces gibt die absolute Basis‑URL des Dokuments zurück, das den Knoten enthält. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Die schreibgeschützte childNodes‑Eigenschaft des Node‑Interfaces gibt eine Live‑[`NodeList`](../../com.aspose.html.collections/nodelist/) von Kindknoten des angegebenen Elements zurück, wobei dem ersten Kindknoten der Index 0 zugewiesen wird. Kindknoten umfassen Elemente, Text und Kommentare. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Die schreibgeschützte firstChild‑Eigenschaft des [`Node`](../node/) Interfaces gibt das erste Kind des Knotens im Baum zurück, oder null, wenn der Knoten keine Kinder hat. |
| [getInputEncoding](../../com.aspose.html.dom/entity/inputencoding/) Ein Attribut, das die beim Parsen verwendete Kodierung für diese Entität angibt, wenn es sich um eine externe geparste Entität handelt. Dieser Wert ist null, wenn es sich um eine Entität aus dem internen Teilbereich handelt oder wenn sie nicht bekannt ist. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Die schreibgeschützte lastChild‑Eigenschaft des [`Node`](../node/) Interfaces gibt das letzte Kind des Knotens zurück. Wenn dessen Elternteil ein Element ist, ist das Kind in der Regel ein Element‑Knoten, ein Text‑Knoten oder ein Kommentar‑Knoten. Sie gibt null zurück, wenn keine Kind‑Elemente vorhanden sind. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Gibt den lokalen Teil des qualifizierten Namens dieses Knotens zurück. Für Knoten jeglichen Typs außer [`ELEMENT_NODE`](../node/element_node/) und [`ATTRIBUTE_NODE`](../node/attribute_node/) sowie für mit einer DOM Level‑1‑Methode erstellte Knoten, wie z. B. [`Document.createElement()`](../document/createelement/), ist dieser immer null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Die schreibgeschützte Eigenschaft Element.packageURI gibt die Paket‑URI des Elements zurück, oder null, falls das Element nicht in einem Paket ist. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Die schreibgeschützte nextSibling‑Eigenschaft des [`Node`](../node/) Interfaces gibt den Knoten zurück, der dem angegebenen Knoten im `childNodes`‑Array des Elternteils unmittelbar folgt, oder null, wenn der angegebene Knoten das letzte Kind im Elternelement ist. |
| [getNodeName](../../com.aspose.html.dom/entity/nodename/) Der Name dieses Knotens, abhängig von seinem Typ. |
| [getNodeType](../../com.aspose.html.dom/entity/nodetype/) Ein Code, der den Typ des zugrunde liegenden Objekts darstellt. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Die nodeValue‑Eigenschaft der [`Node `](../node/)‑Schnittstelle gibt den Wert des aktuellen Knotens zurück oder setzt ihn. |
| [getNotationName](../../com.aspose.html.dom/entity/notationname/) Für ungeparste Entitäten der Name der Notation für die Entität. Für geparste Entitäten ist dieser Wert null. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Die schreibgeschützte ownerDocument‑Eigenschaft des Node‑Interfaces gibt das oberste Dokumentobjekt des Knotens zurück. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Die schreibgeschützte parentElement‑Eigenschaft des [`Node`](../node/) Interfaces gibt das übergeordnete [`Element`](../element/) des DOM‑Knotens zurück, oder null, wenn der Knoten keinen Elternteil hat oder sein Elternteil kein DOM‑Element ist. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Die schreibgeschützte parentNode‑Eigenschaft des Node‑Interfaces gibt den Elternknoten des angegebenen Knotens im DOM‑Baum zurück. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Die schreibgeschützte Eigenschaft prefix gibt das Paket‑Präfix des angegebenen Elements zurück, oder null, falls kein Präfix angegeben ist. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Die schreibgeschützte previousSibling‑Eigenschaft des [`Node`](../node/) Interfaces gibt den Knoten zurück, der dem angegebenen Knoten im `childNodes`‑Array des Elternteils unmittelbar vorausgeht, oder null, wenn der angegebene Knoten der erste in dieser Liste ist. |
| [getPublicId](../../com.aspose.html.dom/entity/publicid/) Der öffentliche Bezeichner, der der Entität zugeordnet ist, falls angegeben, sonst null. |
| [getSystemId](../../com.aspose.html.dom/entity/systemid/) Der Systembezeichner, der der Entität zugeordnet ist, falls angegeben, sonst null. Dies kann ein absoluter URI sein oder nicht. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | Die textContent‑Eigenschaft der [`Node`](../node/)‑Schnittstelle stellt den Textinhalt des Knotens und seiner Nachkommen dar. |
| [getXmlEncoding](../../com.aspose.html.dom/entity/xmlencoding/) Ein Attribut, das im Rahmen der Textdeklaration die Kodierung dieser Entität angibt, wenn es sich um eine externe geparste Entität handelt. Andernfalls ist es null. |
| [getXmlVersion](../../com.aspose.html.dom/entity/xmlversion/) Ein Attribut, das im Rahmen der Textdeklaration die Versionsnummer dieser Entität angibt, wenn es sich um eine externe geparste Entität handelt. Andernfalls ist es null. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Die addEventListener()-Methode des [`EventTarget `](../eventtarget/) Interfaces richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Die appendChild()-Methode des Node-Interface fügt einen Knoten am Ende der Kindliste eines angegebenen Elternknotens hinzu. Wenn das angegebene Kind eine Referenz zu einem bereits im Dokument vorhandenen Knoten ist, verschiebt appendChild() ihn von seiner aktuellen Position zur neuen Position (es ist nicht erforderlich, den Knoten vor dem Anhängen an einen anderen Knoten aus seinem Elternknoten zu entfernen). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Die cloneNode()-Methode des Node-Interface gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Ihr Parameter bestimmt, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Die cloneNode()-Methode des Node-Interface gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Ihr Parameter bestimmt, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Sendet ein Event an das angegebene [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListener in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Erfassungs‑ und optionalen Bubbling‑Phase) gelten auch für manuell mit [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) gesendete Events. |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript‑Objekt abzurufen. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Die hasChildNodes()-Methode des Node‑Interfaces gibt einen booleschen Wert zurück, der angibt, ob der angegebene [`Node`](../node/) Kindknoten hat oder nicht. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Die insertBefore()-Methode des Node-Interface fügt einen Knoten vor einem Referenzknoten als Kind eines angegebenen Elternknotens ein. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Die isDefaultNamespace()-Methode des Node-Interface akzeptiert eine Namespace‑URI als Argument. Sie gibt einen booleschen Wert zurück, der true ist, wenn die Namespace‑URI das Standard‑Namespace des angegebenen Knotens ist, andernfalls false. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Die isEqualNode()-Methode des [`Node`](../node/) Interfaces prüft, ob zwei Knoten gleich sind. Zwei Knoten sind gleich, wenn sie denselben Typ, dieselben charakteristischen Merkmale (für Elemente wären das ihre ID, die Anzahl der Kinder usw.), ihre Attribute übereinstimmen usw. Der genaue Satz von Datenpunkten, die übereinstimmen müssen, variiert je nach Knotentyp. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Die isSameNode()-Methode des Node-Interface ist ein veraltetes Alias für den strikten Gleichheitsoperator ===. Sie prüft, ob zwei Knoten identisch sind (mit anderen Worten, ob sie auf dasselbe Objekt verweisen). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Die lookupNamespaceURI()-Methode des Node-Interface nimmt ein Präfix als Parameter und gibt die zugehörige Namespace‑URI des angegebenen Knotens zurück, falls gefunden (andernfalls null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Die lookupPrefix()-Methode des Node-Interface gibt eine Zeichenkette zurück, die das Präfix für eine gegebene Namespace‑URI enthält, falls vorhanden, andernfalls null. Wenn mehrere Präfixe möglich sind, wird das erste Präfix zurückgegeben. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Setzt alle [`Text`](../text/) Knoten in der vollen Tiefe des Unterbaums unterhalb dieses Knotens, einschließlich Attributknoten, in eine \"normale\" Form, bei der nur die Struktur (z. B. [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), und [`entity references`](../entityreference/)) die [`Text`](../text/) Knoten trennt, d. h. es gibt weder benachbarte Text‑Knoten noch leere Text‑Knoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM‑Ansicht eines Dokuments dieselbe ist, als wäre sie gespeichert und erneut geladen worden, und ist nützlich, wenn Operationen (wie XPointer‑[XPointer]‑Nachschlagen), die von einer bestimmten Dokumentbaumstruktur abhängen, verwendet werden sollen. Wenn der Parameter \"normalize-characters\" des [`DOMConfiguration`](../../com.aspose.html/configuration/) Objekts, das an das [`Node.ownerDocument`](../node/ownerdocument/) angehängt ist, true ist, normalisiert diese Methode außerdem vollständig die Zeichen der Text‑Knoten. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Die Methode `removeChild()` des Node-Interfaces entfernt einen Kindknoten aus dem DOM und gibt den entfernten Knoten zurück. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Diese Methode ermöglicht das Entfernen von Event-Listenern vom Event-Ziel. Wenn ein Listener während der Verarbeitung eines Events entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Event-Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Diese Methode ermöglicht das Entfernen von Event-Listenern vom Event-Ziel. Wenn ein Listener während der Verarbeitung eines Events entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Event-Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Diese Methode ermöglicht das Entfernen von Event-Listenern vom Event-Ziel. Wenn ein Listener während der Verarbeitung eines Events entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Event-Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Ersetzt den Kindknoten oldChild durch newChild in der Kindliste und gibt den alten oldChild‑Knoten zurück. Ist newChild ein [`DocumentFragment`](../documentfragment/)‑Objekt, wird oldChild durch alle Kinder des [`DocumentFragment`](../documentfragment/) ersetzt, die in derselben Reihenfolge eingefügt werden. Befindet sich newChild bereits im Baum, wird es zuerst entfernt. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Gibt einen String zurück, der diese Instanz darstellt. |

### Siehe auch

* class [Node](../node/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
