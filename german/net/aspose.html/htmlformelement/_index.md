---
title: HTMLFormElement
second_title: Aspose.HTML für .NET-API-Referenz
description: DieBILDEN element umfasst ein Verhalten das einer Sammlung und einem Element ähnelt. Es bietet direkten Zugriff auf die enthaltenen Formularsteuerelemente sowie die Attribute des Formularelements. Siehe Definition des FORMElements in HTML 4.01.
type: docs
weight: 3220
url: /de/net/aspose.html/htmlformelement/
---
## HTMLFormElement class

Die`BILDEN` element umfasst ein Verhalten, das einer Sammlung und einem Element ähnelt. Es bietet direkten Zugriff auf die enthaltenen Formularsteuerelemente sowie die Attribute des Formularelements. Siehe Definition des FORM-Elements in HTML 4.01.

Siehe auch die[Document Object Model (DOM) Level 2 HTML-Spezifikation](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109) .

```csharp
public class HTMLFormElement : HTMLElement, IHTMLFormElement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AcceptCharset](../../aspose.html/htmlformelement/acceptcharset) { get; set; } | Liste der vom Server unterstützten Zeichensätze. Siehe die Attributdefinition Accept-Charset in HTML 4.01. |
| [Action](../../aspose.html/htmlformelement/action) { get; set; } | Serverseitiger Formularhandler. Siehe Aktionsattributdefinition in HTML 4.01. |
| override [Attributes](../../aspose.html.dom/element/attributes) { get; } | Eine NamedNodeMap, die die Attribute dieses Knotens enthält (wenn es sich um ein Element handelt) oder null andernfalls. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | Der absolute Basis-URI dieses Knotens oder null, wenn die Implementierung keinen absoluten URI erhalten konnte. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount) { get; } | Gibt die aktuelle Anzahl der Elementknoten zurück, die Kinder dieses Elements sind. 0, wenn dieses Element keine untergeordneten Knoten hat, die vom nodeType 1. sind |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | Eine NodeList, die alle Kinder dieses Knotens enthält. Wenn es keine Kinder gibt, ist dies eine NodeList, die keine Knoten enthält.. |
| [Children](../../aspose.html.dom/element/children) { get; } | Gibt die untergeordneten Elemente des aktuellen Elements zurück. |
| [ClassList](../../aspose.html.dom/element/classlist) { get; } | Gibt eine Live-DOMTokenList zurück, die Token enthält, die beim Parsen des Attributs „class“ empfangen wurden. |
| [ClassName](../../aspose.html/htmlelement/classname) { get; set; } | Das Klassenattribut des Elements. Dieses Attribut wurde aufgrund von umbenannt, da Konflikte mit dem Schlüsselwort „class“ in vielen Sprachen auftreten. Siehe die Klassenattributdefinition in HTML 4.01. |
| [Dir](../../aspose.html/htmlelement/dir) { get; set; } | Gibt die Basisrichtung von richtungsneutralem Text und die -Richtung von Tabellen an. Siehe dir-Attributdefinition in HTML 4.01. |
| [Elements](../../aspose.html/htmlformelement/elements) { get; } | Gibt eine Auflistung aller Formular-Steuerelemente im Formular zurück. |
| [Enctype](../../aspose.html/htmlformelement/enctype) { get; set; } | Der Inhaltstyp des übermittelten Formulars, im Allgemeinen "application/x-www-form-urlencoded". Siehe die Definition des enctype-Attributs in HTML 4.01. Es ist nicht garantiert, dass der onsubmit-Handler ausgelöst wird, wenn diese Methode aufgerufen wird. Das Verhalten ist aus historischen Gründen inkonsistent und Autoren sollten sich nicht auf ein bestimmtes verlassen. |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | Das erste untergeordnete Element dieses Knotens. Wenn es keinen solchen Knoten gibt, wird null zurückgegeben. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild) { get; } | Gibt den ersten untergeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine untergeordneten Elemente hat. |
| [Id](../../aspose.html/htmlelement/id) { get; set; } | Der Bezeichner des Elements. Siehe die ID-Attributdefinition in HTML 4.01. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml) { get; set; } | Gibt ein HTML- oder XML-Fragment zurück, das den Inhalt des Elements darstellt. Kann festgelegt werden, um den Inhalt des Elements durch Knoten zu ersetzen, die aus der angegebenen Zeichenfolge geparst wurden. |
| [Lang](../../aspose.html/htmlelement/lang) { get; set; } | Sprachcode definiert in RFC 1766. Siehe die lang-Attributdefinition in HTML 4.01. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | Das letzte untergeordnete Element dieses Knotens. Wenn es keinen solchen Knoten gibt, wird null zurückgegeben. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild) { get; } | Gibt den letzten untergeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine untergeordneten Elemente hat. |
| [Length](../../aspose.html/htmlformelement/length) { get; } | Die Anzahl der Formularsteuerelemente im Formular. |
| override [LocalName](../../aspose.html.dom/element/localname) { get; } | Gibt den lokalen Teil des qualifizierten Namens dieses Knotens zurück. Für Knoten eines anderen Typs als ELEMENT_NODE und ATTRIBUTE_NODE und Knoten, die mit einer DOM-Level-1-Methode wie Document.createElement() erstellt wurden, ist dies immer null. |
| [Method](../../aspose.html/htmlformelement/method) { get; set; } | HTTP-Methode [[IETF-RFC 2616](http://www.ietf.org/rfc/rfc2616.txt) zum Absenden des Formulars verwendet. Siehe Methodenattributdefinition in HTML 4.01. |
| [Name](../../aspose.html/htmlformelement/name) { get; set; } | Benennt das Formular. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri) { get; } | Der Namespace-URI dieses Knotens oder null, wenn er nicht angegeben ist. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling) { get; } | Gibt den nächsten gleichgeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine untergeordneten Elementknoten hat, die im Dokumentbaum nach diesem Knoten kommen. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | Der Knoten unmittelbar nach diesem Knoten. Wenn es keinen solchen Knoten gibt, wird null zurückgegeben. |
| override [NodeName](../../aspose.html.dom/element/nodename) { get; } | Der Name dieses Knotens, abhängig von seinem Typ. |
| override [NodeType](../../aspose.html.dom/element/nodetype) { get; } | Ein Code, der den Typ des zugrunde liegenden Objekts darstellt. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | Der Wert dieses Knotens, abhängig von seinem Typ. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml) { get; set; } | Gibt ein HTML- oder XML-Fragment zurück, das das Element und seinen Inhalt darstellt. Kann festgelegt werden, um das Element durch Knoten zu ersetzen, die aus der angegebenen Zeichenfolge geparst wurden. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | Das diesem Knoten zugeordnete Document-Objekt. Dies ist auch das Document-Objekt, das zum Erstellen neuer Knoten verwendet wird. Wenn dieser Knoten ein Dokument oder ein Dokumenttyp ist, der noch mit keinem Dokument verwendet wird, ist dies null. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | Ruft das übergeordnete Element ab[`Element`](../../aspose.html.dom/element) dieses Knotens. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | Das übergeordnete Element dieses Knotens. Alle Knoten außer Attr, Document, DocumentFragment, Entity und Notation können einen Elternknoten haben. Wenn jedoch ein Knoten gerade erstellt und noch nicht zum Baum hinzugefügt oder aus dem Baum entfernt wurde, ist dies null. |
| override [Prefix](../../aspose.html.dom/element/prefix) { get; } | Das Namespace-Präfix dieses Knotens oder null, wenn es nicht angegeben ist. Wenn es als null definiert ist, hat das Setzen keine Auswirkung |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling) { get; } | Gibt den vorherigen gleichgeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine Element-Geschwisterknoten hat, die vor diesem im Dokumentbaum stehen. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | Der Knoten unmittelbar vor diesem Knoten. Wenn es keinen solchen Knoten gibt, wird null zurückgegeben. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo) { get; } | Die diesem Element zugeordneten Typinformationen. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot) { get; } | Gibt shadowRoot zurück, das auf diesem Element gespeichert ist, oder null, wenn es geschlossen ist. |
| [Style](../../aspose.html/htmlelement/style) { get; } | Stellt ein Stilattribut dar, mit dem der Autor Stilinformationen direkt auf ein bestimmtes Element anwenden kann. |
| [TagName](../../aspose.html.dom/element/tagname) { get; } | Der Name des Elements. |
| [Target](../../aspose.html/htmlformelement/target) { get; set; } | Frame zum Rendern der Ressource. Siehe Zielattributdefinition in HTML 4.01. |
| override [TextContent](../../aspose.html.dom/element/textcontent) { get; set; } | Dieses Attribut gibt den Textinhalt dieses Knotens und seiner Nachkommen zurück. Wenn es als null definiert ist, hat das Festlegen keine Auswirkung. Beim Setzen werden alle möglichen Kinder dieses Knotens entfernt und, falls die neue Zeichenfolge nicht leer oder null ist, durch einen einzelnen Textknoten ersetzt, der die Zeichenfolge enthält, auf die dieses Attribut gesetzt ist. |
| [Title](../../aspose.html/htmlelement/title) { get; set; } | Der Empfehlungstitel des Elements. Siehe Definition des Titelattributs in HTML 4.01. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | Fügt den Knoten newChild am Ende der Liste der Kinder dieses Knotens hinzu. Wenn das newChild bereits im Baum vorhanden ist, wird es zuerst entfernt. |
| [AttachShadow](../../aspose.html.dom/element/attachshadow)(ShadowRootMode) | Erstellt einen Schattenstamm und hängt ihn an das aktuelle Element an. |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | Gibt ein Duplikat dieses Knotens zurück, dh dient als generischer Kopierkonstruktor für Knoten. Der doppelte Knoten hat keinen übergeordneten Knoten (parentNode ist null) und keine Benutzerdaten. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | Gibt ein Duplikat dieses Knotens zurück, dh dient als generischer Kopierkonstruktor für Knoten. Der doppelte Knoten hat keinen übergeordneten Knoten (parentNode ist null) und keine Benutzerdaten. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | Diese Methode ermöglicht die Weiterleitung von Ereignissen in das Ereignismodell der Implementierung. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [GetAttribute](../../aspose.html.dom/element/getattribute)(string) | Ruft einen Attributwert nach Namen ab. |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode)(string) | Ruft einen Attributknoten nach Namen ab. |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens)(string, string) | Ruft einen Attr-Knoten nach lokalem Namen und Namespace-URI ab. |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens)(string, string) | Ruft einen Attributwert nach lokalem Namen und Namespace-URI ab. |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname)(string) | Gibt ein aktives NodeList-Objekt zurück, das alle Elemente im Dokument enthält, die alle im Argument angegebenen Klassen haben. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname)(string) | Gibt eine NodeList aller untergeordneten Elemente mit einem bestimmten Tag-Namen in Dokumentreihenfolge zurück. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens)(string, string) | Gibt eine NodeList aller untergeordneten Elemente mit einem gegebenen lokalen Namen und Namensraum-URI in Dokumentenreihenfolge zurück. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [HasAttribute](../../aspose.html.dom/element/hasattribute)(string) | Gibt true zurück, wenn ein Attribut mit einem bestimmten Namen für dieses Element angegeben ist oder einen Standardwert hat, andernfalls false. |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens)(string, string) | Gibt „true“ zurück, wenn ein Attribut mit einem bestimmten lokalen Namen und Namensraum-URI für dieses Element angegeben ist oder einen Standardwert hat, andernfalls „false“. |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes)() | Gibt zurück, ob dieser Knoten (wenn es sich um ein Element handelt) irgendwelche Attribute hat |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | Gibt zurück, ob dieser Knoten Kinder hat. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | Fügt den Knoten vor dem vorhandenen untergeordneten Knoten child ein. Wenn child null ist, fügen Sie einen Knoten am Ende der Liste der untergeordneten Elemente ein. Wenn child ein DocumentFragment-Objekt ist, werden alle seine untergeordneten Elemente in derselben Reihenfolge vor dem untergeordneten Element eingefügt. Wenn das Kind bereits im Stammbaum ist, wird es zuerst entfernt. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | Diese Methode prüft, ob der angegebene NamespaceURI der Standard-Namespace ist oder nicht. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | Testet, ob zwei Knoten gleich sind. Diese Methode testet auf Gleichheit von Knoten, nicht auf Gleichheit (dh ob die beiden Knoten Verweise auf dasselbe Objekt sind), was mit Node.isSameNode() getestet werden kann. Alle Knoten, die gleich sind, sind auch gleich, obwohl das Gegenteil möglicherweise nicht der Fall ist. |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | Gibt zurück, ob dieser Knoten derselbe Knoten wie der gegebene ist. Mit dieser Methode kann festgestellt werden, ob zwei von der Implementierung zurückgegebene Node-Referenzen auf dasselbe Objekt verweisen. Wenn zwei Node-Referenzen Referenzen auf dasselbe Objekt sind, selbst wenn über einen Proxy, können die Referenzen vollständig austauschbar verwendet werden, sodass alle Attribute dieselben Werte haben und das Aufrufen derselben DOM-Methode für beide Referenzen immer genau denselben Effekt hat. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | Suchen Sie den Namespace-URI, der dem angegebenen Präfix zugeordnet ist, beginnend mit diesem Knoten. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | Suchen Sie das Präfix, das dem angegebenen Namespace-URI zugeordnet ist, beginnend mit diesem Knoten. Die Standard-Namespace-Deklarationen werden von dieser Methode ignoriert. Siehe Namespace Prefix Lookup für Details zum Algorithmus, der von dieser Methode verwendet wird. |
| [Normalize](../../aspose.html.dom/node/normalize)() | Bringt alle Textknoten in der vollen Tiefe des Unterbaums unterhalb dieses Knotens, einschließlich Attributknoten, in eine "normale" Form, wo nur Struktur (z. B. Elemente, Kommentare, Verarbeitungsanweisungen, CDATA-Abschnitte und Entitätsreferenzen) Text trennt Knoten, dh es gibt weder benachbarte Textknoten noch leere Textknoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM-Ansicht eines Dokuments dieselbe ist, als ob es gespeichert und neu geladen worden wäre, und ist nützlich, wenn Operationen (wie XPointer [XPointer]-Lookups), die von einer bestimmten Dokumentbaumstruktur abhängen, ausgeführt werden sollen verwendet werden. Wenn der Parameter „normalize-characters“ des an Node.ownerDocument angehängten DOMConfiguration-Objekts wahr ist, normalisiert diese Methode auch die Zeichen der Text-Nodes vollständig. |
| [QuerySelector](../../aspose.html.dom/element/queryselector)(string) | Gibt das erste Element im Dokument zurück, das mit selector übereinstimmt |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall)(string) | Gibt eine NodeList aller Elemente im Dokument zurück, die mit selector übereinstimmen. |
| [Remove](../../aspose.html.dom/element/remove)() | Entfernt diese Instanz. |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute)(string) | Entfernt ein Attribut nach Namen. |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode)(Attr) | Entfernt den angegebenen Attributknoten. |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens)(string, string) | Entfernt ein Attribut nach lokalem Namen und Namespace-URI. |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | Entfernt den durch oldChild angegebenen untergeordneten Knoten aus der Liste der untergeordneten Elemente und gibt ihn zurück. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../aspose.html.dom.events/ieventlistener) wird aus einem entfernt[`EventTarget`](../../aspose.html.dom/eventtarget) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../aspose.html.dom.events/ieventlistener) wird aus einem entfernt[`EventTarget`](../../aspose.html.dom/eventtarget) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../aspose.html.dom.events/ieventlistener) wird aus einem entfernt[`EventTarget`](../../aspose.html.dom/eventtarget) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | Ersetzt den untergeordneten Knoten oldChild durch newChild in der Liste der untergeordneten Elemente und gibt den oldChild-Knoten zurück. Wenn newChild ein DocumentFragment-Objekt ist, wird oldChild durch alle DocumentFragment-Kinder ersetzt, die in derselben Reihenfolge eingefügt werden. Wenn das newChild bereits im Baum vorhanden ist, wird es zuerst entfernt. |
| [Reset](../../aspose.html/htmlformelement/reset)() | Stellt die Standardwerte eines Formularelements wieder her. Es führt die gleiche Aktion wie eine Reset-Taste aus. |
| [SetAttribute](../../aspose.html.dom/element/setattribute)(string, string) | Fügt ein neues Attribut hinzu. Wenn ein Attribut mit diesem Namen bereits im Element vorhanden ist, wird sein Wert auf den Wert parameter geändert. |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode)(Attr) | Fügt einen neuen Attributknoten hinzu. Wenn ein Attribut mit diesem Namen (nodeName) bereits im Element vorhanden ist, wird es durch das neue ersetzt. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens)(Attr) | Fügt ein neues Attribut hinzu. Wenn ein Attribut mit diesem lokalen Namen und dieser Namespace-URI bereits im Element vorhanden ist, wird es durch das neue ersetzt. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens)(string, string, string) | Fügt ein neues Attribut hinzu. Wenn ein Attribut mit demselben lokalen Namen und Namespace-URI bereits für das Element vorhanden ist, wird sein Präfix in den Präfixteil des qualifizierten Namens und sein Wert in den Wertparameter geändert. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute)(string, bool) | Wenn der Parameter isId wahr ist, deklariert diese Methode das angegebene Attribut als ein benutzerdefiniertes ID-Attribut. |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode)(Attr, bool) | Wenn der Parameter isId wahr ist, deklariert diese Methode das angegebene Attribut als ein benutzerdefiniertes ID-Attribut. |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens)(string, string, bool) | Wenn der Parameter isId wahr ist, deklariert diese Methode das angegebene Attribut als ein benutzerdefiniertes ID-Attribut. |
| [Submit](../../aspose.html/htmlformelement/submit)() | Sendet das Formular ab. Es führt die gleiche Aktion aus wie eine Senden-Schaltfläche. |
| override [ToString](../../aspose.html.dom/node/tostring)() | Gibt a zurückString die diese Instanz darstellt. |

### Siehe auch

* class [HTMLElement](../htmlelement)
* interface [IHTMLFormElement](../ihtmlformelement)
* namensraum [Aspose.Html](../../aspose.html)
* Montage [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
