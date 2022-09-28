---
title: SVGFEBlendElement
second_title: Aspose.HTML für .NET-API-Referenz
description: Die SVGFEBlendElementSchnittstelle entspricht dem feBlendElement.
type: docs
weight: 1370
url: /de/net/aspose.html.dom.svg.filters/svgfeblendelement/
---
## SVGFEBlendElement class

Die SVGFEBlendElement-Schnittstelle entspricht dem 'feBlend'-Element.

```csharp
public class SVGFEBlendElement : SVGElement, ISVGFilterPrimitiveStandardAttributes
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Attributes](../../aspose.html.dom/element/attributes) { get; } | Eine NamedNodeMap, die die Attribute dieses Knotens enthält (wenn es sich um ein Element handelt) oder null andernfalls. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | Der absolute Basis-URI dieses Knotens oder null, wenn die Implementierung keinen absoluten URI erhalten konnte. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount) { get; } | Gibt die aktuelle Anzahl der Elementknoten zurück, die Kinder dieses Elements sind. 0, wenn dieses Element keine untergeordneten Knoten hat, die vom nodeType 1. sind |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | Eine NodeList, die alle Kinder dieses Knotens enthält. Wenn es keine Kinder gibt, ist dies eine NodeList, die keine Knoten enthält.. |
| [Children](../../aspose.html.dom/element/children) { get; } | Gibt die untergeordneten Elemente des aktuellen Elements zurück. |
| [ClassList](../../aspose.html.dom/element/classlist) { get; } | Gibt eine Live-DOMTokenList zurück, die Token enthält, die beim Parsen des Attributs „class“ empfangen wurden. |
| [ClassName](../../aspose.html.dom.svg/svgelement/classname) { get; } | Entspricht dem Attribut 'class' des angegebenen Elements. |
| [ClassName](../../aspose.html.dom/element/classname) { get; set; } | Das Klassenattribut des Elements. Dieses Attribut wurde in due umbenannt, da Konflikte mit dem Schlüsselwort „class“ in vielen Sprachen auftreten. Siehe die Klassenattributdefinition in HTML 4.01. |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | Das erste untergeordnete Element dieses Knotens. Wenn es keinen solchen Knoten gibt, wird null zurückgegeben. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild) { get; } | Gibt den ersten untergeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine untergeordneten Elemente hat. |
| [Height](../../aspose.html.dom.svg.filters/svgfeblendelement/height) { get; } | Entspricht dem Attribut „Höhe“ des angegebenen „Filter“-Elements. |
| [Id](../../aspose.html.dom.svg/svgelement/id) { get; set; } | Der Wert des Attributs „id“ für das angegebene Element oder die leere Zeichenfolge, wenn „id“ nicht vorhanden ist. |
| [In1](../../aspose.html.dom.svg.filters/svgfeblendelement/in1) { get; } | Entspricht dem Attribut „in“ des angegebenen „feBlend“-Elements. |
| [In2](../../aspose.html.dom.svg.filters/svgfeblendelement/in2) { get; } | Entspricht dem Attribut „in2“ des angegebenen „feBlend“-Elements. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml) { get; set; } | Gibt ein HTML- oder XML-Fragment zurück, das den Inhalt des Elements darstellt. Kann festgelegt werden, um den Inhalt des Elements durch Knoten zu ersetzen, die aus der angegebenen Zeichenfolge geparst wurden. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | Das letzte untergeordnete Element dieses Knotens. Wenn es keinen solchen Knoten gibt, wird null zurückgegeben. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild) { get; } | Gibt den letzten untergeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine untergeordneten Elemente hat. |
| override [LocalName](../../aspose.html.dom/element/localname) { get; } | Gibt den lokalen Teil des qualifizierten Namens dieses Knotens zurück. Für Knoten eines anderen Typs als ELEMENT_NODE und ATTRIBUTE_NODE und Knoten, die mit einer DOM-Level-1-Methode wie Document.createElement() erstellt wurden, ist dies immer null. |
| [Mode](../../aspose.html.dom.svg.filters/svgfeblendelement/mode) { get; } | Entspricht dem Attribut 'mode' des angegebenen 'feBlend'-Elements. Akzeptiert eine der SVG_FEBLEND_MODE_*-Konstanten, die auf dieser Schnittstelle definiert sind. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri) { get; } | Der Namespace-URI dieses Knotens oder null, wenn er nicht angegeben ist. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling) { get; } | Gibt den nächsten gleichgeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine untergeordneten Elementknoten hat, die im Dokumentbaum nach diesem Knoten kommen. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | Der Knoten unmittelbar nach diesem Knoten. Wenn es keinen solchen Knoten gibt, wird null zurückgegeben. |
| override [NodeName](../../aspose.html.dom/element/nodename) { get; } | Der Name dieses Knotens, abhängig von seinem Typ. |
| override [NodeType](../../aspose.html.dom/element/nodetype) { get; } | Ein Code, der den Typ des zugrunde liegenden Objekts darstellt. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | Der Wert dieses Knotens, abhängig von seinem Typ. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml) { get; set; } | Gibt ein HTML- oder XML-Fragment zurück, das das Element und seinen Inhalt darstellt. Kann festgelegt werden, um das Element durch Knoten zu ersetzen, die aus der angegebenen Zeichenfolge geparst wurden. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | Das diesem Knoten zugeordnete Document-Objekt. Dies ist auch das Document-Objekt, das zum Erstellen neuer Knoten verwendet wird. Wenn dieser Knoten ein Dokument oder ein Dokumenttyp ist, der noch mit keinem Dokument verwendet wird, ist dies null. |
| [OwnerSVGElement](../../aspose.html.dom.svg/svgelement/ownersvgelement) { get; } | Das nächste Vorfahren-'svg'-Element. Null, wenn das angegebene Element das äußerste SVG-Element ist. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | Ruft das übergeordnete Element ab[`Element`](../../aspose.html.dom/element) dieses Knotens. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | Das übergeordnete Element dieses Knotens. Alle Knoten außer Attr, Document, DocumentFragment, Entity und Notation können einen Elternknoten haben. Wenn jedoch ein Knoten gerade erstellt und noch nicht zum Baum hinzugefügt oder aus dem Baum entfernt wurde, ist dies null. |
| override [Prefix](../../aspose.html.dom/element/prefix) { get; } | Das Namespace-Präfix dieses Knotens oder null, wenn es nicht angegeben ist. Wenn es als null definiert ist, hat das Setzen keine Auswirkung |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling) { get; } | Gibt den vorherigen gleichgeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine Element-Geschwisterknoten hat, die vor diesem im Dokumentbaum stehen. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | Der Knoten unmittelbar vor diesem Knoten. Wenn es keinen solchen Knoten gibt, wird null zurückgegeben. |
| [Result](../../aspose.html.dom.svg.filters/svgfeblendelement/result) { get; } | Entspricht dem Attribut „Ergebnis“ des angegebenen „Filter“-Elements. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo) { get; } | Die diesem Element zugeordneten Typinformationen. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot) { get; } | Gibt shadowRoot zurück, das auf diesem Element gespeichert ist, oder null, wenn es geschlossen ist. |
| [Style](../../aspose.html.dom.svg/svgelement/style) { get; } | Entspricht dem Attribut 'style' des angegebenen Elements. Wenn der Benutzeragent kein Styling mit CSS unterstützt, muss dieses Attribut immer den Wert null haben. |
| [TagName](../../aspose.html.dom/element/tagname) { get; } | Der Name des Elements. |
| override [TextContent](../../aspose.html.dom/element/textcontent) { get; set; } | Dieses Attribut gibt den Textinhalt dieses Knotens und seiner Nachkommen zurück. Wenn es als null definiert ist, hat das Festlegen keine Auswirkung. Beim Setzen werden alle möglichen Kinder dieses Knotens entfernt und, falls die neue Zeichenfolge nicht leer oder null ist, durch einen einzelnen Textknoten ersetzt, der die Zeichenfolge enthält, auf die dieses Attribut gesetzt ist. |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement) { get; } | Das Element, das das aktuelle Ansichtsfenster festgelegt hat. Oft das nächste Vorfahren-'svg'-Element. Null, wenn das angegebene Element das äußerste SVG-Element ist. |
| [Width](../../aspose.html.dom.svg.filters/svgfeblendelement/width) { get; } | Entspricht dem Attribut „Breite“ des angegebenen „Filter“-Elements. |
| [X](../../aspose.html.dom.svg.filters/svgfeblendelement/x) { get; } | Entspricht dem Attribut 'x' im angegebenen 'filter'-Element. |
| [Y](../../aspose.html.dom.svg.filters/svgfeblendelement/y) { get; } | Entspricht dem Attribut 'y' des angegebenen 'filter'-Elements. |

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
| [SetAttribute](../../aspose.html.dom/element/setattribute)(string, string) | Fügt ein neues Attribut hinzu. Wenn ein Attribut mit diesem Namen bereits im Element vorhanden ist, wird sein Wert auf den Wert parameter geändert. |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode)(Attr) | Fügt einen neuen Attributknoten hinzu. Wenn ein Attribut mit diesem Namen (nodeName) bereits im Element vorhanden ist, wird es durch das neue ersetzt. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens)(Attr) | Fügt ein neues Attribut hinzu. Wenn ein Attribut mit diesem lokalen Namen und dieser Namespace-URI bereits im Element vorhanden ist, wird es durch das neue ersetzt. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens)(string, string, string) | Fügt ein neues Attribut hinzu. Wenn ein Attribut mit demselben lokalen Namen und Namespace-URI bereits für das Element vorhanden ist, wird sein Präfix in den Präfixteil des qualifizierten Namens und sein Wert in den Wertparameter geändert. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute)(string, bool) | Wenn der Parameter isId wahr ist, deklariert diese Methode das angegebene Attribut als ein benutzerdefiniertes ID-Attribut. |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode)(Attr, bool) | Wenn der Parameter isId wahr ist, deklariert diese Methode das angegebene Attribut als ein benutzerdefiniertes ID-Attribut. |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens)(string, string, bool) | Wenn der Parameter isId wahr ist, deklariert diese Methode das angegebene Attribut als ein benutzerdefiniertes ID-Attribut. |
| override [ToString](../../aspose.html.dom/node/tostring)() | Gibt a zurückString die diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [SVG_FEBLEND_MODE_COLOR](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_color) | Entspricht Wert 'Farbe'. |
| const [SVG_FEBLEND_MODE_COLOR_BURN](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_color_burn) | Entspricht Wert 'color_burn'. |
| const [SVG_FEBLEND_MODE_COLOR_DODGE](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_color_dodge) | Entspricht Wert 'color_dodge'. |
| const [SVG_FEBLEND_MODE_DARKEN](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_darken) | Entspricht dem Wert 'abdunkeln'. |
| const [SVG_FEBLEND_MODE_DIFFERENCE](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_difference) | Entspricht Wert 'Differenz'. |
| const [SVG_FEBLEND_MODE_EXCLUSION](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_exclusion) | Entspricht dem Wert 'Ausschluss'. |
| const [SVG_FEBLEND_MODE_HARD_LIGHT](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_hard_light) | Entspricht dem Wert 'hard_light'. |
| const [SVG_FEBLEND_MODE_HUE](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_hue) | Entspricht Wert 'hue'. |
| const [SVG_FEBLEND_MODE_LIGHTEN](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_lighten) | Entspricht Wert 'aufhellen'. |
| const [SVG_FEBLEND_MODE_LUMINOSITY](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_luminosity) | Entspricht Wert 'Leuchtkraft'. |
| const [SVG_FEBLEND_MODE_MULTIPLY](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_multiply) | Entspricht Wert 'multiplizieren'. |
| const [SVG_FEBLEND_MODE_NORMAL](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_normal) | Entspricht dem Wert 'normal'. |
| const [SVG_FEBLEND_MODE_OVERLAY](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_overlay) | Entspricht Wert 'Overlay'. |
| const [SVG_FEBLEND_MODE_SATURATION](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_saturation) | Entspricht dem Wert 'Sättigung'. |
| const [SVG_FEBLEND_MODE_SCREEN](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_screen) | Entspricht dem Wert 'screen'. |
| const [SVG_FEBLEND_MODE_SOFT_LIGHT](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_soft_light) | Entspricht dem Wert 'soft_light'. |
| const [SVG_FEBLEND_MODE_UNKNOWN](../../aspose.html.dom.svg.filters/svgfeblendelement/svg_feblend_mode_unknown) | Der Typ ist keiner der vordefinierten Typen. Es ist ungültig, einen neuen Wert dieses Typs zu definieren oder einen vorhandenen Wert auf diesen Typ umzustellen. |

### Siehe auch

* class [SVGElement](../../aspose.html.dom.svg/svgelement)
* interface [ISVGFilterPrimitiveStandardAttributes](../isvgfilterprimitivestandardattributes)
* namensraum [Aspose.Html.Dom.Svg.Filters](../../aspose.html.dom.svg.filters)
* Montage [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
