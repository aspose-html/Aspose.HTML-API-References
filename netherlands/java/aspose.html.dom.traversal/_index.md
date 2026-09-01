---
title: "com.aspose.html.dom.traversal"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Het com.aspose.html.dom.traversal-pakket bevat methoden die iterators en tree-walkers maken om tussen elementen te navigeren en een knoop en zijn kinderen te doorlopen in documentvolgorde."
type: docs

url: /nl/java/com.aspose.html.dom.traversal/
---
Het **com.aspose.html.dom.traversal**-pakket bevat methoden die iterators en tree‑walkers creëren om tussen elementen te navigeren en een knooppunt en zijn kinderen in documentvolgorde te doorlopen.

## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal bevat methoden die iterators en tree-walkers maken om een knoop en zijn kinderen te doorlopen in documentvolgorde (diepte‑eerste, pre‑order traversie, wat gelijk is aan de volgorde waarin de start‑tags voorkomen in de tekstrepresentatie van het document). In DOM's die de Traversal‑functie ondersteunen, zal DocumentTraversal worden geïmplementeerd door dezelfde objecten die de Document‑interface implementeren. |
| [IElementTraversal](./ielementtraversal/) | De ElementTraversal‑interface is een set van alleen‑lees attributen die een auteur in staat stelt gemakkelijk tussen elementen in een document te navigeren. In conforme implementaties van Element Traversal moeten alle objecten die Element implementeren ook de ElementTraversal‑interface implementeren. |
| [INodeFilter](./inodefilter/) | Filters zijn objecten die weten hoe ze knopen moeten "filteren". Als een NodeIterator of TreeWalker een NodeFilter krijgt, past hij het filter toe voordat hij de volgende knoop retourneert. Als het filter aangeeft de knoop te accepteren, retourneert de traversielogica deze; anders zoekt de traversie naar de volgende knoop en doet alsof de afgewezen knoop niet bestond. |
| [INodeIterator](./inodeiterator/) | Iterators worden gebruikt om door een verzameling knopen te stappen, bv. de verzameling knopen in een NodeList, de document‑subboom beheerd door een specifieke Node, de resultaten van een query, of elke andere verzameling knopen. De te itereren verzameling knopen wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert één NodeIterator‑implementatie voor documentvolgorde‑traversie van een document‑subboom. Instanties van deze iterators worden gecreëerd door DocumentTraversal .createNodeIterator() aan te roepen. |
| [ITraversal](./itraversal/) | Iterators worden gebruikt om door een verzameling knopen te stappen, bv. de verzameling knopen in een NodeList, de document‑subboom beheerd door een specifieke Node, de resultaten van een query, of elke andere verzameling knopen. De te itereren verzameling knopen wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert één NodeIterator‑implementatie voor documentvolgorde‑traversie van een document‑subboom. Instanties van deze iterators worden gecreëerd door DocumentTraversal .createNodeIterator() aan te roepen. |
| [ITreeWalker](./itreewalker/) | TreeWalker‑objecten worden gebruikt om door een documentboom of subboom te navigeren met behulp van de weergave van het document gedefinieerd door hun whatToShow‑vlaggen en filter (indien aanwezig). Elke functie die navigatie uitvoert met een TreeWalker zal automatisch elke weergave die door een TreeWalker is gedefinieerd ondersteunen. |
