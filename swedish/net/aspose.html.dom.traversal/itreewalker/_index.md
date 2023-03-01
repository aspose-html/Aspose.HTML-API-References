---
title: Interface ITreeWalker
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Traversal.ITreeWalker gränssnitt. TreeWalkerobjekt används för att navigera i ett dokumentträd eller underträd med hjälp av vyn av dokumentet som definieras av deras whatToShowflaggor och filter om några. Alla funktioner som utför navigering med en TreeWalker kommer automatiskt att stödja alla vyer som definieras av en TreeWalker.
type: docs
weight: 2520
url: /sv/net/aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker-objekt används för att navigera i ett dokumentträd eller underträd med hjälp av vyn av dokumentet som definieras av deras whatToShow-flaggor och filter (om några). Alla funktioner som utför navigering med en TreeWalker kommer automatiskt att stödja alla vyer som definieras av en TreeWalker.

Att utelämna noder från den logiska vyn av ett underträd kan resultera i en -struktur som skiljer sig väsentligt från samma underträd i det fullständiga, ofiltrerade dokumentet . Noder som är syskon i TreeWalker-vyn kan vara barn till olika, vitt separerade noder i den ursprungliga vyn. Tänk till exempel ett NodeFilter som hoppar över alla noder utom textnoder och rotnoden för ett dokument. I den logiska vy som resulterar kommer alla textnoder att vara syskon och visas som direkta barn till rotnoden, oavsett hur djupt kapslad strukturen i originaldokumentet är.

Se även[Dokumentobjekt Modell (DOM) Nivå 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sedan DOM nivå 2

```csharp
public interface ITreeWalker : ITraversal
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CurrentNode](../../aspose.html.dom.traversal/itreewalker/currentnode/) { get; set; } | Noden där TreeWalker för närvarande är placerad. Ändringar av DOM-trädet kan göra att den aktuella noden inte längre accepteras av TreeWalkers associerade filter. currentNode kan också uttryckligen ställas in på vilken nod som helst, eller inte inom underträdet som anges av rotnoden eller skulle accepteras av filtret och whatToShow-flaggor. Ytterligare korsning sker i förhållande till currentNode även om den inte är en del av den aktuella vyn, genom att applicera filtren i den begärda riktningen; om ingen traversal är möjlig ändras inte aktuellNode. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [FirstChild](../../aspose.html.dom.traversal/itreewalker/firstchild/)() | Flyttar TreeWalker till den första synliga underordnade av den nuvarande noden och returnerar den nya noden. Om den aktuella noden har no synliga barn, returnerar null och behåller noden current . |
| [LastChild](../../aspose.html.dom.traversal/itreewalker/lastchild/)() | Flyttar TreeWalker till den sista synliga underordnade av den nuvarande noden och returnerar den nya noden. Om den aktuella noden har no synliga barn, returnerar null och behåller noden current . |
| [NextNode](../../aspose.html.dom.traversal/itreewalker/nextnode/)() | Flyttar TreeWalker till nästa synliga nod i document ordning i förhållande till den aktuella noden och returnerar den nya noden. Om den nuvarande noden inte har någon nästa nod, eller om sökningen efter nextNode försöker att kliva uppåt från TreeWalkers root nod, returnerar null och behåller den nuvarande noden. |
| [NextSibling](../../aspose.html.dom.traversal/itreewalker/nextsibling/)() | Flyttar TreeWalker till nästa syskon till noden current och returnerar den nya noden. Om den aktuella noden inte har någon visible nästa syskon, returnerar null och behåller den nuvarande noden. |
| [ParentNode](../../aspose.html.dom.traversal/itreewalker/parentnode/)() | Flyttar till och returnerar den närmast synliga förfadernoden för noden current . Om sökningen efter parentNode försöker stega uppåt från TreeWalkers rotnod, eller om den inte lyckas hitta en synlig förfadernod, behåller denna metod den nuvarande positionen och returnerar null. |
| [PreviousNode](../../aspose.html.dom.traversal/itreewalker/previousnode/)() | Flyttar TreeWalker till föregående synliga nod i dokumentordning i förhållande till den aktuella noden och returnerar noden new . Om den aktuella noden inte har någon tidigare nod, eller om sökningen efter previousNode försöker kliva uppåt från TreeWalkers rotnod, returnerar null och behåller den nuvarande noden. |
| [PreviousSibling](../../aspose.html.dom.traversal/itreewalker/previoussibling/)() | Flyttar TreeWalker till föregående syskon till den nuvarande noden och returnerar den nya noden. Om den nuvarande noden har no synlig tidigare syskon, returnerar null och behåller nuvarande nod. |

### Se även

* interface [ITraversal](../itraversal/)
* namnutrymme [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* hopsättning [Aspose.HTML](../../)


