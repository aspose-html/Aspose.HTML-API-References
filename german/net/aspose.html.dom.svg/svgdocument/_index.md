---
title: Class SVGDocument
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Svg.SVGDocument klas. EinSVGDocumentist die Wurzel der SVGHierarchie und enthält den gesamten Inhalt. Neben dem Zugriff auf die Hierarchie bietet es auch einige bequeme Methoden für den Zugriff auf bestimmte Informationssätze aus dem Dokument. Element inline in ein XHTMLDokument XHTML eingebettet ist dann existiert kein SVGDocumentObjekt stattdessen ist das Stammobjekt in der Dokumentobjekthierarchie ein DocumentObjekt eines anderen Typs beispielsweise ein HTMLDocumentObjekt. Ein SVGDocumentObjekt wird jedoch tatsächlich existieren wenn das Stammelement der XMLDokumenthierarchie ein svgElement ist  z. B. beim Anzeigen einer eigenständigen SVGDatei dh einer Datei mit dem MIMETyp image/svgxml. In diesem Fall ist das SVGDocumentObjekt das Stammobjekt der DocumentObjectModelHierarchie.
type: docs
weight: 2010
url: /de/net/aspose.html.dom.svg/svgdocument/
---
## SVGDocument class

Ein`SVGDocument`ist die Wurzel der SVG-Hierarchie und enthält den gesamten Inhalt. Neben dem Zugriff auf die Hierarchie bietet es auch einige bequeme Methoden für den Zugriff auf bestimmte Informationssätze aus dem Dokument. -Element inline in ein XHTML-Dokument [XHTML] eingebettet ist, dann existiert kein SVGDocument-Objekt; stattdessen ist das Stammobjekt in der Dokumentobjekthierarchie ein Document-Objekt eines anderen Typs, beispielsweise ein HTMLDocument-Objekt. Ein SVGDocument-Objekt wird jedoch tatsächlich existieren, wenn das Stammelement der XML-Dokumenthierarchie ein 'svg'-Element ist , z. B. beim Anzeigen einer eigenständigen SVG-Datei (dh einer Datei mit dem MIME-Typ "image/svg+xml"). In diesem Fall ist das SVGDocument-Objekt das Stammobjekt der Document-Object-Model-Hierarchie.

