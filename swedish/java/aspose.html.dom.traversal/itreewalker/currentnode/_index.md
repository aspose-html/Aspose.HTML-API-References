---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.HTML för Java API-referens"
description: "ITreeWalker egenskap. Noden där TreeWalker för närvarande är positionerad. Ändringar i DOM‑trädet kan göra att den aktuella noden inte längre accepteras av TreeWalkers associerade filter. currentNode kan också explicit sättas till vilken nod som helst, oavsett om den ligger inom det delträd som angavs av rot‑noden eller skulle accepteras av filtret och whatToShow‑flaggorna. Ytterligare traversering sker relativt till currentNode även om den inte är en del av den aktuella vyn genom att tillämpa filtren i den begärda riktningen; om ingen traversering är möjlig förändras inte currentNode."
type: docs

url: /sv/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Noden där TreeWalker för närvarande är positionerad. Ändringar i DOM‑trädet kan göra att den aktuella noden inte längre accepteras av TreeWalkers associerade filter. currentNode kan också explicit sättas till vilken nod som helst, oavsett om den ligger inom det delträd som angavs av rot‑noden eller skulle accepteras av filtret och whatToShow‑flaggorna. Ytterligare traversering sker relativt till currentNode även om den inte är en del av den aktuella vyn, genom att tillämpa filtren i den begärda riktningen; om ingen traversering är möjlig, förändras inte currentNode.

```java
public Node CurrentNode { get; set; }
```

### Property Value

Den aktuella noden.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Uppstår om ett försök görs att sätta currentNode till null. |

### Se även

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
