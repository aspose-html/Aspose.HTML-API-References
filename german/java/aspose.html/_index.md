---
title: "Aspose.Html"
second_title: "Aspose.HTML für Java API-Referenz"
description: "The Aspose.Html package contains classes and methods to manipulate HTML documentsaspose.html/htmldocument/ whether simple or complex and on the fly. Aspose.HTML for Java allows developers to Insert Remove Replace HTML nodes extract CSS style information Navigate through HTML documentaspose.html/htmldocument/ either by NodeIteratoraspose.html.dom.traversal/inodeiterator/ TreeWalkeraspose.html.dom.traversal/itreewalker/ that are provided by Traversal Specifications XPath or CSS selector queries. It also offers the scripting which allows to manipulate HTML DOM via JavaScript. As well as HTML this API also provides the capabilities to load EPUB and MHTML. Aspose APIs are famous for their inter file format conversion features and this API also provides the capabilities to load HTML file and render the output in PDF XPS and raster image formats including JPEG PNG BMP and TIFF"
type: docs

url: /de/java/com.aspose.html/
---
Das Aspose.Html-Paket enthält Klassen und Methoden zur Manipulation von [`HTML-Dokumenten`](aspose.html/htmldocument/), egal ob einfach oder komplex und in Echtzeit. Aspose.HTML für Java ermöglicht Entwicklern das Einfügen, Entfernen und Ersetzen von HTML‑Knoten, das Extrahieren von CSS‑Stilinformationen, das Navigieren durch [`HTML-Dokument`](aspose.html/htmldocument/) entweder mittels [`NodeIterator`](aspose.html.dom.traversal/inodeiterator/), [`TreeWalker`](aspose.html.dom.traversal/itreewalker/), die durch Traversal‑Spezifikationen bereitgestellt werden, XPath‑ oder CSS‑Selektor‑Abfragen. Es bietet zudem das Scripting, das die Manipulation des HTML‑DOM über JavaScript erlaubt. Neben HTML stellt diese API auch die Möglichkeit bereit, EPUB und MHTML zu laden. Aspose‑APIs sind für ihre Funktionen zur Konvertierung zwischen Dateiformaten bekannt, und diese API ermöglicht ebenfalls das Laden von HTML‑Dateien und das Rendern der Ausgabe in PDF, XPS und Raster‑Bildformate einschließlich JPEG, PNG, BMP und TIFF.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [ArrayBuffer](./arraybuffer/) | The ArrayBuffer object is used to represent a generic, fixed-length raw binary data buffer. |
| [Configuration](./configuration/) | Represents the configuration context object that is used to set up the environment settings for the application. Managing configuration you can override document style applying a custom user stylesheet, or handle any web requests from the application as well as to configure scripts policy. Details are in [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/). |
| [Float32Array](./float32array/) | Represents an array of 32-bit floating point numbers (corresponding to the C float data type) in the platform byte order. |
| [Float64Array](./float64array/) | Represents an array of 64-bit floating point numbers (corresponding to the C float data type) in the platform byte order. |
| [FontsSettings](./fontssettings/) | Represents fonts handling settings. |
| [HTMLAddressElement](./htmladdresselement/) | The address element. See the ADDRESS element definition in HTML 4.01. |
| [HTMLAnchorElement](./htmlanchorelement/) | The anchor element. See the A element definition in HTML 4.01. |
| [HTMLAppletElement](./htmlappletelement/) | An embedded Java applet. See the APPLET element definition in HTML 4.01. This element is deprecated in HTML 4.01. |
| [HTMLAreaElement](./htmlareaelement/) | Client-side image map area definition. See the AREA element definition in HTML 4.01. |
| [HTMLBaseElement](./htmlbaseelement/) | Document base URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)]. See the BASE element definition in HTML 4.01. |
| [HTMLBaseFontElement](./htmlbasefontelement/) | Base font. See the BASEFONT element definition in HTML 4.01. This element is deprecated in HTML 4.01. |
| [HTMLBodyElement](./htmlbodyelement/) | The HTML document body. This element is always present in the DOM API, even if the tags are not present in the source document. See the BODY element definition in HTML 4.01. |
| [HTMLBRElement](./htmlbrelement/) | Force a line break. See the BR element definition in HTML 4.01. |
| [HTMLButtonElement](./htmlbuttonelement/) | Schaltfläche. Siehe die Definition des BUTTON-Elements in HTML 4.01. |
| [HTMLCanvasElement](./htmlcanvaselement/) | Das HTMLCanvasElement-Interface stellt Eigenschaften und Methoden zum Manipulieren des Layouts und der Darstellung von Canvas-Elementen bereit. Das HTMLCanvasElement-Interface erbt außerdem die Eigenschaften und Methoden des HTMLElement-Interfaces. |
| [HTMLDataListElement](./htmldatalistelement/) | Das datalist-Element stellt eine Menge von option-Elementen dar, die vordefinierte Optionen für andere Steuerelemente repräsentieren. Siehe auch die [HTML 5.2 W3C Recommendation](https://www.w3.org/TR/html52/sec-forms.html#elementdef-datalist). |
| [HTMLDirectoryElement](./htmldirectoryelement/) | Verzeichnisliste. Siehe die Definition des DIR-Elements in HTML 4.01. Dieses Element ist in HTML 4.01 veraltet. |
| [HTMLDivElement](./htmldivelement/) | Generischer Blockcontainer. Siehe die Definition des DIV-Elements in HTML 4.01. |
| [HTMLDListElement](./htmldlistelement/) | Definitionsliste. Siehe die Definition des DL-Elements in HTML 4.01. |
| [HTMLDocument](./htmldocument/) | Stellt ein HTML-Dokument dar. Alle HTML-Objekte der obersten Ebene werden zu diesem Objekt hinzugefügt. Diese Klasse repräsentiert die HTML-Seite so, wie wir sie im Browser sehen. Alle Formulare, Tabellen, Skripte, … werden über die Schnittstellen dieser Klasse zur HTML-Seite hinzugefügt. [HTMLDocument](https://dom.spec.whatwg.org/#ref-for-dom-domimplementation-createhtmldocument) ist die HTML-Implementierung des allgemeinsten [Document](https://dom.spec.whatwg.org/#document)-Interfaces und beide bilden den Kern‑ bzw. Ausgangspunkt des [DOM](https://dom.spec.whatwg.org/) – Document Object Model. Diese Konzepte entsprechen vollständig den offiziellen Grundlagen bzw. Standards der Webentwicklung. Für Webentwicklungszwecke kann man HTMLDocument im Allgemeinen als Alias für Document betrachten, auf dem HTMLDocument basiert. |
| [HTMLElement](./htmlelement/) | Alle HTML-Element-Interfaces erben von dieser Klasse. Elemente, die nur die Kernattribute von HTML bereitstellen, werden durch das Basis-Interface `HTMLElement` repräsentiert. Diese Elemente sind wie folgt: special: SUB, SUP, SPAN, BDOfont: TT, I, B, U, S, STRIKE, BIG, SMALL phrase: EM, STRONG, DFN, CODE, SAMP, KBD, VAR, CITE, ACRONYM, ABBRlist: DD, DTNOFRAMES, NOSCRIPTADDRESS, CENTER. Das `style`-Attribut eines HTML-Elements ist über das Interface `ElementCSSInlineStyle` zugänglich, das im CSS‑Modul [[DOM Level 2 Style Sheets and CSS](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113)] definiert ist. |
| [HTMLFieldSetElement](./htmlfieldsetelement/) | Organisiert Formularelemente in logische Gruppen. Siehe die Definition des FIELDSET-Elements in HTML 4.01. |
| [HTMLFontElement](./htmlfontelement/) | Lokale Schriftänderung. Siehe die Definition des FONT-Elements in HTML 4.01. Dieses Element ist in HTML 4.01 veraltet. |
| [HTMLFormElement](./htmlformelement/) | Das `FORM`-Element umfasst ein Verhalten, das einer Sammlung und einem Element ähnelt. Es bietet direkten Zugriff auf die enthaltenen Formularelemente sowie auf die Attribute des Formularelements. Siehe die Definition des FORM-Elements in HTML 4.01. |
| [HTMLFrameElement](./htmlframeelement/) | Erstelle einen Frame. Siehe die Definition des FRAME-Elements in HTML 4.01. |
| [HTMLFrameSetElement](./htmlframesetelement/) | Erstelle ein Raster von Frames. Siehe die Definition des FRAMESET-Elements in HTML 4.01. |
| [HTMLHeadElement](./htmlheadelement/) | Informationen zum Dokumentkopf. Siehe die Definition des HEAD-Elements in HTML 4.01. |
| [HTMLHeadingElement](./htmlheadingelement/) | Für die Elemente `H1` bis `H6`. Siehe die Definition des H1-Elements in HTML 4.01. |
| [HTMLHRElement](./htmlhrelement/) | Erstelle eine horizontale Linie. Siehe die Definition des HR-Elements in HTML 4.01. |
| [HTMLHtmlElement](./htmlhtmlelement/) | Wurzel eines HTML-Dokuments. Siehe die Definition des HTML-Elements in HTML 4.01. |
| [HTMLIFrameElement](./htmliframeelement/) | Inline-Unterfenster. Siehe die Definition des IFRAME-Elements in HTML 4.01. |
| [HTMLImageElement](./htmlimageelement/) | Eingebettetes Bild. Siehe die Definition des IMG-Elements in HTML 4.01. |
| [HTMLInputElement](./htmlinputelement/) | Formularsteuerelement. Je nach Umgebung, in der die Seite angezeigt wird, kann die Eigenschaft value für den Dateiupload‑Eingabetyp schreibgeschützt sein. Beim Eingabetyp "password" kann der tatsächlich zurückgegebene Wert maskiert werden, um unbefugte Nutzung zu verhindern. Siehe die Definition des INPUT-Elements in [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)]. Siehe außerdem die [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109). |
| [HTMLIsIndexElement](./htmlisindexelement/) | Dieses Element wird für einzeilige Texteingabe verwendet. Siehe die Definition des ISINDEX-Elements in HTML 4.01. Dieses Element ist in HTML 4.01 veraltet. |
| [HTMLLabelElement](./htmllabelelement/) | Beschriftungstext eines Formularfeldes. Siehe die Definition des LABEL-Elements in HTML 4.01. |
| [HTMLLegendElement](./htmllegendelement/) | Stellt eine Beschriftung für eine `FIELDSET`‑Gruppe bereit. Siehe die Definition des LEGEND-Elements in HTML 4.01. |
| [HTMLLIElement](./htmllielement/) | Listenelement. Siehe die Definition des LI-Elements in HTML 4.01. |
| [HTMLLinkElement](./htmllinkelement/) | Das `LINK`-Element gibt einen Link zu einer externen Ressource an und definiert die Beziehung dieses Dokuments zu jener Ressource (oder umgekehrt). Siehe die Definition des LINK-Elements in HTML 4.01 (siehe auch das Interface `LinkStyle` im StyleSheet‑Modul [[DOM Level 2 Style Sheets and CSS](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113)]). |
| [HTMLMapElement](./htmlmapelement/) | Clientseitige Bildkarte. Siehe die MAP-Elementdefinition in HTML 4.01. |
| [HTMLMenuElement](./htmlmenuelement/) | Menüliste. Siehe die MENU-Elementdefinition in HTML 4.01. Dieses Element ist in HTML 4.01 veraltet. |
| [HTMLMetaElement](./htmlmetaelement/) | Dies enthält generische Metainformationen über das Dokument. Siehe die META-Elementdefinition in HTML 4.01. |
| [HTMLModElement](./htmlmodelement/) | Hinweis auf Änderungen an einem Teil eines Dokuments. Siehe die INS- und DEL-Elementdefinitionen in HTML 4.01. |
| [HTMLNoScriptElement](./htmlnoscriptelement/) | Skriptanweisungen. Siehe die NOSCRIPT-Elementdefinition in HTML 4.01. |
| [HTMLObjectElement](./htmlobjectelement/) | Generisches eingebettetes Objekt. Grundsätzlich sind alle Eigenschaften des object-Elements les- und schreibbar, aber in einigen Umgebungen können einige Eigenschaften nach der Instanziierung des zugrunde liegenden Objekts schreibgeschützt sein. Siehe die OBJECT-Elementdefinition in [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)]. |
| [HTMLOListElement](./htmlolistelement/) | Geordnete Liste. Siehe die OL-Elementdefinition in HTML 4.01. |
| [HTMLOptGroupElement](./htmloptgroupelement/) | Optionen logisch gruppieren. Siehe die OPTGROUP-Elementdefinition in HTML 4.01. |
| [HTMLOptionElement](./htmloptionelement/) | Eine auswählbare Option. Siehe die OPTION-Elementdefinition in HTML 4.01. |
| [HTMLParagraphElement](./htmlparagraphelement/) | Absätze. Siehe die P-Elementdefinition in HTML 4.01. |
| [HTMLParamElement](./htmlparamelement/) | Parameter, die an das `OBJECT`-Element übergeben werden. Siehe die PARAM-Elementdefinition in HTML 4.01. |
| [HTMLPreElement](./htmlpreelement/) | Vorformatierter Text. Siehe die PRE-Elementdefinition in HTML 4.01. |
| [HTMLQuoteElement](./htmlquoteelement/) | Für die `Q`- und `BLOCKQUOTE`-Elemente. Siehe die Q-Elementdefinition in HTML 4.01. |
| [HTMLScriptElement](./htmlscriptelement/) | Skriptanweisungen. Siehe die SCRIPT-Elementdefinition in HTML 4.01. |
| [HTMLSelectElement](./htmlselectelement/) | Das select-Element ermöglicht die Auswahl einer Option. Die enthaltenen Optionen können direkt über das select-Element als Sammlung zugegriffen werden. Siehe die SELECT-Elementdefinition in HTML 4.01. |
| [HTMLStyleElement](./htmlstyleelement/) | Stilinformationen. Siehe die STYLE-Elementdefinition in HTML 4.01, das CSS-Modul [[DOM Level 2 Style Sheets and CSS](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113)] und die `LinkStyle`-Schnittstelle im StyleSheets-Modul [[DOM Level 2 Style Sheets and CSS](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113)]. |
| [HTMLTableCaptionElement](./htmltablecaptionelement/) | Tabellenbeschriftung. Siehe die CAPTION-Elementdefinition in HTML 4.01. |
| [HTMLTableCellElement](./htmltablecellelement/) | Das Objekt, das die `TH`- und `TD`-Elemente repräsentiert. Siehe die TD-Elementdefinition in HTML 4.01. |
| [HTMLTableColElement](./htmltablecolelement/) | Gruppiert die `COL`- und `COLGROUP`-Elemente neu. Siehe die COL-Elementdefinition in HTML 4.01. |
| [HTMLTableElement](./htmltableelement/) | Die create*- und delete*-Methoden der Tabelle ermöglichen es Autoren, Tabellen zu erstellen und zu ändern. [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)] legt fest, dass von jedem der `CAPTION`-, `THEAD`- und `TFOOT`-Elemente nur eines in einer Tabelle existieren darf. Daher wird, wenn eines bereits existiert und die Methode createTHead() oder createTFoot() aufgerufen wird, das bereits vorhandene THead- bzw. TFoot-Element zurückgegeben. Siehe die TABLE-Elementdefinition in HTML 4.01. |
| [HTMLTableRowElement](./htmltablerowelement/) | Eine Zeile in einer Tabelle. Siehe die TR-Elementdefinition in HTML 4.01. |
| [HTMLTableSectionElement](./htmltablesectionelement/) | Die `THEAD`-, `TFOOT`- und `TBODY`-Elemente. |
| [HTMLTemplateElement](./htmltemplateelement/) | Das template-Element |
| [HTMLTextAreaElement](./htmltextareaelement/) | Mehrzeiliges Textfeld. Siehe die TEXTAREA-Elementdefinition in HTML 4.01. |
| [HTMLTitleElement](./htmltitleelement/) | Das title-Element. Siehe die TITLE-Elementdefinition in HTML 4.01. |
| [HTMLUListElement](./htmlulistelement/) | Ungeordnete Liste. Siehe die UL-Elementdefinition in HTML 4.01. |
| [HTMLUnknownElement](./htmlunknownelement/) | Das unbekannte HTML-Element. |
| [Int16Array](./int16array/) | Stellt ein Array von Zweierkomplement‑16‑Bit‑vorzeichenbehafteten Ganzzahlen im Byte‑Ordner der Plattform dar. |
| [Int32Array](./int32array/) | Stellt ein Array von Zweierkomplement‑32‑Bit‑vorzeichenbehafteten Ganzzahlen im Byte‑Ordner der Plattform dar. |
| [Int8Array](./int8array/) | Stellt ein Array von Zweierkomplement‑8‑Bit‑vorzeichenbehafteten Ganzzahlen dar. |
| [License](./license/) | Stellt Methoden bereit, um die Komponente zu lizenzieren. |
| [Metered](./metered/) | Stellt Methoden bereit, um den metered key zu setzen. |
| [MimeType](./mimetype/) | Stellt Internet-Medientypen dar. |
| [PlatformException](./platformexception/) | Stellt die Basisklasse für alle Ausnahmen dar, die während der Anwendungs­ausführung auftreten können. |
| [TypedArray](./typedarray/) | TypedArray‑Objekte präsentieren eine array‑ähnliche Ansicht eines zugrunde liegenden binären Datenpuffers. |
| [TypedArray&lt;T&gt;](./typedarray-1/) | TypedArray‑Objekte präsentieren eine array‑ähnliche Ansicht eines zugrunde liegenden binären Datenpuffers. |
| [Uint16Array](./uint16array/) | Stellt ein Array von Zweierkomplement‑16‑Bit‑vorzeichenlosen Ganzzahlen im Byte‑Ordner der Plattform dar. |
| [Uint32Array](./uint32array/) | Stellt ein Array von Zweierkomplement‑32‑Bit‑vorzeichenlosen Ganzzahlen im Byte‑Ordner der Plattform dar. |
| [Uint8Array](./uint8array/) | Stellt ein Array von Zweierkomplement‑8‑Bit‑vorzeichenlosen Ganzzahlen dar. |
| [Uint8ClampedArray](./uint8clampedarray/) | Stellt ein Array von 8‑Bit‑vorzeichenlosen Ganzzahlen dar, die auf 0‑255 begrenzt sind; wenn Sie einen Wert außerhalb des Bereichs [0,255] angeben, wird stattdessen 0 oder 255 gesetzt; |
| [Url](./url/) | Stellt eine Objekt­darstellung eines universellen Identifikators (URL) bereit. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IConfigurationBuilder](./iconfigurationbuilder/) | Stellt einen Builder für Konfigurationsobjekte dar. |
| [IDocumentFragmentElement](./idocumentfragmentelement/) | Stellt die gemeinsame Schnittstelle für alle Document‑Fragment‑Elemente dar. |
| [IHTMLFormElement](./ihtmlformelement/) | Stellt eine Basisschnittstelle dar, die von HTML‑Formular‑Elementen implementiert werden sollte. |
| [IHTMLOptionsCollection](./ihtmloptionscollection/) | Ein `HTMLOptionsCollection` ist eine Liste von Knoten, die HTML‑Option‑Elemente repräsentieren. Auf einen einzelnen Knoten kann entweder über den ordinalen Index oder über die `name`‑ bzw. `id`‑Attribute des Knotens zugegriffen werden. Sammlungen im HTML‑DOM werden als live angenommen, d. h. sie werden automatisch aktualisiert, wenn das zugrunde liegende Dokument geändert wird. |
| [IUrlSearchParams](./iurlsearchparams/) | Stellt Methoden bereit, um mit dem Abfrage‑String von URLs zu arbeiten. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [Sandbox](./sandbox/) | Ein Sandbox‑Flag‑Set ist eine Menge von null oder mehr der folgenden Flags, die verwendet werden, um die Fähigkeiten potenziell nicht vertrauenswürdiger Ressourcen einzuschränken. |
