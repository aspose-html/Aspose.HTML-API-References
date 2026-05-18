---
title: "Element‑Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.Element‑Klasse. Das Element‑Interface repräsentiert ein Element in einem HTML‑ oder XML‑Dokument"
type: docs

url: /de/java/com.aspose.html.dom/element/
---
## Element class

Die Element‑Schnittstelle repräsentiert ein Element in einem HTML‑ oder XML‑Dokument.

```java
public class Element : Node, IChildNode, IParentNode
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Element](element/)(QualifiedName, Document) | Initialisiert eine neue Instanz der `Element`‑Klasse. Rufen Sie diesen Konstruktor nicht direkt auf, verwenden Sie [`CreateElement`](../document/createelement/) oder [`CreateElementNS`](../document/createelementns/). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) Eine NamedNodeMap, die die Attribute dieses Knotens enthält (wenn es ein Element ist) oder sonst null. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Die schreibgeschützte baseURI‑Eigenschaft des Node‑Interfaces gibt die absolute Basis‑URL des Dokuments zurück, das den Knoten enthält. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) Gibt die aktuelle Anzahl von Elementknoten zurück, die Kinder dieses Elements sind. 0, wenn dieses Element keine Kindknoten vom Typ nodeType 1 hat. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Die schreibgeschützte childNodes‑Eigenschaft des Node‑Interfaces gibt eine Live‑[`NodeList`](../../com.aspose.html.collections/nodelist/) von Kindknoten des angegebenen Elements zurück, wobei dem ersten Kindknoten der Index 0 zugewiesen wird. Kindknoten umfassen Elemente, Text und Kommentare. |
| [getChildren](../../com.aspose.html.dom/element/children/) Gibt die Kind-Elemente des aktuellen Elements zurück. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) Gibt eine Live‑DOMTokenList zurück, die Tokens enthält, die beim Parsen des Attributs \"class\" erhalten wurden. |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Die schreibgeschützte firstChild‑Eigenschaft des [`Node`](../node/) Interfaces gibt das erste Kind des Knotens im Baum zurück, oder null, wenn der Knoten keine Kinder hat. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Gibt den ersten Kind-Elementknoten dieses Elements zurück. null, wenn dieses Element keine Kind-Elemente hat. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Die schreibgeschützte lastChild‑Eigenschaft des [`Node`](../node/) Interfaces gibt das letzte Kind des Knotens zurück. Wenn dessen Elternteil ein Element ist, ist das Kind in der Regel ein Element‑Knoten, ein Text‑Knoten oder ein Kommentar‑Knoten. Sie gibt null zurück, wenn keine Kind‑Elemente vorhanden sind. |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Gibt das letzte Kind‑Element‑Knoten dieses Elements zurück. null, wenn dieses Element keine Kindelemente hat. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Gibt den lokalen Teil des qualifizierten Namens dieses Knotens zurück. Für Knoten eines anderen Typs als ELEMENT_NODE und ATTRIBUTE_NODE sowie für Knoten, die mit einer DOM Level‑1‑Methode wie Document.createElement() erstellt wurden, ist dies immer null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) Der Namespace‑URI dieses Knotens, oder null, wenn er nicht angegeben ist. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Gibt den nächsten Geschwister‑Element‑Knoten dieses Elements zurück. null, wenn dieses Element keine nachfolgenden Element‑Geschwisterknoten im Dokumentbaum hat. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Die schreibgeschützte nextSibling‑Eigenschaft des [`Node`](../node/) Interfaces gibt den Knoten zurück, der dem angegebenen Knoten im `childNodes`‑Array des Elternteils unmittelbar folgt, oder null, wenn der angegebene Knoten das letzte Kind im Elternelement ist. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) Der Name dieses Knotens, abhängig von seinem Typ. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) Ein Code, der den Typ des zugrunde liegenden Objekts darstellt. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Die nodeValue‑Eigenschaft der [`Node `](../node/)‑Schnittstelle gibt den Wert des aktuellen Knotens zurück oder setzt ihn. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Die schreibgeschützte ownerDocument‑Eigenschaft des Node‑Interfaces gibt das oberste Dokumentobjekt des Knotens zurück. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Die schreibgeschützte parentElement‑Eigenschaft des [`Node`](../node/)‑Interfaces gibt das übergeordnete `Element` des DOM‑Knotens zurück, oder null, wenn der Knoten keinen Elternteil hat oder sein Elternteil kein DOM‑Element ist. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Die schreibgeschützte parentNode‑Eigenschaft des Node‑Interfaces gibt den Elternknoten des angegebenen Knotens im DOM‑Baum zurück. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) Das Namespace‑Präfix dieses Knotens, oder null, wenn es nicht angegeben ist. Wenn es auf null gesetzt ist, hat das Setzen keine Wirkung. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Gibt den vorherigen Geschwister‑Element‑Knoten dieses Elements zurück. null, wenn dieses Element keine vorherigen Element‑Geschwisterknoten im Dokumentbaum hat. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Die schreibgeschützte previousSibling‑Eigenschaft des [`Node`](../node/) Interfaces gibt den Knoten zurück, der dem angegebenen Knoten im `childNodes`‑Array des Elternteils unmittelbar vorausgeht, oder null, wenn der angegebene Knoten der erste in dieser Liste ist. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Gibt das auf diesem Element gespeicherte shadowRoot zurück oder null, wenn es geschlossen ist. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) Der Name des Elements. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if the new String is not empty or null, replaced by a single Text node containing the String this attribute is set to. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Die addEventListener()-Methode des [`EventTarget `](../eventtarget/) Interfaces richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Die appendChild()-Methode des Node-Interface fügt einen Knoten am Ende der Kindliste eines angegebenen Elternknotens hinzu. Wenn das angegebene Kind eine Referenz zu einem bereits im Dokument vorhandenen Knoten ist, verschiebt appendChild() ihn von seiner aktuellen Position zur neuen Position (es ist nicht erforderlich, den Knoten vor dem Anhängen an einen anderen Knoten aus seinem Elternknoten zu entfernen). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Erstellt einen Shadow-Root und fügt ihn dem aktuellen Element hinzu. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Die cloneNode()-Methode des Node-Interface gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Ihr Parameter bestimmt, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Die cloneNode()-Methode des Node-Interface gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Ihr Parameter bestimmt, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Sendet ein Event an das angegebene [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListener in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Erfassungs‑ und optionalen Bubbling‑Phase) gelten auch für manuell mit [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) gesendete Events. |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Ruft einen Attributwert anhand des Namens ab. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Gibt die Attributnamen des Elements als Array von Zeichenketten zurück. Hat das Element keine Attribute, wird ein leeres Array zurückgegeben. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Ruft einen Attributknoten anhand des Namens ab. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Ruft einen Attr‑Knoten anhand des lokalen Namens und der Namespace‑URI ab. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Ruft einen Attributwert anhand des lokalen Namens und der Namespace‑URI ab. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Gibt ein [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/)‑Objekt zurück, das alle Elemente innerhalb von `element` enthält, die alle im Argument angegebenen Klassen besitzen. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Gibt ein [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/)‑Objekt zurück, das alle `elements` mit einem angegebenen Tag‑Namen in Dokumentreihenfolge enthält. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Gibt ein [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/)‑Objekt zurück, das alle `elements` mit einem angegebenen lokalen Namen und Paket‑URI‑String in Dokumentreihenfolge enthält. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript‑Objekt abzurufen. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | Gibt true zurück, wenn ein Attribut mit dem angegebenen Namen an diesem Element festgelegt ist oder einen Standardwert hat, andernfalls false. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | Gibt true zurück, wenn ein Attribut mit dem angegebenen lokalen Namen und der Namespace‑URI an diesem Element festgelegt ist oder einen Standardwert hat, andernfalls false. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | Gibt zurück, ob dieser Knoten (falls er ein Element ist) Attribute besitzt. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Die hasChildNodes()-Methode des Node‑Interfaces gibt einen booleschen Wert zurück, der angibt, ob der angegebene [`Node`](../node/) Kindknoten hat oder nicht. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Die insertBefore()-Methode des Node-Interface fügt einen Knoten vor einem Referenzknoten als Kind eines angegebenen Elternknotens ein. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Die isDefaultNamespace()-Methode des Node-Interface akzeptiert eine Namespace‑URI als Argument. Sie gibt einen booleschen Wert zurück, der true ist, wenn die Namespace‑URI das Standard‑Namespace des angegebenen Knotens ist, andernfalls false. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Die isEqualNode()-Methode des [`Node`](../node/) Interfaces prüft, ob zwei Knoten gleich sind. Zwei Knoten sind gleich, wenn sie denselben Typ, dieselben charakteristischen Merkmale (für Elemente wären das ihre ID, die Anzahl der Kinder usw.), ihre Attribute übereinstimmen usw. Der genaue Satz von Datenpunkten, die übereinstimmen müssen, variiert je nach Knotentyp. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Die isSameNode()-Methode des Node-Interface ist ein veraltetes Alias für den strikten Gleichheitsoperator ===. Sie prüft, ob zwei Knoten identisch sind (mit anderen Worten, ob sie auf dasselbe Objekt verweisen). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Die lookupNamespaceURI()-Methode des Node-Interface nimmt ein Präfix als Parameter und gibt die zugehörige Namespace‑URI des angegebenen Knotens zurück, falls gefunden (andernfalls null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Die lookupPrefix()-Methode des Node-Interface gibt eine Zeichenkette zurück, die das Präfix für eine gegebene Namespace‑URI enthält, falls vorhanden, andernfalls null. Wenn mehrere Präfixe möglich sind, wird das erste Präfix zurückgegeben. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Setzt alle [`Text`](../text/)‑Knoten in der vollen Tiefe des Unterbaums unterhalb dieses Knotens, einschließlich Attribut‑Knoten, in eine \"normale\" Form, bei der nur die Struktur (z. B. `elements`, [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), und [`entity references`](../entityreference/)) die [`Text`](../text/)‑Knoten trennt, d. h. es gibt weder benachbarte Text‑Knoten noch leere Text‑Knoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM‑Ansicht eines Dokuments derselbe ist, als wäre es gespeichert und erneut geladen worden, und ist nützlich, wenn Operationen (wie XPointer‑[XPointer]‑Lookups), die von einer bestimmten Dokumentbaumstruktur abhängen, verwendet werden sollen. Wenn der Parameter \"normalize-characters\" des [`DOMConfiguration`](../../com.aspose.html/configuration/)‑Objekts, das an das [`Node.ownerDocument`](../node/ownerdocument/) angehängt ist, true ist, normalisiert diese Methode außerdem vollständig die Zeichen der Text‑Knoten. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | Gibt das erste Element im Dokument zurück, das dem Selektor entspricht |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | Gibt eine NodeList aller Elemente im Dokument zurück, die dem Selektor entsprechen |
| [remove](../../com.aspose.html.dom/element/remove/)() | Entfernt diese Instanz. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | Entfernt ein Attribut nach Name. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | Entfernt den angegebenen Attributknoten. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | Entfernt ein Attribut nach lokalem Namen und Paket-URI. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Die Methode `removeChild()` des Node-Interfaces entfernt einen Kindknoten aus dem DOM und gibt den entfernten Knoten zurück. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Diese Methode ermöglicht das Entfernen von Event-Listenern vom Event-Ziel. Wenn ein Listener während der Verarbeitung eines Events entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Event-Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Diese Methode ermöglicht das Entfernen von Event-Listenern vom Event-Ziel. Wenn ein Listener während der Verarbeitung eines Events entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Event-Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Diese Methode ermöglicht das Entfernen von Event-Listenern vom Event-Ziel. Wenn ein Listener während der Verarbeitung eines Events entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Event-Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Ersetzt den Kindknoten oldChild durch newChild in der Kindliste und gibt den alten oldChild‑Knoten zurück. Ist newChild ein [`DocumentFragment`](../documentfragment/)‑Objekt, wird oldChild durch alle Kinder des [`DocumentFragment`](../documentfragment/) ersetzt, die in derselben Reihenfolge eingefügt werden. Befindet sich newChild bereits im Baum, wird es zuerst entfernt. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | Fügt ein neues Attribut hinzu. Wenn bereits ein Attribut mit diesem Namen im Element vorhanden ist, wird sein Wert auf den des Parameterwertes geändert. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | Fügt einen neuen Attributknoten hinzu. Wenn bereits ein Attribut mit diesem Namen (nodeName) im Element vorhanden ist, wird es durch das neue ersetzt. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | Fügt ein neues Attribut hinzu. Wenn bereits ein Attribut mit diesem lokalen Namen und diesem Paket‑URI im Element vorhanden ist, wird es durch das neue ersetzt. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | Fügt ein neues Attribut hinzu. Wenn bereits ein Attribut mit demselben lokalen Namen und Paket‑URI im Element vorhanden ist, wird sein Präfix auf den Präfix‑Teil des qualifiedName geändert und sein Wert auf den Wert‑Parameter gesetzt. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/#toggleattribute)(String) | Wenn force nicht angegeben ist, wird qualifiedName „gewechselt“, d. i. es wird entfernt, wenn es vorhanden ist, und hinzugefügt, wenn es nicht vorhanden ist. Ist force true, wird qualifiedName hinzugefügt. Ist force false, wird qualifiedName entfernt. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/#toggleattribute_1)(String, bool) | Wenn force nicht angegeben ist, wird qualifiedName „gewechselt“, d. i. es wird entfernt, wenn es vorhanden ist, und hinzugefügt, wenn es nicht vorhanden ist. Ist force true, wird qualifiedName hinzugefügt. Ist force false, wird qualifiedName entfernt. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Gibt einen String zurück, der diese Instanz darstellt. |

### Siehe auch

* class [Node](../node/)
* interface [IChildNode](../ichildnode/)
* interface [IParentNode](../iparentnode/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
