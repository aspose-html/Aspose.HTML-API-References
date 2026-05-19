---
title: "NodeFilter Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.traversal.filters.NodeFilter klasse. Filters zijn objecten die weten hoe ze knooppunten moeten filteren"
type: docs

url: /nl/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filters zijn objecten die weten hoe ze knooppunten "filteren".

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Test of een opgegeven knooppunt zichtbaar is in de logische weergave van een TreeWalker of NodeIterator. Deze functie wordt aangeroepen door de implementatie van TreeWalker en NodeIterator; hij wordt normaal niet direct vanuit gebruikerscode aangeroepen. (Hoewel je dit wel kunt doen als je hetzelfde filter wilt gebruiken om je eigen toepassingslogica te sturen.) |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Accepteer het knooppunt. Navigatiemethoden die zijn gedefinieerd voor NodeIterator of TreeWalker zullen dit knooppunt retourneren. |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Weiger het knooppunt. Navigatiemethoden die zijn gedefinieerd voor NodeIterator of TreeWalker zullen dit knooppunt niet retourneren. Voor TreeWalker worden de kinderen van dit knooppunt ook geweigerd. NodeIterators beschouwen dit als een synoniem voor FILTER_SKIP. |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Sla dit enkele knooppunt over. Navigatiemethoden die zijn gedefinieerd voor NodeIterator of TreeWalker zullen dit knooppunt niet retourneren. Voor zowel NodeIterator als TreeWalker worden de kinderen van dit knooppunt nog steeds in aanmerking genomen. |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | Toon alle knooppunten. |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Toon Attr-knooppunten. Dit is alleen zinvol bij het maken van een iterator of tree-walker met een attribuutknooppunt als root; in dit geval betekent dit dat het attribuutknooppunt op de eerste positie van de iteratie of traversie verschijnt. Aangezien attributen nooit kinderen van andere knooppunten zijn, verschijnen ze niet bij het traverseren van de documentboom. |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Toon CDATASection-knooppunten. |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Toon Comment-knooppunten. |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | Toon Document-knooppunten. |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Toon DocumentFragment-knooppunten. |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Toon DocumentType-knooppunten. |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | Toon Element-knooppunten. |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Toon Entity-knooppunten. Dit is alleen zinvol bij het maken van een iterator of tree-walker met een Entity-knooppunt als root; in dit geval betekent dit dat het Entity-knooppunt op de eerste positie van de traversie verschijnt. Aangezien entiteiten geen deel uitmaken van de documentboom, verschijnen ze niet bij het traverseren van de documentboom. |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Toon EntityReference-knooppunten. |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Toon Notation-knooppunten. Dit is alleen zinvol bij het maken van een iterator of tree-walker met een Notation-knooppunt als wortel; in dit geval betekent dit dat het Notation-knooppunt op de eerste positie van de traversatie verschijnt. Aangezien notaties geen deel uitmaken van de documentboom, verschijnen ze niet tijdens het doorlopen van de documentboom. |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Toon ProcessingInstruction-knooppunten. |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | Toon Tekst-knooppunten. |

### Zie ook

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
