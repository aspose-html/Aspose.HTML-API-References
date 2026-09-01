---
title: "com.aspose.html.dom.traversal"
second_title: "Aspose.HTML för Java API-referens"
description: "Paketet com.aspose.html.dom.traversal innehåller metoder som skapar iteratorer och träd‑vandringar för att navigera mellan element och traversera en nod och dess barn i dokumentordning."
type: docs

url: /sv/java/com.aspose.html.dom.traversal/
---
Paketet **com.aspose.html.dom.traversal** innehåller metoder som skapar iteratorer och träd‑walkers för att navigera mellan element och traversera en nod och dess barn i dokumentordning.

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal innehåller metoder som skapar iteratorer och träd‑vandringar för att traversera en nod och dess barn i dokumentordning (djup‑först, pre‑order traversal, vilket är motsvarande den ordning i vilken starttaggarna förekommer i dokumentets textrepresentation). I DOM‑er som stödjer Traversal‑funktionen kommer DocumentTraversal att implementeras av samma objekt som implementerar Document‑gränssnittet. |
| [IElementTraversal](./ielementtraversal/) | ElementTraversal‑gränssnittet är en uppsättning skrivskyddade attribut som låter en författare enkelt navigera mellan element i ett dokument. I konforme implementationer av Element Traversal måste alla objekt som implementerar Element också implementera ElementTraversal‑gränssnittet. |
| [INodeFilter](./inodefilter/) | Filter är objekt som vet hur man filtrerar bort noder. Om en NodeIterator eller TreeWalker får ett NodeFilter appliceras filtret innan nästa nod returneras. Om filtret godkänner noden returneras den av traversallogiken; annars letar traversalen efter nästa nod och låtsas att den avvisade noden inte fanns. |
| [INodeIterator](./inodeiterator/) | Iteratorer används för att gå igenom en uppsättning noder, t.ex. uppsättningen noder i en NodeList, dokumentets underträd som styrs av en specifik Node, resultatet av en fråga eller någon annan noduppsättning. Vilka noder som ska itereras bestäms av implementationen av NodeIterator. DOM nivå 2 specificerar en enda NodeIterator‑implementation för dokumentordningstraversal av ett dokumentunderträd. Instanser av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Iteratorer används för att gå igenom en uppsättning noder, t.ex. uppsättningen noder i en NodeList, dokumentets underträd som styrs av en specifik Node, resultatet av en fråga eller någon annan noduppsättning. Vilka noder som ska itereras bestäms av implementationen av NodeIterator. DOM nivå 2 specificerar en enda NodeIterator‑implementation för dokumentordningstraversal av ett dokumentunderträd. Instanser av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | TreeWalker‑objekt används för att navigera i ett dokumentträd eller underträd med hjälp av den vy av dokumentet som definieras av deras whatToShow‑flaggor och filter (om något). Alla funktioner som utför navigation med en TreeWalker kommer automatiskt att stödja vilken vy som helst som definieras av en TreeWalker. |
