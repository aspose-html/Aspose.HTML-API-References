---
title: "Node.InsertBefore"
second_title: "Aspose.HTML för Java API-referens"
description: "Node‑metod. insertBefore‑metoden i Node‑gränssnittet infogar en nod före en referensnod som ett barn till en specificerad föräldranod."
type: docs

url: /sv/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

insertBefore()-metoden i Node-gränssnittet infogar en nod före en referensnod som ett barn till en specificerad föräldranod.

Om den angivna noden redan finns i dokumentet, flyttar insertBefore() den från sin nuvarande position till den nya positionen. (Det vill säga, den tas automatiskt bort från sin befintliga förälder innan den läggs till i den specificerade nya föräldern.)

Detta innebär att en nod inte kan finnas på två platser i dokumentet samtidigt.

```java
public Node InsertBefore(Node node, Node child)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nod | Node | Noden som ska infogas. |
| barn | Node | Noden före vilken newNode infogas. Om detta är null infogas newNode i slutet av nodens barnnoder. |

### Returvärde

Returnerar det tillagda barnet (såvida inte newNode är ett [`DocumentFragment`](../../documentfragment/), i så fall returneras det tomma [`DocumentFragment`](../../documentfragment/)).

### Se även

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
