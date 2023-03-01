---
title: Aspose.Html.Dom.Traversal
second_title: Aspose.HTML voor .NET API-referentie
description: De Aspose.Html.Dom.Traversalnaamruimte bevat methoden die iterators en treewalkers maken om tussen elementen te navigeren en een knooppunt en zijn kinderen in documentvolgorde te doorkruisen.
type: docs
weight: 170
url: /nl/net/aspose.html.dom.traversal/
---
De **Aspose.Html.Dom.Traversal**naamruimte bevat methoden die iterators en tree-walkers maken om tussen elementen te navigeren en een knooppunt en zijn kinderen in documentvolgorde te doorkruisen.

## Interfaces

| Koppel | Beschrijving |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal bevat methoden die iterators en boomlopers maken om een knooppunt en zijn kinderen in documentvolgorde te doorlopen (diepte eerst, pre-order traversal, wat gelijk is aan de volgorde waarin de starttags voorkomen in de tekstrepresentatie van het document). In DOM's die de Traversal-functie ondersteunen, wordt DocumentTraversal geïmplementeerd door dezelfde objecten die de Document-interface implementeren. |
| [IElementTraversal](./ielementtraversal/) | De ElementTraversal-interface is een set alleen-lezen attributen waarmee een auteur gemakkelijk tussen elementen in een document kan navigeren. Bij conforme implementaties van Element Traversal moeten alle objecten die Element implementeren ook de ElementTraversal-interface implementeren. |
| [INodeFilter](./inodefilter/) | Filters zijn objecten die nodes kunnen "uitfilteren". Als een NodeIterator of TreeWalker een NodeFilter krijgt, wordt het filter toegepast voordat het volgende knooppunt wordt geretourneerd. Als het filter zegt om het knooppunt te accepteren, retourneert de traversal-logica it; anders zoekt traversal naar het volgende knooppunt en doet alsof het -knooppunt dat werd afgewezen er niet was. |
| [INodeIterator](./inodeiterator/) | Iterators worden gebruikt om door een set knooppunten te stappen, bijv. de set knooppunten in een NodeList, de substructuur van het document die wordt beheerd door een bepaald knooppunt, de resultaten van een query of een andere set knooppunten. De set te herhalen knooppunten wordt bepaald door de -implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIterator-implementatie voor documentvolgorde traversal van een documentsubstructuur. Instanties van deze iterators worden gemaakt door DocumentTraversal .createNodeIterator(). aan te roepen |
| [ITraversal](./itraversal/) | Iterators worden gebruikt om door een set knooppunten te stappen, bijv. de set knooppunten in een NodeList, de substructuur van het document die wordt beheerd door een bepaald knooppunt, de resultaten van een query of een andere set knooppunten. De set te herhalen knooppunten wordt bepaald door de -implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIterator-implementatie voor documentvolgorde traversal van een documentsubstructuur. Instanties van deze iterators worden gemaakt door DocumentTraversal .createNodeIterator(). aan te roepen |
| [ITreeWalker](./itreewalker/) | TreeWalker-objecten worden gebruikt om door een documentstructuur of -substructuur te navigeren met behulp van de weergave van het document dat is gedefinieerd door hun whatToShow-vlaggen en filter (indien aanwezig). Elke functie die navigatie uitvoert met behulp van een TreeWalker, ondersteunt automatisch elke weergave gedefinieerd door een TreeWalker. |


