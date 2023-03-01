---
title: ITreeWalker.CurrentNode
second_title: Aspose.HTML för .NET API Referens
description: ITreeWalker fast egendom. Noden där TreeWalker för närvarande är placerad. Ändringar av DOMträdet kan göra att den aktuella noden inte längre accepteras av TreeWalkers associerade filter. currentNode kan också uttryckligen ställas in på vilken nod som helst eller inte inom underträdet som anges av rotnoden eller skulle accepteras av filtret och whatToShowflaggor. Ytterligare korsning sker i förhållande till currentNode även om den inte är en del av den aktuella vyn genom att applicera filtren i den begärda riktningen om ingen traversal är möjlig ändras inte aktuellNode.
type: docs
weight: 10
url: /sv/net/aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Noden där TreeWalker för närvarande är placerad. Ändringar av DOM-trädet kan göra att den aktuella noden inte längre accepteras av TreeWalkers associerade filter. currentNode kan också uttryckligen ställas in på vilken nod som helst, eller inte inom underträdet som anges av rotnoden eller skulle accepteras av filtret och whatToShow-flaggor. Ytterligare korsning sker i förhållande till currentNode även om den inte är en del av den aktuella vyn, genom att applicera filtren i den begärda riktningen; om ingen traversal är möjlig ändras inte aktuellNode.

```csharp
public Node CurrentNode { get; set; }
```

### Fastighetsvärde

Den aktuella noden.

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Ökas om ett försök görs att sätta currentNode till null. |

### Se även

* class [Node](../../../aspose.html.dom/node/)
* interface [ITreeWalker](../)
* namnutrymme [Aspose.Html.Dom.Traversal](../../itreewalker/)
* hopsättning [Aspose.HTML](../../../)


