---
title: "NodeFilter-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.traversal.filters.NodeFilter-klass. Filter är objekt som vet hur man filtrerar bort noder"
type: docs

url: /sv/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filter är objekt som vet hur man "filter out" noder.

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Testa om en angiven nod är synlig i den logiska vyn av en TreeWalker eller NodeIterator. Denna funktion kommer att anropas av implementationen av TreeWalker och NodeIterator; den anropas normalt inte direkt från användarkod. (Även om du kan göra det om du vill använda samma filter för att styra din egen applikationslogik.) |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Denna metod används för att hämta ECMAScript‑objekttypen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Acceptera noden. Navigationsmetoder som definierats för NodeIterator eller TreeWalker kommer att returnera denna nod. |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Avvisa noden. Navigationsmetoder som definierats för NodeIterator eller TreeWalker kommer inte att returnera denna nod. För TreeWalker kommer även barnen till denna nod att avvisas. NodeIterators behandlar detta som en synonym för FILTER_SKIP. |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Hoppa över denna enda nod. Navigationsmetoder som definierats för NodeIterator eller TreeWalker kommer inte att returnera denna nod. För både NodeIterator och TreeWalker kommer barnen till denna nod fortfarande att beaktas. |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | Visa alla noder. |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Visa Attr-noder. Detta är endast meningsfullt när man skapar en iterator eller tree-walker med en attributnod som rot; i så fall betyder det att attributnoden kommer att visas i den första positionen av iterationen eller traverseringen. Eftersom attribut aldrig är barn till andra noder, visas de inte vid traversering av dokumentträdet. |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Visa CDATASection-noder. |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Visa kommentarnoder. |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | Visa dokumentnoder. |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Visa DocumentFragment-noder. |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Visa DocumentType-noder. |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | Visa elementnoder. |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Visa Entity-noder. Detta är endast meningsfullt när man skapar en iterator eller tree-walker med en Entity-nod som rot; i så fall betyder det att Entity-noden kommer att visas i den första positionen av traverseringen. Eftersom enheter inte är en del av dokumentträdet, visas de inte vid traversering av dokumentträdet. |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Visa EntityReference-noder. |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Visa Notation-noder. Detta är meningsfullt endast när du skapar en iterator eller tree-walker med en Notation-nod som rot; i detta fall betyder det att Notation-noden kommer att visas i den första positionen i traverseringen. Eftersom notationer inte är en del av dokumentträdet visas de inte när du traverserar dokumentträdet. |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Visa ProcessingInstruction-noder. |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | Visa Text-noder. |

### Se även

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
