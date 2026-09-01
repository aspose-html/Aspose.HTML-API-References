---
title: "SVGMarkerElement Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.svg.SVGMarkerElement Klasse. Das SVGMarkerElement-Interface entspricht dem marker-Element."
type: docs

url: /de/java/com.aspose.html.dom.svg/svgmarkerelement/
---
## SVGMarkerElement class

Die SVGMarkerElement-Schnittstelle entspricht dem ‘marker’-Element.

```java
public class SVGMarkerElement : SVGElement, ISVGFitToViewBox
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) Eine NamedNodeMap, die die Attribute dieses Knotens enthält (wenn es ein Element ist) oder andernfalls null. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Die schreibgeschützte baseURI-Eigenschaft des Node-Interfaces gibt die absolute Basis-URL des Dokuments zurück, das den Knoten enthält. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) Gibt die aktuelle Anzahl von Elementknoten zurück, die Kind dieses Elements sind. 0, wenn dieses Element keine Kindknoten vom Typ nodeType 1 hat. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Die schreibgeschützte childNodes-Eigenschaft des Node-Interfaces gibt eine Live-[`NodeList`](../../com.aspose.html.collections/nodelist/) der Kindknoten des angegebenen Elements zurück, wobei dem ersten Kindknoten der Index 0 zugewiesen wird. Kindknoten umfassen Elemente, Text und Kommentare. |
| [getChildren](../../com.aspose.html.dom/element/children/) Gibt die Kind-Elemente des aktuellen Elements zurück. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) Gibt eine Live-DOMTokenList zurück, die Tokens enthält, die beim Parsen des "class"-Attributs erhalten wurden. |
| [getClassName](../../com.aspose.html.dom.svg/svgelement/classname/) Entspricht dem Attribut ‘class’ des angegebenen Elements. |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Die schreibgeschützte firstChild-Eigenschaft des [`Node`](../../com.aspose.html.dom/node/) Interfaces gibt das erste Kind des Knotens im Baum zurück, oder null, wenn der Knoten keine Kinder hat. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Gibt den ersten Kind-Elementknoten dieses Elements zurück. null, wenn dieses Element keine Kind-Elemente hat. |
[getId]
[setId] The value of the ‘id’ attribute on the given element, or the empty String if ‘id’ is not present. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Die schreibgeschützte lastChild-Eigenschaft des [`Node`](../../com.aspose.html.dom/node/) Interfaces gibt das letzte Kind des Knotens zurück. Wenn dessen Elternteil ein Element ist, ist das Kind in der Regel ein Elementknoten, ein Textknoten oder ein Kommentar‑Knoten. Sie gibt null zurück, wenn keine Kind‑Elemente vorhanden sind |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Gibt den letzten Kindelementknoten dieses Elements zurück. null, wenn dieses Element keine Kindelemente hat. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Gibt den lokalen Teil des qualifizierten Namens dieses Knotens zurück. Für Knoten jeglichen Typs außer ELEMENT_NODE und ATTRIBUTE_NODE sowie für mit einer DOM Level 1‑Methode erstellte Knoten, wie Document.createElement(), ist dies immer null. |
| [getMarkerHeight](../../com.aspose.html.dom.svg/svgmarkerelement/markerheight/) Entspricht dem Attribut ‘markerHeight’ des angegebenen ‘marker’-Elements. |
| [getMarkerUnits](../../com.aspose.html.dom.svg/svgmarkerelement/markerunits/) Entspricht dem Attribut ‘markerUnits’ des angegebenen ‘marker’-Elements. Einer der auf diesem Interface definierten Marker‑Einheitstypen. |
| [getMarkerWidth](../../com.aspose.html.dom.svg/svgmarkerelement/markerwidth/) Entspricht dem Attribut ‘markerWidth’ im angegebenen ‘marker’-Element. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) Der Namespace‑URI dieses Knotens oder null, wenn er nicht angegeben ist. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Gibt den nächsten Geschwister‑Elementknoten dieses Elements zurück. null, wenn dieses Element keine nachfolgenden Element‑Geschwisterknoten im Dokumentbaum hat. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Die schreibgeschützte nextSibling‑Eigenschaft des [`Node`](../../com.aspose.html.dom/node/)‑Interfaces gibt den Knoten zurück, der unmittelbar auf den angegebenen im [`childNodes`](../../com.aspose.html.dom/node/childnodes/)‑Array des Elternteils folgt, oder null, wenn der angegebene Knoten das letzte Kind im Elternelement ist. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) Der Name dieses Knotens, abhängig von seinem Typ. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) Ein Code, der den Typ des zugrunde liegenden Objekts darstellt. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Die nodeValue‑Eigenschaft des [`Node `](../../com.aspose.html.dom/node/)‑Interfaces gibt den Wert des aktuellen Knotens zurück oder setzt ihn. |
| [getOrientAngle](../../com.aspose.html.dom.svg/svgmarkerelement/orientangle/) Entspricht dem Attribut ‘orient’ im angegebenen ‘marker’-Element. Wenn markerUnits SVG_MARKER_ORIENT_ANGLE ist, der Winkelwert für das Attribut ‘orient’; andernfalls wird er auf Null gesetzt. |
| [getOrientType](../../com.aspose.html.dom.svg/svgmarkerelement/orienttype/) Entspricht dem Attribut ‘orient’ im angegebenen ‘marker’-Element. Einer der auf diesem Interface definierten Marker‑Orientierungstypen. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Die schreibgeschützte ownerDocument‑Eigenschaft des Node‑Interfaces gibt das oberste Dokumentobjekt des Knotens zurück. |
| [getOwnerSVGElement](../../com.aspose.html.dom.svg/svgelement/ownersvgelement/) Das nächstgelegene übergeordnete ‘svg’-Element. Null, wenn das angegebene Element das äußerste svg-Element ist. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Die schreibgeschützte parentElement‑Eigenschaft des [`Node`](../../com.aspose.html.dom/node/)‑Interfaces gibt das übergeordnete [`Element`](../../com.aspose.html.dom/element/)-DOM‑Knoten zurück, oder null, wenn der Knoten keinen Elternteil hat oder sein Elternteil kein DOM‑Element ist. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Die schreibgeschützte parentNode‑Eigenschaft des Node‑Interfaces gibt den Elternknoten des angegebenen Knotens im DOM‑Baum zurück. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) Das Namespace‑Präfix dieses Knotens oder null, wenn es nicht angegeben ist. Wenn es auf null gesetzt ist, hat das Setzen keine Wirkung. |
| [getPreserveAspectRatio](../../com.aspose.html.dom.svg/svgmarkerelement/preserveaspectratio/) Entspricht dem Attribut ‘preserveAspectRatio’ im angegebenen Element. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Gibt den vorherigen Geschwister‑Elementknoten dieses Elements zurück. null, wenn dieses Element keine vorherigen Element‑Geschwisterknoten im Dokumentbaum hat. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Die schreibgeschützte previousSibling‑Eigenschaft des [`Node`](../../com.aspose.html.dom/node/)‑Interfaces gibt den Knoten zurück, der unmittelbar vor dem angegebenen im [`childNodes`](../../com.aspose.html.dom/node/firstchild/)‑Array des Elternteils steht, oder null, wenn der angegebene Knoten der erste in dieser Liste ist. |
| [getRefX](../../com.aspose.html.dom.svg/svgmarkerelement/refx/) Entspricht dem Attribut ‘refX’ im angegebenen ‘marker’-Element. |
| [getRefY](../../com.aspose.html.dom.svg/svgmarkerelement/refy/) Entspricht dem Attribut ‘refY’ im angegebenen ‘marker’-Element. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Gibt das auf diesem Element gespeicherte shadowRoot zurück oder null, wenn es geschlossen ist. |
| [getStyle](../../com.aspose.html.dom.svg/svgelement/style/) Entspricht dem Attribut ‘style’ des angegebenen Elements. Wenn der User‑Agent keine CSS‑Styling‑Unterstützung bietet, muss dieses Attribut stets den Wert null haben. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) Der Name des Elements. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | Dieses Attribut gibt den Textinhalt dieses Knotens und seiner Nachkommen zurück. Wenn es auf null gesetzt ist, hat das Setzen keine Wirkung. Beim Setzen werden alle möglichen Kindknoten dieses Knotens entfernt und, falls die neue Zeichenkette nicht leer oder null ist, durch einen einzelnen Textknoten ersetzt, der die Zeichenkette enthält, auf die dieses Attribut gesetzt wird. |
| [getViewBox](../../com.aspose.html.dom.svg/svgmarkerelement/viewbox/) Entspricht dem Attribut ‘viewBox’ im angegebenen Element. |
| [getViewportElement](../../com.aspose.html.dom.svg/svgelement/viewportelement/) Das Element, das den aktuellen Viewport festgelegt hat. Oft das nächstgelegene übergeordnete ‘svg’-Element. Null, wenn das angegebene Element das äußerste svg-Element ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Die addEventListener()-Methode des [`EventTarget `](../../com.aspose.html.dom/eventtarget/)‑Interfaces richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel ausgeliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Die addEventListener()-Methode des [EventTarget ](T:com.aspose.html.dom.EventTarget)Interface richtet eine Funktion ein, die aufgerufen wird, sobald das angegebene Ereignis an das Ziel geliefert wird. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Die appendChild()-Methode des Node-Interface fügt einen Knoten am Ende der Kindliste eines angegebenen Elternknotens hinzu. Wenn das angegebene Kind eine Referenz zu einem bereits im Dokument vorhandenen Knoten ist, verschiebt appendChild() ihn von seiner aktuellen Position an die neue Position (es ist nicht erforderlich, den Knoten vor dem Anhängen an einen anderen Knoten aus seinem Elternknoten zu entfernen). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Erstellt einen Shadow Root und fügt ihn dem aktuellen Element hinzu. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Die cloneNode()-Methode des Node-Interface gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Ihr Parameter bestimmt, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Die cloneNode()-Methode des Node-Interface gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Ihr Parameter bestimmt, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Sendet ein Event an das angegebene [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synchron) und ruft die betroffenen EventListeners in der richtigen Reihenfolge auf. Die normalen Ereignisverarbeitungsregeln (einschließlich der Erfassungs‑ und optionalen Bubbling‑Phase) gelten ebenfalls für manuell mit [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) gesendete Events. |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Ruft einen Attributwert anhand des Namens ab. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Gibt die Attributnamen des Elements als Array von Strings zurück. Hat das Element keine Attribute, wird ein leeres Array zurückgegeben. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Ruft einen Attributknoten anhand des Namens ab. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Ruft einen Attr‑Knoten anhand des lokalen Namens und des Package‑URI ab. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Ruft einen Attributwert anhand des lokalen Namens und des Package‑URI ab. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Gibt ein [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/)-Objekt zurück, das alle Elemente innerhalb [`element`](../../com.aspose.html.dom/element/) enthält, die alle im Argument angegebenen Klassen besitzen. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Gibt ein [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/)-Objekt zurück, das alle [`elements`](../../com.aspose.html.dom/element/) mit einem angegebenen Tag‑Namen in Dokumentreihenfolge enthält. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Gibt ein [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/)-Objekt zurück, das alle [`elements`](../../com.aspose.html.dom/element/) mit einem angegebenen lokalen Namen und Package‑URI‑String in Dokumentreihenfolge enthält. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | Gibt true zurück, wenn ein Attribut mit dem angegebenen Namen an diesem Element festgelegt ist oder einen Standardwert hat, andernfalls false. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | Gibt true zurück, wenn ein Attribut mit dem angegebenen lokalen Namen und Package‑URI an diesem Element festgelegt ist oder einen Standardwert hat, andernfalls false. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | Gibt zurück, ob dieser Knoten (falls er ein Element ist) Attribute besitzt |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Die hasChildNodes()-Methode des Node-Interface gibt einen booleschen Wert zurück, der angibt, ob das angegebene [`Node`](../../com.aspose.html.dom/node/) Kindknoten hat oder nicht. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Die insertBefore()-Methode des Node-Interface fügt einen Knoten vor einem Referenzknoten als Kind eines angegebenen Elternknotens ein. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Die isDefaultNamespace()-Methode des Node-Interface akzeptiert einen Package‑URI als Argument. Sie gibt einen booleschen Wert zurück, der true ist, wenn das Package das Standard‑Package des angegebenen Knotens ist, andernfalls false. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Die isEqualNode()-Methode des [`Node`](../../com.aspose.html.dom/node/)-Interface prüft, ob zwei Knoten gleich sind. Zwei Knoten sind gleich, wenn sie denselben Typ, dieselben definierenden Merkmale (bei Elementen wären das ihre ID, die Anzahl der Kinder usw.) sowie passende Attribute besitzen. Die genauen Datenpunkte, die übereinstimmen müssen, variieren je nach Knotentyp. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Die isSameNode()-Methode des Node-Interface ist ein veralteter Alias für den strikten Gleichheitsoperator ===. Sie prüft, ob zwei Knoten identisch sind (mit anderen Worten, ob sie auf dasselbe Objekt verweisen). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Die lookupNamespaceURI()-Methode des Node-Interface nimmt ein Präfix als Parameter und gibt den zugehörigen Package‑URI des angegebenen Knotens zurück, falls gefunden (andernfalls null). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Die lookupPrefix()-Methode des Node-Interface gibt einen String zurück, der das Präfix für einen angegebenen Package‑URI enthält, falls vorhanden, andernfalls null. Wenn mehrere Präfixe möglich sind, wird das erste Präfix zurückgegeben. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Setzt alle [`Text`](../../com.aspose.html.dom/text/)-Knoten in der vollen Tiefe des Unterbaums unterhalb dieses Knotens, einschließlich Attributknoten, in eine \"normale\" Form, bei der nur die Struktur (z. B. [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), und [`entity references`](../../com.aspose.html.dom/entityreference/)) die [`Text`](../../com.aspose.html.dom/text/)-Knoten trennt, d. h. es gibt weder benachbarte Text‑Knoten noch leere Text‑Knoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM‑Ansicht eines Dokuments dieselbe ist, wie wenn sie gespeichert und erneut geladen würde, und ist nützlich, wenn Vorgänge (wie XPointer‑[XPointer]-Nachschlagen) verwendet werden sollen, die von einer bestimmten Dokumentbaumstruktur abhängen. Ist der Parameter \"normalize-characters\" des [`DOMConfiguration`](../../com.aspose.html/configuration/)-Objekts, das an das [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) angehängt ist, true, normalisiert diese Methode zudem vollständig die Zeichen der Text‑Knoten. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | Gibt das erste Element im Dokument zurück, das dem Selektor entspricht |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | Gibt eine NodeList aller Elemente im Dokument zurück, die dem Selektor entsprechen |
| [remove](../../com.aspose.html.dom/element/remove/)() | Entfernt diese Instanz. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | Entfernt ein Attribut nach Namen. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | Entfernt den angegebenen Attributknoten. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | Entfernt ein Attribut nach lokalem Namen und Paket-URI. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Die Methode removeChild() der Node‑Schnittstelle entfernt einen Kindknoten aus dem DOM und gibt den entfernten Knoten zurück. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein Listener während der Verarbeitung eines Ereignisses entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein Listener während der Verarbeitung eines Ereignisses entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Diese Methode ermöglicht das Entfernen von Ereignis‑Listenern vom Ereignis‑Ziel. Wenn ein Listener während der Verarbeitung eines Ereignisses entfernt wird, wird er nicht durch die aktuellen Aktionen ausgelöst. Ereignis‑Listener können nach dem Entfernen niemals mehr aufgerufen werden. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Ersetzt den Kindknoten oldChild durch newChild in der Kindliste und gibt den Knoten oldChild zurück. Wenn newChild ein [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/)‑Objekt ist, wird oldChild durch alle Kinder des [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) ersetzt, die in derselben Reihenfolge eingefügt werden. Wenn newChild bereits im Baum vorhanden ist, wird es zuerst entfernt. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | Fügt ein neues Attribut hinzu. Wenn bereits ein Attribut mit diesem Namen im Element vorhanden ist, wird sein Wert auf den des Wert‑Parameters geändert. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | Fügt einen neuen Attributknoten hinzu. Wenn bereits ein Attribut mit diesem Namen (nodeName) im Element vorhanden ist, wird es durch das neue ersetzt. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | Fügt ein neues Attribut hinzu. Wenn bereits ein Attribut mit diesem lokalen Namen und dieser Paket‑URI im Element vorhanden ist, wird es durch das neue ersetzt. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | Fügt ein neues Attribut hinzu. Wenn bereits ein Attribut mit demselben lokalen Namen und derselben Paket‑URI im Element vorhanden ist, wird sein Präfix auf den Präfix‑Teil des qualifiedName geändert und sein Wert auf den des Wert‑Parameters gesetzt. |
| [setOrientToAngle](../../com.aspose.html.dom.svg/svgmarkerelement/setorienttoangle/)(SVGAngle) | Setzt den Wert des Attributs ‘orient’ auf den angegebenen Winkel. |
| [setOrientToAuto](../../com.aspose.html.dom.svg/svgmarkerelement/setorienttoauto/)() | Setzt den Wert des Attributs ‘orient’ auf 'auto'. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | Wenn force nicht angegeben ist, wird qualifiedName „gewechselt“, d. h. es wird entfernt, wenn es vorhanden ist, und hinzugefügt, wenn es nicht vorhanden ist. Ist force true, wird qualifiedName hinzugefügt. Ist force false, wird qualifiedName entfernt. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | Wenn force nicht angegeben ist, wird qualifiedName „gewechselt“, d. h. es wird entfernt, wenn es vorhanden ist, und hinzugefügt, wenn es nicht vorhanden ist. Ist force true, wird qualifiedName hinzugefügt. Ist force false, wird qualifiedName entfernt. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [SVG_MARKERUNITS_STROKEWIDTH](../../com.aspose.html.dom.svg/svgmarkerelement/svg_markerunits_strokewidth/) | Der Wert des Attributs ‘markerUnits’ ist 'strokeWidth'. |
| const [SVG_MARKERUNITS_UNKNOWN](../../com.aspose.html.dom.svg/svgmarkerelement/svg_markerunits_unknown/) | Der Markierungseinheitstyp ist keiner der vordefinierten Typen. Es ist ungültig, zu versuchen, einen neuen Wert dieses Typs zu definieren oder einen bestehenden Wert zu diesem Typ zu wechseln. |
| const [SVG_MARKERUNITS_USERSPACEONUSE](../../com.aspose.html.dom.svg/svgmarkerelement/svg_markerunits_userspaceonuse/) | Der Wert des Attributs ‘markerUnits’ ist 'userSpaceOnUse'. |
| const [SVG_MARKER_ORIENT_ANGLE](../../com.aspose.html.dom.svg/svgmarkerelement/svg_marker_orient_angle/) | Das Attribut ‘orient’ hat einen Winkelwert. |
| const [SVG_MARKER_ORIENT_AUTO](../../com.aspose.html.dom.svg/svgmarkerelement/svg_marker_orient_auto/) | Das Attribut ‘orient’ hat den Wert 'auto'. |
| const [SVG_MARKER_ORIENT_UNKNOWN](../../com.aspose.html.dom.svg/svgmarkerelement/svg_marker_orient_unknown/) | Die Marker‑Orientierung ist keiner der vordefinierten Typen. Es ist ungültig, zu versuchen, einen neuen Wert dieses Typs zu definieren oder einen bestehenden Wert zu diesem Typ zu wechseln. |

### Siehe auch

* class [SVGElement](../svgelement/)
* interface [ISVGFitToViewBox](../isvgfittoviewbox/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
