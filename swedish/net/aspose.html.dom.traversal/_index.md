---
title: Aspose.Html.Dom.Traversal
second_title: Aspose.HTML för .NET API Referens
description: Den Aspose.Html.Dom.Traversalnamnrymden innehåller metoder som skapar iteratorer och trädvandrare för att navigera mellan element och korsar en nod och dess underordnade i dokumentordning.
type: docs
weight: 170
url: /sv/net/aspose.html.dom.traversal/
---
Den **Aspose.Html.Dom.Traversal**namnrymden innehåller metoder som skapar iteratorer och trädvandrare för att navigera mellan element och korsar en nod och dess underordnade i dokumentordning.

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal innehåller metoder som skapar iteratorer och trädvandrare för att korsa en nod och dess underordnade i dokumentordning (djup first, pre-order traversal, vilket motsvarar den ordning i vilken starttaggarna förekommer i textrepresentationen av dokumentet). I DOM:er som stöder genomgångsfunktionen, kommer DocumentTraversal att implementeras av samma objekt som implementerar dokumentgränssnittet. |
| [IElementTraversal](./ielementtraversal/) | ElementTraversal-gränssnittet är en uppsättning skrivskyddade attribut som gör att en författare enkelt kan navigera mellan element i ett dokument. I överensstämmande implementeringar av Element Traversal måste alla objekt som implementerar Element också implementera ElementTraversal-gränssnittet. |
| [INodeFilter](./inodefilter/) | Filter är objekt som vet hur man "filtrerar bort" noder. Om en NodeIterator eller TreeWalker ges ett NodeFilter, tillämpar den filtret innan den returnerar nästa nod. Om filtret säger att man ska acceptera noden, returnerar övergångslogiken it; annars letar traversal efter nästa nod och låtsas att -noden som avvisades inte fanns där. |
| [INodeIterator](./inodeiterator/) | Iteratorer används för att stega igenom en uppsättning noder, t.ex. uppsättningen av noder i en NodeList, dokumentunderträdet som styrs av en viss Nod, resultaten av en fråga eller någon annan uppsättning av noder. Uppsättningen av noder som ska itereras bestäms av -implementeringen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator-implementering för dokument-order genomgång av ett dokumentunderträd. Förekomster av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Iteratorer används för att stega igenom en uppsättning noder, t.ex. uppsättningen av noder i en NodeList, dokumentunderträdet som styrs av en viss Nod, resultaten av en fråga eller någon annan uppsättning av noder. Uppsättningen av noder som ska itereras bestäms av -implementeringen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator-implementering för dokument-order genomgång av ett dokumentunderträd. Förekomster av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | TreeWalker-objekt används för att navigera i ett dokumentträd eller underträd med hjälp av vyn av dokumentet som definieras av deras whatToShow-flaggor och filter (om några). Alla funktioner som utför navigering med en TreeWalker kommer automatiskt att stödja alla vyer som definieras av en TreeWalker. |


