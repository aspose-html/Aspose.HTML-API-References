---
title: "INodeIterator.NextNode"
second_title: "Aspose.HTML för Java API-referens"
description: "INodeIterator-metod. Returnerar nästa nod i uppsättningen och avancerar iteratorns position i uppsättningen. Efter att en NodeIterator har skapats returnerar det första anropet till nextNode den första noden i uppsättningen."
type: docs

url: /sv/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Returnerar nästa nod i mängden och avancerar iteratorns position i mängden. Efter att en NodeIterator har skapats returnerar det första anropet till nextNode() den första noden i mängden.

```java
public Node NextNode()
```

### Returvärde

Den nästa noden i den uppsättning som itereras över, eller null om det inte finns fler medlemmar i den uppsättningen.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: Kastad om denna metod anropas efter att detach‑metoden har anropats. |

### Se även

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
