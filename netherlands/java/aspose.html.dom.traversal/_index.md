---
title: "com.aspose.html.dom.traversal"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Het com.aspose.html.dom.traversal‑pakket bevat methoden die iteratoren en tree‑walkers maken om tussen elementen te navigeren en een knooppunt en zijn kinderen in documentvolgorde te doorlopen."
type: docs

url: /nl/java/com.aspose.html.dom.traversal/
---
Het **com.aspose.html.dom.traversal**-pakket bevat methoden die iterators en tree‑walkers creëren om tussen elementen te navigeren en een knooppunt en zijn kinderen in documentvolgorde te doorlopen.

## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal bevat methoden die iteratoren en tree‑walkers maken om een knooppunt en zijn kinderen in documentvolgorde te doorlopen (diepte‑eerste, pre‑order doorloop, wat overeenkomt met de volgorde waarin de start‑tags voorkomen in de tekstrepresentatie van het document). In DOM’s die de Traversal‑functie ondersteunen, zal DocumentTraversal worden geïmplementeerd door dezelfde objecten die de Document‑interface implementeren. |
| [IElementTraversal](./ielementtraversal/) | De ElementTraversal‑interface is een reeks alleen‑lees‑attributen die een auteur in staat stellen gemakkelijk tussen elementen in een document te navigeren. In conforme implementaties van Element Traversal moeten alle objecten die Element implementeren ook de ElementTraversal‑interface implementeren. |
| [INodeFilter](./inodefilter/) | Filters zijn objecten die weten hoe ze knooppunten moeten \"filteren\". Als een NodeIterator of TreeWalker een NodeFilter krijgt, past hij het filter toe voordat hij het volgende knooppunt retourneert. Als het filter aangeeft het knooppunt te accepteren, retourneert de doorlooplogica het; anders zoekt de doorloop naar het volgende knooppunt en doet alsof het afgewezen knooppunt niet bestond. |
| [INodeIterator](./inodeiterator/) | Iterators worden gebruikt om door een verzameling knooppunten te stappen, bijv. de verzameling knooppunten in een NodeList, de document‑subboom die wordt beheerd door een specifieke Node, de resultaten van een query, of elke andere verzameling knooppunten. De te itereren verzameling wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIterator‑implementatie voor document‑volgorde doorloop van een document‑subboom. Instanties van deze iterators worden gecreëerd door DocumentTraversal.createNodeIterator() aan te roepen. |
| [ITraversal](./itraversal/) | Iterators worden gebruikt om door een verzameling knooppunten te stappen, bijv. de verzameling knooppunten in een NodeList, de document‑subboom die wordt beheerd door een specifieke Node, de resultaten van een query, of elke andere verzameling knooppunten. De te itereren verzameling wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIterator‑implementatie voor document‑volgorde doorloop van een document‑subboom. Instanties van deze iterators worden gecreëerd door DocumentTraversal.createNodeIterator() aan te roepen. |
| [ITreeWalker](./itreewalker/) | TreeWalker‑objecten worden gebruikt om door een documentboom of subboom te navigeren met behulp van de weergave van het document die wordt gedefinieerd door hun whatToShow‑vlaggen en filter (indien aanwezig). Elke functie die navigatie uitvoert met een TreeWalker ondersteunt automatisch elke weergave die door een TreeWalker wordt gedefinieerd. |