```csharp
public class SVGDocument : Document, IDocumentCSS
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SVGDocument](svgdocument/#constructor)() | Initialisiert eine neue Instanz von`SVGDocument` Klasse. |
| [SVGDocument](svgdocument/#constructor_1)(Configuration) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. |
| [SVGDocument](svgdocument/#constructor_2)(RequestMessage) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_10)(string) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_4)(Url) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_3)(RequestMessage, Configuration) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_8)(Stream, string) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Das Laden des Dokuments beginnt an der aktuellen Position im Stream. |
| [SVGDocument](svgdocument/#constructor_6)(Stream, Url) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Das Laden des Dokuments beginnt an der aktuellen Position im Stream. |
| [SVGDocument](svgdocument/#constructor_11)(string, Configuration) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_14)(string, string) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_12)(string, Url) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_5)(Url, Configuration) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_9)(Stream, string, Configuration) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Das Laden des Dokuments beginnt an der aktuellen Position im Stream. |
| [SVGDocument](svgdocument/#constructor_7)(Stream, Url, Configuration) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Das Laden des Dokuments beginnt an der aktuellen Position im Stream. |
| [SVGDocument](svgdocument/#constructor_15)(string, string, Configuration) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_13)(string, Url, Configuration) | Initialisiert eine neue Instanz von`SVGDocument` Klasse. Der Konstruktor arbeitet synchron, er wartet auf das Laden aller externen Ressourcen (Bilder, Skripte usw.). Um das Dokument asynchron zu laden, verwenden Sie die Methode[`Navigate`](../../aspose.html.dom/document/navigate/) oder seine Überladungen. Oder Sie können das Laden einiger externer Ressourcen deaktivieren, indem Sie entsprechende Flags setzen[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | Eine NamedNodeMap, die die Attribute dieses Knotens enthält (wenn es sich um ein Element handelt) oder null andernfalls. |
| override [BaseURI](../../aspose.html.dom/document/baseuri/) { get; } | Der absolute Basis-URI dieses Knotens oder null, wenn die Implementierung keinen absoluten URI erhalten konnte. |
| [CharacterSet](../../aspose.html.dom/document/characterset/) { get; } | Ruft die Kodierung des Dokuments ab. |
| [Charset](../../aspose.html.dom/document/charset/) { get; } | Ruft die Kodierung des Dokuments ab. |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount/) { get; } | Gibt die aktuelle Anzahl der Elementknoten zurück, die Kinder dieses Elements sind. 0, wenn dieses Element keine untergeordneten Knoten hat, die vom nodeType 1. sind |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Eine NodeList, die alle Kinder dieses Knotens enthält. Wenn es keine Kinder gibt, ist dies eine NodeList, die keine Knoten enthält.. |
| [Children](../../aspose.html.dom/document/children/) { get; } | Gibt die untergeordneten Elemente zurück. |
| [ContentType](../../aspose.html.dom/document/contenttype/) { get; } | Ruft den Inhaltstyp des Dokuments ab. |
| [Context](../../aspose.html.dom/document/context/) { get; } | Ruft den aktuellen Browserkontext ab. |
| [DefaultView](../../aspose.html.dom/document/defaultview/) { get; } | Das IDL-Attribut defaultView der Document-Schnittstelle muss beim Abrufen von das WindowProxy-Objekt des Browsing-Kontexts dieses Dokuments zurückgeben, , wenn dieses Dokument einen zugehörigen Browsing-Kontext hat, oder andernfalls null. |
| [Doctype](../../aspose.html.dom/document/doctype/) { get; } | Die diesem Dokument zugeordnete Dokumenttypdeklaration. |
| [DocumentElement](../../aspose.html.dom/document/documentelement/) { get; } | Dies ist ein praktisches Attribut, das direkten Zugriff auf den untergeordneten Knoten ermöglicht, der das Dokumentelement des Dokuments ist. |
| [DocumentURI](../../aspose.html.dom/document/documenturi/) { get; } | Der Speicherort des Dokuments oder null, wenn nicht definiert oder wenn das Dokument mit DOMImplementation.createDocument erstellt wurde. |
| [Domain](../../aspose.html.dom.svg/svgdocument/domain/) { get; } | Der Domänenname des Servers, der das Dokument bereitgestellt hat, oder eine Nullzeichenfolge, wenn der Server nicht durch einen Domänennamen identifiziert werden kann. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Das erste untergeordnete Element dieses Knotens. Wenn es keinen solchen Knoten gibt, wird null zurückgegeben. |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild/) { get; } | Gibt den ersten untergeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine untergeordneten Elemente hat. |
| [Implementation](../../aspose.html.dom/document/implementation/) { get; } | Das DOMImplementation-Objekt, das dieses Dokument verarbeitet. |
| [InputEncoding](../../aspose.html.dom/document/inputencoding/) { get; } | Ruft die Kodierung des Dokuments ab. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Das letzte untergeordnete Element dieses Knotens. Wenn es keinen solchen Knoten gibt, wird null zurückgegeben. |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild/) { get; } | Gibt den letzten untergeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine untergeordneten Elemente hat. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Gibt den lokalen Teil des qualifizierten Namens dieses Knotens zurück. Für Knoten eines anderen Typs als ELEMENT_NODE und ATTRIBUTE_NODE und Knoten, die mit einer DOM-Level-1-Methode wie Document.createElement() erstellt wurden, ist dies immer null. |
| [Location](../../aspose.html.dom/document/location/) { get; } | Der Speicherort des Dokuments. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | Der Namespace-URI dieses Knotens oder null, wenn er nicht angegeben ist. |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling/) { get; } | Gibt den nächsten gleichgeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine untergeordneten Elementknoten hat, die im Dokumentbaum nach diesem Knoten kommen. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Der Knoten unmittelbar nach diesem Knoten. Wenn es keinen solchen Knoten gibt, wird null zurückgegeben. |
| override [NodeName](../../aspose.html.dom/document/nodename/) { get; } | Der Name dieses Knotens, abhängig von seinem Typ. |
| override [NodeType](../../aspose.html.dom/document/nodetype/) { get; } | Ein Code, der den Typ des zugrunde liegenden Objekts darstellt. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Der Wert dieses Knotens, abhängig von seinem Typ. |
| [Origin](../../aspose.html.dom/document/origin/) { get; } | Ruft den Dokumentursprung ab. |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument/) { get; } | Ruft das Besitzerdokument ab. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Ruft das übergeordnete Element ab[`Element`](../../aspose.html.dom/element/) dieses Knotens. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Das übergeordnete Element dieses Knotens. Alle Knoten außer Attr, Document, DocumentFragment, Entity und Notation können einen Elternknoten haben. Wenn jedoch ein Knoten gerade erstellt und noch nicht zum Baum hinzugefügt oder aus dem Baum entfernt wurde, ist dies null. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | Das Namespace-Präfix dieses Knotens oder null, wenn es nicht angegeben ist. Wenn es als null definiert ist, hat das Setzen keine Auswirkung |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling/) { get; } | Gibt den vorherigen gleichgeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine Element-Geschwisterknoten hat, die vor diesem im Dokumentbaum stehen. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Der Knoten unmittelbar vor diesem Knoten. Wenn es keinen solchen Knoten gibt, wird null zurückgegeben. |
| [ReadyState](../../aspose.html.dom/document/readystate/) { get; } | Gibt die Dokumentenbereitschaft zurück. Das "Laden", während das Dokument geladen wird, "interaktiv", wenn es mit dem Parsen fertig ist, aber immer noch Unterressourcen lädt, und "abschließen", sobald es geladen ist. |
| [Referrer](../../aspose.html.dom.svg/svgdocument/referrer/) { get; } | Gibt den URI der Seite zurück, die auf diese Seite verlinkt ist. Der Wert ist ein leerer String, wenn der Benutzer direkt auf die Seite navigiert ist (nicht über einen Link, sondern beispielsweise über ein Lesezeichen). |
| [RootElement](../../aspose.html.dom.svg/svgdocument/rootelement/) { get; } | Die Wurzel „svg“ in der Dokumenthierarchie. |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking/) { get; set; } | Ein Attribut, das angibt, ob eine Fehlerprüfung erzwungen wird oder nicht. Wenn auf „false“ gesetzt, steht es der Implementierung frei, nicht jeden möglichen Fehlerfall zu testen, der normalerweise für DOM-Operationen definiert ist, und keine DOMException für DOM-Operationen auszulösen oder Fehler zu melden, während Document.normalizeDocument() verwendet wird. Im Fehlerfall ist das Verhalten undefiniert. Dieses Attribut ist standardmäßig wahr. |
| [StyleSheets](../../aspose.html.dom/document/stylesheets/) { get; } | Eine Liste mit allen Stylesheets, die explizit mit einem Dokument verknüpft oder darin eingebettet sind. Bei HTML-Dokumenten umfasst dies externe Stylesheets, die über das HTML-LINK-Element eingebunden werden, und Inline-STYLE-Elemente. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent/) { get; set; } | Dieses Attribut gibt den Textinhalt dieses Knotens und seiner Nachkommen zurück. Wenn es als null definiert ist, hat das Festlegen keine Auswirkung. Beim Setzen werden alle möglichen Kinder dieses Knotens entfernt und, falls die neue Zeichenfolge nicht leer oder null ist, durch einen einzelnen Textknoten ersetzt, der die Zeichenfolge enthält, auf die dieses Attribut gesetzt ist. |
| [Title](../../aspose.html.dom.svg/svgdocument/title/) { get; } | Der Titel eines Dokuments, wie er durch das Unterelement „title“ des Root-Elements „svg“ angegeben wird (d. h.Hier ist der Titel... ) |
| [URL](../../aspose.html.dom.svg/svgdocument/url/) { get; } | Der vollständige URI des Dokuments. |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone/) { get; set; } | Ein Attribut, das als Teil der XML-Deklaration angibt, ob dieses Dokument eigenständig ist. Dies ist falsch, wenn nicht angegeben. |
| [XmlVersion](../../aspose.html.dom/document/xmlversion/) { get; set; } | Ein Attribut, das als Teil der XML-Deklaration die Versionsnummer dieses Dokuments angibt. Wenn keine Deklaration vorhanden ist und dieses Dokument die Funktion „XML“ unterstützt, ist der Wert „1.0“. Wenn dieses Dokument die Funktion "XML" nicht unterstützt, ist der Wert immer null. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Fügt den Knoten newChild am Ende der Liste der Kinder dieses Knotens hinzu. Wenn das newChild bereits im Baum vorhanden ist, wird es zuerst entfernt. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Gibt ein Duplikat dieses Knotens zurück, dh dient als generischer Kopierkonstruktor für Knoten. Der doppelte Knoten hat keinen übergeordneten Knoten (parentNode ist null) und keine Benutzerdaten. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Gibt ein Duplikat dieses Knotens zurück, dh dient als generischer Kopierkonstruktor für Knoten. Der doppelte Knoten hat keinen übergeordneten Knoten (parentNode ist null) und keine Benutzerdaten. |
| [CreateAttribute](../../aspose.html.dom/document/createattribute/)(string) | Erstellt ein Attr des angegebenen Namens. |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens/)(string, string) | Erstellt ein Attribut des angegebenen qualifizierten Namens und Namespace-URI. |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection/)(string) | Erstellt einen CDATASection-Knoten, dessen Wert die angegebene Zeichenfolge ist. |
| [CreateComment](../../aspose.html.dom/document/createcomment/)(string) | Erstellt einen Kommentarknoten mit der angegebenen Zeichenfolge. |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment/)() | Erstellt ein leeres DocumentFragment-Objekt. |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype/)(string, string, string, string) | Erstellt einen DocumentType-Knoten. |
| [CreateElement](../../aspose.html.dom/document/createelement/)(string) | Erstellt ein Element des angegebenen Typs. Beachten Sie, dass die zurückgegebene Instanz die Element-Schnittstelle implementiert, sodass Attribute direkt für das zurückgegebene Objekt angegeben werden können. |
| [CreateElementNS](../../aspose.html.dom/document/createelementns/)(string, string) | Erstellt ein Element des angegebenen qualifizierten Namens und Namespace-URI. |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference/)(string) | Erstellt ein EntityReference-Objekt. Wenn die referenzierte Entität bekannt ist, wird außerdem die untergeordnete Liste des EntityReference-Knotens mit der des entsprechenden Entitätsknotens identisch gemacht. |
| [CreateEvent](../../aspose.html.dom/document/createevent/)(string) | Erstellt eine[`Event`](../../aspose.html.dom.events/event/) eines Typs, der von der Implementierung unterstützt wird. |
| [CreateExpression](../../aspose.html.dom/document/createexpression/)(string, IXPathNSResolver) | Erstellt einen geparsten XPath-Ausdruck mit aufgelösten Namespaces. Dies ist nützlich, wenn ein Ausdruck in einer Anwendung wiederverwendet wird, da es ermöglicht, die Ausdruckszeichenfolge in eine effizientere interne Form zu kompilieren und alle Namensraumpräfixe vorab aufzulösen, die innerhalb des Ausdrucks vorkommen. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node) | Erstellen Sie einen neuen NodeIterator über dem Teilbaum, der an dem angegebenen Knoten verwurzelt ist. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long) | Erstellen Sie einen neuen NodeIterator über dem Teilbaum, der an dem angegebenen Knoten verwurzelt ist. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Erstellen Sie einen neuen NodeIterator über dem Teilbaum, der an dem angegebenen Knoten verwurzelt ist. |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver/)(Node) | Passt jeden DOM-Knoten an, um Namespaces aufzulösen, so dass ein XPath-Ausdruck leicht ausgewertet werden kann relativ zum Kontext des Knotens, in dem er im Dokument vorkam. Dieser Adapter funktioniert wie die DOM-Level-3-Methode`lookupNamespace-URI` auf Knoten beim Auflösen des Namensraum-URI aus einem gegebenen Präfix unter Verwendung der aktuellen Informationen, die in der Knotenhierarchie zu dem Zeitpunkt verfügbar sind, an dem lookupNamespaceURI aufgerufen wird, wobei auch das implizite XML-Präfix korrekt aufgelöst wird. |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction/)(string, string) | Erstellt einen ProcessingInstruction-Knoten mit dem angegebenen Namen und den angegebenen Datenstrings. |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode/)(string) | Erstellt einen Textknoten mit der angegebenen Zeichenfolge. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node) | Erstellen Sie einen neuen TreeWalker über dem Teilbaum, der an dem angegebenen Knoten verwurzelt ist. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long) | Erstellen Sie einen neuen TreeWalker über dem Teilbaum, der an dem angegebenen Knoten verwurzelt ist. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | Erstellen Sie einen neuen TreeWalker über dem Teilbaum, der an dem angegebenen Knoten verwurzelt ist. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Diese Methode ermöglicht die Weiterleitung von Ereignissen in das Ereignismodell der Implementierung. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [Evaluate](../../aspose.html.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Wertet eine XPath-Ausdruckszeichenfolge aus und gibt, wenn möglich, ein Ergebnis des angegebenen Typs zurück. |
| [GetElementById](../../aspose.html.dom/document/getelementbyid/)(string) | Gibt das Element zurück, das ein ID-Attribut mit dem angegebenen Wert hat. Wenn kein solches Element vorhanden ist, gibt dies null zurück. Wenn mehr als ein Element ein ID-Attribut mit diesem Wert hat, ist das, was zurückgegeben wird, undefiniert. |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname/)(string) | Gibt ein aktives NodeList-Objekt zurück, das alle Elemente im Dokument enthält, die alle im Argument angegebenen Klassen haben. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname/)(string) | Gibt eine NodeList aller Elemente in Dokumentreihenfolge mit einem bestimmten Tag-Namen zurück und sind im Dokument enthalten. |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens/)(string, string) | Gibt eine NodeList aller Elemente mit einem gegebenen lokalen Namen und Namespace-URI in Dokumentenreihenfolge zurück. |
| [GetOverrideStyle](../../aspose.html.dom.svg/svgdocument/getoverridestyle/)(Element, string) | Diese Methode wird verwendet, um die Überschreibungsstildeklaration für ein bestimmtes Element und ein bestimmtes Pseudoelement abzurufen. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | Gibt zurück, ob dieser Knoten (wenn es sich um ein Element handelt) irgendwelche Attribute hat |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Gibt zurück, ob dieser Knoten Kinder hat. |
| [ImportNode](../../aspose.html.dom/document/importnode/)(Node, bool) | Importiert einen Knoten aus einem anderen Dokument in dieses Dokument, ohne den Quellknoten aus dem Originaldokument zu ändern oder zu entfernen; Diese Methode erstellt eine neue Kopie des Quellknotens. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Fügt den Knoten vor dem vorhandenen untergeordneten Knoten child ein. Wenn child null ist, fügen Sie einen Knoten am Ende der Liste der untergeordneten Elemente ein. Wenn child ein DocumentFragment-Objekt ist, werden alle seine untergeordneten Elemente in derselben Reihenfolge vor dem untergeordneten Element eingefügt. Wenn das Kind bereits im Stammbaum ist, wird es zuerst entfernt. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Diese Methode prüft, ob der angegebene NamespaceURI der Standard-Namespace ist oder nicht. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Testet, ob zwei Knoten gleich sind. Diese Methode testet auf Gleichheit von Knoten, nicht auf Gleichheit (dh ob die beiden Knoten Verweise auf dasselbe Objekt sind), was mit Node.isSameNode() getestet werden kann. Alle Knoten, die gleich sind, sind auch gleich, obwohl das Gegenteil möglicherweise nicht der Fall ist. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Gibt zurück, ob dieser Knoten derselbe Knoten wie der gegebene ist. Mit dieser Methode kann festgestellt werden, ob zwei von der Implementierung zurückgegebene Node-Referenzen auf dasselbe Objekt verweisen. Wenn zwei Node-Referenzen Referenzen auf dasselbe Objekt sind, selbst wenn über einen Proxy, können die Referenzen vollständig austauschbar verwendet werden, sodass alle Attribute dieselben Werte haben und das Aufrufen derselben DOM-Methode für beide Referenzen immer genau denselben Effekt hat. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Suchen Sie den Namespace-URI, der dem angegebenen Präfix zugeordnet ist, beginnend mit diesem Knoten. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Suchen Sie das Präfix, das dem angegebenen Namespace-URI zugeordnet ist, beginnend mit diesem Knoten. Die Standard-Namespace-Deklarationen werden von dieser Methode ignoriert. Siehe Namespace Prefix Lookup für Details zum Algorithmus, der von dieser Methode verwendet wird. |
| [Navigate](../../aspose.html.dom/document/navigate/)(RequestMessage) | Lädt das Dokument basierend auf dem angegebenen Anforderungsobjekt und ersetzt den vorherigen Inhalt. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string) | Lädt das Dokument unter der angegebenen URL (Uniform Resource Locator) in die aktuelle Instanz und ersetzt den vorherigen Inhalt. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Url) | Lädt das Dokument unter der angegebenen URL (Uniform Resource Locator) in die aktuelle Instanz und ersetzt den vorherigen Inhalt. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, string) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wodurch der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, Url) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wodurch der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, string) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, Url) | Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Bringt alle Textknoten in der vollen Tiefe des Unterbaums unterhalb dieses Knotens, einschließlich Attributknoten, in eine "normale" Form, wo nur Struktur (z. B. Elemente, Kommentare, Verarbeitungsanweisungen, CDATA-Abschnitte und Entitätsreferenzen) Text trennt Knoten, dh es gibt weder benachbarte Textknoten noch leere Textknoten. Dies kann verwendet werden, um sicherzustellen, dass die DOM-Ansicht eines Dokuments dieselbe ist, als ob es gespeichert und neu geladen worden wäre, und ist nützlich, wenn Operationen (wie XPointer [XPointer]-Lookups), die von einer bestimmten Dokumentbaumstruktur abhängen, ausgeführt werden sollen verwendet werden. Wenn der Parameter „normalize-characters“ des an Node.ownerDocument angehängten DOMConfiguration-Objekts wahr ist, normalisiert diese Methode auch die Zeichen der Text-Nodes vollständig. |
| [QuerySelector](../../aspose.html.dom/document/queryselector/)(string) | Gibt das erste Element im Dokument zurück, das mit selector übereinstimmt |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall/)(string) | Gibt eine NodeList aller Elemente im Dokument zurück, die mit selector übereinstimmen. |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Entfernt den durch oldChild angegebenen untergeordneten Knoten aus der Liste der untergeordneten Elemente und gibt ihn zurück. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) wird aus einem entfernt[`EventTarget`](../../aspose.html.dom/eventtarget/) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) wird aus einem entfernt[`EventTarget`](../../aspose.html.dom/eventtarget/) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) wird aus einem entfernt[`EventTarget`](../../aspose.html.dom/eventtarget/) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |
| override [RenderTo](../../aspose.html.dom.svg/svgdocument/renderto/)(IDevice) | Diese Methode wird verwendet, um den Inhalt des aktuellen Dokuments auf dem angegebenen Gerät zu drucken. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Ersetzt den untergeordneten Knoten oldChild durch newChild in der Liste der untergeordneten Elemente und gibt den oldChild-Knoten zurück. Wenn newChild ein DocumentFragment-Objekt ist, wird oldChild durch alle DocumentFragment-Kinder ersetzt, die in derselben Reihenfolge eingefügt werden. Wenn das newChild bereits im Baum vorhanden ist, wird es zuerst entfernt. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save)(IOutputStorage) | Speichert den Dokumentinhalt und die Ressourcen im Ausgabespeicher. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_6)(string) | Speichert das Dokument in der durch angegebenen lokalen Datei`Weg` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_3)(Url) | Speichert das Dokument in der durch angegebenen lokalen Datei`URL` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_1)(IOutputStorage, SVGSaveFormat) | Speichert den Dokumentinhalt und die Ressourcen im Ausgabespeicher. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_2)(IOutputStorage, SVGSaveOptions) | Speichert den Dokumentinhalt und die Ressourcen im Ausgabespeicher. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_7)(string, SVGSaveFormat) | Speichert das Dokument in der durch angegebenen lokalen Datei`Weg` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_8)(string, SVGSaveOptions) | Speichert das Dokument in der durch angegebenen lokalen Datei`Weg` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_4)(Url, SVGSaveFormat) | Speichert das Dokument in der durch angegebenen lokalen Datei`URL` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_5)(Url, SVGSaveOptions) | Speichert das Dokument in der durch angegebenen lokalen Datei`URL` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files". |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Gibt a zurückString die diese Instanz darstellt. |
| [Write](../../aspose.html.dom/document/write/)(params string[]) | Schreibt eine Textzeichenfolge in einen Dokumentenstrom, der von open() geöffnet wurde. Beachten Sie, dass die Funktion ein Dokument erzeugt, das nicht unbedingt von einer DTD gesteuert wird und daher möglicherweise ein ungültiges Ergebnis im Kontext des Dokuments erzeugt. |
| [WriteLn](../../aspose.html.dom/document/writeln/)(params string[]) | Schreibt eine Textzeichenfolge gefolgt von einem Zeilenumbruchzeichen in einen document -Stream, der durch open() geöffnet wurde. Beachten Sie, dass die Funktion ein Dokument erzeugt, das nicht unbedingt von einer DTD gesteuert wird, und daher möglicherweise ein ungültiges Ergebnis im Kontext des -Dokuments erzeugt. |

## Veranstaltungen

| Name | Beschreibung |
| --- | --- |
| event [OnAbort](../../aspose.html.dom/document/onabort/) | Ruft den Event-Handler für das OnAbort-Ereignis ab oder legt ihn fest. |
| event [OnBlur](../../aspose.html.dom/document/onblur/) | Ruft den Event-Handler für das OnBlur-Ereignis ab oder legt ihn fest. |
| event [OnCancel](../../aspose.html.dom/document/oncancel/) | Ruft den Ereignishandler für das OnCancel-Ereignis ab oder legt ihn fest. |
| event [OnCanplay](../../aspose.html.dom/document/oncanplay/) | Ruft den Ereignishandler für das OnCanplay-Ereignis ab oder legt ihn fest. |
| event [OnCanPlayThrough](../../aspose.html.dom/document/oncanplaythrough/) | Ruft den Ereignishandler für das OnCanPlayThrough-Ereignis ab oder legt ihn fest. |
| event [OnChange](../../aspose.html.dom/document/onchange/) | Ruft den Event-Handler für das OnChange-Ereignis ab oder legt ihn fest. |
| event [OnClick](../../aspose.html.dom/document/onclick/) | Ruft den Event-Handler für das OnClick-Ereignis ab oder legt ihn fest. |
| event [OnCueChange](../../aspose.html.dom/document/oncuechange/) | Ruft den Event-Handler für das OnCueChange-Ereignis ab oder legt ihn fest. |
| event [OnDblClick](../../aspose.html.dom/document/ondblclick/) | Ruft den Ereignishandler für das OnDblClick-Ereignis ab oder legt ihn fest. |
| event [OnDurationChange](../../aspose.html.dom/document/ondurationchange/) | Ruft den Ereignishandler für das OnDurationChange-Ereignis ab oder legt ihn fest. |
| event [OnEmptied](../../aspose.html.dom/document/onemptied/) | Ruft den Ereignishandler für das OnEmptied-Ereignis ab oder legt ihn fest. |
| event [OnEnded](../../aspose.html.dom/document/onended/) | Ruft Ereignishandler für OnEnded-Ereignis ab oder legt sie fest. |
| event [OnError](../../aspose.html.dom/document/onerror/) | Ruft den Event-Handler für das OnError-Ereignis ab oder legt ihn fest. |
| event [OnFocus](../../aspose.html.dom/document/onfocus/) | Ruft den Event-Handler für das OnFocus-Ereignis ab oder legt ihn fest. |
| event [OnInput](../../aspose.html.dom/document/oninput/) | Ruft den Ereignishandler für das OnInput-Ereignis ab oder legt ihn fest. |
| event [OnInvalid](../../aspose.html.dom/document/oninvalid/) | Ruft Ereignishandler für das OnInvalid-Ereignis ab oder legt es fest. |
| event [OnKeyDown](../../aspose.html.dom/document/onkeydown/) | Ruft den Event-Handler für das OnKeyDown-Ereignis ab oder legt ihn fest. |
| event [OnKeyPress](../../aspose.html.dom/document/onkeypress/) | Ruft den Event-Handler für das OnKeyPress-Ereignis ab oder legt ihn fest. |
| event [OnKeyUp](../../aspose.html.dom/document/onkeyup/) | Ruft den Event-Handler für das OnKeyUp-Ereignis ab oder legt ihn fest. |
| event [OnLoad](../../aspose.html.dom/document/onload/) | Ruft den Ereignishandler für das OnLoad-Ereignis ab oder legt ihn fest. |
| event [OnLoadedData](../../aspose.html.dom/document/onloadeddata/) | Ruft den Ereignishandler für das OnLoadedData-Ereignis ab oder legt ihn fest. |
| event [OnLoadedMetadata](../../aspose.html.dom/document/onloadedmetadata/) | Ruft den Event-Handler für das OnLoadedMetadata-Ereignis ab oder legt ihn fest. |
| event [OnLoadStart](../../aspose.html.dom/document/onloadstart/) | Ruft den Ereignishandler für das OnLoadStart-Ereignis ab oder legt ihn fest. |
| event [OnMouseDown](../../aspose.html.dom/document/onmousedown/) | Ruft den Ereignishandler für das OnMouseDown-Ereignis ab oder legt ihn fest. |
| event [OnMouseEnter](../../aspose.html.dom/document/onmouseenter/) | Ruft Ereignishandler für das OnMouseEnter-Ereignis ab oder legt es fest. |
| event [OnMouseLeave](../../aspose.html.dom/document/onmouseleave/) | Ruft den Ereignishandler für das OnMouseLeave-Ereignis ab oder legt ihn fest. |
| event [OnMouseMove](../../aspose.html.dom/document/onmousemove/) | Ruft Ereignishandler für das OnMouseMove-Ereignis ab oder legt es fest. |
| event [OnMouseOut](../../aspose.html.dom/document/onmouseout/) | Ruft den Event-Handler für das OnMouseOut-Ereignis ab oder legt ihn fest. |
| event [OnMouseOver](../../aspose.html.dom/document/onmouseover/) | Ruft den Ereignishandler für das OnMouseOver-Ereignis ab oder legt ihn fest. |
| event [OnMouseUp](../../aspose.html.dom/document/onmouseup/) | Ruft Ereignishandler für das OnMouseUp-Ereignis ab oder legt es fest. |
| event [OnMouseWheel](../../aspose.html.dom/document/onmousewheel/) | Ruft Ereignishandler für das OnMouseWheel-Ereignis ab oder legt es fest. |
| event [OnPause](../../aspose.html.dom/document/onpause/) | Ruft den Ereignishandler für das OnPause-Ereignis ab oder legt ihn fest. |
| event [OnPlay](../../aspose.html.dom/document/onplay/) | Ruft den Ereignishandler für das OnPlay-Ereignis ab oder legt ihn fest. |
| event [OnPlaying](../../aspose.html.dom/document/onplaying/) | Ruft den Event-Handler für das OnPlaying-Ereignis ab oder legt ihn fest. |
| event [OnProgress](../../aspose.html.dom/document/onprogress/) | Ruft den Ereignishandler für das OnProgress-Ereignis ab oder legt ihn fest. |
| event [OnRateChange](../../aspose.html.dom/document/onratechange/) | Ruft den Ereignishandler für das OnRateChange-Ereignis ab oder legt ihn fest. |
| event [OnReadyStateChange](../../aspose.html.dom/document/onreadystatechange/) | Ruft den Ereignishandler für das OnReadyStateChange-Ereignis ab oder legt ihn fest. |
| event [OnReset](../../aspose.html.dom/document/onreset/) | Ruft den Ereignishandler für das OnReset-Ereignis ab oder legt ihn fest. |
| event [OnResize](../../aspose.html.dom/document/onresize/) | Ruft den Event-Handler für das OnResize-Ereignis ab oder legt ihn fest. |
| event [OnScroll](../../aspose.html.dom/document/onscroll/) | Ruft den Event-Handler für das OnScroll-Ereignis ab oder legt ihn fest. |
| event [OnSeeked](../../aspose.html.dom/document/onseeked/) | Ruft den Ereignishandler für das OnSeeked-Ereignis ab oder legt ihn fest. |
| event [OnSeeking](../../aspose.html.dom/document/onseeking/) | Ruft den Event-Handler für das OnSeeking-Ereignis ab oder legt ihn fest. |
| event [OnSelect](../../aspose.html.dom/document/onselect/) | Ruft den Ereignishandler für das OnSelect-Ereignis ab oder legt ihn fest. |
| event [OnShow](../../aspose.html.dom/document/onshow/) | Ruft den Ereignishandler für das OnShow-Ereignis ab oder legt ihn fest. |
| event [OnStalled](../../aspose.html.dom/document/onstalled/) | Ruft den Event-Handler für das OnStalled-Ereignis ab oder legt ihn fest. |
| event [OnSubmit](../../aspose.html.dom/document/onsubmit/) | Ruft den Event-Handler für das OnSubmit-Ereignis ab oder legt ihn fest. |
| event [OnSuspend](../../aspose.html.dom/document/onsuspend/) | Ruft den Ereignishandler für das OnSuspend-Ereignis ab oder legt ihn fest. |
| event [OnTimeUpdate](../../aspose.html.dom/document/ontimeupdate/) | Ruft Ereignishandler für das OnTimeUpdate-Ereignis ab oder legt es fest. |
| event [OnToggle](../../aspose.html.dom/document/ontoggle/) | Ruft den Event-Handler für das OnToggle-Ereignis ab oder legt ihn fest. |
| event [OnVolumeChange](../../aspose.html.dom/document/onvolumechange/) | Ruft Ereignishandler für das OnVolumeChange-Ereignis ab oder legt es fest. |
| event [OnWaiting](../../aspose.html.dom/document/onwaiting/) | Ruft den Ereignishandler für das OnWaiting-Ereignis ab oder legt ihn fest. |

### Siehe auch

* class [Document](../../aspose.html.dom/document/)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent/)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss/)
* namensraum [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* Montage [Aspose.HTML](../../)


