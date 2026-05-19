---
title: "INodeIterator.NextNode"
second_title: "Aspose.HTML voor Java API-referentie"
description: "INodeIterator method. Retourneert de volgende knoop in de set en verschuift de positie van de iterator in de set. Nadat een NodeIterator is gemaakt, retourneert de eerste aanroep van nextNode de eerste knoop in de set"
type: docs

url: /nl/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Retourneert het volgende knooppunt in de set en verschuift de positie van de iterator in de set. Na het aanmaken van een NodeIterator, retourneert de eerste aanroep van nextNode() het eerste knooppunt in de set.

```java
public Node NextNode()
```

### Retourwaarde

De volgende Node in de set die wordt doorlopen, of null als er geen leden meer in die set zijn.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: Opgeworpen als deze methode wordt aangeroepen nadat de detach-methode is uitgevoerd. |

### Zie ook

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
