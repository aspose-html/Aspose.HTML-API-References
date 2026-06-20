---
title: "NodeFilter Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.traversal.filters.NodeFilter Klasse. Filter sind Objekte, die wissen, wie man Knoten herausfiltert"
type: docs

url: /de/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filter sind Objekte, die wissen, wie man Knoten "herausfiltert".

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Prüft, ob ein bestimmter Knoten in der logischen Ansicht eines TreeWalker oder NodeIterator sichtbar ist. Diese Funktion wird von der Implementierung von TreeWalker und NodeIterator aufgerufen; sie wird normalerweise nicht direkt aus dem Benutzercode heraus aufgerufen. (Obwohl Sie dies tun könnten, wenn Sie denselben Filter verwenden möchten, um Ihre Anwendungslogik zu steuern.) |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript‑Objekttyp abzurufen. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Akzeptiere den Knoten. Navigationsmethoden, die für NodeIterator oder TreeWalker definiert sind, geben diesen Knoten zurück. |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Verwerfe den Knoten. Navigationsmethoden, die für NodeIterator oder TreeWalker definiert sind, geben diesen Knoten nicht zurück. Für TreeWalker werden auch die Kinder dieses Knotens verworfen. NodeIterators behandeln dies als Synonym für FILTER_SKIP. |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Überspringe diesen einzelnen Knoten. Navigationsmethoden, die für NodeIterator oder TreeWalker definiert sind, geben diesen Knoten nicht zurück. Für sowohl NodeIterator als auch TreeWalker werden die Kinder dieses Knotens weiterhin berücksichtigt. |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | Alle Knoten anzeigen. |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Attr-Knoten anzeigen. Dies ist nur sinnvoll, wenn ein Iterator oder Tree-Walker mit einem Attributknoten als Wurzel erstellt wird; in diesem Fall bedeutet dies, dass der Attributknoten an der ersten Position der Iteration oder Traversierung erscheint. Da Attribute niemals Kinder anderer Knoten sind, erscheinen sie nicht beim Durchlaufen des Dokumentbaums. |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | CDATASection-Knoten anzeigen. |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Kommentar-Knoten anzeigen. |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | Dokument-Knoten anzeigen. |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | DocumentFragment-Knoten anzeigen. |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | DocumentType-Knoten anzeigen. |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | Element-Knoten anzeigen. |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Entity-Knoten anzeigen. Dies ist nur sinnvoll, wenn ein Iterator oder Tree-Walker mit einem Entity-Knoten als Wurzel erstellt wird; in diesem Fall bedeutet dies, dass der Entity-Knoten an der ersten Position der Traversierung erscheint. Da Entitäten nicht Teil des Dokumentbaums sind, erscheinen sie nicht beim Durchlaufen des Dokumentbaums. |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | EntityReference-Knoten anzeigen. |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Notation-Knoten anzeigen. Dies ist nur sinnvoll, wenn ein Iterator oder Tree-Walker mit einem Notation-Knoten als Wurzel erstellt wird; in diesem Fall bedeutet dies, dass der Notation-Knoten an der ersten Position der Traversierung erscheint. Da Notationen kein Teil des Dokumentbaums sind, erscheinen sie nicht beim Durchlaufen des Dokumentbaums. |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | ProcessingInstruction-Knoten anzeigen. |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | Text-Knoten anzeigen. |

### Siehe auch

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
