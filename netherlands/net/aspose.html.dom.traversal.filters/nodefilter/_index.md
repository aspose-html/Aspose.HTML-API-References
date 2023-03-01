---
title: Class NodeFilter
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Traversal.Filters.NodeFilter klas. Filters zijn objecten die nodes kunnen uitfilteren.
type: docs
weight: 2460
url: /nl/net/aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filters zijn objecten die nodes kunnen "uitfilteren".

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## methoden

| Naam | Beschrijving |
| --- | --- |
| abstract [AcceptNode](../../aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Test of een gespecificeerd knooppunt zichtbaar is in de logische weergave van a TreeWalker of NodeIterator. Deze functie wordt aangeroepen door de implementatie van TreeWalker and NodeIterator; het wordt normaal gesproken niet rechtstreeks aangeroepen vanuit gebruikerscode. (Hoewel u dit zou kunnen doen als u het filter same wilt gebruiken om uw eigen toepassingslogica te sturen.) |
| override [GetPlatformType](../../aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Accepteer het knooppunt. Navigatiemethoden gedefinieerd voor NodeIterator of TreeWalker zullen dit knooppunt retourneren. |
| const [FILTER_REJECT](../../aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Verwerp de knoop. Navigatiemethoden gedefinieerd voor NodeIterator of TreeWalker zullen dit knooppunt niet retourneren. Voor TreeWalker worden de kinderen van dit knooppunt ook afgewezen. NodeIterators behandelen dit als een synoniem voor FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Sla dit enkele knooppunt over. Navigatiemethoden gedefinieerd voor NodeIterator of TreeWalker zullen dit knooppunt niet retourneren. Voor zowel NodeIterator als TreeWalker worden de kinderen van dit knooppunt nog steeds beschouwd als . |
| const [SHOW_ALL](../../aspose.html.dom.traversal.filters/nodefilter/show_all/) | Toon alle knooppunten. |
| const [SHOW_ATTRIBUTE](../../aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Toon Attr-knooppunten. Dit is alleen zinvol bij het maken van een iterator of tree-walker met een attribuutknooppunt als root; in dit geval betekent dit dat het attribuutknooppunt op de eerste positie van de iteratie of traversal zal verschijnen. Aangezien attributen nooit kinderen zijn van andere knooppunten, verschijnen ze niet bij het doorlopen van de documentstructuur. |
| const [SHOW_CDATA_SECTION](../../aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Toon CDATAsectie-knooppunten. |
| const [SHOW_COMMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Toon commentaarknooppunten. |
| const [SHOW_DOCUMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document/) | Toon documentknooppunten. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Toon DocumentFragment-knooppunten. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Toon DocumentType-knooppunten. |
| const [SHOW_ELEMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_element/) | Elementknooppunten tonen. |
| const [SHOW_ENTITY](../../aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Entiteitsknooppunten weergeven. Dit is alleen zinvol bij het maken van een iterator of tree-walker met een Entity node als root; in dit geval betekent dit dat het knooppunt Entity op de eerste positie van de traversal verschijnt. Aangezien entiteiten geen deel uitmaken van de documentboom, verschijnen ze niet wanneer de documentboom doorkruist. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Toon EntityReference-knooppunten. |
| const [SHOW_NOTATION](../../aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Toon notatieknooppunten. Dit is alleen zinvol bij het maken van een iterator of tree-walker met een notatieknooppunt als root; in dit geval betekent dit dat het Notatieknooppunt zal verschijnen in de eerste positie van de traversal. Aangezien notaties geen deel uitmaken van de documentboom, verschijnen ze niet bij het doorlopen van de documentboom. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Toon ProcessingInstruction-knooppunten. |
| const [SHOW_TEXT](../../aspose.html.dom.traversal.filters/nodefilter/show_text/) | Toon tekstknooppunten. |

### Zie ook

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [INodeFilter](../../aspose.html.dom.traversal/inodefilter/)
* naamruimte [Aspose.Html.Dom.Traversal.Filters](../../aspose.html.dom.traversal.filters/)
* montage [Aspose.HTML](../../)


