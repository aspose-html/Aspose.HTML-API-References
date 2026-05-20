---
title: "Node.AppendChild"
second_title: "Aspose.HTML för Java API-referens"
description: "Node‑metod. Metoden appendChild i Node‑gränssnittet lägger till en nod i slutet av listan med barn till en angiven föräldranod. Om det angivna barnet är en referens till en befintlig nod i dokumentet, flyttar appendChild den från sin nuvarande position till den nya positionen; det krävs ingen borttagning av noden från dess föräldranod innan den läggs till i någon annan nod."
type: docs

url: /sv/java/com.aspose.html.dom/node/appendchild/
---
## Node.AppendChild method

appendChild()-metoden i Node-gränssnittet lägger till en nod i slutet av listan med barn till en angiven föräldranod. Om det givna barnet är en referens till en befintlig nod i dokumentet, flyttar appendChild() den från sin nuvarande position till den nya positionen (det krävs inte att noden tas bort från sin föräldranod innan den läggs till i någon annan nod).

Detta innebär att en nod inte kan finnas på två ställen i dokumentet samtidigt. Så om noden redan har en förälder tas den först bort och läggs sedan till på den nya positionen. Metoden [`Node.cloneNode()`](../clonenode/) kan användas för att skapa en kopia av noden innan den läggs till under den nya föräldern. Kopior som görs med [`cloneNode`](../clonenode/) hålls inte automatiskt synkroniserade.

```java
public Node AppendChild(Node node)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nod | Node | Noden som ska läggas till i den angivna föräldranoden (vanligtvis ett element). |

### Returvärde

En Node som är det tillagda barnet (aChild), förutom när aChild är ett [`DocumentFragment`](../../documentfragment/), i så fall returneras det tomma [`DocumentFragment`](../../documentfragment/).

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../domexception/) | Kastas när DOM-trädets begränsningar bryts. |

### Se även

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
