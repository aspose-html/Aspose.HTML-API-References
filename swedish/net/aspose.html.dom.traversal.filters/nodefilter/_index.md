---
title: Class NodeFilter
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Traversal.Filters.NodeFilter klass. Filter är objekt som vet hur man filtrerar bort noder.
type: docs
weight: 2460
url: /sv/net/aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filter är objekt som vet hur man "filtrerar bort" noder.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| abstract [AcceptNode](../../aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Testa om en angiven nod är synlig i den logiska vyn av a TreeWalker eller NodeIterator. Denna funktion kommer att anropas av implementeringen av TreeWalker och NodeIterator; den anropas normalt inte direkt from användarkod. (Även om du kan göra det om du vill använda same -filtret för att styra din egen applikationslogik.) |
| override [GetPlatformType](../../aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Acceptera noden. Navigationsmetoder definierade för NodeIterator eller TreeWalker kommer att returnera denna nod. |
| const [FILTER_REJECT](../../aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Avvisa noden. Navigeringsmetoder definierade för NodeIterator eller TreeWalker kommer inte att returnera denna nod. För TreeWalker kommer även underordnade till denna nod att avvisas. NodeIterators behandlar detta som en synonym för FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Hoppa över denna enda nod. Navigeringsmetoder definierade för NodeIterator eller TreeWalker kommer inte att returnera denna nod. För både NodeIterator och TreeWalker kommer barnen till denna nod fortfarande att beaktas. |
| const [SHOW_ALL](../../aspose.html.dom.traversal.filters/nodefilter/show_all/) | Visa alla noder. |
| const [SHOW_ATTRIBUTE](../../aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Visa Attr-noder. Detta är endast meningsfullt när man skapar en iterator eller trädvandrare med en attributnod som sin rot; i detta fall betyder det att attributnoden kommer att visas i den första positionen av iterationen eller genomgången. Eftersom attribut aldrig är underordnade av andra noder, visas de inte när de går över dokumentträdet. |
| const [SHOW_CDATA_SECTION](../../aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Visa CDATASection-noder. |
| const [SHOW_COMMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Visa kommentarsnoder. |
| const [SHOW_DOCUMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document/) | Visa dokumentnoder. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Visa DocumentFragment-noder. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Visa DocumentType-noder. |
| const [SHOW_ELEMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_element/) | Visa elementnoder. |
| const [SHOW_ENTITY](../../aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Visa enhetsnoder. Detta är endast meningsfullt när du skapar en iterator eller trädvandrare med en Entity-nod som dess -rot; i det här fallet betyder det att Entity -noden kommer att visas i den första positionen för genomgången. Eftersom entiteter inte är en del av dokumentträdet, visas de inte när går över dokumentträdet. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Visa enhetsreferensnoder. |
| const [SHOW_NOTATION](../../aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Visa notationsnoder. Detta är endast meningsfullt när man skapar en iterator eller trädvandrare med en notationsnod som sin rot; i det här fallet betyder det att noden kommer att visas i den första positionen för -traversalen. Eftersom noteringar inte är en del av dokumentträdet, visas de inte när du går över dokumentträdet. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Visa bearbetningsinstruktionsnoder. |
| const [SHOW_TEXT](../../aspose.html.dom.traversal.filters/nodefilter/show_text/) | Visa textnoder. |

### Se även

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [INodeFilter](../../aspose.html.dom.traversal/inodefilter/)
* namnutrymme [Aspose.Html.Dom.Traversal.Filters](../../aspose.html.dom.traversal.filters/)
* hopsättning [Aspose.HTML](../../)


